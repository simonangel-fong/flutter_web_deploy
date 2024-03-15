# flutter_web_deploy

A repo for testing deploy flutter web app

- [flutter\_web\_deploy](#flutter_web_deploy)
  - [Deployment](#deployment)
  - [Shortcut](#shortcut)

---

## Deployment

- Deployment Options

  - **GitHub Page**
  - AWS S3
  - Google Web hosting
  - ...

- [x] [`GitHub`](./doc/github_page/github_page.md)
- [x] [`AWS S3`](./doc/aws_s3/aws_s3.md)
- [ ] [`AWS Amplify`](./doc/aws_amplify/aws_amplify.md)

---

## Shortcut

```sh
flutter clean

flutter build web 

# flutter build web --base-href /flutter_web_deploy/
# flutter build web --base-href /capstone_blank_design/ --web-renderer html
# flutter build web --base-href /capstone_blank_design/ --web-renderer canvaskit

```

---

[TOP](#flutter_web_deploy)
