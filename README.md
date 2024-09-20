# eNMS < 4.7.1 Multiple Path Traversal Vulnerability
The eNMS application is vulnerable to a path traversal vulnerability, identified as CVE-2024-46644-9. This vulnerability allows an attacker to access and upload sensitive files outside the intended directory by manipulating the URL request.

# CVE ID
**CVE-2024-46644 - CVE-2024-46649**

# Details
* **Vulnerability Type**: Path Traversal
* **Affected Application**: eNMS
* **Affected Versions**: < 4.7.1
* **Impact**: Unauthorized access to sensitive files, allowing arbitrary file upload and potential exposure of confidential information.

# PoC / Attack Example

Within the application there are 6 vulnerable parameters for reading/uploading sensitive files:
* [CVE-2024-46644](CVE-2024-46644.md)
* [CVE-2024-46645](CVE-2024-46645.md)
* [CVE-2024-46646](CVE-2024-46646.md)
* [CVE-2024-46647](CVE-2024-46647.md)
* [CVE-2024-46648](CVE-2024-46648.md)
* [CVE-2024-46649](CVE-2024-46649.md)


# References
https://www.cve.org/CVERecord?id=CVE-2024-46644
# Credits
**Andrea Pessione** and **Manuel Scala** <br></br>
<a href="https://sk-it.com/"><img src="img/skit_logo.png" width="300">
