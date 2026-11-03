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


## Week 4 scenario expansion
Five independent Week 4 learning scenarios are available in Environment B > Learning Scenarios: Encrypt Student Records, Secure University Web Communications, Investigate a Modified Grade Report, Protect University Encryption Keys, and Verify a University Software Update. The existing Environment A/B tools remain shared across scenarios. Hash checking uses Web Crypto SHA-256; encryption, TLS, key rotation, and signatures are clearly labeled conceptual simulations.

## Week 5 extension: Authentication and Access Control

Environment B now includes **Week 5 · Authentication Lab**, with interactive password-policy review, authentication factors, simulated MFA request rejection, identity lifecycle management, role/permission tests, access decisions, and audit monitoring. Six new Week 5 guided scenarios require three ordered actions each and record completion evidence in IndexedDB and SIEM. The existing Week 1–4 scenarios and operational pages are retained.

**Training limitations:** Password-policy changes and authentication checks are conceptual simulations, not a real authentication backend. Do not enter real passwords or personal information. The simulated passkey explanation is educational; no real WebAuthn enrollment is performed. Back up existing student work as JSON before deploying or resetting. This package extends the uploaded Week 4 ZIP; it is not verified to match every file currently published under the `/v42/` website path.

**Deploy to `/Cyberlab/v42/`:** extract the ZIP and upload its `index.html`, `app.js`, and `styles.css` to the appropriate folder in the GitHub repository. A browser refresh may be needed after deployment.
