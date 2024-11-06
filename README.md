# Lab 6  Trust and Digital Certificates


Objective: Digital certificates are used to define a trust infrastructure within PKI (Public Key
Infrastructure). A certificate can hold a key pair, while a distributable certificate will only
contain the public key. In this lab we will read-in digital certificates and analyse them.


| No    | Description                                                                                                                                                      | Result                                                                                                                            |
|-------|------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------|
| A.1  | From: <br> Web link (Digital Certificate): <br> http://asecuritysite.com/encryption/digitalcert <br> Open up Certificate 1 and identify the following:          | - Serial number: <br> - Effective date: <br> - Name: <br> - Issuer: <br> - What is CN used for: <br> - What is ON used for: <br> - What is O used for: <br> - What is L used for: |
| A.2  | Now open up the ZIP file for the certificate (Certificate 3), and view the DER file.                                                                            | - What other information can you gain from the certificate: <br> - What is the size of the public key: <br> - Which hashing method has been used: <br> - Is the certificate trusted on your system: <br> `[Yes] [No]` |
| A.3  | Make a connection to the www.live.com Web site: <br> `openssl s_client -connect www.live.com:443`                                                               | - Can you identify the certificate chain? <br> - What is the subject on the certificate? <br> - Who is the issuer on the certificate? |
| A.4  | Google moved in July 2018 to mark sites as being insecure if they did not have a match between their digital certificate and the site. <br> First, open a browser and see if you can access. | - Run a scan from SSLLabs on testfire.net. What do you observe from the result? |

