# 🧩 Sistema de Cadastro e Dashboard de Usuários

Este projeto implementa um fluxo simples de **cadastro** e **autenticação de usuários**, com um **painel (dashboard)** de boas-vindas após o login.  
É um protótipo front-end que pode ser integrado futuramente a uma API backend.

---

## 📁 Estrutura do Projeto

/
|-- cadastro.html     # Página de cadastro de novos usuários
|-- dashboard.html    # Dashboard com menu e mensagem de boas-vindas
|-- login.html        # (Opcional) Página de login do usuário
└-- README.md         # Documentação do projeto

---

## 🚀 Funcionalidades

### 🧍 Cadastro de Usuário (`cadastro.html`)
- Formulário com campos: **Nome**, **E-mail**, **Senha** e **Confirmação de Senha**.  
- Validação básica (senhas iguais e campos obrigatórios).  
- Simulação de cadastro armazenando dados no `localStorage`.  
- Redirecionamento automático para o dashboard após o cadastro.

### 📊 Dashboard do Usuário (`dashboard.html`)
- Menu lateral simples com opções (Início, Relatórios, Configurações, Sair).  
- Mensagem de boas-vindas personalizada usando o nome do usuário autenticado.  
- Layout responsivo e limpo em HTML + CSS puro.

---

## ⚙️ Tecnologias Utilizadas

- **HTML5**
- **CSS3**
- **JavaScript (ES6+)**
- **LocalStorage** (simulação de persistência de dados)

---

## 🧠 Como Usar

1. **Clonar o repositório**
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   cd seu-repositorio
   ```

2. **Abrir o arquivo cadastro.html no navegador**
   → Preencha o formulário de cadastro.

3. **Após o cadastro**, o sistema redireciona para `dashboard.html`.  
   → O nome do usuário será exibido automaticamente.

4. *(Opcional)* Crie um arquivo `login.html` se quiser permitir login separado.

---

## 🧩 Exemplo de Fluxo

| Etapa | Arquivo | Ação |
|:------|:---------|:------|
| 1️⃣ | cadastro.html | Cadastro de novo usuário |
| 2️⃣ | dashboard.html | Exibição da mensagem de boas-vindas |
| 3️⃣ | (opcional) login.html | Login com e-mail e senha |

---

## 🛠️ Melhorias Futuras

- Integração com API REST real para autenticação.
- Criptografia de senha (no backend).
- Design responsivo completo (mobile-first).
- Sistema de logout e controle de sessão.

---

## 👨‍💻 Autor

**Seu Nome**  
📧 Email: seu.email@exemplo.com  
🔗 GitHub: [https://github.com/seu-usuario](https://github.com/seu-usuario)

💡 Projeto desenvolvido para fins educacionais e de prototipagem de interface.

