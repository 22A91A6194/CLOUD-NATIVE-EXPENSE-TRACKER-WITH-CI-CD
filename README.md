**Project:** Cloud Native Expense Tracker with CI/CD.

It is a Web Application that helps users keep track of their daily expenses easily and efficiently.  (MERN)
•	**Front End:** React.jsFSD:
⚡ Frontend Tech Stack & Features:

S.No	Package / Library	Purpose
1.	    Vite		Fast build tool for frontend development
2. 	 Tailwind CSS		Utility-first CSS framework for fast UI development
3. 	    Axios		For making HTTP requests to the backend
4. 	Emoji Picker (React)	To enable emoji selection in forms (e.g., comments, expense tags)
5. 	   Moment.js		Date formatting and calendar-related operations
6. 	React Hot Toast		Display toast notifications (e.g., "Expense Added Successfully!")
7. 	   React Icons		Vector icons from various icon libraries
8. 	   Recharts		Charts & graphs for dashboards (expense insights, stats, etc.)


📁 Important API Paths (Frontend)

File Name	API Purpose
Login-API	To authenticate users
Register-API	To register new users
Get_User_Info	To fetch user profile details after login
Verify_OTP	To verify OTP sent to user email during login

📌 All these APIs are called using Axios from frontend




•	**Backend** built with Node.js and express.

🛠️ Backend Tech Stack (driver.js and Others)
S.No	Package			Purpose
1.	 cors			Handle Cross-Origin requests (frontend & backend on different ports)
2. 	 bcryptjs		Encrypt (hash) passwords before storing in database
3. 	 dotenv			Use environment variables (like DB URI, secret keys)
4. 	 jsonwebtoken		Generate & verify secure tokens for user authentication
5. 	 mongoose		ORM to interact with MongoDB
6.  	 nodemon		Auto-restarts server on file changes
7. 	 multer			Handle file uploads (e.g., profile pictures)
8. 	 nodemailer		Send emails (e.g., OTPs, confirmation mails)
9. 	 xlsx			Generate and download Excel sheets from your app


•	Need of **Database** (Used MongoDB).

**Motto of the project:**
The main goal of your project is to help users manage their money better by tracking expenses in real-time, providing a simple interface, and ensuring reliable, scalable deployment using modern cloud and DevOps technologies.

**Access Link:** https://stormledgers-nine.vercel.app/
