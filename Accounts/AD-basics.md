# 👩🏻‍💻 User Accounts & Active Directory — *Draft Notes*

> *Currently expanding my hands-on experience with Active Directory — documenting concepts as I learn them. 🚧

## 🧩 What’s Covered (Planned)
- How to reset a locked user account.
- How to add a computer to a domain ✅ *(practiced during internship)*
- How to check user group membership.
- How to create or disable accounts properly.
- Best practices for password resets & account security.

## 🧠 Current Knowledge
From observation and theory so far:
💻 **Joined a workstation to the hospital’s domain**
- Steps: This PC → Properties → Computer Name → Domain → entered domain credentials → “Welcome to the domain”.
- Purpose: connect the device to centralized authentication via Active Directory.

- Account lookups are done using **Active Directory Users and Computers (ADUC)**.  
- Password resets and unlocking are done through **right-click → Reset Password / Unlock Account**.  
- Computer accounts must match the correct **OU (Organizational Unit)** before joining.  
- Naming conventions and permissions matter — especially for medical or high-security environments.  

## 📅 To-Do
- Document the full step-by-step process after real-world practice.
- Add screenshots and command examples (e.g., `net user`, `whoami /groups`).
- Cross-reference this with network and printer troubleshooting cases.

---

> “Document even the things you don’t fully know yet — that’s how they become yours.” 
