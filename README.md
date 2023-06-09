# WSA LABS TOPICS

## SQL Injection

- SQL injection vulnerability in WHERE clause allowing retrieval of hidden data
- SQL injection vulnerability allowing login bypass
- SQL injection UNION attack, determining the number of columns returned by the query
- SQL injection UNION attack, finding a column containing text
- SQL injection UNION attack, retrieving data from other tables
- SQL injection UNION attack, retrieving multiple values in a single column
- SQL injection attack, querying the database type and version on Oracle
- SQL injection attack, querying the database type and version on MySQL and Microsoft
- SQL injection attack, listing the database contents on non-Oracle databases
- SQL injection attack, listing the database contents on Oracle
- Blind SQL injection with conditional responses
- Blind SQL injection with conditional errors

## Cross-site scripting

- Reflected XSS into HTML context with nothing encoded
- Stored XSS into HTML context with nothing encoded
- DOM XSS in document.write sink using source location.search
- DOM XSS in innerHTML sink using source location.search
- DOM XSS in jQuery anchor href attribute sink using location.search source
- DOM XSS in jQuery selector sink using a hashchange event
- Reflected XSS into attribute with angle brackets HTML-encoded
- Stored XSS into anchor href attribute with double quotes HTML-encoded
- Reflected XSS into a JavaScript string with angle brackets HTML encoded
- DOM XSS in document.write sink using source location.search inside a select element
- DOM XSS in AngularJS expression with angle brackets and double quotes HTML-encoded
- Reflected DOM XSS
- Stored DOM XSS
- Exploiting cross-site scripting to steal cookies
- Exploiting cross-site scripting to capture passwords
- Exploiting XSS to perform CSRF
- Reflected XSS into HTML context with most tags and attributes blocked
- Reflected XSS into HTML context with all tags blocked except custom ones
- Reflected XSS with some SVG markup allowed
- Reflected XSS in canonical link tag
- Reflected XSS into a JavaScript string with single quote and backslash escaped
- Reflected XSS into a JavaScript string with angle brackets and double quotes HTML-encoded and single quotes escaped
- Stored XSS into onclick event with angle brackets and double quotes HTML-encoded and single quotes and backslash escaped
- Reflected XSS into a template literal with angle brackets, single, double quotes, backslash and backticks Unicode-escaped
- Reflected XSS with event handlers and href attributes blocked
- Reflected XSS in a JavaScript URL with some characters blocked
- Reflected XSS with AngularJS sandbox escape without strings
- Reflected XSS with AngularJS sandbox escape and CSP
- Reflected XSS protected by very strict CSP, with dangling markup attack
- Reflected XSS protected by CSP, with CSP bypass

## Cross-site request forgery (CSRF)

- CSRF vulnerability with no defenses
- CSRF where token validation depends on request method
- CSRF where token validation depends on token being present
- CSRF where token is not tied to user session
- CSRF where token is tied to non-session cookie
- CSRF where token is duplicated in cookie
- SameSite Lax bypass via method override
- SameSite Strict bypass via client-side redirect
- SameSite Strict bypass via sibling domain
- SameSite Lax bypass via cookie refresh
- CSRF where Referer validation depends on header being present
- CSRF with broken Referer validation

## Clickjacking

- Basic clickjacking with CSRF token protection
- Clickjacking with form input data prefilled from a URL parameter
- Clickjacking with a frame buster script
- Exploiting clickjacking vulnerability to trigger DOM-based XSS
- Multistep clickjacking

## DOM-based vulnerabilities

