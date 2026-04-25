Resposta 1:
Isso acontece por causa do comportamento padrão de mascaramento de segredos em ferramentas de CI/CD (como GitHub Actions, GitLab CI/CD, etc.).

Resposta 2:
Não, o job deploy_app não consegue ler diretamente a variável BUILD_VERSION criada no job build_app.