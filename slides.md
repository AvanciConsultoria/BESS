---
theme: seriph
title: Storage at the Edge — Distributed BESS in Brazil
info: |
  Seminário técnico sobre o artigo Storage at the edge: Distributed BESS as a technical and regulatory solution for Brazil's energy transition.
  Estrutura: problema, metodologia, resultados, avaliação crítica e conexão com a disciplina.
class: text-left
transition: slide-left
mdc: true
drawings:
  persist: false
css: style.css
---

<div class="kicker">PPGSE — Integração de Sistemas de Armazenamento de Energia ao SEP</div>

# Storage at the Edge

<div class="hero-subtitle mt-4">
Distributed BESS as a technical and regulatory solution for Brazil's energy transition
</div>

<div class="grid-3 mt-10">
  <div class="card"><div class="metric-small">BESS</div><div class="caption mt-2">Battery Energy Storage Systems</div></div>
  <div class="card"><div class="metric-small">SIN</div><div class="caption mt-2">Sistema Interligado Nacional</div></div>
  <div class="card"><div class="metric-small">GD FV</div><div class="caption mt-2">Geração distribuída fotovoltaica</div></div>
</div>

<div class="bess-footer"><span>Artigo: Susteras, Almeida & Salles — Energy Policy, 2026</span><span>Seminário técnico</span></div>

---
layout: two-cols
---

# 1. Por que este artigo importa?

A expansão da geração distribuída fotovoltaica no Brasil deixou de ser apenas uma história de crescimento da fonte solar.

Ela passou a ser também uma história de **operação do sistema elétrico**.

<div class="callout mt-5">
O problema central deixou de ser apenas gerar energia renovável. O novo desafio é absorver essa energia com segurança, flexibilidade e sinal econômico adequado.
</div>

::right::

<div class="dark-card">
<h2>Três tensões sistêmicas</h2>

- Excesso de geração solar em determinados horários
- Rampa acentuada ao entardecer
- Sinal econômico desalinhado com a necessidade operativa

</div>

<div class="mt-5 card">
<span class="tag">Mensagem-chave</span>
<p class="mt-3">BESS é apresentado como recurso técnico, econômico e regulatório para coordenar flexibilidade distribuída.</p>
</div>

---

# 2. O crescimento da GD no Brasil

<div class="grid-2 mt-4">
<div class="figure-box">
<img src="/article/gr2.jpg" class="figure-xl" onerror="this.style.display='none'; this.parentElement.innerHTML='<div class=metric>+9,98 GW</div><p>Maior acréscimo anual de GD no período observado: 2024.</p><p class=caption>Substitua por public/article/gr2.jpg</p>'" />
</div>
<div class="figure-box">
<img src="/article/gr3.jpg" class="figure-xl" onerror="this.style.display='none'; this.parentElement.innerHTML='<div class=metric>41,5 GW</div><p>Capacidade acumulada aproximada de GD ao final do 1º semestre de 2025.</p><p class=caption>Substitua por public/article/gr3.jpg</p>'" />
</div>
</div>

<div class="mt-4 grid-3">
<div class="card"><span class="tag-green">Causa</span><p class="mt-2">Net metering e expansão acelerada da geração distribuída.</p></div>
<div class="card"><span class="tag-orange">Efeito</span><p class="mt-2">Fluxos reversos, sobretensão local e curtailment.</p></div>
<div class="card"><span class="tag-red">Desafio</span><p class="mt-2">Falta de coordenação de flexibilidade distribuída.</p></div>
</div>

---

# 3. Da geração solar ao problema operacional

<div class="timeline mt-6">
<div class="step"><b>GD FV cresce</b><br><span class="caption">Expansão distribuída</span></div>
<div class="step"><b>Geração diurna ↑</b><br><span class="caption">Oferta concentrada</span></div>
<div class="step"><b>Carga líquida ↓</b><br><span class="caption">Duck curve</span></div>
<div class="step"><b>Rampa ↑</b><br><span class="caption">Entardecer crítico</span></div>
<div class="step"><b>Curtailment</b><br><span class="caption">Energia renovável desperdiçada</span></div>
</div>

