# **APP CAD**

> Um aplicativo Android simples para salvar informações em um banco de dados.

## 📱 Descrição

O **APP CAD** permite ao usuário mexer em três telas interativas para simular um cadastro e um login de um app, que serão armazenadas em um banco de dados. Você poderá inserir informções como nome, nome do login,
e uma senha.

## 🔧 Funcionalidades

- [x] Entrada de dados (nome, nome do login, senha)
- [x] Cadastrar e fazer login de um usuário
- [x] Interação entre telas

## 🚀 Tecnologias Utilizadas

- [x] **Android Studio** (Koala | 2024.1.2)
- [x] **Java** para desenvolvimento
- [x] **ConstraintLayout** para interface responsiva
- [x] **TextView** e **EditText** para entrada de dados
- [x] **Button** para executar o app.
- [X] **SQLiteOpenHelper** para a criação do banco.

## 🛠️ Como Rodar o Projeto

Siga os passos abaixo para rodar o projeto localmente:

1. Clone este repositório:

    ```bash
    git clone https://github.com/Andriele15/app-banco.git

    ```

2. Abra o projeto no Android Studio.
3. Compile e execute o projeto em um emulador ou dispositivo físico.

## 📂 Estrutura do Projeto

```bash
├── app
│ ├── src
│ │ ├── main
│ │ │ ├── java/br/ulbra/bancodedados
│ │ │ │ ├── MainActivity.java # Atividade dos botões
│ │ │ │ ├── DBHelper.java # Atividade do banco de dados
│ │ │ │ ├── LoginActivity.java # Atividade para fazer o login
│ │ │ │ ├── RegistrarActivity.java # Atividade para poder fazer o cadastro
│ │ │ ├── res
│ │ │ │ ├── layout
│ │ │ │ │ ├── activity_main.xml # Layout da tela principal
│ │ │ │ │ ├── activity_login.xml # Layout da tela de login
│ │ │ │ │ ├── activity_registrar.xml # Layout da tela de cadastro
│ │ │ │ └── values
│ │ │ │ ├── strings.xml # Strings usadas no app
│ │ │ │ ├── colors.xml # Cores definidas no projeto
│ └── build.gradle # Configuração do Gradle
└── README.md # Este arquivo
```
 
## 🎨 Design e Prototipagem
 
A interface do app foi criada usando **ConstraintLayout** para manter a responsividade em diferentes tamanhos de tela.
 
O design é minimalista e fácil de usar, com foco na simplicidade.
 
 ## 🖥️ Telas do Aplicativo

1. **Tela Principal**
 
Na tela principal, você poderá escolher entre a opção de cadastrar um usuário, ou ir para a tela de login de um usuário.
 
![principal](https://github.com/user-attachments/assets/7ef93885-7b56-4ed2-8a39-87ffae72a103)

2. **Tela De Cadastro**
 
Na tela de cadastro, você terá que inserir informções como nome, o nome para ser seu login, e sua senha. Além de você ter que confirmar a sua senha novamente.

![cadastro](https://github.com/user-attachments/assets/1309b887-5652-4e54-b741-f3c88065dbed)


2. **Tela De Login**
 
Na tela de login, você poderá fazer o login com as informações que você colocou no cadastro. Para fazer isso,
você deve colocar o que você inseriu no campo de "Insira seu login" da tela do cadastro e por fim a sua senha que foi definida. Quando você concluir o login você será mandado para a tela principal novamente.

![login](https://github.com/user-attachments/assets/a4ae7cfb-1c3a-49fa-af9f-9fcc82aba57e)


## 👨‍💻 Desenvolvedores –

**Andriele Pacheco** - Desenvolvedor - [GitHub](https://github.com/Andriele15)
 
 ## 📄 Licença MIT 
 
Este projeto está licenciado sob os termos da licença MIT. 
Para mais
detalhes, veja o arquivo [LICENSE](LICENSE).
