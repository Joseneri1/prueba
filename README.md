<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Oryzeum: Sérum Corrector Antimanchas - JIDENA LAB</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 20px;
            background-color: #f4f4f4;
            color: #333;
        }
        .container {
            max-width: 900px;
            margin: 20px auto;
            background-color: #fff;
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        h1, h2 {
            color: #0056b3;
            text-align: center;
        }
        .product-section {
            margin-bottom: 25px;
            padding: 15px;
            border: 1px solid #ddd;
            border-radius: 5px;
        }
        .tabs {
            display: flex;
            justify-content: center;
            margin-bottom: 20px;
        }
        .tab-button {
            background-color: #e9e9e9;
            border: none;
            padding: 10px 20px;
            cursor: pointer;
            font-size: 16px;
            margin: 0 5px;
            border-radius: 5px;
            transition: background-color 0.3s ease;
        }
        .tab-button.active, .tab-button:hover {
            background-color: #007bff;
            color: white;
        }
        .tab-content {
            display: none; /* Hidden by default, JavaScript will show */
            padding: 15px;
            border: 1px solid #007bff;
            border-top: none;
            border-radius: 0 0 5px 5px;
            background-color: #e0f7fa;
        }
        .tab-content.active {
            display: block;
        }
        ul {
            list-style-type: disc;
            margin-left: 20px;
        }
        .disclaimer {
            font-size: 0.9em;
            color: #777;
            text-align: center;
            margin-top: 30px;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Oryzeum: Sérum Corrector Antimanchas</h1>
        <p style="text-align: center;">De JIDENA LAB</p>

        <div class="product-section">
            <h2>Descripción del Producto</h2>
            <p>Oryzeum es un sérum corrector antimanchas innovador diseñado para combatir la hiperpigmentación cutánea. Contiene un 1% de ácido kójico, obtenido de la fermentación de <em>Aspergillus oryzae</em>, conocido por su eficacia despigmentante. [cite: 5, 7, 8, 13, 16]</p>
            <p>Simplifica tu rutina de skincare ofreciendo 3 acciones en 1: <strong>protege, cubre y aclara</strong> la hiperpigmentación. [cite: 13, 15, 27]</p>
            <p>Es una fórmula no comedogénica, libre de hidroquinona y parabenos, ideal para pieles con melasma, hiperpigmentaciones postinflamatorias y léntigos solaris. [cite: 13, 26]</p>
        </div>

        <div class="product-section">
            <h2>Detalles y Uso</h2>
            <div class="tabs">
                <button class="tab-button active" onclick="showTab('beneficios')">Beneficios Clave</button>
                <button class="tab-button" onclick="showTab('modo-uso')">Modo de Uso</button>
                <button class="tab-button" onclick="showTab('advertencias')">Advertencias</button>
            </div>

            <div id="beneficios" class="tab-content active">
                <h3>Beneficios Clave de Oryzeum</h3>
                <ul>
                    <li><strong>Acción Despigmentante:</strong> Ayuda a eliminar las manchas y unificar el tono de la piel gracias al ácido kójico al 1%[cite: 5, 10, 15, 16].</li>
                    <li><strong>Cobertura:</strong> Actúa como un corrector de maquillaje para manchas[cite: 15, 29].</li>
                    <li><strong>Protección Solar:</strong> Ofrece protección solar (SPF 15) para proteger la piel de la exposición solar directa[cite: 15, 16].</li>
                    <li><strong>Fórmula 3 en 1:</strong> Simplifica tu rutina de cuidado facial[cite: 13, 15, 27].</li>
                    <li><strong>Vegano y Cruelty-Free:</strong> Producto ético y respetuoso[cite: 38].</li>
                    <li><strong>Envase Reciclable:</strong> Comprometidos con el medio ambiente[cite: 38].</li>
                </ul>
            </div>

            <div id="modo-uso" class="tab-content">
                <h3>Modo de Uso</h3>
                <p>Aplicar sobre zonas con hiperpigmentación, con la piel limpia y seca. Distribuir uniformemente. Utilizar como un corrector de maquillaje únicamente para manchas. [cite: 28, 29]</p>
            </div>

            <div id="advertencias" class="tab-content">
                <h3>Advertencias Importantes</h3>
                <ul>
                    <li>Solo para uso externo. [cite: 29]</li>
                    <li>Evitar contacto con ojos, mucosas o piel lesionada. [cite: 30]</li>
                    <li>Suspender en caso de irritación o alergia. [cite: 30]</li>
                    <li>No combinar con otros despigmentantes sin supervisión. [cite: 31]</li>
                    <li>Realizar prueba de sensibilidad previa. [cite: 31]</li>
                    <li>Conservar entre 15°C y 25°C, en un lugar fresco, seco y sin exposición solar directa. Mantener el envase bien cerrado. [cite: 34, 35]</li>
                </ul>
            </div>
        </div>

        <div class="product-section">
            <h2>Información Adicional</h2>
            <p>Producto vegano y cruelty-free. Ingredientes GRAS (Generally Recognized As Safe), biocompatibles y seguros para uso prolongado. Envase y caja reciclables. [cite: 38]</p>
            <p>Teléfono de contacto: 55-82-17-57-74 [cite: 26]</p>
        </div>

        <div class="disclaimer">
            <p>Este es un ejemplo de estructura HTML. La funcionalidad "dinámica" (como cambiar las pestañas) se logra con JavaScript. Para cargar contenido desde una base de datos o interactuar con un servidor, se requeriría un lenguaje de backend.</p>
        </div>
    </div>

    <script>
        function showTab(tabId) {
            // Ocultar todos los contenidos de las pestañas
            const tabContents = document.querySelectorAll('.tab-content');
            tabContents.forEach(content => {
                content.classList.remove('active');
            });

            // Desactivar todos los botones de las pestañas
            const tabButtons = document.querySelectorAll('.tab-button');
            tabButtons.forEach(button => {
                button.classList.remove('active');
            });

            // Mostrar el contenido de la pestaña seleccionada
            document.getElementById(tabId).classList.add('active');

            // Activar el botón de la pestaña seleccionada
            event.currentTarget.classList.add('active');
        }
    </script>
</body>
</html>
