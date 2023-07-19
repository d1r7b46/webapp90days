# Web App Attack Basics - 90 Days of Education


The below is a plan for self education, inclusive of the following topics:
SQL injection
XSS Attacks
access control vulnerabilities
business logic
information disclosure
file upload vulnerabilities
Server-Side Request Forgery (SSRF)
server-side template injection (SSTI)
XML external entity (XXE) injection

I will try to find learning material for each major section based on the 4 predominant learning styles: Visual, Auditory, Read/Write, and Kinaesthetic.

Visual - learning via diagrams, pictures, charts, notes with different spatial arrangements or colors
Auditory - learning via active listening
Read/Write - learning via reading and writing
Kinaesthetic - interactive learning, learning by doing



**Study Plan: Web App Pentesting Fundamentals**

*Week 1-2: SQL Injection*
1. Day 1-3: Introduction to SQL injection (Concepts and Risks)
   - Visual
      - Understanding Components of a Table: https://www.w3resource.com/sql/sql-basic/the-components-of-a-table.php 
   - Auditory
      - Professor Messer's Explanation here: https://www.youtube.com/watch?v=H0IN5Ok7tZk
   - Read/Write
      - Read & take notes: https://portswigger.net/web-security/sql-injection
      - Read & take notes: https://owasp.org/www-community/attacks/SQL_Injection
      - Make and use 10-20 physical or digital flashcards, focusing on vocab and key concepts
   - Kinaesthetic
      - PortSwigger Labs (APPRENTICE): https://portswigger.net/web-security/sql-injection
         - Part of kinaesthetic is watching someone work and mimicking. My favorite online teacher for PortSwigger labs is Rana Khalil (https://www.youtube.com/@RanaKhalil101)
      - TryHackMe Rooms (free): https://tryhackme.com/room/sqlilab & https://tryhackme.com/room/sqlinjectionlm
3. Day 3-6: Types of SQL injection attacks
   - Visual
      - Draw diagrams for yourself of each type you learn about in the material below. If possible, partner with a mentor to ensure understanding.
   - Auditory
      - 4 Types of SQL Injection by Bert Wagner: https://www.youtube.com/watch?v=UMJV3OpjsoM
   - Read/Write
      - Read & take notes - High Level Review: https://www.geeksforgeeks.org/types-of-sql-injection-sqli/
      - Read & take notes - Union: https://portswigger.net/web-security/sql-injection/union-attacks
      - Read & take notes - Blind: https://portswigger.net/web-security/sql-injection/blind
      - Make and use 10-20 physical or digital flashcards, focusing on vocab and key concepts
   - Kinaesthetic
      - Complete the Injection section of Juice Shop: https://pwning.owasp-juice.shop/part2/injection.html
      - Learn about SQLMap by finishing this TryHackMe room (free): https://tryhackme.com/room/sqlmap
5. Day 6-9: Preventive measures and best practices
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
      - Learn the code in the following, create some code that would be susceptible and seek out: https://bobby-tables.com/plsql
7. Day 9-14: Practice SQL injection on vulnerable web applications and in labs
   - Kinaesthetic
      - TryHackMe Rooms (free): https://tryhackme.com/room/sqhell OR https://tryhackme.com/room/prioritise
      - Complete OWASP WebGoat's SQL Injection section: https://owasp.org/www-project-webgoat/
      - Complete Damn Vulnerable Web Application's section on SQL Injections: https://github.com/digininja/DVWA
      - Review all flashcards created through these first two weeks

*Week 3-4: XSS Attacks*
1. Day 15-18: Understanding Cross-Site Scripting (XSS) vulnerabilities
2. Day 18-21: Reflected, Stored, and DOM-based XSS attacks
3. Day 21-24: Mitigation techniques and secure coding practices
4. Day 24-28: Hands-on XSS exploitation exercises

*Week 5-6: Access Control Vulnerabilities*
1. Day 17-18: Introduction to Access Control flaws (Insecure Direct Object References, IDOR)
2. Day 19-20: Role-based access control and privilege escalation
3. Day 21-22: Implementing proper access controls
4. Day 23-24: Test and practice identifying access control issues

*Week 7-8: Business Logic & Information Disclosure*
1. Day 25-26: Understanding Business Logic vulnerabilities
2. Day 27-28: Identifying and exploiting logic flaws
3. Day 29-30: Safeguarding business logic and handling sensitive information
4. Day 31-32: Analyzing and avoiding information disclosure risks

*Week 9-10: File Upload Vulnerabilities & SSRF*
1. Day 33-34: Exploring File Upload vulnerabilities and potential exploits
2. Day 35-36: Best practices for secure file uploads
3. Day 37-38: Introduction to Server-Side Request Forgery (SSRF)
4. Day 39-40: Detecting and preventing SSRF attacks

*Week 11-12: SSTI & XML External Entity (XXE) Injection*
1. Day 41-42: Understanding Server-Side Template Injection (SSTI) vulnerabilities
2. Day 43-44: Mitigation strategies and secure coding techniques
3. Day 45-46: Introduction to XML External Entity (XXE) Injection
4. Day 47-48: Preventing XXE attacks and staying secure

*Week 13: Review & Practice*
1. Day 49-51: Review all topics covered in the past weeks
2. Day 52-53: Practice on realistic web app pentesting scenarios (e.g., Bug Bounty platforms)
3. Day 54-55: Seek guidance or mentorship from experienced pentesters if possible
4. Day 56-90: Continue hands-on practice, explore real-world applications, and attend webinars or workshops to deepen understanding.

**Tips for Success for those that have ADHD:**
1. Break the study sessions into short, focused blocks with regular breaks to maintain attention.
2. Use interactive learning methods, such as online labs, capture-the-flag (CTF) challenges, and videos.
3. Create a quiet and organized study environment to minimize distractions.
4. Utilize task lists, timers, and study apps to help with time management and focus.
5. Consider joining a study group or finding an accountability partner to stay motivated and engaged.
6. Celebrate achievements and progress throughout the 90 days to boost morale.
