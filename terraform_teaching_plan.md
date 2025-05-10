
# 7-Day Terraform Teaching Plan for Beginners

This structured routine is designed to introduce Terraform to beginners through daily lessons and hands-on practice.

---

## **Day 1: Introduction & Setup**
**Objective**: Understand what Terraform is and set up the environment.

### Topics:
- What is IaC (Infrastructure as Code)?
- Why Terraform? Benefits and use cases.
- Terraform architecture & workflow.
- Install Terraform & configure CLI.
- Set up a free-tier AWS/Azure/GCP account.

### Hands-on:
- Install Terraform.
- Configure a cloud provider (e.g., AWS with access keys).
- Run `terraform version`, `terraform --help`.

---

## **Day 2: First Terraform Project**
**Objective**: Build and apply a simple resource.

### Topics:
- HCL syntax overview.
- Terraform files (`main.tf`, `variables.tf`, `outputs.tf`).
- Provider and resource blocks.
- Commands: `terraform init`, `plan`, `apply`, `destroy`.

### Hands-on:
- Create an S3 bucket or basic EC2 instance.

---

## **Day 3: Variables, Outputs, Locals**
**Objective**: Introduce dynamic configuration.

### Topics:
- Variables: `default`, `type`, `description`.
- Output blocks and `terraform output`.
- Use of `locals` to simplify logic.

### Hands-on:
- Create reusable infrastructure with variables.
- Output values after deployment.

---

## **Day 4: State and Backend**
**Objective**: Understand Terraform state and remote storage.

### Topics:
- What is `terraform.tfstate`?
- State file importance and risks.
- Remote backend configuration (S3, Azure Blob, GCS).

### Hands-on:
- Store state in remote backend like S3.
- Enable state locking with DynamoDB (AWS).

---

## **Day 5: Modules**
**Objective**: Learn code reuse and modular design.

### Topics:
- What are modules?
- How to create and use local modules.
- Input/output variables in modules.

### Hands-on:
- Create a VPC module and reuse it in the main project.

---

## **Day 6: Advanced Features**
**Objective**: Work with loops, conditionals, and meta-arguments.

### Topics:
- Meta-arguments: `count`, `for_each`
- `depends_on`, `lifecycle`, `provisioner`
- `dynamic` blocks

### Hands-on:
- Create multiple EC2 instances using loops.
- Add lifecycle rules to protect resources.

---

## **Day 7: Best Practices + Project**
**Objective**: Wrap up with best practices and a mini project.

### Topics:
- State management tips.
- Sensitive data handling.
- Recommended file/folder structure.
- Common Terraform pitfalls.

### Hands-on:
- Build a mini project: a web server with networking and storage.

---

Happy Terraforming!
