# HR Aids Consults coding challenge
===================================

## @author => KEHINDE Olamide 
## @email => olakehinde59@gmail.com

# Problem:
==========
• An application for billing 10,000 users over a given billing API (owned by a third
party e.g. Telco/Bank).
• The billing API takes 1.6secs to process and respond to each request
• The details of the users to bill is stored in a Database with fields; id, username, 
mobile_number and amount_to_bill

# Requirements:
===============
Write or describe a simple PHP code that will be able bill all the 10,000 users within 
1hr.
Also suggest an approach to scale the above if you need to bill 100,000 users within 
4.5hrs. 

# Description of Solution
=========================
This operation is a resource heavy request, so it is advisable to use stored procedures (or cron jobs) and functions. 
It will optimize the speed and time complexity to upto 40% (or more) speed in data searching and fetching records. 

Another option is to optimize the php code by reducing the use of loops.
