<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
</head>
<body>
  <h1>🐾 Sistema de Gestión de Pacientes Veterinarios con FilamentPHP</h1>

  <div class="section">
    <h2>📋 Descripción</h2>
    <p>
      Este proyecto es una aplicación de demostración construida con <strong>Laravel</strong> y <strong>FilamentPHP</strong>, diseñada para gestionar pacientes en una clínica veterinaria. Permite:
    </p>
    <ul>
      <li>Registrar pacientes (gatos, perros o conejos).</li>
      <li>Asignar propietarios a cada paciente.</li>
      <li>Registrar tratamientos administrados.</li>
      <li>Visualizar estadísticas y gráficos relacionados con los tratamientos.</li>
    </ul>
  </div>

  <div class="section">
    <h2>🚀 Características</h2>
    <ul>
      <li><strong>Panel de Administración:</strong> Interfaz intuitiva para gestionar pacientes, propietarios y tratamientos.</li>
      <li><strong>Widgets Personalizados:</strong>
        <ul>
          <li>Gráfico de tratamientos mensuales.</li>
        </ul>
      </li>
      <li><strong>Relaciones:</strong> Gestión de relaciones entre pacientes y tratamientos.</li>
      <li><strong>Validaciones:</strong> Formularios con validaciones para garantizar la integridad de los datos.</li>
    </ul>
  </div>

  <div class="section">
    <h2>🛠️ Tecnologías Utilizadas</h2>
    <ul>
      <li><a href="https://laravel.com/" target="_blank">Laravel 11.x</a></li>
      <li><a href="https://filamentphp.com/" target="_blank">FilamentPHP 3.x</a></li>
      <li><a href="https://laravel-livewire.com/" target="_blank">Livewire</a></li>
      <li><a href="https://tailwindcss.com/" target="_blank">Tailwind CSS</a></li>
      <li><a href="https://github.com/flowframe/laravel-trend" target="_blank">Trend (para gráficos)</a></li>
    </ul>
  </div>

  <div class="section">
    <h2>✅ Requisitos Previos</h2>
    <ul>
      <li>PHP >= 8.1</li>
      <li>Composer</li>
      <li>Node.js y NPM</li>
    </ul>
  </div>

  <div class="section">
    <h2>⚙️ Instalación</h2>
    <ol>
      <li><strong>Clona el repositorio:</strong>
        <pre><code>git clone https://github.com/lllThomasGlll/Laravel-Filament-Clinic.git</code></pre>
      </li>
      <li><strong>Instala las dependencias de PHP:</strong>
        <pre><code>composer install</code></pre>
      </li>
      <li><strong>Instala las dependencias de JavaScript:</strong>
        <pre><code>npm install</code></pre>
      </li>
      <li><strong>Ejecuta las migraciones:</strong>
        <pre><code>php artisan migrate</code></pre>
      </li>
      <li><strong>Inicia el servidor de desarrollo:</strong>
        <pre><code>php artisan serve</code></pre>
      </li>
      <li><strong>Accede a la aplicación en tu navegador:</strong>
        <pre><code>http://localhost:8000</code></pre>
      </li>
    </ol>
  </div>
</body>
</html>
