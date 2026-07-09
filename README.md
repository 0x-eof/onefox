# onefox
A `userChrome.css` tweak that merges the Firefox address bar (URL bar) and tabs into a single unified row. 
Designed with a strict focus on minimalism, stability, and visual consistency.

---

## Key Features
* **Responsive Design:** Resizing the window will not break, overlap, or clip any UI elements.
* **Uniform Aesthetics:** Some backgrounds are transparent (like the URL bar and bookmarks bar background), this allows you to use your favorite Firefox theme without looking broken.
* **No extra fluff:** You want a one line Firefox and nothing more.
* **More space for tabs:** This edit gives more space to tabs rather than the URL bar.

---

## Installation
1. **Enable Custom Stylesheets in Firefox:**
   * Open a new tab and type `about:config` in the address bar.
   * Accept the warning.
   * Search for `toolkit.legacyUserProfileCustomizations.stylesheets` and set it to **true**.

2. **Locate your Profile Directory:**
   * Go to `about:profiles`.
   * Find **Root folder** and click **Open Folder**.

3. **Deploy the CSS:**
   * Inside your profile folder, create a new directory named `chrome` (if it doesn't already exist).
   * Paste the `userChrome.css` file inside that folder.

4. **Restart Firefox:**
   * Close all Firefox windows and relaunch the browser for the changes to take effect.
