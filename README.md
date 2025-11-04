# 💙 Get2Know — A Playful Interactive Quiz for First Impressions

**Get2Know** is a lighthearted single-page web experience designed to make a first contact fun, engaging, and a little flirty.  
It walks the user through a few witty questions — from destiny to dream dates — ending with a smooth WhatsApp redirection to start the real conversation. ✨

---

## 🌟 Features

- 💬 **Interactive multi-step quiz** with creative, humorous questions  
- 📊 **Progress bar** that tracks quiz completion  
- 🎨 **Modern blue-themed UI**, mobile-friendly and elegant  
- 💌 **WhatsApp integration** — redirects to your number with a custom message  
- ⚡ **No frameworks needed** — built entirely with HTML, CSS, and JavaScript  

---

## 🧩 How It Works

1. The user answers a few fun questions.
2. After the final step, they’re asked to enter their phone number.  
3. When they click **Send Message**, the app redirects them to **your WhatsApp number** with a prewritten text message.
4. Voilà — the conversation begins. 💬

---

## 🚀 Getting Started

### 1. Clone this repository
```bash
git clone https://github.com/KainanGuerra/get2know.git
```

### 2. Open the project
Just open `index.html` in your browser — no build tools required.

### 3. Customize your WhatsApp number
Inside the `<script>` section, find this line and replace it with your own number:

```js
const yourNumber = "55XXXXXXXXXXX";
```
*(Use your full number with country code, e.g. Brazil → 5599999999999)*

---

## 🖌️ Customization

You can easily modify:
- The **questions and answers** inside the `questions` array  
- The **colors** in the `:root` CSS variables  
- The **message** sent via WhatsApp link  

Example:
```js
const message = encodeURIComponent("Hey 😄 I loved your answers on Get2Know!");
```

---

## 📱 Demo

👉 *[Live Demo (optional link to your GitHub Pages or Vercel site)](https://KainanGuerra.github.io/get2know)*

---

## 💡 Inspiration

This project was created as a playful and creative way to spark a first conversation — mixing humor, curiosity, and a bit of destiny 😉  

---

## 🧑‍💻 Tech Stack

- **HTML5**
- **CSS3**
- **Vanilla JavaScript (ES6)**

---

## 📜 License

This project is open-source under the [MIT License](LICENSE).

---

### ✨ “A fun and flirty interactive quiz that leads straight to a WhatsApp chat.” 💙
