# Cyber Threat Identification

**Internship Task 3 — VEDA TECHNOLOGY**  
**Track:** Cyber Security  
**Level:** 1  
**Project type:** Educational awareness resource

## 1. Project overview

This project explains common cyber threats, who they target, their potential impact, and practical ways to reduce risk. It is intended as a beginner-friendly awareness resource for students, employees, and small organizations.

## 2. Objectives

- Identify phishing, malware, ransomware, social engineering, and credential theft.
- Explain common targets and impacts.
- Recommend safe, practical prevention measures.
- Provide a small static website that can be deployed using a free static-hosting service.

## 3. Threat classification

| Threat | What it is | Common targets | Potential impact | Prevention |
|---|---|---|---|---|
| Phishing | Deceptive messages or websites designed to trick people into revealing information or opening unsafe content. | Email users, students, employees, customers | Account compromise, financial loss, data exposure | Verify sender and domain; avoid unexpected links/attachments; visit sites by typing the known address; report suspicious messages; use MFA. |
| Malware | Malicious software, such as spyware, trojans, or worms, that performs unwanted or harmful actions. | Personal computers, phones, servers, organizations | Data theft, device disruption, unauthorized access | Install updates; use reputable security software; download only from trusted sources; use least-privilege accounts; maintain backups. |
| Ransomware | Malware that blocks access to files or systems, often by encrypting data, and demands payment. | Individuals, schools, hospitals, businesses | Downtime, data loss, recovery costs, possible data exposure | Keep offline or immutable backups; patch systems; restrict access; train users; use endpoint protection; test recovery procedures. |
| Social engineering | Manipulation that persuades a person to reveal information or perform an unsafe action. | Help desks, staff, students, administrators | Unauthorized access, fraud, information disclosure | Verify unusual requests through a second channel; use approval procedures; limit public exposure of sensitive details; train staff. |
| Credential theft | Stealing passwords, session tokens, or other login information. | Users of email, social media, banking, and workplace systems | Account takeover, identity misuse, further breaches | Use unique passwords with a password manager; enable MFA/passkeys; never share one-time codes; check login alerts; change compromised credentials. |

## 4. Safe response checklist

1. Stop interacting with a suspicious message, link, attachment, or pop-up.
2. Do not reply, pay, or provide passwords or one-time codes.
3. Report the incident to the relevant IT/security contact or platform.
4. If an account may be compromised, use a trusted device to change its password and revoke active sessions; enable MFA.
5. If malware or ransomware is suspected, disconnect the affected device from networks when safe to do so and contact IT support. Do not delete evidence or attempt risky self-repair.
6. Restore files only from known-good backups after the affected system has been assessed.
7. Record what happened, when it happened, and what systems may be affected—without sharing sensitive data publicly.

## 5. Interview questions and answers

### What is phishing?
Phishing is a type of cyberattack in which an attacker impersonates a trusted person or organization to trick someone into clicking a malicious link, opening an unsafe attachment, or disclosing sensitive information.

### What is ransomware?
Ransomware is malicious software that prevents access to files or systems, commonly by encrypting them, and demands payment for recovery. Paying does not guarantee that files will be restored or that stolen information will be deleted.

### What is social engineering?
Social engineering is the use of psychological manipulation to influence people into revealing information, granting access, or carrying out actions that weaken security. Examples include impersonation, urgent fake requests, and pretexting.

## 6. Tools used

- HTML and CSS for a lightweight static website.
- A web browser for testing.
- Git and GitHub for version control and public project hosting.
- A static hosting provider (for example, GitHub Pages or Netlify) for deployment.

No paid tools or real user data are required.

## 7. Run locally

1. Download or clone this repository.
2. Open `index.html` in a modern browser.
3. Review the threat cards and prevention checklist.

This is a static educational page; no server, database, credentials, or API keys are needed.

## 8. Deployment

### Option A: GitHub Pages
1. Create a public GitHub repository and upload the project files.
2. In the repository, open **Settings → Pages**.
3. Choose deployment from the `main` branch and the root folder.
4. Save and wait for GitHub Pages to publish the site.
5. Open the generated URL and test it on mobile and desktop.

### Option B: Netlify
1. Sign in to Netlify and create a new site from the GitHub repository, or deploy the project folder using the provider's supported manual deployment flow.
2. For this static site, use the project root as the publish directory.
3. Publish and test the generated URL.

The included `netlify.toml` supplies basic static-site settings. Provider interfaces can change; follow the current on-screen instructions.

## 9. Testing checklist

- [ ] Website opens without a build step.
- [ ] Page title and all five threat categories display correctly.
- [ ] Prevention text is readable on a mobile screen.
- [ ] Links, if added later, use trusted HTTPS destinations.
- [ ] No passwords, API keys, personal records, or other secrets are committed.
- [ ] Public deployment URL loads successfully.

## 11. Limitations

This is an awareness and educational project, not a malware scanner, incident-response platform, or guarantee of security. Recommendations should be adapted to the organization's policies and risk level.

## 12. Author and submission

- **Author:** Innocent Joseph Matabaro 
- **Internship:** VEDA TECHNOLOGY — Cyber Security
- **Task:** Task 3 — Cyber Threat Identification

