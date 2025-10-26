# API Tests for ReqRes
![CI](https://github.com/NikitaMelehin/postman-api-reqres-project/actions/workflows/api-tests.yml/badge.svg)

Automated API tests for https://reqres.in using **Postman** and **Newman**.

---

## 📌 Stack
- Postman
- Newman
- Node.js
- GitHub Actions (CI)
- HTML Extra Report

---

## 📌 Project Structure
```
├── collections/         # Postman collection
├── environments/        # Postman environment
├── reports/             # HTML test reports
├── .github/workflows/   # CI configuration
├── package.json         # npm scripts
└── README.md
```
## 📌 Commands
| Action | Command |
|---------|---------|
| Run tests | `npm test` |
| Run tests with HTML report | `npm run test:report` |

Reports will be saved to `./reports`.

## 📌 CI
Tests run automatically on each push via GitHub Actions.