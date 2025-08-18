# Cerebrum Security Disclosure & Bug Bounty

At Cerebrum, we value the security of our systems as much as the privacy of our clients. Our robust compliance solutions are designed to ensure optimal security, and we are dedicated to continuously improving our safeguards.

## Bug Bounty Program

We believe that securing our platforms is an ongoing effort, and we acknowledge the valuable role that security researchers play in this process. To show our appreciation, we are launching our Bug Bounty Program. We invite researchers to identify and report potential vulnerabilities in our system.

This program is specifically designed to encourage you to notify us of any **previously unreported vulnerabilities**. Please note, the bounty will only be paid if the vulnerability reported is unknown to us and was not yet reported.

## Security Vulnerability Categories & Bounty Amounts

### Low-Level Vulnerabilities

These issues may cause minor inconvenience, but they aren't likely to pose a serious risk.

* **Bounty:** $200
* *Examples:* Lack of proper rate limiting, overly verbose error messages, session management issues, missing security headers.

### Medium-Level Vulnerabilities

These vulnerabilities could potentially affect the functionality of our systems or compromise the privacy of a small subset of data.

* **Bounty:** $500
* *Examples:* Weak authorization checks leading to privilege escalation through IDOR, lax CSRF token validation, poor API input validation, missing or expired TLS certificates, insecure file uploads.

### High-Level Vulnerabilities

These vulnerabilities could jeopardize the security of our platform or compromise sensitive data on a large scale.

* **Bounty:** $1,500
* *Examples:* SQL injection attacks, leaks of sensitive PII, subversion of existing encryption measures, arbitrary code execution on the server, access to hashed API keys or passwords.

### Critical-Level Vulnerabilities

These vulnerabilities could cause a complete system compromise or a catastrophic data breach.

* **Bounty:** $3,000
* *Examples:* Complete authentication bypass, cloud environment access or takeover, direct access to the database.

## How to Report a Vulnerability

We ask that you do not disclose any potential vulnerability publicly before it has been resolved. Please use GitHub's private vulnerability reporting feature to submit your findings. This ensures your report is delivered directly and securely to our team.

1.  Navigate to the main page of the repository.
2.  Under the repository name, click on the **Security** tab.
3.  Read all previously published advisories to ensure your submission is not a duplicate.
      1. **Note:** if you ignore this step, your submission and future reports may be dismissed immediately.
4.  In the left sidebar, click on **Report a vulnerability**.
5.  Fill out the form with all the necessary details, including:
    * A clear description of the vulnerability.
    * The steps required to reproduce it.
    * The potential impact of the vulnerability.
    * Any proof-of-concept code, screenshots, or videos that can help us understand the issue.
6.  Click **Submit report**.

Our team will review your submission and get back to you as soon as possible.

## What to Expect After You Submit a Report

Once you've submitted your report via GitHub's private vulnerability reporting feature, here’s how our process typically unfolds:

- **Triage and Acknowledgment:** Our security team will first acknowledge the receipt of your report, usually within 2-3 business days. We will then conduct an initial review to confirm that the report is understandable, reproducible, and not a duplicate of a previously submitted vulnerability. If we need more information, we will communicate with you directly through the GitHub advisory.

- **Validation and Severity Assessment:** After the initial triage, our team will thoroughly validate the vulnerability. We will assess its impact and assign a severity level based on the categories defined above. This assessment determines the final bounty amount. We will notify you of our findings and the confirmed bounty.

- **Remediation:** Our engineering team will prioritize and work on a fix for the validated vulnerability. The timeline for remediation can vary based on the complexity of the issue and our release schedule. We are committed to keeping you informed of our progress.

- **Bounty Payout:** Once the vulnerability has been successfully remediated and the fix has been deployed, we will initiate the bounty payment process. Our team will reach out to you to securely coordinate payment details. Please allow up to 30 days after the fix is deployed for the payment to be processed.

- **Public Disclosure and Recognition:** After the patch is live, we will work with you to coordinate public disclosure. We will create a public security advisory on GitHub, detailing the vulnerability and the fix. We are happy to give you full credit for your discovery in the advisory. If you prefer to remain anonymous, please let us know.

## Thank You!

Like the billions of neurons working together in our brain, your contributions help us enhance the robustness of Cerebrum's security. We appreciate your collaboration and look forward to working together to improve our cybersecurity defenses! Thank you for your help and for being a good samaritan!
