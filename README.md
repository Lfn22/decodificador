<div align="center">

# 🔐 Decodificador de Texto

**Criptografe e descriptografe mensagens secretas no navegador.**

[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/pt-BR/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/pt-BR/docs/Web/CSS)

</div>

---

## 📋 Sobre o projeto

Aplicação web que criptografa e decodifica mensagens usando substituição de vogais por sequências de caracteres. Permite trocar mensagens secretas com qualquer pessoa que conheça a chave de codificação.

Projeto desenvolvido como desafio da **[Alura](https://www.alura.com.br/)** — One Oracle Next Education (ONE).

---

## ✨ Funcionalidades

- 🔒 Criptografia de texto por substituição de vogais
- 🔓 Decodificação de mensagens criptografadas
- 📋 Botão de copiar resultado com um clique
- ⚠️ Validação de entrada (apenas letras minúsculas sem acento)
- 📱 Layout responsivo para desktop e mobile

---

## 🔑 Tabela de criptografia

| Letra original | Substituto |
|---|---|
| `e` | `enter` |
| `i` | `imes` |
| `a` | `ai` |
| `o` | `ober` |
| `u` | `ufat` |

**Exemplo:**
```
gato  →  gaitober
mensagem  →  menternsaigementer
```

---

## 🚀 Como rodar localmente

### Pré-requisitos
- Navegador moderno
- Nenhuma dependência ou instalação necessária

### Passos

```bash
# 1. Clone o repositório
git clone https://github.com/Lfn22/decodificador.git

# 2. Entre na pasta
cd decodificador

# 3. Abra no navegador
open decodf.html

# Ou arraste o arquivo decodf.html para o navegador
```

---

## 🗂️ Estrutura do projeto

```
decodificador/
├── decodf.html         # Estrutura da página
├── style.css           # Estilização e responsividade
└── decodificando.js    # Lógica de criptografia e decodificação
```

---

## 🛠️ Tecnologias

| Tecnologia | Uso |
|---|---|
| JavaScript (ES6+) | Lógica de substituição, manipulação do DOM |
| HTML5 | Estrutura semântica da interface |
| CSS3 | Estilização, layout responsivo |

---

## 📚 Conceitos praticados

- Manipulação de strings em JavaScript
- Funções puras e reutilizáveis
- Eventos do DOM (click, input)
- Validação de entrada do usuário
- Clipboard API para copiar texto

---

## 👨‍💻 Autor

**Lindomar Negreiros** — [@Lfn22](https://github.com/Lfn22)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/lindomar-lopes-de-negreiros-filho-4540b8220/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/Lfn22)

---

## 📄 Licença

Este projeto está sob a licença MIT.
