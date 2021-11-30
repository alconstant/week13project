
In the last 7 days, how many unique visitors were located in India?
- 243

In the last 24 hours, of the visitors from China, how many were using Mac OSX?
- 9

In the last 2 days, what percentage of visitors received 404 errors? How about 503 errors?
- 404 errors: 40% 
- 503 errors: 60%

In the last 7 days, what country produced the majority of the traffic on the website?
- China

Of the traffic that's coming from that country, what time of day had the highest amount of activity?
- 1PM

List all the types of downloaded files that have been identified for the last 7 days, along with a short description of each file type (use Google if you aren't sure about a particular file type).
- GZ (gzip): archive compressed using gzip
- DEB: debian software package file 
- CSS (cascading style sheets): files that describe how html is displayed on the screen.
- ZIP: compressed file to take up less storage
- RPM(Red Hat Package Manager): file used to store installation packages for Linux.


Now that you have a feel for the data, Let's dive a bit deeper. Look at the chart that shows Unique Visitors Vs. Average Bytes.

Locate the time frame in the last 7 days with the most amount of bytes (activity).
In your own words, is there anything that seems potentially strange about this activity?
One visitor downloaded a large amount of bytes in a short time frame.


Filter the data by this event.

What is the timestamp for this event? Nov 21 21:57:00
What kind of file was downloaded? rpm
From what country did this activity originate? India
What HTTP response codes were encountered by this visitor? 200



Switch to the Kibana Discover page to see more details about this activity.

What is the source IP address of this activity? 35.143.166.159
What are the geo coordinates of this activity? { "lat": 43.34121, "lon": -73.6103075 } 
What OS was the source machine running? WIN 8
What is the full URL that was accessed? https://artifacts.elastic.co/downloads/beats/metricbeat/metricbeat-6.3.2-i686.rpm
From what website did the visitor's traffic originate? http://facebook.com/success/jay-c-buckey



Finish your investigation with a short overview of your insights.

What do you think the user was doing? It looks like a Linux package was attempting to be downloaded.
Was the file they downloaded malicious? If not, what is the file used for? No, the file is used to download metricbeat to get metrics of an operating system
Is there anything that seems suspicious about this activity? It seems suspicious that the traffic began on facebook because that is not typically a place you see metricbeat links.
Is any of the traffic you inspected potentially outside of compliance guidlines? Since this is not usually a link you would find on facebook it would be worth monitoring just in case. 