<div class="grid-2 mt-8">
<div class="card">
<h3>Problema técnico</h3>
<p>O sistema precisa equilibrar geração e carga em tempo real, mas a GD FV reduz a carga líquida no meio do dia e exige maior flexibilidade ao final da tarde.</p>
</div>
<div class="card">
<h3>Problema econômico-regulatório</h3>
<p>Os sinais de preço e tarifa nem sempre induzem o comportamento ótimo para o sistema, mesmo quando existe benefício técnico.</p>
</div>
</div>

---

# 4. Duck curve e curtailment no SIN

<div class="figure-box mt-2">
<img src="/article/gr4.jpg" class="figure-xl" onerror="this.style.display='none'; this.parentElement.innerHTML='<h2>Duck curve brasileira</h2><p>Insira public/article/gr4.jpg para exibir as curvas de carga bruta, carga líquida e curtailment médio por tipo de dia.</p>'" />
</div>

<div class="grid-3 mt-4">
<div class="card"><b>Carga bruta</b><p class="caption mt-2">Inclui a geração presumida da GD.</p></div>
<div class="card"><b>Carga líquida</b><p class="caption mt-2">É a carga vista pelo operador após a contribuição da GD.</p></div>
<div class="card"><b>Curtailment</b><p class="caption mt-2">Energia renovável disponível, mas não aproveitada pelo sistema.</p></div>
</div>

---

# 5. Lacuna científica

<div class="grid-2 mt-6">
<div class="card">
<h3>O que já se sabe</h3>
<ul>
<li>BESS pode deslocar energia no tempo.</li>
<li>BESS pode suavizar rampas e reduzir picos.</li>
<li>BESS pode prestar serviços ancilares.</li>
</ul>
</div>
<div class="warning">
<h3>O que faltava demonstrar</h3>
<ul>
<li>Qual estratégia distribuída é mais efetiva no contexto brasileiro?</li>
<li>O sinal econômico atual remunera o valor sistêmico?</li>
<li>O marco regulatório permite monetizar a flexibilidade?</li>
</ul>
</div>
</div>

<div class="callout mt-6">
<b>Pergunta central:</b> como BESS distribuídos podem reduzir curtailment e rampas no SIN, e por que a viabilidade depende de desenho regulatório?
</div>

---

# 6. Objetivo e contribuição do artigo

<div class="grid-3 mt-5">
<div class="card"><div class="metric-small">1</div><h3>Benchmark empírico</h3><p>Dados reais do SIN e avaliação de desempenho de BESS em contexto de alta GD.</p></div>
<div class="card"><div class="metric-small">2</div><h3>Diagnóstico econômico</h3><p>Mostra desalinhamento entre preço, tarifa e necessidade operativa.</p></div>
<div class="card"><div class="metric-small">3</div><h3>Lacunas regulatórias</h3><p>Identifica mudanças necessárias para liberar flexibilidade distribuída.</p></div>
</div>

<div class="dark-card mt-6">
<h2>Tese do artigo</h2>
<p>BESS distribuídos são tecnicamente capazes de mitigar curtailment, mas sua adoção depende de compatibilidade econômica e reconhecimento regulatório.</p>
</div>

---

# 7. Metodologia geral

<div class="timeline mt-4">
<div class="step"><b>Dados reais</b><br><span class="caption">ONS, CCEE, ANEEL</span></div>
<div class="step"><b>Curvas horárias</b><br><span class="caption">Jul/2024 a Jun/2025</span></div>
<div class="step"><b>Três estratégias</b><br><span class="caption">BESS distribuído</span></div>
<div class="step"><b>Simulação</b><br><span class="caption">Janelas fixas</span></div>
<div class="step"><b>Avaliação</b><br><span class="caption">Técnica, econômica e regulatória</span></div>
</div>

<table class="table-clean mt-6">
<tr><th>Parâmetro</th><th>Assunção</th><th>Comentário</th></tr>
<tr><td>Resolução</td><td>Horária</td><td>Compatível com ONS/CCEE</td></tr>
<tr><td>Horizonte</td><td>12 meses</td><td>Jul/2024 a Jun/2025</td></tr>
<tr><td>Relação E/P</td><td>3 horas</td><td>Energia nominal equivalente a 3h de potência</td></tr>
<tr><td>Eficiência round-trip</td><td>90%</td><td>Típica para Li-ion</td></tr>
<tr><td>Ciclagem</td><td>1 ciclo/dia</td><td>Caso de energy shifting</td></tr>
</table>

