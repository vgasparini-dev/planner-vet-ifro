<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Planner Veterinária - IFRO Jaru</title>
<style>
*{margin:0;padding:0;box-sizing:border-box;}
body{font-family:'Segoe UI',sans-serif;background:#0f1117;color:#e2e8f0;min-height:100vh;}
header{background:linear-gradient(135deg,#1a2332,#2d4a6e);padding:16px 24px;display:flex;align-items:center;justify-content:space-between;border-bottom:2px solid #3b82f6;}
header h1{font-size:1.4rem;color:#60a5fa;}header span{font-size:0.85rem;color:#94a3b8;}
nav{background:#1e293b;display:flex;gap:4px;padding:8px 24px;border-bottom:1px solid #334155;flex-wrap:wrap;}
nav button{background:transparent;border:none;color:#94a3b8;padding:8px 16px;border-radius:6px;cursor:pointer;font-size:0.9rem;transition:all 0.2s;}
nav button.active,nav button:hover{background:#3b82f6;color:#fff;}
.container{max-width:1200px;margin:0 auto;padding:24px;}
.section{display:none;}
.section.active{display:block;}
.cards{display:grid;grid-template-columns:repeat(auto-fit,minmax(200px,1fr));gap:16px;margin-bottom:24px;}
.card{background:#1e293b;border-radius:10px;padding:20px;border-left:4px solid #3b82f6;}
.card h3{font-size:0.85rem;color:#94a3b8;margin-bottom:8px;}
.card p{font-size:1.8rem;font-weight:700;color:#60a5fa;}
.card.green{border-color:#22c55e;}.card.green p{color:#22c55e;}
.card.yellow{border-color:#f59e0b;}.card.yellow p{color:#f59e0b;}
.card.red{border-color:#ef4444;}.card.red p{color:#ef4444;}
h2{font-size:1.2rem;color:#60a5fa;margin-bottom:16px;border-bottom:1px solid #334155;padding-bottom:8px;}
table{width:100%;border-collapse:collapse;background:#1e293b;border-radius:10px;overflow:hidden;margin-bottom:24px;}
th{background:#2d4a6e;color:#e2e8f0;padding:10px;font-size:0.85rem;text-align:center;}
td{padding:9px;text-align:center;font-size:0.82rem;border-bottom:1px solid #334155;}
tr:hover td{background:#263549;}
.pill{display:inline-block;padding:3px 10px;border-radius:20px;font-size:0.75rem;font-weight:600;}
.pill.anat{background:#1e3a5f;color:#60a5fa;}
.pill.fisio{background:#14532d;color:#4ade80;}
.pill.bioquim{background:#44220e;color:#fb923c;}
.pill.farm{background:#3b0764;color:#c084fc;}
.pill.patol{background:#450a0a;color:#f87171;}
.pill.micro{background:#0c4a6e;color:#38bdf8;}
.pill.livre{background:#1e293b;color:#64748b;}
form{background:#1e293b;border-radius:10px;padding:20px;margin-bottom:24px;}
form h3{color:#60a5fa;margin-bottom:16px;}
.form-row{display:grid;grid-template-columns:1fr 1fr;gap:12px;margin-bottom:12px;}
label{display:block;font-size:0.8rem;color:#94a3b8;margin-bottom:4px;}
input,select,textarea{width:100%;background:#0f1117;border:1px solid #334155;border-radius:6px;padding:8px 12px;color:#e2e8f0;font-size:0.9rem;}
input:focus,select:focus,textarea:focus{outline:none;border-color:#3b82f6;}
btn{background:#3b82f6;border:none;color:#fff;padding:10px 20px;border-radius:6px;cursor:pointer;font-size:0.9rem;}
btn:hover{background:#2563eb;}
.event-list{list-style:none;}
.event-list li{background:#1e293b;border-radius:8px;padding:12px 16px;margin-bottom:8px;display:flex;align-items:center;gap:12px;border-left:3px solid #3b82f6;}
.event-list li.feriado{border-color:#f59e0b;}
.event-list li.prova{border-color:#ef4444;}
.event-list li.ferias{border-color:#22c55e;}
.event-date{font-size:0.8rem;color:#94a3b8;min-width:90px;}
.event-name{font-size:0.9rem;}
.badge{font-size:0.7rem;padding:2px 8px;border-radius:10px;margin-left:auto;}
.badge.feriado{background:#78350f;color:#fbbf24;}
.badge.ferias{background:#14532d;color:#4ade80;}
.badge.prova{background:#450a0a;color:#fca5a5;}
.badge.aula{background:#1e3a5f;color:#93c5fd;}
.agenda-item{background:#1e293b;border-radius:8px;padding:14px 16px;margin-bottom:10px;display:flex;justify-content:space-between;align-items:center;border-left:3px solid #3b82f6;}
.agenda-item.done{opacity:0.5;border-color:#334155;}
.agenda-item .info h4{font-size:0.95rem;margin-bottom:4px;}
.agenda-item .info span{font-size:0.8rem;color:#94a3b8;}
.agenda-item button{background:#334155;border:none;color:#e2e8f0;padding:6px 12px;border-radius:6px;cursor:pointer;font-size:0.8rem;}
.agenda-item button:hover{background:#475569;}
.crono-table td.study{background:#1e3a5f;color:#93c5fd;font-weight:600;}
.crono-table td.rest{background:#14532d;color:#4ade80;}
.crono-table td.free{background:#1e293b;color:#64748b;}
@media(max-width:600px){.form-row{grid-template-columns:1fr;}.cards{grid-template-columns:1fr 1fr;}}
</style>
</head>
<body>
<header>
<div>
<h1>🐾 Planner Veterinária IFRO</h1>
<div style="font-size:0.8rem;color:#94a3b8;">5º Semestre · Campus Jaru · 2026</div>
</div>
<span id="clock"></span>
</header>
<nav>
<button class="active" onclick="showSection('dashboard',this)">Dashboard</button>
<button onclick="showSection('agenda',this)">Agenda</button>
<button onclick="showSection('horario',this)">Horário</button>
<button onclick="showSection('calendario',this)">Calendário</button>
<button onclick="showSection('cronograma',this)">Cronograma</button>
</nav>
<div class="container">

<!-- DASHBOARD -->
<div id="dashboard" class="section active">
<div class="cards">
<div class="card"><h3>Disciplinas</h3><p>6</p></div>
<div class="card green"><h3>Dias p/ fim sem.</h3><p id="diasFim">--</p></div>
<div class="card yellow"><h3>Próx. Prova</h3><p id="proxProva">--</p></div>
<div class="card red"><h3>Pendências</h3><p id="pendencias">0</p></div>
</div>
<h2>Próximos Eventos</h2>
<ul class="event-list" id="proxEventos"></ul>
</div>

<!-- AGENDA -->
<div id="agenda" class="section">
<form onsubmit="addAgenda(event)">
<h3>+ Nova Tarefa / Avaliação</h3>
<div class="form-row">
<div><label>Título</label><input id="ag-titulo" required placeholder="Ex: Prova de Fisiologia"></div>
<div><label>Data</label><input id="ag-data" type="date" required></div>
</div>
<div class="form-row">
<div><label>Disciplina</label>
<select id="ag-disc">
<option>Anatomia Veterinária</option>
<option>Fisiologia Animal</option>
<option>Bioquímica Clínica</option>
<option>Farmacologia</option>
<option>Patologia Geral</option>
<option>Microbiologia</option>
<option>Outro</option>
</select></div>
<div><label>Tipo</label>
<select id="ag-tipo">
<option value="prova">Prova</option>
<option value="trabalho">Trabalho</option>
<option value="seminario">Seminário</option>
<option value="entrega">Entrega</option>
<option value="outro">Outro</option>
</select></div>
</div>
<div><label>Observações</label><textarea id="ag-obs" rows="2" placeholder="Conteúdo, capítulos..."></textarea></div>
<br><button class="btn" type="submit">Salvar</button>
</form>
<h2>Tarefas Cadastradas</h2>
<div id="agendaList"></div>
</div>

<!-- HORÁRIO -->
<div id="horario" class="section">
<h2>Grade Semanal - 5º Semestre</h2>
<table>
<thead><tr><th>Horário</th><th>Segunda</th><th>Terça</th><th>Quarta</th><th>Quinta</th><th>Sexta</th></tr></thead>
<tbody id="horarioBody"></tbody>
</table>
</div>

<!-- CALENDÁRIO -->
<div id="calendario" class="section">
<h2>Calendário Acadêmico IFRO 2026</h2>
<ul class="event-list" id="calList"></ul>
</div>

<!-- CRONOGRAMA -->
<div id="cronograma" class="section">
<h2>Cronograma de Estudos Semanal</h2>
<table class="crono-table">
<thead><tr><th>Horário</th><th>Seg</th><th>Ter</th><th>Qua</th><th>Qui</th><th>Sex</th><th>Sáb</th><th>Dom</th></tr></thead>
<tbody id="cronoBody"></tbody>
</table>
</div>

</div>

<script>
// Relógio
function updateClock(){const n=new Date();document.getElementById('clock').textContent=n.toLocaleString('pt-BR');}
setInterval(updateClock,1000);updateClock();

// Navegação
function showSection(id,btn){document.querySelectorAll('.section').forEach(s=>s.classList.remove('active'));document.getElementById(id).classList.add('active');document.querySelectorAll('nav button').forEach(b=>b.classList.remove('active'));btn.classList.add('active');}

// Horário de aulas 5º semestre
const aulas=[
['07:30-09:10','Anatomia Vet.','Fisiologia','Anatomia Vet.','Bioquímica','Farmacologia'],
['09:10-10:50','Anatomia Vet.','Fisiologia','Patologia Geral','Bioquímica','Farmacologia'],
['10:50-11:30','Livre','Microbiologia','Livre','Microbiologia','Livre'],
['13:30-15:10','Fisiologia','Patologia Geral','Farmacologia','Anatomia Vet.','Microbiologia'],
['15:10-16:50','Fisiologia','Patologia Geral','Farmacologia','Anatomia Vet.','Microbiologia'],
];
const matCor={'Anatomia Vet.':'anat','Fisiologia':'fisio','Bioquímica':'bioquim','Farmacologia':'farm','Patologia Geral':'patol','Microbiologia':'micro','Livre':'livre'};
const tb=document.getElementById('horarioBody');
aulas.forEach(row=>{const tr=document.createElement('tr');row.forEach((c,i)=>{const td=document.createElement('td');if(i===0){td.textContent=c;td.style.color='#94a3b8';td.style.fontWeight='600';}else{const cls=matCor[c]||'livre';td.innerHTML=`<span class="pill ${cls}">${c}</span>`;}tr.appendChild(td);});tb.appendChild(tr);});

// Calendário IFRO 2026
const eventos=[
{d:'2026-02-02',n:'Início do 1º Semestre 2026',t:'aula'},
{d:'2026-02-23',n:'Carnaval - Ponto Facultativo',t:'feriado'},
{d:'2026-04-03',n:'Sexta-feira Santa',t:'feriado'},
{d:'2026-04-21',n:'Tiradentes',t:'feriado'},
{d:'2026-05-01',n:'Dia do Trabalho',t:'feriado'},
{d:'2026-05-05',n:'Hoje - Meio do Semestre',t:'aula'},
{d:'2026-06-04',n:'Corpus Christi',t:'feriado'},
{d:'2026-06-15',n:'Último dia de aulas - 1º Sem.',t:'aula'},
{d:'2026-06-16',n:'Início do período de provas finais',t:'prova'},
{d:'2026-06-30',n:'Encerramento 1º Semestre',t:'ferias'},
{d:'2026-07-01',n:'Início das Férias',t:'ferias'},
{d:'2026-07-31',n:'Fim das Férias',t:'ferias'},
{d:'2026-08-03',n:'Início do 2º Semestre 2026',t:'aula'},
{d:'2026-09-07',n:'Independência do Brasil',t:'feriado'},
{d:'2026-10-12',n:'Nossa Senhora Aparecida',t:'feriado'},
{d:'2026-11-02',n:'Finados',t:'feriado'},
{d:'2026-11-15',n:'Proclamação da República',t:'feriado'},
{d:'2026-11-20',n:'Consciência Negra',t:'feriado'},
{d:'2026-11-27',n:'Último dia de aulas - 2º Sem.',t:'aula'},
{d:'2026-12-14',n:'Encerramento do Ano Letivo',t:'ferias'},
];

const cl=document.getElementById('calList');
evento=>{const li=document.createElement('li');li.className=eventos[i].t;const dt=new Date(eventos[i].d+'T12:00:00');const ds=dt.toLocaleDateString('pt-BR',{day:'2-digit',month:'short',year:'numeric'});li.innerHTML=`<span class="event-date">${ds}</span><span class="event-name">${eventos[i].n}</span><span class="badge ${eventos[i].t}">${eventos[i].t}</span>`;cl.appendChild(li);};
events.forEach((ev,i)=>{const li=document.createElement('li');li.className=ev.t;const dt=new Date(ev.d+'T12:00:00');const ds=dt.toLocaleDateString('pt-BR',{day:'2-digit',month:'short',year:'numeric'});li.innerHTML=`<span class="event-date">${ds}</span><span class="event-name">${ev.n}</span><span class="badge ${ev.t}">${ev.t}</span>`;cl.appendChild(li);});

// Dashboard - próximos eventos
const pe=document.getElementById('proxEventos');
const hoje=new Date();hoje.setHours(0,0,0,0);
const futuros=eventos.filter(e=>new Date(e.d+'T12:00:00')>=hoje).slice(0,6);
futuros.forEach(ev=>{const li=document.createElement('li');li.className=ev.t;const dt=new Date(ev.d+'T12:00:00');const ds=dt.toLocaleDateString('pt-BR',{day:'2-digit',month:'short'});li.innerHTML=`<span class="event-date">${ds}</span><span class="event-name">${ev.n}</span><span class="badge ${ev.t}">${ev.t}</span>`;pe.appendChild(li);});

// Dias para fim do semestre
const fimSem=new Date('2026-06-30T12:00:00');
const dias=Math.ceil((fimSem-hoje)/(1000*60*60*24));
document.getElementById('diasFim').textContent=dias>0?dias:'--';

// Próxima prova (placeholder)
document.getElementById('proxProva').textContent='Jun';

// Agenda
function loadAgenda(){const items=JSON.parse(localStorage.getItem('agenda')||'[]');const list=document.getElementById('agendaList');list.innerHTML='';document.getElementById('pendencias').textContent=items.filter(i=>!i.done).length;items.sort((a,b)=>a.data.localeCompare(b.data)).forEach((item,idx)=>{const div=document.createElement('div');div.className='agenda-item'+(item.done?' done':'');const dt=new Date(item.data+'T12:00:00').toLocaleDateString('pt-BR');div.innerHTML=`<div class="info"><h4>${item.titulo}</h4><span>${dt} · ${item.disc} · ${item.tipo}${item.obs?' · '+item.obs:''}</span></div><button onclick="toggleDone(${idx})">${item.done?'Reabrir':'Concluir'}</button>`;list.appendChild(div);});}
function addAgenda(e){e.preventDefault();const items=JSON.parse(localStorage.getItem('agenda')||'[]');items.push({titulo:document.getElementById('ag-titulo').value,data:document.getElementById('ag-data').value,disc:document.getElementById('ag-disc').value,tipo:document.getElementById('ag-tipo').value,obs:document.getElementById('ag-obs').value,done:false});localStorage.setItem('agenda',JSON.stringify(items));e.target.reset();loadAgenda();alert('Salvo!');}
function toggleDone(idx){const items=JSON.parse(localStorage.getItem('agenda')||'[]');items[idx].done=!items[idx].done;localStorage.setItem('agenda',JSON.stringify(items));loadAgenda();}
loadAgenda();

// Cronograma
const crono=[
['06:00-07:00','Revisão','Revisão','Revisão','Revisão','Revisão','Livre','Livre'],
['07:30-11:30','AULAS','AULAS','AULAS','AULAS','AULAS','Estudo Livre','Descanso'],
['11:30-13:30','Almoço/Des.','Almoço/Des.','Almoço/Des.','Almoço/Des.','Almoço/Des.','Almoço','Almoço'],
['13:30-17:00','AULAS','AULAS','AULAS','AULAS','AULAS','Estudo Livre','Descanso'],
['17:00-18:30','Exercício','Exercício','Exercício','Exercício','Exercício','Livre','Livre'],
['19:00-21:30','Estudo Anat.','Estudo Fisio','Estudo Bio.','Estudo Farm.','Estudo Pato','Revisão Geral','Livre'],
['21:30-22:00','Planejamento','Planejamento','Planejamento','Planejamento','Planejamento','Livre','Livre'],
];
const cb=document.getElementById('cronoBody');
crono.forEach(row=>{const tr=document.createElement('tr');row.forEach((c,i)=>{const td=document.createElement('td');td.textContent=c;if(i>0){if(c==='AULAS')td.className='study';else if(c.includes('Estudo')||c.includes('Revisão'))td.className='rest';else td.className='free';}else{td.style.color='#94a3b8';td.style.fontWeight='600';}tr.appendChild(td);});cb.appendChild(tr);});
</script>
</body>
</html>
