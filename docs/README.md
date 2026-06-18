Aquí van los documentos del proyecto
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Trazabilidad - Deshidratador Solar</title>
    <style>
        /* Estilos básicos para una presentación limpia */
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            background: #f8f9fa;
            color: #212529;
            line-height: 1.6;
        }
        .container {
            max-width: 1100px;
            margin: 0 auto;
            padding: 20px;
        }
        header {
            background: #2c3e50;
            color: white;
            padding: 20px 0;
            text-align: center;
            border-radius: 0 0 10px 10px;
        }
        header h1 {
            margin: 0;
            font-size: 2.5rem;
        }
        header p {
            font-size: 1.2rem;
            margin: 5px 0 0;
            opacity: 0.9;
        }
        h2 {
            border-bottom: 3px solid #2c3e50;
            padding-bottom: 10px;
            margin-top: 40px;
        }
        .card {
            background: white;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            padding: 20px;
            margin: 20px 0;
        }
        .gallery {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
        }
        .gallery img {
            max-width: 300px;
            height: auto;
            border-radius: 8px;
            box-shadow: 0 2px 8px rgba(0,0,0,0.15);
            transition: transform 0.2s;
        }
        .gallery img:hover {
            transform: scale(1.02);
        }
        .file-list {
            list-style: none;
            padding: 0;
        }
        .file-list li {
            background: #e9ecef;
            margin: 8px 0;
            padding: 10px 15px;
            border-radius: 5px;
            display: flex;
            align-items: center;
            gap: 10px;
        }
        .file-list li a {
            text-decoration: none;
            color: #2c3e50;
            font-weight: 500;
        }
        .file-list li a:hover {
            text-decoration: underline;
        }
        footer {
            text-align: center;
            margin-top: 50px;
            padding: 20px;
            border-top: 1px solid #dee2e6;
            color: #6c757d;
        }
        .badge {
            display: inline-block;
            background: #2c3e50;
            color: white;
            padding: 5px 12px;
            border-radius: 20px;
            font-size: 0.8rem;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>🌞 Proyecto de Trazabilidad</h1>
            <p>Deshidratador Solar - Residencias Profesionales</p>
        </div>
    </header>

    <div class="container">
        <!-- Descripción del proyecto -->
        <section>
            <h2>📖 Descripción</h2>
            <div class="card">
                <p>
                    Este proyecto documenta el desarrollo y la operación de un <strong>deshidratador solar</strong> 
                    utilizado para el secado de productos agrícolas. Aquí encontrarás toda la información técnica, 
                    manuales, imágenes y resultados obtenidos durante el período de residencia.
                </p>
                <p>
                    <span class="badge">Última actualización: Junio 2026</span>
                </p>
                <p>
                    <strong>Colaboradores:</strong> Si deseas agregar o modificar contenido, consulta la sección 
                    <a href="#colaborar">¿Cómo colaborar?</a> al final de esta página.
                </p>
            </div>
        </section>

        <!-- Documentos -->
        <section>
            <h2>📄 Documentos</h2>
            <div class="card">
                <ul class="file-list">
                    <!-- Agrega aquí tus archivos PDF, Word, Excel, etc. -->
                    <li>📎 <a href="docs/manual.pdf" target="_blank">Manual de operación del deshidratador</a></li>
                    <li>📎 <a href="docs/informe.docx" target="_blank">Informe final de residencia</a></li>
                    <li>📎 <a href="docs/diagramas.pdf" target="_blank">Diagramas y planos</a></li>
                    <!-- Puedes agregar más enlaces según tus archivos -->
                </ul>
                <p><em>Los documentos se encuentran en la carpeta <code>docs/</code> del repositorio.</em></p>
            </div>
        </section>

        <!-- Imágenes -->
        <section>
            <h2>🖼️ Galería de imágenes</h2>
            <div class="card">
                <div class="gallery">
                    <!-- Coloca aquí tus imágenes. Ajusta los nombres de archivo -->
                    <img src="images/deshidratador1.jpg" alt="Vista frontal del deshidratador">
                    <img src="images/deshidratador2.png" alt="Interior del deshidratador">
                    <img src="images/diagrama.jpg" alt="Diagrama de flujo del proceso">
                    <!-- Agrega más imágenes según necesites -->
                </div>
                <p style="margin-top:15px; text-align:center;">
                    <em>Las imágenes se encuentran en la carpeta <code>images/</code>.</em>
                </p>
            </div>
        </section>

        <!-- Sección de colaboración -->
        <section id="colaborar">
            <h2>🤝 ¿Cómo colaborar?</h2>
            <div class="card">
                <p>Este repositorio está abierto para que futuros estudiantes (o cualquier interesado) puedan:</p>
                <ul>
                    <li><strong>Agregar nuevos documentos</strong> (informes, manuales, etc.) en la carpeta <code>docs/</code>.</li>
                    <li><strong>Subir imágenes</strong> adicionales a la carpeta <code>images/</code>.</li>
                    <li><strong>Modificar o mejorar</strong> esta página web editando el archivo <code>index.html</code>.</li>
                    <li><strong>Actualizar el README</strong> para reflejar nuevos avances.</li>
                </ul>
                <h4>Flujo de trabajo recomendado:</h4>
                <ol>
                    <li><strong>Fork</strong> el repositorio (si no tienes permisos de escritura directos).</li>
                    <li>Clona tu fork o la rama principal en tu computadora.</li>
                    <li>Crea una rama nueva para tus cambios: <code>git checkout -b mi-mejora</code>.</li>
                    <li>Realiza tus modificaciones (agrega archivos, edita HTML, etc.).</li>
                    <li>Haz commit y push a tu rama.</li>
                    <li>Abre un <strong>Pull Request</strong> para que los cambios sean revisados y fusionados.</li>
                </ol>
                <p>
                    Si eres colaborador directo del repositorio (con permisos de escritura), puedes hacer 
                    <code>git push</code> directamente a la rama <code>main</code> (siempre y cuando coordines con el equipo).
                </p>
                <p>
                    <strong>Recuerda:</strong> Mantén siempre actualizada la página <code>index.html</code> para que refleje 
                    los nuevos archivos agregados (actualiza los enlaces y las imágenes).
                </p>
            </div>
        </section>
    </div>

    <footer>
        <div class="container">
            <p>Proyecto de Residencias - Trazabilidad del Deshidratador Solar</p>
            <p>Licencia MIT · <a href="https://github.com/tu-usuario/trazabilidad-deshidratador" target="_blank">Ver repositorio</a></p>
        </div>
    </footer>
</body>
</html>
