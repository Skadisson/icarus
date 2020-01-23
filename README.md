# icarus
Product Suggestion Engine powerd by SciKit Learn

## concept
Art.Nr -> 
Prs 
Nam
Bes
Var
Opt
Gew
Maß
Cat*

Knd.Nr -> 
B2B
B2C
PLZ
Art.Nr*
Bud
Nav*

Tree:

(([Art.Nr*] - [Knd.Nr_Art.Nr*]) * (Prs + Var + Opt + Gew" + Maß" + Cat*)) / (B2B + B2C + PLZ" + Bud + Nav*)

(([Art.Nr*] - [Knd.Nr_Art.Nr*]) * (Prs + Var + Opt + Cat*)) / (B2B + B2C + Bud + Nav*)

Nom:

(Knd.Nr_Art.Nr*_(Nam + Bes)) / (([Art.Nr*] - [Knd.Nr_Art.Nr*]) * (Nam + Bes))

Res:
Tree - Nom = Sug
