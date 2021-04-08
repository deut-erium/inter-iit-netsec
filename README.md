# Inter-IIT 9.0 
Solutions of IITB for [SAPTANG's netsec challenge](https://interiit-tech.org/events/network_security_hackathon) for Inter IIT tech meet 9.0

# Problem Statements
## [1. CVE-2014-0226 (100 points)](1_CVE-2014-0226)
### Bug Overview: 
Race condition in the mod_status module in the Apache HTTP Server before 2.4.10 allows remote attackers to cause a denial of service (heap-based buffer overflow), or possibly obtain sensitive credential information or execute arbitrary code, via a crafted request that triggers improper scoreboard handling within the status_handler function in modules/generators/mod_status.c and the lua_ap_scoreboard_worker function in modules/lua/lua_request.c.
- Aim: Write a working exploit for this CVE.
- Install vulnerable service in a VM/Docker and ensure to meet the condition so that you can exploit it.
- Run your exploit on the vulnerable service and make a video of it.
- Write a brief report about this bug including your exploit code and link for exploit and Video proof.


## [2. CVE-2017-12615 (100 points)](2_CVE-2017-12615)
### Bug Overview: 
When running Apache Tomcat 7.0.0 to 7.0.79 on Windows with HTTP PUTs enabled (e.g. via setting the read-only initialisation parameter of the Default to false) it was possible to upload a JSP file to the server via a specially crafted request. This JSP could then be requested and any code it contained would be executed by the server. That could lead to remote code execution on the server.
- Aim: Write a working exploit for this CVE by which you can achieve RCE on local VM/Docker.
- Install vulnerable service in a VM/Docker and ensure to meet the condition so that you can exploit it.
- Run your exploit on the vulnerable service and make a video of it.
- Write a brief report about this bug including your exploit code and link for exploit and Video proof.


## [3. CVE-2020-0609 and CVE-2020-0610 (200 points)](3_CVE-2020-0609_CVE-2020-0610)
### Bug Overview: 
Specially crafted requests lead to DoS/RCE without any user interaction on Windows RDP service.
- Aim: Setup a local Vm in which to install vulnerable windows RDP service and write an exploit that could lead to DoS/RCE on the local VM server.
- Write a brief report about this bug including your exploit code and link for exploit and Video proof.


## [4. CVE-2018-1335 (100 points)](4_CVE-2018-1335)
### Bug Overview: 
This bug leads to command injection vulnerability in Apache Tika -server
1.18 and uses Cscript.exe to execute Jscript or VBS code and run arbitrary commands.
- Aim: Write a working exploit for this CVE by which you can achieve RCE on the local VM.
- Install vulnerable service in a VM and ensure to meet the condition so that you can exploit it.
- Run your exploit on the vulnerable service and make a video of it.
- Write a brief report about this bug including your exploit code and link for exploit and Video proof.

## [5. CVE-2019-0232 (100 points)](5_CVE-2019-0232)
### Bug Overview: 
Apache Tomcat has a vulnerability in the CGI Servlet which can be exploited to achieve remote code execution (RCE). This is only exploitable when running on Windows in a non-default configuration in conjunction with batch files.
- Aim: Write a working exploit by which you can achieve RCE on the local VM.
- Install vulnerable service in a VM and ensure to meet the condition so that you can exploit it.
- Run your exploit on the vulnerable service and make a video of it.
- Write a brief report about this bug including your exploit code and link for exploit and Video proof.

# Team
- Himanshu Sheoran [deut-erium](https://github.com/deut-erium)
- Lakshya Kumar [p0i5on8](https://github.com/p0i5on8)
- Sahil Jain [jsahil730](https://github.com/jsahil730)
- Ram Krishna Poricha [ramporicha-iitb](https://github.com/ramporicha-iitb)
- Sawan Goyal [goyalsawan](https://github.com/goyalsawan)
