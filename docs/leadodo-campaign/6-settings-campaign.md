---
sidebar_position: 6
---

# Step 6: Settings Campaign

Now that your email sequence is ready, it’s time to configure the final campaign settings in Smartlead. This step includes selecting sender accounts, setting your schedule, and defining how the campaign runs.

You’ll see this screen after clicking **Save & Next**:

---

## 📤 Sender Accounts

Click **“Choose Sender Accounts”** to select which inboxes will be sending this campaign.

- If you’ve added multiple Google Workspace inboxes, select all of them.
- Smartlead will automatically rotate between the inboxes to increase deliverability and avoid limits.

---

## 🕒 Schedule Campaign

Click **“Schedule Campaign”** to configure the sending schedule for your campaign.

You’ll see the screen below:

#### ✅ Recommended Settings

- **Time Zone**: Set to your target audience (e.g. Europe/Amsterdam)
- **Send Days**: Monday to Friday ✅ (Avoid weekends)
- **Hours**: 08:00 – 16:00
- **Send Interval**: Set to every **85 minutes**  
  Smartlead will auto-randomize between 30–60 seconds per email to mimic human behavior.

### 📈 Gradual Sending Volume (Golden Rule)

To build a healthy sending reputation and **avoid landing in spam**, you must slowly warm up your inboxes.

Use this rule:

| Week       | Max Emails per Account/Day |
|------------|-----------------------------|
| Week 1     | 5 emails                    |
| Week 2     | 10 emails                   |
| Week 3     | 15 emails                   |
| Week 4+    | 20 emails                   |

❗ **Never start at full volume** — this will damage your domain reputation and reduce deliverability.

### 📅 Additional Fields

- **Start Date**: You can leave blank to start immediately, or choose a future date
- **Max Leads per Day per Campaign**: Set this to something like 1000, we will not use this to put a limit on our campaign.

When you're done, click **Save** to apply the schedule settings.


💡 **Tip:** Avoid sending on weekends or outside business hours. Starting your campaign slowly and cautiously helps build a healthy sender reputation — which is essential for long-term deliverability and success.


---

## ⚙️ Campaign Settings

After scheduling your campaign, click **"Modify Settings"** to fine-tune how Smartlead handles delivery, tracking, and reply behavior.

Below is a recommended setup that maximizes deliverability and protects your sender reputation.

### 🏷 Campaign Name

At the top, name your campaign clearly so you can recognize it later.  
Example: `NL_Dentists_March_2025`

### ✋ Stop Sending When Lead...

Select: ✅ **Replies to a message**

This ensures Smartlead immediately stops all follow-ups when a prospect responds.

### ✉️ Optimise Email Delivery

Enable both checkboxes:

- ✅ **Boost your deliverability by sending emails in plain text, without HTML**
- ✅ **Force plain text as content type**

This helps avoid spam filters and mimics how real people send emails.

### 🔍 What Shouldn't We Track?

Check both boxes:

- ✅ **DON’T track email opens**  
- ✅ **DON’T track link clicks**

Tracking opens and clicks increases the chance of being flagged as spam.  
Leadodo campaigns do not rely on open data — we focus only on real replies.

### 🧠 Intelligent AI Lead Categorisation

Select: ✅ **Intelli-categorise replies using Smartlead’s AI**

Leave the default response types as they are (e.g. Interested, Meeting booked, Auto Reply, etc.).
This allows Smartlead to automatically label replies for easier follow-up management later.

### 📊 Prioritise Sending Pattern

Set the slider to:

> **70% Follow-ups / 30% New Leads**

This ensures the system focuses more on following up with existing prospects before reaching new ones — improving reply rates and reducing wasted leads.

### 🧍‍♂️ Company-Level Auto-Pause

Enable: ✅ **Auto-pause if one of the leads from the same domain replies**

This prevents multiple people from the same company receiving outreach after someone already responded.

### 🚀 Enhanced Email Sending & Delivery

Enable: ✅ **Auto-analyse leads' mailbox email service providers**

This improves matching between sender and recipient (e.g. Gmail-to-Gmail), increasing deliverability.

### 📤 Isolated Lead Email Provider Sending

Choose: ✅ **Send To All**

This keeps things simple and works well for most campaigns.

### 🔐 High Bounce Rate Auto-Protection

Enable: ✅ **Activate auto-pause protection from bounces**

Set the threshold to `4` — if bounce rate goes above this, Smartlead will auto-pause to protect your sender reputation.

### ❌ Unsubscribe (Optional)

In most B2B campaigns, **you do not need to include an unsubscribe message** — especially when sending plain text emails.

Leave this setting **unchecked**, unless your target region requires it by law (e.g. some parts of the EU or Canada).

📌 Note:  
If you send emails in **plain text only**, Smartlead will not allow an unsubscribe header anyway — and that’s fine.  
Think of it like reaching out to a business contact manually — you wouldn’t include an unsubscribe link in a personal message either.


---

Once everything is set, return to the overview screen and double-check your selections. You’re now ready to launch your campaign!
