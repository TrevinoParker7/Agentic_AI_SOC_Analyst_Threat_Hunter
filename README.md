# 🔥(POC) Demo of An Unpopular Opinion: AI + SOC Analysts

> **AI will replace bad SOC Analysts, not good ones.**

I just built an **Agentic AI SOC Analyst / Threat Hunter** that does hours of manual work in minutes.
It can:

* 🔍 Hunt threats
* ⚡ Prioritize intelligently
* 📝 Investigate + document findings

All **faster than any junior analyst I’ve ever seen**.

---

## ❓ Does this mean SOC Analysts are obsolete?

❌ **No.**
But it does mean the days of “click-next analysts” are numbered.

👉 The future SOC team will be **human + AI**:

* 🤖 **AI handles**: noise, repetition, speed
* 🧠 **Humans handle**: intuition, creativity, strategy

---

## 💥 The Controversial Part

* Companies won’t need as many entry-level analysts — **AI will fill that gap**.
* The analysts who thrive will be those who **leverage AI as a partner, not compete with it**.

---

## 🎥 Demo

I even made a short demo video of my Agentic AI in action — doing the work *with me*, not *for me*.

---

## 💭 What do you think?

* Is AI going to be the **end of SOC analyst jobs**?
* Or is it the **biggest upgrade our industry has ever seen**?

---

### 🔗 Tags

