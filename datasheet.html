<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>DataSheet</title>
<link href="https://fonts.googleapis.com/css2?family=DM+Mono:wght@400;500&family=Fraunces:ital,wght@0,300;0,600;1,300&display=swap" rel="stylesheet">
<style>
  :root {
    --cyan:   #00f0ff;
    --purple: #a259ff;
    --pink:   #ff4ecd;
    --teal:   #3cffd0;
    --glass:        rgba(255,255,255,0.06);
    --glass-border: rgba(255,255,255,0.12);
    --text:       #eef4ff;
    --text-muted: rgba(200,220,255,0.55);
    --text-dim:   rgba(160,185,220,0.35);
    --row-bg:      rgba(255,255,255,0.03);
    --row-alt:     rgba(255,255,255,0.055);
    --row-hover:   rgba(0,240,255,0.06);
    --row-border:  rgba(255,255,255,0.07);
    --col-border:  rgba(255,255,255,0.08);
    --group-line:  rgba(0,240,255,0.18);
  }

  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

  body {
    font-family: 'DM Mono', monospace;
    color: var(--text);
    min-height: 100vh;
    display: flex;
    flex-direction: column;
    background: #060a12;
    overflow-x: hidden;
  }

  /* ── Orbs & stars ── */
  body::before, body::after {
    content: '';
    position: fixed; border-radius: 50%;
    filter: blur(90px); pointer-events: none; z-index: 0;
    animation: orbDrift 12s ease-in-out infinite alternate;
  }
  body::before {
    width: 520px; height: 520px;
    background: radial-gradient(circle, rgba(162,89,255,0.32) 0%, transparent 70%);
    top: -140px; left: -100px;
  }
  body::after {
    width: 420px; height: 420px;
    background: radial-gradient(circle, rgba(0,240,255,0.25) 0%, transparent 70%);
    bottom: -80px; right: -60px;
    animation-direction: alternate-reverse; animation-duration: 9s;
  }
  .orb-mid {
    position: fixed; width: 300px; height: 300px; border-radius: 50%;
    background: radial-gradient(circle, rgba(255,78,205,0.16) 0%, transparent 70%);
    filter: blur(70px); top: 40%; left: 55%;
    pointer-events: none; z-index: 0;
    animation: orbDrift 15s ease-in-out infinite alternate; animation-delay: -5s;
  }
  @keyframes orbDrift {
    from { transform: translate(0,0) scale(1); }
    to   { transform: translate(35px,25px) scale(1.1); }
  }
  .scanlines {
    position: fixed; inset: 0; pointer-events: none; z-index: 1;
    background: repeating-linear-gradient(to bottom, transparent 0, transparent 3px, rgba(0,0,0,0.06) 3px, rgba(0,0,0,0.06) 4px);
  }
  .stars { position: fixed; inset: 0; z-index: 0; pointer-events: none; }
  .star {
    position: absolute; border-radius: 50%; background: #fff;
    animation: twinkle var(--d,2s) ease-in-out infinite alternate;
  }
  @keyframes twinkle {
    from { opacity: var(--mo,0.05); transform: scale(1); }
    to   { opacity: 0.85; transform: scale(1.5); }
  }

  header, .toolbar, .sheet-wrap, .statusbar { position: relative; z-index: 10; }

  /* ── Header ── */
  header {
    background: rgba(6,10,18,0.75);
    backdrop-filter: blur(24px); -webkit-backdrop-filter: blur(24px);
    border-bottom: 1px solid rgba(0,240,255,0.18);
    padding: 0 24px; height: 58px;
    display: flex; align-items: center; justify-content: space-between;
    position: sticky; top: 0; z-index: 100;
    box-shadow: 0 1px 30px rgba(0,240,255,0.07);
  }
  .logo {
    font-family: 'Fraunces', serif; font-size: 1.3rem; font-weight: 600;
    display: flex; align-items: center; gap: 10px;
    background: linear-gradient(90deg, var(--cyan), var(--purple));
    -webkit-background-clip: text; -webkit-text-fill-color: transparent;
    background-clip: text; filter: drop-shadow(0 0 12px rgba(0,240,255,0.28));
  }
  .logo-dot { width: 8px; height: 8px; border-radius: 50%; background: var(--cyan); box-shadow: 0 0 8px var(--cyan); flex-shrink: 0; }
  .header-actions { display: flex; align-items: center; gap: 8px; }

  /* ── Glass Buttons ── */
  .btn {
    font-family: 'DM Mono', monospace; font-size: 0.72rem;
    padding: 7px 16px; border-radius: 8px; cursor: pointer;
    transition: all 0.2s; letter-spacing: 0.05em;
    backdrop-filter: blur(12px); position: relative; overflow: hidden;
  }
  .btn::before {
    content: ''; position: absolute; inset: 0;
    background: linear-gradient(135deg, rgba(255,255,255,0.1) 0%, transparent 60%);
    pointer-events: none;
  }
  .btn-ghost {
    background: rgba(255,255,255,0.06); border: 1px solid rgba(255,255,255,0.14); color: rgba(200,220,255,0.75);
  }
  .btn-ghost:hover { background: rgba(255,255,255,0.11); border-color: rgba(0,240,255,0.38); color: var(--cyan); box-shadow: 0 0 14px rgba(0,240,255,0.12); }
  .btn-primary {
    background: rgba(0,240,255,0.14); border: 1px solid rgba(0,240,255,0.38); color: var(--cyan);
    box-shadow: 0 0 14px rgba(0,240,255,0.1);
  }
  .btn-primary:hover { background: rgba(0,240,255,0.24); border-color: var(--cyan); box-shadow: 0 0 26px rgba(0,240,255,0.28); transform: translateY(-1px); }
  .btn-danger-sm {
    background: rgba(255,50,80,0.08); border: 1px solid rgba(255,60,90,0.25); color: rgba(255,120,130,0.7);
    font-size: 0.68rem; padding: 5px 11px;
  }
  .btn-danger-sm:hover { background: rgba(255,50,80,0.16); border-color: rgba(255,60,90,0.5); color: #ff8090; box-shadow: 0 0 12px rgba(255,60,90,0.18); }

  /* ── Toolbar ── */
  .toolbar {
    background: rgba(6,10,18,0.55);
    backdrop-filter: blur(20px); -webkit-backdrop-filter: blur(20px);
    border-bottom: 1px solid rgba(255,255,255,0.07);
    padding: 9px 24px; display: flex; align-items: center; gap: 10px; flex-wrap: wrap;
  }
  .toolbar-group { display: flex; align-items: center; gap: 6px; }
  .toolbar-divider { width: 1px; height: 22px; background: rgba(255,255,255,0.1); }
  .tb-btn {
    font-family: 'DM Mono', monospace; font-size: 0.69rem;
    padding: 5px 13px; border-radius: 6px;
    border: 1px solid rgba(255,255,255,0.1);
    background: rgba(255,255,255,0.05); color: var(--text-muted);
    cursor: pointer; transition: all 0.18s; letter-spacing: 0.03em;
    backdrop-filter: blur(10px); position: relative; overflow: hidden;
  }
  .tb-btn::before { content:''; position:absolute; inset:0; background:linear-gradient(135deg,rgba(255,255,255,0.07) 0%,transparent 60%); pointer-events:none; }
  .tb-btn:hover { border-color: rgba(0,240,255,0.35); color: var(--cyan); background: rgba(0,240,255,0.07); box-shadow: 0 0 10px rgba(0,240,255,0.1); }
  .tb-btn.active { background: rgba(0,240,255,0.14); border-color: rgba(0,240,255,0.45); color: var(--cyan); box-shadow: 0 0 14px rgba(0,240,255,0.18); }
  .tb-btn.danger { color: rgba(255,120,120,0.65); border-color: rgba(255,80,80,0.2); }
  .tb-btn.danger:hover { background: rgba(255,60,60,0.1); border-color: rgba(255,80,80,0.45); color: #ff9090; box-shadow: 0 0 10px rgba(255,60,60,0.14); }

  .search-wrap { position: relative; margin-left: auto; }
  .search-wrap input {
    font-family: 'DM Mono', monospace; font-size: 0.72rem;
    padding: 6px 12px 6px 30px; border: 1px solid rgba(255,255,255,0.11);
    border-radius: 6px; background: rgba(255,255,255,0.05);
    backdrop-filter: blur(12px); color: var(--text); width: 200px; outline: none; transition: all 0.18s;
  }
  .search-wrap input::placeholder { color: var(--text-dim); }
  .search-wrap input:focus { border-color: rgba(0,240,255,0.38); background: rgba(0,240,255,0.05); box-shadow: 0 0 14px rgba(0,240,255,0.09); }
  .search-wrap::before { content:'⌕'; position:absolute; left:9px; top:50%; transform:translateY(-50%); font-size:14px; color:var(--text-dim); pointer-events:none; }

  /* ── Sheet ── */
  .sheet-wrap { flex: 1; overflow: auto; padding: 20px 24px 60px; }
  .sheet-title-row { display: flex; align-items: center; gap: 14px; margin-bottom: 16px; }
  #sheet-title {
    font-family: 'Fraunces', serif; font-size: 1.4rem; font-weight: 300; font-style: italic;
    color: var(--text); border: none; background: transparent; outline: none;
    border-bottom: 1px dashed rgba(0,240,255,0.22); padding: 2px 4px; min-width: 180px;
  }
  .row-count {
    font-size: 0.67rem; color: var(--cyan);
    background: rgba(0,240,255,0.07); border: 1px solid rgba(0,240,255,0.2);
    padding: 2px 10px; border-radius: 20px; letter-spacing: 0.05em;
  }

  /* ── Table glass card ── */
  .table-outer {
    border-radius: 12px; overflow: auto;
    border: 1px solid rgba(0,240,255,0.14);
    box-shadow: 0 8px 40px rgba(0,0,0,0.5), 0 0 60px rgba(0,240,255,0.04);
    backdrop-filter: blur(20px); -webkit-backdrop-filter: blur(20px);
  }

  table {
    border-collapse: collapse; font-size: 0.78rem;
    /* width grows with columns — no min-width cap */
  }

  /* ── Table header (days as columns) ── */
  thead tr { background: rgba(0,240,255,0.07); border-bottom: 1px solid rgba(0,240,255,0.18); }
  th {
    padding: 11px 14px; text-align: left;
    font-weight: 500; font-size: 0.66rem; letter-spacing: 0.09em;
    text-transform: uppercase; border-right: 1px solid rgba(255,255,255,0.07);
    white-space: nowrap; user-select: none; color: rgba(0,240,255,0.68);
  }
  th:last-child { border-right: none; }
  th.th-chk  { width: 36px; text-align: center; color: rgba(255,255,255,0.22); }
  th.th-task { min-width: 200px; max-width: 280px; }
  th.th-pri  { width: 120px; }
  th.th-day  {
    min-width: 110px; text-align: center;
    cursor: pointer; transition: color 0.15s;
  }
  th.th-day:hover { color: var(--cyan); }
  th.th-day .day-date { display: block; font-size: 0.58rem; color: var(--text-dim); letter-spacing: 0.05em; font-weight: 400; margin-top: 2px; text-transform: none; }
  th.th-day .day-pill-hdr {
    display: inline-flex; align-items: center; gap: 5px;
    padding: 2px 9px 2px 5px; border-radius: 20px; font-size: 0.68rem; font-weight: 500;
  }
  th.th-day .dot { width: 5px; height: 5px; border-radius: 50%; }

  /* ── Task rows ── */
  tbody tr.task-row {
    border-bottom: 1px solid var(--row-border);
    transition: background 0.1s;
  }
  tbody tr.task-row:nth-child(even) { background: var(--row-alt); }
  tbody tr.task-row:hover { background: var(--row-hover); }
  tbody tr.task-row.selected { background: rgba(0,240,255,0.08); }

  td {
    padding: 0; border-right: 1px solid var(--col-border); vertical-align: middle;
  }
  td:last-child { border-right: none; }

  /* checkbox */
  td.td-chk { text-align: center; padding: 8px 4px; border-right: 1px solid rgba(255,255,255,0.1); min-width: 36px; }
  td.td-chk input { accent-color: var(--cyan); cursor: pointer; }

  /* Task name cell */
  td.td-task {
    min-width: 200px; max-width: 280px; padding: 0;
    border-right: 1px solid rgba(0,240,255,0.15);
  }
  .task-inner {
    display: flex; flex-direction: column; gap: 0;
    padding: 6px 12px 4px;
  }
  .task-name-wrap { display: flex; align-items: center; gap: 6px; }
  .task-name-wrap input[type="text"] {
    flex: 1; background: transparent; border: none;
    font-family: 'DM Mono', monospace; font-size: 0.78rem;
    color: var(--text); outline: none; min-height: 28px; padding: 2px 0;
  }
  .task-name-wrap input::placeholder { color: var(--text-dim); }
  .task-name-wrap input:focus { border-bottom: 1px solid rgba(0,240,255,0.35); }

  /* Priority mini-buttons */
  .pri-btns { display: flex; gap: 4px; margin-top: 4px; margin-bottom: 2px; }
  .pri-btn {
    display: flex; align-items: center; gap: 4px;
    font-family: 'DM Mono', monospace; font-size: 0.58rem;
    padding: 2px 7px; border-radius: 20px; cursor: pointer;
    border: 1px solid transparent; transition: all 0.15s; letter-spacing: 0.04em;
    background: rgba(255,255,255,0.04);
  }
  .pri-btn .pdi { width: 6px; height: 6px; border-radius: 50%; }
  .pri-btn.pb-Low    { border-color: rgba(60,255,208,0.2);  color: rgba(60,255,208,0.55);  }
  .pri-btn.pb-Medium { border-color: rgba(255,217,61,0.2);  color: rgba(255,217,61,0.55);  }
  .pri-btn.pb-High   { border-color: rgba(255,140,0,0.25);  color: rgba(255,140,0,0.6);    }
  .pri-btn.pb-Critical { border-color: rgba(255,60,90,0.25); color: rgba(255,60,90,0.65);  }

  .pri-btn.pb-Low .pdi    { background: #3cffd0; box-shadow: 0 0 4px rgba(60,255,208,0.6);  }
  .pri-btn.pb-Medium .pdi { background: #ffd93d; box-shadow: 0 0 4px rgba(255,217,61,0.65); }
  .pri-btn.pb-High .pdi   { background: #ff8c00; box-shadow: 0 0 4px rgba(255,140,0,0.7);   }
  .pri-btn.pb-Critical .pdi { background: #ff3c5a; box-shadow: 0 0 5px rgba(255,60,90,0.8); }

  .pri-btn.active.pb-Low    { background: rgba(60,255,208,0.12); border-color: rgba(60,255,208,0.5);  color: #3cffd0; box-shadow: 0 0 8px rgba(60,255,208,0.25); }
  .pri-btn.active.pb-Medium { background: rgba(255,217,61,0.12); border-color: rgba(255,217,61,0.5);  color: #ffd93d; box-shadow: 0 0 8px rgba(255,217,61,0.25); }
  .pri-btn.active.pb-High   { background: rgba(255,140,0,0.12);  border-color: rgba(255,140,0,0.55);  color: #ff8c00; box-shadow: 0 0 8px rgba(255,140,0,0.3);   }
  .pri-btn.active.pb-Critical { background: rgba(255,60,90,0.12); border-color: rgba(255,60,90,0.55); color: #ff3c5a; box-shadow: 0 0 8px rgba(255,60,90,0.3);  }

  .pri-btn:not(.active):hover { opacity: 0.8; transform: scale(1.05); }

  /* Day status cells */
  td.td-day {
    text-align: center; vertical-align: middle;
    padding: 10px 8px; min-width: 110px;
    border-right: 1px solid var(--col-border);
  }

  /* Tick / untick button */
  .tick-btn {
    display: inline-flex; align-items: center; justify-content: center;
    width: 32px; height: 32px; border-radius: 50%; border: 2px solid;
    cursor: pointer; font-size: 0.9rem; transition: all 0.2s;
    backdrop-filter: blur(8px); position: relative; background: none;
  }
  .tick-btn::after {
    content: ''; position: absolute; inset: -5px; border-radius: 50%;
    opacity: 0; transition: opacity 0.2s;
  }
  .tick-btn:hover::after { opacity: 1; }

  .tick-done {
    background: rgba(0,255,120,0.1); border-color: #00ff78; color: #00ff78;
    box-shadow: 0 0 10px rgba(0,255,120,0.45), inset 0 0 6px rgba(0,255,120,0.08);
  }
  .tick-done::after { background: radial-gradient(circle, rgba(0,255,120,0.14) 0%, transparent 70%); }
  .tick-done:hover { background: rgba(0,255,120,0.18); box-shadow: 0 0 22px rgba(0,255,120,0.6); transform: scale(1.12); }

  .tick-undone {
    background: rgba(255,50,80,0.08); border-color: #ff3c5a; color: #ff3c5a;
    box-shadow: 0 0 8px rgba(255,60,90,0.3), inset 0 0 5px rgba(255,60,90,0.07);
  }
  .tick-undone::after { background: radial-gradient(circle, rgba(255,60,90,0.14) 0%, transparent 70%); }
  .tick-undone:hover { background: rgba(255,50,80,0.16); box-shadow: 0 0 20px rgba(255,60,90,0.5); transform: scale(1.12); }

  @keyframes tickPop {
    0% { transform: scale(1); } 40% { transform: scale(1.3); }
    70% { transform: scale(0.9); } 100% { transform: scale(1); }
  }
  .tick-btn.pop { animation: tickPop 0.3s ease; }

  /* Empty + add row */
  tr.add-task-row td { padding: 6px 12px; border-bottom: none; }
  tr.empty-row td { padding: 50px; text-align: center; color: var(--text-dim); font-size: 0.75rem; font-style: italic; letter-spacing: 0.06em; }

  /* Add-day button row */
  .add-day-btn {
    font-family: 'DM Mono', monospace; font-size: 0.66rem;
    color: rgba(0,240,255,0.5); background: rgba(0,240,255,0.04);
    border: 1px dashed rgba(0,240,255,0.18); border-radius: 5px;
    padding: 4px 12px; cursor: pointer; transition: all 0.18s; letter-spacing: 0.04em;
    backdrop-filter: blur(8px);
  }
  .add-day-btn:hover { border-color: rgba(0,240,255,0.45); color: var(--cyan); background: rgba(0,240,255,0.09); box-shadow: 0 0 10px rgba(0,240,255,0.1); }

  .add-task-inline-btn {
    font-family: 'DM Mono', monospace; font-size: 0.65rem;
    color: rgba(0,240,255,0.45); background: transparent;
    border: 1px dashed rgba(0,240,255,0.16); border-radius: 4px;
    padding: 3px 10px; cursor: pointer; transition: all 0.18s;
  }
  .add-task-inline-btn:hover { border-color: rgba(0,240,255,0.4); color: var(--cyan); background: rgba(0,240,255,0.07); }

  .del-row-btn {
    background: transparent; border: none;
    color: rgba(255,120,120,0.3); cursor: pointer; padding: 4px 6px;
    border-radius: 4px; transition: all 0.15s; font-size: 0.7rem;
    font-family: 'DM Mono', monospace;
  }
  .del-row-btn:hover { background: rgba(255,60,60,0.1); color: #ff9090; box-shadow: 0 0 8px rgba(255,60,60,0.12); }

  /* ── Status bar ── */
  .statusbar {
    background: rgba(6,10,18,0.78); backdrop-filter: blur(20px); -webkit-backdrop-filter: blur(20px);
    color: var(--text-dim); font-size: 0.64rem; letter-spacing: 0.06em;
    padding: 5px 24px; display: flex; align-items: center; gap: 22px;
    border-top: 1px solid rgba(0,240,255,0.09); position: sticky; bottom: 0;
  }
  .statusbar b { color: var(--cyan); font-weight: 500; }

  /* ── Modal ── */
  .modal-overlay {
    display: none; position: fixed; inset: 0;
    background: rgba(0,0,0,0.72); backdrop-filter: blur(6px);
    z-index: 200; align-items: center; justify-content: center;
  }
  .modal-overlay.open { display: flex; }
  .modal {
    background: rgba(10,16,28,0.88);
    backdrop-filter: blur(28px) saturate(1.3); -webkit-backdrop-filter: blur(28px) saturate(1.3);
    border: 1px solid rgba(0,240,255,0.18); border-radius: 14px;
    padding: 26px; width: 420px; max-width: 95vw; max-height: 85vh; overflow-y: auto;
    box-shadow: 0 30px 80px rgba(0,0,0,0.6), 0 0 60px rgba(0,240,255,0.07);
    position: relative;
  }
  .modal::before {
    content: ''; position: absolute; inset: 0; border-radius: 14px;
    background: linear-gradient(135deg, rgba(255,255,255,0.04) 0%, transparent 50%);
    pointer-events: none;
  }
  .modal h2 {
    font-family: 'Fraunces', serif; font-size: 1.1rem; font-weight: 600; margin-bottom: 18px;
    background: linear-gradient(90deg, var(--cyan), var(--purple));
    -webkit-background-clip: text; -webkit-text-fill-color: transparent; background-clip: text;
  }
  .form-row { display: flex; flex-direction: column; gap: 5px; margin-bottom: 14px; }
  .form-row label { font-size: 0.63rem; text-transform: uppercase; letter-spacing: 0.1em; color: var(--text-muted); }
  .form-row input, .form-row select {
    font-family: 'DM Mono', monospace; font-size: 0.78rem; padding: 9px 12px;
    border: 1px solid rgba(255,255,255,0.1); border-radius: 7px;
    background: rgba(255,255,255,0.05); backdrop-filter: blur(10px);
    color: var(--text); outline: none; transition: all 0.18s;
  }
  .form-row input:focus, .form-row select:focus {
    border-color: rgba(0,240,255,0.42); background: rgba(0,240,255,0.05);
    box-shadow: 0 0 12px rgba(0,240,255,0.09);
  }
  .form-row select option { background: #0e1421; }
  .modal-actions { display: flex; gap: 8px; justify-content: flex-end; margin-top: 20px; border-top: 1px solid rgba(255,255,255,0.07); padding-top: 16px; }

  /* ── Tab nav ── */
  .tab-nav {
    display: flex; align-items: center; gap: 4px;
    position: absolute; left: 50%; transform: translateX(-50%);
  }
  .tab-btn {
    font-family: 'DM Mono', monospace; font-size: 0.7rem;
    padding: 6px 16px; border-radius: 6px; cursor: pointer;
    transition: all 0.18s; letter-spacing: 0.04em;
    border: 1px solid rgba(255,255,255,0.1);
    background: rgba(255,255,255,0.04); color: var(--text-muted);
    backdrop-filter: blur(10px);
  }
  .tab-btn:hover { border-color: rgba(0,240,255,0.3); color: var(--cyan); background: rgba(0,240,255,0.06); }
  .tab-btn.active { background: rgba(0,240,255,0.14); border-color: rgba(0,240,255,0.45); color: var(--cyan); box-shadow: 0 0 14px rgba(0,240,255,0.18); }

  /* ── Report page ── */
  #report-page { display: none; flex: 1; overflow-y: auto; padding: 28px 24px 60px; position: relative; z-index: 10; }
  #report-page.active { display: block; }

  .report-header { margin-bottom: 28px; }
  .report-title {
    font-family: 'Fraunces', serif; font-size: 1.6rem; font-weight: 300; font-style: italic;
    background: linear-gradient(90deg, var(--cyan), var(--purple), var(--pink));
    -webkit-background-clip: text; -webkit-text-fill-color: transparent; background-clip: text;
    margin-bottom: 6px;
  }
  .report-subtitle { font-size: 0.7rem; color: var(--text-dim); letter-spacing: 0.06em; }

  /* Summary cards */
  .summary-cards { display: grid; grid-template-columns: repeat(auto-fit, minmax(150px, 1fr)); gap: 14px; margin-bottom: 30px; }
  .s-card {
    background: rgba(255,255,255,0.05);
    backdrop-filter: blur(16px); -webkit-backdrop-filter: blur(16px);
    border: 1px solid rgba(255,255,255,0.1); border-radius: 12px;
    padding: 16px 18px; position: relative; overflow: hidden;
    transition: border-color 0.2s;
  }
  .s-card::before {
    content: ''; position: absolute; inset: 0;
    background: linear-gradient(135deg, rgba(255,255,255,0.06) 0%, transparent 55%);
    pointer-events: none;
  }
  .s-card:hover { border-color: rgba(0,240,255,0.28); }
  .s-card-label { font-size: 0.62rem; text-transform: uppercase; letter-spacing: 0.1em; color: var(--text-dim); margin-bottom: 6px; }
  .s-card-value { font-size: 1.8rem; font-weight: 500; line-height: 1; }
  .s-card-sub { font-size: 0.65rem; color: var(--text-muted); margin-top: 4px; }
  .cv-cyan   { color: var(--cyan); text-shadow: 0 0 16px rgba(0,240,255,0.5); }
  .cv-green  { color: #00ff78; text-shadow: 0 0 16px rgba(0,255,120,0.4); }
  .cv-purple { color: var(--purple); text-shadow: 0 0 16px rgba(162,89,255,0.4); }
  .cv-amber  { color: #ffd93d; text-shadow: 0 0 16px rgba(255,217,61,0.4); }
  .cv-pink   { color: var(--pink); text-shadow: 0 0 16px rgba(255,78,205,0.4); }

  /* Section header */
  .section-head {
    font-size: 0.68rem; text-transform: uppercase; letter-spacing: 0.1em;
    color: var(--text-muted); margin-bottom: 14px; padding-bottom: 8px;
    border-bottom: 1px solid rgba(255,255,255,0.07);
    display: flex; align-items: center; justify-content: space-between;
  }

  /* Progress bar rows */
  .prog-list { display: flex; flex-direction: column; gap: 10px; margin-bottom: 32px; }
  .prog-row {
    background: rgba(255,255,255,0.04); border: 1px solid rgba(255,255,255,0.08);
    border-radius: 10px; padding: 12px 16px;
    backdrop-filter: blur(12px);
    transition: border-color 0.18s;
  }
  .prog-row:hover { border-color: rgba(0,240,255,0.2); }
  .prog-top { display: flex; align-items: center; justify-content: space-between; margin-bottom: 8px; }
  .prog-name { font-size: 0.8rem; color: var(--text); white-space: nowrap; overflow: hidden; text-overflow: ellipsis; max-width: 55%; }
  .prog-right { display: flex; align-items: center; gap: 10px; flex-shrink: 0; }
  .prog-pct { font-size: 0.9rem; font-weight: 500; }
  .prog-days { font-size: 0.65rem; color: var(--text-dim); white-space: nowrap; }
  .prog-bar-track {
    height: 6px; border-radius: 6px; background: rgba(255,255,255,0.08); overflow: hidden;
  }
  .prog-bar-fill {
    height: 100%; border-radius: 6px; transition: width 0.8s cubic-bezier(.22,1,.36,1);
    position: relative;
  }
  .prog-bar-fill::after {
    content: ''; position: absolute; inset: 0; border-radius: 6px;
    background: linear-gradient(90deg, transparent 0%, rgba(255,255,255,0.25) 50%, transparent 100%);
    animation: shimmer 2s infinite;
  }
  @keyframes shimmer { 0%{transform:translateX(-100%)} 100%{transform:translateX(200%)} }

  /* Day dots row inside task */
  .prog-dots { display: flex; gap: 5px; margin-top: 7px; flex-wrap: wrap; }
  .prog-dot {
    display: flex; align-items: center; gap: 4px;
    font-size: 0.6rem; color: var(--text-dim);
    padding: 2px 7px; border-radius: 20px;
    border: 1px solid rgba(255,255,255,0.08);
    background: rgba(255,255,255,0.03);
  }
  .prog-dot .di { width: 5px; height: 5px; border-radius: 50%; }
  .prog-dot.pd-done { border-color: rgba(0,255,120,0.3); color: #00ff78; background: rgba(0,255,120,0.07); }
  .prog-dot.pd-done .di { background: #00ff78; box-shadow: 0 0 4px rgba(0,255,120,0.7); }
  .prog-dot.pd-pend .di { background: rgba(255,60,90,0.5); }

  /* Day completion bars */
  .day-grid { display: grid; grid-template-columns: repeat(auto-fill, minmax(150px, 1fr)); gap: 12px; margin-bottom: 32px; }
  .day-card {
    background: rgba(255,255,255,0.04); border: 1px solid rgba(255,255,255,0.09);
    border-radius: 10px; padding: 14px 16px;
    backdrop-filter: blur(12px); transition: all 0.18s;
  }
  .day-card:hover { border-color: rgba(0,240,255,0.2); transform: translateY(-2px); }
  .day-card-hdr { display: flex; align-items: center; gap: 8px; margin-bottom: 10px; }
  .day-card-pill { display: inline-flex; align-items: center; gap: 5px; padding: 2px 9px 2px 5px; border-radius: 20px; font-size: 0.7rem; font-weight: 500; }
  .day-card-pill .dot { width: 5px; height: 5px; border-radius: 50%; }
  .day-pct-big { font-size: 1.5rem; font-weight: 500; line-height: 1; margin-bottom: 4px; }
  .day-sub { font-size: 0.62rem; color: var(--text-dim); margin-bottom: 8px; }

  /* History section */
  .history-list { display: flex; flex-direction: column; gap: 10px; }
  .hist-card {
    background: rgba(255,255,255,0.03); border: 1px solid rgba(255,255,255,0.08);
    border-radius: 10px; padding: 14px 18px; backdrop-filter: blur(12px);
  }
  .hist-hdr { display: flex; align-items: center; justify-content: space-between; margin-bottom: 10px; }
  .hist-week { font-size: 0.75rem; color: var(--cyan); }
  .hist-pct { font-size: 1.1rem; font-weight: 500; }
  .hist-meta { font-size: 0.62rem; color: var(--text-dim); }
  .hist-tasks { display: flex; flex-wrap: wrap; gap: 5px; margin-top: 8px; }
  .hist-task-chip {
    font-size: 0.6rem; padding: 2px 8px; border-radius: 20px;
    border: 1px solid rgba(255,255,255,0.1); background: rgba(255,255,255,0.04); color: var(--text-muted);
  }
  .hist-task-chip.done { border-color: rgba(0,255,120,0.25); background: rgba(0,255,120,0.07); color: #00ff78; }

  /* Empty history */
  .hist-empty { padding: 40px; text-align: center; color: var(--text-dim); font-size: 0.75rem; font-style: italic; }

  /* Save week button */
  .save-week-btn {
    font-family: 'DM Mono', monospace; font-size: 0.72rem;
    padding: 9px 20px; border-radius: 8px; cursor: pointer;
    background: rgba(162,89,255,0.14); border: 1px solid rgba(162,89,255,0.4); color: var(--purple);
    box-shadow: 0 0 14px rgba(162,89,255,0.12); transition: all 0.2s; letter-spacing: 0.04em;
    backdrop-filter: blur(12px);
  }
  .save-week-btn:hover { background: rgba(162,89,255,0.24); border-color: var(--purple); box-shadow: 0 0 24px rgba(162,89,255,0.28); transform: translateY(-1px); }

  .del-hist-btn {
    background: transparent; border: none; color: rgba(255,100,100,0.3);
    cursor: pointer; font-size: 0.65rem; font-family: 'DM Mono', monospace;
    padding: 2px 6px; border-radius: 3px; transition: all 0.12s;
  }
  .del-hist-btn:hover { color: #ff9090; background: rgba(255,60,60,0.1); }
    position: fixed; bottom: 52px; right: 20px;
    background: rgba(10,16,28,0.9); backdrop-filter: blur(20px);
    color: var(--cyan); border: 1px solid rgba(0,240,255,0.28); border-radius: 6px;
    padding: 8px 18px; font-size: 0.7rem; letter-spacing: 0.05em;
    opacity: 0; transform: translateY(8px); transition: all 0.22s;
    pointer-events: none; z-index: 300; box-shadow: 0 0 18px rgba(0,240,255,0.12);
  }
  .notif.show { opacity: 1; transform: translateY(0); }

  /* Day header colors */
  .dh-Mon { background:rgba(60,255,208,0.08); color:#3cffd0; }  .dh-Mon .dot { background:#3cffd0; box-shadow:0 0 4px #3cffd0; }
  .dh-Tue { background:rgba(122,172,255,0.08); color:#7aacff; } .dh-Tue .dot { background:#7aacff; box-shadow:0 0 4px #7aacff; }
  .dh-Wed { background:rgba(255,199,106,0.08); color:#ffc76a; } .dh-Wed .dot { background:#ffc76a; box-shadow:0 0 4px #ffc76a; }
  .dh-Thu { background:rgba(196,154,255,0.08); color:#c49aff; } .dh-Thu .dot { background:#c49aff; box-shadow:0 0 4px #c49aff; }
  .dh-Fri { background:rgba(90,255,154,0.08);  color:#5aff9a; } .dh-Fri .dot { background:#5aff9a; box-shadow:0 0 4px #5aff9a; }
  .dh-Sat { background:rgba(255,142,219,0.08); color:#ff8edb; } .dh-Sat .dot { background:#ff8edb; box-shadow:0 0 4px #ff8edb; }
  .dh-Sun { background:rgba(255,142,219,0.08); color:#ff8edb; } .dh-Sun .dot { background:#ff8edb; box-shadow:0 0 4px #ff8edb; }
</style>
</head>
<body>

<div class="orb-mid"></div>
<div class="stars" id="stars"></div>
<div class="scanlines"></div>

<header>
  <div class="logo"><div class="logo-dot"></div>DataSheet</div>
  <div class="tab-nav">
    <button class="tab-btn active" id="tab-sheet" onclick="switchTab('sheet')">&#128203; Sheet</button>
    <button class="tab-btn" id="tab-report" onclick="switchTab('report')">&#128202; Weekly Report</button>
  </div>
  <div class="header-actions">
    <button class="btn btn-ghost" id="btn-export" onclick="exportCSV()">Export CSV</button>
    <button class="btn btn-ghost" id="btn-addday" onclick="openAddDayModal()">+ Add Day</button>
    <button class="btn btn-primary" id="btn-addtask" onclick="addTask()">+ Add Task</button>
  </div>
</header>

<div class="toolbar">
  <div class="toolbar-group">
    <button class="tb-btn active" id="fp-all"      onclick="filterPri('all')">All priority</button>
    <button class="tb-btn" id="fp-Low"      onclick="filterPri('Low')">Low</button>
    <button class="tb-btn" id="fp-Medium"   onclick="filterPri('Medium')">Medium</button>
    <button class="tb-btn" id="fp-High"     onclick="filterPri('High')">High</button>
    <button class="tb-btn" id="fp-Critical" onclick="filterPri('Critical')">Critical</button>
  </div>
  <div class="toolbar-divider"></div>
  <button class="tb-btn danger" onclick="deleteSelected()">Delete selected</button>
  <div class="search-wrap">
    <input type="text" id="search" placeholder="Search tasks..." oninput="renderTable()">
  </div>
</div>

<div class="sheet-wrap" id="sheet-page">
  <div class="sheet-title-row">
    <input id="sheet-title" value="Weekly Planner" spellcheck="false">
    <span class="row-count" id="row-count">0 tasks</span>
  </div>
  <div class="table-outer" id="table-outer">
    <table id="main-table">
      <thead id="thead"></thead>
      <tbody id="tbody"></tbody>
    </table>
  </div>
</div>

<!-- Report Page -->
<div id="report-page">
  <div class="report-header">
    <div class="report-title">Weekly Report</div>
    <div class="report-subtitle" id="report-daterange">Showing current week data</div>
  </div>

  <!-- Summary cards -->
  <div class="summary-cards">
    <div class="s-card">
      <div class="s-card-label">Overall done</div>
      <div class="s-card-value cv-green" id="rp-overall">0%</div>
      <div class="s-card-sub" id="rp-overall-sub">0 of 0 cells</div>
    </div>
    <div class="s-card">
      <div class="s-card-label">Tasks tracked</div>
      <div class="s-card-value cv-cyan" id="rp-tasks">0</div>
      <div class="s-card-sub">across all days</div>
    </div>
    <div class="s-card">
      <div class="s-card-label">Days tracked</div>
      <div class="s-card-value cv-purple" id="rp-days">0</div>
      <div class="s-card-sub">columns in sheet</div>
    </div>
    <div class="s-card">
      <div class="s-card-label">Best day</div>
      <div class="s-card-value cv-amber" id="rp-best-day">—</div>
      <div class="s-card-sub" id="rp-best-sub">highest completion</div>
    </div>
    <div class="s-card">
      <div class="s-card-label">Fully done tasks</div>
      <div class="s-card-value cv-pink" id="rp-full-tasks">0</div>
      <div class="s-card-sub">100% across all days</div>
    </div>
  </div>

  <!-- Per-task breakdown -->
  <div class="section-head">
    <span>Task completion</span>
    <span style="font-size:0.6rem;color:var(--text-dim)">% = done days ÷ total days</span>
  </div>
  <div class="prog-list" id="rp-task-list"></div>

  <!-- Per-day breakdown -->
  <div class="section-head">
    <span>Day completion</span>
    <span style="font-size:0.6rem;color:var(--text-dim)">% = done tasks ÷ total tasks</span>
  </div>
  <div class="day-grid" id="rp-day-grid"></div>

  <!-- Save week + history -->
  <div class="section-head">
    <span>Week history</span>
    <button class="save-week-btn" onclick="saveWeekSnapshot()">Save Week &amp; Reset Sheet</button>
  </div>
  <div id="rp-history"></div>
</div>

<div class="statusbar">
  <span>TASKS <b id="sb-tasks">0</b></span>
  <span>DAYS <b id="sb-days">0</b></span>
  <span>SELECTED <b id="sb-sel">0</b></span>
  <span style="margin-left:auto">Click task name to edit · Click priority dot to set · Click ✕/✓ to toggle</span>
</div>

<!-- Add Day Modal -->
<div class="modal-overlay" id="day-modal">
  <div class="modal">
    <h2>Add day column</h2>
    <div class="form-row">
      <label>Day of week</label>
      <select id="dm-day">
        <option value="Mon">Monday</option><option value="Tue">Tuesday</option>
        <option value="Wed">Wednesday</option><option value="Thu">Thursday</option>
        <option value="Fri">Friday</option><option value="Sat">Saturday</option>
        <option value="Sun">Sunday</option>
      </select>
    </div>
    <div class="form-row">
      <label>Date (optional)</label>
      <input type="date" id="dm-date">
    </div>
    <div class="modal-actions">
      <button class="btn btn-ghost" onclick="closeDayModal()" style="color:var(--text)">Cancel</button>
      <button class="btn btn-primary" onclick="saveDayColumn()">Add column</button>
    </div>
  </div>
</div>

<div class="notif" id="notif"></div>

<script>
// ── Stars ─────────────────────────────────────────────────
const starsEl = document.getElementById('stars');
for (let i = 0; i < 110; i++) {
  const s = document.createElement('div'); s.className = 'star';
  const sz = Math.random() * 2 + 0.4;
  Object.assign(s.style, { width:sz+'px', height:sz+'px', left:Math.random()*100+'%', top:Math.random()*100+'%',
    '--d':(Math.random()*3+1.2).toFixed(2)+'s', '--mo':(Math.random()*0.1+0.03).toFixed(2),
    animationDelay:(Math.random()*4).toFixed(2)+'s' });
  starsEl.appendChild(s);
}

// ── Constants ─────────────────────────────────────────────
const DAY_NAMES  = {Mon:'Monday',Tue:'Tuesday',Wed:'Wednesday',Thu:'Thursday',Fri:'Friday',Sat:'Saturday',Sun:'Sunday'};
const DAY_SHORT  = {Mon:'Mon',Tue:'Tue',Wed:'Wed',Thu:'Thu',Fri:'Fri',Sat:'Sat',Sun:'Sun'};
const PRIORITIES = ['Low','Medium','High','Critical'];

// ── Data model ────────────────────────────────────────────
// days:  [{id, day, date}]          — columns
// tasks: [{id, name, priority}]     — rows
// status: { taskId_dayId: 'done'|'pending' }
let days   = [];
let tasks  = [];
let status = {};
let selected = new Set();
let filterPriMode = 'all';

function uid() { return Math.random().toString(36).slice(2,10); }
function cellKey(tid, did) { return tid + '_' + did; }

function load() {
  try {
    const raw = JSON.parse(localStorage.getItem('ds4') || 'null');
    if (raw) { days = raw.days||[]; tasks = raw.tasks||[]; status = raw.status||{}; }
  } catch(e) {}
  if (!days.length && !tasks.length) seedData();
}
function save() { localStorage.setItem('ds4', JSON.stringify({days, tasks, status})); }

function seedData() {
  days = [
    {id:uid(), day:'Mon', date:'2026-03-30'},
    {id:uid(), day:'Tue', date:'2026-03-31'},
    {id:uid(), day:'Wed', date:'2026-04-01'},
    {id:uid(), day:'Thu', date:'2026-04-02'},
    {id:uid(), day:'Fri', date:'2026-04-03'},
  ];
  tasks = [
    {id:uid(), name:'Team standup meeting',   priority:'High'},
    {id:uid(), name:'Review pull requests',   priority:'Medium'},
    {id:uid(), name:'Update documentation',   priority:'Low'},
    {id:uid(), name:'Fix login page bug',     priority:'High'},
    {id:uid(), name:'Client call',            priority:'Critical'},
    {id:uid(), name:'Weekly report',          priority:'Low'},
  ];
  // seed some done statuses
  status[cellKey(tasks[0].id, days[0].id)] = 'done';
  status[cellKey(tasks[4].id, days[1].id)] = 'done';
  status[cellKey(tasks[3].id, days[2].id)] = 'done';
  save();
}

// ── Filter ────────────────────────────────────────────────
function filterPri(mode) {
  filterPriMode = mode;
  PRIORITIES.concat(['all']).forEach(p => {
    const el = document.getElementById('fp-'+p); if(el) el.classList.toggle('active', p===mode);
  });
  renderTable();
}

function getFilteredTasks() {
  const q = document.getElementById('search').value.toLowerCase().trim();
  return tasks.filter(t => {
    if (filterPriMode !== 'all' && t.priority !== filterPriMode) return false;
    if (q && !t.name.toLowerCase().includes(q)) return false;
    return true;
  });
}

// ── Render ────────────────────────────────────────────────
function renderTable() {
  const filteredTasks = getFilteredTasks();
  const thead = document.getElementById('thead');
  const tbody = document.getElementById('tbody');

  // ── Header row: checkbox | Task | Day cols...
  let hdr = `<tr>
    <th class="th-chk"><input type="checkbox" id="select-all" onchange="toggleSelectAll(this)"></th>
    <th class="th-task" style="border-right:1px solid rgba(0,240,255,0.15)">Task</th>`;
  days.forEach(d => {
    hdr += `<th class="th-day" onclick="promptRemoveDay('${d.id}')">
      <span class="day-pill-hdr dh-${d.day}">
        <span class="dot"></span>${DAY_SHORT[d.day]||d.day}
      </span>
      ${d.date ? `<span class="day-date">${formatDate(d.date)}</span>` : ''}
    </th>`;
  });
  // add-day th
  hdr += `<th style="padding:6px 10px;width:44px;text-align:center">
    <button class="add-day-btn" onclick="event.stopPropagation();openAddDayModal()" title="Add day column">+</button>
  </th>`;
  hdr += `</tr>`;
  thead.innerHTML = hdr;

  // ── Body rows: one per task
  if (!filteredTasks.length) {
    tbody.innerHTML = `<tr class="empty-row"><td colspan="${days.length+3}">No tasks yet — click "+ Add Task" to start</td></tr>`;
    stats(filteredTasks.length);
    return;
  }

  let rows = '';
  filteredTasks.forEach(task => {
    const isSel = selected.has(task.id);
    rows += `<tr class="task-row${isSel?' selected':''}" data-tid="${task.id}">
      <td class="td-chk">
        <input type="checkbox" ${isSel?'checked':''} onchange="toggleSelect('${task.id}',this)" onclick="event.stopPropagation()">
      </td>
      <td class="td-task" style="border-right:1px solid rgba(0,240,255,0.15)">
        <div class="task-inner">
          <div class="task-name-wrap">
            <input type="text" value="${esc(task.name)}" placeholder="Task name…"
              onchange="editTaskName('${task.id}',this.value)"
              onblur="editTaskName('${task.id}',this.value)">
            <button class="del-row-btn" onclick="deleteTask('${task.id}')" title="Delete task">✕</button>
          </div>
          <div class="pri-btns">
            ${PRIORITIES.map(p=>`
            <button class="pri-btn pb-${p}${task.priority===p?' active':''}"
              onclick="setPriority('${task.id}','${p}')">
              <span class="pdi"></span>${p}
            </button>`).join('')}
          </div>
        </div>
      </td>`;

    // Day status cells
    days.forEach(d => {
      const key = cellKey(task.id, d.id);
      const done = status[key] === 'done';
      rows += `<td class="td-day">
        <button class="tick-btn ${done?'tick-done':'tick-undone'}"
          onclick="toggleStatus('${task.id}','${d.id}',this)"
          title="${done?'Mark pending':'Mark done'}">
          ${done?'✓':'✕'}
        </button>
      </td>`;
    });

    rows += `<td style="padding:4px 6px"></td></tr>`;
  });

  // Add task row
  rows += `<tr class="add-task-row">
    <td colspan="${days.length+3}" style="padding:7px 14px">
      <button class="add-task-inline-btn" onclick="addTask()">+ add task</button>
    </td>
  </tr>`;

  tbody.innerHTML = rows;
  stats(filteredTasks.length);
}

function formatDate(d) {
  if (!d) return '';
  const dt = new Date(d+'T00:00:00');
  return dt.toLocaleDateString('en-GB',{day:'numeric',month:'short'});
}
function esc(s) { return String(s||'').replace(/&/g,'&amp;').replace(/"/g,'&quot;').replace(/</g,'&lt;'); }

function stats(visible) {
  document.getElementById('row-count').textContent = `${visible} task${visible!==1?'s':''}`;
  document.getElementById('sb-tasks').textContent = tasks.length;
  document.getElementById('sb-days').textContent  = days.length;
  document.getElementById('sb-sel').textContent   = selected.size;
}

// ── Edit task name ─────────────────────────────────────────
function editTaskName(tid, val) {
  const t = tasks.find(x=>x.id===tid); if(!t) return;
  t.name = val; save();
}

// ── Set priority ──────────────────────────────────────────
function setPriority(tid, pri) {
  const t = tasks.find(x=>x.id===tid); if(!t) return;
  t.priority = pri; save(); renderTable();
  notify('Priority → '+pri);
}

// ── Toggle status (tick/untick) ───────────────────────────
function toggleStatus(tid, did, btn) {
  const key = cellKey(tid, did);
  const nowDone = status[key] !== 'done';
  status[key] = nowDone ? 'done' : 'pending';
  save();
  btn.classList.remove('tick-done','tick-undone');
  btn.classList.add(nowDone ? 'tick-done' : 'tick-undone');
  btn.textContent = nowDone ? '✓' : '✕';
  btn.title = nowDone ? 'Mark pending' : 'Mark done';
  btn.classList.remove('pop');
  void btn.offsetWidth;
  btn.classList.add('pop');
  notify(nowDone ? '✓ Done' : '↩ Pending');
}

// ── Add / delete tasks ────────────────────────────────────
function addTask() {
  const t = {id:uid(), name:'', priority:'Medium'};
  tasks.push(t); save(); renderTable();
  setTimeout(()=>{
    const inputs = document.querySelectorAll('.task-name-wrap input[type="text"]');
    if (inputs.length) inputs[inputs.length-1].focus();
  },30);
}

function deleteTask(tid) {
  tasks = tasks.filter(t=>t.id!==tid);
  Object.keys(status).forEach(k=>{ if(k.startsWith(tid+'_')) delete status[k]; });
  selected.delete(tid); save(); renderTable(); notify('Task removed');
}

// ── Selection ─────────────────────────────────────────────
function toggleSelect(tid, cb) {
  if(cb.checked) selected.add(tid); else selected.delete(tid);
  const row = document.querySelector(`tr[data-tid="${tid}"]`);
  if(row) row.classList.toggle('selected', cb.checked);
  document.getElementById('sb-sel').textContent = selected.size;
}
function toggleSelectAll(cb) {
  getFilteredTasks().forEach(t=>{ if(cb.checked) selected.add(t.id); else selected.delete(t.id); });
  renderTable();
}
function deleteSelected() {
  if(!selected.size) { notify('Nothing selected'); return; }
  const count = selected.size;
  tasks = tasks.filter(t=>!selected.has(t.id));
  selected.forEach(tid=>Object.keys(status).forEach(k=>{ if(k.startsWith(tid+'_')) delete status[k]; }));
  selected.clear(); save(); renderTable();
  notify('Deleted '+count+' task'+(count>1?'s':''));
}

// ── Day columns ───────────────────────────────────────────
function openAddDayModal() {
  document.getElementById('dm-day').value = 'Mon';
  document.getElementById('dm-date').value = new Date().toISOString().slice(0,10);
  document.getElementById('day-modal').classList.add('open');
  setTimeout(()=>document.getElementById('dm-day').focus(), 60);
}
function closeDayModal() { document.getElementById('day-modal').classList.remove('open'); }
function saveDayColumn() {
  const day  = document.getElementById('dm-day').value;
  const date = document.getElementById('dm-date').value;
  days.push({id:uid(), day, date}); save(); closeDayModal(); renderTable();
  notify('Added ' + DAY_NAMES[day]);
}
function promptRemoveDay(did) {
  const d = days.find(x=>x.id===did); if(!d) return;
  if (!confirm(`Remove column "${DAY_NAMES[d.day]}"? Status data for this day will be lost.`)) return;
  days = days.filter(x=>x.id!==did);
  Object.keys(status).forEach(k=>{ if(k.endsWith('_'+did)) delete status[k]; });
  save(); renderTable(); notify('Day removed');
}

// ── Export CSV ────────────────────────────────────────────
function exportCSV() {
  const hdr = ['Task','Priority',...days.map(d=>(DAY_NAMES[d.day]||d.day)+(d.date?' ('+d.date+')':''))];
  const rows = tasks.map(t => {
    const cells = days.map(d => status[cellKey(t.id,d.id)]==='done'?'Done':'Pending');
    return [t.name, t.priority, ...cells].map(v=>`"${String(v).replace(/"/g,'""')}"`).join(',');
  });
  const a = document.createElement('a');
  a.href = 'data:text/csv;charset=utf-8,'+encodeURIComponent([hdr.join(','),...rows].join('\n'));
  a.download = (document.getElementById('sheet-title').value||'datasheet')+'.csv';
  a.click(); notify('CSV exported');
}

// ── Notify ────────────────────────────────────────────────
function notify(msg) {
  const n = document.getElementById('notif');
  n.textContent = msg; n.classList.add('show');
  clearTimeout(n._t); n._t = setTimeout(()=>n.classList.remove('show'), 1800);
}

// ── Modal close ───────────────────────────────────────────
document.getElementById('day-modal').addEventListener('click',function(e){if(e.target===this)closeDayModal();});
document.addEventListener('keydown',e=>{
  if(e.key==='Escape') closeDayModal();
  if((e.ctrlKey||e.metaKey)&&e.key==='Enter'&&document.getElementById('day-modal').classList.contains('open')) saveDayColumn();
});

// ── Tab switching ─────────────────────────────────────────
let currentTab = 'sheet';

function switchTab(tab) {
  currentTab = tab;
  document.getElementById('tab-sheet').classList.toggle('active', tab==='sheet');
  document.getElementById('tab-report').classList.toggle('active', tab==='report');
  document.getElementById('sheet-page').style.display   = tab==='sheet'  ? '' : 'none';
  document.getElementById('report-page').style.display  = tab==='report' ? 'block' : 'none';
  document.querySelector('.toolbar').style.display      = tab==='sheet'  ? '' : 'none';
  // header buttons
  ['btn-export','btn-addday','btn-addtask'].forEach(id=>{
    const el=document.getElementById(id); if(el) el.style.display = tab==='sheet'?'':'none';
  });
  if (tab==='report') renderReport();
}

// ── Report render ─────────────────────────────────────────
function renderReport() {
  const total = tasks.length * days.length;
  let doneCount = 0;
  tasks.forEach(t=>days.forEach(d=>{ if(status[cellKey(t.id,d.id)]==='done') doneCount++; }));
  const overallPct = total ? Math.round(doneCount/total*100) : 0;

  // update date range subtitle
  const allDates = days.map(d=>d.date).filter(Boolean).sort();
  document.getElementById('report-daterange').textContent =
    allDates.length >= 2
      ? `Week of ${formatDate(allDates[0])} — ${formatDate(allDates[allDates.length-1])}`
      : allDates.length === 1 ? `Date: ${formatDate(allDates[0])}` : 'Current week data';

  // Summary cards
  document.getElementById('rp-overall').textContent = overallPct + '%';
  document.getElementById('rp-overall-sub').textContent = doneCount + ' of ' + total + ' cells done';
  document.getElementById('rp-tasks').textContent = tasks.length;
  document.getElementById('rp-days').textContent  = days.length;

  // Best day
  let bestDay = null, bestPct = -1;
  days.forEach(d=>{
    const done = tasks.filter(t=>status[cellKey(t.id,d.id)]==='done').length;
    const pct  = tasks.length ? Math.round(done/tasks.length*100) : 0;
    if (pct > bestPct) { bestPct = pct; bestDay = d; }
  });
  document.getElementById('rp-best-day').textContent = bestDay ? (DAY_SHORT[bestDay.day]||bestDay.day) : '—';
  document.getElementById('rp-best-sub').textContent = bestDay ? bestPct+'% done' : 'no data';

  // Fully done tasks
  const fullDone = tasks.filter(t=>days.length>0 && days.every(d=>status[cellKey(t.id,d.id)]==='done')).length;
  document.getElementById('rp-full-tasks').textContent = fullDone;

  // ── Per-task bars ──
  const PRI_COLORS = {Low:'rgba(60,255,208,1)',Medium:'rgba(255,217,61,1)',High:'rgba(255,140,0,1)',Critical:'rgba(255,60,90,1)'};
  const PRI_GLOW   = {Low:'rgba(60,255,208,0.55)',Medium:'rgba(255,217,61,0.55)',High:'rgba(255,140,0,0.55)',Critical:'rgba(255,60,90,0.55)'};

  const taskList = document.getElementById('rp-task-list');
  if (!tasks.length) {
    taskList.innerHTML = '<div style="color:var(--text-dim);font-size:0.75rem;font-style:italic;padding:16px 0">No tasks in sheet</div>';
  } else {
    taskList.innerHTML = tasks.map(t=>{
      const doneDays = days.filter(d=>status[cellKey(t.id,d.id)]==='done').length;
      const pct = days.length ? Math.round(doneDays/days.length*100) : 0;
      const col   = PRI_COLORS[t.priority]||'var(--cyan)';
      const glow  = PRI_GLOW[t.priority]||'rgba(0,240,255,0.4)';
      const pctColor = pct===100?'#00ff78': pct>=50?'#ffd93d':'#ff3c5a';
      const dotsHtml = days.map(d=>{
        const done = status[cellKey(t.id,d.id)]==='done';
        return `<span class="prog-dot ${done?'pd-done':'pd-pend'}">
          <span class="di"></span>${DAY_SHORT[d.day]||d.day}${d.date?'<span style="opacity:0.5;margin-left:2px">'+formatDate(d.date)+'</span>':''}
        </span>`;
      }).join('');
      return `<div class="prog-row">
        <div class="prog-top">
          <span class="prog-name">${escHtml(t.name||'Untitled task')}</span>
          <span class="prog-right">
            <span class="prog-days">${doneDays}/${days.length} days</span>
            <span class="prog-pct" style="color:${pctColor};text-shadow:0 0 10px ${pctColor}66">${pct}%</span>
          </span>
        </div>
        <div class="prog-bar-track">
          <div class="prog-bar-fill" style="width:${pct}%;background:${col};box-shadow:0 0 8px ${glow}"></div>
        </div>
        ${days.length?`<div class="prog-dots">${dotsHtml}</div>`:''}
      </div>`;
    }).join('');
  }

  // ── Per-day bars ──
  const dayGrid = document.getElementById('rp-day-grid');
  if (!days.length) {
    dayGrid.innerHTML = '<div style="color:var(--text-dim);font-size:0.75rem;font-style:italic;padding:16px 0">No day columns in sheet</div>';
  } else {
    dayGrid.innerHTML = days.map(d=>{
      const doneTasks = tasks.filter(t=>status[cellKey(t.id,d.id)]==='done').length;
      const pct = tasks.length ? Math.round(doneTasks/tasks.length*100) : 0;
      const pctColor = pct===100?'#00ff78': pct>=50?'#ffd93d':'#ff3c5a';
      const DAY_COL = {Mon:'#3cffd0',Tue:'#7aacff',Wed:'#ffc76a',Thu:'#c49aff',Fri:'#5aff9a',Sat:'#ff8edb',Sun:'#ff8edb'};
      const col = DAY_COL[d.day]||'var(--cyan)';
      return `<div class="day-card">
        <div class="day-card-hdr">
          <span class="day-card-pill dh-${d.day}"><span class="dot"></span>${DAY_NAMES[d.day]||d.day}</span>
          ${d.date?`<span style="font-size:0.6rem;color:var(--text-dim)">${formatDate(d.date)}</span>`:''}
        </div>
        <div class="day-pct-big" style="color:${pctColor};text-shadow:0 0 14px ${pctColor}66">${pct}%</div>
        <div class="day-sub">${doneTasks} of ${tasks.length} tasks done</div>
        <div class="prog-bar-track">
          <div class="prog-bar-fill" style="width:${pct}%;background:${col};box-shadow:0 0 8px ${col}88"></div>
        </div>
      </div>`;
    }).join('');
  }

  // ── History ──
  renderHistory();
}

function escHtml(s){ return String(s||'').replace(/&/g,'&amp;').replace(/</g,'&lt;').replace(/>/g,'&gt;'); }

// ── Save week snapshot ────────────────────────────────────
function saveWeekSnapshot() {
  if (!tasks.length && !days.length) { notify('Nothing to save'); return; }

  // Build snapshot
  const allDates = days.map(d=>d.date).filter(Boolean).sort();
  const weekLabel = allDates.length >= 2
    ? formatDate(allDates[0])+' – '+formatDate(allDates[allDates.length-1])
    : allDates.length===1 ? formatDate(allDates[0]) : 'Week of '+new Date().toLocaleDateString('en-GB',{day:'numeric',month:'short'});

  const total = tasks.length * days.length;
  let doneCount = 0;
  const taskSnapshots = tasks.map(t=>{
    const doneDays = days.filter(d=>status[cellKey(t.id,d.id)]==='done').length;
    if(doneDays===days.length && days.length>0) doneCount += days.length;
    else doneCount += doneDays;
    return { name: t.name, priority: t.priority, doneDays, totalDays: days.length,
             pct: days.length?Math.round(doneDays/days.length*100):0 };
  });
  const overallPct = total ? Math.round(doneCount/total*100) : 0;

  const snap = {
    id: uid(),
    savedAt: new Date().toISOString(),
    weekLabel,
    overallPct,
    totalCells: total,
    doneCells: doneCount,
    tasks: taskSnapshots,
    dayLabels: days.map(d=>(DAY_NAMES[d.day]||d.day)+(d.date?' '+formatDate(d.date):''))
  };

  // Persist history
  let history = [];
  try { history = JSON.parse(localStorage.getItem('ds4_history')||'[]'); } catch(e){}
  history.unshift(snap);
  localStorage.setItem('ds4_history', JSON.stringify(history.slice(0,20)));

  // Reset sheet
  tasks=[]; days=[]; status={}; selected.clear();
  save();
  renderHistory();
  notify('Week saved! Sheet is now fresh.');
  // Stay on report tab
  renderReport();
}

// ── Render history ────────────────────────────────────────
function renderHistory() {
  let history = [];
  try { history = JSON.parse(localStorage.getItem('ds4_history')||'[]'); } catch(e){}

  const container = document.getElementById('rp-history');
  if (!history.length) {
    container.innerHTML = '<div class="hist-empty">No saved weeks yet — click "Save Week &amp; Reset Sheet" to archive this week\'s data.</div>';
    return;
  }

  container.innerHTML = '<div class="history-list">'+history.map((snap,i)=>{
    const pctColor = snap.overallPct===100?'#00ff78': snap.overallPct>=50?'#ffd93d':'#ff3c5a';
    const savedDate = new Date(snap.savedAt).toLocaleDateString('en-GB',{day:'numeric',month:'short',year:'numeric'});
    const taskChips = (snap.tasks||[]).map(t=>`
      <span class="hist-task-chip ${t.pct===100?'done':''}">
        ${escHtml(t.name||'Untitled')} ${t.pct}%
      </span>`).join('');
    return `<div class="hist-card">
      <div class="hist-hdr">
        <div>
          <div class="hist-week">${escHtml(snap.weekLabel)}</div>
          <div class="hist-meta">Saved ${savedDate} · ${snap.doneCells||0}/${snap.totalCells||0} cells done</div>
        </div>
        <div style="display:flex;align-items:center;gap:12px">
          <span class="hist-pct" style="color:${pctColor};text-shadow:0 0 12px ${pctColor}66">${snap.overallPct}%</span>
          <button class="del-hist-btn" onclick="deleteHistoryItem('${snap.id}')" title="Remove">✕</button>
        </div>
      </div>
      <div class="prog-bar-track" style="margin-bottom:8px">
        <div class="prog-bar-fill" style="width:${snap.overallPct}%;background:${pctColor};box-shadow:0 0 8px ${pctColor}66"></div>
      </div>
      <div class="hist-tasks">${taskChips}</div>
    </div>`;
  }).join('')+'</div>';
}

function deleteHistoryItem(id) {
  let history = [];
  try { history = JSON.parse(localStorage.getItem('ds4_history')||'[]'); } catch(e){}
  history = history.filter(h=>h.id!==id);
  localStorage.setItem('ds4_history', JSON.stringify(history));
  renderHistory();
  notify('History entry removed');
}

load();
renderTable();
</script>
</body>
</html>
