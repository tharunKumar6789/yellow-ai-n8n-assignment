# Yellow.ai n8n Automation Assignment

🎥 Video Explanation Link:  
------> https://drive.google.com/file/d/19AF8ukiXk4Tl2g55jJs6d5o-0KP6Pyu0/view?usp=sharing <------

## 👨‍💻 Tharun Kumar

This project is built using n8n to automate high-value lead detection from GitHub.

The workflow uses a schedule trigger to monitor stargazers of a GitHub repository.  
For every new user, it fetches detailed profile data using the GitHub API.  

The workflow filters users based on:
- Followers > 100 OR  
- Public repositories > 50  

Only high-value leads proceed further in the workflow.  

Then, OpenAI is used to analyze the user’s bio and company to generate a one-line personalized sales pitch.  

Finally, the user details and AI-generated pitch are sent to a Discord channel.  

## Logic Log
GitHub API rate limits are handled by using scheduled polling instead of continuous requests, ensuring controlled API usage and avoiding limit exhaustion.
