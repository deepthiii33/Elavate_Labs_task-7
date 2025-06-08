# 📝 Detailed Report: Browser Extension Audit

##  Environment
- **OS:** Kali Linux
- **Browser:** Mozilla Firefox
---

##  Extensions I Found

Here's what was installed at the time of the audit:

![Installed Extensions](https://github.com/deepthiii33/Elavate_Labs_task-7/blob/main/screenshots/extensions_list.png)

| Extension        | Did I Install It? | Do I Use It? | Why It's There |
|------------------|-------------------|--------------|----------------|
| **FoxyProxy**     | Yes ✅             | Yes ✅        | I use it with Burp Suite for intercepting browser traffic during testing. |
| **Cookie-Editor** | Yes ✅             | Yes ✅        | Handy for editing cookies and working with sessions when testing web apps. |

---

##  Step by Step process

### 1. Opened Firefox Add-ons Page
I went to `about:addons` in Firefox to see what’s installed.

### 2. Looked Over Each Extension
I checked what each extension does, whether I installed it myself, and if I still use it. Both of these were tools I had added intentionally.

### 3. Checked Permissions
I reviewed what kind of access each extension had. Nothing looked suspicious — they only activate when I use them and don’t run in the background unnecessarily.

### 4. Verified Reviews & Safety
I searched both extensions on Mozilla’s add-ons site. Both have lots of positive reviews and are widely used in the security/dev community.

### 5. Restarted Firefox
After the review, I restarted Firefox to make sure everything ran smoothly — and it did.

---

## Final Decisions

| Extension        | Action | Why I Kept It |
|------------------|--------|----------------|
| **FoxyProxy**     | Kept   | I need it for switching proxy settings when working with Burp Suite. |
| **Cookie-Editor** | Kept   | It’s helpful for testing cookies and session-related behavior in web apps. |

Nothing looked unsafe, so I didn’t remove anything.

---

##  Lessons Learned

- Even legit extensions should be reviewed now and then.
- Firefox gives pretty good control over what an extension can access — I like that it doesn’t just give full access without a warning.
- If you're not using an extension anymore, it’s better to remove it — even if it’s not harmful.
- Tools like these are great for pentesting, but they also need to be managed like any other software.

---

## Conclusion

I didn’t find any suspicious or unnecessary extensions during this check, which is a good sign. Both of the tools I had installed are part of my regular testing workflow.

That said, this was a good reminder to stay aware of what’s installed — it only takes one bad extension to cause serious problems.


