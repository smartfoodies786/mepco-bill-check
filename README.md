# MEPCO Bill Check

Static guide site for checking MEPCO electricity bills online — guide + official portal link only. No data is collected or stored, and the site never claims to fetch the bill itself.

## Pages (34)

- `index.html` — homepage: checker (opens the official PITC portal in a new tab), 4 steps, quick answers, 13-district list, payment + complaint strips, FAQ x10 with FAQPage JSON-LD, Bijli Bhai tip box
- 7 depth pages — reference number, duplicate download, without reference, payment, understanding charges, complaint/helpline, SMS check
- 13 district bill pages — Multan, Khanewal, Sahiwal, Bahawalpur, Bahawalnagar, Muzaffargarh, Dera Ghazi Khan, Rahim Yar Khan, Vehari, Lodhran, Layyah, Rajanpur, Pakpattan
- 13 electrician guide pages — Multan head guide + 12 district guides (guide only, no listings yet)

## Verified facts

- Official portal: https://bill.pitc.com.pk/mepcobill (14-digit reference number or 10-digit Customer ID)
- Helplines: 118 and 0800-63726
- SMS: 8334 = bill amount + due date (send "PITC" + reference number); 8118 = complaints/alerts
- Printed duplicate bill accepted at banks

## Deploy

Static site, no build step. Import into Vercel as a static project. Domain not bought yet — replace `example.com` in `sitemap.xml` and `robots.txt` with the live domain before submitting to Search Console, and add canonicals then.
