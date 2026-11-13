# Formly — Quick Frontend Demo

A polished no-backend form-builder prototype, ready to deploy as a static site on Vercel.

## Deploy to Vercel
1. Extract this ZIP.
2. Upload the contents to a new GitHub repository.
3. In Vercel, choose **Add New → Project** and import the repository.
4. Framework preset: **Other**.
5. Build command: leave empty. Output directory: `.`.
6. Deploy.

No Render service, backend, database, environment variables or build step is required.

## Try the demo
- Create a blank form, event registration or feedback form.
- Add fields from the left panel.
- Click a field on the canvas to edit its label, placeholder, options and required setting.
- Move fields up/down, delete fields and change the accent color/font/layout.
- Preview and submit a test response.
- Publish to see the demo share panel.
- View the saved test responses in the Responses section and export CSV.

## Important demo limitations
This version uses browser `localStorage` only:
- Forms and submissions are saved in the current browser on the current device.
- Data is not shared between users, browsers or devices.
- The “published” link is a demo placeholder, not a real public form URL.
- There is no real account system, organization isolation, cloud sync, file upload processing, email notification or online payment.
- Anyone using the same browser profile can access the demo data; do not enter real or sensitive personal information.

This is intentionally a frontend prototype for quick UI/UX testing. When you're ready, the next step is to add a database and authentication, then make published forms accessible to respondents via unique URLs.
