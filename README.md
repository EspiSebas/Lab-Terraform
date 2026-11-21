# Terraform + AWS S3 + GitHub Actions

![Terraform](https://img.shields.io/badge/Terraform-IaC-7B42BC?logo=terraform)
![AWS](https://img.shields.io/badge/AWS-S3-FF9900?logo=amazonaws)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-CI%2FCD-2088FF?logo=githubactions)

## 📌 About the Project

This project demonstrates how to provision AWS infrastructure using **Terraform** and automate static website deployment with **GitHub Actions**.

The pipeline automatically creates and configures an Amazon S3 bucket and deploys website files whenever changes are pushed to the repository.

## 🛠️ Technologies

- **Terraform:** Infrastructure as Code (IaC).
- **AWS S3:** Static website hosting.
- **GitHub Actions:** CI/CD automation.
- **AWS IAM:** Access and permissions management.

## ⚙️ How It Works

1. Push changes to the `main` branch.
2. GitHub Actions triggers the workflow.
3. AWS credentials are configured using GitHub Secrets.
4. Terraform provisions the S3 infrastructure.
5. Website files are deployed to the S3 bucket.

## 🔐 Configuration

Add the following secrets to your GitHub repository:

- `AWS_ACCESS_KEY_ID`
- `AWS_SECRET_ACCESS_KEY`

## 🚀 Run Locally

```bash
git clone https://github.com/EspiSebas/Lab-Terraform.git

cd Lab-Terraform/infra

terraform init
terraform plan
terraform apply
```

## 📚 What I Learned

- Infrastructure as Code with Terraform.
- AWS S3 static website hosting.
- CI/CD pipelines with GitHub Actions.
- AWS IAM permissions and credentials.
- Automated cloud infrastructure deployment.

## 👨‍💻 Author

**Sebastian Espinosa**

- [GitHub](https://github.com/EspiSebas)
- [LinkedIn](https://linkedin.com/in/sebastian-espinosa-dev/)
