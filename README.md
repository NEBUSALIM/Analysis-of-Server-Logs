Exercise 2 : Analysis of Server Logs
Problem Statement : 
•	Check logs in the Logs.csv file and find the uptime of each host
Solution Abstract :
1.	Separate the log entries into instances where the server was running fine and not working fine. 
2.	Compare the time difference between these instances to find the maximum uptime of host.
Tools/Packages Used:
•	Datetime
•	Numpy
•	Pandas
Result :
1.	Successfully read the log files.
2.	Converted the log_time to dateTime format for further processing.
3.	Sorted the data based on log_time.
4.	Grouped the data based on ‘host’ so that the maximum uptime for each host can be calculated.
5.	Created two dataframes, one for the instances when the server was up and running and another when it was not up and running.
6.	Calculated the difference in log_time between these two dataframes to get the uptime for the host.
7.	The highest value from this is taken as the maximum uptime for the host.
8.	Refer appendix for final results
Future Scope :
1.	We can predict future failures provided we have data on network traffic, server load, performance matrix etc.