---

# 8. Estratégias avaliadas

<div class="grid-3 mt-5">
<div class="card">
<span class="tag">Estratégia 1</span>
<h3>Standalone BESS</h3>
<p>Bateria como agente independente, interagindo com sinal de preço no atacado.</p>
</div>
<div class="card">
<span class="tag-green">Estratégia 2</span>
<h3>Behind-the-meter</h3>
<p>Bateria em consumidores BT, deslocando consumo conforme sinal da tarifa branca.</p>
</div>
<div class="card">
<span class="tag-orange">Estratégia 3</span>
<h3>BESS + GD FV</h3>
<p>Bateria junto à geração FV remota, deslocando injeção para o horário de maior valor.</p>
</div>
</div>

<div class="callout mt-8">
As estratégias representam três loci de controle: mercado, consumidor e gerador distribuído.
</div>

---

# 9. Estratégia 1 — Standalone BESS

<div class="grid-2 mt-4">
<div>
<h2>Hipótese operacional</h2>
<ul>
<li>Carregar quando há excesso ou preço baixo.</li>
<li>Descarregar no pico do sistema.</li>
<li>Atuar como ativo modular e despachável.</li>
</ul>
<div class="eq mt-5">
$$R = \sum_t P_{desc,t}\cdot PLD_t - \sum_t P_{carga,t}\cdot PLD_t$$
</div>
</div>
<div class="figure-box">
<img src="/article/gr5.jpg" class="figure-xl" onerror="this.style.display='none'; this.parentElement.innerHTML='<h2>Ciclo esperado do BESS</h2><p>Insira public/article/gr5.jpg</p>'" />
</div>
</div>

---

# 10. Estratégia 1 — desalinhamento preço × sistema

<div class="grid-2 mt-3">
<div class="figure-box">
<img src="/article/gr6.jpg" class="figure-xl" onerror="this.style.display='none'; this.parentElement.innerHTML='<h2>Fluxo ideal vs fluxo econômico</h2><p>Insira public/article/gr6.jpg</p>'" />
</div>
<div>
<h2>Resultado conceitual</h2>
<p>O ciclo economicamente otimizado por PLD não coincide necessariamente com o ciclo que mais reduz curtailment ou rampa.</p>
<div class="warning mt-5">
<b>Diagnóstico:</b> preço de mercado não internaliza integralmente o valor sistêmico da flexibilidade.
</div>
<div class="card mt-5"><span class="metric-small">BRL 82/MWh</span><p class="caption mt-2">Spread médio observado no estudo, insuficiente para viabilizar o investimento no cenário base.</p></div>
</div>
</div>

---

# 11. Estratégia 1 — resultado técnico

<div class="grid-2 mt-4">
<div class="figure-box">
<img src="/article/gr7.jpg" class="figure-xl" onerror="this.style.display='none'; this.parentElement.innerHTML='<h2>Resultado Strategy 1</h2><p>Insira public/article/gr7.jpg</p>'" />
</div>
<div>
<div class="metric">69%</div>
<h2>redução média de curtailment</h2>
<p>O artigo estima que até <b>72,5 GWh / 18,2 GW</b> de BESS poderiam ser inseridos antes de deslocar o curtailment para a madrugada.</p>
<div class="callout mt-5">Tecnicamente é a estratégia mais forte, mas regulatoriamente é a menos madura no Brasil.</div>
</div>
</div>

---

# 12. Estratégia 2 — Behind-the-meter BESS

<div class="grid-2 mt-4">
<div>
<h2>Objetivo</h2>
<p>Deslocar consumo de baixa tensão do horário de ponta para o período de maior disponibilidade solar.</p>
<ul>
<li>Carga: 7h–14h</li>
<li>Descarga: 17h–22h</li>
<li>Base econômica: tarifa branca</li>
</ul>
</div>
<div class="figure-box">
<img src="/article/gr8.jpg" class="figure-xl" onerror="this.style.display='none'; this.parentElement.innerHTML='<h2>Ciclo BESS — Tarifa Branca</h2><p>Insira public/article/gr8.jpg</p>'" />
</div>
</div>

---

# 13. Estratégia 2 — por que baixa tensão?

