# How I Earned Hall of Fame Recognition from NASA and Other Organizations Through Responsible Disclosure

As a cybersecurity researcher and bug bounty hunter, earning Hall of Fame recognition from NASA and several other organizations has been one of the most rewarding milestones in my journey. Seeing my name publicly acknowledged for helping improve security was not only exciting but also a reminder that ethical hacking can make a real impact.

Many people assume that Hall of Fame recognitions are reserved for elite security researchers with years of experience. However, my experience has shown that persistence, continuous learning, and a structured methodology are often more important than advanced technical skills alone.

<img src="https://raw.githubusercontent.com/dharmstm/article/refs/heads/main/images/nasahof.jpeg" alt="NASA Hall of Fame Recognition">

<p><em>My name listed in NASA's Hall of Fame for responsible vulnerability disclosure.</em></p>

## How I Started

My cybersecurity journey began with a simple curiosity about how websites, applications, and systems work behind the scenes. I spent countless hours learning web application security through platforms such as TryHackMe, Hack The Box, PortSwigger Web Security Academy, and Bugcrowd.

Rather than jumping directly into advanced exploitation techniques, I focused on understanding the fundamentals. I learned how HTTP requests work, how authentication mechanisms function, how sessions are managed, and how common vulnerabilities such as XSS, IDOR, and security misconfigurations occur.

Building a strong foundation allowed me to understand not only how vulnerabilities are discovered but also why they exist in the first place.

As my knowledge grew, I started exploring Vulnerability Disclosure Programs (VDPs) and Bug Bounty Programs. These programs provided a legal and ethical way to apply my skills while helping organizations improve their security posture.

## Discovering NASA's Vulnerability Disclosure Program

While browsing Bugcrowd and researching public vulnerability disclosure programs, I came across NASA's Vulnerability Disclosure Program.

The opportunity immediately caught my attention. NASA is one of the most respected organizations in the world, and the idea of contributing to its security was incredibly motivating.

Before performing any testing, I carefully reviewed the engagement documentation. This included:

* Program Scope
* Out-of-Scope Assets
* Testing Guidelines
* Disclosure Policies
* Vulnerability Rating Taxonomy (VRT)

Many beginners overlook this step and start testing immediately. However, understanding the rules of engagement is critical. Respecting scope boundaries and following responsible disclosure practices are essential parts of ethical hacking.

<img src="https://raw.githubusercontent.com/dharmstm/article/refs/heads/main/images/bugcrowdnasavdppage.png" alt="NASA Hall of Fame Recognition">

## My Methodology

One of the biggest lessons I learned during bug hunting is that success rarely comes from randomly clicking through applications. Instead, I follow a structured methodology whenever I assess a target.

### 1. Reconnaissance

Reconnaissance is often where the majority of my time is spent.

Before searching for vulnerabilities, I try to understand the target's attack surface by identifying:

* Subdomains
* Hidden directories
* Public files
* Historical URLs
* JavaScript endpoints
* APIs
* Technology stacks
* Development or staging environments

The more visibility you gain into a target, the more opportunities you create for discovering security weaknesses.

Many of my successful findings originated from assets that were not part of the primary application but were still accessible and within scope.

### 2. Manual Testing

While automated tools can be useful, I rely heavily on manual testing.

Manual testing allows me to understand business logic, user workflows, and access control mechanisms that scanners often miss.

Some areas I focus on include:

* Broken Access Control
* Information Disclosure
* Insecure Direct Object References (IDOR)
* Cross-Site Scripting (XSS)
* Open Redirects
* Sensitive Data Exposure
* Security Misconfigurations
* Content Spoofing
* Business Logic Issues

One thing I learned early is that many Hall of Fame recognitions come from relatively simple vulnerabilities that others overlook.

You do not always need a critical Remote Code Execution vulnerability. Sometimes a properly documented low- or medium-severity issue can still provide significant value to an organization.

### 3. Creating a Proof of Concept

Finding a vulnerability is only half the work.

The next step is proving its impact.

Whenever I identify a potential issue, I create a clear and reproducible Proof of Concept (PoC).

My reports typically include:

* Vulnerability Summary
* Affected Asset
* Step-by-Step Reproduction
* Impact Assessment
* Supporting Screenshots
* Proof of Concept
* Remediation Recommendations

A well-written report significantly increases the chances of successful triage and acceptance.

## Reporting Through Bugcrowd

After validating my findings, I submitted detailed reports through Bugcrowd.

Writing reports taught me an important lesson: communication skills are just as important as technical skills.

Security teams review hundreds of submissions. Clear explanations, reproducible steps, and concise impact assessments help analysts understand and validate findings quickly.

Each accepted report became another learning experience and another opportunity to improve my skills as a researcher.

## Challenges I Faced

Like every bug bounty hunter, I faced numerous challenges.

Not every report was accepted.

I encountered:

* Duplicate Reports
* Informational Classifications
* Out-of-Scope Findings
* Known Issues
* Low-Impact Reports

Initially, rejections felt discouraging.

However, I eventually realized that every rejected report provided valuable feedback.

Each rejection helped me refine my methodology, improve my understanding of vulnerability impact, and write better reports.

The most successful researchers are not those who never fail—they are the ones who continue learning after failure.

## Why Hall of Fame Recognition Matters

Receiving Hall of Fame recognition was about much more than seeing my name on a webpage.

It represented:

* Real-world cybersecurity impact
* Professional credibility
* Validation of my research efforts
* Continuous learning and improvement
* Contribution to a safer internet

For students and aspiring cybersecurity professionals, Hall of Fame acknowledgments can be powerful additions to portfolios, resumes, and professional profiles.

<img src="https://raw.githubusercontent.com/dharmstm/article/refs/heads/main/images/ultabeautyhof.jpeg" alt="Ulta Beauty Hall of Fame Recognition">

<img src="https://raw.githubusercontent.com/dharmstm/article/refs/heads/main/images/dreamscape.jpeg" alt="Dreamscape Hall of Fame Recognition">

## How Beginners Can Earn Hall of Fame Recognition

If you are just beginning your journey, my advice is simple:

1. Learn the fundamentals thoroughly.
2. Practice on legal training platforms.
3. Understand program scope before testing.
4. Focus on quality rather than quantity.
5. Develop strong reconnaissance skills.
6. Write professional reports.
7. Learn from every rejection.
8. Stay consistent and patient.

Most importantly, remember that ethical hacking is not about attacking systems. It is about helping organizations identify weaknesses before malicious actors can exploit them.

## Final Thoughts

Earning Hall of Fame recognition from NASA and other organizations was not the result of luck or a single breakthrough discovery. It was the result of continuous learning, disciplined reconnaissance, careful testing, and responsible disclosure.

Every accepted report represents an opportunity to make the digital world a little safer while growing as a cybersecurity professional.

If you are passionate about cybersecurity, keep learning, keep practicing, and remain ethical in your approach. Your next valid vulnerability report could be the one that earns you recognition and opens the door to new opportunities.

The journey from a beginner to a recognized security researcher is absolutely possible—and it starts with a single report.
