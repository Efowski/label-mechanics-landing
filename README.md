# Label Mechanics landing v0.2

Static HTML/CSS/JS landing page prepared for Cloudflare Pages. The Kit `Clare` inline signup form is already embedded.

## Before publishing

1. Test the full signup flow with an email address: submit -> confirmation email -> confirm -> subscriber appears in Kit.
2. Replace the temporary `mailto:efowski@gmail.com` customer-discovery link when Label Mechanics gets its own address or a dedicated contact form.

## Local preview

Use a small local HTTP server so the external Kit script loads in a normal web context:

`python -m http.server 8000`

Then open `http://localhost:8000`.

## Deployment

Create a GitHub repository, commit these files, then connect that repository to Cloudflare Pages. This site has no build step and can be served from the repository root.
