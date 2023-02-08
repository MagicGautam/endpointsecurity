# Endpoint Security algorithm

This is an implementation of an Endpoint security algorithm which searches the host's directory for potential malwares by extensively checking files present in the directory you've wished to be checked. 

To make the system work I've created a few methods. Their functions vary from accessing each and every file to creating the SHA256 hash of the file and then checking it's hash on VIRUSTOTAL's Malware Hash Database via and API call and then deciding weather the file present is a virus or not.
