# appLembrete
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aplicativo de Lembrete</title>
    <link rel="stylesheet" href="style.css">
    <script src="script.js" defer></script>
</head>
<body>
    <h1>Aplicativo de Lembrete</h1>
    <form id="reminder-form">
        <label for="title">Título do Lembrete:</label>
        <input type="text" id="title" name="title" required>
        <br>
        <label for="date">Data do Lembrete:</label>
        <input type="date" id="date" name="date" required>
        <br>
        <button type="submit">Criar Lembrete</button>
    </form>
    <div id="reminders-list">
        <!-- Aqui é onde os lembretes serão exibidos -->
    </div>
</body>
</html>
