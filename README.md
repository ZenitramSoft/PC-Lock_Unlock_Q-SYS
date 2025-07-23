Windows Unlock/Lock Button for Q-SYS

This is a simple but super useful Q-SYS Lua component that lets you unlock or lock a Windows PC from a touch panel.

It’s perfect for meeting room setups or shared computers with generic logins—just tap a button and it types the password for you.

Setup Instructions: Connect a HID Keyboard to your Q-SYS Core. In Q-SYS Designer, name the HID Keyboard and enable Script Access. Enter that name into the Named_Component field. Type your desired password into the Password_Field. Press Unlock or Lock and let it do its thing.

What It Does: Unlock: Sends a wake-up sequence, types the password character by character (including Shift for caps/symbols), and presses Enter. Lock: Sends Win + L to lock the PC. Prevents multiple unlock attempts from overlapping. Works great for shared PCs with generic logins.

Notes: This isn’t meant for high-security environments. If you want to keep it secure, just hide the controls behind an admin menu or PIN-protected page. You can customize it further with LED feedback, status labels, or debug toggles.
