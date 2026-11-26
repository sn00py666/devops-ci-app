# devops-ci-app

Учебное Flask-приложение для практической работы № 10.

Pylint → pytest → Docker build → smoke-test → GHCR.

Pull Request запускает проверки. Успешный push в `main` публикует образ с тегами полного SHA и `latest`.

- Проверка состояния: `/health`.
- Образ: `ghcr.io/sn00py666/devops-ci-app`.
- Workflow: `.github/workflows/ci.yml`.
