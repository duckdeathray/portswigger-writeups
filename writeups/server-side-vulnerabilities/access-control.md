Access Control
- who or what is authorized to perform actions or access to resources

1. Authentication -> is the user who they say they are
2. Session management -> identify what HTTP requests are being made by user
3. Access Control -> determine if user is allowed to carry out action

Vertical privilege escalation
- user gains access to functionality beyond what is permitted

Unprotected functionality
- occurs when protection is not enforced for sensitive functionality

**Lab: Unprotected Admin functionality**

Description: discover unprotected admin panel and delete user carlos

1. Try adding /robots.txt after the webpage as suggested in the previous example
2. A page shows up showing User: * and [Disalow] administrator-panel
3. Now replace the text after the website URL with /administrator-panel to gain access as admin
4. Delete the user carlos 
