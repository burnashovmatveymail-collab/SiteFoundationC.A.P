<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width,initial-scale=1" />
<title>C.A.P Foundation — Secure Portal</title>
<style>
  :root{
    --bg:#061107;--panel:#08140a;--grid:#0f2612;--accent:#5df37a;--accent2:#32c95a;
    --text:#d7f7df;--muted:#8fb89a;--danger:#ff5b5b;--card:#0b1a0d;
  }
  *{box-sizing:border-box}
  body{margin:0;background:
    radial-gradient(1200px 600px at 50% -10%,rgba(27,74,38,0.25),transparent 70%),
    linear-gradient(180deg,#061107 0%, #040b06 100%);
    color:var(--text);font-family:ui-monospace,SFMono-Regular,Menlo,Monaco,Consolas,monospace;
    min-height:100vh;display:flex;align-items:flex-start;justify-content:center;padding:24px}
  .wrap{width:1120px;max-width:98%;background:
    linear-gradient(180deg,rgba(93,243,122,0.06),rgba(0,0,0,0.22));
    border:1px solid rgba(93,243,122,0.18);border-radius:12px;padding:16px 16px 22px;
    box-shadow:0 12px 60px rgba(0,0,0,0.55)}
  header{display:flex;align-items:center;gap:12px}
  .logo{font-weight:800;letter-spacing:2px;color:var(--accent);
    padding:6px 10px;border-radius:8px;background:rgba(93,243,122,0.06);
    border:1px solid rgba(93,243,122,0.2)}
  .scan{color:var(--muted);font-size:12px}
  .grid{background-image:linear-gradient(rgba(50,201,90,0.08) 1px,transparent 1px),
        linear-gradient(90deg,rgba(50,201,90,0.08) 1px,transparent 1px);
        background-size:24px 24px; border-radius:10px; border:1px solid rgba(93,243,122,0.12)}
  .card{background:var(--card);padding:14px;border-radius:10px;border:1px solid rgba(93,243,122,0.15);margin-top:12px}
  label{width:170px;color:var(--muted);font-size:13px}
  input, select, textarea{flex:1;padding:10px;border-radius:8px;background:transparent;
    border:1px dashed rgba(93,243,122,0.25);color:inherit;outline:none}
  textarea{resize:vertical}
  form.row{display:flex;gap:12px;align-items:center;margin-bottom:10px}
  .btn{background:linear-gradient(180deg,var(--accent),var(--accent2));
    border:none;padding:10px 14px;border-radius:8px;color:#041006;font-weight:800;cursor:pointer}
  .btn.ghost{background:transparent;border:1px solid rgba(93,243,122,0.33);color:var(--text)}
  .btn.danger{background:var(--danger);color:#fff}
  .topbar{display:flex;justify-content:space-between;align-items:center;margin-bottom:10px}
  .small{font-size:12px;color:var(--muted)}
  .docs{display:grid;gap:10px}
  .doc{padding:12px;border-radius:8px;border:1px solid rgba(93,243,122,0.15);
       background:linear-gradient(180deg,rgba(50,201,90,0.05),rgba(0,0,0,0.05))}
  .tag{display:inline-block;padding:2px 8px;border-radius:999px;border:1px solid rgba(93,243,122,0.3);font-size:12px;color:var(--accent)}
  .modal-back{position:fixed;inset:0;background:rgba(0,0,0,0.6);display:none;align-items:center;justify-content:center;z-index:60}
  .modal{width:820px;max-width:95%;background:var(--panel);padding:16px;border-radius:10px;border:1px solid rgba(93,243,122,0.18)}
  .hidden{display:none}
  .lang-select{padding:8px;border-radius:8px;background:transparent;border:1px solid rgba(93,243,122,0.22);color:inherit}
  .sidebar{width:280px}
  .cat-item{padding:8px;border-radius:8px;background:rgba(50,201,90,0.05);border:1px solid rgba(93,243,122,0.12);cursor:pointer;margin-bottom:6px}
  .cat-item.active{outline:2px solid rgba(93,243,122,0.35)}
  .hr{height:1px;background:linear-gradient(90deg,transparent,rgba(93,243,122,0.35),transparent);margin:10px 0}
</style>
</head>
<body>
<div class="wrap grid">
  <header>
    <div class="logo">C.A.P FOUNDATION</div>
    <div>
      <div class="scan" id="subtitle">CLASSIFIED — INTERNAL SECURE PORTAL</div>
      <div class="small" id="subtitle2">Control of Anomalous Phenomena • v2025.08</div>
    </div>
    <div style="margin-left:auto;display:flex;gap:8px;align-items:center">
      <select id="uiLang" class="lang-select"></select>
      <div id="sessionInfo" class="small"></div>
    </div>
  </header>

  <!-- LOGIN (без демо-кнопки) -->
  <div id="loginCard" class="card">
    <h3 id="t_login_title">Защищённый вход</h3>
    <p class="small" id="t_login_hint">Регистрация отключена. Учетные записи создаются АСБ.</p>
    <form onsubmit="return false;">
      <div class="row"><label id="l_login">Логин</label><input id="inpLogin" type="text" autocomplete="off" /></div>
      <div class="row"><label id="l_password">Пароль</label><input id="inpPass" type="password" /></div>
      <div class="row"><label id="l_access">Уровень доступа</label>
        <select id="inpAccess"><option value="BETA">BETA</option><option value="OMEGA">OMEGA</option><option value="ADMIN">ADMIN</option></select>
      </div>
      <div style="display:flex;justify-content:flex-end;gap:8px;margin-top:8px">
        <button id="btnLogin" class="btn" type="button">ДОСТУП К БАЗЕ</button>
      </div>
    </form>
  </div>

  <!-- PANEL -->
  <div id="panel" class="card hidden">
    <div class="topbar">
      <div>
        <strong id="t_admin_panel">Панель управления</strong>
        <div class="small" id="whoami"></div>
      </div>
      <div style="display:flex;gap:8px;align-items:center">
        <button id="btnAdd" class="btn hidden">Добавить документ</button>
        <button id="btnCreateUser" class="btn hidden">Создать аккаунт</button>
        <button id="btnUsersList" class="btn hidden">Список аккаунтов</button>
        <button id="btnLogout" class="btn ghost">Выйти</button>
      </div>
    </div>

    <div style="display:flex;gap:12px;align-items:flex-start">
      <!-- LEFT -->
      <div style="flex:1">
        <div style="display:flex;justify-content:space-between;align-items:center">
          <h4 id="t_docs">Документы</h4>
          <div>
            <span class="small">Фильтр:</span>
            <select id="catFilter" class="lang-select" style="padding:6px"></select>
          </div>
        </div>
        <div id="docEmpty" class="small">Документов на текущем языке/категории нет.</div>
        <div id="docList" class="docs"></div>
      </div>

      <!-- RIGHT -->
      <div class="sidebar">
        <div class="card">
          <div class="small">Состояние</div>
          <div class="hr"></div>
          <div class="small">UI язык: <strong id="curLangLabel">Русский</strong></div>
          <div class="small">Документы (язык): <strong id="docsLangLabel">Русский</strong></div>
          <div class="small">Всего аккаунтов: <strong id="usersCount">0</strong></div>
          <div class="hr"></div>
          <div class="small">Категории:</div>
          <div id="catsBox"></div>
        </div>

        <div class="card" style="margin-top:10px">
          <div class="small">Быстрые действия</div>
          <div class="hr"></div>
          <button id="btnExport" class="btn ghost">Экспорт БД</button>
          <button id="btnImport" class="btn ghost">Импорт БД</button>
          <button id="btnManageCats" class="btn ghost hidden">Категории</button>
        </div>
      </div>
    </div>
  </div>

  <!-- Modal: Add Document -->
  <div id="modalDoc" class="modal-back">
    <div class="modal">
      <h3>Добавить документ</h3>
      <div class="small">Сохранится на текущем языке интерфейса.</div>
      <div style="margin-top:8px"><input id="docTitle" placeholder="Заголовок" /></div>
      <div style="margin-top:8px;display:flex;gap:8px;align-items:center">
        <label style="width:170px">Категория</label>
        <select id="docCategory"></select>
      </div>
      <div id="newCatRow" style="display:none;margin-top:8px"><input id="docNewCategory" placeholder="Новая категория" /></div>
      <div style="margin-top:8px">
        <label style="width:170px;display:block;margin-bottom:6px">Класс</label>
        <select id="docClass" style="width:100%;padding:10px;border-radius:8px;background:transparent;border:1px dashed rgba(93,243,122,0.25);color:inherit">
          <option value="ALPHA">ALPHA</option><option value="BETA">BETA</option><option value="OMEGA">OMEGA</option><option value="CUSTOM">CUSTOM</option>
        </select>
      </div>
      <div id="customClassRow" style="display:none;margin-top:8px"><input id="docCustomClass" placeholder="Свой класс (если CUSTOM)" /></div>
      <div style="margin-top:8px"><textarea id="docBody" rows="9" placeholder="Текст документа"></textarea></div>
      <div style="display:flex;justify-content:flex-end;gap:8px;margin-top:10px">
        <button id="saveDoc" class="btn">Сохранить</button>
        <button id="cancelDoc" class="btn ghost">Отмена</button>
      </div>
    </div>
  </div>

  <!-- Modal: Create User -->
  <div id="modalUser" class="modal-back">
    <div class="modal">
      <h3>Создать аккаунт</h3>
      <div class="small">Регистрация закрыта. Аккаунты создаёт администратор.</div>
      <div style="margin-top:8px"><input id="uLogin" placeholder="Логин" /></div>
      <div style="margin-top:8px"><input id="uPass" placeholder="Пароль" /></div>
      <div style="margin-top:8px"><input id="uEmail" placeholder="Почта" /></div>
      <div style="margin-top:8px"><input id="uFullName" placeholder="Имя и Фамилия" /></div>
      <div style="margin-top:8px"><input id="uRole" placeholder="Должность (Scientist, Hunter…)" /></div>
      <div style="margin-top:8px"><select id="uAccess"><option value="BETA">BETA</option><option value="OMEGA">OMEGA</option><option value="ADMIN">ADMIN</option></select></div>
      <div style="display:flex;justify-content:flex-end;gap:8px;margin-top:10px">
        <button id="saveUser" class="btn">Создать</button>
        <button id="cancelUser" class="btn ghost">Отмена</button>
      </div>
    </div>
  </div>

  <!-- Modal: Users List (Только главный админ) -->
  <div id="modalUsersList" class="modal-back">
    <div class="modal">
      <h3>Список аккаунтов</h3>
      <div class="small">Просмотр, редактирование и удаление аккаунтов. Доступно только главному администратору.</div>
      <div id="usersTable" style="margin-top:10px"></div>
      <div style="display:flex;justify-content:flex-end;gap:8px;margin-top:10px">
        <button id="closeUsersList" class="btn ghost">Закрыть</button>
      </div>
    </div>
  </div>

  <!-- Modal: Manage Categories -->
  <div id="modalCats" class="modal-back">
    <div class="modal">
      <h3>Категории (текущий язык)</h3>
      <div class="small">Создание / переименование / удаление.</div>
      <div id="catManageList" style="margin-top:12px;display:flex;flex-direction:column;gap:8px"></div>
      <div style="display:flex;gap:8px;justify-content:flex-end;margin-top:12px">
        <button id="closeCats" class="btn ghost">Закрыть</button>
      </div>
    </div>
  </div>

</div>

<script>
/* Keys */
const KEY_USERS='cap_users_v3';
const KEY_DOCS='cap_docs_v3';
const KEY_CATS='cap_cats_v2';
const KEY_SESSION='cap_session_v3';
const KEY_LANG='cap_lang_v3';
const MASTER_LOGIN='C.A.P Admin Foundation';
const MASTER_PASS='QwePoiCAP';

/* Langs (UI only) */
const languages=[{code:'ru',label:'Русский'},{code:'en',label:'English'},{code:'uk',label:'Українська'},{code:'he',label:'עברית'},{code:'fr',label:'Français'},{code:'de',label:'Deutsch'},{code:'es',label:'Español'},{code:'ja',label:'日本語'}];

function load(k,d){ try{return JSON.parse(localStorage.getItem(k))??d}catch(e){return d}}
function save(k,v){ localStorage.setItem(k,JSON.stringify(v)) }

/* Ensure master */
function ensureMaster(){
  let users=load(KEY_USERS,[]);
  if(!users.find(u=>u.login===MASTER_LOGIN)){
    users.push({login:MASTER_LOGIN,pass:MASTER_PASS,email:'admin@cap.local',fullName:'C.A.P Admin',role:'Administrator',access:'ADMIN',created:Date.now(),createdBy:MASTER_LOGIN});
    save(KEY_USERS,users);
  }
}
ensureMaster();

/* Initial cats/docs */
function ensureInitialData(){
  const docs=load(KEY_DOCS,[]);
  const cats=load(KEY_CATS,[]);
  if(!cats.find(c=>c.code==='Admin' && c.lang==='ru')){
    cats.push({id:'cat_admin_ru',code:'Admin',name:'Admin',lang:'ru'});
  }
  if(!docs.find(d=>d.isMaster && d.lang==='ru')){
    const body=`СЕКРЕТНО — ГЛАВНЫЙ ДОКУМЕНТ
C.A.P FOUNDATION (Контроль Аномальных Явлений)

Цели: Обнаружение • Содержание • Уничтожение.
Создан: 12.02.2025. Международный мандат.

Структура: ЭНИМАЛ • СИМБИОЛ • ВПС • ЖЕЛЕЗНЫЙ КУПОЛ • АСБ • Научный отдел.

Классы: ALPHA / BETA / OMEGA.

Доступ администратора:
Login: ${MASTER_LOGIN}
Password: ${MASTER_PASS}`;
    docs.push({id:'doc_master_ru',title:'Главный документ C.A.P (RU)',body,lang:'ru',categoryCode:'Admin',categoryName:'Admin',cls:'OMEGA',ts:Date.now(),author:MASTER_LOGIN,isMaster:true});
  }
  save(KEY_DOCS,docs); save(KEY_CATS,cats);
}
ensureInitialData();

/* Elements */
const ui={
  uiLang:qs('#uiLang'),
  loginCard:qs('#loginCard'),
  panel:qs('#panel'),
  whoami:qs('#whoami'),
  btnLogin:qs('#btnLogin'),
  btnLogout:qs('#btnLogout'),
  btnAdd:qs('#btnAdd'),
  btnCreateUser:qs('#btnCreateUser'),
  btnUsersList:qs('#btnUsersList'),
  btnManageCats:qs('#btnManageCats'),
  docList:qs('#docList'),
  docEmpty:qs('#docEmpty'),
  catsBox:qs('#catsBox'),
  catFilter:qs('#catFilter'),
  usersCount:qs('#usersCount'),
  curLangLabel:qs('#curLangLabel'),
  docsLangLabel:qs('#docsLangLabel'),
  // modals/fields
  modalDoc:qs('#modalDoc'),
  modalUser:qs('#modalUser'),
  modalUsersList:qs('#modalUsersList'),
  modalCats:qs('#modalCats'),
  docTitle:qs('#docTitle'),
  docBody:qs('#docBody'),
  docCategory:qs('#docCategory'),
  docNewCategory:qs('#docNewCategory'),
  newCatRow:qs('#newCatRow'),
  docClass:qs('#docClass'),
  customClassRow:qs('#customClassRow'),
  docCustomClass:qs('#docCustomClass'),
  uLogin:qs('#uLogin'),
  uPass:qs('#uPass'),
  uEmail:qs('#uEmail'),
  uFullName:qs('#uFullName'),
  uRole:qs('#uRole'),
  uAccess:qs('#uAccess'),
  usersTable:qs('#usersTable'),
  closeUsersList:qs('#closeUsersList'),
  catManageList:qs('#catManageList'),
  closeCats:qs('#closeCats')
};

function qs(s,root=document){return root.querySelector(s)}
function qsa(s,root=document){return [...root.querySelectorAll(s)]}

/* Language selector */
languages.forEach(l=>{ const o=document.createElement('option');o.value=l.code;o.textContent=l.label;ui.uiLang.appendChild(o); });
ui.uiLang.value=localStorage.getItem(KEY_LANG)||'ru';
updateLangUI();

ui.uiLang.addEventListener('change',()=>{localStorage.setItem(KEY_LANG',ui.uiLang.value)});

/* fix typo above and apply proper set + rerender */
ui.uiLang.addEventListener('change',()=>{
  localStorage.setItem(KEY_LANG, ui.uiLang.value);
  updateLangUI(); renderCats(); renderCatFilter(); renderDocs();
});

function getLang(){ return localStorage.getItem(KEY_LANG)||'ru' }
function updateLangUI(){
  const cur=languages.find(x=>x.code===getLang()); ui.curLangLabel.textContent=cur?cur.label:'—';
  ui.docsLangLabel.textContent=ui.curLangLabel.textContent;
}

/* Session */
function setSession(s){ save(KEY_SESSION,s) }
function getSession(){ return load(KEY_SESSION,null) }
function clearSession(){ localStorage.removeItem(KEY_SESSION) }

/* Login */
ui.btnLogin.addEventListener('click',()=>{
  const login=qs('#inpLogin').value.trim();
  const pass=qs('#inpPass').value;
  const access=qs('#inpAccess').value;
  const u=load(KEY_USERS,[]).find(x=>x.login===login && x.pass===pass && x.access===access);
  if(!u){ alert('Доступ запрещён. Проверьте данные.'); return; }
  setSession({login:u.login,access:u.access,ts:Date.now()});
  showPanel(u);
});

/* Auto-login if session */
(function(){ const s=getSession(); if(!s) return; const u=load(KEY_USERS,[]).find(x=>x.login===s.login); if(u) showPanel(u) })();

/* Show panel */
function showPanel(user){
  ui.loginCard.classList.add('hidden');
  ui.panel.classList.remove('hidden');
  ui.whoami.textContent=`${user.login} — ${user.role||'—'} (${user.access})`;
  // Admin buttons: only master sees Users List and Manage Cats
  const isMaster = user.login===MASTER_LOGIN;
  if(user.access==='ADMIN'){ ui.btnAdd.classList.remove('hidden'); ui.btnCreateUser.classList.remove('hidden'); }
  else { ui.btnAdd.classList.add('hidden'); ui.btnCreateUser.classList.add('hidden'); }
  if(isMaster){ ui.btnUsersList.classList.remove('hidden'); ui.btnManageCats.classList.remove('hidden'); }
  else { ui.btnUsersList.classList.add('hidden'); ui.btnManageCats.classList.add('hidden'); }
  updateUsersCount(); renderCats(); renderCatFilter(); renderDocs();
}

/* Logout */
ui.btnLogout.addEventListener('click',()=>{ if(!confirm('Выйти из системы?')) return; clearSession(); ui.panel.classList.add('hidden'); ui.loginCard.classList.remove('hidden'); });

/* Users count */
function updateUsersCount(){ ui.usersCount.textContent = load(KEY_USERS,[]).length }

/* Docs */
function renderDocs(){
  const docs=load(KEY_DOCS,[]);
  const lang=getLang();
  const cat=ui.catFilter.value||'__all__';
  const filtered=docs.filter(d=>d.lang===lang && (cat==='__all__' || d.categoryCode===cat));
  ui.docList.innerHTML='';
  if(filtered.length===0){ ui.docEmpty.style.display='block'; return } else ui.docEmpty.style.display='none';
  filtered.sort((a,b)=>b.ts-a.ts).forEach(d=>{
    const el=document.createElement('div'); el.className='doc';
    el.innerHTML=`<div style="display:flex;justify-content:space-between;gap:8px;align-items:center">
      <h4 style="margin:0">${escapeHtml(d.title)}</h4>
      <span class="tag">${escapeHtml(d.cls||'—')}</span>
    </div>
    <div class="small">Автор: ${escapeHtml(d.author||'—')} • ${new Date(d.ts).toLocaleString()} • Категория: ${escapeHtml(d.categoryName||d.categoryCode||'—')}</div>
    <pre style="white-space:pre-wrap;margin-top:8px;color:#cfead6">${escapeHtml(d.body)}</pre>
    <div style="display:flex;gap:8px;justify-content:flex-end;margin-top:8px">
      <button class="btn ghost" data-edit="${d.id}">Редактировать</button>
      <button class="btn danger" data-del="${d.id}">Удалить</button>
    </div>`;
    ui.docList.appendChild(el);
    el.querySelector('[data-del]').addEventListener('click',()=>{ if(!confirm('Удалить документ?'))return; const id=d.id; const all=load(KEY_DOCS,[]).filter(x=>x.id!==id); save(KEY_DOCS,all); renderDocs(); });
    el.querySelector('[data-edit]').addEventListener('click',()=>{ openEditDoc(d) });
  });
}

/* Edit doc -> reuse add modal */
function openEditDoc(doc){
  ui.docTitle.value=doc.title;
  ui.docBody.value=doc.body;
  populateCategorySelect();
  ui.docCategory.value=doc.categoryCode||'__none__';
  ui.docClass.value= (doc.cls==='ALPHA'||doc.cls==='BETA'||doc.cls==='OMEGA')?doc.cls:'CUSTOM';
  ui.customClassRow.style.display = ui.docClass.value==='CUSTOM' ? 'block':'none';
  ui.docCustomClass.value= (ui.docClass.value==='CUSTOM')?doc.cls:'';
  ui.newCatRow.style.display='none';
  ui.modalDoc.style.display='flex';
  // override save button once
  const handler=()=>{
    const title=ui.docTitle.value.trim(), body=ui.docBody.value.trim(); if(!title||!body){alert('Заполните поля');return}
    let catCode=ui.docCategory.value, catName=null;
    if(catCode==='__new__'){ const name=ui.docNewCategory.value.trim(); if(!name){alert('Новая категория пуста');return}
      catCode='cat_'+name.replace(/\s+/g,'_').toLowerCase()+'_'+Math.random().toString(36).slice(2,5);
      catName=name; const cats=load(KEY_CATS,[]); cats.push({id:catCode,code:catCode,name,lang:getLang()}); save(KEY_CATS,cats); renderCats(); renderCatFilter();
    } else if(catCode==='__none__'){ catCode=null; }
    else { const found=load(KEY_CATS,[]).find(c=>c.code===catCode && c.lang===getLang()); catName=found?found.name:catCode; }
    let cls=ui.docClass.value; if(cls==='CUSTOM'){ cls=ui.docCustomClass.value.trim()||'CUSTOM' }
    const all=load(KEY_DOCS,[]); const idx=all.findIndex(x=>x.id===doc.id); if(idx>=0){ all[idx]={...all[idx],title,body,categoryCode:catCode,categoryName:catName,cls}; save(KEY_DOCS,all); }
    ui.modalDoc.style.display='none'; renderDocs();
    ui.saveDoc.removeEventListener('click',handler);
  };
  ui.saveDoc.addEventListener('click',handler);
}

/* Escape */
function escapeHtml(s){ return String(s||'').replace(/[&<>"]/g,c=>({'&':'&amp;','<':'&lt;','>':'&gt;','"':'&quot;'}[c])) }

/* Categories UI */
function renderCats(){
  const cats=load(KEY_CATS,[]).filter(c=>c.lang===getLang());
  ui.catsBox.innerHTML='';
  cats.forEach(c=>{
    const el=document.createElement('div'); el.className='cat-item'; el.textContent=c.name;
    el.addEventListener('click',()=>{ ui.catFilter.value=c.code; renderDocs(); highlightActiveCat(); });
    ui.catsBox.appendChild(el);
  });
  highlightActiveCat(); populateCategorySelect();
}
function highlightActiveCat(){
  const active=ui.catFilter.value;
  qsa('.cat-item').forEach(el=>{
    const name=el.textContent;
    const obj=load(KEY_CATS,[]).find(c=>c.name===name && c.lang===getLang());
    if(obj && obj.code===active) el.classList.add('active'); else el.classList.remove('active');
  });
}
function renderCatFilter(){
  const cats=load(KEY_CATS,[]).filter(c=>c.lang===getLang());
  ui.catFilter.innerHTML='';
  const allOpt=document.createElement('option'); allOpt.value='__all__'; allOpt.textContent='Все'; ui.catFilter.appendChild(allOpt);
  cats.forEach(c=>{ const o=document.createElement('option'); o.value=c.code; o.textContent=c.name; ui.catFilter.appendChild(o); });
  ui.catFilter.addEventListener('change',()=>{ renderDocs(); highlightActiveCat(); });
}
function populateCategorySelect(){
  const cats=load(KEY_CATS,[]).filter(c=>c.lang===getLang());
  ui.docCategory.innerHTML='';
  const def=document.createElement('option'); def.value='__none__'; def.textContent='— Без категории —'; ui.docCategory.appendChild(def);
  cats.forEach(c=>{ const o=document.createElement('option'); o.value=c.code; o.textContent=c.name; ui.docCategory.appendChild(o); });
  const oNew=document.createElement('option'); oNew.value='__new__'; oNew.textContent='— Создать новую категорию —'; ui.docCategory.appendChild(oNew);
}
ui.docCategory.addEventListener('change',()=>{ ui.newCatRow.style.display = ui.docCategory.value==='__new__' ? 'block' : 'none' });
ui.docClass.addEventListener('change',()=>{ ui.customClassRow.style.display = ui.docClass.value==='CUSTOM' ? 'block':'none' });

/* Open add doc */
qs('#btnAdd').addEventListener('click',()=>{ ui.docTitle.value=''; ui.docBody.value=''; ui.docNewCategory.value=''; ui.docCustomClass.value=''; populateCategorySelect(); ui.docClass.value='ALPHA'; ui.customClassRow.style.display='none'; ui.newCatRow.style.display='none'; ui.modalDoc.style.display='flex'; });

/* Save / cancel add doc */
qs('#cancelDoc').addEventListener('click',()=> ui.modalDoc.style.display='none');
qs('#saveDoc').addEventListener('click',()=>{ // create new doc
  const title=ui.docTitle.value.trim(), body=ui.docBody.value.trim();
  if(!title||!body){ alert('Заполните заголовок и текст'); return; }
  let catCode=ui.docCategory.value, catName=null;
  if(catCode==='__new__'){ const name=ui.docNewCategory.value.trim(); if(!name){ alert('Новая категория пуста'); return; }
    catCode='cat_'+name.replace(/\s+/g,'_').toLowerCase()+'_'+Math.random().toString(36).slice(2,5); catName=name;
    const cats=load(KEY_CATS,[]); cats.push({id:catCode,code:catCode,name,lang:getLang()}); save(KEY_CATS,cats); renderCats(); renderCatFilter();
  } else if(catCode==='__none__'){ catCode=null; } else { const found=load(KEY_CATS,[]).find(c=>c.code===catCode && c.lang===getLang()); catName=found?found.name:catCode; }
  let cls=ui.docClass.value; if(cls==='CUSTOM'){ cls=ui.docCustomClass.value.trim()||'CUSTOM' }
  const id='doc_'+Math.random().toString(36).slice(2,10);
  const sess=getSession()||{login:'unknown'};
  const docs=load(KEY_DOCS,[]);
  docs.push({id,title,body,lang:getLang(),categoryCode:catCode,categoryName:catName,cls,ts:Date.now(),author:sess.login});
  save(KEY_DOCS,docs); ui.modalDoc.style.display='none'; renderDocs();
});

/* Create user */
qs('#btnCreateUser').addEventListener('click',()=> ui.modalUser.style.display='flex');
qs('#cancelUser').addEventListener('click',()=> ui.modalUser.style.display='none');
qs('#saveUser').addEventListener('click',()=>{
  const login=ui.uLogin.value.trim(), pass=ui.uPass.value, email=ui.uEmail.value.trim(), fullName=ui.uFullName.value.trim(), role=ui.uRole.value.trim(), access=ui.uAccess.value;
  if(!login||!pass){alert('Логин и пароль обязательны');return}
  const users=load(KEY_USERS,[]);
  if(users.find(u=>u.login===login)){ alert('Такой логин уже существует'); return; }
  const creator=(getSession()||{}).login||MASTER_LOGIN;
  users.push({login,pass,email,fullName,role,access,created:Date.now(),createdBy:creator});
  save(KEY_USERS,users);
  ui.modalUser.style.display='none';
  ui.uLogin.value=ui.uPass.value=ui.uEmail.value=ui.uFullName.value=ui.uRole.value='';
  updateUsersCount();
});

/* Users List (only master admin) */
qs('#btnUsersList').addEventListener('click',()=>{
  const s=getSession(); if(!s || s.login!==MASTER_LOGIN){ alert('Доступ только главному администратору'); return; }
  renderUsersTable(); ui.modalUsersList.style.display='flex';
});
ui.closeUsersList.addEventListener('click',()=> ui.modalUsersList.style.display='none');

function renderUsersTable(){
  const users=load(KEY_USERS,[]).sort((a,b)=>a.login.localeCompare(b.login));
  const rows=users.map((u,i)=> userRow(u,i)).join('');
  ui.usersTable.innerHTML=`
    <div style="overflow:auto;max-height:60vh">
      <table style="width:100%;border-collapse:collapse">
        <thead>
          <tr>
            <th class="small" style="text-align:left;padding:6px;border-bottom:1px solid rgba(93,243,122,0.2)">Логин</th>
            <th class="small" style="text-align:left;padding:6px;border-bottom:1px solid rgba(93,243,122,0.2)">Имя</th>
            <th class="small" style="text-align:left;padding:6px;border-bottom:1px solid rgba(93,243,122,0.2)">Почта</th>
            <th class="small" style="text-align:left;padding:6px;border-bottom:1px solid rgba(93,243,122,0.2)">Роль</th>
            <th class="small" style="text-align:left;padding:6px;border-bottom:1px solid rgba(93,243,122,0.2)">Доступ</th>
            <th class="small" style="text-align:left;padding:6px;border-bottom:1px solid rgba(93,243,122,0.2)">Создал</th>
            <th class="small" style="padding:6px;border-bottom:1px solid rgba(93,243,122,0.2)"></th>
          </tr>
        </thead>
        <tbody>${rows}</tbody>
      </table>
    </div>`;
  // wire actions
  qsa('[data-edit-user]').forEach(btn=>btn.addEventListener('click',()=> editUser(btn.getAttribute('data-edit-user'))));
  qsa('[data-del-user]').forEach(btn=>btn.addEventListener('click',()=> delUser(btn.getAttribute('data-del-user'))));
}

function userRow(u,i){
  return `<tr>
    <td style="padding:6px;border-bottom:1px dashed rgba(93,243,122,0.15)">${escapeHtml(u.login)}</td>
    <td style="padding:6px;border-bottom:1px dashed rgba(93,243,122,0.15)">${escapeHtml(u.fullName||'')}</td>
    <td style="padding:6px;border-bottom:1px dashed rgba(93,243,122,0.15)">${escapeHtml(u.email||'')}</td>
    <td style="padding:6px;border-bottom:1px dashed rgba(93,243,122,0.15)">${escapeHtml(u.role||'')}</td>
    <td style="padding:6px;border-bottom:1px dashed rgba(93,243,122,0.15)"><span class="tag">${escapeHtml(u.access)}</span></td>
    <td style="padding:6px;border-bottom:1px dashed rgba(93,243,122,0.15)">${escapeHtml(u.createdBy||'—')}</td>
    <td style="padding:6px;border-bottom:1px dashed rgba(93,243,122,0.15);text-align:right">
      <button class="btn ghost" data-edit-user="${u.login}">Изм.</button>
      <button class="btn danger" data-del-user="${u.login}">Удалить</button>
    </td>
  </tr>`;
}

function editUser(login){
  const users=load(KEY_USERS,[]);
  const idx=users.findIndex(u=>u.login===login); if(idx<0) return;
  const u=users[idx];
  const fullName=prompt('Имя и Фамилия:', u.fullName||''); if(fullName===null) return;
  const email=prompt('Почта:', u.email||''); if(email===null) return;
  const role=prompt('Должность:', u.role||''); if(role===null) return;
  const access=prompt('Уровень доступа (BETA/OMEGA/ADMIN):', u.access||'BETA'); if(access===null) return;
  users[idx]={...u,fullName,email,role,access};
  save(KEY_USERS,users); renderUsersTable(); updateUsersCount();
}

function delUser(login){
  if(login===MASTER_LOGIN){ alert('Нельзя удалить главный аккаунт'); return; }
  if(!confirm('Удалить аккаунт '+login+'?')) return;
  const users=load(KEY_USERS,[]).filter(u=>u.login!==login); save(KEY_USERS,users);
  // если удаляем текущую сессию — разлогин
  const s=getSession(); if(s && s.login===login){ clearSession(); location.reload(); return; }
  renderUsersTable(); updateUsersCount();
}

/* Manage categories (only master) */
ui.btnManageCats.addEventListener('click',()=>{
  const s=getSession(); if(!s || s.login!==MASTER_LOGIN){ alert('Доступ только главному администратору'); return; }
  renderCatsManager(); ui.modalCats.style.display='flex';
});
ui.closeCats.addEventListener('click',()=> ui.modalCats.style.display='none');

function renderCatsManager(){
  const cats=load(KEY_CATS,[]).filter(c=>c.lang===getLang());
  ui.catManageList.innerHTML='';
  if(cats.length===0){ ui.catManageList.textContent='Категорий нет'; return; }
  cats.forEach(c=>{
    const row=document.createElement('div'); row.style.display='flex'; row.style.gap='8px';
    const name=document.createElement('input'); name.value=c.name; name.style.flex='1';
    const btnRename=document.createElement('button'); btnRename.textContent='Переименовать'; btnRename.className='btn ghost';
    const btnDelete=document.createElement('button'); btnDelete.textContent='Удалить'; btnDelete.className='btn danger';
    row.appendChild(name); row.appendChild(btnRename); row.appendChild(btnDelete); ui.catManageList.appendChild(row);
    btnRename.addEventListener('click',()=>{ const all=load(KEY_CATS,[]); const i=all.findIndex(x=>x.id===c.id); if(i>=0){ all[i].name=name.value.trim()||all[i].name; save(KEY_CATS,all); renderCats(); renderCatFilter(); alert('Переименовано'); } });
    btnDelete.addEventListener('click',()=>{ if(!confirm('Удалить категорию? Документы останутся без категории.')) return; let all=load(KEY_CATS,[]).filter(x=>x.id!==c.id); save(KEY_CATS,all); renderCats(); renderCatFilter(); renderCatsManager(); });
  });
}

/* Open modals backdrop close */
qsa('.modal-back').forEach(m=> m.addEventListener('click',(e)=>{ if(e.target===m) m.style.display='none'; }));

/* Export / Import */
qs('#btnExport').addEventListener('click',()=>{
  const payload={users:load(KEY_USERS,[]),docs:load(KEY_DOCS,[]),cats:load(KEY_CATS,[])};
  const blob=new Blob([JSON.stringify(payload,null,2)],{type:'application/json'});
  const url=URL.createObjectURL(blob); const a=document.createElement('a'); a.href=url; a.download='cap_export_'+Date.now()+'.json'; a.click(); URL.revokeObjectURL(url);
});
qs('#btnImport').addEventListener('click',()=>{
  const input=document.createElement('input'); input.type='file'; input.accept='application/json';
  input.addEventListener('change',(e)=>{ const f=e.target.files[0]; if(!f) return; const r=new FileReader(); r.onload=()=>{ try{ const p=JSON.parse(r.result); if(p.users) save(KEY_USERS,p.users); if(p.docs) save(KEY_DOCS,p.docs); if(p.cats) save(KEY_CATS,p.cats); alert('Импорт завершён'); updateUsersCount(); renderCats(); renderCatFilter(); renderDocs(); }catch(err){ alert('Неверный файл'); } }; r.readAsText(f); });
  input.click();
});

/* Helpers */
function loadUsers(){ return load(KEY_USERS,[]) }
function loadDocs(){ return load(KEY_DOCS,[]) }
function loadCats(){ return load(KEY_CATS,[]) }

renderCats(); renderCatFilter(); renderDocs(); updateUsersCount();
</script>
</body>
</html>
