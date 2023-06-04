# 1. Intoduction 
In this Major Project our main focus is to build an Interview Management System for digitally managing the interviews of any individual. The admin can view, add and delete all the users (candidates) according to their choice. Interviewer can also add and update interview questions. There are additional features like Resume Parser, and White board to enhance the interview process. In this way the interviewer can easily conduct interviews and select the right candidate.

# 2. Objectives
- To develop a job posting website and a resume scraper, which scrap the data from the resume uploaded on the job website.
- To develop an authentication system for admin and users. 
- To develop a video call system to take the interview virtually.
- To develop a code editor inside the interview management system .
- To integrate the resume scrapper which we have already developed, into the interview management system.

# 3. Software Desgin
![1](https://github.com/akshatprogrammer/ML-Recruitment-System/assets/67745418/bc125ea4-6043-4bc6-9f55-2df55c6f41b0)
<br>Architectural Design of the Project <br>

![2](https://github.com/akshatprogrammer/ML-Recruitment-System/assets/67745418/f59183c5-2a29-4b08-8613-1439b33f110f)

![3](https://github.com/akshatprogrammer/ML-Recruitment-System/assets/67745418/1a42c7cd-4d43-4687-a5b6-f5591dd27a4c)

# 4. Requirements 
## 4.1 Requirements

### 4.1.1 Hardware Requirements

- Webcam Enabled Device
- PC or Laptop
- Wifi Connection


### 4.1.2 Software Requirements

- Python Environment
- VS Code or PyCharm
- Xampp
- MySQL
- SMTP 
- ReactJS Environment
- Firebase
- WebRTC
- Socket
- Browser

## 4.2 Methodology
The methodology followed in this research involves the following steps: 
1. <b>Data Collection:</b> The first step was to collect data. For this, we have collected resumes from our classmates. We collected around 50 resumes. The collected data was stored in a database for further processing.
2. <b>Preprocessing:</b> The next step was to preprocess the collected data to extract useful information from it. The resumes were parsed to extract the candidate's name, contact details, education, work experience, skills, and certifications. 
3. <b>Feature Extraction:</b> The extracted data was then used to extract relevant features for each job posting and candidate. This was done using Natural Language Processing (NLP) techniques such as Named Entity Recognition (NER), Part-of-Speech (POS) tagging, and Sentiment Analysis. The features extracted for the job postings included the required skills, experience, and job description. The features extracted from the candidate's resume included the candidate's skills, experience, education, and certifications.
4. <b>Score Calculation:</b> Based on the extracted features, a score was calculated for each candidate. This was done using predefined criteria such as matching skills, years of experience, and education level. If the candidate's score exceeded a predefined threshold, the candidate was considered for the next stage. 
5. <b>Interview Scheduling:</b> An email was automatically sent to the candidate using the Smtplib library of Python. The email has the link and invitation to the virtual interview on the video conferencing platform. The interview schedule was automatically generated based on the candidate's availability and the availability of the interviewer. An admin can also manage interviews.
6. <b>Interview Taking:</b> The interview was conducted using the video conferencing platform, which Uses webRTC and Socket.io for API calls and establishing connections between peers and the interviewer could use the code editor to evaluate the candidate's programming skills in real time. For authentication, we are using Google OAuth. The code editor is made using the express framework and JDoodle API. Any code editor API can be used. One can also make its own code editor but that is out of the scope of this research paper, hence we have used already available options.
![4](https://github.com/akshatprogrammer/ML-Recruitment-System/assets/67745418/2d6dc140-1592-4e7b-8108-9351cee1725a)
![5](https://github.com/akshatprogrammer/ML-Recruitment-System/assets/67745418/d1be8c29-4366-41ea-8a7e-2d886eb30b88)
# 5. Components
1. [<b>Job Posting Website</b>](https://github.com/akshatprogrammer/jobDescription-BAAM)
2. [<b>BAAM Resume Parser</b>](https://github.com/akshatprogrammer/Resume-Analyser-Using-NLP)
3. [<b>BAAM Video Conferencing App</b>](https://github.com/akshatprogrammer/VideoConferencing)

# 6. Output

![6](https://github.com/akshatprogrammer/ML-Recruitment-System/assets/67745418/7964a633-942e-4dfe-9cc9-3251e9298b66)
![7](https://github.com/akshatprogrammer/ML-Recruitment-System/assets/67745418/d6942cbe-bc18-47eb-8d70-c10c9fd2a220)
![8](https://github.com/akshatprogrammer/ML-Recruitment-System/assets/67745418/35d8522b-bdd2-4b53-a51e-54e70ac0e941)
![9](https://github.com/akshatprogrammer/ML-Recruitment-System/assets/67745418/8d9393c0-c9d7-4bd6-91f8-9e25eadd332c)
![10](https://github.com/akshatprogrammer/ML-Recruitment-System/assets/67745418/7e609af8-be07-4fa3-885a-8c69b67e26af)

# 7. Research Paper Details
The details of our research publication are as follows: 


B. S. Shahi, A. Jain, M. Goyal and A. Gupta, “NLP-Enabled Interview-Taking System For Job Applicant Screening” 2023 1st International Conference on Computational Intelligence for Information, Security and Communication Applications (CIISCA), India, 2023 (Accepted)

# 8. References
1. Ghalwash, D., Elkhateb, A., Elragal, A.       (2020). A natural language processing-based system for evaluating job applicants' resumes. IEEE Access, 8, 154501-154510. doi 10.1109/ACCESS.2020.3015113 
2. Zhang, Y., Sun, S., Wang, Y., Song, X. (2021). A natural language processing-based candidate selection system. IEEE Access, 9, 37827-37839. doi 10.1109/ACCESS.2021.3066324
3. Kumar, R., & Chakraborty, S. (2016). A survey on automated resume parsing and standardization of resume data. Journal of Intelligent Information Systems, 46(1), 29-56. 
4. Singh, S., & Singh, S. (2019). An Overview of Resume Parsing Techniques. International Journal of Engineering and Advanced Technology (IJEAT), 9(1), 68-72. 
5. Peiretti, M. D., Navarro, L., & Gorgoglione, M. (2021). Covid-19 and remote work: An analysis of the videoconferencing software market. Information Systems Frontiers, 23(2), 375-386. 
6. Sun, Y., Xie, B., & Liang, Y. (2021). Design and implementation of a mobile video conferencing application based on WebRTC. Journal of Ambient Intelligence and Humanized Computing, 12(4), 3587-3598. 
7. Wang, Z., Sun, J., & Wang, Z. (2021). A collaborative code editor for teaching computer science. International Journal of Emerging Technologies in Learning (iJET), 16(5), 164-177. 
8. Lopes, P., & Cruz, D. (2018). Web-based code editors: a comparative study. In International Conference on Information Technology & Systems (pp. 137-148). Springer. 
9. Kim, M. J., Kim, D. J., & Kim, J. W. (2021). User-oriented design guidelines for employment websites: a content analysis of online job postings. Journal of Information Science Theory and Practice, 9(2), 28-45. 
10. Christoforou, A., & Leonidis, A. (2021). Exploring the Usability of Recruitment Websites from the Users' Perspective. In Proceedings of the 15th Mediterranean Conference on Information Systems (MCIS 2021) (pp. 1-11).

# About Team
[<b>Akshat Jain</b>](https://github.com/akshatprogrammer)
[<b>Bhupendra Singh Shahi</b>](https://github.com/BhupendraShahi)
