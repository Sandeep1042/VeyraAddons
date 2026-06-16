# VeyraAddons
This repository have custom script (add-on) for Veyra web-game which can be used with  Tampermonkey

## Installation Guide

Follow these instructions to deploy any userscript from this repository into your local browser environment using the **Tampermonkey** web extension.

### 1. Prerequisites
Ensure a modern userscript manager is installed and running on your active browser profile:
* **Google Chrome / Brave / Edge:** [Tampermonkey via Chrome Web Store](https://chromewebstore.google.com/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo)
* **Mozilla Firefox:** [Tampermonkey via Firefox Add-ons](https://addons.mozilla.org/en-US/firefox/addon/tampermonkey/)

### 2. Deployment Steps

1. **Locate the Target Script:**
   Navigate into the repository folders above and click on the specific `.js` script file you wish to install.

2. **Access the Raw Source:**
   * Click the **"Raw"** button located at the top-right corner of the code presentation frame. This loads the clean, unformatted script text directly into the viewport Or take you to the tampermonkey code editor.
   * Click the install button on the top left of your screen Or else copy the code and proceed to next step.

4. **Initialize the Tampermonkey Workspace:**
   * Click your browser's Tampermonkey toolbar icon and open the **Dashboard**.
   * Click the **`+` (Add Script)** icon tab to instantiate a blank workspace editor frame.

5. **Compile and Overwrite:**
   * Copy the entire raw code block from your browser window (`Ctrl + A` then `Ctrl + C`).
   * Select all default template text inside the Tampermonkey editor and paste your script directly over it.

6. **Commit and Save:**
   Go to **File** in the editor's upper toolbar menu and select **Save** (or press `Ctrl + S` / `Cmd + S`).

7. **Validation:**
   Navigate directly to the platform specified inside the script's script header (`@match` metadata rules). The automation engine will automatically bootstrap and execute once the document lifecycle reads ready.

---
