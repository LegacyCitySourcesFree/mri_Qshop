<h1 align="center">🛒 Legacy Shops — MRI Qbox (QBX Core)</h1>

<p align="center">
Sistema de lojas completo, moderno e totalmente configurável in-game, criado para servidores FiveM que utilizam o framework <b>MRI Qbox / qbx_core</b>.
</p>

<hr>

<h2>📷 Demonstração</h2>

<p><b>Painel Administrativo dentro da loja</b></p>
<img src="https://i.imgur.com/PLACEHOLDER1.png" width="100%">

<p><b>Interface da Loja para os jogadores</b></p>
<img src="https://i.imgur.com/PLACEHOLDER2.png" width="100%">

<blockquote>
Substitua os links acima pelas screenshots reais do seu projeto no GitHub.
</blockquote>

<hr>

<h2>✨ Sobre o Projeto</h2>

<p>
O <b>Legacy Shops</b> foi desenvolvido para permitir que qualquer administrador crie, edite e gerencie lojas diretamente pelo jogo,
sem necessidade de mexer em arquivos ou reiniciar scripts.
</p>

<p>
Cada loja é totalmente independente, com seus próprios itens, preços, imagens, NPC, localização e configurações.
Tudo é salvo automaticamente em JSON e carregado em tempo real.
</p>

<hr>

<h2>⚙️ Funcionalidades</h2>

<ul>
  <li>🧩 Lojas ilimitadas e independentes</li>
  <li>🖼️ Itens com imagem via URL</li>
  <li>🛠️ Painel Admin dentro da própria loja (NUI)</li>
  <li>🔐 Acesso ao painel por permissão ACE ou permissão do QBX</li>
  <li>📍 Definição de coordenadas e NPC direto pelo painel</li>
  <li>➕ Adicionar / remover / editar itens em tempo real</li>
  <li>💰 Sistema de compra seguro via servidor</li>
  <li>🎯 Integração com ox_target</li>
  <li>💾 Salvamento persistente em JSON (sem necessidade de SQL)</li>
  <li>🎨 UI moderna, leve, responsiva e otimizada</li>
  <li>♻️ Atualização automática das lojas para todos os jogadores</li>
</ul>

<hr>

<h2>🧠 Como Funciona</h2>

<ol>
  <li>O jogador interage com o NPC via <b>ox_target</b></li>
  <li>A interface da loja abre com os itens configurados</li>
  <li>Admins visualizam a aba <b>Admin</b> automaticamente</li>
  <li>Pelo painel é possível criar novas lojas, editar itens e salvar tudo em tempo real</li>
</ol>

<hr>

<h2>🚀 Instalação</h2>

<pre>
1. Coloque a pasta "legacy_shops" em resources
2. Adicione: ensure legacy_shops no server.cfg
3. Configure a permissão ACE (opcional)
4. Inicie o servidor
</pre>

<h3>Permissão ACE (opcional)</h3>

<pre>
add_ace group.admin legacyshops.admin allow
</pre>

<hr>

<h2>🕹️ Como Usar</h2>

<h3>Para jogadores</h3>
<ul>
  <li>Vá até o NPC da loja</li>
  <li>Interaja via ox_target</li>
  <li>Escolha o item e compre</li>
</ul>

<h3>Para administradores</h3>
<ul>
  <li>Acesse a loja</li>
  <li>Entre na aba <b>Admin</b></li>
  <li>Crie novas lojas</li>
  <li>Adicione itens com nome, label, preço e imagem</li>
  <li>Defina as coordenadas do NPC</li>
  <li>Clique em <b>Salvar</b></li>
</ul>

<hr>

<h2>📁 Estrutura</h2>

<pre>
legacy_shops/
 ├─ client.lua
 ├─ server.lua
 ├─ config.lua
 ├─ data/shops.json
 └─ html/
</pre>

<hr>

<h2>🔒 Segurança</h2>

<ul>
  <li>Validação de compra feita 100% no servidor</li>
  <li>Proteção contra exploits de NUI</li>
  <li>Permissões verificadas antes de abrir painel admin</li>
</ul>

<hr>

<h2>🧭 Próximas melhorias</h2>

<ul>
  <li>🗂️ Categorias de itens dentro da loja</li>
  <li>🔎 Sistema de busca mais avançado</li>
  <li>🖌️ Upload de imagens direto pelo painel</li>
  <li>📦 Integração nativa com ox_inventory metadata</li>
  <li>📊 Log de compras para administração</li>
  <li>💳 Suporte a múltiplas formas de pagamento (cash, bank, item, crypto)</li>
</ul>

<hr>

<h2 align="center">🏙️ Desenvolvido pela Legacy City</h2>
<p align="center">Um sistema profissional, prático e pensado para facilitar a gestão das lojas do seu servidor.</p>
