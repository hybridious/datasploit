[![ToolsWatch Best Tools](https://www.toolswatch.org/badges/toptools/2016.svg)](https://www.toolswatch.org/2013/12/2013-top-security-tools-as-voted-by-toolswatch-org-readers/)

[![Black Hat Arsenal](https://www.toolswatch.org/badges/arsenal/2016.svg)](https://www.blackhat.com/us-16/arsenal.html#datasploit)


# Overview of the tool:
* Performs OSINT on a domain / email / username / phone and find out information from different sources.
* Correlates and collaborate the results, show them in a consolidated manner. 
* Tries to find out credentials, api-keys, tokens, subdomains, domain history, legacy portals, etc. related to the target. 
* Use specific script / launch automated OSINT for consolidated data.
* Available in both GUI and Console.
 
## Basic Usage:
```

	  ____/ /____ _ / /_ ____ _ _____ ____   / /____  (_)/ /_
	  / __  // __ `// __// __ `// ___// __ \ / // __ \ / // __/
	 / /_/ // /_/ // /_ / /_/ /(__  )/ /_/ // // /_/ // // /_  
	 \__,_/ \__,_/ \__/ \__,_//____// .___//_/ \____//_/ \__/  
	                               /_/                        
						
         	   Open Source Assistant for #OSINT            
                 website: www.datasploit.info               
	
Usage: domainOsint.py [options]

Options:
  -h,	    	--help			    show this help message and exit
  -d DOMAIN,	--domain=DOMAIN		Domain name against which automated Osint 
                                    is to be performed.

```

# Required Setup:
* Bunch of python libraries (use requirements.txt)
* MongoDb, Django, Celery and RabbitMq (Refer to setup guide).


## Detailed Tool Documentation:
> [http://datasploit.readthedocs.io/en/latest/](http://datasploit.readthedocs.io/en/latest/)


