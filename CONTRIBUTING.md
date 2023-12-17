<h1>
	<img src="https://i.ibb.co/QfkB43X/LOGO-DZS-BLACK-TRANSPARENT-PNG.png" width="55px" align="center" />
	<span>Contribuição, Segue Orientações 📎</span>
</h1>

[![Star](https://img.shields.io/github/stars/draggner/s-pdg-html5?style=social)](https://github.com/draggner/s-pdg-html5/stargazers)
[![Forks](https://img.shields.io/github/forks/draggner/s-pdg-html5?style=social)](https://github.com/draggner/s-pdg-html5/forks)
[![GitHub Issues](https://img.shields.io/github/issues/draggner/s-pdg-html5?style=social)](https://github.com/draggner/s-pdg-html5/issues/)


A finalidade do repositório é desenvolver e compartilhar conhecimento, é um projeto voltado para toda comunidade de desenvolvimento web. Sinta-se livre para contribuir.

- 📌 Inserir sugestão de melhorias
- 📌 Resolver **Issues**, responder

A ideia é desenvolver um repositório base, como uma documentação a ser consultada para aplicar os conceitos na prática. A parti do momento em que o repositório se finalize, o próprio desenvolvedor pode dar continuidade, conforme o desenvolvedor adquira experiências em determinada tecnologia, conforme o tempo passe.

Para contribuir com o repositório, siga os seguintes procedimentos:
### Instruções 📃

1. Faça um **Fork** do repositório.

2. Use o comando `git clone https://github.com/SEU_USERNAME/s-pdg-html5.git`

3. Adicione o comando `git remote add upstream https://github.com/draggner/s-pdg-html5.git` para manter o repositório atualizado, usando o comando:

>   `git pull upstream main` que serve para baixar e mesclar as alterações do repositório local com base na branch `main` do repositório do repositório original pelo qual realizou o fork.

>   Caso não queira mesclar as alterações, pode usar o comando `git fetch upstream main` para baixar sem mesclar.

4. Crie uma nova **branch** com o comando `git checkout -b` no seguinte padrão: `feat/SEU_USERNAME`
  
>   Ex: `git checkout -b feat/draggner`

5. A parti daqui, os procedimentos são quando realizou a devida alterações que deseja contribuir.

>    **Observe** que qualquer melhoria, deve está igual ao repositório original. Caso esteja desatualizado, prossiga com os comandos anteriores para manter atualizado.

6. Adicione as alterações para **staging area** com o comando `git add ARQUIVO`.

>   **Observação:** Você pode utilizar o comando `git add .` para adicionar todas as alterações de uma vez só. 
>   Ou pode usar o comando `git add PRIMEIRO_ARQUIVO SEGUNDO_ARQUIVO` para adicionar as alterações com base nos arquivos que queira commitar.

7. Após os procedimentos acima, use o comando `git commit -m` e siga o procedimento de Padrão de Commit, na tabela após as instruções.

8. Envie as alterações para o seu repositório remoto com o comando `git push origin feat/SEU_USERNAME`;.

9. Crie um **Pull Request**.

### Padrão de Commit 📦

| Tipo de Commit | Descrição | Exemplo de Commit |
| -------------- | --------- | ----------------- |
| `feat` | Adicionar uma nova funcionalidade ao projeto. | `feat: CONTEXTO_A_SER_TRATADO` |
| `fix` | Corrige um bug ou problema no projeto. | `fix: CONTEXTO_A_SER_TRATADO` |
| `docs` | Altera a documentação do projeto. Ex: README.md, comentários no código. | `docs: CONTEXTO_A_SER_TRATADO` |
| `style` | Realiza mudanças na aparência, sem alterar na funcionalidade. | `style: CONTEXTO_A_SER_TRATADO` |
| `refactor` | Realiza mudanças no código que não alteram a funcionalidade.| `refactor: CONTEXTO_A_SER_TRATADO` |
| `test` | Adiciona ou modifica testes no projeto. | `test: CONTEXTO_A_SER_TRATADO` |
