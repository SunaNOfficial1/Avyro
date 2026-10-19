# AVYRO College Bag Website

Upload all files/folders in this project to your GitHub Pages repository.

## Included
- SPSC, BMARPC and GSC bag images
- Click-to-open product viewer
- Zoom in/out controls, mouse wheel zoom and touch pinch zoom
- WhatsApp: 01614073205
- Call: 01614073205
- bKash Send Money: 01714073205
- Referral code: avyro
- Required order form
- Half payment: 300 Taka
- Full payment: 600 Taka
- Required warning message

## Important: connect the order form
GitHub Pages is only the website. It cannot safely store customer orders by itself.

The form is prepared to send the order to a Google Apps Script Web App. After deploying your Apps Script, put its `/exec` URL into this line in `index.html`:

<form id="orderForm" data-script-url="PASTE-YOUR-APPS-SCRIPT-URL-HERE">

Then commit/publish the files to GitHub Pages.

Do not put private API keys or passwords in this website.
