<h2>Requirements</h2>
<b>resources</b>
https://alx-intranet.hbtn.io/rltoken/d--jVK8sBSlhkosu7pFzdw

<h2>General</h2>
<li>Allowed editors: vi, vim, emacs
<li>All your files will be interpreted/compiled on Ubuntu 14.04 LTS using python3 (version 3.4.3)
<li>All your files should end with a new line
<li>The first line of all your files should be exactly #!/usr/bin/python3
<li>A README.md file, at the root of the folder of the project, is mandatory
<li>Your code should use the PEP 8 style (version 1.7.x)
<li>All your files must be executable

<h2>Task 0. UTF-8 Validation </h2>

<p>Write a method that determines if a given data set represents a valid UTF-8 encoding.

<li>Prototype: def validUTF8(data)
<li>Return: True if data is a valid UTF-8 encoding, else return False
<li>A character in UTF-8 can be 1 to 4 bytes long
<li>The data set can contain multiple characters
<li>The data will be represented by a list of integers
<li>Each integer represents 1 byte of data, therefore you only need to handle the 8 least significant bits of each integer