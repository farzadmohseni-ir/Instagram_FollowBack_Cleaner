# Instagram_FollowBack_Cleaner
A Python-based tool to analyze your Instagram follow data, identify users who don’t follow you back, and batch unfollow them safely.


<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/a/a5/Instagram_icon.png" width="100" alt="Instagram Logo">
</p>

<h1 align="center">📉 Instagram Follow Cleaner</h1>

<p align="center">
  <b>A powerful and simple Python tool to help you find and unfollow users who don't follow you back — safely, smartly, and in batches.</b>
</p>

---

## 🚀 Features

- ✅ Login with Instagram credentials (supports 2FA)
- 📥 Load data from official Instagram **Data Export**
- 🔍 Detect non-followers (users you follow, but who don't follow you back)
- 📊 Export non-followers to CSV
- 🔄 Batch unfollow non-followers
- 💾 Resume unfollowing in later sessions
- 🛡️ Randomized delays to mimic human behavior and reduce risk of detection

---

## 📁 How to Get Your Instagram Data (Step-by-Step)

📦 Instagram allows you to download all of your account data, including your followers and followings. Here’s how:

1. 🔗 Go to the [Instagram Data Download Page](https://www.instagram.com/download/request/)
2. 🔐 Log in to your account
3. 🗂️ Select **JSON** format (not HTML!)
4. 📧 Enter your email and request the data
5. ⏳ Wait for an email with a link to download your ZIP archive
6. 🗃️ After extracting the ZIP file, locate the following files:
   - `followers_1.json`
   - `following.json`  
     *(usually located inside the `followers_and_following/` folder)*

7. 📂 Move both files to the **same folder as the Python script** you're running

---

💡 *Note: You must request fresh data from Instagram each time you want updated results.*
