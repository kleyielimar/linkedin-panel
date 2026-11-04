<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>LinkedIn · Panel de constancia · Kleyi Elimar</title>
<style>
:root{--bg:#f6f4ef;--card:#fff;--ink:#1f2933;--mut:#6b7280;--acc:#0a66c2;--ok:#2f855a;--warn:#c05621;--line:#e5e1d8}
@media(prefers-color-scheme:dark){:root{--bg:#14171a;--card:#1d2227;--ink:#e8eaed;--mut:#9aa3ad;--acc:#5aa9f0;--ok:#68d391;--warn:#f6ad55;--line:#2b323a}}
*{box-sizing:border-box}body{margin:0;background:var(--bg);color:var(--ink);font:16px/1.5 system-ui,-apple-system,Segoe UI,Roboto,sans-serif}
main{max-width:1000px;margin:0 auto;padding:24px 16px 64px}
h1{font-size:1.7rem;margin:0}h2{font-size:1.15rem;margin:0 0 12px}.sub{color:var(--mut);margin:4px 0 24px}
.grid{display:grid;gap:14px}.g4{grid-template-columns:repeat(auto-fit,minmax(150px,1fr))}.g2{grid-template-columns:repeat(auto-fit,minmax(300px,1fr))}
.card{background:var(--card);border:1px solid var(--line);border-radius:14px;padding:18px}
.kpi b{display:block;font-size:2rem;line-height:1.1}.kpi span{color:var(--mut);font-size:.85rem}
section{margin-top:28px}
.why{border-left:5px solid var(--acc)}
.why li{margin:6px 0}
.bar{display:flex;align-items:center;gap:8px;margin:6px 0;font-size:.88rem}.bar i{display:block;height:12px;border-radius:6px;background:var(--acc)}
.bar .l{width:46%;overflow:hidden;text-overflow:ellipsis;white-space:nowrap}.bar em{font-style:normal;color:var(--mut)}
table{width:100%;border-collapse:collapse;font-size:.9rem}th,td{text-align:left;padding:8px 6px;border-bottom:1px solid var(--line)}th{color:var(--mut);font-weight:600}
.tag{display:inline-block;padding:2px 8px;border-radius:99px;font-size:.75rem;background:var(--line)}.tag.ok{color:var(--ok)}.tag.w{color:var(--warn)}
svg text{fill:var(--mut);font-size:10px}
.week{display:grid;grid-template-columns:repeat(5,1fr);gap:8px}.day{border:1px solid var(--line);border-radius:10px;padding:10px;font-size:.85rem}.day b{display:block;margin-bottom:4px}
@media(max-width:640px){.week{grid-template-columns:1fr}}
label.t{display:flex;gap:10px;align-items:flex-start;padding:8px 0;border-bottom:1px solid var(--line);cursor:pointer}
label.t input{margin-top:5px;width:18px;height:18px;accent-color:var(--ok)}
label.t input:checked+span{text-decoration:line-through;color:var(--mut)}
.prog{height:10px;background:var(--line);border-radius:6px;overflow:hidden;margin:6px 0 14px}.prog i{display:block;height:100%;background:var(--ok);width:0;transition:width .3s}
.streak{display:grid;grid-template-columns:repeat(7,1fr);gap:6px}.streak button{aspect-ratio:1;border:1px solid var(--line);border-radius:8px;background:var(--card);color:var(--ink);cursor:pointer;font-size:.8rem}.streak button.on{background:var(--ok);color:#fff;border-color:var(--ok)}
.note{color:var(--mut);font-size:.85rem}
</style>
</head>
<body><main>
<h1>Panel de constancia en LinkedIn</h1>
<p class="sub">Kleyi Elimar · Datos del 8 oct al 4 nov 2026 · Meta: ser consistente, no viral.</p>

<div class="grid g4">
  <div class="card kpi"><b>496</b><span>Impresiones</span></div>
  <div class="card kpi"><b>182</b><span>Miembros alcanzados</span></div>
  <div class="card kpi"><b>12</b><span>Interacciones (2,4 %)</span></div>
  <div class="card kpi"><b>823</b><span>Seguidores (+16)</span></div>
</div>

<section class="card why">
<h2>Por qué hago esto (léelo cuando se te olvide)</h2>
<ul>
<li><b>Tu público real está ahí.</b> El 23 % de tus seguidores son empresas de 2–10 personas y el 14 % de 11–50. Son dueños y fundadores que necesitan lo que tú resuelves: orden, procesos, delegación.</li>
<li><b>Sin constancia, el alcance se cae a casi cero.</b> Con un post por semana, el 31 oct tuviste 0 impresiones. Los picos duran 1–2 días.</li>
<li><b>El tema que funciona es tuyo.</b> El post de delegación duplicó las interacciones de los demás. Más de eso, no algo distinto.</li>
<li><b>Los comentarios te dan visibilidad ajena.</b> Comentar con criterio en perfiles de tu nicho te muestra a gente que aún no te sigue.</li>
<li><b>Son 15 minutos.</b> Si hoy solo haces 5, el día cuenta.</li>
</ul>
</section>

<section class="grid g2">
  <div class="card"><h2>Impresiones por día</h2><div id="daily"></div><p class="note">Pico: 14 oct (76). Después, caída sin publicar. Barras vacías = días sin actividad.</p></div>
  <div class="card"><h2>Publicaciones por impresiones</h2><div id="posts"></div></div>
</section>

<section class="grid g2">
  <div class="card"><h2>Quién te sigue</h2><div id="aud"></div></div>
  <div class="card"><h2>Qué dicen los datos</h2>
  <table>
   <tr><td><span class="tag ok">Funciona</span></td><td>Delegación ("tareas que salen de tus manos": 4 interacciones).</td></tr>
   <tr><td><span class="tag ok">Funciona</span></td><td>Posts antiguos siguen circulando (6 jul: 78 impresiones).</td></tr>
   <tr><td><span class="tag w">Mejorar</span></td><td>Ritmo: 1 post por semana, huecos largos.</td></tr>
   <tr><td><span class="tag w">Mejorar</span></td><td>Casi 1 interacción por post. Faltan preguntas de cierre.</td></tr>
   <tr><td><span class="tag w">Mejorar</span></td><td>Seguidores: ~4 por semana; subir con comentarios.</td></tr>
  </table></div>
</section>

<section class="card">
<h2>Tu semana tipo (≈ 15 min al día)</h2>
<div class="week">
 <div class="day"><b>Lunes</b>Publicar post 1 (delegación o proceso). 15 min.</div>
 <div class="day"><b>Martes</b>3 comentarios con criterio + responder los tuyos.</div>
 <div class="day"><b>Miércoles</b>Publicar post 2 (caso real o pregunta).</div>
 <div class="day"><b>Jueves</b>3 comentarios + responder los tuyos.</div>
 <div class="day"><b>Viernes</b>2 comentarios + mirar 3 cifras (5 min) + anotar 1 idea.</div>
</div>
<p class="note">Versión mínima en un día malo: 1 comentario o responder a 1 persona. Nunca cero.</p>
</section>

<section class="card">
<h2>Plan de acción</h2>
<div class="prog"><i id="pb"></i></div><p class="note" id="pt"></p>
<div id="plan"></div>
<p class="note">Las casillas se guardan en este navegador.</p>
</section>

<section class="card">
<h2>Racha de esta semana</h2>
<div class="streak" id="streak"></div>
<p class="note">Marca cada día que hiciste tu mínimo. El objetivo es no romper la cadena, no ser perfecta.</p>
</section>

<section class="card">
<h2>Ideas para que no se te olvide</h2>
<ol>
<li><b>Ancla a un hábito que ya tienes.</b> "Después del primer café, abro LinkedIn". No dependas de acordarte.</li>
<li><b>Evento fijo en el calendario</b> con alarma, 15 min, y el enlace directo a LinkedIn en la descripción.</li>
<li><b>Día de lote:</b> el domingo escribe 2 posts y déjalos programados (LinkedIn permite programar). Entre semana solo comentas.</li>
<li><b>Banco de ideas:</b> una nota en el móvil. Cada vez que resuelvas algo con un cliente, anota una línea. Nunca empiezas de cero.</li>
<li><b>Versión mínima obligatoria:</b> un día de poco tiempo = un comentario. Así no se rompe el hábito.</li>
<li><b>Mide poco:</b> viernes, 3 cifras (impresiones, interacciones, seguidores nuevos). Ver subir los números te da motivo.</li>
<li><b>Responsable externo:</b> mándale tu cifra del viernes a una persona de confianza o compártela en un grupo.</li>
<li><b>Recompensa semanal</b> si cumples 4 de 5 días.</li>
<li><b>Recordatorio automático:</b> la rutina programada en Claude te avisa al móvil cada día laboral con tu tarea del día. No entra a tu LinkedIn, solo te lo recuerda.</li>
</ol>
</section>

<p class="note">Actualiza los datos cada mes: exporta las analíticas de LinkedIn y sustituye los números en este archivo (sección DATA).</p>
</main>
<script>
// ===== DATA =====
const daily=[17,21,7,14,10,56,76,22,10,6,6,8,30,13,9,9,2,5,17,22,16,13,4,0,9,26,50,18];
const dstart=new Date(2026,9,8);
const posts=[["Antiguo (6 jul)",78],["Tareas que salen de tus manos (13 oct)",72],["Nuevo logro (13 oct)",71],["Buen mes, más clientes (20 oct)",58],["IA y orden del negocio (27 oct)",41],["Procesos y delegación (3 nov)",30],["Negocio funciona solo cuando (9 oct)",30],["Equipos sin más presión (6 oct)",29]];
const aud=[["2–10 empleados",23],["11–50 empleados",14],["Consultoría y servicios",13],["Formación y coaching",9],["Propietarios",8],["Directivos",8],["Fundadores",7],["Madrid",6],["Buenos Aires",4]];
const plan=[
"Esta semana: publicar 2 posts (lunes y miércoles) sobre delegación o procesos, con un caso concreto.",
"Cerrar cada post con una pregunta específica (ej. «¿Qué tarea te cuesta más soltar?»).",
"Comentar 3 veces, 3 días por semana, en perfiles de dueños de pequeños negocios en español (15 min).",
"Responder todos los comentarios de mis posts en menos de 24 horas.",
"Crear el evento recurrente de 15 min en el calendario y fijar el ancla (café).",
"Abrir la nota «Banco de ideas» y anotar 5 ideas hoy.",
"Escribir 2 posts el domingo y programarlos (día de lote).",
"Viernes: anotar impresiones, interacciones y seguidores nuevos (5 min).",
"Dentro de 4 semanas: exportar analíticas, comparar con estas cifras y ajustar."
];
// ===== RENDER =====
const $=id=>document.getElementById(id);
(()=>{const w=560,h=150,m=18,bw=(w-m)/daily.length,mx=Math.max(...daily);
let s=`<svg viewBox="0 0 ${w} ${h+22}" width="100%" role="img" aria-label="Impresiones por día">`;
daily.forEach((v,i)=>{const bh=v/mx*h,d=new Date(dstart);d.setDate(d.getDate()+i);
s+=`<rect x="${m+i*bw+1}" y="${h-bh}" width="${bw-3}" height="${Math.max(bh,1)}" rx="2" fill="${v==mx?'var(--ok)':'var(--acc)'}"><title>${d.getDate()}/${d.getMonth()+1}: ${v}</title></rect>`;
if(i%7==0)s+=`<text x="${m+i*bw}" y="${h+14}">${d.getDate()}/${d.getMonth()+1}</text>`});
s+=`<text x="0" y="10">${mx}</text></svg>`;$('daily').innerHTML=s})();
const bars=(el,d,max,u)=>$(el).innerHTML=d.map(([l,v])=>`<div class="bar"><span class="l" title="${l}">${l}</span><i style="width:${v/max*45}%"></i><em>${v}${u}</em></div>`).join('');
bars('posts',posts,78,'');bars('aud',aud,23,' %');
const K='li-plan-v1',st=JSON.parse(localStorage.getItem(K)||'{}');
$('plan').innerHTML=plan.map((t,i)=>`<label class="t"><input type="checkbox" data-i="${i}" ${st[i]?'checked':''}><span>${t}</span></label>`).join('');
const upd=()=>{const n=Object.values(st).filter(Boolean).length;$('pb').style.width=n/plan.length*100+'%';$('pt').textContent=`${n} de ${plan.length} acciones completadas`};
$('plan').onchange=e=>{st[e.target.dataset.i]=e.target.checked;localStorage.setItem(K,JSON.stringify(st));upd()};upd();
const K2='li-streak-v1',sk=JSON.parse(localStorage.getItem(K2)||'{}');
$('streak').innerHTML=['L','M','X','J','V','S','D'].map((d,i)=>`<button data-i="${i}" class="${sk[i]?'on':''}">${d}</button>`).join('');
$('streak').onclick=e=>{const b=e.target.closest('button');if(!b)return;const i=b.dataset.i;sk[i]=!sk[i];b.classList.toggle('on',sk[i]);localStorage.setItem(K2,JSON.stringify(sk))};
</script>
</body></html>
