# presentation-Q3-2019

Hey, everyone! Today we're gonna talk about OWASP Top 10

 The OWASP Top 10 is a powerful awareness document for web application security. It represents a broad consensus about the most critical security risks to web applications

`Slide with #1 Injection attacks`

 The first one is called **Injection attacks**

`Slide with #1 description`

Injection attacks happen when untrusted data is sent to a code interpreter through a form input or some other data submission to your web application. For example, an attacker could enter SQL database code into a form that expects, for example, a plaintext username. And if that form input is not properly secured, this would result in that SQL code being executed. This is called an SQL injection attack.

`Slide with 'Ways to prevent'`

`Slide with #2 Broken authentication`

So, number two is **Broken authentication**

`Slide with #2 description`

Different vulnerabilities in authentication (login) systems can give attackers access to user accounts or even compromise an entire system using an admin account. For example, an attacker can have a list of known username/password combinations obtained during a data breach and try all those combinations on your login system to see if any of that work

`Slide with 'Ways to prevent'`

`Slide with #3 Sensitive data exposure`

So, nuber three is **Sensitive data exposure**

`Slide with #3 description`

Data exposure risk can be minimized by encrypting all of your sensitive data as well as disabling the caching* of your sensitive information. Additionally, web developers should take care to ensure that they are not unnecessarily storing any sensitive data asa well as make sure, that oll of the sensitive data is secured at rest

`Slide with 'Ways to prevent'`

`Slide with #4 XML External entities`

Number four is **XML External entities**

`Slide with #4 description`

This is an attack against a web application that parses XML* input. This input can reference an external entity, attempting to exploit a vulnerability in the parser. An ‘external entity’ in this context refers to a storage unit, such as a hard drive. An XML parser can be duped into sending data to an unauthorized external entity, which can pass this information directly to an attacker

`Slide with 'Ways to prevent'`

`Slide with #5 XML External entities`

Number five is **Broken access control**

`Slide with #5 description`

Broken access controls allow attackers to bypass authorization and perform tasks as if they were privileged users, for example an admin. And if your application is not secured properly, thiscould allow a user to change which account they are logged in as simply by changing a url path, without any other verifications

`Slide with 'Ways to prevent'`

`Slide with #6 XML External entities`

Number six is **Security misconfiguration**

`Slide with #6 description`

Security misconfiguration is the most common vulnerability on the list, and is often the result of using default configurations or handling errors with overshared information. For instance, if your application shows an error to a user with overshared information, this may reveal a bunch of vulnerabilities in your application

`Slide with 'Ways to prevent'`

`Slide with #7 Cross-site scripting`

Number seven is **Cross-site scripting**

`Slide with #7 description`

Cross-site scripting vulnerabilities occur when web applications allow users to add custom code into a url path or onto a website that will be seen by other users. This vulnerability can be exploited to run malicious JavaScript code on a victim’s browser. For example, an attacker could send an email to a victim that appears to be from a trusted bank, with a link to that bank’s website. This link could have some malicious JavaScript code tagged onto the end of the url. If the bank’s site is not properly protected against cross-site scripting, then that malicious code will be run in the victim’s web browser when they click on the link

`Slide with 'Ways to prevent'`

`Slide with #8 Insecure deserialization`

Number eight is **insecure deserialization**

`Slide with #8 description`

This threat targets the many web applications which frequently serialize and deserialize data. Serialization means taking objects from the application code and converting them into a format that can be used for another purpose, such as storing the data to disk or streaming it. Deserialization is just the opposite: converting serialized data back into objects the application can use. Serialization is sort of like packing furniture away into boxes before a move, and deserialization is like unpacking the boxes and assembling the furniture after the move. An insecure deserialization attack is like having the movers tamper with the contents of the boxes before they are unpacked

`Slide with 'Ways to prevent'`

`Slide with #9 Using components with known vulnerabilities`

Number nine is **using different components with known vulnerabilities**

`Slide with #9 description`

Many modern web developers use components such as libraries and frameworks in their web applications. Some attackers look for different vulnerabilities in these components which they can then use to orchestrate attacks. Some of the more popular components are used on hundreds of thousands of websites; an attacker finding a security hole in one of these components could leave all of those websites vulnerable to exploit

`Slide with 'Ways to prevent'`

`Slide with #10 Unsufficient logging and monitoring`

Number 10 is **Unsufficient logging and monitoring**

`Slide with #10 description`

Many web applications are not taking enough steps to detect data breaches. The average discovery time for a breach is around 200 days after it has happened. This gives attackers a lot of time to cause damage before there is any response. OWASP recommends that web developers should implement logging and monitoring as well as incident response plans to ensure that they are made aware of attacks on their applications

`Slide with 'Ways to prevent'`

`Slide 'Stay safe'`

So, thank you for watching. This was basic info about OWASP top 10 vulnerabilities and for more information and technical details you can look the [official report](https://www.owasp.org/images/7/72/OWASP_Top_10-2017_%28en%29.pdf.pdf) and stau safe on the internet :)

`Think about it)))`