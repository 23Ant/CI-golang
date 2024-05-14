### CI-golang

---

#### Visão Geral

Este repositório, [CI-golang](https://github.com/23Ant/CI-golang), é voltado para a demonstração da integração contínua (Continuous Integration - CI) usando Go (Golang) e Docker, juntamente com GitHub Actions para automatizar o processo de criação e atualização de imagens no Docker Hub.

#### Descrição do Projeto

O projeto consiste em:

- **Desenvolvimento em Go**: Utilizamos a linguagem Go para desenvolver aplicações simples que demonstram conceitos básicos da linguagem, facilitando o entendimento da estrutura de código em Go.
- **Dockerização**: Empacotamos nossa aplicação em uma imagem Docker, o que simplifica o processo de distribuição e implantação da aplicação em qualquer ambiente que suporte Docker.
- **Integração Contínua**: Implementamos CI com GitHub Actions, o que nos permite automatizar testes e o deployment da nossa imagem Docker no Docker Hub sempre que houver uma alteração no repositório.

#### Estrutura do Repositório

Aqui está uma breve descrição dos componentes chave do repositório:

- **.github/workflows**: Contém os scripts de CI construídos com GitHub Actions para automatizar o teste e o deployment.
- **Dockerfile**: Script para criar uma imagem Docker da aplicação Go.
- **README.md**: Este arquivo, que fornece uma visão geral e guia sobre o projeto.
- **go.mod**: Arquivo que gerencia as dependências do projeto.
- **math.go**: Um exemplo de arquivo de código fonte em Go, exemplificando uma função matemática simples.
- **math_test.go**: Arquivo de teste para as funções definidas em `math.go`.

#### Tecnologias Utilizadas

- Linguagem de Programação: **Go** 
- Docker para a criação de containers: **Dockerfile** 

#### Como Usar

1. **Clonar o Repositório:**
   ```bash
   git clone https://github.com/23Ant/CI-golang.git
   ```
   
2. **Construir a Imagem Docker:**
   ```bash
   docker build -t ci-golang .
   ```

3. **Executar a Aplicação via Docker:**
   ```bash
   docker run ci-golang
   ```

4. **Visualizar Workflows:**
   Acesse a pasta `.github/workflows` para examinar e personalizar os workflows de CI/CD conforme necessário.

#### Contribuições

Contribuições são sempre bem-vindas! Sinta-se à vontade para forkar o repositório, fazer suas alterações e abrir um Pull Request para a integração das mudanças.

#### Contato

Para mais informações ou dúvidas, por favor, abra uma 'issue' diretamente no (https://github.com/23Ant/CI-golang).

---

Este README serve como um guia inicial para compreender e colaborar com o projeto CI-golang. Ele foi construído para facilitar o uso e contribuição para o projeto, garantindo uma experiência fluida e educativa para desenvolvedores que desejam explorar CI/CD com Go e Docker.  
