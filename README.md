<div align="center">
  <img src="https://portal.cin.ufpe.br/wp-content/uploads/2020/07/Horizontal-Vermelho-Logotipo-CIn-UFPE.png" alt="logo_cin" width="400" height="auto" style="border-radius:20px;" />
  <h2>
    BANCO DE DADOS - CIN UFPE
  </h2>
  <h1>
    Projeto — Copa do Mundo 2022
  </h1> 
</div>

## :brain: Integrantes
- Isabelle Queiroz Gomes de Assis
- Luiz Phillip Pereira Barbosa
- Paulo Vitor Alves de Oliveira
- Rodrigo Medeiros Florencio Leal
- Thiago Botelho Rodrigues
- Vinícius Marçal de Araújo

## :trophy: Motivação
- <Explicação do minimundo do projeto>
  
## :pencil: Requisitos da modelagem
- Como explicado anteriormente, a modelagem do banco foi construída a partir do contexto da Copa do Mundo 2022, que aconteceu no Catar entre novembro e dezembro do mesmo ano;
- Não foram abordadas todas as informações do campeonato, mantendo-se um escopo restrito aos requisitos do projeto;
- Os requisitos da modelagem foram minimamente atendidos da seguinte forma:
  - Atributos:
    - Composto, multivalorado, discriminador em relacionamento
      - Endereço, Rede_Social, Plataforma
  - Relacionamentos:
    - Relacionamento 1:1, 1:N, N:M
      - Selecao-Pais, Clube-Jogador, Selecao-Campeonato
    - Relacionamento parcial-total, parcial-parcial
      - Pais-Selecao, Jogador-Clube
    - Relacionamento Unário ou Auto Relacionamento, Binário, N-ário
      - Goleiro-Goleiro, Jogador-Selecao, Emissora-Pais-Jogo
    - Relacionamento Identificador ou Entidade Fraca 
      - Transmissao, Tecnico-Selecao
  - Outros:
    - Entidade Associativa
      - Competiu
    - Herança (qualquer tipo)
      - Jogador-Goleiro-De_Linha

## :house: Sobre o povoamento
- O escopo do povoamento do banco foi reduzido para que a massa de dados não se tornasse muito extensa;
- Para que fosse mantida a coerência no banco, foram escolhidas cinco seleções que jogaram entre si durante o torneio;
- Assim sendo, as informações do banco englobam apenas as seguintes confederações:
  - Argentina (AFA); 
  - Austrália (FFA); 
  - Brasil (CBF); 
  - Croácia (HNS); 
  - França (FFF).
- Com isso, temos como base:
  - 32 seleções (5 detalhadas);
  - 5 técnicos;
  - 129 jogadores (26 por seleção*);
    - 15 goleiros;
    - 114 jogadores de linha;
    - *O francês Karim Benzema foi cortado por lesão antes do torneio começar.
  - 70 clubes de futebol;
  - 37 países;
  - 6 emissoras;
  - 5 jogos/partidas;
  - 43 redes sociais (~8 por seleção).

## :books: Sobre as consultas
- Além de atender os requisitos do projeto, as consultas foram pensadas pelo grupo de maneira a percorrerem todas as entidades da modelagem, se aproveitando de todas as informações captadas;
 
- Requisitos das consultas:
  - Group by/Having
  - Junção interna, externa
  - Semi-junção, anti-junção
  - Subconsulta do tipo escalar, do tipo linha, do tipo tabela
  - Operação de conjunto













