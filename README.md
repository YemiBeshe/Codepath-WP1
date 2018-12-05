
# WordPress codepath week seven 
Presentation on week7

EXPOIT 1:- 
Vulnerabilty CVE-2015-3440
WP version: 4.2
Remediation; Update to version: 4.7.5
Steps to exploit 
1. creat some post on the blog and logout .
1. visit the blog 
1. let go to the post and add a comment, and your coment shloud include xss <svg/onload-alert('XSS')>
<img src="https://github.com/YemiBeshe/Codepath-WP1/blob/master/Screen%20Shot%20WP%20comment%20XSS.png">
1. Then view page source to confirm code was injected  
<img src="https://github.com/YemiBeshe/Codepath-WP1/blob/master/pop%20up%20on%20WP.png">

EXPOIT 2:-
Vulnerabilty CVE-2018-6389
WP version: 4.2
Remediation; Update to version: 4.9
Steps to exploit 
1. Download py script https://github.com/Quitten/doser.py
1. run py script on wp python doser.py -t 999 -g 'http://wpdistillery.vm'
in brower try to visit WPdistilery.vp 
page is inaccesable becaouse of DOS attack
