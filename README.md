# Web App Attack Basics - 90 Days of Education
This plan is designed for self-education in web application security and includes the following topics:
**Week 1-2:** SQL Injection <br>
**Week 3-4:** XSS Attacks (Cross-Site Scripting) <br>
**Week 5-6:** Access Control Vulnerabilities <br>
**Week 7-8:** Business Logic & Information Disclosure <br>
**Week 9-10:** File Upload Vulnerabilities & Server-Side Request Forgery (SSRF) <br>
**Week 11-12:** Server-Side Template Injection (SSTI) & XML External Entity (XXE) Injection <br>
**Week 13:** Review, Practice, Seek Mentorship, & Take Next Steps <br><br>

I will try to find free resources for each major section based on the 4 predominant learning styles. Many people need to utilize a mixture of learning styles to grasp concepts. Feel free to work your way through everything provided or to go through it until you feel comfortable discussing the topic in an interview or with peers. <br>
The 4 types are: <br>
**Visual** - learning via diagrams, pictures, charts, notes with different spatial arrangements or colors<br>
**Auditory** - learning via active listening<br>
**Read/Write** - learning via reading and writing<br>
**Kinesthetic** - interactive learning, learning by doing<br>

<br><br>

## **Before you Begin**
- Set up an account with PortSwigger <br>
https://portswigger.net/web-security
- Set up Juice Shop <br>
https://pwning.owasp-juice.shop
- Set up a TryHackMe account (affiliate link) <br>
https://tryhackme.com/signup?referrer=5fc50abdccbc930779bcc40e
- Choose a note-taking app (I use OneNote & gitbook, personally)
<br><br>
Optional:
- Set up a Quizlet account <br>
https://quizlet.com <br><br><br>


## Informational  
I have curated a group of diverse YouTube channels and personalities to optimize the learning experience. I suggest you identify your preferred learning style, espectially as it comes to auditory and visual, and seek out the type of learning that you get the most from. This plan will heavily benefit those who are mulitmodal learners, or those that learn best by a multitude of styles. <br><br>

Okay onto the good stuff!


<br><br>
## Plan & Schedule 

### **Week 1: Web Basics and Vocabulary** <br>
*Day 1-2: Introduction to Web & Web App Basics*
- Auditory
   - The "Web Demystified" series from Mozilla Hacks: https://www.youtube.com/playlist?list=PLo3w8EB99pqLEopnunz-dOOBJ8t-Wgt2g
- Read/Write
   - Read & take notes: https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/How_the_Web_works
   - Read & take notes: https://rinaarts.com/the-absolute-beginners-guide-to-web-applications/
   - Make and practice with 10-20 physical or digital flashcards, focusing on vocab and key concepts
- Visual
   - Look up image searches like "website diagram" or "web basics diagram", find a few that from trusted sources and make your own in your notes. 
- Kinesthetic
   - TryHackMe rooms "DNS in Detail" and "HTTP in Detail": https://tryhackme.com/room/dnsindetail & https://tryhackme.com/room/httpindetail

*Day 3-4: Understand Web Application Architecture and Components*
- Auditory
   - ForrestKnight's "Everything You NEED to Know About WEB APP Architecture": https://www.youtube.com/watch?v=sDlCSIDwpDs
- Read/Write
   - Read & take notes: https://docs.oracle.com/cd/E13222_01/wls/docs81/webapp/basics.html
   - Make and practice with 10-20 physical or digital flashcards, focusing on vocab and key concepts
- Visual
   - Look up image searches like "web app architecture", find a few that from trusted sources and make your own in your notes.
- Kinesthetic
   - Reach through this article and create a venn diagram for your notes that details websites vs web applications: https://www.freecodecamp.org/news/difference-between-a-website-and-a-web-application/

*Day 5-6: Learn About HTTP Methods, Status codes, and Headers.*
- Auditory
   - Hackersploit's "Web App Penetration Testing - Introduction To HTTP" : https://www.youtube.com/watch?v=TvRyJmPjcbw
- Read/Write
   - Read & take notes: https://www.freecodecamp.org/news/secure-your-web-application-with-these-http-headers-fd66e0367628/
   - Read & take notes: https://developer.mozilla.org/en-US/docs/Web/HTTP/Status
   - Make and practice with 10-20 physical or digital flashcards, focusing on vocab and key concepts
