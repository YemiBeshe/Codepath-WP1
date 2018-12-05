
# WordPress codepath week seven 
Presentation on week7

EXPOIT 1:- 
Vulnerabilty CVE-2015-3440
WP version: 4.2
Remediation; Update to version: 4.7.5
Steps to exploit 
1. creat some post on the blog and logout .
1. visit the blog as aregular user 
1. let go to the post and add a comment, and your coment shloud include xss <svg/onload-alert('XSS')>
1. Then view page source to confirm code was injected  
