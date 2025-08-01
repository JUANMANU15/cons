# cons
constructora 
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Gamboc Construcciones</title>
  <link href="https://fonts.googleapis.com/css2?family=Rubik:wght@400;600&display=swap" rel="stylesheet">
  <style>
    :root {
      --primario: #000000;
      --secundario: #ffcc00;
      --claro: #fff8dc;
      --blanco: #ffffff;
      --gris: #f8f9fa;
    }
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: 'Rubik', sans-serif;
      background-color: var(--gris);
      color: var(--primario);
      line-height: 1.6;
    }
    header {
      background: linear-gradient(to right, var(--primario), #333);
      color: var(--secundario);
      padding: 1.5rem;
      text-align: center;
      position: sticky;
      top: 0;
      z-index: 1000;
    }
    header h1 {
      font-size: 2rem;
      margin-bottom: 0.5rem;
    }
    nav a {
      color: var(--secundario);
      margin: 0 1rem;
      text-decoration: none;
      font-weight: 600;
    }
    section {
      padding: 3rem 1.5rem;
      max-width: 1000px;
      margin: auto;
    }
    h2 {
      color: var(--primario);
      margin-bottom: 1rem;
      font-size: 1.8rem;
      border-left: 5px solid var(--secundario);
      padding-left: 1rem;
    }
    ul {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1rem;
      list-style: none;
      padding: 0;
    }
    li {
      background-color: var(--claro);
      padding: 1rem;
      border-left: 4px solid var(--secundario);
      border-radius: 8px;
      box-shadow: 0 2px 4px rgba(0,0,0,0.1);
    }
    .contacto p {
      margin: 0.5rem 0;
    }
    footer {
      background-color: var(--primario);
      color: var(--secundario);
      text-align: center;
      padding: 1rem;
    }
    .galeria {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 1rem;
    }
    .galeria img {
      width: 100%;
      border-radius: 8px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.2);
    }
  </style>
</head>
<body>
  <header>
    <h1>Gamboc Construcciones</h1>
    <nav>
      <a href="#quienes">¿Quiénes Somos?</a>
      <a href="#valores">Valores</a>
      <a href="#politicas">Políticas</a>
      <a href="#servicios">Servicios</a>
      <a href="#galeria">Galería</a>
      <a href="#contacto">Contacto</a>
    </nav>
  </header>

  <section id="quienes">
    <h2>¿Quiénes Somos?</h2>
    <p>Somos una empresa comprometida con la calidad de nuestros servicios, asegurando resultados efectivos en cada proyecto. En Gamboc Construcciones tenemos el propósito de “construir la historia” de cada uno de nuestros clientes a través del cuidado y mantenimiento de sus espacios.</p>
    <p>Con más de 20 años de experiencia como empresa familiar en el sector de la construcción, nos rigen principios sólidos y un fuerte compromiso con nuestro trabajo. Nuestro objetivo principal es brindar garantía y calidad a las necesidades de nuestros clientes.</p>
  </section>

  <section id="valores">
    <h2>Misión</h2>
    <p>Construir y remodelar espacios para que nuestros clientes tengan una alta calidad de vida, mejorando e innovando el lugar donde trabajan, descansan o se recrean, con técnicas vanguardistas sin perder las estructuras tradicionales, recuperando la historia de cada hogar.</p>

    <h2>Visión</h2>
    <p>Ser una empresa reconocida por su capacidad de crecimiento, así como la garantía, actualización y eficacia de sus servicios.</p>

    <h2>Valores</h2>
    <ul>
      <li>Compromiso</li>
      <li>Profesionalismo</li>
      <li>Honestidad</li>
      <li>Dedicación</li>
      <li>Trato justo</li>
      <li>Trabajo en equipo</li>
      <li>Puntualidad</li>
    </ul>

    <h2>Filosofía</h2>
    <p>La capacitación continua de nuestro equipo es fundamental.</p>
    <p>Fijar metas y cumplirlas es una acción que nos conduce al crecimiento.</p>
    <p>Mejorar entornos y espacios es una finalidad indiscutible.</p>
  </section>

  <section id="politicas">
    <h2>Políticas</h2>
    <p>Nuestras políticas se basan en brindar un servicio de calidad que cumpla con las expectativas del cliente, en un marco de respeto, cumplimiento normativo, mejora continua y seguridad para nuestros colaboradores.</p>
    <p>Nos aseguramos de:</p>
    <ul>
      <li>Cumplir con los tiempos establecidos en cada proyecto.</li>
      <li>Utilizar materiales de calidad y técnicas adecuadas.</li>
      <li>Ofrecer atención personalizada y seguimiento puntual.</li>
      <li>Proteger la integridad de nuestro personal y del cliente.</li>
      <li>Fomentar una cultura de trabajo ordenada, limpia y eficiente.</li>
    </ul>
  </section>

  <section id="servicios">
    <h2>Servicios</h2>
    <ul>
      <li>Remodelación e instalación eléctrica</li>
      <li>Drenaje y alimentación de agua</li>
      <li>Instalación de muros de tablaroca</li>
      <li>Pisos y azulejos</li>
      <li>Proyectos de mantenimiento menor</li>
      <li>Acabados de concreto y piedra</li>
      <li>Albañilería en general</li>
      <li>Electricidad y fontanería</li>
      <li>Plafones, enjarres y techos</li>
      <li>Instalación de lámparas</li>
      <li>Drenaje para inodoro y lavabo</li>
      <li>Colocación de estufa y campana</li>
      <li>Loza y banquetas de concreto</li>
    </ul>
  </section>

  <section id="galeria">
    <h2>Galería</h2>
    <div class="galeria">
      <img src="imagenes/imagen_1_1.jpeg" alt="Instalación de tablaroca">
      <img src="imagenes/imagen_1_3.png" alt="Acabado de muros">
      <img src="imagenes/imagen_2_5.jpeg" alt="Piso y azulejo en cocina">
      <img src="imagenes/imagen_3_3.jpeg" alt="Drenaje y fontanería">
      <img src="imagenes/imagen_4_1.jpeg" alt="Colocación de estufa eléctrica">
      <img src="imagenes/imagen_5_4.jpeg" alt="Loza de concreto con tubería de luz">
    </div>
  </section>


  <section id="contacto" class="contacto">
    <h2>Contacto</h2>
    <p><strong>Nombre:</strong> ING. ROBERTO GÁMEZ BOCANEGRA</p>
    <p><strong>WhatsApp:</strong> 473 320 0921</p>
    <p><strong>Facebook:</strong> Constructora Gamboc</p>
    <p><strong>Email:</strong> <a href="mailto:gamboconstrucciones@gmail.com">gamboconstrucciones@gmail.com</a></p>
    <p><strong>Dirección:</strong> Carretera a las momias, Guanajuato, Gto. México</p>
  </section>

  <footer>
    <p>&copy; 2025 Gamboc Construcciones. Todos los derechos reservados.</p>
  </footer>
</body>
</html>

