<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Motorready - Encuentra tu moto ideal</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: url('https://images.unsplash.com/photo-1503376780353-7e6692767b70?auto=format&fit=crop&w=1950&q=80') no-repeat center center/cover;
      color: white;
    }

    header {
      background-color: #003399;
      padding: 10px 20px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    header h1 {
      margin: 0;
      color: white;
      font-size: 1.8em;
    }

    .search-bar input {
      padding: 8px;
      border-radius: 5px;
      border: none;
    }

    .main-content {
      text-align: center;
      padding: 100px 20px;
      background-color: rgba(0, 0, 0, 0.5);
    }

    .main-content h2 {
      margin-bottom: 30px;
      font-size: 2.2em;
    }

    .filters select {
      margin: 10px;
      padding: 10px;
      border-radius: 5px;
      border: none;
      width: 200px;
    }

    .filters button {
      padding: 10px 20px;
      background-color: red;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      font-weight: bold;
    }

    .top-bar a {
      color: white;
      text-decoration: none;
      margin: 0 10px;
    }

    .top-bar {
      display: flex;
      gap: 15px;
    }
  </style>
</head>
<body>

  <header>
    <h1>Motorready</h1>
    <div class="search-bar">
      <input type="text" placeholder="Busca tu moto ideal" />
    </div>
    <div class="top-bar">
      <a href="#">Inicio</a>
      <a href="#">Clasificados</a>
      <a href="#">Financiamiento</a>
      <a href="#" style="color: red;">PUBLICA GRATIS</a>
    </div>
  </header>

  <div class="main-content">
    <h2>ENCUENTRA TU MOTO IDEAL</h2>
    <div class="filters">
      <select><option>Todas las clases</option></select>
      <select><option>Todas las marcas</option></select>
      <select><option>Todas las familias</option></select>
      <select><option>Todos los modelos</option></select>
      <select><option>Todas las clasificadas</option></select>
      <select><option>Todos los departamentos</option></select>
      <br />
      <button>BUSCAR</button>
    </div>
  </div>

</body>
</html>

