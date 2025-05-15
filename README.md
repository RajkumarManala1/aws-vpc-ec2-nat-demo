# 🌐 AWS VPC Hands-On Project: Public & Private Subnets, EC2, NAT Gateway, and Bastion Host

This project is a **complete hands-on demonstration of building a secure and scalable VPC on AWS**, using the AWS Management Console (root user) to configure each resource manually. I created this to deepen my understanding of core AWS networking concepts and help others learn with a clear, step-by-step walkthrough.

🔗 **Watch the full tutorial on YouTube**  
▶️ [Click here to watch the video](https://youtu.be/pgxzw5_34go)

---

## 🚀 What I Built

In this project, I created and configured:

- ✅ A **custom VPC** with a CIDR block of `11.0.0.0/16`
- ✅ One **Public Subnet** (`11.0.1.0/24`) and one **Private Subnet** (`11.0.2.0/24`)
- ✅ An **Internet Gateway** for public access
- ✅ A **NAT Gateway** for secure outbound access from the private subnet
- ✅ Two **EC2 instances**:
  - Public EC2 with an Elastic IP (Bastion Host)
  - Private EC2 (accessed via the Bastion Host)
- ✅ **Custom Route Tables** for each subnet
- ✅ **Security Groups** to control traffic flow

---

## 🌟 Architecture Diagram

Below is the architecture diagram for this project:

![AWS VPC Architecture Diagram](https://github.com/RajkumarManala1/aws-vpc-ec2-nat-demo/blob/main/architecture-diagram.png)

## 📂 Project Structure

```bash
aws-vpc-hands-on-tutorial/
├── README.md
├── PPT/
│   └── AWS_VPC_Tutorial_Slides.pptx
├── architecture-diagram.png
└── video-link.txt
```

---

## 🤝 Let's Connect!

Feel free to **fork**, **share**, or **use** these materials in your own projects — that’s what they’re here for!

📫 **Stay in touch or reach out for collaboration:**

- 💼 [LinkedIn – Raj Kumar Manala](https://www.linkedin.com/in/raj-kumar-manala-ab1b78134/)
- 🧑‍💻 [GitHub – RajkumarManala1](https://github.com/RajkumarManala1)

Thanks for checking out the project!
