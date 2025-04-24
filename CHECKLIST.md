# Advanced Software Engineer Roadmap Checklist

Use this checklist to track your progress through the 12-month roadmap. Fork this repository to maintain your own state.

---

### Month 1: Software Architecture & Design Patterns

- [ ] Study: SOLID Principles
- [ ] Study: Common OOP Design Patterns (Factory, Singleton, Observer, etc.)
- [ ] Study: Clean Code Practices
- [ ] Resource: Complete relevant sections of Coursera Specialization / Head First Design Patterns / Refactoring.Guru
- [ ] Project: Refactor or build a small app using patterns/layers
- [ ] Deliverable: Document before/after comparison and improvements

### Month 2: System Design Fundamentals

- [ ] Study: Scalable Web Architecture Concepts (Vertical/Horizontal Scaling, Load Balancing, Caching)
- [ ] Study: Monolithic vs. Microservices Trade-offs
- [ ] Study: System Design Process (Requirements, Components, Diagrams)
- [ ] Resource: Complete relevant sections of System Design Primer / Grokking Course
- [ ] Project (Design): Design URL Shortener (Document: Req, Components, Scaling Plan)
- [ ] Project (Prototype): Implement basic URL Shortener
- [ ] Stretch: Implement basic Load Balancer locally
- [ ] Deliverable: System design document and prototype code

### Month 3: Performance Optimization & Caching

- [ ] Study: Code Profiling & Benchmarking Techniques
- [ ] Study: Basic Algorithmic Complexity (Big O) Awareness
- [ ] Study: Caching Strategies (Server-side, Client-side, Invalidation, TTL)
- [ ] Study: Database Query Optimization (Indexing, EXPLAIN)
- [ ] Study: Asynchronous Processing Concepts
- [ ] Resource: Review Redis caching articles/guides
- [ ] Tool: Use a benchmarking tool (JMeter, wrk)
- [ ] Project: Benchmark baseline app performance
- [ ] Project: Implement Caching (e.g., Redis) in app
- [ ] Project: Optimize identified bottlenecks (code/DB queries)
- [ ] Deliverable: Report with before/after performance metrics

### Month 4: Database Design & Data Management

- [ ] Study: SQL vs. NoSQL Differences & Use Cases
- [ ] Study: Data Modeling (Relational Normalization, NoSQL Document Design - Embedding vs Referencing)
- [ ] Study: Indexing Strategies
- [ ] Study: Transactions (ACID vs. BASE/CAP Theorem)
- [ ] Resource: Complete relevant Database Course / MongoDB University modules
- [ ] Resource: Read early chapters of *Designing Data-Intensive Applications*
- [ ] Project: Design schema for a feature in both SQL and NoSQL
- [ ] Project: Implement the feature using both database types
- [ ] Deliverable: Code for both implementations and comparison document

### Month 5: Distributed Systems Concepts

- [ ] Study: CAP Theorem & Consistency Models (Strong vs. Eventual)
- [ ] Study: Consensus Algorithms Basics (Raft/Paxos idea)
- [ ] Study: Replication & Sharding Concepts
- [ ] Study: Fault Tolerance Techniques (Heartbeats, Quorums)
- [ ] Resource: Complete relevant sections of Coursera Cloud Concepts / MIT 6.824 Lectures (or DDIA chapters)
- [ ] Project: Choose & attempt one:
    - [ ] Build simple distributed Key-Value Store (focus on replication/failure)
    - [ ] Complete one MIT 6.824 Lab (Raft/MapReduce)
    - [ ] Build simple Message Queue simulation
    - [ ] Contribute to a small distributed systems OS project
- [ ] Deliverable: Project code and README explaining concepts/challenges

### Month 6: Microservices & Cloud-Native Architecture

- [ ] Study: Microservice Principles & Trade-offs
- [ ] Study: Service Decomposition Strategies
- [ ] Study: API Design (REST/gRPC/GraphQL basics) & Communication Patterns (Sync/Async)
- [ ] Study: Key Microservice Patterns (API Gateway, Service Discovery, Circuit Breaker, Saga)
- [ ] Study: 12-Factor App Principles
- [ ] Resource: Read relevant chapters of *Building Microservices* / *Microservices Patterns* / Microservices.io
- [ ] Project: Design multi-service application (e.g., E-commerce)
- [ ] Project: Implement 2-3 core microservices with independent DBs
- [ ] Project: Containerize services using Docker (write Dockerfiles)
- [ ] Project: Implement basic API Gateway
- [ ] Optional: Implement Circuit Breaker pattern
- [ ] Deliverable: Code, Dockerfiles, Architecture Diagram, README explaining design

### Month 7: Cloud Infrastructure & DevOps Basics

- [ ] Study: Core Cloud Provider Services (AWS: EC2, VPC, S3, RDS, ELB)
- [ ] Study: Infrastructure as Code (IaC) Principles
- [ ] Tool: Learn basic Terraform (or CloudFormation) syntax
- [ ] Study: Basic CI/CD Concepts & Configuration Management
- [ ] Resource: Complete AWS Free Tier tutorials / SAA course basics
- [ ] Resource: Complete Terraform basic tutorials
- [ ] Project: Write Terraform script for basic cloud infrastructure (VPC, Instances/ECS Cluster, DB, LB)
- [ ] Project: Deploy containerized microservice(s) to the cloud using IaC
- [ ] Project: Configure managed database (RDS) and connect service
- [ ] Deliverable: Terraform code, deployment scripts, Cloud Architecture Diagram

### Month 8: Containers & Orchestration