- Visual
   - INPUT
- Kinesthetic
   - INPUT

*Day 7: Familiarize yourself with common web-related terms and concepts.*
- Go through your flashcards from the week, seek out other similar flash card decks so you can add missing terms to your own.
- Finish up any notes from the week. 
- Work on any optional rooms/boxes as seen below. 
<br>

Optional - Subscription Needed:
- TryHackMe Pre Security Path, Finish "How The Web Works": https://tryhackme.com/paths
- "How websites work" and "HTTP in detail" on TryHackMe. 
<br>

Final Mentions: <br>
This three part series is great - if you want to solidify your knowledge, make your way through these and take notes along the way. Don't forget to use talk to speech if you prefer auditory.
- Part 1: https://www.freecodecamp.org/news/how-the-web-works-a-primer-for-newcomers-to-web-development-or-anyone-really-b4584e63585c/
- Part 2: https://www.freecodecamp.org/news/how-the-web-works-part-ii-client-server-model-the-structure-of-a-web-application-735b4b6d76e3/
- Part 3: https://www.freecodecamp.org/news/how-the-web-works-part-iii-http-rest-e61bc50fa0a/

<br><br>
### **Week 2: SQL Injections** <br>
*Day 8-9: Introduction to SQL injection*
- Auditory
   - Professor Messer's Explanation SQL Injection here: https://www.youtube.com/watch?v=H0IN5Ok7tZk
- Read/Write
   - Read & take notes: https://portswigger.net/web-security/sql-injection
   - Read & take notes: https://owasp.org/www-community/attacks/SQL_Injection
   - Make and practice with 10-20 physical or digital flashcards, focusing on vocab and key concepts
- Visual
  - Understanding Components of a Table, recreate diagrams as needed: https://www.w3resource.com/sql/sql-basic/the-components-of-a-table.php 
