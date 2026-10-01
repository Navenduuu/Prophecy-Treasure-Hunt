PHOTO QR LOCK — SETUP GUIDE

1. Open index.html in a browser to test the page.
2. Replace photo.jpg with your photograph.
   - Keep the filename exactly: photo.jpg
   - If your photo is PNG, change src="photo.jpg" in index.html to src="photo.png".
3. Open index.html in a text editor.
4. Find:
       const CORRECT_PASSWORD = "1234";
   Replace 1234 with your desired password.
5. Upload index.html and your photograph to a web-hosting service.
6. Copy the public HTTPS URL of index.html.
7. Create a QR code containing that URL.
8. When participants scan the QR code:
       QR → password screen → correct password → photograph

IMPORTANT:
This template is suitable for a treasure hunt / escape-room game.
The password is stored in the webpage's JavaScript, so this is NOT
strong cryptographic protection. Do not use it for genuinely confidential
photographs or sensitive information.
