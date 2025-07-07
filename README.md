# RPA_Challenge_Invoice_Extraction
UiPath bot for extracting and uploading invoice data based on due dates

[![Watch the video](https://img.youtube.com/vi/msx0Xek9tuY/0.jpg)](https://youtu.be/msx0Xek9tuY)


# 📄 RPA Challenge Invoice Extraction Bot (UiPath)

This UiPath automation bot extracts invoice data from a multi-tabbed web interface on the **RPA Challenge** site. It dynamically filters invoices by **due date** and uploads the processed data as an Excel file, completing the task in **under 47 seconds**.

---

## 🚀 What It Does

✅ Automates invoice processing with the following steps:
1. Launches browser and navigates to the invoice challenge site  
2. Iterates through 3 tabs (each with 4 invoice entries)  
3. Checks the **Due Date** of each invoice — only processes invoices **past due**  
4. Extracts required details from the **table and invoice preview**
5. Populates the data into an Excel file
6. Uploads the completed Excel sheet back to the site

---

## 🧠 Logic Highlights

- Conditional logic based on **Due Date** (`DueDate < Today`)
- Tab navigation using dynamic selectors
- Accurate data scraping from both **table entries** and **invoice previews**
- Fast and robust design — processed in **< 47 seconds**

---

## 🔧 Technologies Used

- ✅ UiPath Studio
- ✅ Excel Activities
- ✅ Web Automation
- ✅ Dynamic Selectors
- ✅ Date Filtering Logic
- ✅ Element Navigation Across Tabs

---

## 📁 Project Structure

RPA_Challenge_Invoice_Extraction/
├── Main.xaml
├── project.json
├── Input/
│ └── (if used: sample invoices / templates)
├── Output/
│ └── example.csv
├── README.md


---

## ▶️ How to Run

1. Open the project in **UiPath Studio**
2. Run `Main.xaml`
3. Ensure internet access is enabled and the challenge site is reachable
4. The bot will:
   - Navigate through all three tabs
   - Filter and extract invoice data
   - Save an csv file
   - Upload the csv back to the site

---

## 💡 What I Learned

- Navigating and extracting data across **tabbed web interfaces**
- Using **If conditions** to control invoice filtering logic
- Managing Excel writing and uploading via browser
- Improving speed with optimized selectors and workflows

---

## 👤 Author

**Jerry Abraham**  
[GitHub](https://github.com/jerryab31)

---

