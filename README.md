# CESA: Chebyshev-Polynomials-based Efficient and Secure Access Authentication Scheme for 5G Networks

This repository contains the formal verification models of **CESA**, a lightweight and secure access authentication scheme designed for User Equipment (UE) and Massive Machine-Type Communication (mMTC) devices in 5G networks.

Formal security validation was performed using **ProVerif** and **Scyther** under the Dolev–Yao adversary model.

---

## 📄 Manuscript Information

**Title**  
CESA: Chebyshev-Polynomials-based Efficient and Secure Access Authentication Scheme for both User Equipment and Massive Machine-Type-Communication Devices over 5G Networks

**Journal**  
IEEE Internet of Things Journal  
30 January 2025

**Authors**
- Naryun Woo  
- Taewoong Kang  
- Jihyeon Ryu (Corresponding Author)

**Affiliation**  
School of Computer and Information Engineering  
Kwangwoon University  
Seoul, Republic of Korea  

---

## 🔐 Research Overview

CESA is a lightweight authentication and key agreement protocol for 5G networks that:

- Utilizes **extended Chebyshev chaotic maps**
- Supports both **UE and massive MTC devices**
- Achieves mutual authentication and secure session key agreement
- Ensures identity anonymity and untraceability
- Provides Perfect Forward/Backward Secrecy (PFS/PBS)

Compared to existing schemes, CESA achieves:

- 97.38% improvement in computational efficiency
- 67.36% improvement in bandwidth efficiency
- 72.71% improvement in signaling efficiency
- 99.45% improvement in transmission efficiency
- 48.19% improvement in storage efficiency
---

## 📂 Repository Structure
```
proverif/
cesa_model.pv
→ ProVerif specification

scyther/
cesa_model.spdl
→ Scyther specification
```
---

## 🛠 Formal Verification

### ProVerif

Used to verify:
- Mutual authentication
- Session key secrecy
- Correspondence properties
- Identity protection

### Scyther

Used to verify:
- Secret
- Alive
- Weakagree
- Niagree
- Nisynch
- Forward/Backward secrecy

All security claims are verified successfully with no attacks detected within bounded sessions.

Cite (Scyther):  
C. J. F. Cremers, *Scyther: Semantics and Verification of Security Protocols*,  
Ph.D. dissertation, Eindhoven University of Technology, 2006.

---

## 📌 Notes

- This repository contains **formal verification models only**.
- No implementation code is included.
- Models correspond to the security analysis section of the CESA manuscript.

---

## 📬 Contact

For questions regarding the verification models:

📧 mercy1234@kw.ac.kr  

For bug reports or technical discussions, please open a GitHub Issue in this repository.
