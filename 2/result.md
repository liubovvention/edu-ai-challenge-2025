# 1. Title

**Logout Button Unresponsive in Safari Browser**

# 2. Description

When attempting to log out of the web application using the "Logout" button, the button does not respond or trigger any action. This issue occurs **only in the Safari browser**. Other browsers (e.g., Chrome, Firefox, Edge) handle the logout functionality as expected.

# 3. Steps to Reproduce

1. Open the web application in the **Safari browser** (macOS or iOS).
2. Log in with valid credentials.
3. Once logged in, click on the "Logout" button located in the navigation bar.
4. Observe the behavior.

# 4. Expected vs Actual Behavior

**Expected:**
Clicking the "Logout" button should terminate the user session, clear any authentication tokens, and redirect the user to the login screen or homepage.

**Actual:**
Clicking the "Logout" button has no effect. No visual feedback or redirection occurs. User remains logged in and session persists.

# 5. Environment (if known)

* Browser: Safari (confirmed on version 17.4 and 17.5)
* OS: macOS Sonoma / iOS 17
* Web App Version: \[1.0.1]
* Authentication Method: \[JWT]

# 6. Severity or Impact

**High** – Prevents users from logging out securely, which may pose a **security risk** and impacts user experience on Safari, a widely used browser on macOS and iOS devices.