Youtube Video: [https://www.youtube.com/watch?v=vFuM--0H3qE](https://www.youtube.com/watch?v=vFuM--0H3qE)

---

# 🛡️ MITRE ATT\&CK Walkthrough with Explanations

I will go thru the Full MITRE ATT\&CK to see what we can find.

---

## 🔎 Reconnaissance

> **What it is:** Adversaries gather information about a target before launching an attack. This could include scanning networks, scraping employee info, or probing public-facing systems.
> **Why it matters:** Stopping recon early can block attackers before they even enter your environment.

<img width="3744" height="1828" alt="Screenshot 2025-08-30 214330" src="https://github.com/user-attachments/assets/53569b1c-2693-4639-8d04-103186971f23" />  

I will be using VS Code and Python and ChatGPT 5 Nano.

<img width="3834" height="2281" alt="Screenshot 2025-08-30 205212" src="https://github.com/user-attachments/assets/b0bc3b63-7aa1-427a-9814-aa7c653615ef" />  

We will start by running the `main.py` by clicking run, and begin the Threat Hunt looking for the first MITRE ATT\&CK tactic: Reconnaissance.

<img width="3837" height="2189" alt="Screenshot 2025-08-30 210508" src="https://github.com/user-attachments/assets/ffa6597e-8b21-4832-a346-c2121f0b9a8f" />  
<img width="3839" height="2210" alt="Screenshot 2025-08-30 210550" src="https://github.com/user-attachments/assets/2806766a-9496-477d-a024-70818b52afa7" />  

---

## 🛠️ Resource Development

> **What it is:** Attackers set up the tools and infrastructure they’ll need for the attack — domains, servers, stolen credentials, or malware.
> **Why it matters:** Catching this can reveal attack prep before the first intrusion attempt.

<img width="3778" height="2203" alt="Screenshot 2025-08-30 213339" src="https://github.com/user-attachments/assets/326571d3-7622-41a0-a9a8-180302d3dbe9" />  
<img width="3819" height="2232" alt="Screenshot 2025-08-30 213719" src="https://github.com/user-attachments/assets/8a9518c8-efbb-42fb-96fd-9e441b16c6b6" />  
<img width="3835" height="2196" alt="Screenshot 2025-08-30 213831" src="https://github.com/user-attachments/assets/c472c931-7b65-495c-9baa-f749f4b3989f" />  

---

## 🚪 Initial Access

> **What it is:** The attacker’s first foothold inside your environment. This often happens via phishing, exploiting public apps, or using stolen credentials.
> **Why it matters:** If you stop them here, the attack fails before it even starts.

<img width="3576" height="2275" alt="Screenshot 2025-09-03 123213" src="https://github.com/user-attachments/assets/33502214-0d2d-4082-8ab9-2ce5975194ca" />  
<img width="3596" height="2233" alt="Screenshot 2025-09-03 123437" src="https://github.com/user-attachments/assets/15606200-f3c2-4acc-9000-ef847a798597" />  
<img width="2862" height="435" alt="Screenshot 2025-09-03 123805" src="https://github.com/user-attachments/assets/48829351-0e08-42cc-be16-3ac9213e01db" />  

---

## ⚡ Execution

> **What it is:** Running malicious code in your environment (e.g., PowerShell, macros, scripts).
> **Why it matters:** This is where malware “goes live.” Detecting execution attempts gives defenders a chance to cut it off.

<img width="3085" height="1048" alt="Screenshot 2025-09-03 153724" src="https://github.com/user-attachments/assets/0aaa8e7d-f9c5-4adf-abc9-00beac8d11e3" />  
<img width="3073" height="1416" alt="Screenshot 2025-09-03 153748" src="https://github.com/user-attachments/assets/b3364318-06cf-4b27-99c0-ce59c77683e6" />  
<img width="3107" height="1746" alt="Screenshot 2025-09-03 153806" src="https://github.com/user-attachments/assets/866ae12c-d14f-45b6-8910-ef06fc06c190" />  

---

## 🔄 Persistence

> **What it is:** Techniques that let attackers maintain long-term access (e.g., registry run keys, scheduled tasks, web shells).
> **Why it matters:** Without persistence, attackers lose access once a machine is rebooted or patched.

<img width="2284" height="1020" alt="Screenshot 2025-09-03 154625" src="https://github.com/user-attachments/assets/566768b7-d269-40a4-89c4-99ef6e5d18dd" />  
<img width="3082" height="1350" alt="Screenshot 2025-09-03 154708" src="https://github.com/user-attachments/assets/6cb43d4a-5f30-4336-a804-2dfc9b90ff98" />  
<img width="2453" height="1281" alt="Screenshot 2025-09-03 154728" src="https://github.com/user-attachments/assets/b2185e56-9463-4dd6-81ee-e19602958f33" />  
<img width="3153" height="1347" alt="Screenshot 2025-09-03 154745" src="https://github.com/user-attachments/assets/8d0e9afa-44cb-44fa-bc19-e0e08247a96a" />  
<img width="3127" height="1312" alt="Screenshot 2025-09-03 154800" src="https://github.com/user-attachments/assets/7b5cede2-178d-4ce8-a124-ce16a7f3db14" />  

---

## 📈 Privilege Escalation

> **What it is:** Attackers try to gain higher-level permissions, often moving from a user account to admin/system.
> **Why it matters:** Higher privileges = more control, stealth, and damage potential.

<img width="1962" height="1022" alt="Screenshot 2025-09-03 161640" src="https://github.com/user-attachments/assets/ffa2140b-1021-40a9-a2a7-706f769aa4dd" />  
<img width="2509" height="1513" alt="Screenshot 2025-09-03 161719" src="https://github.com/user-attachments/assets/d6efc2a2-332d-4c3f-a9f7-114cce3024d9" />  

---

## 🕵️ Defense Evasion

> **What it is:** Methods to avoid detection (disabling security tools, obfuscating code, deleting logs).
> **Why it matters:** If attackers can hide, they can operate longer and cause more damage.

<img width="3089" height="1033" alt="Screenshot 2025-09-03 165537" src="https://github.com/user-attachments/assets/666b0485-eb67-4925-b4d0-917b8cfac77c" />

<img width="3101" height="1531" alt="Screenshot 2025-09-03 165602" src="https://github.com/user-attachments/assets/d2396fd3-69e2-4a05-9fc8-9d6235e794e2" />

<img width="3113" height="1655" alt="Screenshot 2025-09-03 165618" src="https://github.com/user-attachments/assets/50a46908-976d-4a8b-ba18-5e798320ba59" />

<img width="3064" height="1431" alt="Screenshot 2025-09-03 165633" src="https://github.com/user-attachments/assets/b7b6c3a3-a789-4a3f-bab9-66dd25679830" />


---

## 🔑 Credential Access

> **What it is:** Stealing usernames, passwords, tokens, or hashes.
> **Why it matters:** With valid creds, attackers look like normal users — making detection harder.

<img width="2372" height="1069" alt="Screenshot 2025-09-03 170709" src="https://github.com/user-attachments/assets/b176638f-6437-43df-beba-1930f6d955b4" />



<img width="3094" height="1820" alt="Screenshot 2025-09-03 170727" src="https://github.com/user-attachments/assets/d23e5b73-e862-4511-8a0d-9fe88c10ddeb" />


---

## 🗺️ Discovery

> **What it is:** Mapping the environment — users, network shares, security tools, domains.
> **Why it matters:** Recon inside the network lets attackers plan lateral movement.

---

## 🔄 Lateral Movement

> **What it is:** Moving between systems to expand access (e.g., RDP, pass-the-hash, exploiting trust).
> **Why it matters:** It’s how one compromised machine becomes a full network breach.

---

## 📥 Collection

> **What it is:** Gathering data of value (screenshots, files, databases, keystrokes).
> **Why it matters:** This is the staging ground before exfiltration.

---

## 🌐 Command and Control (C2)

> **What it is:** Attackers establish communication channels to control compromised systems.
> **Why it matters:** Detecting C2 traffic can cut the puppet strings.

---

## 📤 Exfiltration

> **What it is:** Stealing data out of the environment (e.g., over HTTP, cloud storage, encrypted channels).
> **Why it matters:** Prevents data loss, IP theft, and compliance nightmares.

---

## 💣 Impact

> **What it is:** Final stage — ransomware, destruction, defacement, encryption.
> **Why it matters:** This is where business operations break down.