<div class="grid-2 mt-3">
<div class="figure-box">
<img src="/article/gr9.jpg" class="figure-xl" onerror="this.style.display='none'; this.parentElement.innerHTML='<h2>Curva típica BT</h2><p>Insira public/article/gr9.jpg</p>'" />
</div>
<div class="figure-box">
<img src="/article/gr10.jpg" class="figure-xl" onerror="this.style.display='none'; this.parentElement.innerHTML='<h2>Curva típica MT</h2><p>Insira public/article/gr10.jpg</p>'" />
</div>
</div>

<div class="callout mt-4">
Consumidores BT tendem a concentrar carga no fim do dia; consumidores MT já consomem mais durante o dia. Portanto, a flexibilidade marginal está mais presente na baixa tensão.
</div>

---

# 14. Estratégia 2 — resultados e limitação

<div class="grid-2 mt-4">
<div class="figure-box">
<img src="/article/gr11.jpg" class="figure-xl" onerror="this.style.display='none'; this.parentElement.innerHTML='<h2>Resultado Strategy 2</h2><p>Insira public/article/gr11.jpg</p>'" />
</div>
<div>
<div class="metric">33%</div>
<h2>redução média de curtailment</h2>
<p>Capacidade simulada: <b>40,0 GWh / 8,6 GW</b>.</p>
<div class="warning mt-5"><b>Limitação:</b> o carregamento pode aumentar a demanda individual observada, exigindo coordenação para evitar novo pico local.</div>
</div>
</div>

---

# 15. Estratégia 2 — restrição operacional individual

<div class="grid-2 mt-4">
<div class="figure-box">
<img src="/article/gr12.jpg" class="figure-xl" onerror="this.style.display='none'; this.parentElement.innerHTML='<h2>Limitação de carga BT</h2><p>Insira public/article/gr12.jpg</p>'" />
</div>
<div>
<h2>Trade-off técnico</h2>
<p>Limitar a potência de carga reduz o impacto sobre a demanda individual, mas pode deslocar o carregamento para horários menos efetivos contra o curtailment.</p>
<div class="card mt-5"><b>Aprendizado:</b> flexibilidade distribuída precisa de agregação, sinal econômico e coordenação.</div>
</div>
</div>

---

# 16. Estratégia 3 — BESS associado à GD FV

<div class="grid-2 mt-4">
<div>
<h2>Objetivo</h2>
<p>Deslocar a injeção de energia FV de períodos de excesso para períodos de maior demanda e maior valor tarifário.</p>
<ul>
<li>BESS co-localizado com geração remota</li>
<li>Carga durante geração solar</li>
<li>Descarga entre 18h e 21h</li>
</ul>
</div>
<div class="figure-box">
<img src="/article/gr13.jpg" class="figure-xl" onerror="this.style.display='none'; this.parentElement.innerHTML='<h2>Energy shifting FV</h2><p>Insira public/article/gr13.jpg</p>'" />
</div>
</div>

---

# 17. Estratégia 3 — resultado técnico

<div class="grid-2 mt-4">
<div class="figure-box">
<img src="/article/gr14.jpg" class="figure-xl" onerror="this.style.display='none'; this.parentElement.innerHTML='<h2>Resultado Strategy 3</h2><p>Insira public/article/gr14.jpg</p>'" />
</div>
<div>
<div class="metric">21%</div>
<h2>redução média de curtailment</h2>
<p>Capacidade simulada: <b>18,0 GWh / 6,0 GW</b>.</p>
<div class="callout mt-5">Menor impacto sistêmico, mas maior compatibilidade regulatória com o arcabouço de compensação de créditos.</div>
</div>
</div>

---

# 18. Estratégia 3 — arbitragem regulatória por créditos

<div class="grid-2 mt-4">
<div class="figure-box">
<img src="/article/gr15.jpg" class="figure-xl" onerror="this.style.display='none'; this.parentElement.innerHTML='<h2>Créditos de energia</h2><p>Insira public/article/gr15.jpg</p>'" />
</div>
<div>
<h2>Sinal econômico</h2>
<p>No regime de compensação, a injeção em horário de ponta pode gerar crédito energético superior para consumo fora de ponta.</p>
<div class="card mt-5"><span class="metric-small">~1,6 MWh</span><p class="caption mt-2">Crédito fora de ponta para cada 1 MWh injetado em ponta, conforme interpretação regulatória discutida no artigo.</p></div>
</div>
</div>

