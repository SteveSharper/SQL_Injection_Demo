# SQL_Injection_Demo
This lab report (not actual program) demonstrates the dangers of SQL Injection attacks on a sample website and how it can be prevented. Due to a common error in the way database logins are programmed, the user is able to input a query of their own which could render anything from one single record to an entire record exposed. To avoid this and protect the privacy of your database's data, it is important to program db-using sites with prepared statements instead of allowing the user t enter directly into the query.

This lab exercise was done using a Virtual Machine running Ubuntu, and the makeshift site made specifically to simulate the attack is seedlabsqlinjection.com, a site that can only be viewed through the VM browser.
