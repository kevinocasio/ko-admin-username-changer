# KO Admin Username Changer

> Lightweight WordPress plugin to safely change your WordPress username and harden security without database scripts or session dropouts.

## Overview

WordPress permanently locks the username field in user profiles. **KO Admin Username Changer** unlocks this limitation, allowing site owners and administrators to safely change their login username directly within the dashboard.

## Features

* **Direct DB Mutation:** Safely updates the `user_login` column in the database without SQL scripts.
* **Instant Session Refresh:** Cleans user cache and refreshes auth cookies so you stay logged in.
* **Input Validation:** Prevents illegal characters, spaces, empty strings, and duplicate usernames.
* **Zero Front-End Assets:** Pure PHP execution with 0 bytes of extra CSS or JS loaded on public pages.
* **Clean Single-Card UI:** Centered, distraction-free control panel following the KO Design System.

## Installation

1. Click the green **`< > Code`** button at the top of this repository and select **Download ZIP** (or download from [Releases](../../releases)).
2. In your WordPress admin dashboard, navigate to **Plugins -> Add New Plugin -> Upload Plugin**.
3. Choose the downloaded `.zip` file and click **Install Now**.
4. Click **Activate Plugin**.
5. Manage settings directly under the **KO Plugins** dashboard menu.

---

## Author & Support

* **Author:** [Kevin Ocasio](https://kevinocasio.com/)
* **Plugin Page:** [KO Admin Username Changer on KevinOcasio.com](https://kevinocasio.com/wordpress-plugins/ko-admin-username-changer/)
* **WordPress Plugins:** [Free WordPress Plugin Directory](https://kevinocasio.com/wordpress-plugins/)
* **Software Portfolio:** [Live Projects & Digital Assets](https://kevinocasio.com/portfolio/)
* **Tools & Resources:** [Recommended Tech Stack & Tools](https://kevinocasio.com/tools/)
* **License:** GPL-2.0-or-later
