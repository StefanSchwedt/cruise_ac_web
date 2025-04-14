# CrUISE-AC: Leveraging Crowd Knowledge for Better User Stories

**From Bugs to Benefits: Improving User Stories by Leveraging Crowd Knowledge with CrUISE-AC**

---

## 🧠 Main Idea

Incomplete or ambiguous user stories are a common root of costly software defects. CrUISE-AC (Crowd and User Informed Suggestion Engine for Acceptance Criteria) uses AI and public issue trackers to automatically generate non-trivial **acceptance criteria** (AC) for user stories. The system analyzes crowdsourced bug reports and feature requests to uncover edge cases and implicit requirements, improving the quality of software specifications early in development.

> 🧪 Evaluations across e-commerce and CMS domains showed that **80–82%** of generated ACs were rated as useful by experts.

---

## 📂 Datasets Used

CrUISE-AC was evaluated using **real-world data** from these public issue trackers:

- [WooCommerce](https://github.com/woocommerce/woocommerce/issues)
- [Magento](https://github.com/magento/magento2/issues)
- [PrestaShop](https://github.com/PrestaShop/PrestaShop/issues)
- [OpenCart](https://github.com/opencart/opencart/issues)
- [nopCommerce](https://github.com/nopSolutions/nopCommerce/issues)
- [Shopware 5](https://issues.shopware.com/?products=SW-5)
- [Shopware 6](https://issues.shopware.com/?products=SW-6)
- [Moodle](https://github.com/moodle/moodle/issues)
- [Umbraco](https://github.com/umbraco/Umbraco-CMS/issues)

And over **300 real user stories** from industry projects in e-commerce and CMS domains.

---

## 👥 Authors & Contact

**Stefan Schwedt**  
Heriot-Watt University, Edinburgh, Scotland  
📧 schwedt@cruise-ac.net  

**Thomas Ströder**  
Fachhochschule der Wirtschaft (FHDW), Mettmann, Germany  
📧 thomas.stroeder@fhdw.de  

---

## 🤝 Call for Industry Participation

Are you working on agile development projects?

We're inviting **industry partners** to collaborate in a **field study** to test and refine CrUISE-AC in real-world settings. Your team can benefit from automated insights while helping us validate and improve the tool in practice.

**💡 Let’s explore how CrUISE-AC can help your team reduce defects and enhance requirements quality.**

📬 **Interested? Reach out via email or use the form below.**

---

## 🧪 Test Us: Submit a User Story

Use the form below to send us a user story. We’ll analyze it and reply with:

- Automatically generated **acceptance criteria**
- A short **feedback questionnaire**

```html
<form method="POST" action="https://formspree.io/f/YOUR_FORM_ID">
  <label for="name">Your Name:</label><br>
  <input type="text" id="name" name="name" required><br><br>

  <label for="email">Your Email:</label><br>
  <input type="email" id="email" name="email" required><br><br>

  <label for="userstory">Your User Story:</label><br>
  <textarea id="userstory" name="userstory" rows="6" required></textarea><br><br>

  <input type="submit" value="Submit">
</form>
