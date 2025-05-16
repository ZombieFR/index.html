<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Mapa Conceptual FOL</title>
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/markmap-toolbar@0.18.10/dist/style.css" />
<style>
  * { margin: 0; padding: 0; }
  #mindmap { width: 100vw; height: 100vh; display: block; }
</style>
</head>
<body>
<svg id="mindmap"></svg>
<script src="https://cdn.jsdelivr.net/npm/d3@7.9.0/dist/d3.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/markmap-view@0.18.10/dist/browser/index.js"></script>
<script src="https://cdn.jsdelivr.net/npm/markmap-toolbar@0.18.10/dist/index.js"></script>
<script>
(() => {
  setTimeout(() => {
    const { markmap: Markmap, mm } = window;
    const toolbar = new Markmap.Toolbar();
    toolbar.attach(mm);
    const toolbarEl = toolbar.render();
    toolbarEl.style.position = 'absolute';
    toolbarEl.style.bottom = '20px';
    toolbarEl.style.right = '20px';
    document.body.appendChild(toolbarEl);
  });
})();
(() => {
  const content = `Temas 9, 10 y 11 - FOL 📘
- Tema 9: Planificación de la carrera profesional 🎯
  - 9.1 Hoja de ruta 🛣️
    - Saber hacia dónde voy
    - Elegir formación y experiencia que me sirvan
  - 9.2 Planificación de la carrera
    - Metas personales y profesionales
    - Tener en cuenta:
      - Formación profesional
      - Experiencia laboral
      - Lo que pide el mercado
  - 9.3 Perfil profesional 👤
    - Qué sé hacer (formación + experiencia)
    - Cómo soy (habilidades + actitud)
    - Qué me interesa (motivación + gustos)
  - 9.4 Autoconocimiento y autoestima 💪
    - Conocerse a uno mismo
    - Confiar en lo que sé hacer
    - Afrontar retos con ganas
  - 9.5 Currículum Vitae (CV) 📄
    - Datos personales
    - Formación
    - Experiencia
    - Habilidades
    - Clave: claro, actualizado y bonito
  - 9.6 Carta de presentación ✉️
    - Me presento a la empresa
    - Explico por qué quiero el puesto
    - Digo lo mejor de mí
- Tema 10: Empleabilidad y oportunidades de empleo 💼
  - 10.1 Empleabilidad
    - Capacidad de encontrar y mantener empleo
    - Claves:
      - Formación continua
      - Aprender siempre (upskilling, reskilling)
  - 10.2 Mercado laboral 🌍
    - Oferta: personas que buscan trabajo
    - Demanda: empresas que necesitan contratar
    - Puede ser por zona o por sector
  - 10.3 Proceso de selección 🧪
    - Objetivo empresa: encontrar a la persona ideal
    - Objetivo candidato: demostrar que valgo
    - Herramientas:
      - Test
      - Dinámicas de grupo
      - Entrevistas
  - 10.4 Tipos de trabajo
    - Por cuenta ajena 👨‍💼 (para una empresa)
    - Por cuenta propia 👩‍💻 (emprender, ser tu jefe)
    - En la Administración Pública 🏛️ (funcionario)
  - 10.5 Sectores profesionales 🛠️
    - Conjunto de trabajos similares
    - Ej: Sanidad, Informática, Comercio, etc.
- Tema 11: Aprendizaje autónomo e identidad digital 🌐
  - 11.1 Formación permanente 📚
    - Aprender toda la vida
    - Mejora la empleabilidad
    - Ayuda a crecer como persona
  - 11.2 Itinerarios de formación
    - Después del ciclo puedo seguir:
      - FP Superior
      - Universidad
      - Cursos, certificados...
  - 11.3 Competencias digitales 💻
    - Saber usar tecnología en el trabajo
    - Ejemplos:
      - Redes sociales
      - Apps
      - Seguridad online
  - 11.4 Identidad digital 👨‍💻
    - Imagen que das en internet
    - Influye en la búsqueda de empleo
    - Cuidar lo que compartes
  - 11.5 Huella digital 🔍
    - Activa: lo que publicas tú
    - Pasiva: lo que se guarda sin saberlo
    - Afecta a tu reputación
  - 11.6 Networking 🤝
    - Hacer contactos profesionales
    - Usar LinkedIn, eventos, redes
`;
  window.mm = Markmap.create('#mindmap', null, content);
})();
</script>
</body>
</html>
