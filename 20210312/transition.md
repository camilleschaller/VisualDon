Comment fonctionnent les transitions en D3 et en svelte?

Ce premier exemple montre la transition d'un cercle d'une position cx égale à 150 vers une nouvelle position égale à 850. Nous introduisons au passage la fonction duration exprimée en millisecondes qui permet de préciser la durée de la transition.

var circleMove = svg.append("circle")
    .attr("cx",150)
    .attr("cy",50)
    .attr("r",30);
    
circleMove.transition()
    .duration(2000)
    .attr("cx", 850);

