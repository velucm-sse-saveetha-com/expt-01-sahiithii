orbits(mercury, sun).
orbits(venus, sun).
orbits(earth, sun).
orbits(mars, sun).
orbits(moon, earth).
orbits(phobos, mars).
orbits(deimos, mars).
planet(P) :- orbits(P,sun).
satellite(S) :- orbits(S,P), planet(P).
INPUT/OUTPUT
?- orbits(A,B).
A = mercury,
B = sun ;
A = venus,
B = sun ;
A = earth,
B = sun ;
A = mars,
B = sun ;
A = moon,
B = earth ;
A = phobos,
B = mars ;
A = deimos,
B = mars.
