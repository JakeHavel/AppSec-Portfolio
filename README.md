
The Vulnerability: Path traversal
The Exploitation: Any code or endpoint that accesses a file on the server can be used to go backwards to other files, for example: https://insecure-website.com/loadImage?filename=../../../etc/passwd
The Remediation: 
