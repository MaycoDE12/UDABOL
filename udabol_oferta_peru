<!DOCTYPE html>
<html lang="es">

<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>UDABOL</title>
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" rel="stylesheet">
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">

  <style>
    /*diseño formulario */
    .form-section {
      background-color: #f5f5f5;
      padding: 20px;
      border-radius: 8px;
      max-width: 700px;
      margin: auto;
    }

    .form-group {
      margin-bottom: 10px;
    }

    .form-control {
      width: 100%;
      padding: 10px;
      border: 1px solid #ddd;
      border-radius: 4px;
    }

    .input-group {
      display: flex;
    }

    .input-group-text {
      background-color: #f5f5f5;
      border: 1px solid #ddd;
      padding: 10px;
      border-radius: 4px 0 0 4px;
    }

    .btn {
      background-color: #01402E;
      color: white;
      border: none;
      padding: 10px;
      border-radius: 4px;
      cursor: pointer;
    }

    .btn:hover {
      background-color: #04170c;
    }

    .form-text {
      font-size: 12px;
      color: #666;
    }

    .form-check {
      margin: 5px 0;
    }


    /*-----------------------------*/
    /*carrousel semniterminado*/
    .carousel {
      max-width: 800px;
      margin: 0 auto;
      position: relative;
    }

    .carousel-inner {
      display: flex;
      overflow: hidden;
      position: relative;
    }

    .carousel-item {
      display: none;
      width: 100%;
    }

    .carousel-item.active {
      display: block;
    }

    .testimonial {
      padding: 20px;
      border: 1px solid #ddd;
      border-radius: 10px;
      box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
    }

    .testimonial-content {
      display: flex; 
      align-items: center;
      justify-content: flex-start; 
    }

    .testimonial-image {
      flex: 1;
      max-width: 150px;
      padding-right: 10px;
    }

    .testimonial-image img {
      width: 100%;
      border-radius: 10px;
    }

    .testimonial-quote {
      flex: 3;
      font-size: 16px;
      line-height: 1.5;
      color: #333;
    }

    .testimonial-author {
      margin-top: 20px;
      text-align: center;
      font-size: 14px;
      color: #777;
    }

    .carousel-control {
      position: absolute;
      top: 50%;
      transform: translateY(-50%);
      background-color: rgba(0, 0, 0, 0.5);
      border: none;
      color: white;
      padding: 10px;
      cursor: pointer;
      font-size: 18px;
      border-radius: 20%;
      z-index: 1;
    }

    .prev {
      left: 5px;
    }

    .next {
      right: 5px;
    }

    /*------------------------------------------*/


    /* navbar */
    .navbar-left {
      display: flex;
      align-items: center;
    }
    .navbar-left .logo {
      margin-left: 40px;
      height: 50px;
      margin-right: 0px;
    }

    .uni-info {
      display: flex;
      flex-direction: column;
      margin-left: 10px;
    }

    .uni-name {
      font-size: 18px;
      font-weight: bold;
    }

    .uni-subtitle {
      font-size: 12px;
      color: gray;
    }

    /**/

    .buttons-container {
      display: flex;
      justify-content: space-around;
      background-color: #FFF;
      padding: 10px 0;
    }

    .btn {
      flex: 1;
      margin: 0 5px;
      padding: 10px;
      border-radius: 5px;
      color: #fff;
      font-size: 14px;
      text-decoration: none;
      display: flex;
      align-items: center;
      justify-content: center;
      font-weight: bold;
    }

    .btn-info {
      background-color: #F29F05;
      /* Color del botón de información */
    }

    .btn-call {
      background-color: #D9B91A;
      /* Color del botón de llamada */
    }

    .btn i {
      margin-right: 5px;
      /* Espacio entre el icono y el texto */
    }

    /* MENSAJE FINAL */
    .final-message {
      background-color: #f4f7fa;
      border-left: 5px solid #04402F;
      /* Línea decorativa a la izquierda */
      padding: 20px;
      border-radius: 8px;
      color: #333;
      font-family: Arial, sans-serif;
    }

    .final-message h2 {
      color: #04402F;
      margin-bottom: 10px;
      font-size: 22px;
    }

    .highlight {
      color: #F29F05;
      /* Color para resaltar la convocatoria */
      font-size: 16px;
      margin: 10px 0;
    }

    .note {
      margin-top: 15px;
      font-size: 13px;
      color: #666;
      border-top: 1px solid #d9b91a;
      padding-top: 10px;
    }

    /* NOTOCIA MINI SOMBRA */
    .info-box {
      display: flex;
      align-items: center;
      background-color: #f4f7fa;
      /* color de fondo similar al de la imagen */
      padding: 10px;
      border-radius: 5px;
      font-size: 14px;
      margin-right: 20px;
      margin-left: 20px;
      color: #333;
      border: 1px solid #e0e0e0;
      /* borde claro para darle un toque de caja */
    }

    .icon {
      margin-right: 8px;
      font-size: 16px;
    }

    .text {
      color: #333;
      /* Color del texto principal */
    }

    .text strong {
      font-weight: bold;
      /* Negrita para el texto destacado */
    }

    /*TITULACION*/
    .titulacion-oficial {
      background-color: #01402E;
      color: white;
      padding: 20px;
      border-radius: 5px;
    }

    .titulacion-oficial img {
      display: block;
      margin: 20px auto;
      max-width: 60%;
      height: auto;
    }

    .titulacion-oficial p {
      font-size: 14px;
    }

    /* NOTICIA DE CONTACTO */
    .contacto {
      background-color: #465954;
      color: white;
      padding: 20px;
      border-radius: 5px;
      max-width: auto;

    }

    .contacto-item {
      display: flex;
      align-items: center;
      margin-bottom: 10px;
    }

    .contacto-item i {
      font-size: 1.5em;
      margin-right: 10px;
      background-color: rgba(255, 255, 255, 0.2);
      /* Fondo de los íconos */
      border-radius: 50%;
      padding: 10px;
    }

    body {
      font-family: 'Roboto', sans-serif;
      padding-top: 70px;
    }

    .icon {
      font-family: 'Font Awesome 5 Free';
      font-weight: 900;
      font-size: 24px;
      color: #333;
    }

    .sponsors {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 20px;
      margin-top: 40px;
      margin-bottom: 40px;
    }

    .sponsor-img {

      width: auto;
      height: auto;
      filter: brightness(0) invert(1);
    }

    .custom-color {
      color: #01402E;
    }

    .hero {
      background-image: url('imagenes/banner.jpg');
      background-size: cover;
      background-position: center;
      color: white;
      text-align: left;
      padding: 120px 0px;
      position: relative;
      margin-bottom: 20px;
      margin-top: 0px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
    }

    .hero h1 {
      font-size: 2.5rem;
      font-weight: bold;
    }

    .hero p {
      font-size: 1.2rem;
    }

    .features {
      background-color: #f8f9fa;
      padding: 10px 20px;
      margin: 0 20px;
    }

    .features h3 {
      font-size: 1.2rem;
      text-align: center;
      margin-top: 10px;
    }

    .features .icon {
      font-size: 2rem;
      margin-bottom: 10px;
      transition: color 0.3s ease;
    }

    .features .icon:hover {
      color: #01402E;
    }

    .info-section {
      padding: 20px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
      border-radius: 8px;
      margin: 20px;
      background-color: #fff;
    }

    footer {
      background-color: #333;
      color: #fff;
      padding: 20px 0;
      text-align: center;
      width: 100%;
      margin-top: 40px;
    }

    .form-section {
      padding: 20px;
      border-radius: 12px;
      box-shadow: 0px 4px 20px rgba(0, 0, 0, 0.1);
      margin: 20px;
      background-color: #fff;
    }

    .form-section h3 {
      font-size: 1.5rem;
      margin-bottom: 20px;
    }

    .form-group label {
      font-weight: bold;
    }

    .navbar {
      background-color: #01402E;
      color: white;
      position: fixed;
      margin-button: 0px;
      top: 0;
      width: 100%;
      z-index: 1000;
      padding: 10px 20px;
    }

    .navbar a {
      color: white;
      margin-right: 10px;
      font-weight: bold;
    }

    .navbar-brand {
      display: flex;
      align-items: center;
    }

    .navbar-logo {
      width: 50px;
      height: auto;
      margin-right: 10px;
    }

    .expandable-section {
      border-radius: 8px;
      overflow: hidden;
      margin-bottom: 20px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    }

    .expandable-section .header {
      background-color: #01402E;
      color: white;
      padding: 10px;
      cursor: pointer;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    .expandable-section .header:hover {
      background-color: #012D24;
    }

    .expandable-section .content {
      display: none;
      padding: 10px;
      background-color: #f8f9fa;
    }

    .news-section {
      margin-top: 20px;
      border-top: 1px solid #dee2e6;
      padding-top: 10px;
    }

    .news-item {
      background-color: #f8f9fa;
      padding: 10px;
      border-radius: 4px;
      margin-bottom: 10px;
      box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    }

    .news-item:hover {
      background-color: #e9ecef;
    }

    .news-section .news-item:first-child {
      background-color: #01402E;
      color: #fff;
      font-weight: bold;
    }

    .news-item img {
      display: block;
      margin: 20px auto;
      max-width: 100%;
      height: auto;
    }

    @media (max-width: 768px) {
      .navbar-left .logo {
        margin-left: 0px;
        height: 50px;
        margin-right: 0px;
      }

      footer {
        
        margin-button: 180px;
      }

      .fixed-bottom {
        position: fixed;
        bottom: 0;
        left: 0;
        width: 100%;
        z-index: 9999;
        display: flex;
        justify-content: space-between;
        background-color: #01402E !important;

      }

      .btn {

        background: #01402E;
      }

      .btn-block {
        flex: 1;
        margin: 0;
      }

      .hero {
        padding: 20px 15px;
      }

      .hero h1 {
        font-size: 2rem;
      }

      .hero p {
        font-size: 1rem;
      }

      .features {
        background-color: #f8f9fa;
        padding: 10px 20px;
        margin: 0 20px;
        margin-right: 22px;
      }

      .features .row {
        display: flex;
        justify-content: space-around;
        flex-wrap: nowrap;
      }

      .features .col-md-4 {
        display: flex;
        flex-direction: column;
        align-items: center;
      }

      .features .icon {
        font-size: 1.5rem;
      }

      .features h3 {
        font-size: 1rem;
      }



      .sponsors {
        gap: 20px;
      }

      .sponsor-img {

        width: auto;
        height: auto;
      }

      .testimonial-content {
        flex-direction: column; 
        align-items: center;
        text-align: center;
      }

      .testimonial-image {
        max-width: 150px; 
        padding-right: 0; 
        margin-bottom: 15px; 
      }

      .testimonial-quote {
        font-size: 14px; 
        margin-top: 0; 
      }
    }
  </style>
</head>

<body>
  <!-- Mostrar solo en dispositivos móviles (revisar en el @media cualquier correccion añadida)-->
  <div class="d-flex d-md-none fixed-bottom buttons-container">
    <a href="#" class="btn btn-info text-center">
      <i class="fas fa-info-circle"></i> Más Informacion
    </a>
    <a href="tel:+59170074000" class="btn btn-call text-center">
      <i class="fas fa-phone-alt"></i> Llama Ahora
    </a>
  </div>

  <!-- Navbar Responsiva //corregido -->
  <nav class="navbar navbar-expand-md navbar-dark fixed-top">
   
      <!-- <a class="navbar-brand" href="#">
        <img src="imagenes/logo3.png" alt="Logo" class="navbar-logo">
        <span class="uni-name">UDABOL</span>-->
      <div class="navbar-left">
        <img src="imagenes/logo3.png" alt="Logo de UDABOL" class="logo">
        <div class="uni-info">
          <span class="uni-name">UDABOL</span>
          <span class="uni-subtitle">Universidad de Aquino Bolivia</span>
        </div>
      </div>

    
  </nav>

  <!-- Encabezado Hero -->
  <header class="hero">
    <div class="container">
      <h1>Promoción Exclusiva para estudiantes Peruanos</h1>
      <p>¡Estudia en la UDABOL y sé parte de la excelencia académica!l</p>
    </div>
  </header>

  <!-- Contenido Principal -->
  <div class="container-fluid">
    <div class="row">
      <div class="col-md-8">
        <section class="features text-center">
          <div class="row">
            <div class="col-md-4 col-sm-6 mb-4">
              <div class="icon custom-color">
                <i class="fas fa-hospital-alt"></i>
              </div>
              <h3>Moderno Hospital</h3>
            </div>
            <div class="col-md-4 col-sm-6 mb-4">
              <div class="icon custom-color">
                <i class="fas fa-user-md"></i> 
              </div>
              <h3>Mejores docentes</h3>
            </div>
            <div class="col-md-4 col-sm-12 mb-4">
              <div class="icon custom-color">
                <i class="fas fa-laptop-medical"></i> 
              </div>
              <h3>Tecnología de Punta</h3>
            </div>
          </div>
        </section>
        <!-- Sección de información -->
        <section class="info-section">
          <h2>Oferta exclusiva para estudiantes de Perú</h2>
          <p>Con el Plan Promoción Perú 2025, podrás acceder a descuentos de hasta el 50% en la matrícula de carreras de
            prestigio internacional como Medicina. Además, tendrás la ventaja de formarte en el hospital universitario
            más moderno de Bolivia, donde podrás aplicar tus conocimientos en un entorno real desde el inicio de tu
            carrera. ¡No pierdas esta oportunidad! Ingresa directamente sin examen de admisión y obtén un título
            reconocido en toda la región. Solicita más información e identifica tu procedencia peruana para acceder a
            estos beneficios exclusivos. ¡Estudia en la UDABOL y construye un futuro brillante!</p>
        </section>
        <!-- SECCION DE SOMBRA -->
        <div class="info-box">
          <span class="icon">🎓</span>
          <span class="text">
            <strong>Mas de 30 años de experiencia</strong> La UDABOL cuenta con una trayectoria consolidada en la
            educación superior boliviana. <strong>con un descuento exclusivo</strong>
          </span>
        </div>
        <!-- Sección Expandible -->
        <section class="info-section">
                    <div class="expandable-section">
                      <div class="header" onclick="toggleContent(this)">
                        <h4>Porque estudiar en la UDABOL</h4>
                        <i class="fas fa-plus"></i>
                      </div>
                      <div class="content">
                        <ul>
                          <li><strong>Formación Competitiva: </strong>La acreditación MERCOSUR garantiza una formación de alto nivel, preparando a los estudiantes para competir en el mercado laboral internacional. 💪</li>
                          <li><strong>Ingreso sin examen de admisión: </strong>La UDABOL ofrece un método de enseñanza que prepara a los estudiantes para los exámenes de conclusión de grado, facilitando el ingreso a universidades en diversos países. 🚪🔓</li>
                          <li><strong>Calidad Académica Certificada: </strong>La UDABOL cuenta con alianzas y redes internacionales, asegurando una educación de calidad y excelencia. 🎓🌟</li>
                          <li><strong>Amplia Oferta Educativa: </strong>Además de las carreras de salud, la UDABOL ofrece una variedad de programas académicos en diferentes áreas del conocimiento. 📚</li>
                          <li><strong>Comunidad Internacional: </strong>La UDABOL cuenta con una comunidad estudiantil diversa, brindando la oportunidad de interactuar con personas de diferentes culturas y nacionalidades. 🌎🤝</li>
                          <li><strong>Responsabilidad Social: </strong> La Fundación UDABOL desarrolla proyectos sociales en áreas como salud, educación y vivienda, permitiendo a los estudiantes participar en actividades de servicio a la comunidad. ❤️
          </li>
                          <li><strong>Infraestructura de primer nivel: </strong>La UDABOL cuenta con modernas instalaciones, incluyendo laboratorios equipados, biblioteca, centro de simulación y hospital universitario. 🔬🏥</li>
                          <li><strong>Accesibilidad financiera: </strong>La UDABOL ofrece planes de pago flexibles y becas para facilitar el acceso a la educación superior. 💰</li>
                          <li><strong>Convalidaciones sin costo: </strong>La UDABOL agiliza el proceso de inscripción para estudiantes con estudios previos, otorgando convalidaciones sin costo. ⏩</li>
                      </div>
                    </div>
          <div class="expandable-section">
            <div class="header" onclick="toggleContent(this)">
              <h4>Descubre Medicina</h4>
              <i class="fas fa-plus"></i>
            </div>
            <div class="content">
              <ul>
                <li>1er Semestre
                  <ul>
                    <li>Anatomía Humana I</li>
                    <li>Histología I</li>
                    <li>Embriología I</li>
                    <li>Soporte Básico de la Vida</li>
                    <li>Idioma I</li>
                  </ul>
                </li>
                <li>2do Semestre
                  <ul>
                    <li>Anatomía Humana II</li>
                    <li>Histología II</li>
                    <li>Embriología II</li>
                    <li>Interculturalidad</li>
                    <li>Metodología de la Investigación</li>
                  </ul>
                </li>
                <li>3er Semestre
                  <ul>
                    <li>Microbiología I - Bacteriología</li>
                    <li>Bioquímica y Biología Molecular I</li>
                    <li>Genética Médica</li>
                    <li>Fisiología I</li>
                    <li>Bioestadística y Demografía</li>
                    <li>Idioma II</li>
                  </ul>
                </li>
                <li>4to Semestre
                  <ul>
                    <li>Microbiología II - Micología y Virología</li>
                    <li>Bioquímica y Biología Molecular II</li>
                    <li>Fisiología II</li>
                    <li>Parasitología</li>
                    <li>Psicología Médica</li>
                  </ul>
                </li>
                <li>5to Semestre
                  <ul>
                    <li>Patología General</li>
                    <li>Semiología I</li>
                    <li>Farmacología y Terapéutica I</li>
                    <li>Fisiopatología</li>
                    <li>Responsabilidad Social Universitaria</li>
                  </ul>
                </li>
                <li>6to Semestre
                  <ul>
                    <li>Técnica Quirúrgica y Anestesiología</li>
                    <li>Patología Especial</li>
                    <li>Semiología II</li>
                    <li>Farmacología y Terapéutica II</li>
                    <li>Imagenología</li>
                    <li>Epidemiología</li>
                  </ul>
                </li>
                <li>7mo Semestre
                  <ul>
                    <li>Cirugía de Abdomen</li>
                    <li>Cirugía de Tórax</li>
                    <li>Cardiología</li>
                    <li>Neumología</li>
                    <li>Gastroenterología</li>
                    <li>Atención Primaria en Salud</li>
                  </ul>
                </li>
                <li>8vo Semestre
                  <ul>
                    <li>Cirugía de Cabeza y Cuello</li>
                    <li>Neurología y Neurocirugía</li>
                    <li>Psiquiatría</li>
                    <li>Reumatología</li>
                    <li>Traumatología y Ortopedia</li>
                    <li>Gerencia y Administración de Salud</li>
                  </ul>
                </li>
                <li>9no Semestre
                  <ul>
                    <li>Otorrinolaringología</li>
                    <li>Oftalmología</li>
                    <li>Urología</li>
                    <li>Nefrología</li>
                    <li>Hematología</li>
                    <li>Pediatría I</li>
                    <li>Ginecología y Obstetricia I</li>
                  </ul>
                </li>
                <li>10mo Semestre
                  <ul>
                    <li>Medicina Legal, Deontología y Ética Médica</li>
                    <li>Dermatología</li>
                    <li>Endocrinología</li>
                    <li>Infectología y Medicina Tropical</li>
                    <li>Pediatría II</li>
                    <li>Ginecología y Obstetricia II</li>
                  </ul>
                </li>
                <li>11avo Semestre
                  <ul>
                    <li>Clínica de Cirugía</li>
                    <li>Clínica de Pediatría</li>
                    <li>Clínica de Medicina Interna</li>
                    <li>Clínica de Obstetricia y Ginecología</li>
                    <li>Servicio Social de Salud Rural Obligatorio</li>
                  </ul>
                </li>
              </ul>
            </div>
          </div>


        </section>
        <section>
          <div class="info-box">
            <span class="icon">📖</span>
            <span class="text">
              <strong>Medicina sin examen de admisión: </strong> La UDABOL ofrece la posibilidad de ingresar a la
              carrera de Medicina sin necesidad de realizar un examen de admisión</strong>
            </span>
          </div>
        </section>

        <section class="info-section">
          <h2>La universidad líder en Bolivia</h2>
          <ul>
            <li><strong>Mas de 30 años de experiencia: </strong>La UDABOL cuenta con una trayectoria consolidada en la
              educación superior boliviana.</li>
            <li><strong>Amplia red nacional </strong> Presencia en las principales ciudades de Bolivia: La Paz, Santa
              Cruz, Cochabamba y Oruro.</li>
            <li><strong>Infraestructura moderna </strong> Instalaciones propias y equipadas con tecnología de
              vanguardia.</li>
            <li><strong>Hospital Universitario </strong> El hospital universitario más grande y moderno del país,
              brindando oportunidades de práctica clínica a los estudiantes de ciencias de la salud.</li>
            <li><strong>Medicina sin examen de admisión </strong> La UDABOL ofrece la posibilidad de ingresar a la
              carrera de Medicina sin necesidad de realizar un examen de admisión.</li>

          </ul>
        </section>
        <section>
          <div class="info-box">
            <span class="icon">🏥</span>
            <span class="text">
              <strong>Hospital Universitario: </strong>El hospital universitario más grande y moderno del país,
              brindando oportunidades de práctica clínica a los estudiantes de ciencias de la salud</strong>
            </span>
          </div>
        </section>
        <section class="info-section">
          <div class="expandable-section">
            <div class="header" onclick="toggleContent(this)">
              <h4>¡Estudia en la UDABOL y sé parte de la excelencia académica!</h4>
              <i class="fas fa-plus"></i>
            </div>
            <div class="content">
              <ul>
                <li><strong>Formación práctica en el hospital universitario más avanzado de Bolivia:</strong> En la UDABOL, podrás aplicar tus conocimientos teóricos en un entorno real, dentro del hospital universitario más moderno y equipado del país.</li>
                <li><strong>Clases teóricas y prácticas de primer nivel: </strong>Combina una sólida base teórica con prácticas en el mejor hospital de Bolivia, garantizando una formación completa y de excelencia.</li>
                <li><strong>Certificación Internacional: </strong>Las carreras de Medicina y Odontología están acreditadas por el MERCOSUR, garantizando una formación de calidad y reconocimiento en toda la región.
</li>
                <li><strong>Estudia en el mejor hospital de Bolivia con el Plan Medicos Perú 2025: </strong>Obtén descuentos de hasta el 50% en tu carrera y fórmate en un entorno de vanguardia.</li>  
              </ul>
            </div>
          </div>

        </section>
          <section>
            <div class="info-box">
              <span class="icon">🏢</span>
              <span class="text">
                <strong>Amplia red nacional </strong>Presencia en las principales ciudades de Bolivia: La Paz, Santa
                Cruz, Cochabamba y Oruro</strong>
              </span>
            </div>
          </section>
        <section class="info-section">
            <div id="testimonial-carousel" class="carousel">
              <div class="carousel-inner">
                <div class="carousel-item active">
                  <div class="testimonial">
                    <div class="testimonial-content">
                      <div class="testimonial-image">
                        <img src="imagenes/certificado_a.jpg" alt="Certificado_udabol">
                      </div>
                      <div class="testimonial-quote">
                        <blockquote>
                           "Certificado otorgado por la Universidad Aquino de Bolivia (UDABOL) como constancia de participación realizado en Bolivia."
                        </blockquote>
                      </div>
                    </div>
                    <p class="testimonial-author"><strong>Congreso nacional de Tecnologia</strong></p>
                  </div> 
                </div>
                <!-- certificados --> 
                <div class="carousel-item active">
                  <div class="testimonial">
                    <div class="testimonial-content">
                      <div class="testimonial-image">
                        <img src="imagenes/certificado_a.jpg" alt="Certificado_udabol">
                      </div>
                      <div class="testimonial-quote">
                        <blockquote>
                          "Certificado Lingua que acredita el nivel [Nivel alcanzado: A1, A2, B1, B2, C1 o C2] en el idioma INGLES. Otorgado por La Universidad Aquino de Bolivia (UDABOL)."
                        </blockquote>
                      </div>
                    </div>
                    <p class="testimonial-author"><strong>lengua extranjera LINGUA 2024</strong></p>
                  </div> 
                </div>
              </div>             
              <button class="carousel-control prev" onclick="prevSlide()">❮</button>
              <button class="carousel-control next" onclick="nextSlide()">❯</button>
            </div>
          </section>
      </div>


      <!-- Columna de Formulario -->
      <div class="col-md-4">
        <section class="form-section">
          <h3>Solicita información</h3>
          <form>
            <div class="form-group">
              <label for="tipoEstudios">Sede</label>
              <select class="form-control" id="tipoEstudios" required>
                <option value="" disabled selected>Selecciona una sede donde estudiar</option>
                <option value="1"> Santa Cruz </option>
                <option value="2"> La Paz </option>
                <option value="3"> Cochabamba </option>
                <option value="4"> Oruro </option>
                <option value="5"> No he decidido</option>
              </select>
              <small class="form-text">Selecciona un tipo de estudios</small>
            </div>
            <div class="form-group">
              <label for="tituloInteres">Carrera que te interesa:</label>
              <select class="form-control" id="tituloInteres" required>
                <option value="" disabled selected>Medicina</option>
                <option value="Administración de Empresas">Administración de Empresas</option>
                <option value="Arquitectura">Arquitectura</option>
                <option value="Auditoría">Auditoría</option>
                <option value="Bioquímica y Farmacia">Bioquímica y Farmacia</option>
                <option value="Comunicación">Comunicación</option>
                <option value="Derecho">Derecho</option>
                <option value="Diseño de Interiores">Diseño de Interiores</option>
                <option value="Enfermería">Enfermería</option>
                <option value="Fisioterapia y Kinesiología">Fisioterapia y Kinesiología</option>
                <option value="Ingeniería Agronómica">Ingeniería Agronómica</option>
                <option value="Ingeniería Ambiental">Ingeniería Ambiental</option>
                <option value="Ingeniería Comercial">Ingeniería Comercial</option>
                <option value="Ingeniería de Sistemas">Ingeniería de Sistemas</option>
                <option value="Ingeniería de Telecomunicaciones">Ingeniería de Telecomunicaciones</option>
                <option value="Ingeniería en Gas y Petróleo">Ingeniería en Gas y Petróleo</option>
                <option value="Marketing y Publicidad">Marketing y Publicidad</option>
                <option value="Odontología">Odontología</option>
                <option value="Psicología">Psicología</option>
                <option value="Relaciones Internacionales">Relaciones Internacionales</option>
                <option value="Turismo">Turismo</option>
                <option value="Veterinaria y Zootecnia">Veterinaria y Zootecnia</option>
              </select>
            </div>
            <div class="form-group">
              <label for="nombre">Nombre</label>
              <input type="text" class="form-control" id="nombre" placeholder="Escribe tu nombre" required>
              <small class="form-text">Escribe tu nombre</small>
            </div>
            <div class="form-group">
              <label for="apellidos">Apellidos</label>
              <input type="text" class="form-control" id="apellidos" placeholder="Escribe tus apellidos" required>
              <small class="form-text">Escribe tus apellidos</small>
            </div>
            <div class="form-group">
              <label for="email">Email</label>
              <input type="email" class="form-control" id="email" placeholder="Escribe un email válido" required>
              <small class="form-text">Escribe un email válido</small>
            </div>
            <div class="form-group">
              <label for="pais">País</label>
              <select class="form-control" id="pais" required>
                <option value="Peru" selected>Peru</option>  
              </select>
            </div>
            <div class="form-group">
              <label for="provincia">Provincia</label>
              <select class="form-control" id="provincia" required>
                <option value="" disabled selected>Provincias de peru</option>
                <option value="lima">Lima</option>
                <option value="Amazonas">Amazonas</option>
                <option value="Ancash">Áncash</option>
                <option value="Apurimac">Apurímac</option>
                <option value="Arequipa">Arequipa</option>
                <option value="Ayacucho">Ayacucho</option>
                <option value="Cajamarca">Cajamarca</option>
                <option value="Callao">Callao (provincia constitucional)</option>
                <option value="Cusco">Cusco</option>
                <option value="Huancavelica">Huancavelica</option>
                <option value="Huanuco">Huánuco</option>
                <option value="Ica">Ica</option>
                <option value="Junin">Junín</option>
                <option value="La Libertad">La Libertad</option>
                <option value="Lambayeque">Lambayeque</option>
                <option value="Lima">Lima</option>
                <option value="Loreto">Loreto</option>
                <option value="Madre de Dios">Madre de Dios</option>
                <option value="Moquegua">Moquegua</option>
                <option value="Pasco">Pasco</option>
                <option value="Piura">Piura</option>
                <option value="Puno">Puno</option>
                <option value="San Martin">San Martín</option>
                <option value="Tacna">Tacna</option>
                <option value="Tumbes">Tumbes</option>
                <option value="Ucayali">Ucayali</option>
              </select>
            </div>
            <div class="form-group">
              <label for="telefono">Teléfono</label>
              <div class="input-group">
                <span class="input-group-text">+51</span>
                <input type="tel" class="form-control" id="telefono" placeholder="900 000 000" required>
              </div>
            </div>
            <div class="form-group">
              <p>Quiero que también me contacten por <i class="fab fa-whatsapp"></i></p>
              <div class="form-check">
                <input class="form-check-input" type="radio" name="contactoWhatsApp" id="contactoSi" value="si"
                  required>
                <label class="form-check-label" for="contactoSi">Sí</label>
              </div>
              <div class="form-check">
                <input class="form-check-input" type="radio" name="contactoWhatsApp" id="contactoNo" value="no"
                  required>
                <label class="form-check-label" for="contactoNo">No</label>
              </div>
            </div>

            <button type="submit" class="btn btn-primary btn-block">SOLICITA INFORMACIÓN</button>
          </form>
        </section>


        <!-- Noticias -->
        <div class="titulacion-oficial">
          <h4 class="mb-3">Titulación oficial</h4>
          <p>
            Al finalizar tu carrera en la UDABOL, obtendrás un título oficial reconocido por el Ministerio de Educación
            de Bolivia, válido en todo el país y en el MERCOSUR.
          </p>
          <img src="imagenes/diploma.png" alt="titulo udabol">
          <p class="text-center">
            UDABOL. Universidad de Aquino Bolivia.
          </p>
        </div>

        <!--  IMAGENES DE NOTICIAS ; CONVENIOS ANUNCIOS -->
        </section>
        <h1>
        </h1>
        <div class="news-item">
          <img src="imagenes/logo_convenio.png" alt="convenios udabol">
        </div>
        
        <div class="news-section">
          <div class="contacto">
            <h4 class="mb-2">Contacta con nosotros sin compromiso</h4>
            <div class="contacto-item">
              <i class="fas fa-envelope"></i>
              <a href="mailto:internacional@udabol.edu.bo">internacional@udabol.edu.bo</a>

            </div>
            <div class="contacto-item">
              <i class="fas fa-phone"></i>
              <span>+591 77007767</span>
            </div>
            <div class="contacto-item">
              <i class="fas fa-user"></i>
              <span>¿TE LLAMAMOS?</span>
            </div>
          </div>

        </div>
      </div>

    </div>
  </div>
  </div>
  <div style="text-align: center; margin: 20px;">
    <h2>NOTICIAL UDABOL 🟢</h2>
    <div style="display: flex; flex-wrap: wrap; justify-content: center; gap: 20px; margin-top: 30px;">
      <div style="flex: 1; min-width: 300px; max-width: 400px;">
        <a href="https://www.youtube.com/watch?v=adCQlcHTzt4" target="_blank">
          <img src="imagenes/miniatura.png" alt="Vista previa del video udabol" style="width: 100%; height: auto;">
        </a>
        <p><strong>¡Estudiantes del Colegio Bolivia exploran la tecnología de última generación en nuestra
            universidad!</strong></p>
        <p>Recibimos a los estudiantes en nuestras aulas y laboratorios para vivir una experiencia tecnológica única.
          ¡Exploraron equipos avanzados y herramientas que los inspiraron a decidir su futuro académico!</p>
      </div>
      <div style="flex: 1; min-width: 300px; max-width: 400px;">
        <a href="https://www.youtube.com/watch?v=S8lDE0P_oNg" target="_blank">
          <img src="imagenes/miniatura1.png" alt="Vista previa del video udabol" style="width: 100%; height: auto;">
        </a>
        <p><strong>UDABOL: Calidad, innovación y tecnología, ¡te esperamos!</strong></p>
        <p>UDABOL es más que una universidad: prácticas reales, simuladores robóticos, Realidad aumentada, hospital
          digital de última generación</p>
      </div>
      <div style="flex: 1; min-width: 300px; max-width: 400px;">
        <a href="https://www.youtube.com/watch?v=4b6R5pGLTjA" target="_blank">
          <img src="imagenes/miniatura2.png" alt="Vista previa del video udabol" style="width: 100%; height: auto;">
        </a>
        <p><strong>Revoluciona la salud: únete a la próxima generación de expertos en farmacia e investigación</strong></p>
        <p>Estudia y desarrolla soluciones innovadoras para los desafíos globales en salud. Sé parte de una comunidad que transforma la investigación y la industria farmacéutica
</p>
      </div>
    </div>
  </div>

  <div style="text-align: center; margin: 20px;">
    <h2>Las 3 claves del exito</h2>
    <div style="display: flex; justify-content: space-around; margin-top: 30px;">
      <div>
        <h1 style="color: #D9AA1E;">1</h1>
        <p>la universidad Privada mas grande del Pais</p>
      </div>
      <div>
        <h1 style="color: #D9AA1E;">2</h1>
        <p>Te preparamos para el Futuro</p>
      </div>
      <div>
        <h1 style="color: #D9AA1E;">3</h1>
        <p>mas de 20.000 Estudiantes peruanos graduados</p>
      </div>
    </div>
  </div>

  <!-- ENcabeezado inferior -->
  <footer>
    <div class="container">
      <div class="sponsors">
        <img src="imagenes/footer.png" alt="Sponsor 1" class="sponsor-img img-fluid">
      </div>
      <p>&copy;UDABOL - Corporación de Aquino Bolivia 2024</p>
    </div>
  </footer>


  <script>
    /*controla el carrousel */
    let currentIndex = 0;

    function showSlide(index) {
      const items = document.querySelectorAll('.carousel-item');
      if (index >= items.length) currentIndex = 0;
      if (index < 0) currentIndex = items.length - 1;
      items.forEach((item, i) => {
        item.style.transform = `translateX(${(i - currentIndex) * 100}%)`;
      });
    }

    function nextSlide() {
      currentIndex++;
      showSlide(currentIndex);
    }

    function prevSlide() {
      currentIndex--;
      showSlide(currentIndex);
    }

    document.addEventListener('DOMContentLoaded', () => showSlide(currentIndex));

    /*maneja los abre y cierra (+)*/
    function toggleContent(header) {
      var content = header.nextElementSibling;
      var icon = header.querySelector('i');

      if (content.style.display === "none" || content.style.display === "") {
        content.style.display = "block";
        icon.classList.remove('fa-plus');
        icon.classList.add('fa-minus');
      } else {
        content.style.display = "none";
        icon.classList.remove('fa-minus');
        icon.classList.add('fa-plus');
      }
    }
  </script>
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.3/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>

</html>
