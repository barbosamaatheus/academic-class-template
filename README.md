# Meu Projeto Hugo

Um site estático gerado com [Hugo](https://gohugo.io/), rápido, moderno e fácil de manter.

---

## 🚀 Começando

Siga os passos abaixo para rodar o projeto localmente:

### Pré-requisitos

- [Hugo](https://gohugo.io/getting-started/installing/) >= 0.111
- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/) (opcional, se for usar assets como Sass ou JS)

### Instalação

1. Clone o repositório:

```bash
git clone https://github.com/SEU_USUARIO/SEU_REPOSITORIO.git
cd SEU_REPOSITORIO
```

````

2. Instale dependências (se houver):

```bash
npm install
```

3. Rode o servidor local do Hugo:

```bash
hugo server
```

4. Abra no navegador:

```
http://localhost:1313
```

---

## 📁 Estrutura do projeto

```
├── archetypes/       # Modelos de conteúdo
├── content/          # Conteúdo do site (posts, páginas)
├── layouts/          # Templates HTML
├── static/           # Arquivos estáticos (imagens, CSS, JS)
├── config.toml       # Configuração do Hugo
```

---

## ⚙️ Configuração

As principais configurações estão no arquivo `config.toml`:

```toml
baseURL = "https://seuusuario.github.io/seuprojeto/"
languageCode = "pt-br"
title = "Meu Projeto Hugo"
theme = "nome-do-tema"
```

---

## 📦 Publicação

Para gerar os arquivos finais para produção:

```bash
hugo
```

O conteúdo será gerado na pasta `public/`. Você pode enviar para GitHub Pages ou outro servidor.

---

## ❤️ Contribuição

Sinta-se à vontade para abrir issues ou pull requests. Toda ajuda é bem-vinda!

---

## 📄 Licença

Este projeto está licenciado sob a [MIT License](LICENSE).
````
