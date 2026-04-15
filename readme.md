# Comparação de Métodos para a Reconstrução de Sinal
Este repositório foi desenvolvido para guardar e compartilhar os avanços na utilização do Método de Nelder-Mead para a recuperação da energia do calorímetro de telhas TileCal do experimento ATLAS.

## Base de Dados
Para maior entendimento dos resultados, foi utilizado dados simulados que foram gerados pela ferramenta disponível no repositório: https://github.com/ingoncalves/calorimetry-pulse-simulator

## Parte Um
A primeira parte deste projéto visa comparar os resultados obtidos a partir do método proposto (Nelder-Mead) com os resultados de alguns métodos utilizados atualmente no experimento, mais especificamente o Optimal Filter (OF2) e o Constrained Optimal Filter (COF).

## Copiando o Repositório
Os métodos, base de dados utilizada e os resultados salvos podem ser copiados para estudo, mas é necessário configurar o ambiente para que tudo funcione corretamente. Após clonar o projeto, siga os passos abaixo.

### Ambiente Virtual
Inicie um ambiente virtual dentro da pasta do projeto, digite os seguintes comandos:
<pre>
  python -m venv .venv
  
  .\.venv\Scripts\activate
  
  pip install -r .\requirements.txt
</pre>

### Interpretador
Tente rodar qualquer célula do <a href='https://github.com/nicolasfouv/nelder-mead-for-signal-recovery/blob/main/nm_of2_cof.ipynb'>nm_of2_cof.ipynb</a> e selecione o interpredador do ambiente virtual (de caminho .\\.venv\Scripts\python). Após isso, todo o arquivo está pronto para ser rodado.
