# Open-Shop-SOAP
Communication templates for WSC Revivals.

## Why are there bubbles?
In order for OSC to distribute Homebrew content through the Wii Shop Channel, a protocol called SOAP will need to be worked out in order to get this working.

## What is SOAP?
*[From Wikipedia, the free encyclopedia.](https://en.wikipedia.org/wiki/SOAP)*<br>
SOAP (originally Simple Object Access Protocol) is a messaging protocol specification for exchanging structured information in the implementation of web services in computer networks. Its purpose is to induce extensibility, neutrality and independence. It uses XML Information Set for its message format, and relies on application layer protocols, most often Hypertext Transfer Protocol (HTTP) or Simple Mail Transfer Protocol (SMTP), for message negotiation and transmission.<br>

## What purpose has this SOAP Protocol?
The **SOAP Protocol** is used by the **Wii Shop Channel** in order to connect to the IAS/ECS Servers by Nintendo. Those servers have a specific certificate binded to them, and this certificate has to be same as the certificate in the channel itself, so this server has to be re-created. The channel will get a client certificate, of course.

## Understanding the SOAP Templates
Each SOAP template is stored as an XML on this repo, however, there is also header information for the SOAP's POST command and Response/Request templates.

Please note that the original parameters in each SOAP template have been replaced with placeholders to protect the security of the original account holders of the WSC accounts when logging the data.
E.g: <AccountId>12345678</AccountId> to <AccountId>$AccountId</AccountId>.
It's up to you to fill in those spaces and create your own data for these templates.
