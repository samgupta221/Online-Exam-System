# 🚀 Online Exam System – Java (Spring Boot)

A comprehensive **Online Examination System** built using **Spring Boot, Spring Security, Thymeleaf, Bootstrap 5**, and **JPA/Hibernate**.  
The platform provides a secure and user-friendly environment for **Admins** and **Students** to manage and take online tests effectively.

✔️ Completely Free  
✔️ Full Source Code Included

---
# 📸 Screenshots


<table width="100%">


<tr>
<td align="center"><b>Exam Page (with Pagination)</b></td>
</tr>
<tr>
<td align="center"><img src="https://github.com/sumitkumar1503/online-exam-system/blob/master/screenshots/exampage.png" width="90%"></td>
</tr>

<tr>
<td align="center"><b>Admin Dashboard</b></td>
</tr>
<tr>
<td align="center"><img src="https://github.com/sumitkumar1503/online-exam-system/blob/master/screenshots/admindashboard.png?raw=true" width="90%"></td>
</tr>

<tr>
<td align="center"><b>Manage Exam</b></td>
</tr>
<tr>
<td align="center"><img src="https://github.com/sumitkumar1503/online-exam-system/blob/master/screenshots/adminmanageexam.png" width="90%"></td>
</tr>

<tr>
<td align="center"><b>Manage Question</b></td>
</tr>
<tr>
<td align="center"><img src="https://github.com/sumitkumar1503/online-exam-system/blob/master/screenshots/adminmanagequestion.png" width="90%"></td>
</tr>
</table>

---

# ✨ Features

## 👨‍💻 Admin Features
- Secure Admin Login
- Stats Dashboard (Total Students, Exams, Questions, Submissions)
- **Exam CRUD** (title, duration, description)
- **Question CRUD** per exam
- Cascade deletes for exams → questions → results
- Protect answered questions from accidental delete
- Manage Students
- Reset Student Password
- Delete Student Account (cascade all related data)
- View all submissions for any exam

---

## 🧑‍🎓 Student Features
- Student Registration (Full Name, Email, Mobile, Profile Picture)
- Secure Login
- Dashboard with KPIs + Performance Chart
- Take Exam (paginated interface + question palette)
- Live Timer (auto submit)
- Instant Results (score, percentage, pass/fail)
- Detailed Review Page (correct vs incorrect answers)
- Profile Update
- Upload New Profile Picture
- Change Password
- View All Previous Exam Results

---

# 🛠️ Tech Stack

| Layer | Technology                                 |
|------|--------------------------------------------|
| Backend | Spring Boot 3, Spring Security 6           |
| Frontend | Thymeleaf, Html, Bootstrap 5, Chart.js     |
| Database | H2 (file-based) (configurable to other DB) |
| ORM | Hibernate / JPA                            |
| Build | Maven                                      |
| Storage | Local File System for images               |

---