- [ ] Study: Docker Deep Dive (Dockerfile best practices, layering)
- [ ] Tool: Learn Docker Compose for local development
- [ ] Study: Kubernetes Core Concepts (Pod, Service, Deployment, ConfigMap, Secret, Ingress)
- [ ] Tool: Use local K8s (Minikube/kind)
- [ ] Resource: Complete Docker & Kubernetes course (e.g., Grider) / K8s docs tutorial
- [ ] Project: Write efficient Dockerfiles for all services
- [ ] Project: Create Docker Compose file for local stack
- [ ] Project: Write Kubernetes manifests (Deployments, Services, etc.)
- [ ] Project: Deploy application to local K8s cluster
- [ ] Project: Test K8s scaling (increase replicas)
- [ ] Project: Test K8s self-healing (kill pod)
- [ ] Optional: Learn Helm basics and create a Helm chart
- [ ] Deliverable: Optimized Dockerfiles, Compose file, K8s manifests, Helm chart (optional), README

### Month 9: CI/CD & Automation

- [ ] Study: CI Principles (Automated Build, Test)
- [ ] Study: CD Principles (Automated Deployment to Staging/Prod)
- [ ] Tool: Learn CI/CD tool (GitHub Actions / Jenkins / GitLab CI) - Pipeline syntax
- [ ] Study: Integrating IaC (Terraform) into pipelines
- [ ] Study: Basic Security Scanning in CI (e.g., dependency check)
- [ ] Resource: Review CI/CD tool documentation & examples (e.g., GitHub Actions for Docker/K8s)
- [ ] Resource: Read relevant sections of *Continuous Delivery* book
- [ ] Project: Set up CI pipeline (build, test, lint) for project repo
- [ ] Project: Build & Push Docker images to registry from CI
- [ ] Project: Set up CD pipeline stage to deploy to K8s (staging env)
- [ ] Optional: Integrate Terraform apply in pipeline
- [ ] Optional: Add automated post-deployment health check
- [ ] Deliverable: Pipeline configuration files (e.g., YAML), updated README

### Month 10: Observability & Resilience

- [ ] Study: Monitoring Concepts (Four Golden Signals)
- [ ] Tool: Learn Metrics Collection (Prometheus) & Visualization (Grafana)
- [ ] Study: Structured Logging best practices
- [ ] Tool: Learn Centralized Logging (ELK basics or CloudWatch Logs)
- [ ] Study: Distributed Tracing Concepts (Jaeger/Zipkin awareness)
- [ ] Study: Alerting Principles & Tools (Alertmanager / CloudWatch Alarms)
- [ ] Study: Resilience Patterns (Circuit Breaker, Retry, Fallback)
- [ ] Study: Chaos Engineering Principles
- [ ] Study: SRE Concepts (SLOs, Error Budgets)
- [ ] Resource: Review Prometheus/Grafana/ELK setup guides
- [ ] Resource: Read relevant Google SRE book chapters
- [ ] Project: Instrument services with metrics endpoint (/metrics)
- [ ] Project: Set up Prometheus & Grafana, create dashboard
- [ ] Project: Implement structured logging & centralize logs
- [ ] Project: Configure at least one meaningful alert
- [ ] Project: Perform resilience tests (kill instance, simulate dependency failure) & verify behavior (failover, circuit breaker)
- [ ] Deliverable: Monitoring dashboard screenshots, alert config, logging setup notes, resilience test results

### Month 11: Security Best Practices

- [ ] Study: OWASP Top 10 Vulnerabilities & Mitigations
- [ ] Study: Authentication vs. Authorization
- [ ] Study: Secure Auth Mechanisms (JWT, OAuth 2.0 flow basics)
- [ ] Study: Encryption (At Rest, In Transit - HTTPS/TLS)
- [ ] Study: Cloud Security Basics (Security Groups, IAM Least Privilege)
- [ ] Study: Secure Coding Practices (Input Validation, Dependency Management)
- [ ] Tool: Use Dependency Scanning tool (`npm audit`, etc.)
- [ ] Tool: Use Web Vulnerability Scanner (OWASP ZAP / Burp Suite basic scan)
- [ ] Resource: Review OWASP Top 10 documentation
- [ ] Resource: Review Cloud Provider security best practices (e.g., AWS Well-Architected)
- [ ] Project: Perform security audit of application using OWASP Top 10 checklist
- [ ] Project: Implement robust authentication/authorization
- [ ] Project: Ensure HTTPS is used everywhere
- [ ] Project: Securely manage secrets (no hardcoding, use Vault/Secrets Manager/Env Vars)
- [ ] Project: Fix vulnerabilities found by dependency scans / ZAP scan
- [ ] Project: Review and harden cloud infrastructure security settings (firewalls, IAM)
- [ ] Optional: Perform basic Threat Modeling exercise
- [ ] Deliverable: Security audit checklist/report, documentation of implemented security measures

### Month 12: Capstone Project & Portfolio

- [ ] Project: Choose Capstone approach:
    - [ ] Option A: Design & Prototype complex new system (e.g., Uber-like)
    - [ ] Option B: Build full-stack SaaS application end-to-end
    - [ ] Option C: Make significant Open Source Contribution
    - [ ] Option D: Heavily polish and extend existing project (add features, scale testing)
- [ ] Documentation: Write detailed Case Study / README for capstone project (Architecture, Tech, Challenges, Results)
- [ ] Portfolio: Organize GitHub profile, ensure project READMEs are excellent
- [ ] Portfolio: Create/Update personal website or portfolio page (optional)
- [ ] Portfolio: Update LinkedIn profile with new skills and projects
- [ ] Community: Write blog post about project/learnings (optional)
- [ ] Community: Present project/learnings (optional)
- [ ] Reflection: Review progress over the year, identify strengths and areas for continued learning

---
