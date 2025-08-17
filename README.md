<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>L2 Por Siempre — Hi5 (Etapas 1–6)</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-950 text-white font-sans">
  <!-- Header -->
  <header class="text-center py-10 bg-gradient-to-r from-purple-900 to-indigo-900 shadow-xl">
    <h1 class="text-4xl font-bold">⚔️ Lineage II Por Siempre</h1>
    <p class="mt-2 text-gray-300">Servidor Hi5 — Progresivo, competitivo y justo</p>
  </header>

  <!-- Etapa 1 -->
  <section class="p-10">
    <h2 class="text-3xl font-bold text-center mb-6">📈 Rates del Servidor (Etapa 1)</h2>
    <div class="grid md:grid-cols-3 gap-6 text-center max-w-6xl mx-auto">
      <div class="bg-gray-800 p-6 rounded-xl shadow-md">
        <h3 class="text-2xl font-bold text-yellow-400">EXP / SP</h3>
        <p class="mt-1">x10 – x30 progresivo</p>
        <p class="text-sm text-gray-400 mt-2">Del 60+ sube la dificultad de leveo</p>
      </div>
      <div class="bg-gray-800 p-6 rounded-xl shadow-md">
        <h3 class="text-2xl font-bold text-green-400">Drop (materiales/recetas)</h3>
        <p class="mt-1">Balance retail con ligera mejora</p>
        <p class="text-sm text-gray-400 mt-2">Camino principal: crafteo en party</p>
      </div>
      <div class="bg-gray-800 p-6 rounded-xl shadow-md">
        <h3 class="text-2xl font-bold text-blue-400">Adena</h3>
        <p class="mt-1">x10 ajustado a economía viva</p>
        <p class="text-sm text-gray-400 mt-2">Evita inflación, incentiva trade</p>
      </div>
    </div>
    <div class="max-w-4xl mx-auto mt-6 text-center text-gray-300">
      <p>Razas nacen en su <span class="text-yellow-400">village</span> original. Primera clase <span class="text-yellow-400">gratis</span> al nivel 20.</p>
    </div>
  </section>

  <!-- Etapa 2 -->
  <section class="p-10 bg-gray-900 rounded-2xl shadow-xl max-w-6xl mx-auto">
    <h2 class="text-3xl font-bold text-center mb-6">🧙 Buffs & Support (Etapa 2)</h2>
    <ul class="space-y-3 text-lg text-gray-300 max-w-3xl mx-auto">
      <li>✨ Buffs de NPC hasta lvl 40 → <span class="text-yellow-400">30 minutos</span></li>
      <li>⚔️ Buffs de supports reales → <span class="text-green-400">2 horas</span></li>
      <li>🚫 Sin NPC buffer global → fomenta party y mercado de buffs (players pueden vender)</li>
    </ul>
  </section>

  <!-- Etapa 3 -->
  <section class="p-10">
    <h2 class="text-3xl font-bold text-center mb-6">🔨 Craft & Equipo (Etapa 3)</h2>
    <div class="max-w-4xl mx-auto text-center text-lg text-gray-300">
      <p>El equipo desde <span class="text-yellow-400">grado B+</span> se obtiene <span class="text-yellow-400">solo por crafteo</span>. Los drops top (B/A/S/S80/S84) existen pero son <span class="text-purple-300">ultra raros</span> (milagro controlado).</p>
    </div>
  </section>

  <!-- Etapa 4 -->
  <section id="reborn" class="p-10 bg-gray-900 text-white rounded-2xl shadow-xl mt-6 max-w-6xl mx-auto">
    <h2 class="text-3xl font-bold text-center mb-6">⚔️ Sistema de Renacer (Etapa 4)</h2>
    <p class="text-lg mb-6 text-center text-gray-300 max-w-3xl mx-auto">
      Al llegar al nivel máximo, puedes <span class="text-yellow-400 font-semibold">renacer</span> en la iglesia de tu raza (vuelves a nivel 1). Cada RB añade <span class="text-yellow-400">+3% permanente</span> a tus estadísticas base (STR, DEX, CON, INT, WIT, MEN) y desbloquea pasivas por rol.
    </p>

    <div class="grid md:grid-cols-3 gap-6 text-center">
      <div class="bg-gray-800 p-6 rounded-xl shadow-md">
        <h3 class="text-2xl font-bold text-yellow-400">🏅 5 Reborns</h3>
        <p class="mt-2">Título: <span class="italic">Veterano</span></p>
      </div>
      <div class="bg-gray-800 p-6 rounded-xl shadow-md">
        <h3 class="text-2xl font-bold text-red-400">⚔️ 10 Reborns</h3>
        <p class="mt-2">Título: <span class="italic">Guerrero Supremo</span></p>
      </div>
      <div class="bg-gray-800 p-6 rounded-xl shadow-md">
        <h3 class="text-2xl font-bold text-purple-400">🔥 20+ Reborns</h3>
        <p class="mt-2">Título: <span class="italic">Legendario</span> con aura visual</p>
      </div>
    </div>
  </section>

  <!-- Etapa 5 -->
  <section class="p-10 max-w-6xl mx-auto">
    <h2 class="text-3xl font-bold text-center mb-6">🩸 Karma & PvP + Respawn de Raids (Etapa 5)</h2>

    <!-- Karma Simulator -->
    <div class="grid md:grid-cols-2 gap-6">
      <div class="bg-gray-900 rounded-2xl shadow-xl p-6">
        <h3 class="text-xl font-bold mb-3">Simulador de Karma</h3>
        <div class="grid grid-cols-2 gap-4 text-gray-300">
          <label class="flex flex-col">Nivel jugador
            <input id="pLevel" type="number" value="60" class="mt-1 bg-gray-800 rounded px-3 py-2" />
          </label>
          <label class="flex flex-col">Nivel enemigo
            <input id="eLevel" type="number" value="55" class="mt-1 bg-gray-800 rounded px-3 py-2" />
          </label>
        </div>
        <div class="mt-4 flex gap-3">
          <button id="btnPK" class="bg-red-600 hover:bg-red-700 px-4 py-2 rounded">Matar Enemigo</button>
          <button id="btnMob" class="bg-blue-600 hover:bg-blue-700 px-4 py-2 rounded">Matar Mob</button>
          <button id="btnReset" class="bg-gray-700 hover:bg-gray-600 px-4 py-2 rounded">Reset</button>
        </div>
        <div class="mt-4 text-sm text-gray-300">
          <p>Karma: <span id="karmaVal" class="font-bold">0</span> — Estado: <span id="stateVal" class="font-bold">Normal</span></p>
          <p id="karmaMsg" class="mt-2 text-yellow-300"></p>
          <p id="guardMsg" class="text-orange-300"></p>
        </div>
      </div>

      <!-- Raid countdown demo -->
      <div class="bg-gray-900 rounded-2xl shadow-xl p-6">
        <h3 class="text-xl font-bold mb-3">Countdown de Raids (Demo)</h3>
        <p class="text-sm text-gray-400 mb-3">Reemplaza las fechas por las reales del servidor (formato <code>YYYY-MM-DDTHH:MM:SS</code>).</p>
        <div id="raidList" class="space-y-3">
          <div class="flex items-center justify-between bg-gray-800 rounded-xl px-4 py-3" data-name="Zaken" data-next="2025-08-20T20:00:00">
            <strong>Zaken</strong><span class="timer text-gray-300">—</span>
          </div>
          <div class="flex items-center justify-between bg-gray-800 rounded-xl px-4 py-3" data-name="Baium" data-next="2025-08-22T18:30:00">
            <strong>Baium</strong><span class="timer text-gray-300">—</span>
          </div>
          <div class="flex items-center justify-between bg-gray-800 rounded-xl px-4 py-3" data-name="Antharas" data-next="2025-08-25T21:00:00">
            <strong>Antharas</strong><span class="timer text-gray-300">—</span>
          </div>
          <div class="flex items-center justify-between bg-gray-800 rounded-xl px-4 py-3" data-name="Valakas" data-next="2025-08-28T22:00:00">
            <strong>Valakas</strong><span class="timer text-gray-300">—</span>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Etapa 6 -->
  <section class="p-10 bg-gray-900 rounded-2xl shadow-xl max-w-6xl mx-auto mb-10">
    <h2 class="text-3xl font-bold text-center mb-6">🐉 Acceso a Raids (Etapa 6)</h2>
    <p class="text-center text-gray-300 mb-4">Regla: ningún jugador puede entrar si está a más de <span class="text-yellow-400">12 niveles por debajo</span> del raid.</p>
    <div class="max-w-xl mx-auto grid md:grid-cols-3 gap-4 items-end">
      <label class="flex flex-col">Nivel del Raid
        <input id="raidLvl" type="number" value="60" class="mt-1 bg-gray-800 rounded px-3 py-2" />
      </label>
      <label class="flex flex-col">Tu nivel
        <input id="playerRaidLvl" type="number" value="50" class="mt-1 bg-gray-800 rounded px-3 py-2" />
      </label>
      <button id="btnCheckRaid" class="bg-emerald-600 hover:bg-emerald-700 px-4 py-2 rounded">Comprobar acceso</button>
    </div>
    <p id="raidAccessMsg" class="text-center mt-4 text-lg"></p>
  </section>

  <!-- Footer -->
  <footer class="text-center py-6 text-gray-400">
    © 2025 Lineage II Por Siempre | Comunidad Hi5 — Demo Etapas 1–6
  </footer>

  <script>
    // --- Etapa 5: Karma Simulator ---
    let karma = 0, mobs = 0, flagTimer = null;
    const pLevelEl = document.getElementById('pLevel');
    const eLevelEl = document.getElementById('eLevel');
    const karmaVal = document.getElementById('karmaVal');
    const stateVal = document.getElementById('stateVal');
    const karmaMsg = document.getElementById('karmaMsg');
    const guardMsg = document.getElementById('guardMsg');

    document.getElementById('btnPK').addEventListener('click', () => {
      const p = parseInt(pLevelEl.value||0,10);
      const e = parseInt(eLevelEl.value||0,10);
      const diff = p - e;
      // Flag 1 min
      stateVal.textContent = 'Agresivo (morado ~1 min)';
      clearTimeout(flagTimer);
      flagTimer = setTimeout(()=> stateVal.textContent = 'Normal', 60000);

      if (diff >= 10) { // PK a low level
        karma += 1000;
        karmaMsg.textContent = '⚠️ PK a jugador muy débil: Karma alto';
        guardMsg.textContent = '🚫 Guards de ciudad = fuerza de Raid 85. No puedes entrar con karma.';
      } else if (diff >= 0 && diff <= 5) { // PK justo
        karma += 100;
        karmaMsg.textContent = '⚔️ PK casi de tu nivel: Karma bajo. Lima matando 2 mobs de tu nivel.';
        guardMsg.textContent = '';
      } else { // intermedio
        karma += 500;
        karmaMsg.textContent = '🟡 Karma moderado.';
        guardMsg.textContent = '';
      }
      karmaVal.textContent = karma;
    });

    document.getElementById('btnMob').addEventListener('click', () => {
      if (karma <= 0) { karmaMsg.textContent = 'No tienes karma.'; return; }
      mobs++;
      if (mobs >= 2 && karma <= 200) {
        karma = 0; mobs = 0;
        karmaMsg.textContent = '✅ Karma limpiado matando mobs.';
        guardMsg.textContent = '';
      } else {
        karmaMsg.textContent = `Has matado un mob... (${mobs}/2)`;
      }
      karmaVal.textContent = karma;
    });

    document.getElementById('btnReset').addEventListener('click', () => {
      karma = 0; mobs = 0; clearTimeout(flagTimer);
      karmaVal.textContent = '0';
      stateVal.textContent = 'Normal';
      karmaMsg.textContent = '';
      guardMsg.textContent = '';
    });

    // --- Etapa 5: Raid Countdown ---
    const raidRows = document.querySelectorAll('#raidList > div');
    function pad(n){return String(n).padStart(2,'0');}
    function tick(){
      const now = new Date();
      raidRows.forEach(row => {
        const t = row.querySelector('.timer');
        const whenStr = row.getAttribute('data-next');
        if (!whenStr) { t.textContent = '—'; return; }
        const when = new Date(whenStr);
        const diff = when - now;
        if (diff <= 0) { t.textContent = '¡Disponible!'; t.classList.add('text-emerald-400'); return; }
        const d = Math.floor(diff/86400000);
        const h = Math.floor((diff%86400000)/3600000);
        const m = Math.floor((diff%3600000)/60000);
        const s = Math.floor((diff%60000)/1000);
        t.textContent = `${d}d ${pad(h)}:${pad(m)}:${pad(s)}`;
      });
    }
    tick(); setInterval(tick, 1000);

    // --- Etapa 6: Raid Access Checker ---
    document.getElementById('btnCheckRaid').addEventListener('click', () => {
      const raid = parseInt(document.getElementById('raidLvl').value||0,10);
      const pl = parseInt(document.getElementById('playerRaidLvl').value||0,10);
      const min = raid - 12;
      const msg = document.getElementById('raidAccessMsg');
      if (pl < min) {
        msg.innerHTML = `❌ No puedes entrar. Nivel mínimo requerido: <span class="text-yellow-400">${min}</span>`;
        msg.className = 'text-center mt-4 text-lg text-red-400';
      } else {
        msg.innerHTML = '✅ Acceso permitido. ¡Suerte con el drop!';
        msg.className = 'text-center mt-4 text-lg text-emerald-400';
      }
    });
  </script>
</body>
</html>
