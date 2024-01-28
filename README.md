# Tanish-26.github.io

### XSS Context

	- HTML Context
		trying with HTML tags to check if it reflects back or not
			tags to try for example:- <b> <h1> <img src=x>	,<iframe>
			lab:-
			https://labs.hackxpert.com/RXSS/GET/10.php  
	
	- HTML Comment
		escaping the comment tag ( <!--hello--> )
			tags to try for example:- (--><h1>, --<br>, --<img src=x>)
			lab:-
			https://labs.hackxpert.com/RXSS/GET/20.php	 
			 
	- HTML Tag Attribute
		trying different tags to escape the tag because there might be a different tag
		in the back end which we might not be able to see
			 tags to try for example:- ( ','',",>,/,\,-,;,:,),!)
			 lab:-
			 https://labs.hackxpert.com/RXSS/GET/30.php			 	
	
	- JS Injection
		 trying to javascript tags to inject or escape in this condition 
			tags to try for example:- (prompt(),alert()),
			lab:-
			https://labs.hackxpert.com/RXSS/GET/40.php
		 


---
### XSS based CTF's

```
https://tryhackme.com/room/md2pdf
https://infosecwriteups.com/md2pdf-tryhackme-walkthrough-writeup-242c4767de7e
https://tryhackme.com/room/marketplace
https://tryhackme.com/room/thatstheticket
```

---

### Reflected XSS Labs 

```
-----------------------------------------------------------------------------------------
APPRENTICE:-

https://portswigger.net/web-security/cross-site-scripting/reflected/lab-html-context-nothing-encoded
https://portswigger.net/web-security/cross-site-scripting/stored/lab-html-context-nothing-encoded
https://portswigger.net/web-security/cross-site-scripting/contexts/lab-attribute-angle-brackets-html-encoded
https://portswigger.net/web-security/cross-site-scripting/contexts/lab-javascript-string-angle-brackets-html-encoded
-----------------------------------------------------------------------------------------
PRACTITIONER:-

https://portswigger.net/web-security/cross-site-scripting/contexts/lab-html-context-with-most-tags-and-attributes-blocked
https://portswigger.net/web-security/cross-site-scripting/contexts/lab-html-context-with-all-standard-tags-blocked
https://portswigger.net/web-security/cross-site-scripting/contexts/lab-some-svg-markup-allowed
https://portswigger.net/web-security/cross-site-scripting/contexts/lab-canonical-link-tag
https://portswigger.net/web-security/cross-site-scripting/contexts/lab-javascript-string-single-quote-backslash-escaped
https://portswigger.net/web-security/cross-site-scripting/contexts/lab-javascript-string-angle-brackets-double-quotes-encoded-single-quotes-escaped
https://portswigger.net/web-security/cross-site-scripting/contexts/lab-javascript-template-literal-angle-brackets-single-double-quotes-backslash-backticks-escaped
https://portswigger.net/web-security/cross-site-scripting/exploiting/lab-stealing-cookies
-----------------------------------------------------------------------------------------
EXPERT:-

https://portswigger.net/web-security/cross-site-scripting/contexts/client-side-template-injection/lab-angular-sandbox-escape-without-strings
https://portswigger.net/web-security/cross-site-scripting/contexts/client-side-template-injection/lab-angular-sandbox-escape-and-csp
https://portswigger.net/web-security/cross-site-scripting/contexts/lab-event-handlers-and-href-attributes-blocked
https://portswigger.net/web-security/cross-site-scripting/contexts/lab-javascript-url-some-characters-blocked
https://portswigger.net/web-security/cross-site-scripting/content-security-policy/lab-very-strict-csp-with-dangling-markup-attack
https://portswigger.net/web-security/cross-site-scripting/content-security-policy/lab-csp-bypass
```

| lab | type | Complete |
| ---- | ---- | ---- |
| https://portswigger.net/web-security/cross-site-scripting/reflected/lab-html-context-nothing-encoded | APPRENTICE | <input type="checkbox" unchecked> |
| https://portswigger.net/web-security/cross-site-scripting/stored/lab-html-context-nothing-encoded | APPRENTICE | <input type="checkbox" unchecked> |
| https://portswigger.net/web-security/cross-site-scripting/contexts/lab-attribute-angle-brackets-html-encoded | APPRENTICE | <input type="checkbox" unchecked> |
| https://portswigger.net/web-security/cross-site-scripting/contexts/lab-javascript-string-angle-brackets-html-encoded | APPRENTICE | <input type="checkbox" unchecked> |
| https://portswigger.net/web-security/cross-site-scripting/contexts/lab-html-context-with-most-tags-and-attributes-blocked | PRACTITIONER | <input type="checkbox" unchecked> |
| https://portswigger.net/web-security/cross-site-scripting/contexts/lab-html-context-with-all-standard-tags-blocked | PRACTITIONER | <input type="checkbox" unchecked> |
| https://portswigger.net/web-security/cross-site-scripting/contexts/lab-some-svg-markup-allowed | PRACTITIONER | <input type="checkbox" unchecked> |
| https://portswigger.net/web-security/cross-site-scripting/contexts/lab-canonical-link-tag | PRACTITIONER | <input type="checkbox" unchecked> |
| https://portswigger.net/web-security/cross-site-scripting/contexts/lab-javascript-string-single-quote-backslash-escaped | PRACTITIONER | <input type="checkbox" unchecked> |
| https://portswigger.net/web-security/cross-site-scripting/contexts/lab-javascript-string-angle-brackets-double-quotes-encoded-single-quotes-escaped | PRACTITIONER | <input type="checkbox" unchecked> |
| https://portswigger.net/web-security/cross-site-scripting/contexts/lab-javascript-template-literal-angle-brackets-single-double-quotes-backslash-backticks-escaped | PRACTITIONER | <input type="checkbox" unchecked> |
| https://portswigger.net/web-security/cross-site-scripting/exploiting/lab-stealing-cookies | PRACTITIONER | <input type="checkbox" unchecked> |
| https://portswigger.net/web-security/cross-site-scripting/contexts/client-side-template-injection/lab-angular-sandbox-escape-without-strings | EXPERT | <input type="checkbox" unchecked> |
| https://portswigger.net/web-security/cross-site-scripting/contexts/client-side-template-injection/lab-angular-sandbox-escape-and-csp | EXPERT | <input type="checkbox" unchecked> |
| https://portswigger.net/web-security/cross-site-scripting/contexts/lab-event-handlers-and-href-attributes-blocked | EXPERT | <input type="checkbox" unchecked> |
| https://portswigger.net/web-security/cross-site-scripting/contexts/lab-javascript-url-some-characters-blocked | EXPERT | <input type="checkbox" unchecked> |
| https://portswigger.net/web-security/cross-site-scripting/content-security-policy/lab-very-strict-csp-with-dangling-markup-attack | EXPERT | <input type="checkbox" unchecked> |
| https://portswigger.net/web-security/cross-site-scripting/content-security-policy/lab-csp-bypass | EXPERT | <input type="checkbox" unchecked> |
