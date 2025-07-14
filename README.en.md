# NKUST SEE Platfrom

NKUST SEE Platfrom is a platform designed for professors at our university to share YouTube videos and perform related data analysis. The main features of the platform include:
- **Personal homepage**: View comment and favorite records.
- **Statistical charts**: Analyze viewing, favoriting, and commenting data.
- **Rankings**: Generate various rankings based on view counts (overall, last 7 days, last 30 days, etc.).
- **YouTube video playback page**


### Technical Stack & Deployment

- **Backend**：
  - Used **Django** as the backend framework.
  - Integrated **YouTube Data API v3** to parse and extract metadata from uploaded YouTube videos.
  - Implemented user analytics using **Pandas** and **Django User Agents** to summarize daily and weekly usage patterns, including device types.
  - Integrated **Mailgun** for password reset and registration success emails, improving user account management and communication.
- **Frontend**：
  - **jQuery** for AJAX data fetching and DOM manipulation, based on data provided by the backend.
  - Interactive charts for frequency data and statistical summaries are rendered on the frontend using **Chart.js**, based on data provided by the backend.
- **Database**：MySQL
- **Server Deployment**：Hosted on a university Linux server with Apache, I handled the full deployment including configuration, testing, and optimization.

### System Features

- View professors’ comments and favorite records.
- Analyze and visualize professors’ viewing, favoriting, and commenting data.
- Generate rankings based on view counts, with filters for overall, last 7 days, and last 30 days.
- Provide an embedded video playback interface.

## Screenshot
![screencapture-nkustsee-website-login-2024-12-11-08_33_33](https://github.com/user-attachments/assets/8a5aeade-f59e-4647-a0e7-9947c7050b71)
![image (4)](https://github.com/user-attachments/assets/bbd24dbb-e78a-4f01-8ce8-c77334cfcf47)
![image (5)](https://github.com/user-attachments/assets/6013adc8-d4c2-4c4c-a74b-43ab6d0bf37d)
![image (6)](https://github.com/user-attachments/assets/ff860db1-3e88-4215-951c-ec3f6dd25d84)



