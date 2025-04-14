<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Atividade While</title>
</head>
<body>

    <script>
        //criar variavel
        while (true) {
        var usuario = prompt("Digite o seu usuário")
        var senha = parseInt(prompt("Digite a sua seha"))
        
        //Criar condição IF ELSE
        if(usuario == "SENAI" && senha == "2025999") {
            document.write("Acesso consedido")
            break;
        }else {
            alert("Usuario/senha incorretos! Tente novamente")
        }
    }
    </script>
</body>
</html>
