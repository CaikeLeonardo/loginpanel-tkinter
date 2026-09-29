# 🔐 Painel de Login & Cadastro em Python (Tkinter)

Um sistema desktop simples e funcional de **autenticação e cadastro de usuários** desenvolvido em Python utilizando a biblioteca gráfica **Tkinter**. O projeto conta com uma interface personalizada e persistência local de dados.

---

## 🚀 Funcionalidades

- 🔑 **Autenticação de Usuários:** Validação de credenciais cadastradas com alertas visuais para login bem-sucedido ou dados incorretos.
- 📝 **Cadastro de Novos Usuários:** Permite registrar novos usuários e senhas diretamente pela interface gráfica, evitando duplicidades.
- 💾 **Persistência de Dados:** Armazenamento das credenciais em arquivo de texto local (`credenciais.txt`).
- 🎨 **Interface Gráfica Personalizada:** Layout fixo, paleta de cores centralizada no arquivo `cores.py` e componentes estilizados.
- 💬 **Mensagens de Feedback:** Notificações em tempo real utilizando pop-ups da biblioteca `messagebox`.

---

## 🛠️ Tecnologias Utilizadas

- **[Python](https://www.python.org/)** — Linguagem principal
- **[Tkinter](https://docs.python.org/3/library/tkinter.html)** — Interface gráfica do sistema (GUI)

---

## 📁 Estrutura do Projeto

```text
├── cores.py            # Definição das variáveis de cores (HEX) da interface
├── credenciais.txt     # Arquivo de persistência local das contas
└── painel_login.py     # Código principal da aplicação gráfica e lógica
```

---

## ⚙️ Como Executar o Projeto

### Pré-requisitos

Certifique-se de ter o **Python 3.x** instalado na sua máquina. O `Tkinter` geralmente já vem incluído na instalação padrão do Python.

### Passo a passo

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   ```

2. **Navegue até a pasta do projeto:**
   ```bash
   cd seu-repositorio
   ```

3. **Execute a aplicação:**
   ```bash
   python painel_login.py
   ```

---

## 💡 Dicas para Evolução do Projeto (Roadmap)

Se você desejar expandir este projeto para o seu portfólio, aqui estão algumas sugestões de melhorias:

- [ ] **Criptografia de Senhas:** Utilizar a biblioteca `hashlib` ou `bcrypt` para não salvar senhas em texto puro.
- [ ] **Banco de Dados:** Substituir o arquivo `.txt` por **SQLite** ou **MySQL**.
- [ ] **Ocultar/Exibir Senha:** Adicionar um botão no campo de senha para alternar a visibilidade dos caracteres.
- [ ] **Validações Avançadas:** Impedir campos vazios ou senhas muito curtas.

---

## 📝 Licença

Este projeto está sob a licença MIT. Sinta-se livre para usar e modificar para estudos.

---
Developed with 💚 by [Caike Leonardo](https://github.com/CaikeLeonardo)
