# Op-Shadow-Trace

# 🕵️ Operation Shadow Trace — Progress Report

## 🎯 Objective
Infiltrate a malicious clone of the PClub website at [infosec.pclub.in](https://infosec.pclub.in) and recover **6 hidden flags** in the format `PClub{...}`. The challenge involves exploiting OSINT techniques, analyzing hacker mistakes, and solving cryptographic puzzles.

---

## ✅ Flag 1 — *Found!*

### 🔍 Tracking the Careless Hacker

> “The second hacker, however, was far more careless. Driven by ego or pure inexperience, he posted a new blog under his real name…”

From **Blog 2**, I identified the careless hacker as **Kalpit Lal Rama**.

---

### 🧠 OSINT Trail

1. **LinkedIn Search**  
   - Searched "Kalpit Lal Rama"  
   - Found a LinkedIn profile.

2. **X (formerly Twitter)**  
   - From LinkedIn, traced to his **X.com (Twitter)** account.

3. **Reddit Clue**  
   - From Twitter, found his **Reddit** account.  
   - Discovered a **set of numbers** in one of his Reddit posts.

---

### 🧮 Decoding the Numbers

Tried various base encodings on the number sequence:

- Base64  
- Base58  
- Base36 / Base62  
- Decimal to ASCII  
- Unicode  

Eventually led to a link to his **Instagram** profile.

---

### 📸 Instagram Discovery

- On his **Instagram Highlights**, found a **Wikipedia page**.
- The page had a **suspicious caption** suggesting tampering.
- Visited the Wikipedia link and checked the **edit history**.

---

### 🏁 Flag 1 Located!

Inside the **Wikipedia edit logs**, found:

PClub{idk_how_this_got_typed}

### 🎉 Bonus Flag

Also found this humorous hidden reward:

TechSprint{I_think_we_have_a_osint_god_among_us!}

---

## 🔓 Unlocked: 2 More Challenges

After Flag 1, the site revealed **2 more challenges**.

---

## 🧪 Challenge 1 — In Progress

- Reached a **ciphertext** that appears to be dynamically generated.
- It seems to pad and transform the text using something like:

PClub{Fake_Flag}


- Couldn’t reverse the transformation completely yet.
- Still investigating the underlying cipher or padding logic.

---

## 📌 Summary of Progress

| Status         | Details                                      |
|----------------|----------------------------------------------|
| ✅ Flag 1       | `PClub{idk_how_this_got_typed}`              |
| 🎉 Bonus Flag   | `TechSprint{I_think_we_have_a_osint_god_among_us!}` |
| 🧩 Challenge 1  | Ciphertext with padded fake flag (incomplete) |
| 🔓 More to Explore | 2 additional unlocked challenges            |

---

## 📈 Takeaways

- OSINT works wonders — from LinkedIn to Instagram to Wikipedia!
- Hackers often leave unintentional breadcrumbs.
- Exploring edit histories and metadata is crucial.
- Never trust the first flag you find — **it could be fake**.

---

## ⏭️ Next Steps

- Solve the cipher in Challenge 1
- Attempt Challenge 2
