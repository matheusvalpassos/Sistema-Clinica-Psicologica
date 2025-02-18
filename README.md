# 🏥 Sistema Clínica Psicológica

Este é um sistema para clínicas psicológicas desenvolvido para gerenciar consultas, armazenar gravações, registrar o humor do paciente e gerar gráficos para fácil visualização. Além disso, permite salvar exercícios passados pelo psicólogo, ativar ou inativar cadastros conforme pagamento e manter o controle dos dias de consulta dos pacientes.

#  ▶ Começando

Essas instruções permitirão que você obtenha uma cópia do projeto em operação na sua máquina local para fins de desenvolvimento e teste.

Instalação

Siga os passos abaixo para configurar o ambiente:

```
# Clone o repositório:
git clone https://github.com/seu-usuario/Sistema-Clinica-Psicologica.git

# Acesse a pasta do projeto:
cd Sistema-Clinica-Psicologica

# Crie um ambiente virtual (recomendado):
python3 -m venv .venv  # Cria o ambiente virtual
source .venv/bin/activate  # Ativa o ambiente virtual (Linux/macOS)
.venv\Scripts\activate  # Ativa o ambiente virtual (Windows)

# Instale as dependências:
pip install -r requirements.txt

# Execute as migrações do banco de dados:
python manage.py migrate

# Inicie o servidor:
python manage.py runserver
```

#  ⚙️ Executando os testes
```
python manage.py runserver
```

#  📦 Dependências

O sistema foi desenvolvido utilizando Django e as seguintes bibliotecas:
```
asgiref==3.8.1
Django==5.1.6
pillow==11.1.0
sqlparse==0.5.3
tzdata==2025.1
```
Expressões de gratidão
Um agradecimento publicamente Caio Sampaio, responsável pelo intensivo 4DAYS 4PROJECTS da @Pythonando.

⌨️ com ❤️ por Matheus Valpassos
