# jubilant-octo-system
estacionamento inteligente 

<!DOCTYPE html>
<html lang="pt-br">
<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title>Estacionamento Inteligente</title>
	<link rel="stylesheet" href="style.css">
</head>
<body>
	<header>
		<nav>
			<ul>
				<li><a href="#sobre">Sobre</a></li>
				<li><a href="#servicos">Serviços</a></li>
				<li><a href="#contato">Contato</a></li>
			</ul>
		</nav>
	</header>

	<main>
		<section id="sobre">
			<h1>Sobre o Estacionamento Inteligente</h1>
			<p>O Estacionamento Inteligente é uma solução tecnológica para gerenciamento de estacionamentos, que visa tornar a experiência do usuário mais prática, segura e eficiente. Com nossos sensores de ocupação de vagas e software de gestão, podemos monitorar em tempo real a disponibilidade de vagas, otimizar o fluxo de veículos e oferecer recursos como reservas online e pagamento automatizado.</p>
			<img src="choro.jpg" alt="Estacionamento Inteligente">
		</section>

		<section id="servicos">
			<h2>Nossos Serviços</h2>
			<ul>
				<li>Sensorização de vagas de estacionamento</li>
				<li>Monitoramento em tempo real de vagas disponíveis</li>
				<li>Aplicativo para reservas e pagamento</li>
				<li>Integração com sistemas de gestão de estacionamentos existentes</li>
				<li>Sistema de câmeras de segurança e reconhecimento de placas</li>
				<li>Relatórios de utilização e faturamento</li>
			</ul>
		</section>

		<section id="contato">
			<h2>Entre em Contato</h2>
			<form action="enviar.php" method="post">
				<label for="nome">Nome:</label>
				<input type="text" id="nome" name="nome" required>
				<label for="email">E-mail:</label>
				<input type="email" id="email" name="email" required>
				<label for="telefone">Telefone:</label>
				<input type="tel" id="telefone" name="telefone" required>
				<label for="mensagem">Mensagem:</label>
				<textarea id="mensagem" name="mensagem" required></textarea>
				<input type="submit" value="Enviar">
			</form>
		</section>
	</main>

	<footer>
		<p>&copy; 2023 Estacionamento Inteligente. Todos os direitos reservados.</p>
	</footer>
</body>
</html>
