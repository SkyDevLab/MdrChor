# 🥷 MDRChor — Split Smarter, Pay Less MDR

**MDRChor** is a simple, client-side payment split calculator that helps you understand how splitting a payment into smaller transactions can affect MDR (Merchant Discount Rate) charges.

> Same Payment. Less MDR. More for You! 💰

## ✨ What it does

Enter a payment amount and MDRChor shows:

- 💰 The original MDR charge
- ✂️ Automatic payment splits
- 🎯 Custom number of splits
- 🧾 MDR charge for every transaction
- 🎉 Which transactions are charge-free
- 📊 Total MDR after splitting
- 💚 Potential savings compared with one transaction

### Example

For **₹10,000** using the default rules:

**Automatic split**

- ₹2,000 → ₹0 MDR
- ₹2,000 → ₹0 MDR
- ₹2,000 → ₹0 MDR
- ₹2,000 → ₹0 MDR
- ₹2,000 → ₹0 MDR

If the original transaction is charged at **0.4%**, the calculator shows the difference between the original MDR and the split MDR.

### Custom splits

Choose **4 splits** for ₹10,000:

1. ₹2,000
2. ₹2,000
3. ₹2,000
4. ₹4,000

The **0.4% MDR is calculated only on the ₹4,000 transaction**, according to the calculator's configured rules.

## 📐 Current calculation rules

| Transaction amount | MDR |
|---|---:|
| ₹0–₹2,000 | ₹0 |
| Above ₹2,000 to ₹75,000 | 0.4% |
| Above ₹75,000 | ₹300 fixed |

These rules are configurable in the JavaScript source and are provided as an example calculation model. Actual payment-provider fees, limits, taxes, and transaction rules can differ.

## 🚀 Features

- Responsive desktop/mobile UI
- Automatic split calculator
- Custom split calculator
- Live calculation
- Savings comparison
- INR formatting using the Indian numbering system
- No backend
- No database
- No login
- Runs entirely in the browser
- GitHub Pages friendly

## 🔍 SEO

MDRChor is designed as a lightweight static website so it can be indexed easily by search engines.

SEO improvements included/planned:

- Descriptive page title
- Meta description
- Mobile-friendly responsive layout
- Semantic HTML
- Clear headings
- Descriptive page content
- Fast client-side calculation
- GitHub Pages deployment
- Search-focused explanatory content

Useful search phrases for the project include:

- MDR calculator
- payment MDR calculator
- merchant discount rate calculator
- MDR charge calculator India
- payment split calculator
- payment transaction charge calculator
- 0.4 percent MDR calculator
- calculate MDR charges
- payment fee calculator India

## 🛠️ Tech Stack

- HTML5
- CSS3
- Vanilla JavaScript
- GitHub Pages

No framework or build step is required.

## 🔗 Links

- 🌐 **Live Website:** https://skydevlab.github.io/MdrChor/
- 💻 **GitHub Repository:** https://github.com/SkyDevLab/MdrChor

## 🌐 Deploy with GitHub Pages

1. Open the repository **Settings**
2. Select **Pages**
3. Choose **Deploy from a branch**
4. Select `main`
5. Select `/ (root)`
6. Save

GitHub will provide the public Pages URL.

## ⚠️ Important

MDRChor is an educational/calculation tool. It does not process payments and does not guarantee that a payment provider will permit or price transactions according to these rules.

Always check the applicable terms, MDR schedule, taxes, minimum charges, transaction limits, and anti-abuse rules of your payment provider.

## 📄 License

Add the license you prefer before publishing the project for wider reuse.

---

Made with ❤️ by **SkyDevLab**.

**MDRChor — Chori nahi, Smart Split! 😎**
