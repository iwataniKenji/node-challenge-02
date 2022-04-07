<section align="center">
    <h1>NodeJS Ignite Challenge #2</h1>
</section>

---

<h2 align="center">Summary</h2>

<p align="center">
    <a href="#description">📙 Description</a>
    <a href="#tests">⚙️ Tests</a>
    <a href="#technologies">💻 Technologies</a>
</p>

<H2 id="description">📙 Description</H2>

<p>This challenge focused on implementing functionalities through middlewares on Express. Basically, you have to complete all the middlewares functions based on the tests described on the challenge description.</p>
<p>This second challenge itself is very similar to the first one, changing just some minor functionalities.</p>

<p>Originally created on Ignite from <a href="https://www.rocketseat.com.br/">Rocketseat</a> and made by <a href="https://www.linkedin.com/in/kleverson-kenji-iwatani/">Kenji Iwatani</a></p>

<p>
    <h3><a href="https://www.notion.so/Desafio-02-Trabalhando-com-middlewares-4f89bf538c2e4ee291382b92bdc36790">Challenge description &rarr;</a></h3>
</p>

---

<H2 id="tests">⚙️ Tests</H2>

<h3>Should be able to:</h3>

- [x] Find user by username in header and pass it to request.user
- [x] Let user create a new todo when is in free plan and have less than ten todos
- [x] Let user create infinite new todos when is in Pro plan
- [x] Put user and todo in request when both exits
- [x] Find user by id route param and pass it to request.user

<h3>Should not be able to:</h4>

- [x] Let user create a new todo when is not Pro and already have ten todos
- [x] Find a non existing user by username in header
- [x] Put user and todo in request when user does not exists
- [x] Put user and todo in request when todo id is not uuid
- [x] Put user and todo in request when todo does not exists
- [x] Pass user to request.user when it does not exists

---

<H2 id="technologies">💻 Technologies</H2>

- [x] <a href="https://nodejs.org/en/">NodeJS</a>
- [x] <a href="https://expressjs.com/">ExpressJS</a>
- [x] <a href="https://nodemon.io/">Nodemon</a>
- [x] <a href="https://insomnia.rest/">Insomnia</a>
