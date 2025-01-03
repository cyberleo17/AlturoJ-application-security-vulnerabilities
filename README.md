WARNING: This application contains security vulnerabilities. Run it only in a backed-up and sheltered environment (such as a VM with a recent snapshot and host-only networking) and at your own risk, escpecially if you enable some of the advanced options described below!

AltoroJ is a sample banking J2EE web application. It shows what happens when web applications are written with consideration of app functionality but not app security. It's a simple and uncluttered platform for demonstrating and learning more about real-life application security issues.

AltoroJ uses standard Java & JSP functionality without relying on any additional frameworks. While vast majority of real-life applications do use frameworks, the exact same principles of Application Security apply in both cases. Frameworks can also be hard to understand for someone not familiar with a particular framework and introduce complexities that detract from the overall learning experience. Not to mention, a large number of large and complex "legacy" Java web applications that look very similar to AltoroJ (but are infinitely more complex of course).

AltoroJ uses Apache Derby as its SQL database that is automatically initialized the first time you log into AltoroJ via its web interface. All of the transactions and operations will then be stored in this database from that point on until you delete your repository folder called "altoro" that is located in your OS home folder (e.g. C:\Users[your_username] or /Users/[your_username]) or enable advanced option to re-initialize your database every time your web application server is restarted (see below).

AltoroJ was created in 2008 and has gone through a number of iterations since then. It currently, being used around the world to demonstrate application security vulnerabilities, educate folks on how easy some of these issues are to exploit and how severe the impact may be, and is even a part of academic curricula. Even though AltoroJ is pretty stable, if you do find a bug or create a cool exploit for one of its vulnerabilities - please let us know!!!

Please download the following dependencies:
- Apache Tomcat 7/8/9 (or pull it from this repository).
- IntelliJ Ultimate (To set-up Tomcat Local Server).
