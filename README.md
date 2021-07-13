# xadrez-console
Tecnologia utilizada:
- C#

Este projeto foi desenvolvido durante o curso "C# COMPLETO Programação Orientada a Objetos + Projetos" ministrado pelo professor Nelio Alves.<br />
O projeto contém um sistema de jogo de xadrez por console.

<h2>Objetivo:</h2>
O objetivo do projeto é exercitar os conceitos de orientação a objetos e estrutura de dados na linguagem C#.<br /><br />
Conceitos aplicados:

- Sobrecarga
- Encapsulamento
- Associações
- Herança
- Classe abstrata
- Sobreposição
- Polimorfismo
- Elementos estativos
- Tipos enumerados
- Exceções

Estruturas de dados utilizadas:
- Vetores
- Matrizes
- Listas
- Conjuntos

#  ♟ Sobre o jogo ♟
Para representar as peças no tabuleiro, foram utilizadas as seguintes siglas:
<table>
  <thead>
    <th>Sigla</th>
    <th>Peça</th>
  </thead>
  <tbody>
    <tr>
      <td>R</td>
      <td>Rei</td>
    </tr>
     <tr>
      <td>D</td>
      <td>Dama/Rainha</td>
    </tr>
     <tr>
      <td>B</td>
      <td>Bispo</td>
    </tr>
     <tr>
      <td>C</td>
      <td>Cavalo</td>
    </tr>
     <tr>
      <td>T</td>
      <td>Torre</td>
    </tr>
     <tr>
      <td>P</td>
      <td>Peão</td>
    </tr>
  <tbody>
</table>

<h2> Jogadas especiais implementadas </h2>
 
<br />
<table>
  <thead>
    <th>Nome</th>
    <th>Descrição</th>
  </thead>
  <tbody>
    <tr>
      <td>Roque</td>
      <td>O Roque é uma jogada especial que envolve a movimentação de duas peças em um único lance, o rei e uma das torres. O objetivo da jogada é proteger o rei, tirando-o do centro. O movimento consiste no deslocamento lateral do rei na primeira fileira em duas casas na direção da torre com a qual desejar "rocar", e a torre escolhida passa através do rei permanecendo na primeira casa após o "salto".</td>
    </tr>
     <tr>
      <td>Roque menor</td>
      <td>No roque menor, ou roque pequeno, o rei é movimentado duas casas em direção à torre de sua ala.</td>
    </tr>
     <tr>
      <td>Roque maior</td>
      <td>No roque maior, ou roque grande, o rei faz roque com a torre da ala da dama.</td>
    </tr>
     <tr>
      <td>En Passant</td>
      <td>En passant é um movimento especial de captura do Peão no jogo de xadrez. Na ocasião do avanço por duas casas do peão, caso haja um peão adversário na coluna adjacente na quarta fileira para as brancas, ou quinta para as pretas, este pode capturar o peão como se "de passagem", movendo-o para a casa por onde o peão capturado passou sobre. A captura en passant deve ser feita imediatamente após o peão ter sido movido por duas casas, caso contrário o jogador adversário perde o direito de fazê-lo posteriormente.</td>
    </tr>
     <tr>
      <td>Promoção</td>
      <td>Quando um peão alcança a oitava fileira, ele pode ser trocado por uma peça de escolha no jogador. No caso do projeto, a peça é automaticamente substituida por uma Dama/Rainha.</td>
    </tr>
  <tbody>
</table>


