# devops-ci-app

Учебное Flask-приложение для практической работы № 10.

CI: Pylint → pytest → Docker build → smoke-test → GHCR.

- Проверка состояния: `/health`.
- Образ: `ghcr.io/agugis/devops-ci-app`.
- Workflow: `.github/workflows/ci.yml`.

Pull Request проверяется без публикации. Образ публикуется при push в `main`.
