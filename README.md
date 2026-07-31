<h1 align="center">Hi, I'm Anas Moustafa</h1>
<h3 align="center">Senior Flutter Engineer who ships his own infrastructure</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/anas-moustafa-b36b6a17a/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-blue?logo=linkedin&style=for-the-badge&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:Anas.khaled1892@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?logo=gmail&style=for-the-badge&logoColor=white" alt="Email" />
  </a>
  <a href="https://github.com/AnasKhaled1876">
    <img src="https://img.shields.io/badge/GitHub-100000?logo=github&style=for-the-badge&logoColor=white" alt="GitHub" />
  </a>
</p>

---

I build production Flutter apps and the AWS infrastructure underneath them.
Four published apps across Saudi Arabia, the UAE, and Egypt — two on both stores,
two open source. Clients written in Dart, deployments written in Terraform.

### Selected Work

**Streaming chat, done properly.** egypto's SSE decoder buffers partial frames
across chunk boundaries, tolerates malformed JSON without dropping the stream,
emits sealed event types, and enforces bounded frame and response limits so a runaway
server can't exhaust client memory — with tests covering each case.
→ [`chat_sse_decoder.dart`](https://github.com/AnasKhaled1876/egypto_ai/blob/main/lib/features/chat/data/services/chat_sse_decoder.dart)

**Deployment without long-lived keys.** Replaced SSH-and-deploy-key CI with
GitHub OIDC and AWS Systems Manager: port 22 closed, short-lived credentials,
runtime secrets pulled from Secrets Manager, health-gated releases.

---

## Featured Mobile Apps

### [Tamayozak](https://apps.apple.com/sa/app/tamayozak-%D8%AA%D9%85%D9%8A%D8%B2%D9%83/id6499983810)

Saudi marketplace for premium car plate numbers, published on iOS and Android.

- Flutter client with BLoC and secure card payments for purchases in KSA.
- Arabic-first UI with full RTL layout, deep linking, and push notifications.
- Key purchase journeys covered by unit, widget, and end-to-end tests.

<p>
  <a href="https://apps.apple.com/sa/app/tamayozak-%D8%AA%D9%85%D9%8A%D8%B2%D9%83/id6499983810">
    <img src="https://img.shields.io/badge/App_Store-0D96F6?style=for-the-badge&logo=appstore&logoColor=white" alt="Tamayozak on App Store" />
  </a>
  <a href="https://play.google.com/store/apps/details?id=com.madi.tamayozak">
    <img src="https://img.shields.io/badge/Google_Play-414141?style=for-the-badge&logo=googleplay&logoColor=white" alt="Tamayozak on Google Play" />
  </a>
</p>

### [Al Roqi](https://apps.apple.com/us/app/al-roqi/id1589667013)

Villa design and customization platform for Dubai's luxury real estate market.

- Flutter client for villa design and customization, plus a custom CRM workflow
  for the sales team.
- Modular architecture with responsive layouts across phone and tablet, Google Maps
  integration, and Firebase.
- Shipped to both the App Store and Google Play for a Dubai luxury real estate client.

<p>
  <a href="https://apps.apple.com/us/app/al-roqi/id1589667013">
    <img src="https://img.shields.io/badge/App_Store-0D96F6?style=for-the-badge&logo=appstore&logoColor=white" alt="Al Roqi on App Store" />
  </a>
  <a href="https://play.google.com/store/apps/details?id=com.AlRoqi.tariq_al_raqi">
    <img src="https://img.shields.io/badge/Google_Play-414141?style=for-the-badge&logo=googleplay&logoColor=white" alt="Al Roqi on Google Play" />
  </a>
</p>

### [egypto](https://play.google.com/store/apps/details?id=com.anas.egypto_ai)

AI assistant for Egyptians and tourists visiting Egypt, live on Google Play.

- Built the Flutter client with `Riverpod`, streaming SSE chat, voice input, media upload, and Arabic/English support.
- Runs on a Node.js/Express backend deployed to Vercel, with Redis-backed state and Supabase Postgres.
- Built a complete alternative EC2 deployment with Terraform, including VPC, IAM, Secrets Manager, and CloudWatch, as an operations exercise.

<p>
  <a href="https://play.google.com/store/apps/details?id=com.anas.egypto_ai">
    <img src="https://img.shields.io/badge/Google_Play-414141?style=for-the-badge&logo=googleplay&logoColor=white" alt="egypto on Google Play" />
  </a>
  <a href="https://github.com/AnasKhaled1876/egypto_ai">
    <img src="https://img.shields.io/badge/Source_Code-100000?style=for-the-badge&logo=github&logoColor=white" alt="egypto source code on GitHub" />
  </a>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/AnasKhaled1876/egypto_ai/main/assets/readme/home.jpg" width="31%" alt="egypto home screen" />
  <img src="https://raw.githubusercontent.com/AnasKhaled1876/egypto_ai/main/assets/readme/chat.jpg" width="31%" alt="egypto chat screen" />
  <img src="https://raw.githubusercontent.com/AnasKhaled1876/egypto_ai/main/assets/readme/voice.jpg" width="31%" alt="egypto voice screen" />
</p>

### [Typer](https://play.google.com/store/apps/details?id=com.anas.typer)

Arcade typing game built with Flutter and Flame — type falling words, chain
combos, climb category levels. English and Egyptian Arabic from one codebase.

- Game loop decouples the 60 fps Flame simulation from Flutter rebuilds via a
  throttled snapshot — UI redraws at ~120 ms cadence, not per frame.
- Typing speed is benchmarked against a published academic dataset
  (37k-participant mobile typing study), not an invented rank.
- Zero analyzer diagnostics, 193 tests, CI-gated. Ads, IAP, and Play Games
  leaderboards integrated.

<p>
  <a href="https://play.google.com/store/apps/details?id=com.anas.typer">
    <img src="https://img.shields.io/badge/Google_Play-Download-414141?style=for-the-badge&logo=googleplay&logoColor=white" alt="Typer on Google Play" />
  </a>
  <a href="https://github.com/AnasKhaled1876/typer">
    <img src="https://img.shields.io/badge/Source_Code-100000?style=for-the-badge&logo=github&logoColor=white" alt="Typer source code on GitHub" />
  </a>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/AnasKhaled1876/typer/main/assets/readme/hub.webp" width="31%" alt="Typer arcade hub" />
  <img src="https://raw.githubusercontent.com/AnasKhaled1876/typer/main/assets/readme/gameplay.webp" width="31%" alt="Typer gameplay — typing falling words" />
  <img src="https://raw.githubusercontent.com/AnasKhaled1876/typer/main/assets/readme/shop.webp" width="31%" alt="Typer powerup shop" />
</p>

---

## Cloud & DevOps Projects

### [Highly Available Web Application on AWS](https://github.com/AnasKhaled1876/cloudnotes-aws-high-availability)

- Designed a highly available AWS environment across two Availability Zones.
- Used VPC, public/private subnets, EC2, ALB, Auto Scaling Group, S3, IAM, CloudWatch, Route 53, and RDS.
- Validated routing, scaling, DNS, monitoring, and failure behavior through deployment testing.

### [Terraform AWS Infrastructure](https://github.com/AnasKhaled1876/aws-terraform-infrastructure)

- Recreated production-style AWS infrastructure with reusable Terraform modules.
- Used variables, outputs, remote state in S3, and separate dev/prod environments.
- Reduced configuration drift by keeping infrastructure version-controlled and repeatable.

### [ECS Fargate Containerized API](https://github.com/AnasKhaled1876/ecs-fargate-containerized-api)

- Containerized a REST API with Docker and pushed versioned images to Amazon ECR.
- Deployed to Amazon ECS on AWS Fargate through GitHub Actions.
- Added CloudWatch runtime logging and Linux Bash scripts for backup, health checks, and log cleanup.

---

## Tech Stack

**Mobile:** Flutter, Dart, Riverpod, BLoC, Firebase, Swift, Java

**Infrastructure:** AWS, Terraform, Docker, GitHub Actions, Node.js, PostgreSQL, Redis

### Tools & Practices

`Clean Architecture` `SOLID` `REST APIs` `Payment Gateways` `Push Notifications` `Deep Linking` `Localization` `Unit / Widget / Integration Testing` `Fastlane` `Figma`

---

## Experience Highlights

- Led end-to-end Flutter development from requirements analysis to App Store and Google Play releases.
- Built release workflows using GitHub Actions and Fastlane to reduce manual deployment work.
- Integrated Firebase services, REST APIs, payments, push notifications, maps, localization, and deep linking across production apps.
- Worked with AWS services in production, including Route 53, S3, CloudFront, EC2, IAM, Secrets Manager, and CloudWatch.
- Built personal cloud portfolio projects covering high availability, Terraform IaC, ECS/Fargate, ECR, Docker, Linux automation, and observability.

---

## Education & Certifications

- B.Sc. in Computer Science - Ain Shams University.
- AWS Certified Solutions Architect - Associate (SAA-C03), in progress.
- IBM & Microsoft cloud certifications - CI/CD, containers, and Azure infrastructure.
- Agile Fundamentals: Scrum & Kanban.

---
