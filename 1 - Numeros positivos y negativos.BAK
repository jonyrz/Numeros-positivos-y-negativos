% Autor:
% Fecha: 02/12/2018

pos_neg([],0,0):-!.
pos_neg([X|Resto], P, N) :-
    X >= 0, !,
    pos_neg(Resto, P1, N),
    P is P1 + 1.

pos_neg([_|Resto], P, N) :-
    pos_neg(Resto, P, N1),
    N is  N1 + 1.
    
%pos_neg([3,-1,9,0,-3,-5,-8],P,N).
