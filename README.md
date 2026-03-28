# Yellow.ai n8n Automation Assignment

🎥 Video Explanation Link:  
------> https://drive.google.com/file/d/19AF8ukiXk4Tl2g55jJs6d5o-0KP6Pyu0/view?usp=sharing <------

## 👨‍💻 Tharun Kumar

This project is built using n8n to automate lead generation from GitHub.

The workflow starts with a schedule trigger that runs automatically at intervals.  
It fetches users who starred a GitHub repository using the GitHub API.  
Then it extracts important details like username and profile link.  

Next, it retrieves complete profile information such as followers, bio, and repositories.  
The workflow filters high-value users based on conditions (followers > 100 or repos > 50).  

After filtering, OpenAI is used to generate a personalized one-line sales pitch.  
Finally, the lead details along with the AI-generated pitch are sent to a Discord channel.  

This project demonstrates automation, API integration, and AI usage in a real-world scenario.  
All sensitive credentials are removed for security purposes.  


