# Daniel's Portfolio
**Course:** Digital Support & Security

### Contents
* [Week 1: About Me](#week-1-about-me)
* [Week 2: How I Solve Problems](#week-2-how-i-solve-problems)
* [Week 3: My Development Environment](#week-3-my-development-area)
* [Week 4: Security, Ethics and Professional Responsibility](#week-4-security-ethics-and-professional-responsibility)
* [Week 5: Industry Inspiration & My Technical Direction](#week-5-industry-inspiration--my-technical-direction)
* [Week 6: Year 1 Reflection](#week-6-year-1-reflection)

---

## Week 1: About Me

### About Me
Hi, I'm Daniel. And I've been into computers since I was really young, and I spend most of my free time learning about different areas of tech. I've got a lot of hands-on experience building, taking apart, and fixing PCs. I know my way around Windows and macOS.

Outside of college, I do a bit of local IT support in my area. Some of which the main jobs I've done include:
* Building custom PCs, fixing broken systems, and doing deep cleans
* Upgrading RAM, installing SSDs, and swapping out CPUs
* Replacing screens and batteries on iPhones and iPads
* Removing viruses and sorting out software issues

### My Strengths & What I'm Currently Doing

**What I'm good at:**
* **Physical Hardware:** I'm really comfortable working hands-on with PC parts and repairs.
* **Asking Questions:** I'm confident in my practical skills, but if I don't know something or I'm unsure, I'm not afraid to ask questions to get it right.

**What I need to improve:**
* **Studying:** Getting better at sitting down and revising theory, not just doing the practical stuff.

### Future Goals
* **This Year:** Focus on improving my study habits.
* **After College:** I want to start a Level 4 apprenticeship and work my way up to a Level 6 Bachelor's degree.
* **Long Term:** Once I've got my degree and experience sorted, I want to move to Erbil, In Kurdistan.

---

## Week 2: How I Solve Problems

### The Challenge
During ESP with Pete, We ran into a weird network issue where I couldn't `ping` my workstation at all, even though I was still able to Remote Desktop (RDC) straight into it without any problems. 

### What We Did to Fix It
Since Remote Desktop was working fine, I knew the connection and IP address were fine, which meant something on the machine was specifically blocking ping requests. 

1. So I logged into the workstation via Remote Desktop.
2. Then I went straight to the **Firewall settings** to check the inbound rules and see what was blocking the connection.
3. After looking through the setup, I found the specific application/rule that was stopping the machine from responding to pings and disabled it so traffic could get through.

### Looking Back at it Now
Checking the firewall worked straight away because I didn't waste time checking cables or resetting the network when I already knew RDC worked. 

The best thing I got was **pattern recognition**. Since I know which firewall rule caused the block, I'll remember it immediately if it happens again. Being able to figure out a solution once and apply that pattern to future problems speeds up my troubleshooting alot.

---

## Week 3: My Development Area

### Tools & Systems I Use
To get my Core 1 & Core 2 and ESP Work, I depend on a few main tools:
* **Microsoft Word & PowerPoint:** I use these for writing up my classwork, and presenting to my class.
* **Cisco Packet Tracer:** I use this for networking labs to build, configure, and test network topologies virtually.

### My Confidence Levels (Most to Least Confident)
1. **Microsoft Word & PowerPoint (High Confidence):** I've used this since i was 10 and am pretty confident in making a powerpoint or writing my classwork down.
3. **Cisco Packet Tracer (Getting There):** I know the basics and can build networks, but I am trying to get better at using.

### How My Setup Helps Me Solve Problems
Having these tools helps me alot, especially for our **ESP (Employer Set Project)** prep. Using **Cisco Packet Tracer** It lets me make/test a whole network in a digital environment and test everything out safely before we actually build or touch anything in real life. If something breaks in Packet Tracer, it's easy to see why and fix it without messing up physical hardware. 

Moving forward, I want to become faster at using Cisco Packet Tracer so I can set up and troubleshoot networks without breaking too much.

---

## Week 4: Security, Ethics and Professional Responsibility

### Case Study: Change Healthcare Cyberattack
A real-world example would be why cybersecurity matters is the **Change Healthcare ransomware attack**. Hackers got into their systems because a remote access portal didn't have Multi-Factor Authentication turned on. 

### The Impact on the People, Companies, and Society
* **What it did to Individuals:** Millions of patients had their private medical and personal data stolen, and many couldn't get their prescriptions or treatments paid for on time because the systems were offline.
* **The aftermath for bussniesses:** Pharmacies, hospitals, and clinics lost alot of money as they couldn't process insurance claims for weeks, while Change Healthcare had to pay billions for damages done to the company.
* **Bigger picture for society:** It showed how one weak thing in a major IT system can stop healthcare across an entire country and cause real-world chaos to regular people.

### The Responsibility in Tech You should take 
When you build or support IT systems, you are responsible for protecting people's data.
Some companies and IT workers can prevent attacks like this by:
* Keeping systems patched and updated.
* Backing up data properly and locking down network access so one hacked account can't take down the whole system.

### Professional Behaviour & Company Values
For me, acting like a real IT professional comes down to how YOU handle yourself on the job:
* **Staying Calm Under Pressure:** When systems break or things get stressful, panicking doesn't fix anything. You have to stay calm and focus on the fix.
* **Getting On With the Work:** Staying quiet, focused, and not talking too much when there is a job to do.
* **Respect & Fairness:** Treating everyone the exact same way as a colleague, no matter who they are, and keeping unhelpful personal thoughts to yourself so the team works well together.

---

## Week 5: Industry Inspiration & My Technical Direction

### Careers I an interested in OR Companies That Interest Me
My main goal in the tech industry is to become an **IT Engineer**. When I'm looking at major companies in my opinon I see **Cisco** and **Oracle** stand out the most because of their hardware, networking gear, and how database/cloud systems run in almost every major business.

### How My Interests Have Grown
Before starting this course, I mostly focused on single PCs and building them, repairing hardware, and fixing simple OS issues. Since starting DSS, I have been more interested in **Networking** and **Windows Server**. Seeing how lots of computers connect together and get managed from a central server is interesting.

### Next Steps for My Technical Skills
As my interest in networking has grown, there are two specific things I want to learn and try figure out next:
* **Making Ethernet Cables:** I want to learn how to properly crimp and wire up RJ45 Ethernet cables.
* **Setting Up Subnets:** Getting confident with IP addresses and subnets so I can properly split up and organise networks.

---

## Week 6: Year 1 Reflection

### Looking Back So Far
I am at my best when doing hands-on work and practical troubleshooting at home. Fixing physical PC hardware, checking firewall rules, or testing setups in Packet Tracer, I like figuring out how systems actually work. Over the few weeks, my interests have grown from just fixing computers to wanting to understand networks with Windows Server 2019.

### What It Means to Be a IT Pro
This year taught me that being an IT Pro isn't just about knowing how to fix a computer. You have to be confident in what you know, make smart but informed guesses when diagnosing a problem, and with also staying calm and respectful with colleagues.

### What I want to promise my self to do for Year 2
* **Grades:** Pass all my exams with **at least a C grade**.
* **Technical:** Learn how to make a subnet, making Ethernet cables, and using Cisco Packet Tracer and Windows Server.
* **Next Step After College:** I will use my grades to try land a **Level 4 Degree Apprenticeship** so I can start working as an IT Engineer.
