# 🚀 Quick Start Guide - Nium Capability Explorer

Get up and running in 5 minutes!

---

## **STEP 1: Install Python (if you haven't already)**

Download from: https://www.python.org/downloads/

**Important**: During installation, check the box: ✅ "Add Python to PATH"

Verify installation:
```bash
python --version
```

---

## **STEP 2: Install Required Packages**

Navigate to your project folder and run:

```bash
pip install -r requirements.txt
```

This installs:
- 🌊 **Streamlit** - The web app framework
- 📊 **Pandas** - Data handling
- 📑 **OpenPyXL** - Excel file support

---

## **STEP 3: Prepare Your Data Files**

Place these two files in the same folder as the Python script:

```
📁 Your Project Folder
├── 📄 nium_capability_explorer.py
├── 📄 requirements.txt
├── 📄 README.md
├── 📄 QUICKSTART.md (this file)
├── 📊 11th_April_FI_Payout_data.xlsx
└── 📊 11th_April_Non_FI_Data.xlsx
```

---

## **STEP 4: Run the App**

Open your terminal/command prompt in the project folder and type:

```bash
streamlit run nium_capability_explorer.py
```

**You should see:**
```
  You can now view your Streamlit app in your browser.

  Local URL: http://localhost:8501
  Network URL: http://192.168.x.x:8501
```

The app automatically opens in your browser! 🎉

---

## **STEP 5: Start Exploring**

1. **Select a dataset** - FI or Non-FI
2. **Apply filters** - Country, Payment Mode, Currency, TAT
3. **View results** - See matching corridors
4. **Expand details** - Click 🔹 to see full information
5. **Download data** - Select columns and export as CSV or Excel

---

## **Stop the App**

Press `Ctrl+C` in the terminal where you ran the command.

---

## **Troubleshooting**

### **"Python command not found"**
Python isn't in your PATH. Reinstall Python and check "Add Python to PATH" during setup.

### **"No module named 'streamlit'"**
Run: `pip install -r requirements.txt`

### **"File not found: 11th_April_FI_Payout_data.xlsx"**
Make sure the Excel files are in the same folder as the Python script.

### **Port 8501 already in use**
Run on a different port:
```bash
streamlit run nium_capability_explorer.py --server.port 8502
```

---

## **Share with Your Team**

Once running on your local machine:

**Local Network** (if on same WiFi):
- Use the "Network URL" from the output above
- Share the URL like: `http://192.168.x.x:8501`

**Cloud** (Recommended for larger teams):
1. Create a GitHub account (free)
2. Push this code to a GitHub repo
3. Go to https://share.streamlit.io/
4. Deploy in one click
5. Get a public URL to share

---

## **Common Commands**

| Task | Command |
|------|---------|
| Start app | `streamlit run nium_capability_explorer.py` |
| Install packages | `pip install -r requirements.txt` |
| Stop app | `Ctrl+C` (in terminal) |
| Run on port 9999 | `streamlit run nium_capability_explorer.py --server.port 9999` |
| Clear cache | Press `C` in the app |

---

## **Need Help?**

Check the full README.md for:
- Detailed feature explanations
- Configuration options
- Deployment guides
- Troubleshooting section

---

**That's it! You're all set!** 🎊

Enjoy exploring Nium's capabilities! 🌍💳✨
