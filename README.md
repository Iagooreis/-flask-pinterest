# Pinterest Clone

Um clone simples do Pinterest desenvolvido com Flask, permitindo que os usuários façam upload de imagens, criem contas e explorem um feed de imagens.

## Tecnologias Utilizadas

- **Backend:** Flask, Flask-Login, Flask-SQLAlchemy
- **Frontend:** HTML, CSS, Bootstrap
- **Banco de Dados:** SQLite
- **Armazenamento de Imagens:** Upload via Flask

## Funcionalidades

- Cadastro e login de usuários
- Upload e exibição de imagens
- Feed com imagens enviadas por usuários
- Interface simples e responsiva

## Como Rodar o Projeto

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/Iagooreis/flask-pinterest.git
    cd flask-pinterest
   ```

2. **Crie e ative um ambiente virtual:**
   ```bash
   python -m venv venv
   source venv/bin/activate  # Linux/Mac
   venv\Scripts\activate  # Windows
   ```

3. **Instale as dependências:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Execute a aplicação:**
   ```bash
   flask run
   ```

5. **Acesse no navegador:**
   ```
   http://127.0.0.1:5000
   ```

## Estrutura do Projeto

```
📂 pinterest-clone
├── 📁 static            # Arquivos estáticos (CSS, imagens)
├── 📁 templates         # Templates HTML
├── app.py              # Arquivo principal do Flask
├── models.py           # Modelos do banco de dados
├── forms.py            # Formulários do Flask-WTF
├── config.py           # Configuração do projeto
├── requirements.txt    # Dependências do projeto
└── README.md           # Este arquivo
```

## Melhorias Futuras

- Implementar sistema de curtidas e comentários
- Criar páginas de perfil para usuários
- Melhorar a interface com mais elementos visuais


