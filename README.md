# 💸 Cash App Setup — Simulator

An interactive **developer sandbox** that simulates the **Cash App SetupIntent flow** (QR + redirect) for testing payment method setup integrations.

🔗 **Live Demo:** [https://itsaadii13.github.io/cashapp-website/](https://itsaadii13.github.io/cashapp-website/)

---

## 🚀 Features

- **Interactive Sandbox UI** — Built with HTML, CSS (Bootstrap 5), and Font Awesome.  
- **Simulates SetupIntent Lifecycle** — From creation to authentication and completion.  
- **QR Code Display** — Mimics Cash App QR payment authorization.  
- **Mobile Auth Redirect Simulation** — Demonstrates redirect-based authentication flow.  
- **Webhook & Status Update Simulation** — Automatically updates the SetupIntent status.  
- **JSON Visualization** — Displays formatted SetupIntent and Payment Method Options objects.  
- **Responsive Modern Design** — Works seamlessly on desktop and mobile.

---

## 🧠 How It Works

| Stage | Description |
|--------|--------------|
| **1. Setup** | Initializes a test `SetupIntent` and displays its status. |
| **2. Authenticate** | Shows a Cash App QR code and allows simulated mobile auth. |
| **3. Complete** | Simulates webhook success and updates the `SetupIntent` to `succeeded`. |

This allows developers to understand and test Cash App integration behavior in a **safe test environment**.

---

## 🧰 Tech Stack

- **Frontend:** HTML5, CSS3, Bootstrap 5  
- **Logic:** Vanilla JavaScript  
- **Hosting:** GitHub Pages (Static Deployment)

---

## 📂 Folder Structure 
cashapp-website/
├── index.html # Main simulator interface
├── assets/
│ └── css/
│ └── style.css # Custom styling
└── README.md # Documentation (this file)

---

## 🧪 How to Use

1. Visit the live sandbox:  
   👉 [https://itsaadii13.github.io/cashapp-website/](https://itsaadii13.github.io/cashapp-website/)
2. Scan the QR or click **Mobile Auth** to simulate the authentication flow.
3. Watch the setup status update from `requires_action` → `succeeded`.
4. View the simulated webhook and JSON data in real-time.

---

## ⚠️ Notes

- This is a **demo project only** — no real payments or connections occur.  
- Designed for educational and development use (Stripe-style simulation).  
- To customize it, you can edit the JSON blocks in `index.html`.

---

## 📜 License

MIT License © 2025 — [itsaadii13](https://github.com/itsaadii13)

