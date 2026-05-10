
<style>
  .section-label { font-size: 11px; font-weight: 500; text-transform: uppercase; letter-spacing: 0.08em; color: var(--color-text-tertiary); margin-bottom: 8px; }
  .skill-badge { display: inline-flex; align-items: center; gap: 5px; background: var(--color-background-secondary); border: 0.5px solid var(--color-border-tertiary); border-radius: var(--border-radius-md); padding: 4px 10px; font-size: 13px; color: var(--color-text-primary); }
  .wrap-group { display: flex; flex-wrap: wrap; gap: 6px; }
  .card { background: var(--color-background-primary); border: 0.5px solid var(--color-border-tertiary); border-radius: var(--border-radius-lg); padding: 1rem 1.25rem; }
  .divider { height: 0.5px; background: var(--color-border-tertiary); margin: 1rem 0; }
  tr td { padding: 6px 0; font-size: 14px; vertical-align: top; }
  td.label { color: var(--color-text-secondary); white-space: nowrap; padding-right: 16px; width: 120px; }
</style>

<div style="padding: 1rem 0; display: flex; flex-direction: column; gap: 12px;">

  <div class="card">
    <div style="display: flex; align-items: center; gap: 14px; margin-bottom: 14px;">
      <div style="width: 52px; height: 52px; border-radius: 50%; background: var(--color-background-info); display: flex; align-items: center; justify-content: center; font-weight: 500; font-size: 17px; color: var(--color-text-info);">JY</div>
      <div>
        <p style="font-size: 17px; font-weight: 500; margin: 0; color: var(--color-text-primary);">Jack Yactayo Huarcaya</p>
        <p style="font-size: 13px; color: var(--color-text-secondary); margin: 4px 0 0;">Bachiller en Ingeniería de Sistemas</p>
      </div>
    </div>
    <div class="divider"></div>
    <table style="width: 100%;">
      <tr>
        <td class="label"><i class="ti ti-map-pin" aria-hidden="true" style="font-size:15px; vertical-align:-2px; margin-right:5px;"></i>Ubicación</td>
        <td>Peru</td>
      </tr>
      <tr>
        <td class="label"><i class="ti ti-mail" aria-hidden="true" style="font-size:15px; vertical-align:-2px; margin-right:5px;"></i>Contacto</td>
        <td><a href="mailto:jack-0204@hotmail.com" style="color: var(--color-text-info);">jack-0204@hotmail.com</a></td>
      </tr>
      <tr>
        <td class="label"><i class="ti ti-brand-github" aria-hidden="true" style="font-size:15px; vertical-align:-2px; margin-right:5px;"></i>GitHub</td>
        <td><a href="https://github.com/JackYactayoHuarcaya" style="color: var(--color-text-info);">JackYactayoHuarcaya</a></td>
      </tr>
    </table>
  </div>

  <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(180px, 1fr)); gap: 12px;">

    <div class="card">
      <div class="section-label">Frontend</div>
      <div class="wrap-group">
        <span class="skill-badge">HTML5</span>
        <span class="skill-badge">CSS3</span>
        <span class="skill-badge">JavaScript</span>
        <span class="skill-badge">TypeScript</span>
        <span class="skill-badge">React</span>
        <span class="skill-badge">Next.js</span>
        <span class="skill-badge">Astro</span>
        <span class="skill-badge">TailwindCSS</span>
        <span class="skill-badge">Vite</span>
      </div>
    </div>

    <div class="card">
      <div class="section-label">Backend</div>
      <div class="wrap-group">
        <span class="skill-badge">Node.js</span>
        <span class="skill-badge">Express</span>
        <span class="skill-badge">NestJS</span>
        <span class="skill-badge">Java</span>
        <span class="skill-badge">Spring Boot</span>
      </div>
    </div>

    <div class="card">
      <div class="section-label">Bases de datos</div>
      <div class="wrap-group">
        <span class="skill-badge">MongoDB</span>
        <span class="skill-badge">MySQL</span>
      </div>
    </div>

    <div class="card">
      <div class="section-label">DevOps & Cloud</div>
      <div class="wrap-group">
        <span class="skill-badge">Docker</span>
        <span class="skill-badge">Kubernetes</span>
        <span class="skill-badge">Azure</span>
        <span class="skill-badge">Git</span>
      </div>
    </div>

    <div class="card">
      <div class="section-label">Herramientas</div>
      <div class="wrap-group">
        <span class="skill-badge">Figma</span>
        <span class="skill-badge">VS Code</span>
      </div>
    </div>

  </div>

</div>
