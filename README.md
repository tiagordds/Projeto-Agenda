# Instalação
Passo-a-passo:

1. Clone o repositório:

```bash
git clone [https://github.com/tiagordds/ecommmerce.git](https://github.com/tiagordds/Projeto-Agenda)
cd Projeto_Agenda
```

2. Crie um ambiente virtual (opcional, mas recomendado):

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Instale as dependências:

```bash
pip install -r requirements.txt
```

5. Faça as migrações:

```bash
python manage.py migrate
```

5. Inicialize o servidor:

```bash
python manage.py runserver
```


7. Acesse:

### Abra o seu navegador e acesse http://127.0.0.1:8000/

8. (Opcional) Caso queira popular a base de dados com informações, utilize o script na pasta utils. Navege até a pasta, e rode:

```bash
python create_contacts.py
```
