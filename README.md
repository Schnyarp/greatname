# Greatname.com – Premium Domain Landing Page

This is the landing page template for **greatname.com**, designed to showcase and sell a curated collection of premium domain names. The template features a clean, modern design, an inquiry form for potential buyers, and a hidden page visit counter using [hits.sh](https://hits.sh).

## Features

- **Modern, responsive design** suitable for any premium domain.
- **Customizable domain detection** (shows "Buy [domain]" at the top).
- **Inquiry form** for visitors to make an offer and contact you.
- **Blue-shaded offer banner** to highlight your deals.
- **Hidden visitor counter** using [hits.sh](https://hits.sh).
- **Easy to customize**: Just update the domain name and form handler as needed.

## Setup & Usage

1. **Customize Domain Name**
   - Edit the `<h1>` in the `<header>` and any other references to "greatname.com" to match your domain.

2. **Inquiry Form**
   - The form uses [Formspree](https://formspree.io/) for handling submissions.
   - To use your own Formspree endpoint, replace the `action` URL in the form:
     ```html
     <form class="inquiry-form" action="https://formspree.io/f/your-form-id" method="POST" autocomplete="on">
     ```
   - You can also connect to any other form backend by updating the `action` attribute.

3. **Domain Detection**
   - The script detects the current domain and displays "Buy [domain]" above the form. This helps visitors confirm which domain they are making an offer for.

4. **Visitor Counter**
   - The hidden counter is powered by [hits.sh](https://hits.sh/greatname.com.svg).
   - To use your own domain, generate a new hits.sh URL and update the `<img src="...">` in the HTML.

5. **Deployment**
   - Upload the `index.html` file to your web host or domain's root directory.
   - No backend is required unless you want to process forms yourself.

## Customization

- **Change color scheme, fonts, and layout** by editing the CSS in the `<style>` section of `index.html`.
- **Update links** (e.g., to your own "how to choose a great domain" resource).
- **Adjust or remove features** (like the info article, offer banner, or feature list) as desired.


## Credits

- Built by Greatname.com
- Hidden counter by [hits.sh](https://hits.sh)
- Inquiry form powered by [Formspree](https://formspree.io/)

---

**Questions or issues?**  
Open an issue or contact us via the inquiry form!
