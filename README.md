# API de Autenticação de Login com Spring Security e JWT

Esta API é um sistema de autenticação de login desenvolvido em Java com o framework Spring Security e JWT (JSON Web Tokens). Ela fornece endpoints RESTful para autenticar usuários e gerar tokens de acesso para acessar recursos protegidos.

## Funcionalidades Principais

- **Autenticação de Usuários**: A API permite que os usuários se autentiquem fornecendo credenciais de login (por exemplo, e-mail e senha).
- **Geração de Token JWT**: Após a autenticação bem-sucedida, a API gera um token JWT que pode ser usado para autorizar acesso a recursos protegidos.
- **Proteção de Recursos**: A API utiliza o Spring Security para proteger endpoints e recursos, garantindo que apenas usuários autenticados tenham acesso.

## Tecnologias Utilizadas

- **Java**: Linguagem de programação principal.
- **Spring Framework**: Utilizado para desenvolver a API RESTful e a segurança de aplicativos.
- **Spring Security**: Utilizado para autenticação e autorização de usuários.
- **JWT (JSON Web Tokens)**: Utilizado para geração de tokens de acesso após a autenticação.
