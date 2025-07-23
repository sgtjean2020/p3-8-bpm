# p3-8-bpm
cartão programa
# 📋 Cartão de Rotas RP

Sistema web para gerenciamento de cartões-programa utilizados pelo 8º BPM de Nova Andradina/MS. Permite o cadastro, visualização e edição de rotas operacionais, facilitando o controle digital das atividades de patrulha.

---

## 🚓 Funcionalidades

- Upload de cartões (.docx) com extração de dados
- Visualização em formato cronológico
- Edição direta no banco de dados
- Painel com listagem completa de cartões
- Tela de login e controle de usuários (em desenvolvimento)
- Exportação para PDF (futuramente)

---

## 🛠️ Tecnologias Utilizadas

- Python 3 + Flask
- HTML + CSS (com estilo institucional PM)
- SQLite + SQLAlchemy
- GitHub + Render (deploy gratuito)

---

## ⚙️ Como Rodar Localmente

```bash
git clone https://github.com/seuusuario/cartoes-rp.git
cd cartoes-rp
pip install -r requirements.txt
python app.py
