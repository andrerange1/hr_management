##  HR-control API
<br>

<a style="color: teal;" href="https://documenter.getpostman.com/view/20745940/Uz5DocEb">
    <b>Link para a documentação no postman</b>
</a>

<br>
<p>
<b>HR-control</b> é uma API feita para auxiliar os setores de recursos humanos em empresas, onde administradores cadastrados podem registrar e consultar funcionários além de administrar contratos e informações pessoais de cada um. O sistema também recebe informações e currículos de candidatos a eventuais vagas de trabalho. 
<p>

## 

<li>
A api possui proteção na maioria de seus endpoints então temos um administrador pré-cadastrado no banco para que possam ser criados outros adminstradores
</li>

## 

<strong>Para rodar a API LOCALMENTE</strong>

<p>1 - Clone o projeto</p>
    
<p>2 - Instale o Virtualenv</p>

<li>pip install virtualenv</li>
<br/>
<p>3 - No console dentro da pasta do projeto, crie o ambiente virtual</p>

<li>virtualenv venv</li>
<br/>

<p>4 - Acesse o ambiente virtual criado</p>
<li>source venv/bin/activate</li>
<br/>

<p>5 - Dentro do ambiente virtual, instale as dependências do projeto</p>
<li>pip install -r requirements.txt</li>
<br/>
<p>6 - Rode as migrations do projeto para construir as tabelas do banco</p>
<li>python manage.py migrate</li>
<br/>
<p>7 - Inicie o servidor</p>
<li>python manage.py runserver</li>
<br/>
<p>8 - O endereço do servidor irá aparecer no terminal</p>
<li>Consulte a documentação do postman para conferir as rotas</li>
