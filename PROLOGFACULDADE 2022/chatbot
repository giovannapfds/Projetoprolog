
% Projeto Interdisciplinar Em Ciência da Computação
% Autor: Giovanna Polydoro Ferreira de Souza.
% Projeto: ChatBot.

:-include(basedados1).
:-include(basedados2).

chatbot :-
	format('Olá! Eu sou o Robô inteligente.'), nl ,
	repeat, nl,nl,nl,
	format('O que voce gostaria de saber hoje: '), nl ,


	nl, format('- '),
        read(Entrada),
	consulta_base(Entrada, Resposta),
	format(Resposta), nl ,
	encerra_sessao(Entrada).

consulta_base(Entrada, RespostaCorreta) :-
	definid(Entrada, RespostaCorreta), !.

encerra_sessao(Entrada) :-
	Entrada = ('fim').

