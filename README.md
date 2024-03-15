# flutter_web_deploy

A repo for testing deploy flutter web app

- [flutter\_web\_deploy](#flutter_web_deploy)
  - [Deployment](#deployment)
  - [Shortcut](#shortcut)

---

## Deployment

| Deployment Solution | Result    | Url                                                                                | Document                                              | CICD |
| ------------------- | --------- | ---------------------------------------------------------------------------------- | ----------------------------------------------------- | ---- |
| **GitHub Page**     | Work      | [GitHub Page](https://simonangel-fong.github.io/chowpati/)                         | [GitHub](./doc/github_page/github_page.md)            | No   |
| Azure Storage       | Not Work  | [Azure](https://capstonewebhosting.z14.web.core.windows.net/)                      | [Azure Storage](./doc/azure_storage/azure_storage.md) |      |
| AWS S3 Static Web   | Not Work  | [AWS S3](http://humber-capstone-webhosting.s3-website.ca-central-1.amazonaws.com/) | [AWS S3](./doc/aws_s3/aws_s3.md)                      |      |
| **AWS Amplify**     | Work      | [AWS Amplify](https://dev-page.dbunn4jlo11r2.amplifyapp.com/)                      | [AWS S3](./doc/aws_amplify/aws_amplify.md)            | ??  |
| _Azure App Service_ | _Ongoing_ |                                                                                    |                                                       |      |

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
