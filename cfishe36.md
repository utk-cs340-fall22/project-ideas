# Low-interaction honeypot
### Caleb Fisher

## Summary
Low-interaction honeypots serve as a method of capturing and deflecting malicious traffic in information systems. The specific implementation of this honeypot would focus on capturing and providing limited surveillance of basic attacks on a vulnerable port.

## The Problem
Data is becoming increasingly ubiquitous, and with it, cybersecurity has become a far more pivotal component of the software design process. Security failures are certainly not going anywhere with the potential loaded in data at rest and in transit. Honeypots and larger honey nets take a nontraditional approach to security by featuring deflection and monitoring systems. These features can be particulary helpful in addition to traditional security models because of the ability to stall the risk of new vulnerabilities and gain insight into attack methods.

## Major Features
- Creates a working host with ports vulnerable to common attacks
- Creates a connection logger to identify malicious intruders
- Utilizes MHN (Modern Honey Network) to feed and access attack logs with a neat interface
- Mimics a realistic system to retain attacker involvement

## Languages and Tools
- Python / Go
- Tornado networking library
- MHN 

## Target Audience
The primary audience for this tool would be smaller software solutions that wish to provide an added layer of security. This could aid in abating the risk of common script attacks on startups and open-source projects. It would be particularly useful for groups which are heavily involved with sensitive data.