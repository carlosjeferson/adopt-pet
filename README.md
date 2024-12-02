# Projeto de Adoção de Pets 🐾

Este projeto tem como objetivo criar uma aplicação web para gerenciar o processo de adoção de pets. A aplicação permitirá o registro e controle de informações sobre os animais disponíveis, os adotantes interessados e os atendimentos realizados, utilizando uma interface intuitiva e responsiva.

---

## 🎯 Objetivos do Projeto

- **Desenvolver uma aplicação web** completa para gerenciar o processo de adoção de pets.  
- Implementar dois **CRUDs**:
  - **Animais**: Gerenciar os pets disponíveis para adoção.  
  - **Adotantes**: Gerenciar as informações dos interessados em adotar.  
- Criar uma funcionalidade para registrar e visualizar **Atendimentos** realizados no processo de adoção.

---

## 🛠️ Tecnologias Propostas

- **Linguagem Back-end**: Python  
- **Framework para API**: FastAPI  
- **Banco de Dados**: SQLite  
- **Linguagens Front-end**: HTML, CSS, JavaScript  
- **Framework Front-end**: TailwindCSS  
- **Biblioteca para Requisições**: Axios ou Fetch API  
- **Hospedagem**: Deploy em plataformas como Vercel ou Render  

---

## 📑 Estrutura do Projeto

### 1. **Entidades Principais**  
- **Animal**  
  - ID  
  - Nome  
  - Espécie (cão, gato, etc.)  
  - Idade  
  - Disponibilidade para adoção  

- **Adotante**  
  - ID  
  - Nome  
  - Telefone  
  - Endereço  
  - Histórico de adoções  

- **Atendimento**  
  - ID  
  - Data do atendimento  
  - ID do Animal  
  - ID do Adotante  
  - Status (concluído, pendente)  

### 2. **Funcionalidades**  
- Cadastro, listagem, edição e remoção de animais e adotantes.  
- Registro de atendimentos vinculando animais e adotantes.  
- Página inicial apresentando animais disponíveis para adoção.  

---

## 🌐 Funcionalidades Web

1. **Interface do Usuário**:  
   - Página para visualizar animais disponíveis para adoção.  
   - Formulários para cadastro e edição de dados.  

2. **API Back-end**:  
   - Endpoints RESTful para todas as operações CRUD.  

3. **Validações**:  
   - Controle de dados obrigatórios nos formulários.  
   - Verificação de disponibilidade dos animais para adoção.  

---

## 🚀 Passos para Desenvolvimento

1. **Configuração do Ambiente de Desenvolvimento**  
   - Instalar dependências: FastAPI, Uvicorn, SQLite, TailwindCSS.  

2. **Desenvolvimento do Back-end**  
   - Criar os modelos e endpoints para as entidades.  

3. **Desenvolvimento do Front-end**  
   - Construir páginas responsivas com HTML, TailwindCSS e JavaScript.  

4. **Integração**  
   - Conectar o front-end ao back-end via API RESTful.  

5. **Testes e Deploy**  
   - Testar funcionalidades e corrigir erros.  
   - Realizar o deploy da aplicação.  

---