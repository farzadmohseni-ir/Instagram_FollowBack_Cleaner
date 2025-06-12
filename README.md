# Instagram_FollowBack_Cleaner
A Python-based tool to analyze your Instagram follow data, identify users who don’t follow you back, and batch unfollow them safely.


# 📉 Instagram Follow Cleaner

A powerful and simple Python tool to help you identify Instagram users who don't follow you back — and unfollow them safely in controlled batches.

---

## 🚀 Features

- ✅ Login with Instagram credentials (supports 2FA)
- 📥 Load data from official Instagram **Data Export**
- 🔍 Detect non-followers (users you follow, but who don't follow you back)
- 📊 Export non-followers to CSV
- 🔄 Batch unfollow non-followers
- 💾 Save unfollow progress for later sessions
- 🛡️ Human-like delays to avoid being flagged by Instagram


---

## 📁 How to Get Your Instagram Data (Step-by-Step)

1. Go to [Instagram Data Download Page](https://www.instagram.com/download/request/)
2. Login to your Instagram account
3. Select **JSON** format
4. Enter your email and request the data
5. You'll receive a ZIP file via email within a few minutes
6. Unzip the file and locate:
   - `followers_1.json`
   - `following.json`
   (usually found inside `followers_and_following` folder)

7. Place these two files in the **same folder** as the script.

