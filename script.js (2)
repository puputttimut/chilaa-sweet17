let current=0;
const pages=document.querySelectorAll('.page');

function nextPage(){
pages[current].classList.remove('active');
current++;
if(current<pages.length) pages[current].classList.add('active');
}

for(let i=0;i<20;i++){
let f=document.createElement('div');
f.className='flower';
f.innerHTML='🌸';
f.style.left=Math.random()*100+'vw';
f.style.animationDuration=(5+Math.random()*5)+'s';
document.body.appendChild(f);
}
