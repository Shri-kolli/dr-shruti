# dr-shruti
web-page for the cardiologist. for social media presence 


<!--
README / Instructions (Top of file)

How to use this template
1) Edit the following placeholders:
   - Replace DR_NAME with your sister’s full name (e.g., "Dr. Nane S. Patil").
   - Update BIO_TEXT under "About Doctor" with her background/achievements.
   - Replace images:
       * images/doctor-photo.jpg -> doctor’s portrait (near name).
       * images/heart-bg.jpg -> background (can be swapped for another medical/clinic themed image).
       * images/heart1.jpg, heart2.jpg, heart3.jpg -> carousel images (doctor, clinic, conferences, etc.)
   - In the appointment form, replace `https://formspree.io/f/yourformid` with your Formspree form action URL.
   - In the contact/social section, update email, phone, and social media links.

2) Updating Clinic Locations:
   - Scroll to the "Clinic Locations & Timings" section in HTML.
   - Each `<div class="location-card">` represents one clinic.
   - Replace:
       * <h3>Clinic Name</h3> with the location’s name.
       * <p><strong>Address:</strong> …</p> with actual address.
       * <p><strong>Hours:</strong> …</p> with availability timings.
   - You can duplicate `<div class="location-card">...</div>` blocks to add more locations.

3) Google Maps:
   - Current code shows one Google Maps embed.
   - Replace `YOUR_GOOGLE_MAPS_API_KEY` in the script tag with your API key.
   - Update latitude/longitude or replace iframe with correct Google Maps embed link for each clinic if needed.

4) Appointment Form:
   - Visitors can enter name, email, phone, date, and message.
   - Submissions go to Formspree. To enable:
       * Sign up at https://formspree.io
       * Create a form and get the unique form ID.
       * Replace `yourformid` in the form action URL.

   - SMS integration (optional): can be added with Twilio API if you want text notifications.

5) Testing locally:
   - Double-click `index.html` to open in a browser.
   - For Google Maps API or form submission, better use a local web server:
       * Python: `python -m http.server`
       * VS Code: Live Server extension

6) Deploy to GitHub Pages:
   - Create a GitHub repo (e.g., `username/sister-website`).
   - Add:
       * index.html (this file)
       * /images/ folder with doctor photos, background, and carousel images
   - Push to GitHub.
   - Go to repo -> Settings -> Pages -> Source -> choose main branch / root.
   - Your site will be live at: https://username.github.io/sister-website/

7) Custom Domain:
   - In repo root, create a file called CNAME with: dr-name.com
   - Update DNS records for your domain (A records -> GitHub Pages IPs, CNAME for www -> username.github.io).
   - Save in GitHub Pages -> Custom Domain settings.

8) Editing further:
   - You can request design changes: new fonts, colors, sections (testimonials, publications, awards).
   - Add downloadable CV / research papers.
   - Make the site responsive for mobile (already partially done).
   - Convert later to React/Next.js/WordPress for advanced editing.
-->
