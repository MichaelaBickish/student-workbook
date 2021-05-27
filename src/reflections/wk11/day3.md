# Week 11 | Day 3 Daily Journal

Afternoon Project: 

Read Dotnet WebAPI's > SQL Injection, and answer the following questions

## *What is SQL injection?*
a type of attack that can give an adversary complete control over your web application database by inserting arbitrary SQL code into a database query.

## *What are 3 methods SQL injection can be done by?*
1. Through user input like on a form.
2. Modified cookies from malware that are loaded by the app 
3. Server variables such as HTTP headers can also be used as a SQL injection attack vector.

## *How can we detect and sanitize SQL injection attacks?*
When writing your requests in the back end, use prepared statements with parameterized queries.
A web application firewall (WAF) can detect and block basic SQL injection attacks.
Intrusion detection systems (IDS), both network- and host-based, can be tuned to detect SQL injection attacks. Network-based IDSes can monitor all connections to your database server, and flag suspicious activity. A host-based IDS can monitor web server logs and alert when something strange happens.

