```js
const aboutMe = () => {
  return(
    <>
      <section id='bio'>
        <Names first='Kirill' last='Borisov' />
        <UserName content='scriptvolutionary' />
        <Age content='18' />
        <Status content='student' />
      </section>

      <section id='skills'>
        <FrontEndSkill content='HTML5, CSS3, JS/ES6+, TS, React, NextJS, Tailwind, SCSS' />
        <BackEndSkill content='PHP, NodeJS, ExpressJS, MongoDB, Firebase, MySQL, Prisma' />
      </section>

      <section id='other'>
        <Dev first='Front-end' second='Back-end' />
        <Level frontEnd='Junior' backEnd='Junior' />
      </section>
    </>
  )
}
```
