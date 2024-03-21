# flutter_web_deploy

A repo for testing deploy flutter web app

- [flutter\_web\_deploy](#flutter_web_deploy)
  - [Deployment](#deployment)
  - [Deploy Flutter Web on `Node.js` Server](#deploy-flutter-web-on-nodejs-server)
  - [Shortcut](#shortcut)

---

## Deployment

- Test

| Deployment Solution   | Result   | Url                                                                                | Document                                                        | CICD |
| --------------------- | -------- | ---------------------------------------------------------------------------------- | --------------------------------------------------------------- | ---- |
| Azure Storage         | Not Work | [Azure](https://capstonewebhosting.z14.web.core.windows.net/)                      | [Azure Storage](./doc/azure_storage/azure_storage.md)           |      |
| AWS S3 Static Web     | Not Work | [AWS S3](http://humber-capstone-webhosting.s3-website.ca-central-1.amazonaws.com/) | [AWS S3](./doc/aws_s3/aws_s3.md)                                |      |
| **GitHub Page**       | Work     | [GitHub Page](https://simonangel-fong.github.io/chowpati/)                         | [GitHub](./doc/github_page/github_page.md)                      | No   |
| **AWS Amplify**       | Work     | [AWS Amplify](https://master.d4xxdvavu47mx.amplifyapp.com/)                        | [AWS Amplify](./doc/aws_amplify/aws_amplify.md)                 |      |
| **Azure App Service** | Work     | [Azure App Service](https://flutter-deploy-test.azurewebsites.net/)                | [Azure App Service](./doc/azure_appservice/azure_appservice.md) |      |

- Capstone

| Deployment            | Url                                             |
| --------------------- | ----------------------------------------------- |
| **AWS Amplify**       | https://dev-page.d3ad0k626g19q6.amplifyapp.com/ |
| **Azure App Service** | https://chowpati.azurewebsites.net/             |

---

## Deploy Flutter Web on `Node.js` Server

- [`Node.js` Server](./doc/nodejs/nodejs.md)

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
