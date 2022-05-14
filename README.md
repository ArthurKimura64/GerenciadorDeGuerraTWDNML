# GerenciadorDeGuerraTWDNML
The Walking Dead: No Man's Land é um jogo de estratégia realizado em turnos com o tema do seriado The Walking Dead. No jogo, existe um modo chamado **Guerras de Guilda**, que consiste em um sistema de cooperação entre grupos para a realização de missões e conflitos com outro grupos. Nesse modo de jogo, ocorre os seguintes:

— As Guerras de Guilda são realizadas em temporadas, divididos em 4 Guerras, cada uma durando seis dias, começando pela terça-Feira.

— Durante a segunda-feira, é liberado o alistamento para participar da guerra nos outros dias, que vão de terça-feira até domingo. Para participar da guerra durante um dia em específico, deve, naquele dia, alistar no mínimo 3 jogadores, podendo jogar até 10 jogadores em um único dia. Um jogador pode se alistar em até 2 dias durante uma Guerra.

— Dentro da Guerra, existirão 72 possíveis setores, divididas em 20 ilhas (conjuntos de 3/4 setores que possuem o mesmo nível de dificuldade) e 4 setores separados. Ao realizar o setor A e B de uma certa ilha, o setor C dessa mesma ilha será liberada para ser realizada também.As missões do setor C dão mais pontos do que os setores A ou B.
![image](https://user-images.githubusercontent.com/89915965/168425260-da6b327a-fe42-43e9-af73-d6630148a50f.png)
Imagem baseada em um jogador com times de nível 28.

— Cada jogador alistado para aquele dia possuirá 18 investidas, que podem ser usadas para completar missões.

— Dentro de cada setor, existem 12 missões (8 caso o setor seja o setor C ou os 4 setores separados), sendo 8 missões realizadas com um nível de dificuldade variada (dependendo do setor que está sendo feito) e 4 missões de nível de dificuldade fixo (+2), pelo qual o time de um jogador entra em conflito com o time de um outro jogador do outro grupo. 1 missão de dificuldade fixa só pode ser realizada caso sejam realizadas 2 missões de dificuldade variadas que possuem o mesmo nível de dificuldade entre eles.

— As missões podem ser realizadas por um jogador utilizando suas investidas. Se um jogador falhar em completar a missão com sucesso, ele não receberá sua investida de volta.

O que esse planejador de guerra realiza:

— O planejador recebe 2 tipos de banco de dados:
1. Uma tabela que informa em quais dias e quais horários que um jogador estaria disponível para se alistar e jogar, respectivamente;
2. Uma tabela que informa quis níveis de dificuldade cada jogador pode realizar.

- O planejador deve devolver um alistamento, considerando os horários e dias disponíveis de cada jogador, considerando que:
1. Cada jogador só pode se alistar em até 2 dias de guerra;
2. Para concluir uma ilha completa, é necessário no mínimo 2 jogadores, pelo qual devem ter capacidade necessária para realizar uma certa dificuldade.
3. Existem jogadores que possuem pouco tempo disponível, logo deve-se inserir eles para poder realizar missões de dificuldade confortáveis para que ele possa terminar suas investidas rápido.
