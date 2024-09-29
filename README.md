# Calculadora de Carbono

<h1>Tutorial para execução da aplicação Django em sua máquina</h1>

##<h2>Pré requisitos</h2><hr>
    <ul>
        <li>Possuir Git instalado em seu sistema [Realize a instalação clicando aqui](https://git-scm.com/downloads)</li>
        <li>Requer Python 3.7 ou superior [Você pode instalar por aqui](https://www.python.org/downloads/)</li>
        <li>IDE VS Code</li>
    </ul>

<h2>Passos</h2><hr>
<h3>Clonar o repositório</h3>
<ol>
    <li>Abra seu terminal e navegue até o diretório onde deseja clonar o projeto e execute o comando:</li>
        <code>git clone https://github.com/gabrielSMarcal/calculadora_carbono.git</code>
    <li>Navegue até o seu diretório no projeto:</li>
        <code>cd "seu-repositorio"</code>
    <li>Criar um ambiente virtual (venv):</li>
        <code>py -m venv venv</code>
        <p>Isso criará uma pasta chamada venv dentro do seu diretporio de projeto, contendo uma cópia isolada do interpretador Python e de todas as dependências do projeto.</p>
    <li>Ativar o ambiente virtual:<li>
        <ul>
            <li>Linux/macOS:</li>
                <code>source venv/bin/activate</code>
            <li>Windows:</li>
                <code>venv/Scripts/activate</code>
        </ul><br>
        <p>Você saberá que o ambiente virtual foi criado, pois poderá ser possível visualizar algo como: (venv) C:/Users/seu-usuario/seu-repositório<p>
    <li>Instalar as dependências:</li>
        <code>pip install -r requirements.txt</code>
        <p>Este comando irá instalar todas as bibliotecas Python necessárias listadas no arquivo requirements.txt</p>
    <li>Executar o servidor de desenvolvimento:</li>
        <code>py manage.py runserver</code>
        <p>Por fim, este comando irá lhe permitir acessar o aplicativo em seu navegador web padrão, geralmente em http://127.0.0.1:8000</p>
</ol>
            
                

