# Batimento De Ondas
Gera ondas sonoras, reproduz e plota o gráfico mostrando o batimento.
<i>Stênio V. Medeiros</i>

<h2>Funcionamento</h2>
<p>Gera duas ondas sonoras.</p>
<p>Uma das ondas é muito bem definida, o usuário escolhe a forma (senoidal, quadrada ou dente de serra) e a nota musical (em todas suas oitavas audiveis), simulando assim uma nota tocada em um instrumento musical muito bem afinado.</p>
<p>A segundo onda é sempre senoidal e o usuário pode ajustar a frequência de 20 a 20.000 Hz com resolução de 0,01 Hz, simulando um instrumento musical a ser afinado.</p>
<p>Ao gerar as ondas é reproduzido o seu som no auto falante padrão e um gráfico da onda e plotado na elemento canvas no topo da página.</p>
<p>Se ao tocar o som a ser ajustado o som de referencia estiver ativos, alem de plotar o gráfico das duas ondas, tambem é plotado o gráfico da onda resultante, dada pela soma das duas.</p>
<p>Ao tocar a nota de referência ela continuará ativa até que o usuário click em parar ou toque outra nota.</p>
<p>Já o som a ser ajustado para automaticamente depois de 10 segundos, mas seu gráfico permanece até que outro seja plotado.</p>
<p>O controle de volume é o mesmo para as duas ondas.</p>

<h2>Aplicabilidade</h2>
<p>Como o gráfico gerado leva em conta os mesmos parâmentros dos sons tocados, pode ser usado para exemplificar a associação dos elementos de onda (frequência, comprimento, amplitude e timbre) com o som ouvido.</p>
<p>Como é gerado um gráfico da onda resultante, pode-se ser usado para exemplificar fenômenos de interfêrencia.</p>
<p>Quando as frequências das duas ondas são muito distintas é possivel distinguir perfeitamente os sons, mas quando são próximas ouve-se como um unico som com batimento. Com isso é possivel usar para exemplificar o fenômeno de batimento.</p>
<p>É possivel usar como desafio, de encontrar a frequência da nota tocada chegando ao batimento zero.</p>
<p><b>Além de aplicações didaticas tambem é possivel usar para afinar instrumentos musicais reais</b>, bastando para isso usar apenas a onda de refêrencia e ignorar a segunda onda.</p>

<h3>Desenvolviemnto</h3>
<p>Todo o código foi escrito <i>HTML + CSS + JavaScript</i> puros nas suas versões mais recentes até a data de publicação.</p>
<p>Data de publicação: </i>18 Janeiro 2023</i></p>
<p>Codificação/Pesquisa/Design: <i>Stênio V. Medeiros</i></p>
