```jsx
const AboutMe = () => {
  return (
    <>
      <Container>
        <section id='bio'>
          <Name first='Kirill' last='Borisov' />
          <UserName content='scriptvolutionary' />
          <Age content='19' />
          <Status content='student' />
        </section>

        <section id='skills'>
          <FrontEndSkills content='HTML, CSS/SCSS, JS/JSX/TS/TSX, React/NextJS, TailwindCSS' />
          <BackEndSkills content='PHP, Node/Express/NestJS, MongoDB, Firebase, MySQL' />
        </section>

        <section id='other'>
          <Dev first='Frontend' second='Backend' />
          <Level frontEnd='Middle' backEnd='Middle' />
        </section>
      </Container>
    </>
  )
}
```
