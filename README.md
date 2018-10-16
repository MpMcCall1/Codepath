# Codepath
Secure Software Engineering
WEEK 7
Vunerability 1:
Stored XXS Vunerability 
Wordpress version: 4.2
Inject java script into the comments and the script is triggered when the comment is viewed. <a title='x onmouseover=alert(unescape(/hello%20world/.source)) style=position:absolute;left:0;top:0;width:5000px;height:5000px  AAAAAAAAAAAA...[64 kb]..AAA'></a>
Vunerability 2:
WordPress 4.8.1
plugin: bbpress
Inject javascript as any user that can publish a post and then when another user previews or clicks on the post a popup where the malicious code could go is. 


