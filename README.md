# How to Check Your Windows License Expiry Date
To find out when your Windows license expires, follow these simple steps:
1. Press `Win + R` to open the **Run** dialog.
2. Type `cmd` and hit **Enter**.
3. In the Command Prompt, type:
```
slmgr /xpr
```
4. A window will pop up showing your license status:
- *"This machine is permanently activated"* — you’re good!
- Or an expiry date if it's a temporary license.
> **Tip:** This works on Windows 10 and Windows 11. Use it regularly to avoid surprises.
---