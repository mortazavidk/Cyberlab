# Northstar University CyberLab – CPSC 301

A static, browser-based cybersecurity simulation for Weeks 1–3, designed to be extended with later course modules.

## Deploy to GitHub Pages

1. Create a **public** GitHub repository (for example, `cpsc301-cyberlab`).
2. Upload `index.html`, `styles.css`, and `app.js` to the **root** of the repository (not inside a nested folder).
3. Commit the files.
4. Open **Settings → Pages**. Under **Build and deployment**, select **Deploy from a branch**; choose **main** and **/(root)**, then save.
5. After deployment, open `https://YOUR-USERNAME.github.io/cpsc301-cyberlab/` (replace both placeholders).

Do not upload the ZIP as a single file to GitHub Pages; extract it first and upload the three application files.

## What's included

- Environment A: student information system, LMS, staff directory, university email, document sharing, IT devices.
- Environment B: security dashboard, asset inventory, IAM, SIEM, endpoint security, vulnerability management, email security, data protection, incident management, VTCR risk register.
- Six guided learning scenarios across Weeks 1–3.
- Connected state changes, synthetic event generation, alert generation, and local progress tracking.
- IndexedDB persistence, JSON export/import, and full workspace reset.

## Important limits

This is **Version 1**, a functional teaching prototype—not a real university system or a commercial SIEM/EDR product. It simulates rather than executes malware, exploits, phishing, and network traffic. The account/permission checks are intentionally simplified. Scenario reflection completion is self-reported and not auto-graded. No centralized teacher dashboard or multi-device synchronization is included. IndexedDB is local to each student's browser and can be erased by browser data clearing. Export JSON backups regularly.

All records are fictional. Do not enter actual personal information or credentials.

## Future extension

Add new UI pages and simulation actions in `app.js`; extend the seeded state and introduce IndexedDB migrations if changing the persisted schema. Keep the same repository URL and preserve student backups before major updates.
