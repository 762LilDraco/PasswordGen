# ✨ Password Generator ✨
[Click Me](https://762lildraco.github.io/PasswordGen/)

<span style="color:pink; text-shadow: 0 0 8px hotpink; font-size: 2em; font-weight: bold;">Draco's Password Generator</span>

## 🔐 What This Project Does
This is a **client-side password generator website**. You can choose password length, character sets (uppercase, lowercase, numbers, symbols), and special options like removing ambiguous characters or making the password pronounceable. It then uses the browser’s built-in `crypto.getRandomValues()` function to generate random, secure passwords — **all locally in your browser**. Nothing is sent anywhere.

## 🛠 How It Works
- Written in **pure HTML, CSS, and JavaScript**.
- Uses **cryptographically strong random numbers** from `window.crypto`.
- Options let you adjust password style (length, symbols, ambiguity, pronounceability).
- Displays **entropy bits** as a rough measure of password strength.
- One-click copy to clipboard and option to download as `.txt`.

## ❓ What Is a Password Generator?
A password generator is a tool that automatically creates **strong, random passwords**. Why does that matter?
- **Stronger security**: Random passwords are much harder for attackers to guess or brute-force.
- **Avoids reusing passwords**: Each generated password is unique.
- **Customizable**: You can balance usability and strength (shorter pronounceable vs. long random strings).

Basically, it saves you from coming up with weak stuff like `password123` or `qwerty`. Instead, it spits out long, unique strings that keep your accounts safer.

---

⚡️ Pro tip: Use this alongside a **password manager**. That way you don’t have to remember the generated passwords — just generate, copy, and save.
```
