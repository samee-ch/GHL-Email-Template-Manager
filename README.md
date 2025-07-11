# 🧹GHL Bulk Delete Email Templates Tool

This is a **browser-based GHL Email Template Manager** that helps you **view and bulk delete email templates** from your GoHighLevel subaccount. Since GoHighLevel currently does not offer a native bulk delete option for email templates, this tool uses GHL's official **Delete Email Template API** to manage and delete templates efficiently.

---

## 🚀 Features

- ✅ Fetch all email templates from a specific subaccount
- ✅ View template names, IDs, and last updated times
- ✅ Select specific templates to delete (bulk delete supported)
- ✅ Delay between deletions to avoid API rate limits
- ❌ No server required — runs entirely in the browser
- 🔐 Uses your Private Integration Key securely (you control the data)

---

## 📌 Requirements

Before using the tool, ensure you have the following:

### 🔑 1. **Subaccount Location ID**
- You can find this in your GHL subaccount URL or from your agency dashboard.

### 🔐 2. **Private Integration Key**
- Go to **Settings → API → Create Private Key**
- When creating the key, make sure to enable the following permissions:
  - ✅ View Email Templates
  - ✅ Add/Edit/Update/Delete Email Templates

---

## 🛠️ How to Use

1. **Open the tool in your browser (index.html).**
2. **Fill in the required fields:**
   - Location ID (subaccount)
   - Private Integration Key
   - Optional: set a limit and delete delay (minimum recommended delay is **2 seconds** per template)
3. **Click “Fetch”** — it will show a list of all templates with name, ID, and last updated time.
4. **Select templates you want to delete** using the checkboxes.
5. **Click “Delete from GHL”** to start deleting templates one by one with the specified delay.
6. ⚠️ **Make sure to uncheck** any templates you don't want to delete.

---

## ⚠️ Notes

- This tool makes **direct API calls from the browser**, so your token will be exposed in browser memory — use only on trusted devices.
- Deletion happens **live** on your GHL account. Use with caution.

---

## 🧠 Why This Exists

GoHighLevel does not provide a bulk delete function for email templates. Agencies with hundreds of outdated templates need a fast, safe way to clean up accounts. This tool offers:

- 📈 **Faster operations**
- 🧩 **No backend needed**
- 🔄 **Full control over which templates are removed**

---

## 📌 SEO Keywords

`GHL bulk delete email templates`, `GoHighLevel template manager`, `delete GHL email templates`, `GoHighLevel automation tools`, `manage email templates GHL`, `GHL email cleanup`, `no-code GHL bulk template remover`, `browser based GHL tool`

---

## 📃 License

MIT — Free to use and modify.

