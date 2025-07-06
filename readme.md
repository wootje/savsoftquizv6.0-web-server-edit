## Removed the need for docker. It's ready to upload to your web server.

Changes:
1. Removed Docker files
2. Added 'index.html' to the root directory that redirects you to the login page
3. Removed the need to manually enter your domain name in a file by setting relative paths:<br>
  File: '/application/dist/js/custom.js' <br>
» var api_base_url="/api/public/";<br>
» var api_site_url="/api/public/index.php"; <br>
  <i>(if you install in a sub folder, put the name of the folder before /api & add it to the 'index.html' file in the root directory)</i>
<br>
<br>

## Minimum Server Requirement
- PHP version 7.3 or newer is required
- tokenizer extension
- intl extension
- mysqli extension
- MySQL  version 5.1+

<br>
<br>
<b>Buy me a cup of coffee!</b> 🙂👍 <br>
https://urlshrt.eu/buycupofcoffee
<br>
<br>
<img src="https://urlshrt.eu/donateqr"></img>
<br>
<br>

## Useful links

Open Source Version Demo: https://savsoftquiz.org/demo/application/dist/index.html <br>
Admin Login:<br>
Username: admin<br>
Password: admin<br><br>


User/student Login:<br>
Username:  user007<br>
Password:  123456<br><br>

 


## Installation Instructions

1) Upload all files to the root directory of your web server.<br>
2) Open '/api/.env' <br>
3) Update the Base URL <br>
4) Update database credentials (update both database details, readDB and writeDB.) If you are using single database then use same credentials in both.<br>
5) Import database.sql file to both database (.sql file located in root folder of savsoftquizv6.0 )<br>
6) Open your web browser and go to the domain you host this software on.
7) Log in using the creadentials provided below: <br>
» username: admin<br>
» password:  admin<br>

If you have any issue to login then read instructions at https://github.com/Techkshetra/savsoftquizv6.0/wiki/First-time-login-troubleshoot 

<br>
<br>
# Wiki - Documentation
https://github.com/Techkshetra/savsoftquizv6.0/wiki<br><br>

 

# Found any issue or bug?
Raise issue at https://github.com/Techkshetra/savsoftquizv6.0/issues/<br><br><br>



# Do you need more features?<br>
Try our Enterprise version demo at https://savsoftquiz.com/



Recommended hosting https://bitbullhost.com

The MIT License

Copyright 2021 TechKshetra Info Solutions Pvt. Ltd

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:
The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

<br>
<img alt="GitHub all releases" src="https://img.shields.io/github/downloads/wootje/savsoftquiz_v5.1_php7-8/total">
