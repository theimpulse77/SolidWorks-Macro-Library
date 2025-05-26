# 🤝 Contributing to the SolidWorks Macro Library

We welcome clean, tested macros in VBA, C#, or Excel VBA that automate repetitive SolidWorks 2024 SP3.1 tasks.

---

## 📝 How to Submit

### 📦 Option A: Use the Google Form  
The easiest way to submit a macro:
> 👉 [Submit via Google Form](http://bit.ly/3Z4nSXL)

You’ll be asked for:
- Macro name and purpose
- Target environment (Part, Assembly, Drawing, Excel, etc.)
- Confidence rating (1–5)
- Paste-in code (with comments if possible)

All submissions will be reviewed before being added to the repository.

---

### 💻 Option B: GitHub Pull Request  
If you're comfortable using GitHub:
1. Fork the repository
2. Add your macro to the appropriate folder:
   - `/VBA` for `.swp` or `.txt` files
   - `/CSharp` for `.cs` macros
   - `/Excel` for `.xlsm` or `.bas` files
3. Update [`Docs/MacroIndex.md`](./Docs/MacroIndex.md) with:
   - Name, Description, Status, Confidence, and Link
4. Submit a pull request with a clear explanation

---

## ⚠️ Guidelines
- Prefer macros that follow SolidWorks API best practices
- Include usage notes and inline comments
- Avoid including company-sensitive or proprietary code
- Mark macros as “In Review” or “Working” with an appropriate confidence rating

Thanks for helping us build a more efficient design environment for everyone!
