# Front-End
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <title>Verificação de Nota</title>
</head>
<body>
    <script>
        let nota = parseFloat(prompt("Digite sua nota (0 a 10):"));

        if (nota === 10) {
            prompt("PARABÉNS! Você fechou com DEZZZZZZ!");
        } 
        else if (nota >= 7 && nota <10) {
            prompt(" Parabéns, você arrasou!");
        } 
        else if (nota >= 4 && nota <6) {
            prompt("Você está de recuperaçãooooo.");
        } 
        else if (nota >= 1 && nota <4) {
            prompt("Rodou bb. Mas não desanima! Ano que vem você passa!");
        } 
        else if(nota >=11 && nota <0){
            prompt("Digite a sua nota de 0 a 10.");
        }
    </script>
</body>
</html>
