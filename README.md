# ✅ yaas-as-a-Service

Ever needed a graceful way to say “yaass”?  
This tiny API returns random, generic, creative, and sometimes hilarious approval reasons — perfectly suited for any scenario: personal, professional, student life, dev life, or just because.

Built for humans, approvals, and humor.

---

## 🚀 API Usage

**Method:** `GET`  
**Rate Limit:** `120 requests per minute per IP`

### 🔄 Example Request
```http
GET /yaass
GET /yas
GET /yes
```

### ✅ Example Response
```json
{
  "reason": "In a different season of life, I might say no—but right now? YAASS!"
}
```

Use it in apps, bots, landing pages, Slack integrations, rejection letters, or wherever you need a polite (or witty) yaass.

---

## 🛠️ Self-Hosting

Want to run it yourself? It’s lightweight and simple.

### 1. Clone this repository
```bash
git clone https://github.com/hotheadhacker/yaas-as-a-service.git
cd yaas-as-a-service
```

### 2. Install dependencies
```bash
npm install
```

### 3. Start the server
```bash
npm start
```

The API will be live at:
```
http://localhost:3000/yaass
```
also accessible at:
```
http://localhost:3000/yas
```
and
```
http://localhost:3000/yes
```

You can also change the port using an environment variable:
```bash
PORT=5000 npm start
```

---

## 📁 Project Structure

```
yaas-as-a-service/
├── index.js            # Express API
├── reasons.json        # 500+ universal approval reasons
├── package.json
├── .devcontainer.json  # VS Code / Github devcontainer setup
└── README.md
```

---

## 📦 package.json

For reference, here’s the package config:

```json
{
  "name": "yaas-as-a-service",
  "version": "1.0.0",
  "description": "A lightweight API that returns random approval or yaass reasons.",
  "main": "index.js",
  "scripts": {
    "start": "node index.js"
  },
  "author": "olitreadwell",
  "license": "MIT",
  "dependencies": {
    "express": "^4.18.2",
    "express-rate-limit": "^7.0.0"
  }
}
```

---

## ⚓ Devcontainer

If you open this repo in Github Codespaces, it will automatically use `.devcontainer.json` to set up your environment.  If you open it in VSCode, it will ask you if you want to reopen it in a container.

---
## Projects Using yaas-as-a-Service

Here are some projects and websites that creatively integrate [yaas-as-a-service](https://naas.isalman.dev/no) to deliver humorous or programmatic "no" responses:

1. **[Your Project Here?](https://github.com/YOUR_REPO)**  
   If you're using yaas-as-a-service in your project, open a pull request to be featured here!

---

> Want to use yaas-as-a-service in your own project? Check out the usage section in this README and start returning **"no"** like a pro.
---

## 👤 Author

Created with creative stubbornness by [hotheadhacker](https://github.com/hotheadhacker)

---

## 📄 License

MIT — do whatever, just don’t say yes when you should say no.
