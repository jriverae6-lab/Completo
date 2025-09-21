<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Ingenio Tululá S.A.</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-100 text-gray-900">
  <!-- Header -->
  <header class="bg-green-800 text-white p-6 text-center">
    <h1 class="text-3xl font-bold">Ingenio Tululá S.A.</h1>
    <p class="mt-2">Comprometidos con la calidad, innovación y sostenibilidad</p>
  </header>

  <!-- Navegación -->
  <nav class="bg-green-700 text-white p-4 flex justify-center space-x-6">
    <a href="#empresa" class="hover:underline">Nuestra Empresa</a>
    <a href="#plazas" class="hover:underline">Plazas Disponibles</a>
  </nav>

  <!-- Información de la Empresa -->
  <section id="empresa" class="max-w-5xl mx-auto p-6 bg-white shadow-md rounded-xl mt-6">
    <h2 class="text-2xl font-bold text-green-800 mb-4">Sobre la Empresa</h2>
    <p><strong>Razón Social:</strong> Ingenio Tululá, S.A.</p>
    <p><strong>Ubicación:</strong> Km 4.5 carretera a San José la Máquina, San Andrés Villa Seca, Retalhuleu.</p>
    <p><strong>Industria:</strong> Manufactura y Producción</p>
    <p><strong>Fundación:</strong> 1904</p>
    <p><strong>Tamaño:</strong> Empresa Grande</p>

    <h3 class="text-xl font-semibold mt-4">Visión</h3>
    <p>Expandirnos ágilmente, creando los destilados de la más alta calidad, para el mundo que celebra.</p>

    <h3 class="text-xl font-semibold mt-4">Misión</h3>
    <p>En equipo, generamos experiencias memorables a nuestros clientes, consumidores y colaboradores; con la mayor rentabilidad para nuestra organización bajo los más altos estándares de ética y cumplimiento.</p>

    <h3 class="text-xl font-semibold mt-4">Valores</h3>
    <ul class="list-disc list-inside">
      <li>Sirven ágilmente: Superan las expectativas de los clientes internos y externos.</li>
      <li>Están comprometidos: ¡Cero excusas!</li>
      <li>Son innovadores: Innovan rentablemente en toda la organización.</li>
    </ul>

    <h3 class="text-xl font-semibold mt-4">Historia</h3>
    <p>Fundado en 1904 como fábrica panelera, Ingenio Tululá evolucionó con maquinaria importada desde Hawái y Luisiana para producir azúcar cruda, blanca y derivados. Desde el año 2000 produce energía eléctrica mediante cogeneración con biomasa (bagazo). Hoy es una corporación carbono neutral, mitigando su huella con más de 1,850,000 árboles resguardados y generando más de 72MM KWH de energía limpia.</p>

    <h3 class="text-xl font-semibold mt-4">Servicios</h3>
    <ul class="list-disc list-inside">
      <li>Producción de caña de azúcar (70% bebidas alcohólicas, 30% azúcar cruda).</li>
      <li>Producción de látex y chipa de segunda como materia prima.</li>
      <li>Capacitación agrícola en conjunto con INTECAP y CENGICAÑA.</li>
      <li>Comedor industrial para colaboradores.</li>
    </ul>
  </section>

  <!-- Plazas Disponibles -->
  <section id="plazas" class="max-w-6xl mx-auto p-6 mt-8">
    <h2 class="text-2xl font-bold text-green-800 mb-6">Plazas Disponibles</h2>

    <div class="grid md:grid-cols-2 gap-6">
      <!-- Dirección General -->
      <div class="bg-white shadow-md p-4 rounded-xl">
        <h3 class="text-xl font-semibold text-green-700">Director General</h3>
        <p class="mt-2"><strong>Requisitos Intelectuales:</strong> Formación universitaria en administración, economía o ingeniería industrial. Experiencia mínima de 10 años en puestos directivos. Habilidades de liderazgo, planeación estratégica y toma de decisiones.</p>
        <p class="mt-2"><strong>Responsabilidades:</strong> Define la estrategia organizacional, aprueba planes de producción y recursos, representa legal e institucionalmente a la empresa, toma decisiones de alto impacto.</p>
        <p class="mt-2"><strong>Condiciones de trabajo:</strong> Oficina ejecutiva, reuniones frecuentes, viajes de trabajo, alta presión por cumplimiento de metas y resultados financieros.</p>
        <p class="mt-2"><strong>Sueldo estimado:</strong> Q35,000 – Q50,000</p>
        <p><strong>Jornada:</strong> Lunes a Viernes 8:00 – 18:00</p>
        <form class="mt-3">
          <label class="block mb-1 text-sm">Subir CV:</label>
          <input type="file" class="border p-1 w-full rounded" />
          <button type="submit" class="mt-2 bg-green-700 text-white px-3 py-1 rounded hover:bg-green-800">Enviar</button>
        </form>
      </div>

      <!-- Gerente de Recursos Humanos -->
      <div class="bg-white shadow-md p-4 rounded-xl">
        <h3 class="text-xl font-semibold text-green-700">Gerente de Recursos Humanos</h3>
        <p class="mt-2"><strong>Requisitos Intelectuales:</strong> Licenciatura en Psicología, Administración de Empresas o afín. Experiencia mínima de 5 años en gestión de talento humano.</p>
        <p class="mt-2"><strong>Responsabilidades:</strong> Dirige la contratación, inducción, capacitación y clima laboral. Supervisa el cumplimiento de políticas laborales y de seguridad.</p>
        <p class="mt-2"><strong>Condiciones de trabajo:</strong> Oficina administrativa, interacción constante con todo el personal, alto nivel de comunicación interna.</p>
        <p class="mt-2"><strong>Sueldo estimado:</strong> Q18,000 – Q25,000</p>
        <p><strong>Jornada:</strong> Lunes a Viernes 8:00 – 18:00</p>
        <form class="mt-3">
          <label class="block mb-1 text-sm">Subir CV:</label>
          <input type="file" class="border p-1 w-full rounded" />
          <button type="submit" class="mt-2 bg-green-700 text-white px-3 py-1 rounded hover:bg-green-800">Enviar</button>
        </form>
      </div>

      <!-- Gerente de Informática -->
      <div class="bg-white shadow-md p-4 rounded-xl">
        <h3 class="text-xl font-semibold text-green-700">Gerente de Informática</h3>
        <p class="mt-2"><strong>Requisitos Intelectuales:</strong> Ingeniería en Sistemas o Informática. Experiencia mínima de 5 años en administración de tecnologías.</p>
        <p class="mt-2"><strong>Responsabilidades:</strong> Gestión de sistemas informáticos, seguridad digital y soporte a procesos administrativos y productivos.</p>
        <p class="mt-2"><strong>Condiciones de trabajo:</strong> Ambiente de oficina, ocasional atención en campo, presión por fallas críticas en sistemas.</p>
        <p class="mt-2"><strong>Sueldo estimado:</strong> Q18,000 – Q25,000</p>
        <p><strong>Jornada:</strong> Lunes a Viernes 8:00 – 18:00</p>
        <form class="mt-3">
          <label class="block mb-1 text-sm">Subir CV:</label>
          <input type="file" class="border p-1 w-full rounded" />
          <button type="submit" class="mt-2 bg-green-700 text-white px-3 py-1 rounded hover:bg-green-800">Enviar</button>
        </form>
      </div>

      <!-- Gerente de Fábrica -->
      <div class="bg-white shadow-md p-4 rounded-xl">
        <h3 class="text-xl font-semibold text-green-700">Gerente de Fábrica</h3>
        <p class="mt-2"><strong>Requisitos Intelectuales:</strong> Ingeniería Industrial, Mecánica o Química. Experiencia mínima de 7 años en procesos industriales.</p>
        <p class="mt-2"><strong>Responsabilidades:</strong> Supervisar producción de azúcar y derivados, garantizar calidad, eficiencia y seguridad industrial.</p>
        <p class="mt-2"><strong>Condiciones de trabajo:</strong> Planta industrial, exposición a ruido, calor y riesgos mecánicos.</p>
        <p class="mt-2"><strong>Sueldo estimado:</strong> Q18,000 – Q25,000</p>
        <p><strong>Jornada:</strong> Lunes a Viernes 8:00 – 18:00</p>
        <form class="mt-3">
          <label class="block mb-1 text-sm">Subir CV:</label>
          <input type="file" class="border p-1 w-full rounded" />
          <button type="submit" class="mt-2 bg-green-700 text-white px-3 py-1 rounded hover:bg-green-800">Enviar</button>
        </form>
      </div>

      <!-- Gerente de MTT -->
      <div class="bg-white shadow-md p-4 rounded-xl">
        <h3 class="text-xl font-semibold text-green-700">Gerente de MTT</h3>
        <p class="mt-2"><strong>Requisitos Intelectuales:</strong> Ingeniería Mecánica o afín. Experiencia mínima de 5 años en mantenimiento y gestión de flota.</p>
        <p class="mt-2"><strong>Responsabilidades:</strong> Planificación de mantenimiento preventivo y correctivo, disponibilidad de maquinaria y transporte.</p>
        <p class="mt-2"><strong>Condiciones de trabajo:</strong> Talleres y campo agrícola, exposición a riesgos mecánicos, coordinación en horarios extendidos en zafra.</p>
        <p class="mt-2"><strong>Sueldo estimado:</strong> Q18,000 – Q25,000</p>
        <p><strong>Jornada:</strong> Lunes a Viernes 8:00 – 18:00</p>
        <form class="mt-3">
          <label class="block mb-1 text-sm">Subir CV:</label>
          <input type="file" class="border p-1 w-full rounded" />
          <button type="submit" class="mt-2 bg-green-700 text-white px-3 py-1 rounded hover:bg-green-800">Enviar</button>
        </form>
      </div>

      <!-- Gerente Agrícola -->
      <div class="bg-white shadow-md p-4 rounded-xl">
        <h3 class="text-xl font-semibold text-green-700">Gerente Agrícola</h3>
        <p class="mt-2"><strong>Requisitos Intelectuales:</strong> Ingeniería Agronómica o afín. Experiencia mínima de 5 años en gestión agrícola.</p>
        <p class="mt-2"><strong>Responsabilidades:</strong> Planificación y supervisión de preparación de tierras, siembra, cultivo y cosecha.</p>
        <p class="mt-2"><strong>Condiciones de trabajo:</strong> Trabajo en campo, exposición a condiciones climáticas y variaciones estacionales.</p>
        <p class="mt-2"><strong>Sueldo estimado:</strong> Q18,000 – Q25,000</p>
        <p><strong>Jornada:</strong> Lunes a Viernes 8:00 – 18:00</p>
        <form class="mt-3">
          <label class="block mb-1 text-sm">Subir CV:</label>
          <input type="file" class="border p-1 w-full rounded" />
          <button type="submit" class="mt-2 bg-green-700 text-white px-3 py-1 rounded hover:bg-green-800">Enviar</button>
        </form>
      </div>

      <!-- Jefe de Departamento de RRHH -->
      <div class="bg-white shadow-md p-4 rounded-xl">
        <h3 class="text-xl font-semibold text-green-700">Jefe de Departamento de RRHH</h3>
        <p class="mt-2"><strong>Requisitos Intelectuales:</strong> Licenciatura en Psicología, Administración o afín. Experiencia en procesos de contratación y gestión administrativa.</p>
        <p class="mt-2"><strong>Responsabilidades:</strong> Coordinar inducción, capacitación y control de personal. Supervisar supervisores de área.</p>
        <p class="mt-2"><strong>Condiciones de trabajo:</strong> Oficina administrativa, interacción constante con supervisores y empleados.</p>
        <p class="mt-2"><strong>Sueldo estimado:</strong> Q12,000 – Q15,000</p>
        <p><strong>Jornada:</strong> Lunes a Viernes 8:00 – 17:00, Sábado 8:00 – 12:00</p>
        <form class="mt-3">
          <label class="block mb-1 text-sm">Subir CV:</label>
          <input type="file" class="border p-1 w-full rounded" />
          <button type="submit" class="mt-2 bg-green-700 text-white px-3 py-1 rounded hover:bg-green-800">Enviar</button>
        </form>
      </div>

      <!-- Jefe de Departamento de Informática -->
      <div class="bg-white shadow-md p-4 rounded-xl">
        <h3 class="text-xl font-semibold text-green-700">Jefe de Departamento de Informática</h3>
        <p class="mt-2"><strong>Requisitos Intelectuales:</strong> Ingeniería en Sistemas o Técnico Superior en Informática. Experiencia mínima de 3 años en soporte técnico.</p>
        <p class="mt-2"><strong>Responsabilidades:</strong> Planificación y control del soporte técnico, mantenimiento de redes y servidores.</p>
        <p class="mt-2"><strong>Condiciones de trabajo:</strong> Oficina y sala de servidores, posible trabajo en horarios extendidos ante emergencias.</p>
        <p class="mt-2"><strong>Sueldo estimado:</strong> Q12,000 – Q15,000</p>
        <p><strong>Jornada:</strong> Lunes a Viernes 8:00 – 17:00, Sábado 8:00 – 12:00</p>
        <form class="mt-3">
          <label class="block mb-1 text-sm">Subir CV:</label>
          <input type="file" class="border p-1 w-full rounded" />
          <button type="submit" class="mt-2 bg-green-700 text-white px-3 py-1 rounded hover:bg-green-800">Enviar</button>
        </form>
      </div>

      <!-- Jefe de Departamento de Fábrica -->
      <div class="bg-white shadow-md p-4 rounded-xl">
        <h3 class="text-xl font-semibold text-green-700">Jefe de Departamento de Fábrica</h3>
        <p class="mt-2"><strong>Requisitos Intelectuales:</strong> Ingeniería Industrial o Mecánica. Experiencia en procesos de producción.</p>
        <p class="mt-2"><strong>Responsabilidades:</strong> Coordinar procesos de producción, calidad y seguridad industrial.</p>
        <p class="mt-2"><strong>Condiciones de trabajo:</strong> Planta industrial, exposición a ruido y riesgos mecánicos.</p>
        <p class="mt-2"><strong>Sueldo estimado:</strong> Q12,000 – Q15,000</p>
        <p><strong>Jornada:</strong> Lunes a Viernes 8:00 – 17:00, Sábado 8:00 – 12:00</p>
        <form class="mt-3">
          <label class="block mb-1 text-sm">Subir CV:</label>
          <input type="file" class="border p-1 w-full rounded" />
          <button type="submit" class="mt-2 bg-green-700 text-white px-3 py-1 rounded hover:bg-green-800">Enviar</button>
        </form>
      </div>

      <!-- Jefe de Departamento de MTT -->
      <div class="bg-white shadow-md p-4 rounded-xl">
        <h3 class="text-xl font-semibold text-green-700">Jefe de Departamento de MTT</h3>
        <p class="mt-2"><strong>Requisitos Intelectuales:</strong> Ingeniería Mecánica o Técnico en mantenimiento. Experiencia mínima de 3 años.</p>
        <p class="mt-2"><strong>Responsabilidades:</strong> Supervisar mantenimiento preventivo y correctivo, coordinar transporte.</p>
        <p class="mt-2"><strong>Condiciones de trabajo:</strong> Talleres mecánicos y campo, horarios intensivos en zafra.</p>
        <p class="mt-2"><strong>Sueldo estimado:</strong> Q12,000 – Q15,000</p>
        <p><strong>Jornada:</strong> Lunes a Viernes 8:00 – 17:00, Sábado 8:00 – 12:00</p>
        <form class="mt-3">
          <label class="block mb-1 text-sm">Subir CV:</label>
          <input type="file" class="border p-1 w-full rounded" />
          <button type="submit" class="mt-2 bg-green-700 text-white px-3 py-1 rounded hover:bg-green-800">Enviar</button>
        </form>
      </div>

      <!-- Jefe de Departamento de Campo -->
      <div class="bg-white shadow-md p-4 rounded-xl">
        <h3 class="text-xl font-semibold text-green-700">Jefe de Departamento de Campo</h3>
        <p class="mt-2"><strong>Requisitos Intelectuales:</strong> Ingeniería Agronómica o Técnico agrícola. Experiencia de 3 años en labores agrícolas.</p>
        <p class="mt-2"><strong>Responsabilidades:</strong> Organizar y supervisar siembra, cultivo y cosecha.</p>
        <p class="mt-2"><strong>Condiciones de trabajo:</strong> Campo abierto, exposición a sol, lluvia y plagas.</p>
        <p class="mt-2"><strong>Sueldo estimado:</strong> Q12,000 – Q15,000</p>
        <p><strong>Jornada:</strong> Lunes a Viernes 8:00 – 17:00, Sábado 8:00 – 12:00</p>
        <form class="mt-3">
          <label class="block mb-1 text-sm">Subir CV:</label>
          <input type="file" class="border p-1 w-full rounded" />
          <button type="submit" class="mt-2 bg-green-700 text-white px-3 py-1 rounded hover:bg-green-800">Enviar</button>
        </form>
      </div>


      <!-- Supervisores de Área -->
      <div class="bg-white shadow-md p-4 rounded-xl">
        <h3 class="text-xl font-semibold text-green-700">Supervisor de Área de RRHH</h3>
        <p class="mt-2"><strong>Requisitos Intelectuales:</strong> Técnico en administración o estudiante universitario. Conocimientos en gestión de personal .</p>
        <p class="mt-2"><strong>Responsabilidades:</strong> Supervisar expedientes, planillas y asistencia.</p>
        <p class="mt-2"><strong>Condiciones de trabajo:</strong> Oficina administrativa, interacción constante con personal.</p>
        <p class="mt-2"><strong>Sueldo estimado:</strong> Q7,000 – Q10,000</p>
        <p><strong>Jornada:</strong> Lunes a Viernes 8:00 – 17:00, Sábado 8:00 – 12:00</p>
        <form class="mt-3">
          <label class="block mb-1 text-sm">Subir CV:</label>
          <input type="file" class="border p-1 w-full rounded" />
          <button type="submit" class="mt-2 bg-green-700 text-white px-3 py-1 rounded hover:bg-green-800">Enviar</button>
        </form>
      </div>

      <div class="bg-white shadow-md p-4 rounded-xl">
        <h3 class="text-xl font-semibold text-green-700">Supervisor de Área de Informática</h3>
        <p class="mt-2"><strong>Requisitos Intelectuales:</strong> Técnico en informática o estudiante universitario en sistemas.</p>
        <p class="mt-2"><strong>Responsabilidades:</strong> Supervisar soporte técnico y mantenimiento de equipos.</p>
        <p class="mt-2"><strong>Condiciones de trabajo:</strong> Ambiente de oficina, contacto con equipos electrónicos.</p>
        <p class="mt-2"><strong>Sueldo estimado:</strong> Q7,000 – Q10,000</p>
        <p><strong>Jornada:</strong> Lunes a Viernes 8:00 – 17:00, Sábado 8:00 – 12:00</p>
        <form class="mt-3">
          <label class="block mb-1 text-sm">Subir CV:</label>
          <input type="file" class="border p-1 w-full rounded" />
          <button type="submit" class="mt-2 bg-green-700 text-white px-3 py-1 rounded hover:bg-green-800">Enviar</button>
        </form>
      </div>

      <div class="bg-white shadow-md p-4 rounded-xl">
        <h3 class="text-xl font-semibold text-green-700">Supervisor de Área de Fábrica</h3>
        <p class="mt-2"><strong>Requisitos Intelectuales:</strong> Técnico industrial o mecánico. Experiencia en mantenimiento de maquinaria.</p>
        <p class="mt-2"><strong>Responsabilidades:</strong> Supervisar mecánicos y procesos de reparación.</p>
        <p class="mt-2"><strong>Condiciones de trabajo:</strong> Planta industrial, exposición a ruido, grasa y riesgos mecánicos.</p>
        <p class="mt-2"><strong>Sueldo estimado:</strong> Q7,000 – Q10,000</p>
        <p><strong>Jornada:</strong> Tiempo completo</p>
        <form class="mt-3">
          <label class="block mb-1 text-sm">Subir CV:</label>
          <input type="file" class="border p-1 w-full rounded" />
          <button type="submit" class="mt-2 bg-green-700 text-white px-3 py-1 rounded hover:bg-green-800">Enviar</button>
        </form>
      </div>

      <div class="bg-white shadow-md p-4 rounded-xl">
        <h3 class="text-xl font-semibold text-green-700">Supervisor de Área de MTT</h3>
        <p class="mt-2"><strong>Requisitos Intelectuales:</strong> Técnico mecánico. Conocimiento en reparaciones preventivas y correctivas.</p>
        <p class="mt-2"><strong>Responsabilidades:</strong> Coordina reparaciones y supervisa mecánicos .</p>
        <p class="mt-2"><strong>Condiciones de trabajo:</strong> Talleres mecánicos y campo agrícola.</p>
        <p class="mt-2"><strong>Sueldo estimado:</strong> Q7,000 – Q10,000</p>
        <p><strong>Jornada:</strong>  Variables según zafra. </p>
        <form class="mt-3">
          <label class="block mb-1 text-sm">Subir CV:</label>
          <input type="file" class="border p-1 w-full rounded" />
          <button type="submit" class="mt-2 bg-green-700 text-white px-3 py-1 rounded hover:bg-green-800">Enviar</button>
        </form>
      </div>

  <div class="bg-white shadow-md p-4 rounded-xl">
        <h3 class="text-xl font-semibold text-green-700">Supervisor de Área de Campo</h3>
        <p class="mt-2"><strong>Requisitos Intelectuales:</strong> Técnico agrícola o experiencia comprobable en labores agrícolas.</p>
        <p class="mt-2"><strong>Responsabilidades:</strong> Organizar cuadrillas, asignar tareas de siembra y cosecha .</p>
        <p class="mt-2"><strong>Condiciones de trabajo:</strong> Campo abierto, exposición a clima extremo.</p>
        <p class="mt-2"><strong>Sueldo estimado:</strong> Q7,000 – Q10,000</p>
        <p><strong>Jornada:</strong>  Variables según zafra. </p>
        <form class="mt-3">
          <label class="block mb-1 text-sm">Subir CV:</label>
          <input type="file" class="border p-1 w-full rounded" />
          <button type="submit" class="mt-2 bg-green-700 text-white px-3 py-1 rounded hover:bg-green-800">Enviar</button>
        </form>
      </div>


      <!-- Personal Operativo -->
      <div class="bg-white shadow-md p-4 rounded-xl">
        <h3 class="text-xl font-semibold text-green-700">Oficinista de RRHH</h3>
        <p class="mt-2"><strong>Requisitos Intelectuales:</strong> Bachillerato completo o estudios técnicos en administración.</p>
        <p class="mt-2"><strong>Responsabilidades:</strong> Gestión de expedientes, digitación de planillas y apoyo administrativo .</p>
        <p class="mt-2"><strong>Condiciones de trabajo:</strong> Oficina administrativa, manejo de equipo de cómputo.</p>
        <p class="mt-2"><strong>Sueldo estimado:</strong> Q4,000 – Q5,500</p>
        <p><strong>Jornada:</strong> Lunes a Viernes 8:00 – 17:00, Sábado 8:00 – 12:00</p>
        <form class="mt-3">
          <label class="block mb-1 text-sm">Subir CV:</label>
          <input type="file" class="border p-1 w-full rounded" />
          <button type="submit" class="mt-2 bg-green-700 text-white px-3 py-1 rounded hover:bg-green-800">Enviar</button>
        </form>
      </div>

      <div class="bg-white shadow-md p-4 rounded-xl">
        <h3 class="text-xl font-semibold text-green-700">Perito de Cómputo</h3>
        <p class="mt-2"><strong>Requisitos Intelectuales:</strong> Técnico en informática o estudiante universitario.</p>
        <p class="mt-2"><strong>Responsabilidades:</strong> Instalación de software, mantenimiento de equipos y redes .</p>
        <p class="mt-2"><strong>Condiciones de trabajo:</strong> Oficina y campo, contacto con usuarios y equipos electrónicos.</p>
        <p class="mt-2"><strong>Sueldo estimado:</strong> Q5,000 – Q6,000</p>
        <p><strong>Jornada:</strong>  Lunes a Viernes 8:00 – 17:00, Sábado 8:00 – 12:00</p>
        <form class="mt-3">
          <label class="block mb-1 text-sm">Subir CV:</label>
          <input type="file" class="border p-1 w-full rounded" />
          <button type="submit" class="mt-2 bg-green-700 text-white px-3 py-1 rounded hover:bg-green-800">Enviar</button>
        </form>
      </div>

      <div class="bg-white shadow-md p-4 rounded-xl">
        <h3 class="text-xl font-semibold text-green-700">Mecánico</h3>
        <p class="mt-2"><strong>Requisitos Intelectuales:</strong> Técnico en mecánica automotriz o industrial. Experiencia en mantenimiento de maquinaria.</p>
        <p class="mt-2"><strong>Responsabilidades:</strong> Reparación preventiva y correctiva de motores y equipos industriales .</p>
        <p class="mt-2"><strong>Condiciones de trabajo:</strong> Talleres y planta, exposición a grasa, calor y riesgos mecánicos.</p>
        <p class="mt-2"><strong>Sueldo estimado:</strong> Q4,500 – Q6,000</p>
        <p><strong>Jornada:</strong> Lunes a Viernes 8:00 – 17:00, Sábado 8:00 – 12:00</p>
        <form class="mt-3">
          <label class="block mb-1 text-sm">Subir CV:</label>
          <input type="file" class="border p-1 w-full rounded" />
          <button type="submit" class="mt-2 bg-green-700 text-white px-3 py-1 rounded hover:bg-green-800">Enviar</button>
        </form>
      </div>

      <div class="bg-white shadow-md p-4 rounded-xl">
        <h3 class="text-xl font-semibold text-green-700">Jornalero</h3>
        <p class="mt-2"><strong>Requisitos Intelectuales:</strong> Sin formación formal requerida, preferible experiencia en labores agrícolas.</p>
        <p class="mt-2"><strong>Responsabilidades:</strong> Preparación de tierra, siembra, cultivo y cosecha de caña de azúcar .</p>
        <p class="mt-2"><strong>Condiciones de trabajo:</strong> Campo abierto, exposición a sol, lluvia y esfuerzo físico. .</p>
        <p class="mt-2"><strong>Sueldo estimado:</strong> Q3,500 – Q4,500</p>
        <p><strong>Jornada:</strong> Completa o estacional según zafra</p>
        <form class="mt-3">
          <label class="block mb-1 text-sm">Subir CV:</label>
          <input type="file" class="border p-1 w-full rounded" />
          <button type="submit" class="mt-2 bg-green-700 text-white px-3 py-1 rounded hover:bg-green-800">Enviar</button>
        </form>
      </div>