- DOM-based XSS with data retrieved from the URL hash
- DOM-based XSS with data retrieved from the URL query string
- DOM-based XSS with data retrieved from the document.referrer
- DOM-based XSS with data retrieved from an HTML attribute
- DOM-based XSS with data retrieved from JavaScript code execution
- DOM-based XSS with data retrieved from user input
- DOM-based XSS with data retrieved from an Ajax response
- DOM-based XSS with data retrieved from a server-side template
- DOM-based XSS with data retrieved from a WebSocket message
- DOM-based XSS with data retrieved from localStorage
- DOM-based XSS with data retrieved from sessionStorage
- DOM-based XSS with data retrieved from cookies
- DOM-based XSS with data retrieved from document.write
- DOM-based XSS with data retrieved from document.writeln
- DOM-based XSS with data retrieved from document.write inside an iframe
- DOM-based XSS with data retrieved from document.writeln inside an iframe
- DOM-based XSS with data retrieved from document.write in a nested iframe
- DOM-based XSS with data retrieved from document.writeln in a nested iframe
- DOM-based XSS with data retrieved from document.open/document.write
- DOM-based XSS with data retrieved from document.open/document.write inside an iframe
- DOM-based XSS with data retrieved from document.open/document.writeln
- DOM-based XSS with data retrieved from document.open/document.writeln inside an iframe
- DOM-based XSS with data retrieved from dynamically created script tags
- DOM-based XSS with data retrieved from dynamically created script tags inside an iframe
- DOM-based XSS with data retrieved from dynamically created script tags using document.write
- DOM-based XSS with data retrieved from dynamically created script tags using document.writeln
- DOM-based XSS with data retrieved from dynamically created script tags using document.open/document.write
- DOM-based XSS with data retrieved from dynamically created script tags using document.open/document.writeln
- DOM-based XSS with data retrieved from dynamically created script tags inside an iframe using document.write
- DOM-based XSS with data retrieved from dynamically created script tags inside an iframe using document.writeln
- DOM-based XSS with data retrieved from dynamically created script tags inside an iframe using document.open/document.write
- DOM-based XSS with data retrieved from dynamically created script tags inside an iframe using document.open/document.writeln
- DOM-based XSS with data retrieved from iframe.contentDocument
- DOM-based XSS with data retrieved from window.frames[i]
- DOM-based XSS with data retrieved from window.opener
- DOM-based XSS with data retrieved from window.parent
- DOM-based XSS with data retrieved from window.top
- DOM-based XSS with data retrieved from window.self
- DOM-based XSS with data retrieved from window.globalStorage
- DOM-based XSS with data retrieved from window.sessionStorage
- DOM-based XSS with data retrieved from window.localStorage
- DOM-based XSS with data retrieved from window.location
- DOM-based XSS with data retrieved from window.document
- DOM-based XSS with data retrieved from window
- DOM-based XSS with data retrieved from self
- DOM-based XSS with data retrieved from location
- DOM-based XSS with data retrieved from document
- DOM-based XSS with data retrieved from document.all
- DOM-based XSS with data retrieved from document.documentElement
- DOM-based XSS with data retrieved from document.body
- DOM-based XSS with data retrieved from document.head
- DOM-based XSS with data retrieved from document.images
- DOM-based XSS with data retrieved from document.links
- DOM-based XSS with data retrieved from document.forms
- DOM-based XSS with data retrieved from document.embeds
- DOM-based XSS with data retrieved from document.plugins
- DOM-based XSS with data retrieved from document.scripts
- DOM-based XSS with data retrieved from document.applets
- DOM-based XSS with data retrieved from document.window
- DOM-based XSS with data retrieved from document.location
- DOM-based XSS with data retrieved from document.baseURI
- DOM-based XSS with data retrieved from document.cookie
- DOM-based XSS with data retrieved from document.title
- DOM-based XSS with data retrieved from document.domain
- DOM-based XSS with data retrieved from document.referrer
- DOM-based XSS with data retrieved from document.lastModified
- DOM-based XSS with data retrieved from document.readyState
- DOM-based XSS with data retrieved from document.designMode
- DOM-based XSS with data retrieved from document.implementation
- DOM-based XSS with data retrieved from document.doctype
- DOM-based XSS with data retrieved from document.XMLDocument
- DOM-based XSS with data retrieved from document.createDocumentFragment
- DOM-based XSS with data retrieved from document.createElement
- DOM-based XSS with data retrieved from document.createTextNode
- DOM-based XSS with data retrieved from document.createComment
- DOM-based XSS with data retrieved from document.createProcessingInstruction
- DOM-based XSS with data retrieved from document.createAttribute
- DOM-based XSS with data retrieved from document.createEntityReference
- DOM-based XSS with data retrieved from document.getElementsByTagName
- DOM-based XSS with data retrieved from document.getElementsByName
- DOM-based XSS with data retrieved from document.getElementById
- DOM-based XSS with data retrieved from document.getElementsByClassName
- DOM-based XSS with data retrieved from document.querySelector
- DOM-based XSS with data retrieved from document.querySelectorAll
- DOM-based XSS with data retrieved from document.getElementsByTagNameNS
- DOM-based XSS with data retrieved from document.importNode
- DOM-based XSS with data retrieved from document.adoptNode
- DOM-based XSS with data retrieved from document.createRange
- DOM-based XSS with data retrieved from document.createNodeIterator
- DOM-based XSS with data retrieved from document.createTreeWalker
- DOM-based XSS with data retrieved from document.documentElement.outerHTML
- DOM-based XSS with data retrieved from document.documentElement.innerHTML
- DOM-based XSS with data retrieved from document.documentElement.textContent
- DOM-based XSS with data retrieved from document.documentElement.innerText
- DOM-based XSS with data retrieved from document.documentElement.outerText
- DOM-based XSS with data retrieved from document.documentElement.insertAdjacentHTML
- DOM-based XSS with data retrieved from document.documentElement.createContextualFragment
- DOM-based XSS with data retrieved from document.documentElement.write
- DOM-based XSS with data retrieved from document.documentElement.writeln
- DOM-based XSS with data retrieved from document.documentElement.insertAdjacentText
- DOM-based XSS with data retrieved from document.documentElement.textContent.setter
- DOM-based XSS with data retrieved from document.documentElement.innerText.setter
- DOM-based XSS with data retrieved from document.documentElement.outerText.setter
- DOM-based XSS with data retrieved from document.documentElement.outerHTML.setter
- DOM-based XSS with data retrieved from document.documentElement.innerHTML.setter
- DOM-based XSS with data retrieved from document.documentElement.outerText.getter
- DOM-based XSS with data retrieved from document.documentElement.textContent.getter
- DOM-based XSS with data retrieved from document.documentElement.innerText.getter
- DOM-based XSS with data retrieved from document.documentElement.outerHTML.getter
- DOM-based XSS with data retrieved from document.documentElement.innerHTML.getter
- DOM-based XSS with data retrieved from document.documentElement.attributes.getNamedItem
- DOM-based XSS with data retrieved from document.documentElement.attributes.getNamedItemNS
- DOM-based XSS with data retrieved from document.documentElement.attributes.removeNamedItem
- DOM-based XSS with data retrieved from document.documentElement.attributes.removeNamedItemNS
- DOM-based XSS with data retrieved from document.documentElement.attributes.setNamedItem
- DOM-based XSS with data retrieved from document.documentElement.attributes.setNamedItemNS
- DOM-based XSS with data retrieved from document.documentElement.attributes.item
- DOM-based XSS with data retrieved from document.documentElement.attributes.namedItem
- DOM-based XSS with data retrieved from document.documentElement.attributes.get
- DOM-based XSS with data retrieved from document.documentElement.attributes.set
- DOM-based XSS with data retrieved from document.documentElement.attributes.has
- DOM-based XSS with data retrieved from document.documentElement.attributes.removeAttribute
- DOM-based XSS with data retrieved from document.documentElement.attributes.removeAttributeNS
- DOM-based XSS with data retrieved from document.documentElement.attributes.getAttribute
- DOM-based XSS with data retrieved from document.documentElement.attributes.getAttributeNS
- DOM-based XSS with data retrieved from document.documentElement.attributes.setAttribute
- DOM-based XSS with data retrieved from document.documentElement.attributes.setAttributeNS
- DOM-based XSS with data retrieved from document.documentElement.attributes.hasAttribute
- DOM-based XSS with data retrieved from document.documentElement.attributes.hasAttributeNS
- DOM-based XSS with data retrieved from document.documentElement.attributes.getNamedItemValue
- DOM-based XSS with data retrieved from document.documentElement.attributes.getNamedItemNSValue
- DOM-based XSS with data retrieved from document.documentElement.attributes.removeNamedItemValue
- DOM-based XSS with data retrieved from document.documentElement.attributes.removeNamedItemNSValue
- DOM-based XSS with data retrieved from document.documentElement.attributes.setNamedItemValue
- DOM-based XSS with data retrieved from document.documentElement.attributes.setNamedItemNSValue
- DOM-based XSS with data retrieved from document.documentElement.attributes.itemValue
- DOM-based XSS with data retrieved from document.documentElement.attributes.namedItemValue
- DOM-based XSS with data retrieved from document.documentElement.attributes.getValue
- DOM-based XSS with data retrieved from document.documentElement.attributes.setValue
- DOM-based XSS with data retrieved from document.documentElement.attributes.hasValue
- DOM-based XSS with data retrieved from document.documentElement.attributes.removeValue
- DOM-based XSS with data retrieved from document.documentElement.attributes.removeValueNS
- DOM-based XSS with data retrieved from document.documentElement.attributes.getValue
- DOM-based XSS with data retrieved from document.documentElement.attributes.getValueNS
- DOM-based XSS with data retrieved from document.documentElement.attributes.setValue
- DOM-based XSS with data retrieved from document.documentElement.attributes.setValueNS
- DOM-based XSS with data retrieved from document.documentElement.attributes.hasValue
- DOM-based XSS with data retrieved from document.documentElement.attributes.hasValueNS
- DOM-based XSS with data retrieved from document.documentElement.attributes.getNamedItemType
- DOM-based XSS with data retrieved from document.documentElement.attributes.getNamedItemNSType
- DOM-based XSS with data retrieved from document.documentElement.attributes.removeNamedItemType
- DOM-based XSS with data retrieved from document.documentElement.attributes.removeNamedItemNSType
- DOM-based XSS with data retrieved from document.documentElement.attributes.setNamedItemType
- DOM-based XSS with data retrieved from document.documentElement.attributes.setNamedItemNSType
- DOM-based XSS with data retrieved from document.documentElement.attributes.itemType
- DOM-based XSS with data retrieved from document.documentElement.attributes.namedItemValue
- DOM-based XSS with data retrieved from document.documentElement.attributes.getValueType
- DOM-based XSS with data retrieved from document.documentElement.attributes.setValueType
- DOM-based XSS with data retrieved from document.documentElement.attributes.hasValueType
- DOM-based XSS with data retrieved from document.documentElement.attributes.removeValueType
- DOM-based XSS with data retrieved from document.documentElement.attributes.removeValueNSType
- DOM-based XSS with data retrieved from document.documentElement.attributes.getValueType
- DOM-based XSS with data retrieved from document.documentElement.attributes.getValueNSType
- DOM-based XSS with data retrieved from document.documentElement.attributes.setValueType
- DOM-based XSS with data retrieved from document.documentElement.attributes.setValueNSType
- DOM-based XSS with data retrieved from document.documentElement.attributes.hasValueType
- DOM-based XSS with data retrieved from document.documentElement.attributes.hasValueTypeNS
- DOM-based XSS with data retrieved from document.documentElement.attributes.getNamedItemType
- DOM-based XSS with data retrieved from document.documentElement.attributes.getNamedItemNSType
- DOM-based XSS with data retrieved from document.documentElement.attributes.removeNamedItemType
- DOM-based XSS with data retrieved from document.documentElement.attributes.removeNamedItemNSType
- DOM-based XSS with data retrieved from document.documentElement.attributes.setNamedItemType
- DOM-based XSS with data retrieved from document.documentElement.attributes.setNamedItemNSType
- DOM-based XSS with data retrieved from document.documentElement.attributes.itemType
- DOM-based XSS with data retrieved from document.documentElement.attributes.namedItemType
- DOM-based XSS with data retrieved from document.documentElement.attributes.getValueType
- DOM-based XSS with data retrieved from document.documentElement.attributes.getValueTypeNS
- DOM-based XSS with data retrieved from document.documentElement.attributes.setValueType
- DOM-based XSS with data retrieved from document.documentElement.attributes.setValueTypeNS
- DOM-based XSS with data retrieved from document.documentElement.attributes.hasValueType
- DOM-based XSS with data retrieved from document.documentElement.attributes.hasValueTypeNS
- DOM-based XSS with data retrieved from document.documentElement.attributes.getNamedItemType
- DOM-based XSS with data retrieved from document.documentElement.attributes.getNamedItemNSType
- DOM-based XSS with data retrieved from document.documentElement.attributes.removeNamedItemType
- DOM-based XSS with data retrieved from document.documentElement.attributes.removeNamedItemNSType
- DOM-based XSS with data retrieved from document.documentElement.attributes.setNamedItemType
- DOM-based XSS with data retrieved from document.documentElement.attributes.setNamedItemNSType
- DOM-based XSS with data retrieved from document.documentElement.attributes.itemType
- DOM-based XSS with data retrieved from document.documentElement.attributes.namedItemType
- DOM-based XSS with data retrieved from document.documentElement.attributes.getValueType
- DOM-based XSS with data retrieved from document.documentElement.attributes.getValueTypeNS
- DOM-based XSS with data retrieved from document.documentElement.attributes.setValueType
- DOM-based XSS with data retrieved from document.documentElement.attributes.setValueTypeNS
- DOM-based XSS with data retrieved from document.documentElement.attributes.hasValueType
- DOM-based XSS with data retrieved from document.documentElement.attributes.hasValueTypeNS
- DOM-based XSS with data retrieved from document.documentElement.attributes.getNamedItemType
- DOM-based XSS with data retrieved from document.documentElement.attributes.getNamedItemNSType
- DOM-based XSS with data retrieved from document.documentElement.attributes.removeNamedItemType
- DOM-based XSS with data retrieved from document.documentElement.attributes.removeNamedItemNSType
- DOM-based XSS with data retrieved from document.documentElement.attributes.setNamedItemType
- DOM-based XSS with data retrieved from document.documentElement.attributes.setNamedItemNSType
- DOM-based XSS with data retrieved from document.documentElement.attributes.itemType
- DOM-based XSS with data retrieved from document.documentElement.attributes.namedItemType
- DOM-based XSS with data retrieved from document.documentElement.attributes.getValueType
- DOM-based XSS with data retrieved from document.documentElement.attributes.getValueTypeNS
- DOM-based XSS with data retrieved from document.documentElement.attributes.setValueType
- DOM-based XSS with data retrieved from document.documentElement.attributes.setValueTypeNS
- DOM-based XSS with data retrieved from document.documentElement.attributes.hasValueType
- DOM-based XSS with data retrieved from document.documentElement.attributes.hasValueTypeNS
- DOM-based XSS with data retrieved from document.documentElement.attributes.getNamedItemType
- DOM-based XSS with data retrieved from document.documentElement.attributes.getNamedItemNSType
- DOM-based XSS with data retrieved from document.documentElement.attributes.removeNamedItemType
- DOM-based XSS with data retrieved from document.documentElement.attributes.removeNamedItemNSType
- DOM-based XSS with data retrieved from document.documentElement.attributes.setNamedItemType
- DOM-based XSS with data retrieved from document.documentElement.attributes.setNamedItemNSType
- DOM-based XSS with data retrieved from document.documentElement.attributes.itemType
- DOM-based XSS with data retrieved from document.documentElement.attributes.namedItemType
- DOM-based XSS with data retrieved from document.documentElement.attributes.getValueType
- DOM-based XSS with data retrieved from document.documentElement.attributes.getValueTypeNS
- DOM-based XSS with data retrieved from document.documentElement.attributes.setValueType
- DOM-based XSS with data retrieved from document.documentElement.attributes.setValueTypeNS
- DOM-based XSS with data retrieved from document.documentElement.attributes.hasValueType
- DOM-based XSS with data retrieved from document.documentElement.attributes.hasValueTypeNS
- DOM-based XSS with data retrieved from document.documentElement.attributes.getNamedItemType
- DOM-based XSS with data retrieved from document.documentElement.attributes.getNamedItemNSType
- DOM-based XSS with data retrieved from document.documentElement.attributes.removeNamedItemType
- DOM-based XSS with data retrieved from document.documentElement.attributes.removeNamedItemNSType
- DOM-based XSS with data retrieved from document.documentElement.attributes.setNamedItemType
- DOM-based XSS with data retrieved from document.documentElement.attributes.setNamedItemNSType
