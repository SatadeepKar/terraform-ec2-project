# 🚀 Terraform EC2 Project

## 📌 Objective

Learn Terraform basics (`init`, `plan`, `apply`) and create an AWS EC2 instance using Infrastructure as Code (IaC).

---

## 🛠 Tools Used

* Terraform
* AWS CLI
* AWS EC2

---

## 📁 Project Structure

```
terraform-ec2/
│── main.tf
│── README.md
│── .gitignore
```

---

## ⚙️ Steps Performed

### 1. Installed Terraform & AWS CLI

### 2. Configured AWS

```
aws configure
```

### 3. Created Terraform Configuration (`main.tf`)

Defined:

* AWS provider (ap-south-1)
* EC2 instance resource
* Output for public IP

---

### 4. Initialized Terraform

```
terraform init
```

---

### 5. Planned Infrastructure

```
terraform plan
```

---

### 6. Applied Configuration

```
terraform apply
```

---

## ☁️ Resources Created

* EC2 Instance (Amazon Linux AMI)
* Instance Type: `t3.micro` *(used instead of t2.micro due to AWS restrictions)*
* Tag:

```
Name = Terraform-Student-Instance
```

---

## 📤 Output

* Successfully received **Public IP address** of the EC2 instance

---

## 🧹 Cleanup

To avoid unnecessary charges:

```
terraform destroy
```

---

## 🧠 Key Learnings

* Infrastructure as Code (IaC)
* Terraform workflow: `init → plan → apply`
* AWS resource provisioning using code

---

## ⚠️ Notes

* `.terraform/` and `.tfstate` files are ignored using `.gitignore`
* Large files are not pushed to GitHub

---

## 👨‍💻 Author

Satadeep Kar
