#CV_Igor_Completo

**CV_igor**
# Parte 1
<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01//EN"
			"http://www.w3.org/TR/html4/strict.dtd">
<meta http-equiv="Content-Type" content="text/html;charset=utf-8" >
<html>
	<head>
		<title>Curriculo Vitae</title>
		<link rel="stylesheet" type="text/css" href="style.css">
	</head>
	
	<body>
		<h1>Curriculo Vitae</h1>
		
		<ul id="menu">
			<li><a href="cv_igor_resumido.html">Resumido</a></li>
			<li class="ativo">Completo</li>
		</ul>
		
		<div class="secao">
			<h2>Dados Pessoais</h2>			
				<div id="hcard-Ademir-Mazer-Jr" class="vcard">
				  <img src="f.elconfidencial.com_original_09f_75f_610_09f75f61060ddbb36bac4960e843d508.jpg" alt="photo of Chuck Norris" class="photo" style="width: 200px; height: 200px;"/>
				 <span class="given-name">Igor</span>
				  <span class="additional-name">Menezes</span>
				  <span class="family-name">Sales</span>
                  <span class="family-name">Vieira</span>
				<sup><a href="#1-fn" id="fn1" title="veja o rodapé">1</a></sup>

				 <a class="email" href="mailto:igormsv66@gmail.com">igormsv66@gmail.com</a>
				 <a class="url" href="linkedin.com/in/igorvieira-0b1809168">linkedin.com/in/igorvieira-0b1809168</a>
				
				<div class="adr">
				  <span class="locality">Manaus</span>
				, 
				  <span class="region">Amazonas</span>

				 </div>
				</div>
		</div>

		<div class="secao">
			<h2>Dados Profissionais</h2>
			
			<p><label>Empresa</label>The Brownie: 2022 - Presente</p>
			<p><label>Empresa</label>Samsung Ocean: 2021 - 2022</p>
			<p><label>Empresa</label>Reitoria da Universidade do Estado do Amazonas - UEA</p>
		</div>

		<div class="secao">
			<h2>Formação</h2>
			
			<p><label>Ensino Superior</label>(Em andamento) Análise e Desenvolvimento de Sistemas - FMF</p>
			<p><label>Ensino Superior</label>Administração - UEA</p>
			<p><label>Ensino Médio</label>Colégio Santa Dorotéia</p>
		</div>

        <div class="secao">
			<h2>Idiomas</h2>
			
			<p><label>Idioma 1</label>Português</p>
			<p><label>Idioma Complementar</label>Inglês Avançado</p>
			<p><label>Idioma Complementar</label>Alemão intermediário</p>
		</div>

        <div class="secao"><h2>Cursos Complementares</h2>
        
            <p><label>Programação</label>Lógica de Programação - Fundação Bradesco</p>
            <p><label>Programação</label>Programação Orientada a Objetos - Fundação Bradesco</p>
            <p><label>Computação</label>AWS Cloud Practioner - KA Solutions</p>
            <p><label>Gestão</label>Design Thinking Experience - Echos Online</p>
        </div>
    
		
		<div id="footnote">
			<li id="1-fn">1 - Microformato <a href="#fn1" title="volte">^</a></li>
			<li>Este <a href="http://microformats.org/wiki/hcard">hCard</a> foi criado com <a href="http://microformats.org/code/hcard/creator">hCard creator</a>.</li>
		</div>		
	</body>
</html>

#**CV_igor_resumido**
# Parte 2
<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01//EN"
			"http://www.w3.org/TR/html4/strict.dtd">
<meta http-equiv="Content-Type" content="text/html;charset=utf-8" >
<html>
	<head>
		<title>Curriculo Vitae</title>
		<link rel="stylesheet" type="text/css" href="style.css">
	</head>
	
	<body>
		<h1>Curriculo Vitae</h1>
		
		<ul id="menu">
			<li class="ativo">Resumido</li>
			<li><a href="cv_igor.html">Completo</a></li>
		</ul>
		
		<div class="secao">
			<h2>Dados Pessoais</h2>
				<div id="hcard-Igor-Menezes-Sales-Vieira" class="vcard">
				 <a class="url fn n" href="linkedin.com/in/igorvieira-0b1809168">  
                  <span class="given-name">Igor</span>
				  <span class="additional-name">Menezes</span>
				  <span class="family-name">Vieira</span>
				 </a>
				</div>
		</div>

		<div class="secao">
			<h2>Dados Profissionais</h2>
			
			<p><label>Empresa</label>The Brownie: 2022 - Presente</p>
			<p><label>Empresa</label>Samsung Ocean: 2021 - 2022</p>
			<p><label>Empresa</label>Reitoria da Universidade do Estado do Amazonas-UEA: 2018 - 2019</p>
		</div>
	</body>
</html>

# **css**
# Parte 3
body {
	font: 14px "Lucida Grande", "Trebuchet MS", Verdana, sans-serif;
	color: #3b3b3b;
}

h1,h2 {
	font-family: Georgia;
}

h1 {
	border-bottom: 3px solid #aaa;
	background-color: #3b3b3b;
	color: #ddd;
	padding: 5px;	
}

h2 {
	border-top: 1px solid #ccc;
	border-bottom: 1px solid #ccc;
	background-color: #DDD;
	padding-left: 5px;
	margin: 0 0 0 -15px;
	font-weight: normal;
}

.secao {
	background-color: #eee;
	padding-left: 15px;
}

label {
	font-weight: bold;
	margin-right: 10px;
}

label:after {
	content: ":";
}

a {
	text-decoration:none;
	color: #f33;
}

a:visited {
	text-decoration:none;
	color: #700;
}

a:hover {
	text-decoration:none;
	color: #fa0;
}

#menu {
	margin: 0;
}

#menu ul, #menu li {
	display: inline;
	list-style-type: none;
	margin: 0;
	padding: 0;
}

#menu .ativo {
	background-color: #ddd;
}

.vcard {
	padding: 5px;
}

.url, .email {
	display: block;
}

.photo {
	float: right;
	margin-right: 20%;
}

#footnote {
	border-top: 1px dashed #aaa;
	padding: 5px;
	font: 75% "Lucida Grande", "Trebuchet MS", Verdana, sans-serif;
	
}

#footnote li {
	list-style-type: none;
	margin-top: 3px;
}
