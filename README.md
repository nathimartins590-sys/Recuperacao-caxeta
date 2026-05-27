# Recuperacao-caxeta

Nome: Nathalia M. Correa
Curso: informatica para internet 2608
Basico do sistema: será um sistema de reserva de restaurante
Decisões de implementação: O enquanto — é a "rotina de trabalho", o atendente fica repetindo o menu até você falar "sair" (opção 6). Sem ele, o programa rodaria só uma vez e fecharia.
 O escolha opcao — é a "decisão do atendente", você escolheu 1? Ele registra. Escolheu 3? Ele cancela. Cada caso é uma tarefa diferente.
O contador_reservas — é o "caderno de reservas", guarda quantas reservas já foram feitas. Quando você registra alguém, ele avança uma posição no vetor. É ele que controla onde salvar o próximo cliente.
 O para com vetNomes[i] — é o atendente "folheando o caderno", quando você busca ou cancela, ele percorre todas as reservas uma por uma comparando o nome, até achar.
A variável encontrado — é o "pós-busca", depois de folhear tudo, se não achou nada, avisa "reserva não encontrada". Sem ela, o programa ficaria em silêncio.