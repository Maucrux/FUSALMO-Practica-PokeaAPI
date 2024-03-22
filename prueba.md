// function getRandomInt(min, max) {
// // //     min = Math.ceil(min);
// // //     max = Math.floor(max);
// // //     return Math.floor(Math.random() * (max - min) + min);
// // //   }
// // //   document.addEventListener('DOMContentLoaded', () =>{

// // //     const random= getRandomInt(1,151);//para apsar el aleatorio dinamicamente
// // //     console.log(random);
// // //     fetchData(random);
// // //   });

// // //   //funcion feech para que se espere y luego cuando cargue la informacion la puedan mostrar
// // //   //agregamos un id como parametro
 
// // //   const fetchData = async (id) =>{
// // //     try{
// // //     const res = await fetch(`https://pokeapi.co/api/v2/pokemon/${id}`);

// // //     const data  = await res.json();
// // // //crear una constante que se llame pokemon, y que sea de tipo objeto
// // // const pokemon = {
// // //   img: data.sprites.other.dream_world.front_default,
// // //   nombre: data.species.name,
// // //   id: data.id,
// // //   exp: data.base_experience,
// // //   hp:data.stats[0].base_stat,
// // //   ataque:data.stats[1].base_stat,
// // //   defensa:data.stats[2].base_stat,
// // //   esp:data.stats[3].base_stat


// // // }
// // // //fin de objeto pokemon+

// // //     //pintar card con la data que traemos de la info
// // //     pintarCard(data);
// // //     } catch(error){
// // //         console.log(error);
// // //     }
// // //   }

// // //   //***pintando en Template****///
// // // const pintarCard = (pokemon)=>{
// // //     console.log(pokemon);
// // //     const flex = document.querySelector('.flex');

// // //     const template = document.querySelector('#template-card').content;//content trae lo que vinee dentro del card


// // //     const clone = template.cloneNode(true);
// // //     const fragment = document.createDocumentFragment();
// // // //imagenes svg deben ser las ideales para las paginas web, identificsar la parte donde ira la imagen en el index


// // // // clone.querySelector('.card-body-img').setAttribute('src', pokemon.sprites.other.dream_world.front_default);

// // // // clone.querySelector('.card-body-title').innerHTML = `${pokemon.name} <span>${pokemon.id} hp:${pokemon.hp}</span>`;

// // // // clone.querySelector('.card-body-text').textcontent = pokemon.exp + 'exp';

// // // // ///////////////
// // // // clone.querySelectorAll('.card-footer-social h3')[0].textcontent = pokemon.ataque + 'K';
// // // // /////
// // // // clone.querySelectorAll('.card-footer-social h3')[1].textcontent = pokemon.esp + 'K';
// // // // /////
// // // // clone.querySelectorAll('.card-footer-social h3')[2].textcontent = pokemon.def + 'K';
// // // // /////

// // // clone.querySelector('.card-body-img')
// // // .setAttribute('src', pokemon.img)

// // // clone.querySelector('.card-body-title')
// // // .innerHTML = `${pokemon.nombre} <span> ${pokemon.id}  hp: ${pokemon.hp}</span> `;

// // // clone.querySelector('.card-body-text').textContent = pokemon.exp + ' exp';

// // // clone.querySelectorAll('.card-footer-social h3')[0].textContent = pokemon.ataque + ' k';

// // // clone.querySelectorAll('.card-footer-social h3')[1].textContent = pokemon.esp + ' k';

// // // clone.querySelectorAll('.card-footer-social h3')[2].textContent = pokemon.defensa + ' k';

// // // fragment.appendChild(clone);
// // // flex.appendChild(fragment);
// // // }

