# 📱 Tutorial .NET MAUI — Cria Apps Multiplataforma com VS Code

Este repositório acompanha os tutoriais criados por **Luís Simões da Cunha**, que te ensinam a construir **aplicações modernas, bonitas e multiplataforma** com **.NET MAUI**, usando apenas o **Visual Studio Code**.

> 🔥 Começa do zero e evolui até apps empresariais com autenticação, base de dados, estilos avançados, publicação automatizada e MVVM!

---

## 🧭 Para quem é este tutorial?

- Iniciantes curiosos que querem criar apps reais em Android, iOS, Windows e macOS 🧑‍💻  
- Professores e formadores que procuram recursos didáticos claros e progressivos 🎓  
- Desenvolvedores experientes que querem dominar MAUI com boas práticas, MVVM e GitHub Actions 🧠

---

## 📚 Estrutura do Tutorial

Este repositório acompanha **dois tutoriais complementares**:

### 🌴 1. Tutorial MAUI — Versão Alargada

> Um guia completo, prático e visual, focado no desenvolvimento com **VS Code** e **.NET CLI**.

📖 Partes principais:
- Criação da tua primeira app MAUI (“Aloha, World!”)
- Interação com SQLite e Preferences
- Partilha de localização e listas seguras (com encriptação)
- Criação de interfaces modernas com CollectionView, SwipeView, etc.
- Layouts responsivos e visuais com estilo
- Navegação com Shell, ciclo de vida das páginas
- Apps empresariais com autenticação, DI e arquitetura Clean
- MVVM aplicado passo a passo
- Temas, estilos e personalização por plataforma
- Controles personalizados e publicação automatizada com GitHub Actions


---

### 🧩 2. Tutorial MAUI v02 — Aplicações Empresariais

> Abordagem mais técnica e estruturada, com foco em **boas práticas arquiteturais**.

📖 Destaques:
- MVVM com CommunityToolkit
- Injeção de Dependência com MauiProgram.cs
- Comunicação entre componentes com Messenger
- Navegação desacoplada com serviços e parâmetros
- Validação de formulários e passagem de dados
- Acesso a APIs REST e autenticação
- Integração de serviços e modularização

---

## 🛠️ Pré-requisitos

- SDK do [.NET MAUI](https://learn.microsoft.com/pt-pt/dotnet/maui/get-started/installation)
- [Visual Studio Code](https://code.visualstudio.com/)
- Plataforma com suporte a MAUI (Windows/macOS com requisitos específicos)
- Terminal com .NET CLI

---

## 📦 Organização do Repositório

```bash
📁 src/
   ├── AlohaWorld/           # App introdutória
   ├── MauiTodo/             # Lista de tarefas com SQLite
   ├── FindMe/               # Partilha de localização
   ├── MauiMovies/           # App interativa com layout avançado
   ├── MauiStockTake/        # App com MVVM avançado
   └── AuthApp/              # Login com DI + Messenger
📁 docs/
   ├── Tutorial MAUI - Versão Alargada.pdf
   └── Tutorial MAUI v02.pdf
📁 .github/
   └── workflows/            # GitHub Actions para build e deploy
```

---

## 📚 Licença

Este projeto está licenciado com a [Creative Commons BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/).  
Podes usar e adaptar livremente para fins não comerciais, com atribuição ao autor.

---

## 🙌 Agradecimentos

Tutorial criado por **Luís Simões da Cunha**, 2025.  
Inspirado em princípios de **psicologia cognitiva**, **design instrucional eficaz** e **boas práticas de engenharia de software**.

> “Aprender a criar apps nunca foi tão claro, tão prático e tão motivador!” ✨

---

## 🚀 Começa já!

📥 Clona o repositório:
```bash
git clone https://github.com/luiscunhacsc/GitHub-MAUI
cd GitHub-MAUI
```

▶️ Corre o teu primeiro projeto:
```bash
cd src/AlohaWorld
dotnet build -t:Run -f:net6.0-android
```

E começa a criar apps incríveis com .NET MAUI! 💡
