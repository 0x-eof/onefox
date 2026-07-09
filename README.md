# onefox
A `userChrome.css` tweak that merges the Firefox address bar (URL bar) and tabs into a single unified row.
<img width="1920" height="1044" alt="image" src="https://github.com/user-attachments/assets/e01aa4d8-201d-4ccc-9678-381c673a64df" />


---

## Key Features
* **Dynamic:** Resizing the window will not break, overlap, or clip any UI elements.
* **Uniform Aesthetics:** Some backgrounds are transparent (like the URL bar and bookmarks bar background), this allows you to use your favorite Firefox theme without looking broken.
* **No extra fluff:** You want a one line Firefox and nothing more, only 44 lines of code.
* **More space for tabs:** This edit gives more space to tabs rather than the URL bar.

---

## Installation
1. **Enable Custom Stylesheets and compact mode in Firefox:**
   * Open a new tab and type `about:config` in the address bar.
   * Accept the warning.
   * Search for `toolkit.legacyUserProfileCustomizations.stylesheets` and `browser.compactmode.show` and set both to **true**.
   * Right click in the Firefox UI and select **customize toolbar**.
   * At the bottom change de **density** to **compact**.

2. **Locate your Profile Directory:**
   * Go to `about:profiles`.
   * Find **Root folder** and click **Open Folder**.

3. **Deploy the CSS:**
   * Inside your profile folder, create a new directory named `chrome` (if it doesn't already exist).
   * Paste the `userChrome.css` file inside that folder.

4. **Restart Firefox:**
   * Close all Firefox windows and relaunch the browser for the changes to take effect.

...maybe in some systems you'll want to remove the lines 42 to 44 inside `userChrome.css` file if the tabs height are disaligned. 