- Kinesthetic
  - Complete both Portswigger Apprentice labs: https://portswigger.net/web-security/all-labs#sql-injection
    - Part of Kinesthetic is watching someone work and mimicking. My favorite online teacher for PortSwigger labs is Rana Khalil (https://www.youtube.com/@RanaKhalil101)
  - TryHackMe Rooms (free): https://tryhackme.com/room/sqlilab AND/OR https://tryhackme.com/room/sqlinjectionlm <br><br>

*Day 10-11: Types of SQL injection attacks*<br>
   - Auditory
      - 4 Types of SQL Injection by Bert Wagner: https://www.youtube.com/watch?v=UMJV3OpjsoM
      - Blind SQL Injection Attacks Made Easy: https://www.youtube.com/watch?v=j-fLh_WNg7k
   - Read/Write
      - Read & take notes - High Level Review: https://www.geeksforgeeks.org/types-of-sql-injection-sqli/
      - Read & take notes - Union: https://portswigger.net/web-security/sql-injection/union-attacks
      - Read & take notes - Blind: https://portswigger.net/web-security/sql-injection/blind
      - Make and practice with 10-20 physical or digital flashcards, focusing on vocab and key concepts
   - Visual
      - Draw diagrams for yourself of each type you learn about in the material below. If possible, partner with a mentor to ensure understanding.
   - Kinesthetic
      - Complete any Portswigger Practitioner labs with Union or Blind in the lab name that you can: https://portswigger.net/web-security/all-labs#sql-injection
      - Learn about SQLMap by finishing this TryHackMe room (free): https://tryhackme.com/room/sqlmap <br><br>

*Day 12-13: Preventive measures and best practices*<br>
   - Auditory
      - Catch Rana Khalil's video, focusing specifically on the "How to Prevent" section: https://www.youtube.com/watch?v=1nJgupaUPEQ
   - Read/Write
      - Read & take notes: https://cheatsheetseries.owasp.org/cheatsheets/SQL_Injection_Prevention_Cheat_Sheet.html
      - Read & take notes: https://portswigger.net/web-security/sql-injection#how-to-prevent-sql-injection
      - Read to understand the "Validate All Input" section found here: https://learn.microsoft.com/en-us/sql/relational-databases/security/sql-injection?view=sql-server-ver16
      - Make and practice with 10-20 physical or digital flashcards, focusing on vocab and key concepts
   - Visual
      - Take notes on the Synk's document here, changing up hilighting or even drawing your own diagrams: https://foojay.io/today/8-best-practices-to-prevent-sql-injection-attacks/
   - Kinesthetic
      - INPUT

*Day 14: Hands-on SQL Injection exercises*<br>
   - Kinesthetic
      - TryHackMe Rooms: https://tryhackme.com/room/sqhell AND/OR https://tryhackme.com/room/prioritise
      - Review all flashcards created through the first week. Here's the deck I created: https://quizlet.com/814910147/sql-injections-flash-cards/?i=4yncp7&x=1jqt
<br>
Optional - Subscription Needed: 
- HacktheBox's Spybug: https://app.hackthebox.com/challenges/Spybug

<br><br>

### **Week 3: XSS Attacks** <br>
*Day 11-12: Understanding Cross-Site Scripting (XSS) vulnerabilities*
- Auditory
   -  Catch HackerSploit's video: https://www.youtube.com/watch?v=SHmQ3sQFeLE
- Read/Write
   - Read & take notes: https://portswigger.net/web-security/cross-site-scripting
   - Read through top XSS bug bounty reports: https://github.com/reddelexc/hackerone-reports/blob/master/tops_by_bug_type/TOPXSS.md
   - Make and practice with 10-20 physical or digital flashcards, focusing on vocab and key concepts
- Visual
   - This blog has some good visuals for several XSS attacks: https://dev.to/maleta/cors-xss-and-csrf-with-examples-in-10-minutes-35k3
   - Watch the Computerphile guys explain verbally and by drawing out a xss attack: https://www.youtube.com/watch?v=L5l9lSnNMxg&list=RDLVL5l9lSnNMxg&start_radio=1&rv=L5l9lSnNMxg&t=33
   - The Lightboard Lesson series is awesome to watch through, here's the XSS one: https://www.youtube.com/watch?v=IuzU4y-UjLw
- Kinesthetic
   - TryHackMe room MD2PDF has a XSS vulnerability, can you get the flag? https://tryhackme.com/hacktivities?tab=search&page=1&free=all&order=most-popular&difficulty=all&type=all&searchTxt=xss
   

*Day 13-14: Reflected, Stored, and DOM-based XSS attacks* <br>
- Auditory
   - Although there are also some diagrams on LiveOverflow's video on XSS you can easily just listen to this video if you want: https://www.youtube.com/watch?v=mKAWpFdVcPY
- Read/Write
   - Read & take notes on the Reflected, Stored, and DOM-based XSS attacks on PortSwigger: https://portswigger.net/web-security/cross-site-scripting/reflected
   - Make and practice with 10-20 physical or digital flashcards, focusing on vocab and key concepts
- Visual
   - PwnFunction on YouTube draws and provides graphics as they teach, Reflected XSS is at 5.41, Dom is at 7.30: https://www.youtube.com/watch?v=EoaDgUgS6QA
- Kinesthetic
   - Complete all Portswigger Apprentice labs: https://portswigger.net/web-security/all-labs#cross-site-scripting <br><br>
   
*Day 15-16: Mitigation techniques and secure coding practices*<br>
- Auditory
   - Take a break and listen in to how Samy Kamkar took down Myspace with a xss attack with a worm: https://www.youtube.com/watch?v=DtnuaHl378M
- Read/Write
   - Read & take notes: https://cheatsheetseries.owasp.org/cheatsheets/Cross_Site_Scripting_Prevention_Cheat_Sheet.html
   - Make and practice with 10-20 physical or digital flashcards, focusing on vocab and key concepts
- Visual
   - Web Dev Simplified on YouTube explains how to correct a basic XSS attack: https://www.youtube.com/watch?v=ns1LX6mEvyM
   - Academind takes it some steps further by attacking and editing code for several xss attacks: https://www.youtube.com/watch?v=oEFPFc36weY
- Kinesthetic
   - Review the section "How to prevent XSS attacks", utilizing AI or a mentor to write weak and strong code: https://www.wordfence.com/learn/how-to-prevent-cross-site-scripting-attacks/ <br><br>

*Day 17-20: Hands-on XSS exploitation exercises* <br>
- Kinesthetic
   - Play the XSS Game: https://xss-game.appspot.com
   - Review all flashcards created through these first two weeks 
<br>   
Optional - Subscription Needed:
   - TryHackMe paid $ room Cross-site Scripting might also be a good choice if you pay for the service: https://tryhackme.com/room/xss 
   - Hack the Box paid $ box Cross-site Scripting might also be a good choice if you pay for the service: https://academy.hackthebox.com/course/preview/cross-site-scripting-xss <br><br>

<br><br>


### **Week 4: Authentication Attacks** <br>


### **Week 5: Access Control Vulnerabilities** <br>
*Day 24-27: Introduction to Access Control flaws, Insecure Direct Object References, IDOR*<br>
- Visual 
*Day 27-30: Role-based access control and privilege escalation*<br>
*Day 30-33: Implementing proper access controls*<br>
*Day 33-36: Test and practice identifying access control issues*<br>
<br><br>

### **Week 6: Business Logic**<br>
*Day 36-39: Understanding Business Logic vulnerabilities*<br>
*Day 39-42: Identifying and exploiting logic flaws*<br>
*Day 42-45: Safeguarding business logic and handling sensitive information*<br>
*Day 45-48: Analyzing and avoiding information disclosure risks*<br>
<br><br>

### **Week 7: Information Disclosure**<br>

### **Week 8: File Upload Vulnerabilities**<br>
*Day 48-51: Exploring File Upload vulnerabilities and potential exploits*<br>
*Day 51-54: Best practices for secure file uploads*<br>
*Day 54-57: Introduction to Server-Side Request Forgery*<br>
*Day 57-60: Detecting and preventing SSRF attacks*<br>
<br><br>

### **Week 9: SSRF**<br>

### **Week 10: SSTI**<br>
*Day 60-63: Understanding Server-Side Template Injection (SSTI) vulnerabilities*<br>
*Day 63-66: Mitigation strategies and secure coding techniques*<br>
*Day 66-69: Introduction to XML External Entity (XXE) Injection*<br>
*Day 69-72: Preventing XXE attacks and staying secure*<br>
<br><br>

### **Week 11: XML External Entity (XXE) Injection**<br>

### **Week 12: OWASP Top Ten & a CTF**<br>
- Work through Juice Shop the entire week: https://pwning.owasp-juice.shop/part2/injection.html

### **Week 13: Review & Practice** <br>
*Day 72-77: Review all topics covered in the past weeks*
- Review all flash cards created, find more resources for any topic you do not understand  <br><br>

*Day 77-80: Practice on realistic web app pentesting scenarios*
- Finish any of the labs from the weeks prior that you have not completed (PortSwigger, Juice Shop, THM, HTB) <br><br>

*Day 80-83: Seek guidance or mentorship from experienced pentesters if possible*
- Ask clarifying questions on LinkedIn posts you come across discussing the methods learned
- Engage with others in Discord servers (I run https://discord.gg/thersc but an awesome list of other servers can be found here https://github.com/INIT6Source/Hacker_Discords) <br><br>

*Day 83-90: Continue hands-on practice, explore real-world applications, and attend webinars or workshops to deepen understanding*
- Take a go at Damn Vulnerable Web Application (DVWA) or OWASP WebGoat
- Attend several web application webcasts, prepare some possible questions for the presenter
- Explore some real bug bounty programs to see what you can find, write reports on any finding discovered

<br>
<br><br>


<br><br>
# Extra Resources

If you got here after 90 days - CONGRATS!!!! What did you learn about your learning style? What was the best resource you found on your own? Take some time to reflect and celebrate a win - you deserve it. <br>

Here's some more stuff :D

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

<br><br>
If this helped you get going on your webapp pentesting journey, I want to know! Please feel free to add or tag me - https://www.linkedin.com/in/angsec/ <br>
If you got a ton out of this and want to buy me a coffee, I won't say no :D 
https://ko-fi.com/d1r7b46 <br>
