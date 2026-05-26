# Aula - Projeto de Clima e Informações

Um projeto estático com informações de clima em tempo real usando Meteoblue e widgets Elfsight.

## Preparado para Netlify

Este projeto está pronto para ser deployado no Netlify. Siga os passos abaixo:

### Pré-requisitos
- Conta no [Netlify](https://app.netlify.com)
- Git instalado
- Repositório GitHub (ou GitLab/Bitbucket)

### Como fazer o deploy

1. **Crie um repositório Git** (se ainda não tiver):
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   ```

2. **Faça push para o GitHub**:
   - Crie um repositório em https://github.com/new
   - Adicione o remote: `git remote add origin https://github.com/seu-usuario/seu-repo.git`
   - Faça push: `git push -u origin main`

3. **Deploy no Netlify**:
   - Acesse https://app.netlify.com
   - Clique em "New site from Git"
   - Conecte sua conta GitHub/GitLab/Bitbucket
   - Selecione o repositório
   - Clique em "Deploy site"

### Tudo pronto!
- O arquivo `netlify.toml` configura automaticamente o build
- O `.gitignore` exclui arquivos desnecessários
- Seu site estará online em alguns segundos!

## Desenvolvimento local

Para rodar localmente:
```bash
npm install
npm start
```

Acesse http://localhost:8080
