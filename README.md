# The FreshWay — KS Internationals

A responsive React recreation of the KS Internationals fresh produce export website.

## Run locally

```bash
npm install
npm run dev
```

## Production build

```bash
npm run build
npm run preview
```

## Included

- Responsive FreshWay homepage with product collections, global destinations, certifications and contact details.
- Product collection tabs and specification-sheet dialogs.
- Freight estimator with volume-based container and pallet calculations.
- Grower registration that prepares a WhatsApp message.
- Buyer inquiry form that opens a prefilled email.
- Shipment lookup interface and `/admin` sign-in screen.

The original site’s image assets and selected Unsplash images are loaded by URL. Buyer inquiries and grower registrations use the visitor’s email/WhatsApp apps. Shipment tracking and admin authentication need the original backend services and are not connected in this frontend recreation.

## Publish to GitHub

Create an empty repository on GitHub, then run these commands from this folder (replace the URL with your repository URL):

```bash
git init
git add .
git commit -m "Build FreshWay website recreation"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
git push -u origin main
```
