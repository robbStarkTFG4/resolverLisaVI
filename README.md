<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>LISA PLATFORM</title>
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            background-color: #004d40; 
          
              background-image: url('fondo1.jpg');
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            color: #fff;
        }
        .container {
            background-color: rgba(255, 255, 255, 0.9);
            padding: 25px;
            border-radius: 10px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.15);
            max-width: 600px;
            width: 100%;
            max-height: 80vh;
            overflow-y: auto;
            animation: fadeIn 1s ease-in-out;
        }
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(-20px); }
            to { opacity: 1; transform: translateY(0); }
        }
        h2 {
            text-align: center;
            color: #333;
            font-size: 1.8em;
            margin-bottom: 15px;
            letter-spacing: 1px;
        }
        h3 {
            text-align: center;
            color: #555;
            font-size: 1.2em;
            margin-top: 10px;
        }
        ul {
            list-style-type: none;
            padding: 0;
        }
        li {
            margin: 15px 0;
            background-color: #f0f0f0;
            padding: 10px;
            border-radius: 8px;
            transition: background-color 0.3s;
        }
        li:hover {
            background-color: #e0f7fa;
        }
        a {
            text-decoration: none;
            color: #0288d1;
            font-weight: bold;
            font-size: 1em;
        }
        a:hover {
            color: #01579b;
            text-decoration: underline;
            transition: color 0.3s;
        }
        p {
            margin: 5px 0;
            color: #333;
            font-size: 0.95em;
        }

        /* Responsive adjustments */
        @media (max-width: 600px) {
            .container {
                padding: 15px;
                max-width: 100%;
            }
            h2 {
                font-size: 1.5em;
            }
            h3 {
                font-size: 1.2em;
            }
            p {
                font-size: 0.9em;
            }
        }
    </style>
</head>
<body>

    <div class="container">
        <h2>WEBAPP URL DIRECTORY</h2>
        <h3>Select the appropriate URL</h3>
        <ul>
            <li>
                <p><b>LISA DANANG</b></p>
                <a target="_blank" rel="noopener noreferrer" href="https://da-nang.fr-1.paas.massivegrid.net/dc3webApp4/faces/login.xhtml?faces-redirect=true">https://da-nang.fr-1.paas.massivegrid.net/dc3webApp4/faces/login.xhtml?faces-redirect=true</a>
            </li>
            <li>
                <p><b>PREQUALIFICATION</b></p>
                <a target="_blank" rel="noopener noreferrer" href="https://da-nang.fr-1.paas.massivegrid.net/precalification/">https://da-nang.fr-1.paas.massivegrid.net/precalification/</a>
            </li>
         
        </ul>
    </div>

</body>
</html>




