# campospimentalc19.github.io-
var xPos = 400;
var yPos = 0;
var xPos2=-45;
var yPos2=20;

draw = function() {
    background(29, 40, 115);
    fill(247, 255, 0);
    ellipse(xPos-=4, yPos+=4, 15, 15);
    ellipse(xPos2+=3, yPos2+=2, 30, 30);
};
