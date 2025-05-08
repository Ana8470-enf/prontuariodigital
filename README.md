# Prontuário Digital

Prontuário Digital é um sistema de gerenciamento de prontuários médicos digitais desenvolvido para facilitar o armazenamento e a recuperação de dados de pacientes.

## Estrutura do Projeto

```plaintext
prontuariodigital/
├── backend/
│   ├── app/
│   │   ├── __init__.py
│   │   ├── models.py
│   │   ├── schemas.py
│   │   ├── database.py
│   │   ├── main.py
│   │   ├── whisper_integration.py
│   │   ├── voice_auth.py
│   ├── requirements.txt
│   ├── Dockerfile
│   ├── render.yaml
├── frontend/
│   ├── public/
│   │   ├── index.html
│   ├── src/
│   │   ├── App.js
│   │   ├── index.js
│   │   ├── api.js
│   │   ├── styles.css
│   ├── package.json
│   ├── Dockerfile
│   ├── render.yaml
├── .gitignore
├── README.md
