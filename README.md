# CooperCar — Gestão do Veículo

Protótipo navegável para apresentar à diretoria da CooperCar uma proposta de aplicativo para associados. Tem duas áreas, que você alterna pela barra superior:

- **App do associado:** Início, Meu veículo, Registrar acontecimento, Histórico e Minha CooperCar.
- **Painel administrativo:** visão geral com indicadores, lista de associados com pesquisa e filtros, e detalhes de cada associado.

> Demonstração com dados fictícios. Não há backend, login real, integrações nem dados de associados reais.

## Como abrir

Abra o `index.html` no navegador. Não precisa instalar nada. A fonte (Archivo) vem do Google Fonts; sem internet, o navegador usa a fonte do sistema.

Para publicar no GitHub Pages: **Settings → Pages → Deploy from a branch → `main` / root**.

## Dados da demonstração

- O que for criado durante a demo fica salvo só no navegador de quem estiver usando, na chave `coopercar-demo:v1`, separada de qualquer dado real.
- O botão de reiniciar (↻) na barra superior apaga as alterações e volta aos dados iniciais.
- As datas dos registros de exemplo são calculadas a partir do dia em que a página é aberta, então a demo continua coerente em qualquer data.

## O que ajustar quando houver definições oficiais

| Item | Onde |
|---|---|
| Cores provisórias | Tokens em `:root` no início do `<style>` (tema claro) e os dois blocos de tema escuro logo abaixo |
| Logotipo tipográfico | Elementos com a classe `.logo` |
| Canal de contato | `CONFIG.contato` no início do `<script>`, por exemplo `{ rotulo: 'WhatsApp da CooperCar', url: 'https://...' }` |
| Associados fictícios do painel | Lista `MEMBERS` no script |
