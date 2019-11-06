---
title: "OverTheWire: Natas"
date: 2019-11-05T19:54:00Z
draft: true
---

Ref: https://overthewire.org/wargames/natas/

**This is not a walkthrough.** Just some tips and hints to get out of rabbit holes.

### Level 0-5
* Make use of the **Developer Tools** in your browser.
* In the html code for each level, only `<div id="content">` block is relevant. Pay attention to the hints there.

### Level 6
<details>
  <summary>Hint: Type of Vulnerability</summary>
  [Path Traversal](https://www.owasp.org/index.php/Path_Traversal)
</details>

### Level 7
<details>
  <summary>Hint: Type of Vulnerability</summary>
  [Path Traversal](https://www.owasp.org/index.php/Path_Traversal)
</details>

### Level 8
Tip: To make things easier, might want to run php interactively from your favourite terminal e.g.

`php -a`

### Level 9
Tip: All passwords are also stored in /etc/natas_webpass/. E.g. the password for natas5 is stored in the file /etc/natas_webpass/natas5 (reference: https://overthewire.org/wargames/natas/)
<details>
  <summary>Hint: Type of Vulnerability</summary>
  [Command Injection](https://www.owasp.org/index.php/Command_Injection)  
</details>

### Level 10
<details>
  <summary>Hint: What else can I use?</summary>
  Have a look at the list [here](https://www.owasp.org/index.php/Testing_for_Command_Injection_(OTG-INPVAL-013)#Sanitization)
</details>

### Level 11
Under the properties of XOR operations...
'<censored>' in the code is something else...
Try work out what '<censored>' actually is
Figure out how to get that same cookie

### Level 12
https://en.wikipedia.org/wiki/File_inclusion_vulnerability
Can you see what is preventing you from uploading another type of file?

### Level 13
File headers...

### Level 14
<details>
  <summary>Hint: Type of Vulnerability</summary>
  [SQL Injection](https://www.owasp.org/index.php/Testing_for_SQL_Injection_(OTG-INPVAL-005))
</details>

### Level 15
<details>
  <summary>Hint: Type of Vulnerability</summary>
  [SQL Injection](https://www.owasp.org/index.php/Testing_for_SQL_Injection_(OTG-INPVAL-005)#Boolean_Exploitation_Technique)
</details>

### Level 16
