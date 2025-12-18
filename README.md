# 💎 Bitwarden valut Dedupe and cleaner

Clean bitwarden vault from duplicates entries with easy, sleek, client-side powerhouse designed to meticulously clean and optimize your exported Bitwarden JSON file.
And the best part is Zero-installation required it run on the browser so you can use it on the go **[bwdedup](https://bitwarden-valut-cleaner.pages.dev)**.

## 🔒 Uncompromising Security: Client-Side Only

This tool operates **entirely within your browser**. No data from your vault is ever transmitted to any external server. The JSON file is loaded, processed, and saved locally, ensuring your sensitive credentials remain absolutely secure and private.

## ✨ Elite Features for a Pristine Vault

| Feature                         | Description                                                                                       | Impact                       |
| :------------------------------ | :------------------------------------------------------------------------------------------------ | :--------------------------- |
| **Pure Client-Side Operation**  | Zero dependencies, zero server calls. Just open the HTML file and go.                             | Maximum Security & Privacy   |
| **Advanced URI Matching**       | Go beyond simple URL comparison to catch subtle duplicates across subdomains and paths.           | Superior Duplicate Detection |
| **Flexible Detection Criteria** | Choose from `Name + Username + URI`, `Name + URI`, or `Exact JSON Match`.                         | Granular Control             |
| **Interactive UI Refinement**   | A dark-themed, Bitwarden-inspired interface with enhanced checkboxes and clear status indicators. | Enhanced User Experience     |
| **Individual Entry Management** | View, edit, or delete entries directly before exporting the final clean vault.                    | Total Data Control           |

## 🌐 Advanced URI Matching

The most common source of "false negatives" in duplicate detection is the slight variation in URLs for the same service (e.g., login pages vs. main pages). I solved this with three matching modes, accessible via the **"Duplicate Detection Options"** button:

1. **Full URI (Default)**: Matches the entire URI string.
2. **Hostname Only**: Matches only the hostname (e.g., `accounts.google.com` will match `accounts.google.com/login`).
3. **Main Domain Only (Recommended)**: Matches only the top-level domain (e.g., `google.com` will match all Google subdomains and paths). **This is the key to eliminating duplicates from the same service.**

## 🚀 Quick Start: Achieve Vault Nirvana

1. **Export Your Vault**: Export your Bitwarden vault as a **JSON** file.
2. **Launch the Tool**: goto **[bwdedup](https://bitwarden-valut-cleaner.pages.dev)** in any web browser.
3. **Upload**: Click **"Upload JSON"** and select your exported file.
4. **Configure Detection**:
   - Select your primary matching criteria (e.g., "Name + Username + URI").
   - Click **"Duplicate Detection Options"** and select **"Main Domain Only"** for the most effective cleanup, then click **"Save Options"**.
5. **Detect & Review**: Click **"Detect duplicates"**. The table will highlight and automatically check the duplicates.
6. **Cleanse**: Click **"Remove Selected"** to purge the marked duplicates.
7. **Export**: Click **"Export Cleaned Vault"** to download your new, optimized JSON file.

---

**_Disclaimer_**: This is a community-driven tool and is not officially affiliated with or endorsed by Bitwarden. Use at your own discretion.
