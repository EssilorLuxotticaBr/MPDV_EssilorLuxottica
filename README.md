Formulário de Solicitação de MPDV
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=5.0, user-scalable=yes">
  <title>SOLICITAÇÃO DE MPDV</title>
  <style>
    :root { --bg: #121212; --card: #1e1e1e; --border: #333; --text: #fff; --text-muted: #aaa; --input-bg: #2a2a2a; --accent: #fff; }
    * { margin: 0; padding: 0; box-sizing: border-box; -webkit-tap-highlight-color: transparent; }
    body { font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif; background-color: var(--bg); color: var(--text); padding: 16px; min-height: 100vh; }
    .container { max-width: 600px; margin: 0 auto; background-color: var(--card); border-radius: 12px; padding: 20px; box-shadow: 0 4px 12px rgba(0,0,0,0.3); position: relative; }
    .logo { position: absolute; top: 20px; right: 20px; width: 90px; height: auto; }
    h1 { font-size: 20px; margin-bottom: 8px; padding-right: 100px; line-height: 1.3; }
    .subtitle { font-size: 13px; color: var(--text-muted); margin-bottom: 24px; padding-right: 100px; }
    .form-group { margin-bottom: 16px; }
    label { display: block; font-size: 12px; font-weight: 600; color: var(--text-muted); margin-bottom: 8px; text-transform: uppercase; letter-spacing: 0.5px; }
    input, select { width: 100%; height: 48px; padding: 0 12px; font-size: 16px; background-color: var(--input-bg); border: 1px solid var(--border); border-radius: 8px; color: var(--text); appearance: none; -webkit-appearance: none; -moz-appearance: none; }
    .select-wrapper { position: relative; }
    .select-wrapper::after { content: ''; position: absolute; right: 16px; top: 50%; transform: translateY(-50%); width: 0; height: 0; border-left: 5px solid transparent; border-right: 5px solid transparent; border-top: 5px solid #fff; pointer-events: none; }
    input:focus, select:focus { outline: 2px solid #666; background-color: #333; }
    select:disabled, input[readonly] { opacity: 0.5; background-color: #1a1a1a; color: #777; }
    .grid { display: grid; grid-template-columns: 1fr; gap: 16px; }
    @media (min-width: 480px) { .grid { grid-template-columns: 1fr 1fr; } }
    button { width: 100%; height: 52px; margin-top: 24px; background-color: var(--accent); color: #000; font-size: 16px; font-weight: 700; border: none; border-radius: 8px; text-transform: uppercase; cursor: pointer; }
    button:active { transform: scale(0.98); background-color: #ddd; }
    button:disabled { opacity: 0.6; cursor: not-allowed; }
    .msg { display: none; margin-top: 16px; padding: 14px; border-radius: 8px; font-size: 14px; text-align: center; line-height: 1.4; }
    .msg.show { display: block; }
    .msg.success { background: #1b3a1b; color: #4ade80; border: 1px solid #2f5f2f; }
    .msg.error { background: #3a1b1b; color: #f87171; border: 1px solid #5f2f2f; }
    .msg.loading { background: #1a2a3a; color: #60a5fa; border: 1px solid #2a3a4a; }
    .hint { margin-top: 16px; font-size: 12px; color: #666; background: #1a1a1a; padding: 10px; border-radius: 6px; border: 1px dashed #444; }
  </style>
</head>
<body>
<div class="container">
  <img src="data:image/jpeg;base64,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" alt="Logo" class="logo">
  <h1>SOLICITAÇÃO DE MPDV</h1>
  <p class="subtitle">Mala selecionada filtra Marcas e Responsáveis.</p>
  <form id="form" novalidate>
    <div class="form-group">
      <label for="clifor">Clifor *</label>
      <input type="text" id="clifor" required placeholder="Digite o nome...">
    </div>
    <div class="grid">
      <div class="form-group">
        <label for="mala">Mala *</label>
        <div class="select-wrapper">
          <select id="mala" required>
            <option value="">Selecione...</option>
          </select>
        </div>
      </div>
      <div class="form-group">
        <label for="responsavel">Responsável *</label>
        <div class="select-wrapper">
          <select id="responsavel" required disabled>
            <option value="">Aguardando mala...</option>
          </select>
        </div>
      </div>
    </div>
    <div class="grid">
      <div class="form-group">
        <label for="marca">Marca *</label>
        <div class="select-wrapper">
          <select id="marca" required disabled>
            <option value="">Aguardando mala...</option>
          </select>
        </div>
      </div>
      <div class="form-group">
        <label for="material">Material *</label>
        <div class="select-wrapper">
          <select id="material" required disabled>
            <option value="">Aguardando marca...</option>
          </select>
        </div>
      </div>
    </div>
    <div class="form-group">
      <label for="codigo">Código do Material</label>
      <input type="text" id="codigo" readonly placeholder="-">
    </div>
    <div class="form-group">
      <label for="quantidade">Quantidade *</label>
      <input type="number" id="quantidade" min="1" required placeholder="0">
    </div>
    
    <!-- PDF CATALOG BUTTON -->
    <a id="btnCatalogo" href="#" style="display: block; width: 100%; height: 52px; line-height: 52px; text-align: center; margin-top: 16px; background-color: #2c2c2e; color: #fff; font-size: 16px; font-weight: 700; border: none; border-radius: 8px; text-transform: uppercase; text-decoration: none; cursor: pointer;">
