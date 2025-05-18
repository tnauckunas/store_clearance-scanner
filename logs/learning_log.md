## Daily Engineering Log

<details>  

<summary> Archive: May 17, 2025</summary>  

**What I Studied:**  
- Completed: *Modern Web Scraping Fundamentals with Python (Udemy)*
- Explored use of Anaconda with Spyder for web scraping

**What I Tried:**
- Attempted to run scraper using Spyder IDE via Anaconda
- Targeted HomeDepot product pages checked against [`HomeDepot robots.txt`](https://www.homedepot.com/robots.txt)

**Issues Faced:**
- Spyder (via Anaconda) failed to support dynamic scraping flow
- `robots.txt` disallows many critical endpoints, limiting feasibility
- Workflow lacks real-time debugging + CLI-friendly operation

**Next Move:**
- Shift to **VS Code**
- Begin learning how to build a **custom Python scraper** that:
  - Ethically bypasses `robots.txt` disallows (only where permitted)
  - Operates within public-facing product endpoints
  - Supports category-based CLI structure

----

**Further Update**

 Realization During Course: Tools Aren’t Enough and They Have to *Fit the Mission*

While going through the first quarter of *Modern Web Scraping Fundamentals (Udemy)*, I hit a critical realization. The tools they were using specifically **Spyder via Anaconda** simply weren’t going to work for what I’m trying to build.

Here’s what happened:  
I tested basic spider scraping methods taught in the course, and quickly noticed that **HomeDepot’s robots.txt actively disallows most of the key routes** I needed.  
Spyder, being structured to respect those boundaries, immediately hit a wall.  
The course continued forward like that wasn’t a problem… but for me, it completely broke the use case.

More importantly, I realized this:  
I’ve been jumping into advanced repo ideas without actually building a foundation I fully control or understand. Every time I do that, I lose momentum, feel lost, and drift into distraction.

Right now, I’m starting completely from zero with Python and build my fundemntals.  
It feels weird to say that, but it’s honest.  
This time though, I’m not learning Python just to learn it.  
I’m learning it because I’ve got a repo to build.  
A working clearance scanner CLI. With real output.

> I’m done studying without a mission.  
> If I study, it’s to build. And if I build, I finish.

Momentum restored.

</details>

---

<details>  

<summary>Archive: May 18, 2025</summary>  

I'm currently going through the Python Bootcamp to reinforce my fundamentals before completing the scanner.

Repo 4 will resume the moment I have full command of:
- CLI scripting
- Web scraping architecture
- File handling
- Argument parsing

In the meantime, active logs are in [`python-mastery`](https://github.com/tnauckunas/dev-grind-vault/blob/83d13a7615bda011d2a9b6c486e051d9bec8fd8d/logs/learning_log.md).

**What I Studied:**   
**What I Tried:** 
**Issues Faced:**   
**Next Move:**   

</details>

---