---

# 19. Comparação técnica das estratégias

<table class="table-clean mt-5">
<tr><th>Estratégia</th><th>Capacidade simulada</th><th>Redução de curtailment</th><th>Leitura técnica</th></tr>
<tr><td>Standalone BESS</td><td>72,5 GWh / 18,2 GW</td><td><b>69%</b></td><td>Maior impacto sistêmico</td></tr>
<tr><td>BT behind-the-meter</td><td>40,0 GWh / 8,6 GW</td><td><b>33%</b></td><td>Boa aderência à modulação de carga</td></tr>
<tr><td>BESS + GD FV</td><td>18,0 GWh / 6,0 GW</td><td><b>21%</b></td><td>Menor escala, maior compatibilidade regulatória</td></tr>
</table>

<div class="dark-card mt-7">
<h2>Resultado central</h2>
<p>O BESS funciona tecnicamente. O bloqueio está na viabilidade econômica e no desenho regulatório.</p>
</div>

---

# 20. Comparação técnico-econômico-regulatória

<table class="table-clean mt-4">
<tr><th>Estratégia</th><th>Técnica</th><th>Economia</th><th>Regulação</th></tr>
<tr><td>Standalone BESS</td><td>Alta</td><td>Nula / incerta</td><td>Sem reconhecimento como agente</td></tr>
<tr><td>BESS BT</td><td>Moderada</td><td>Baixa</td><td>Permitida ao consumidor</td></tr>
<tr><td>BESS + GD FV</td><td>Média</td><td>Média com ajustes</td><td>Compatível com net metering</td></tr>
</table>

<div class="grid-3 mt-7">
<div class="card"><span class="tag-green">Técnica</span><p class="mt-2">A tecnologia entrega flexibilidade.</p></div>
<div class="card"><span class="tag-orange">Economia</span><p class="mt-2">CAPEX e spreads ainda limitam retorno.</p></div>
<div class="card"><span class="tag-red">Regulação</span><p class="mt-2">O marco precisa reconhecer o valor sistêmico.</p></div>
</div>

---

# 21. Sensibilidades econômicas

<div class="grid-3 mt-5">
<div class="card"><h3>Estratégia 1</h3><p>Spread médio observado: <b>BRL 82/MWh</b>.</p><p>Viabilidade requer aproximadamente <b>BRL 320/MWh</b> e CAPEX muito inferior ao atual.</p></div>
<div class="card"><h3>Estratégia 2</h3><p>Tarifa branca atual: diferencial de cerca de <b>BRL 150/MWh</b>.</p><p>Viabilidade requer diferencial próximo de <b>BRL 300/MWh</b>.</p></div>
<div class="card"><h3>Estratégia 3</h3><p>Com regra em fins de semana e feriados, ROI melhora sensivelmente.</p><p>Com CAPEX de <b>BRL 1000/kWh</b> e razão ponta/fora ponta 2, ROI supera hurdle rate.</p></div>
</div>

<div class="warning mt-6">O ponto crítico não é apenas o custo da bateria. É a ausência de um sinal que remunere o serviço sistêmico.</div>

---

# 22. Conexão com a disciplina

<table class="table-clean mt-5">
<tr><th>Conteúdo da disciplina</th><th>Como aparece no artigo</th></tr>
<tr><td>Introdução aos ESS</td><td>BESS como recurso de segurança energética, flexibilidade e integração renovável</td></tr>
<tr><td>Tecnologias de baterias</td><td>Hipótese de Li-ion, eficiência de 90%, vida útil e ciclagem diária</td></tr>
<tr><td>Modelagem</td><td>Representação agregada por janelas fixas de carga e descarga</td></tr>
<tr><td>Aplicações no SEP</td><td>Peak shaving, ramp control, energy shifting, curtailment mitigation</td></tr>
<tr><td>Dimensionamento</td><td>Relação energia/potência de 3h e restrições de capacidade por estratégia</td></tr>
<tr><td>Estado de carga</td><td>Operação depende de SOC disponível para absorção e descarga</td></tr>
</table>

---

# 23. Avaliação crítica do artigo

