# POODLE-Attack-Cybersecurity
In-depth analysis and exploration of the POODLE (Padding Oracle On Downgraded Legacy Encryption) attack, focusing on its impact on SSL 3.0, defense strategies, and reflections on cybersecurity measures.

Abstract:

This report presents a comprehensive analysis of the POODLE (Padding Oracle On Downgraded Legacy Encryption) attack, detailing the vulnerability in SSL 3.0 protocol's handling of block cipher padding. We use Express.js and Node.js frameworks with Burp Suite for traffic interception, demonstrating both the attack mechanism and defense strategies.


Introduction:

The POODLE attack, discovered in 2014, exploits vulnerabilities in SSL 3.0, a widely used standard for securing internet traffic. Our project aims to deepen the understanding of this critical security flaw and explore effective defense mechanisms.


Technical Details:

SSL 3.0 Encryption Mechanism: The protocol's mechanism for encryption and block cipher padding.
Exploiting the Padding Oracle: How the POODLE attack leverages SSL 3.0's weaknesses.
Attack Methodology: The process of executing the POODLE attack.
Defense Against the Attack
We explore various defense strategies including disabling SSLv3, patching and updating systems, implementing TLS Fallback SCSV, and more.


System Configuration:

Operating System: MacOS
Platforms: Express.js and Node.js
Tools Used: Burp Suite for traffic interception.


Keywords:
POODLE attack, SSL 3.0, cybersecurity, block cipher padding, man-in-the-middle attack, JavaScript, Burp Suite.

Project video:
[![Project Video](http://img.youtube.com/vi/c11ijeoxa58/0.jpg)](http://www.youtube.com/watch?v=c11ijeoxa58 "Project Video")
