How to use this script

🧰 You Need
Google Account (Gmail)

Blogger Account (already have a blog)
Access to Google Apps Script
RSS feeds from news sources (example: Kompas, Sindonews)

📜 Steps
1. Open Google Apps Script
Visit script.google.com
Click + New Project

2. Copy and Paste Script Txt

3. Activate Blogger API
Click Services menu (puzzle icon on the left)
Click + add service
Search Blogger API then click Add

4. Retrieve Your Blog ID
Log in to Blogger
Select your blog
See the URL, for example:
Edit
https://www.blogger.com/blog/posts/1234567890123456789
Then the blog ID is: 1234567890123456789
Replace CHANGE_WITH_Your_BLOG_ID in the code with that ID.

5. Run and Allow Access
Click the fetchAndPostRSS function
Click the icon ▶️ to run
Allow access to your Google account

6. Create Automatic Schedule
Click the Triggers menu (clock icon ⏰ on the left)
Click + Add Trigger
Select the function: fetchAndPostRSS
Choose the time for example: Time-driven → Hourly
