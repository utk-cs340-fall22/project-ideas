## Project Idea Summary
### Logan Oneal

### Project Title: Dynamic QR Code Generation/Hosting Service

### The Problem
QR codes are used by many different business and organizations to provide an easy means of information access. One of the major problems with QR codes is that once they are created, the link stored in the code is static. This means that if the webpage hosting the linked URL were to go down or change web addresses, the QR code would no longer function properly. 

### The Solution
In order to solve this problem, I am want to build a SAAS service that hosts both a QR code generation tool and a backend system that allows users to update their QR codes any time after the time of creation. I also think there is potential here to monetize QR codes with advertisements which could benefit either the company themselves or the QR code service. 

### Target Audience
This service is for individuals who plan to install QR codes for long periods of time. Some common examples of this are resturants who use QR codes for their menus, businesses who install QR codes in public places, and individuals who use QR codes for personal branding such as business card alternatives. 

### Features List
- QR Code Image Generation
- URL Hosting per QR code
- Ability to redirect hosted URL to any other URL
- Potential QR code monetizion (show an advertisement before page loads)

### Tech Stack
- Frontend: ReactJS, Material UI
- Backend: Either NodeJS or .NET
- Storage: Either Firebase or MongoDB
- DNS: Cloudflare 