<div class="grid-2 mt-5">
<div class="card">
<h3>Pontos fortes</h3>
<ul>
<li>Dados reais do SIN, CCEE e ANEEL.</li>
<li>Foco em contexto brasileiro.</li>
<li>Avaliação técnica, econômica e regulatória integrada.</li>
<li>Resultados quantitativos claros.</li>
</ul>
</div>
<div class="warning">
<h3>Limitações</h3>
<ul>
<li>Não modela fluxo de potência locacional.</li>
<li>Não avalia proteção, tensão e frequência em detalhe.</li>
<li>Não modela degradação explicitamente.</li>
<li>Usa janelas fixas, não otimização dinâmica.</li>
</ul>
</div>
</div>

---

# 24. O que eu defenderia no seminário

<div class="conclusion mt-6">
A principal contribuição do artigo é mostrar que o BESS não é apenas um equipamento de armazenamento: é um instrumento de coordenação entre operação, mercado e regulação.
</div>

<div class="grid-3 mt-8">
<div class="card"><div class="metric-small">1</div><p>O problema de curtailment já é sistêmico.</p></div>
<div class="card"><div class="metric-small">2</div><p>O BESS resolve tecnicamente parte relevante do problema.</p></div>
<div class="card"><div class="metric-small">3</div><p>Sem regulação adequada, o valor sistêmico permanece não monetizado.</p></div>
</div>

---

# 25. Perspectivas para o Brasil

<div class="grid-2 mt-5">
<div class="card">
<h3>Mercado</h3>
<ul>
<li>Queda gradual de CAPEX</li>
<li>Maior difusão de híbridos FV + BESS</li>
<li>Novos modelos de negócio com agregadores</li>
</ul>
</div>
<div class="card">
<h3>Regulação</h3>
<ul>
<li>Definição jurídica do armazenamento</li>
<li>Serviços ancilares para recursos distribuídos</li>
<li>Tarifas horárias mais aderentes ao valor sistêmico</li>
</ul>
</div>
</div>

<div class="dark-card mt-6">
<h2>Visão de futuro</h2>
<p>O BESS distribuído pode evoluir de equipamento individual para recurso coordenado por VPP, agregadores e mercados de flexibilidade.</p>
</div>

---

# 26. Conclusões

<div class="grid-3 mt-5">
<div class="card"><span class="metric-small">69%</span><h3>Standalone</h3><p>Maior redução técnica, mas sem base regulatória madura.</p></div>
<div class="card"><span class="metric-small">33%</span><h3>BT</h3><p>Modula carga, mas precisa de incentivo e agregação.</p></div>
<div class="card"><span class="metric-small">21%</span><h3>BESS + FV</h3><p>Mais compatível com o marco atual, mas com alcance limitado.</p></div>
</div>

<div class="callout mt-7">
<b>Conclusão final:</b> a transição energética brasileira exigirá armazenamento, mas o valor do BESS depende menos da bateria isolada e mais da capacidade de integrá-la ao planejamento, à operação e à regulação do SEP.
</div>

---

# 27. Perguntas esperadas da banca

<div class="grid-2 mt-5">
<div class="card"><b>Por que não foi feita otimização dinâmica?</b><p>O artigo prioriza transparência e aderência às regras atuais; otimização é indicada como pesquisa futura.</p></div>
<div class="card"><b>Qual estratégia é melhor?</b><p>Depende do critério: tecnicamente a Estratégia 1; regulatoriamente a Estratégia 3.</p></div>
<div class="card"><b>O BESS elimina curtailment?</b><p>Não. Reduz parcialmente e precisa ser combinado com operação, rede e sinal econômico.</p></div>
<div class="card"><b>O que falta no Brasil?</b><p>Reconhecimento regulatório, remuneração de serviços sistêmicos e mecanismos de agregação.</p></div>
</div>

---

# Obrigado

<div class="hero-subtitle mt-6">
Storage at the edge is not only about where the battery is installed.
It is about where flexibility is valued.
</div>

<div class="dark-card mt-10">
<h2>Mensagem final</h2>
<p>O armazenamento deixa de ser apenas energia guardada: torna-se capacidade operacional de transformar variabilidade renovável em flexibilidade útil para o sistema elétrico.</p>
</div>

<div class="bess-footer"><span>AvanciConsultoria/BESS</span><span>Slidev project</span></div>
