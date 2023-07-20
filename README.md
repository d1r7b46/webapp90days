# Web App Attack Basics - 90 Days of Education
This plan is designed for self-education in web application security and includes the following topics:
**Week 1-2:** SQL Injection <br>
**Week 3-4:** XSS Attacks (Cross-Site Scripting) <br>
**Week 5-6:** Access Control Vulnerabilities <br>
**Week 7-8:** Business Logic & Information Disclosure <br>
**Week 9-10:** File Upload Vulnerabilities & Server-Side Request Forgery (SSRF) <br>
**Week 11-12:** Server-Side Template Injection (SSTI) & XML External Entity (XXE) Injection <br>
**Week 13:** Review, Practice, Seek Mentorship, & Take Next Steps <br><br>

I will try to find learning material for each major section based on the 4 predominant learning styles. Many people need to utilize a mixture of learning styles to grasp concepts. Feel free to work your way through everything provided or to go through it until you feel comfortable discussing the topic in an interview or with peers. <br>
The 4 types are: <br>
**Visual** - learning via diagrams, pictures, charts, notes with different spatial arrangements or colors<br>
**Auditory** - learning via active listening<br>
**Read/Write** - learning via reading and writing<br>
**Kinaesthetic** - interactive learning, learning by doing<br>

<br><br>

## **Before you Begin**
- Set up an account with PortSwigger <br>
https://portswigger.net/web-security
- Set up Juice Shop <br>
https://pwning.owasp-juice.shop
- Set up a TryHackMe account (affiliate link) <br>
https://tryhackme.com/signup?referrer=5fc50abdccbc930779bcc40e
<br><br>
Optional:
- Set up a Quizlet account <br>
https://quizlet.com <br><br><br>

## Informational  
I've worked to expose myself & the student here to different YouTube channels/personalities for a reason. If you find that you learn the best from Computerphile, go find more of those for the topic at hand. If you learn better from Alex Olsen, go seek out his videos instead! <br><br>
Then, although I've pulled out individual PortSwigger sections I'd advise to read & take notes on the entire PortSwigger trainings for the topics mentioned above. This material will be PortSwigger heavy! <br><br>
If you got a ton out of this and want to buy me a coffee, I won't say no :D 
https://ko-fi.com/d1r7b46 <br><br>
Okay onto the good stuff!


<br><br><br>
## Plan & Schedule 

