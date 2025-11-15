# Inventory Scanner (HTML + Barcode)

A **single-file** web app that turns any phone (or laptop) into an inventory scanner.

* Scan barcodes with the camera  
* Add description & quantity  
* Persists data in the browser (IndexedDB)  
* Export to CSV  

No server, no install – works 100% offline.

---

## Live Demo

**GitHub Pages** (replace `YOUR-USERNAME` with your GitHub handle):

[https://YOUR-USERNAME.github.io/inventory-scanner/](https://YOUR-USERNAME.github.io/inventory-scanner/)

---

## How to Use

1. **Open** `inventory.html` in any modern browser (Safari, Chrome, Edge, Firefox).  
2. On a phone, allow camera access – the rear camera starts automatically.  
3. Scan a barcode → the code appears.  
4. Type a **description** (optional) and **quantity**, then tap **Add**.  
5. Adjust quantities with **+1 / -1** or **Del**.  
6. Tap **Export CSV** to download a spreadsheet-ready file.

---

## Run Locally

```bash
git clone https://github.com/YOUR-USERNAME/inventory-scanner.git
cd inventory-scanner
open inventory.html   # macOS
# or just double-click the file
