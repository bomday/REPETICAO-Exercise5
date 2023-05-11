<h2>PROBLEM STATEMENT: BINlhete premiado? Descubra e ganhe!</h2>
---
<p>Para atrair novos clientes, a empresa de turismo CinTur decidiu promover uma ação e precisa da sua ajuda para concretizá-la.
<br/>
Veja o anúncio da empresa: "Venha garantir seu pacote de viagem gratuito neste fim de ano! Basta visitar uma de nossas agências, sortear um número binário e converter mentalmente o número para decimal. Acertando a conversão de um de nossos bilhetes premiados, prepare as malas e venha conosco!"</p>
<p>O gerente da CinTur convocou você para desenvolver um programa que, ao receber o número sorteado e o palpite inicial do cliente, converta o número binário para decimal através de laços de repetição e verifique se o cliente acertou. O cliente possui até 03 chances para acertar, mas atenção: O cliente só irá falar um próximo palpite se realmente tiver errado o anterior.</p>
<p>Caso o palpite esteja correto, o programa deverá verificar qual será o destino premiado de acordo com a tabela abaixo, que foi divulgada pela a empresa:</p>
<p>Atenção: A empresa também colocou no sorteio números inválidos, ou seja, que não correspondem a nenhum destino.</p>
<p>OBS.1: Sendo a entrada um valor em binário, trabalhe no formato de string.</p>
<p>OBS.2 : Todas as entradas serão amigáveis (Não precisa se preocupar com números negativos).</p>
<h3>Input</h3>
---
<p>Inicialmente, você receberá o número sorteado (em binário):</p>
- n_binario
<br/><br/>
<p>Em seguida, será fornecido o primeiro palpite do cliente (em decimal):</p>
- palpite_01
<br/><br/>
<p>Se, e somente se, o cliente errar, mais um palpite será recebido (também em decimal):</p>
- palpite_02
<br/><br/>
<p>Se, e somente se, o cliente errar novamente, mais um palpite será recebido (também em decimal):</p>
- palpite_03
<br/><br/>
<h3>Output</h3>
---
<p>Caso o cliente tenha acertado, imprima:</p>
-> Parabéns!! Você acertou!
<br/><br/>
<p>Em seguida, observe se era ou não um bilhete premiado e imprima:</p>
<p>Caso o destino seja Porto de Galinhas:</p>
-> “Férias inesquecíveis estão te esperando!"
<br/>
-> "Seu destino será Porto de Galinhas (BRA)."
<br/>
-> "Prepare-se para viver dias incríveis desfrutando das riquezas naturais da nossa região!”
<br/><br/>
<p>Caso o destino seja Fernando de Noronha:</p>
-> “Férias inesquecíveis estão te esperando!"
<br/>
-> "Seu destino será Fernando de Noronha (BRA)."
<br/>
-> "Belíssimas praias estão por vir."
<br/>
-> "Não esqueça o protetor solar.”
<br/><br/>
<p>Caso o destino seja Gramado:</p>
-> “Férias inesquecíveis estão te esperando!"
<br/>
-> "Seu destino será Gramado (BRA)."
<br/>
-> "Aproveite passeios e paisagens espetaculares no sul do país!”
<br/><br/>
<p>Caso o destino seja Berlim:</p>
-> “Férias inesquecíveis estão te esperando!"
<br/>
-> "Seu destino será Berlim (ALE)."
<br/>
-> "Desfrute de muita cultura e de experiências incríveis!"
<br/>
-> "Prepare os casacos de frio!”
<br/><br/>
<p>Caso o destino seja Tóquio:</p>
-> “Férias inesquecíveis estão te esperando!"
<br/>
-> "Seu destino será Tóquio (JPN)."
<br/>
-> "Viva uma experiência inesquecível explorando um país do outro lado do mundo."
<br/>
-> "Prepare-se para muitas horas de voo!”
<br/><br/>
<p>Caso o número não corresponda a nenhum destino:</p>
-> “Mas, infelizmente, hoje não é o seu dia de sorte."
<br/>
-> "Apesar de ter dado a resposta correta, seu bilhete não oferece nenhum prêmio."
<br/>
-> "Sinta-se à vontade para conhecer nossos pacotes e outras promoções imperdíveis com um de nossos vendedores!”
<br/><br/>
<p>Porém, caso o cliente tenha informado a resposta incorreta, imprima:</p>
<p>Se ele ainda possui chance(s) para adivinhar:</p>
-> "Resposta incorreta. Mas não desista! Você ainda tem { n_chances } chance(s)."
<br/><br/>
<p>E repita o processo.</p>
<p>Ou se errou em todas as suas tentativas:</p>
<p>Caso o bilhete correspondesse a um destino:</p>
-> “Infelizmente mais uma resposta incorreta."
<br/>
-> "Agradecemos sua participação!"
<br/>
-> "Seu bilhete era premiado. Que pena!”
<br/><br/>
<p>Ou caso o bilhete não correspondesse a um destino:</p>
-> “Infelizmente mais uma resposta incorreta."
<br/>
-> "Agradecemos sua participação!"
<br/>
-> "Pelo menos seu bilhete não era premiado."
<br/>
-> "Sinta-se à vontade para conhecer nossos pacotes e outras promoções imperdíveis com um de nossos vendedores!”