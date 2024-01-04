# Django Alura Space

Este é um projeto Django para criar uma galeria de fotos web. A aplicação permite aos usuários visualizar, carregar e compartilhar suas fotos de maneira fácil e eficiente.

## Instalação

1. **Clone o repositório:**

```bash
git clone https://github.com/DyegoTkrD/Allura-Space
```

2. Crie um ambiente virtual e ative-o:
```bash
cd Allura-Space
python -m venv venv
source venv/bin/activate  # Para sistemas Unix/Mac
venv\Scripts\activate  # Para Windows
```

3. Instale as dependências:
```bash
pip install -r requirements.txt
```

4. Aplique as migrações:
```bash
python manage.py migrate
```

5. Crie um superusuário:
```bash
python manage.py createsuperuser
```

6. Execute o servidor de desenvolvimento:
```bash
python manage.py runserver
```
Acesse a aplicação em http://localhost:8000/ e o painel administrativo em http://localhost:8000/admin/ usando as credenciais do superusuário criado anteriormente.

## Funcionalidades
Página Inicial: Visualize uma galeria de fotos em miniaturas.
Upload de Fotos: Faça o upload de novas fotos diretamente no site.
Detalhes da Foto: Visualize detalhes da foto, incluindo a data do upload e informações adicionais.
Busca: Pesquise fotos com base em palavras-chave ou categorias.
Painel Administrativo: Gerencie fotos, categorias e usuários por meio de um painel administrativo.

## Contribuição
Contribuições são bem-vindas! Se você deseja melhorar o projeto, adicionar recursos ou corrigir problemas, siga as etapas abaixo:

1. Faça um fork do projeto (https://github.com/seu-usuario/django-photo-gallery/fork)
2. Crie uma branch para sua modificação (git checkout -b feature/nova-feature)
3. Faça commit das suas alterações (git commit -am 'Adiciona nova feature')
4. Faça push para a branch (git push origin feature/nova-feature)
5. Crie um novo Pull Request

## Tecnologias Utilizadas
Django: O framework web utilizado para o backend.
HTML/CSS/JavaScript: Tecnologias front-end para uma experiência de usuário interativa.
SQLite: Banco de dados leve para armazenamento de dados.
