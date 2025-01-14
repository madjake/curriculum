---
author: lizTheDeveloper
type: normal
category: how to
links:
  - >-
    [OWASP Top
    Ten](https://www.owasp.org/images/7/72/OWASP_Top_10-2017_%28en%29.pdf.pdf){website}
  - >-
    [Testing for Reflected Cross site
    scripting](https://www.owasp.org/index.php/Testing_for_Reflected_Cross_site_scripting_(OTG-INPVAL-001)){website}
  - >-
    [Testing for Stored Cross site
    scripting](https://www.owasp.org/index.php/Testing_for_Stored_Cross_site_scripting_(OTG-INPVAL-002)){website}
  - >-
    [Testing for DOM-based Cross site
    scripting](https://www.owasp.org/index.php/Testing_for_DOM-based_Cross_site_scripting_(OTG-CLIENT-001)){website}
---

# Detect XSS Vulnerabilities


---

## Content

In order to review source code to establish whether or not your application is vulnerable to XSS attacks, ask yourself the following questions:

- Does my application *store unvalidated input*?
- Does my application *write unescaped user input to the page*?
- Does my application *write unescaped user input to another page*?
- Do all of my endpoints contain *server side validation*?

Bookmark this insight to receive links to OWASP testing guides for XSS that you can use on your own applications.


---

## Practice

Which of these will produce a vulnerability to XSS?
???

- Storing unvalidated input
- Using JSON
- Using web forms


---

## Revision

Which of these will produce a vulnerability to XSS?
???

- Writing unvalidated input to the page
- Allowing connections to your website from any IP address
- Accepting input from any IP address
 
