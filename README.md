# 101 Labs – IP Subnetting Mastery Tracker

This repository documents my hands-on mastery of **IP subnetting** using the book:

> **101 Labs – IP Subnetting** by Paul Browning (101labs.net)

The goal of this repository is to demonstrate **real, repeatable subnetting skill** suitable for:

* CCNA-level proficiency
* Technical interviews
* Real-world network engineering work

This is not a completion checklist. It is a **mastery tracker**.

---

## How Mastery Is Defined

A lab is considered **mastered** only when all of the following are true:

* ✅ Correct answer on the **first attempt**
* ✅ Completed **without notes or tools**
* ✅ Completed within the **time target** for that lab category
* ✅ Can be repeated correctly **7+ days later**
* ✅ Can be explained verbally

Extra calculations are intentionally avoided unless the lab explicitly asks for them.

---

## Time Targets

| Lab Type                      | Target Time  |
| ----------------------------- | ------------ |
| Basic subnet identification   | ≤ 60 seconds |
| CIDR & block size recognition | ≤ 45 seconds |
| VLSM design labs              | ≤ 2 minutes  |
| Mixed / exam-style problems   | ≤ 90 seconds |

---

## Mastery Tracking Table

> This table is updated as labs are completed and retested.

| Lab # | Topic                   | CIDR | Block Size | Correct Subnet     | Time   | First Attempt | Retested | Mastered | Notes |
| ----- | ----------------------- | ---- | ---------- | ------------------ | ------ | ------------- | -------- | -------- | ----- |
| 1     | Basic Class C Subnet ID | /26  | 64         | 192.168.1.0/26     | 30 sec | Yes           | Yes      | Yes      | Initial attempt used cheat sheet; retested successfully without it |
| 2     | Basic Class C Subnet ID | /26  | 64         | 192.168.1.64/26    | 30 sec | Yes           | Yes      | Yes      | Retested without cheat sheet and answered confidently |
| Review | Retention Check (/26–/28) | /26 /27 /28 | 64 / 32 / 16 | Correctly identified networks | ~15 min | Yes | N/A | Yes | No cheat sheet used; validated retention and network vs broadcast understanding |
| 3 | Subnet Identification | /27 | 32 | 192.168.1.96/27   | 1 min  | Yes | No | Yes | Used jump method, block size recognized quickly |
| 4 | Subnet Identification | /28 | 16 | 192.168.1.64/28   | <1 min | Yes | No | Yes | Counted subnet jumps aloud, no cheat sheet |
| 5 | Subnet Identification | /28 | 16 | 192.168.1.128/28  | <1 min | Yes | No | Yes | Improved speed identifying correct subnet |
| 6 | Subnet Identification | /28 | 16 | 192.168.1.208/28  | 1 min  | Yes | No | Yes | Jump method, no cheat sheet |
| 7 | Subnet Identification | /28 | 16 | 192.168.1.64/28   | <1 min | Yes | No | Yes | Identified subnet boundaries confidently |
| 8 | Subnet Identification | /29 | 8  | 200.100.100.248/29| 2 min  | Yes | No | Yes | Step-by-step reasoning, no cheat sheet |





## Lab Documentation Structure

Each lab has its own write-up using this format:

```
/labs
  lab-01-subnetting-192.168.1.1-26.md
  lab-02-...
```

Each lab write-up includes:

* Given information
* Subnetting method used
* Final answer
* Brief reflection (mistakes, speed, confidence)

---

## Retesting Policy

Subnetting skill fades without repetition.

* Labs are retested after **7 days**
* Failed retests reset mastery status
* Notes are kept on mistake patterns

---

## Why This Repository Exists

Subnetting is a **core networking skill**, not a trivia topic.

This repository exists to show:

* Discipline
* Accuracy
* Speed
* Retention over time

It reflects how real network engineers build and maintain technical competence.

---

## Tools Used

* Pen and paper (primary)
* Mental math
* Markdown documentation
* GitHub for versioned progress tracking

---

*Last updated: {{DATE}}*

