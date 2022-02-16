# geolocalizacao_com_django

<p>O objetivo desse projeto é utiliza a geolocalização com base no IP aleatório gerado pela bliblioteca geoip2</p> </br>
<p>O sistema faz uma busca recebendo como parametro o segmento do estabelecimento e a localidade, caso a localidade não seja informada será usada a localidade baseada no IP.
A busca é feita utilizando a API da plataforma Yelp, logo a após fazer a requisição para a API é exibido na pagina o nome do estabelecimento e a localidade junto com o mapa usando a bliblioteca leaftMap e OpenStretMap marcando as localidades com um bindPoup 
</p>
<h1>Pré Requisito</h1>
<ul>
<li>Python 3x</li>
<li>Django 4x</li>
<li>Geoip 2x</li>
<li>Request 2x</li>
</ul>
<h1>Testando o projeto</h1>
<p>Abra o projeto na IDE de sua preferência ative o ambiente virtual.</p><br>
<p>Logo apos execute o comando <strong>python manage.py runserver</strong></p>
