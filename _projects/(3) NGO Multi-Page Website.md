---
name: Digital Marketing Clinic Website
weight: 3
tools: [Hugo, HTML/CSS, AWS Amplify, GitHub Actions, Static Site]
image: /images/ngo_demo_homepage.png
description: Built a modern, static multi-page website for a non-profit organization using Hugo framework. Features responsive design, CI/CD with AWS Amplify, and low-maintenance architecture suitable for volunteer-run organizations.
# external_url: https://main.dpfot6jx0tjgi.amplifyapp.com/
---

# Digital Marketing Clinic Website

A modern, static multi-page website built for a non-profit organization using the **Hugo** framework.
The site introduces the organization’s mission, services, and contact information through a clean, accessible, and responsive design.

🌐 **Live Demo:** [Demo Link](https://main.dpfot6jx0tjgi.amplifyapp.com/) <br>
💻 **Code Base** [Code](https://github.com/FrozenOolong/digitalmarketingclinic) <br>
🛠️ **Built With:** Hugo • HTML/CSS • AWS Amplify • Github Action

Home Page View 
![image](/images/ngo_demo_homepage.png)
---

Service Page View 
![image](/images/ngo_demo_service.png)
---

Keyword Prediction (Project showcasing) View 
![image](/images/ngo_demo_prediction.png)
---

Contact Page View 
![image](/images/ngo_demo_contact.png)
---

##  Project Overview

The Digital Marketing Clinic (DMC) provides free marketing consultations to small businesses, helping them to build digital presence and optimize online marketing performance, including website, social media, eNewsletter, advertising, and analytics.

The goal of this website was to:

* Establish a professional online presence for DMC
* Clearly communicate the organization’s mission and services
* Make it easy for users to **book a free consultation** through clear call-to-actions

## Design Approach

I aimed for a **modern, simple, and trustworthy** design that delivers essential information without overwhelming users.

**Key Design Choices:**

* **Template:** Selected the [Hugo Hero](https://hugo-hero.netlify.app/) template for its minimal layout, responsive design, and clear navigation.
* **Information Architecture:** Planned all core content (About, Services, Contact) in PowerPoint first to structure headings, paragraphs, and calls to action before implementation.
* **Branding:**

  * Created a custom **logo** and established a **mint-blue color palette** to evoke a fresh and approachable feel.
  * Used **sans-serif fonts** for a clean, modern look.
  * Chose **abstract, element-based images** with consistent tones to maintain neutrality and professionalism.
* **User Experience:** Focused on fast loading, simple navigation, and visible action buttons (“Book Free Consultation”) on the home page.

## Development Considerations

Given DMC’s nature as a volunteer-run non-profit, my priorities were:

* **Low maintenance:** Content updates once or twice a year.
* **Ease of deployment:** Quick to update and redeploy.
* **Low operating cost:** Preferably free hosting options.
* **Professional presentation:** Consistent design without unnecessary animations.

| Option                               | Development Effort | Customization | Cost         | Notes                                       |
| ------------------------------------ | ------------------ | ------------- | ------------ | ------------------------------------------- |
| Build from scratch (HTML/CSS/JS)     | High               | High          | Medium–High  | Requires more dev time and maintenance      |
| Static site generator (Hugo, Jekyll) | Medium             | Medium–High   | Low          | ✅ Best balance between control and simplicity |
| Website builder (Wix, Squarespace)   | Low                | Low–Medium    | Monthly cost | Easy setup but recurring fees               |
| Hire developer/company               | None               | Varies        | High         | Not suitable for small budget               |

➡️ **Decision:** Hugo offered the best trade-off between **customization, cost, and long-term maintainability**.

## Deployment Strategy

To keep the solution simple and affordable:

| Deployment Option                                           | Setup Effort | Cost        | Suitability                  |
| ----------------------------------------------------------- | ------------ | ----------- | ---------------------------- |
| Self-hosted server                                          | High         | Medium      | Overkill for static site     |
| Cloud VM (e.g., AWS EC2, GCP VM)                            | High         | Medium–High | Suitable for full-stack apps |
| Static hosting (AWS Amplify, S3, Netlify, Cloudflare Pages) | Low          | Low–Free    | ✅ Ideal for static websites    |


**Chosen Setup:**

* **Hosting:** AWS Amplify (connected directly to GitHub for CI/CD)
* **Domain:** Managed via AWS Route53 (not currently setup as I have ended the project)
* **Reasoning:** Already had AWS setup, Amplify provides easy deployment, HTTPS, and versioning with no ongoing cost.

If redeployed today, I might consider **Netlify** or **Cloudflare Pages** for even simpler configuration.