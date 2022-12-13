```js
import React from 'react';

function Joana() {
  const skills = ['HTML', 'CSS', 'JavaScript', 'React', 'Jest', 'RTL', 'Git', 'GitHub'];
  const degree = 'Pedagogy';
  const course = 'Trybe'

  return (
    <main className='about-me'>
      <h1>Joana Maria dos Santos</h1>
      <p>{`Estudando na ${course} para me tornar uma desenvolvedora full stack` }</p>
      <ul>
        <h3>Skills</h3>
        {skills.map((skill) => <li>{skill}</li>)}
      </ul>
      <p>{`Degree: ${degree}`}</p>
    </main>
  );
}

export default Joana;

```
<details>
  <summary><strong>Sobre mim</strong></summary><br />
  :woman_teacher: :arrow_right: :woman_technologist: Atualmente estou em transição de carreira, saindo da área da educação para a área da tecnologia. Decidi me aventurar em uma nova área por desejar atuar 
em algo que me permita sair da comodidade e me desafiar cada dia mais. 
  <br />
  <br />
  :mage_woman: No meus tempo livre gosto muito de assistir séries, filmes e ler livros, principalmente de ficção científica, aventura e fantasia. 
</details>
