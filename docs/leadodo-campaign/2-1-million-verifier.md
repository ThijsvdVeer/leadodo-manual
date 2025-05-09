---
sidebar_position: 3
---

# Step 2-1: MillionVerifier

Before uploading your lead list into the Leadodo application, it’s critical to make sure **every email is verified and safe to use**. This prevents high bounce rates, protects your inboxes, and improves deliverability.

If you used **FindyLeads with MillionVerifier**, you already received a file with verified email results. Now we’ll clean that file to include only the best-quality leads.

---

## 🧼 Why Email Verification Matters

Sending emails to **invalid or risky addresses** can:
- Destroy your inbox reputation
- Cause your domain to be flagged
- Land future emails in the spam folder

💡 **Goal:** Only send emails to contacts with a **“good” quality rating.**

---

## 🛠 Fixing Column Formatting Issues

If your Excel file looks like this — with all the data stuck in a single column:

![Single Column Issue](/img/leadodo-manual-columns.jpg)

You’ll need to **split the data into separate columns** before continuing.

### ✅ How to Fix It in Excel:

1. **Select Column A** (the one where all the data is combined).
2. Go to the **“Data”** tab in the top menu.
3. Click on **“Text to Columns”**.
4. Choose **“Delimited”**, then click **Next**.
5. Select the checkbox for **“Comma”**, then click **Finish**.

Excel will now break the data into proper columns, making it easy to filter by `quality`, `result`, etc.

Once your columns are separated, proceed to filter by `good` quality as described earlier.

---

## 📥 Open Your Verified Excel File

In your file, you’ll see columns such as:

| quality | result     | free | role |
|---------|------------|------|------|
| good    | ok         | no   | no   |
| risky   | catch_all  | no   | no   |
| bad     | invalid    | no   | yes  |

We only want to keep **rows marked as "good"** in the **`quality`** column.

---

## ✅ Filter for Good Emails Only

1. Open the Excel file you received.
2. Select all your data.
3. Click **“Insert” → “Table”** to convert it into a filterable table.
4. In the `quality` column, click the filter arrow.
5. **Select only “good”** and press OK.

![Filter Example](/img/leadodo-manual-quality-excel.jpg)

---

## 📤 Create a Clean File

Now that your table shows only good emails:

1. Select all visible rows.
2. Copy and paste them into a **new Excel file**.
3. Save this new file as your **final clean list for Leadodo**.

---

## ⚠️ Optional: Handle Risky Emails

You can also create a second Excel file containing **risky emails** (`catch_all`). These addresses may still be valid, but sending to them increases your risk of bounces.

If you decide to use them:
- Only send to risky emails in a **separate, lower-volume campaign**
- Use inboxes that are fully warmed up
- Monitor bounce rates closely

🚫 Never mix risky or bad emails into your main campaign.

---

## ❌ What if You Didn't Use FindyLeads with MillionVerifier?

You can still verify emails manually by:

1. Creating an account at [https://millionverifier.com](https://millionverifier.com)
2. Purchasing credits
3. Uploading your own CSV lead list
4. Downloading the results and filtering by “good” as shown above

---

✅ Once your list contains only **good, verified email addresses**, you’re ready to proceed to the next step in Leadodo.

Skipping this step can result in **burned inboxes and failed campaigns**, so make sure you clean your data before importing it.
