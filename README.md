## 🤖 Oneview Bot Installation

Oneview is whatsapp one-view saver. Below are the installation instructions for Termux (Android).

<details>
<summary>⚡ Click to View Installation Instructions</summary>
<br>

### 🛠️ Termux Installation Guide (Android)

1.  **Install Termux**
    Download and install Termux from the Google Play Store or F-Droid:
    
    * **Google Play Store Link:**
        [https://play.google.com/store/apps/details?id=com.termux](https://play.google.com/store/apps/details?id=com.termux)

2.  **One-Command Install & Run**
    After opening Termux, copy and paste this single command:

    ```bash
    pkg update -y && pkg install git nodejs -y && git clone https://github.com/coderxsa/oneview.git && cd Oneview && npm install && node index.js
    ```
    
    * This command updates packages, installs necessary dependencies (`git`, `nodejs`), clones the repository, installs project dependencies (`npm install`), and attempts to start the bot (`node index.js`).

---

### ⚠️ Troubleshooting and Manual Run

* **Manual Start:** If the bot does not start automatically after the installation command, you can run it manually by typing:
    ```bash
    node index.js
    ```
* **Initial Setup:** When prompted by the bot, **enter your phone number** in the required format to complete the setup process.

### Additional Information

* **Bot Sign/Creator:** Developed by **coderxsa**
* **OptLink (Optional):** We recommend these resources for further information or optional hosting:
    * **External Hosting:** [bot-hosting.net](https://bot-hosting.net/)
    * **Community/Resource Link:** [optiklink.com/home](https://optiklink.com/home)

</details>