### **Week 1-2: SQL Injection** <br>
*Day 1-3: Introduction to SQL injection (Concepts and Risks)*
   - Visual
      - Understanding Components of a Table: https://www.w3resource.com/sql/sql-basic/the-components-of-a-table.php 
   - Auditory
      - Professor Messer's Explanation here: https://www.youtube.com/watch?v=H0IN5Ok7tZk
   - Read/Write
      - Read & take notes: https://portswigger.net/web-security/sql-injection
      - Read & take notes: https://owasp.org/www-community/attacks/SQL_Injection
      - Make and use 10-20 physical or digital flashcards, focusing on vocab and key concepts
   - Kinaesthetic
      - Complete all Portswigger Apprentice labs: https://portswigger.net/web-security/all-labs#sql-injection
         - Part of kinaesthetic is watching someone work and mimicking. My favorite online teacher for PortSwigger labs is Rana Khalil (https://www.youtube.com/@RanaKhalil101)
      - TryHackMe Rooms (free): https://tryhackme.com/room/sqlilab & https://tryhackme.com/room/sqlinjectionlm <br><br>

*Day 3-6: Types of SQL injection attacks*<br>
   - Visual
      - Draw diagrams for yourself of each type you learn about in the material below. If possible, partner with a mentor to ensure understanding.
   - Auditory
      - 4 Types of SQL Injection by Bert Wagner: https://www.youtube.com/watch?v=UMJV3OpjsoM
      - Blind SQL Injection Attacks Made Easy: https://www.youtube.com/watch?v=j-fLh_WNg7k
   - Read/Write
      - Read & take notes - High Level Review: https://www.geeksforgeeks.org/types-of-sql-injection-sqli/
      - Read & take notes - Union: https://portswigger.net/web-security/sql-injection/union-attacks
      - Read & take notes - Blind: https://portswigger.net/web-security/sql-injection/blind
      - Make and use 10-20 physical or digital flashcards, focusing on vocab and key concepts
   - Kinaesthetic
      - Complete the Injection section of Juice Shop: https://pwning.owasp-juice.shop/part2/injection.html
      - Learn about SQLMap by finishing this TryHackMe room (free): https://tryhackme.com/room/sqlmap <br><br>

*Day 6-9: Preventive measures and best practices*<br>
   - Visual
      - Take notes on the Synk's document here, changing up hilighting or even drawing your own diagrams: https://foojay.io/today/8-best-practices-to-prevent-sql-injection-attacks/
   - Auditory
      - Catch Rana Khalil's video, focusing specifically on the "How to Prevent" section: https://www.youtube.com/watch?v=1nJgupaUPEQ
   - Read/Write
      - Read & take notes: https://cheatsheetseries.owasp.org/cheatsheets/SQL_Injection_Prevention_Cheat_Sheet.html
      - Read & take notes: https://portswigger.net/web-security/sql-injection#how-to-prevent-sql-injection
      - Read to understand the "Validate All Input" section found here: https://learn.microsoft.com/en-us/sql/relational-databases/security/sql-injection?view=sql-server-ver16
      - Make and use 10-20 physical or digital flashcards, focusing on vocab and key concepts
   - Kinaesthetic
      - Learn the code in the following, create some code that would be susceptible and seek out: https://bobby-tables.com/plsql <br><br>

*Day 9-14: Practice SQL injection on vulnerable web applications and in labs*<br>
   - Kinaesthetic
      - TryHackMe Rooms (free): https://tryhackme.com/room/sqhell OR https://tryhackme.com/room/prioritise
      - Complete OWASP WebGoat's SQL Injection section: https://owasp.org/www-project-webgoat/
      - Complete Damn Vulnerable Web Application's section on SQL Injections: https://github.com/digininja/DVWA
      - Review all flashcards created through these first two weeks. Here's the deck I created: https://quizlet.com/814910147/sql-injections-flash-cards/?i=4yncp7&x=1jqt

<br><br>

### **Week 3-4: XSS Attacks** <br>
*Day 15-18: Understanding Cross-Site Scripting (XSS) vulnerabilities*
- Visual
   - This blog has some good visuals for several XSS attacks: https://dev.to/maleta/cors-xss-and-csrf-with-examples-in-10-minutes-35k3
   - Watch the Computerphile guys explain verbally and by drawing out a xss attack: https://www.youtube.com/watch?v=L5l9lSnNMxg&list=RDLVL5l9lSnNMxg&start_radio=1&rv=L5l9lSnNMxg&t=33
   - The Lightboard Lesson series is awesome to watch through, here's the XSS one: https://www.youtube.com/watch?v=IuzU4y-UjLw
- Auditory
   -  Catch HackerSploit's video: https://www.youtube.com/watch?v=SHmQ3sQFeLE
- Read/Write
   - Read & take notes: https://portswigger.net/web-security/cross-site-scripting
   - Read through top XSS bug bounty reports: https://github.com/reddelexc/hackerone-reports/blob/master/tops_by_bug_type/TOPXSS.md
   - Make and use 10-20 physical or digital flashcards, focusing on vocab and key concepts
- Kinaesthetic
   - TryHackMe room MD2PDF has a XSS vulnerability, can you get the flag? https://tryhackme.com/hacktivities?tab=search&page=1&free=all&order=most-popular&difficulty=all&type=all&searchTxt=xss
   - TryHackMe paid $ room Cross-site Scripting might also be a good choice if you pay for the service: https://tryhackme.com/room/xss <br><br>

*Day 18-21: Reflected, Stored, and DOM-based XSS attacks* <br>
- Visual
   - PwnFunction on YouTube draws and provides graphics as they teach, Reflected XSS is at 5.41, Dom is at 7.30: https://www.youtube.com/watch?v=EoaDgUgS6QA
- Auditory
   - Although there are also some diagrams on LiveOverflow's video on XSS you can easily just listen to this video if you want: https://www.youtube.com/watch?v=mKAWpFdVcPY
- Read/Write
   - Read & take notes on the Reflected, Stored, and DOM-based XSS attacks on PortSwigger: https://portswigger.net/web-security/cross-site-scripting/reflected
   - Make and use 10-20 physical or digital flashcards, focusing on vocab and key concepts
- Kinaesthetic
   - Complete all Portswigger Apprentice labs: https://portswigger.net/web-security/all-labs#cross-site-scripting   <br><br>
   
*Day 21-24: Mitigation techniques and secure coding practices*<br>
*Day 24-28: Hands-on XSS exploitation exercises*<br>
- Kinaesthetic
   - Play the XSS Game: https://xss-game.appspot.com

<br><br>

### **Week 5-6: Access Control Vulnerabilities** <br>
*Day 17-18: Introduction to Access Control flaws, Insecure Direct Object References, IDOR*<br>
*Day 19-20: Role-based access control and privilege escalation*<br>
*Day 21-22: Implementing proper access controls*<br>
*Day 23-24: Test and practice identifying access control issues*<br>
<br><br>

### **Week 7-8: Business Logic & Information Disclosure**<br>
*Day 25-26: Understanding Business Logic vulnerabilities*<br>
*Day 27-28: Identifying and exploiting logic flaws*<br>
*Day 29-30: Safeguarding business logic and handling sensitive information*<br>
*Day 31-32: Analyzing and avoiding information disclosure risks*<br>
<br><br>

### **Week 9-10: File Upload Vulnerabilities & SSRF**<br>
*Day 33-34: Exploring File Upload vulnerabilities and potential exploits*<br>
*Day 35-36: Best practices for secure file uploads*<br>
*Day 37-38: Introduction to Server-Side Request Forgery*<br>
*Day 39-40: Detecting and preventing SSRF attacks*<br>
<br><br>

### **Week 11-12: SSTI & XML External Entity (XXE) Injection**<br>
*Day 41-42: Understanding Server-Side Template Injection (SSTI) vulnerabilities*<br>
*Day 43-44: Mitigation strategies and secure coding techniques*<br>
*Day 45-46: Introduction to XML External Entity (XXE) Injection*<br>
*Day 47-48: Preventing XXE attacks and staying secure*<br>
<br><br>

### **Week 13: Review & Practice**<br>
*Day 49-51: Review all topics covered in the past weeks*<br>
*Day 52-53: Practice on realistic web app pentesting scenarios*<br>
*Day 54-55: Seek guidance or mentorship from experienced pentesters if possible*<br>
*Day 56-90: Continue hands-on practice, explore real-world applications, and attend webinars or workshops to deepen understanding*<br>
<br><br>


<br><br>
## **Free Web App Security Courses**
- Qualys Web Application Scanning Self Paced Training: https://www.qualys.com/training/course/web-application-scanning/
- PentesterLab Web for Pentester: https://pentesterlab.com/exercises/web_for_pentester/course
- freeCodeCamp Ethical Hacking 101: Web App Penetration Testing: https://www.youtube.com/watch?v=2_lswM1S264


<br><br>
## **Certifications for Web Application Pentesting**
- eWPT: https://elearnsecurity.com/product/ewpt-certification/
- GWAPT: https://www.giac.org/certifications/web-application-penetration-tester-gwapt/


<br><br><br>
## **Tips for Success for those that have ADHD**<br>
Dearest fellow ADHDers. This might look like a lot! Take a few hours, plan this out, but keep in mind the below:
1. Break the study sessions into short, focused blocks with regular breaks to maintain attention.<br>
2. Use interactive learning methods, such as online labs, capture-the-flag (CTF) challenges, and videos.<br>
3. Create a quiet and organized study environment to minimize distractions.<br>
4. Utilize task lists, timers, and study apps to help with time management and focus.<br>
5. Consider joining a study group or finding an accountability partner to stay motivated and engaged.<br>
6. Celebrate achievements and progress throughout the 90 days to boost morale.<br>
