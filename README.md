# vector
let x = a.x - b.x;
let y = a.y - b.y;

let dist = Math.sqrt(Math.pow(x,2) + Math.pow(y,2)); //vector distance (=power)
let normalVector = Math.abs(x /dist);

let movedistanceX = (normalVector * x)
let movedistanceY = (normalVector * y)
