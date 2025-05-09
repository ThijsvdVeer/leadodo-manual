---
sidebar_position: 3
---
# Step 3: Analyse Businesses

It’s time to put Leadodo’s AI to work.

In this step, we’ll analyze your lead list, identify poorly designed websites, enrich the data with useful metrics, and generate personalized AI copy — all in just a few clicks.

---

## 🔐 Configure License Key & API Keys

Launch the Leadodo application.

On the right side of the screen, you’ll find the **API key input fields**.

Fill in the following keys (from previous setup steps):

| Key Type       | Where to Get It         |
| -------------- | ----------------------- |
| License Key    | Provided after purchase |
| Screenshot API | From SiteShot (Step 4)  |
| OpenAI API     | From OpenAI (Step 5)    |
| PageSpeed API  | From Google (Step 6)    |

After entering the keys, click **Save API Keys**.

✅ Once saved, your application is fully configured and ready to analyze.

---

## 📂 Concurrent Workers

Below the **Manual** button in the Leadodo app, you'll see settings for **Concurrent Workers**. These control how many leads the app processes at the same time — making it much faster when set correctly.

Here’s how each one works:

### 🔢 Worker Types

| Worker Type  | Description                                                  |
| ------------ | ------------------------------------------------------------ |
| **AI** | Controls how many prompts are sent to OpenAI in parallel     |
| **SS** | Controls how many screenshots SiteShot captures at once      |
| **GS** | Controls how many PageSpeed API requests are run in parallel |

### 🧠 Recommended Settings

#### 🧠 AI (OpenAI Workers)

This depends on your **OpenAI Tier**. The higher your tier, the more requests you can safely run in parallel.

| Tier   | Requirements                  | Suggested AI Workers           |
| ------ | ----------------------------- | ------------------------------ |
| Free   | No payment                    | Not supported                  |
| Tier 1 | $5 deposit                    | 5 workers                      |
| Tier 2 | $50 spent, 7+ days active     | 10 workers                     |
| Tier 3 | $100 spent, 7+ days active    | 20 workers ✅ Best performance |
| Tier 4 | $250 spent, 14+ days active   | 25+ (Advanced use)             |
| Tier 5 | $1,000 spent, 30+ days active | 30+ (High scale)               |

> A "worker" means one row of your lead list is processed at a time — so 20 AI workers = 20 leads analyzed in parallel.

#### 🖼 SS (Screenshot Workers – SiteShot)

Your SiteShot plan determines how many screenshot workers you can use:

| SiteShot Plan | Max Concurrent Workers |
| ------------- | ---------------------- |
| Lite          | 10                     |
| Optimal       | 25 ✅ Faster results   |

#### ⚡ GS (Google PageSpeed Workers)

This field should always be set to **50**. That’s the recommended safe maximum for fast and stable performance.

Set your worker values based on your subscription levels for each service — this helps you get the most out of Leadodo without hitting rate limits or delays.

---

## 📂 Preparing Your Excel File

Before uploading your lead list into the Leadodo app, you need to make sure the file is clean, well-structured, and saved in the correct format.

### ✅ Convert to `.xlsx` Format

Leadodo requires your file to be saved as an **Excel `.xlsx` file** — not `.csv`.

If you received a `.csv` file (from MillionVerifier, FindyLeads, or elsewhere), follow these steps:

1. Open the `.csv` file in Excel.
2. Click **“File” > “Save As”**.
3. Choose **Excel Workbook (.xlsx)** as the file format.
4. Save the file.

### 🛠 Fix Columns if Data is in One Column

If all your data appears in **a single column** instead of multiple, you need to split it:

1. Select **Column A** (where the data is stuck).
2. Go to the **“Data”** tab.
3. Click **“Text to Columns”**.
4. Select **“Delimited”**, click **Next**.
5. Check **“Comma”**, then click **Finish**.

Now your data will be separated into correct columns.

### 🔍 Filter for Good Emails Only

Only use emails marked as **"good"** in the `quality` column.  
If your file contains `quality` and `result` columns (from MillionVerifier):

1. Select all your data.
2. Click **“Insert” > “Table”** to make the sheet filterable.
3. Use the filter in the `quality` column to select only **"good"**.
4. Copy the filtered data into a new `.xlsx` file.

This ensures you're only sending to verified, safe email addresses.

### 📄 Required Columns

The final file should contain at least these **5 columns**:

1. Business Name  
2. Email  
3. Website URL  
4. First Name  
5. Last Name  

> If First/Last Name aren’t available, just include empty columns with those headers.

💡 **Column names do not need to be exact.**  
For example, `website`, `url`, or `domain` will all be recognized as Website.

Once your data is cleaned, filtered, and saved in `.xlsx` format, you're ready to import it into Leadodo!

---

## 🧠 Starting the Analysis

### 1. Select Your Excel File

- On the **left side** of the application, click **“Select Excel File”**.
- For best results, place your file inside a new folder — name it anything you like.

### 2. Select Output Folder

- After selecting the Excel file, you’ll be prompted to choose an **output folder**.
- We recommend using the **same folder** as your Excel file for better organization.

---

## 🔄 Column Mapping

Next, a **Column Mapping** window will appear.

This is where you match your columns to the required fields mentioned earlier. If a column isn’t relevant, just leave it blank or set it to:

- **Do Not Import** – Skips the column entirely
- **Custom Variable** – Keeps the column in the final result, useful for fields like `Phone`, `LinkedIn`, or `Location`

Custom variables can be helpful later if you plan to call leads or enrich them further.

---

## 🌍 Set Language & Tone

- **Language**: Type the language you want the AI to use (e.g. `English`, `Spanish`, `Dutch`).
- **Tone of Voice**: Optionally, you can set a tone (e.g. `Professional`, `Casual`, `Bold`, `Friendly`) — similar to how you would in ChatGPT.

---

## ⚙️ Final Settings

- **Remove Duplicates**: For now, leave this **unchecked**.
- When ready, click **Run All Scripts**.

---

## 🕓 What to Expect

Once the process starts, sit back and let Leadodo work its magic.

- It can take **up to 4 hours** to finish — especially with large lead lists.
- If the app seems stuck: **don’t quit**. As long as it hasn’t canceled, it’s still running.
- If something truly breaks, the app will **automatically stop** and cancel the process.

> ⚠️ **Important:**
> During processing, the app creates and updates multiple Excel files. **Do not open any of them** while the app is running — doing so may interrupt the process and cause errors.

---

## ✅ When It’s Done

When the analysis is complete, you’ll find two key output files:

| File Name              | Purpose                       |
| ---------------------- | ----------------------------- |
| `leadodo-final.xlsx` | Full results with all columns |
| `leadodo-final.csv`  | Cleaned version for Smartlead |

You're now ready to move on to the next step: importing your leads into Smartlead.
