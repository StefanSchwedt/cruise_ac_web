---
#
# By default, content added below the "---" mark will appear in the home page
# between the top bar and the list of recent posts.
# To change the home page layout, edit the _layouts/home.html file.
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
#
layout: home
title: Leveraging Crowd Knowledge for Better User Stories
---

<nav style="background-color: #f8f9fa; padding: 10px; margin-bottom: 20px">
  <a href="#publication" style="margin-right: 20px;">Publication</a>
  <a href="#main-idea" style="margin-right: 20px;">Main Idea</a>
  <a href="#datasets" style="margin-right: 20px;">Datasets</a>
  <a href="#authors" style="margin-right: 20px;">Authors</a>
  <a href="#industry" style="margin-right: 20px;">Call for Industry Participation</a>
  <a href="#submit-story">Submit a User Story</a>
</nav>

<h2><a name="publication"></a><img src="assets/icons/book-2.svg" alt="idea icon" width="24" style="vertical-align:middle; margin-right: 8px; margin-top: -4px"> Publication</h2>

This website provides additional information for the paper "From Bugs to Benefits: Improving User Stories by Leveraging Crowd Knowledge with CrUISE-AC".
The paper will be presented at the [47th International Conference on Software Engineering](https://conf.researchr.org/home/icse-2025) in Ottawa, Canada.

A pre-print of the publication can be downloaded [here](https://arxiv.org/abs/2501.15181).

---

<h2><a name="main-idea"></a><img src="assets/icons/bulb.svg" alt="idea icon" width="24" style="vertical-align:middle; margin-right: 8px; margin-top: -4px"> Main Idea</h2>

Incomplete or ambiguous user stories are a common cause of costly software defects. CrUISE-AC (Crowd and User Informed Suggestion Engine for Acceptance Criteria) uses AI and public issue trackers to automatically generate non-trivial **acceptance criteria** (AC) for user stories. The system analyzes crowdsourced bug reports and feature requests to uncover edge cases and implicit requirements, improving the quality of software specifications early in development.

> Evaluations across e-commerce and CMS domains showed that **80–82%** of generated ACs were rated as useful by experts.

---

<h2><a name="datasets"></a><img src="assets/icons/database.svg" alt="idea icon" width="24" style="vertical-align:middle; margin-right: 8px; margin-top: -4px"> Datasets Used</h2>

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

Additionally, over **300 real user stories** were collected from industry projects in e-commerce and CMS domains."

User stories, issues and results are available for [download](https://zenodo.org/records/14709846).

---

<h2><a name="authors"></a><img src="assets/icons/users.svg" alt="idea icon" width="24" style="vertical-align:middle; margin-right: 8px; margin-top: -4px"> Authors & Contact</h2>

**Stefan Schwedt**  
Heriot-Watt University, Edinburgh, Scotland  
schwedt@cruise-ac.net  

**Thomas Ströder**  
Fachhochschule der Wirtschaft (FHDW), Mettmann, Germany  
thomas.stroeder@fhdw.de  

---

<h2><a name="industry"></a><img src="assets/icons/speakerphone.svg" alt="idea icon" width="24" style="vertical-align:middle; margin-right: 8px; margin-top: -4px"> Call for Industry Participation</h2>

Are you working on agile development projects?

We're inviting **industry partners** to collaborate in a **field study** to test and refine CrUISE-AC in real-world settings. Your team will benefit from automated insights while helping us validate and improve the tool in practice.

**Let’s explore how CrUISE-AC can help your team reduce defects and enhance requirements quality.**

**Interested? Reach out via email or use the form below.**

---

<h2><a name="submit-story"></a><img src="assets/icons/forms.svg" alt="idea icon" width="24" style="vertical-align:middle; margin-right: 8px; margin-top: -4px"> Test Us: Submit a User Story</h2>

Use the form below to send us a user story. We’ll analyze it and reply with:

- Automatically generated **acceptance criteria**
- A short **feedback questionnaire**

<form method="POST" action="https://formspree.io/f/xqapjaqn" style="max-width: 600px; margin: 0 auto;">
  <label for="name" style="font-weight: bold;">Your Name:</label><br>
  <input type="text" id="name" name="name" placeholder="Enter your full name" required style="width: 100%; padding: 8px; margin: 8px 0;"><br>

  <label for="company" style="font-weight: bold;">Your Company / Affiliation:</label><br>
  <input type="text" id="company" name="company" placeholder="Enter your company or affiliation" required style="width: 100%; padding: 8px; margin: 8px 0;"><br>

  <label for="email" style="font-weight: bold;">Your Email:</label><br>
  <input type="email" id="email" name="email" placeholder="Enter your email address" required style="width: 100%; padding: 8px; margin: 8px 0;"><br>

  <label for="userstory" style="font-weight: bold;">Your User Story:</label><br>
  <textarea id="userstory" name="userstory" placeholder="As a [role], ..." rows="4" required style="width: 100%; padding: 8px; margin: 8px 0;"></textarea><br>

  <label for="acceptance_criteria" style="font-weight: bold;">Existing Acceptance Criteria (optional):</label><br>
  <textarea id="acceptance_criteria" name="acceptance_criteria" placeholder="Provide any existing acceptance criteria..." rows="4" style="width: 100%; padding: 8px; margin: 8px 0;"></textarea><br>

  <input type="submit" value="Submit" style="background-color: #007BFF; color: white; padding: 10px 20px; border: none; border-radius: 4px; cursor: pointer;">
</form>
