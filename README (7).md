
# Clarusway Blog - MERN Stack Deployment on AWS

This project demonstrates deploying a full MERN (MongoDB, Express, React, Node.js) stack blog application to AWS using EC2 and S3.

---

## Live Links

- **Frontend (S3 Website):** [lina-blogapp-frontend](http://lina-blogapp-frontend.s3-website.eu-north-1.amazonaws.com)
- **Media Image (S3):** [media image](https://lina-blogapp-media.s3.eu-north-1.amazonaws.com/OIP.jpg)
- **GitHub Repo:** [clarusway-blog-backend](https://github.com/Lina-fhahd/clarusway-blog-backend.git)

---

## Technologies Used

- Node.js
- Express.js
- MongoDB & MongoDB Atlas
- AWS EC2
- AWS S3 (Static Website Hosting & Media Storage)
- Git & GitHub

---

## Deployment Steps

1. Created the backend project using Express and connected it to MongoDB Atlas.
2. Deployed the backend to an EC2 instance on AWS.
3. Opened port 5000 on EC2 to allow external access.
4. Deployed the frontend static files to an S3 bucket.
5. Configured the S3 bucket for static website hosting.
6. Created a second S3 bucket for storing media (images).
7. Set proper bucket policies to allow public access to media files.
8. Connected MongoDB Atlas with IP access `0.0.0.0/0`.

---

## Screenshots

| Step || Description |
|------||-------------|
| 1️⃣ | ![Frontend] | Frontend S3 website working (`Hello from Clarusway Blog Frontend`) |
| 2️⃣ | ![EC2] | Server running on EC2 (`port 5000`) |
| 3️⃣ | ![MongoDB Connected] | MongoDB connection successful |
| 4️⃣ | ![MongoDB IP] | MongoDB Atlas IP Access List showing `0.0.0.0/0` |
| 5️⃣ | ![Media Image] | Public media image from S3 |
| 6️⃣ | ![Bucket Policy] | S3 media bucket policy showing public access enabled |
| 7️⃣ | ![Static Hosting] | S3 static website hosting configuration |

---

## Notes

- Be sure **NOT to commit AWS credentials** to GitHub.
- After submitting, **delete the IAM user** created for this assignment.

