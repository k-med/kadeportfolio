# Kade Medley — Technical Support & Field Service Portfolio

This repository contains the source code for [kademedley.com](https://kademedley.com), the professional portfolio of Kade Medley, an English-first Technical Support and Field Service professional based in/targeting Vietnam.

## About the Site

This static website is built with **Hugo** and uses the **PaperMod** theme. It serves as an integrated resume and service catalog for:
- Customer-facing troubleshooting
- Installation & commissioning support
- Technical documentation
- Practical systems support

The site features a multilingual setup (currently highlighting a primary route for Vietnam) to detail projects, services, and background information. 

## Tech Stack

*   **Static Site Generator:** [Hugo](https://gohugo.io/)
*   **Theme:** [PaperMod](https://github.com/adityatelange/hugo-PaperMod) (Customized)
*   **Hosting:** Cloudflare Pages
*   **Version Control:** Git / GitHub

## Local Development

To run this site locally, ensure you have Hugo (extended version recommended for asset pipeline processing like SCSS) installed on your machine.

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/k-med/kadeportfolio.git
    cd kadeportfolio
    ```

2.  **Run the Hugo development server:**
    ```bash
    hugo server -D
    ```
    *(The `-D` flag includes draft content if any exist).*

3.  **View the site:**
    Open `http://localhost:1313/` in your browser.

## Deployment

The site is configured for continuous deployment via **Cloudflare Pages**. 
Pushes to the `main` branch automatically trigger a new build and deployment under the production environment. 

Build Command: `hugo`
Build Output Directory: `public`

## Contact

You can reach Kade Medley through the [Contact](https://kademedley.com/vietnam/contact/) page on the site, or via [LinkedIn](https://www.linkedin.com/in/kademedley/).

.
