# Site-basico-HTML-CSS
Site básico que fiz com as linguagens HTML+CSS. 

<!DOCTYPE html>
<html>
	<head>
		<title>TecBlog - O seu Blog de Técnologia</title>
		<meta charset="utf-8">
		<link rel="stylesheet" type="text/css" href="estilos/estilos.css">
	</head>
	<body> 
		<!--inicio área topo -->
		<div id="area-topo"> 
			<div id="area-logo">
			<h1>Tec<span class="branco">Blog</span></h1>
			</div>
			<div id="area-menu">
				<a href="index.html">Home</a>
				<a href="jogos.html">Jogos</a>
				<a href="celulares.html">Celulares</a>
				<a href="informatica.html">Informática</a>
				<a href="eletronicos.html">Eletrônicos</a>
			</div>
		</div> 
		<!--inicio área conteúdo-->
		<div id="area-conteudo">
			<div id="area-postagem">

				<!-- abertura postagem -->
				<div class="postagem">
					<h2>Titulo da Postagem 1</h2>
					<span class="data-postagem">postado em 20 de março 2022</span>
					<img src="imagens/imagem1.jpg">
					<p>
						Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s
					</p>
					<a href="">Leia Mais</a>
				</div><!-- fim postagem -->

				<!-- abertura postagem -->
				<div class="postagem">
					<h2>Titulo da Postagem 2</h2>
					<span class="data-postagem">postado em 10 de março 2022</span>
					<img src="imagens/imagem2.jpg">
					<p>
						Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s
					</p>
					<a href="">Leia Mais</a>
				</div><!-- fim postagem -->
			</div><!-- fim area conteudo -->

			<!-- inicio area leteral -->
			<div id="area-lateral">

				<div class="conteudo-lateral">
					<h3>Postagens recentes</h3>
					<div class="postagem-lateral">
						<p >
							Lorem Ipsum is simply dummy text of the printing and typesetting industry.
						</p>
						<a href="">Leia Mais</a>
					</div>
					<div class="postagem-lateral" style="border-bottom: none;">
						<p >
							Lorem Ipsum is simply dummy text of the printing and typesetting industry.
						</p>
						<a href="">Leia Mais</a>
					</div>
				</div>
				<div class="conteudo-lateral">
					<h3>Categorias</h3>
					<a href="index.html">Inovações</a><br>
					<a href="jogos.html">Jogos</a><br>
					<a href="celulares.html">Celulares</a><br>
					<a href="informatica.html">Tecnologia</a><br>
					<a href="eletronicos.html">Eletrônicos</a>
				</div>

			</div>
				
			<div id="rodape">
				<p>todos os direitos reservados</p>
			</div>

		</div>
	</body>
</html>	

