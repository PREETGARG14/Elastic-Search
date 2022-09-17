### Easy Method 
___
Cloud setup for 14 day free trail - <a href="https://www.elastic.co/cloud/cloud-trial-overview?medium=email&campaign=marketo-fallback">Elastic Cloud Trail<a/>
<img src="images/1.png">
  Steps -
  * Login /Signup on above website.
  * Verify Email
  * Set password
  * You redirected to Elastic cloud console
  * Click on start free trail
  * Select Elastic Stack <img src="images/2.png">
  * Select hardware profile as default one <img src="images/3.png">
  * Make Deployment settings as same/default 
  * You get ES deployment creds - download them as they visible only once 
  * Your ES configured now <img src="images/4.png">
  * You can open Kibana dashboard too with sample data.
  
### Traditional Method 
___
**Download ES** - <a href="https://www.elastic.co/downloads/elasticsearch">Elastic Download Page<a/>
<img src="images/5.png">
  
**Download Kibana** - <a href="https://www.elastic.co/downloads/kibana">Kibana Download Page<a/>
<img src="images/5.png"> 
  Steps -<br/>
  Once it get installed 
  * Check Elasticsearch version - <br/>1. sudo service elasticsearch start<br/>
                                  2. sudo service elasticsearch status<br/>
                                  3. curl http://localhost:9200 -to check ES version<br/>
                                  4. or cd /usr/share/elasticsearch <br/>
                                  5. sudo ./bin/elasticsearch --version<br/>
  * Check Kibana version - <br/>1. sudo service kibana start<br/>
                                  2. sudo service kibana status<br/>
                                  3. curl http://localhost:5601 -to check kibana version<br/>
                                  4. or cd /usr/share/kibana <br/>
                                  5. ./bin/kibana --version<br/>
  
