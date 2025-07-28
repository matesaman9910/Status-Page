# 🔐 Secure Status Page

A simple status dashboard with Firebase Authentication. Authorized users can update the status, everyone else can view it.

---

## 🚀 Features

- Public can **view status**
- Authorized users can **log in & update**
- Styled using **Tailwind CSS**
- Powered by **Firebase Auth**

---

## 🌐 Live Hosting (GitHub Pages)

1. Fork or clone this repo
2. Copy `index.html` into root
3. Push to `main` branch
4. Go to **Settings > Pages** and enable GitHub Pages on `/ (root)` with the main branch

---

## 🔧 Firebase Setup (already configured)

- Firebase Project: `auth-firebase-d6cd8`
- Auth method: Email/Password

> You can log in using Firebase Authentication:
> 1. Go to your Firebase console
> 2. Enable **Email/Password** login
> 3. Add a test user in **Authentication > Users**

---

## 🛡 Security

- This version uses `localStorage` to save status for simplicity.
- In a real deployment, connect Firebase Realtime Database or Firestore to store persistent status data.
- Passwords are never stored in code — Firebase Auth handles it securely.

---

## 🔮 Coming Soon (optional upgrades)

- [ ] Firebase Realtime Database for global status sync
- [ ] Role-based permissions
- [ ] Status logs / history

---

## 🧠 Author

This was generated and implemented by ChatGPT and tailored for personal or small-team use. Secure it further if you’re going public.

