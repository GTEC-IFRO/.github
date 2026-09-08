# Diretrizes de Contribuição

Para garantir a qualidade e a rastreabilidade do código nos projetos da organização, siga as instruções abaixo.

---

## 1. Fluxo de Branches
* A branch `main` é reservada para versões estáveis/produção. **Não faça commits diretos na `main`**.
* Crie branches no formato:
  * `feat/nome-do-recurso`
  * `fix/nome-do-bug`
  * `chore/tarefas-de-manutencao`
  * `infra/ajustes-de-deploy-ou-container`

## 2. Padrão de Mensagens de Commit
Recomendamos o uso de [Conventional Commits](https://www.conventionalcommits.org/):
* `feat: adiciona endpoint de sincronizacao de dados`
* `fix: corrige validacao de campos vazios no payload`
* `docs: atualiza instrucoes de instalacao no README`
* `refactor: reorganiza estrutura de rotas`

## 3. Pull Requests e Code Review
1. Sempre abra o PR a partir da sua branch de trabalho contra a `main`.
2. Preencha todos os campos do template padrão de PR.
3. Obtenha ao menos 1 aprovação (*review*) de outro membro da equipe.
4. Garanta que todas as verificações automáticas de CI passem antes do merge.
