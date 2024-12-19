# java-script
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Como Fazer uma Torta de Frango</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Receita de Torta de Frango</h1>
    </header>
    <main>
        <section id="ingredientes">
            <h2>Ingredientes</h2>
            <ul>
                <li>500g de peito de frango desfiado</li>
                <li>1 cebola picada</li>
                <li>2 dentes de alho picados</li>
                <li>1 lata de milho verde</li>
                <li>1 lata de ervilha</li>
                <li>1 copo de requeijão</li>
                <li>Sal e pimenta a gosto</li>
                <li>Massa pronta para torta</li>
            </ul>
        </section>
        <section id="preparo">
            <h2>Modo de Preparo</h2>
            <ol>
                <li>Refogue a cebola e o alho até dourar.</li>
                <li>Adicione o frango desfiado e refogue por mais alguns minutos.</li>
                <li>Acrescente o milho, a ervilha e o requeijão, misturando bem.</li>
                <li>Tempere com sal e pimenta a gosto.</li>
                <li>Forre uma forma com a massa de torta, coloque o recheio e cubra com mais massa.</li>
                <li>Asse em forno pré-aquecido a 180°C por cerca de 30 minutos ou até dourar.</li>
            </ol>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Receita de Torta de Frango</p>
    </footer>

<script>
    document.addEventListener('DOMContentLoaded', function() {
        const ingredientes = [
            '500g de peito de frango desfiado',
            '1 cebola picada',
            '2 dentes de alho picados',
            '1 lata de milho verde',
            '1 lata de ervilha',
            '1 copo de requeijão',
            'Sal e pimenta a gosto',
            'Massa pronta para torta'
        ];

        const preparo = [
            'Refogue a cebola e o alho até dourar.',
            'Adicione o frango desfiado e refogue por mais alguns minutos.',
            'Acrescente o milho, a ervilha e o requeijão, misturando bem.',
            'Tempere com sal e pimenta a gosto.',
            'Forre uma forma com a massa de torta, coloque o recheio e cubra com mais massa.',
            'Asse em forno pré-aquecido a 180°C por cerca de 30 minutos ou até dourar.'
        ];

        const ingredientesList = document.querySelector('#ingredientes ul');
        const preparoList = document.querySelector('#preparo ol');

        ingredientes.forEach(item => {
            const li = document.createElement('li');
            li.textContent = item;
            ingredientesList.appendChild(li);
        });

        preparo.forEach(item => {
            const li = document.createElement('li');
            li.textContent = item;
            preparoList.appendChild(li);
        });
    });
</script>
</body>
</html>
