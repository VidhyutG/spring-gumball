# CMPE 172 - Lab #10 Notes

# Steps done to create Spring Gumball CI/CD to GKE

Gradle Dependencies:
1) Spring Web
2) Thymeleaf
3) Spring Boot DevTools
4) Validation
5) Lombok
6) Testcontainers

Paths Configuration:
1) Group: com.example
2) Artifact: spring-gumball:2.2
3) Name: spring-gumball:2.2
4) Package Name: come.example.spring-gumball:2.2
5) Packaging: Jar

# Continuous Integration (CI) Workflow

### 1. CI Workflow Image

![image](https://github.com/VidhyutG/spring-gumball/assets/89988331/20df73a6-e64d-41ab-bc00-3853a361766c)

# Continuous Development (CD) Workflow

### 2. IAM Roles Linking to service account for my GKE Cluster

![image](https://github.com/VidhyutG/spring-gumball/assets/89988331/9160946b-d93c-45ca-8591-c953324af286)

### 3. Action Secrets Created from GitHub

![image](https://github.com/VidhyutG/spring-gumball/assets/89988331/e231150f-7036-4474-aad3-9c5e9c378b6d)

### 4. CD has been deployed successfully 

<img width="2527" alt="image" src="https://github.com/VidhyutG/spring-gumball/assets/89988331/7aaf6998-06db-4822-aaf7-2078c1a9a078">

### 5. Service Ingress is configured

![image](https://github.com/VidhyutG/spring-gumball/assets/89988331/8524cf6b-e7e4-4bdb-9287-5584abc8f00e)

### 6. Spring Gumball Running on Load Balancer

![image](https://github.com/VidhyutG/spring-gumball/assets/89988331/4777e3c9-d7dc-4cec-ba3a-ac6c395d28fe)
