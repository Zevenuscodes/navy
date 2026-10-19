# NavAyu Care

Website for NavAyu Care, an Ayurvedic wellness centre. *Aayurbhavtu Jeewanam.*

A single static page (`index.html`) with no build step:

- Live 24-hour dosha clock (Kapha · Pitta · Vata kala)
- Therapies, Panchakarma, residential programmes, vaidyas and booking sections
- Light and dark themes, responsive down to phone width

## Run locally

```sh
python3 -m http.server 8080
```

Then open http://localhost:8080.

## Before going live

- Replace the placeholders: `Dr. [Full Name]`, portraits, address, phone and email
- Connect the booking form in `index.html` to a real booking service (it currently only shows an on-page confirmation)
