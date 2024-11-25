<template>
  <div id="app">
    <header>
      <h1>山口 雷太さんの自己紹介</h1>
      <nav>
        <ul>
          <li><a href="#about">自己紹介</a></li>
          <li><a href="#skills">スキル</a></li>
          <li><a href="#contact">連絡先</a></li>
        </ul>
      </nav>
    </header>
    <main>
      <section id="about">
        <h2>自己紹介</h2>
        <p>こんにちは、山口 雷太です。スーパーＩＴエンジニア専攻 スーパーＡＩ＆テクノロジー科で学んでいます。</p>
      </section>
      <section id="skills">
        <h2>スキル</h2>
        <ul>
          <li>HTML</li>
          <li>CSS</li>
          <li>JavaScript</li>
          <li>Python</li>
        </ul>
      </section>
      <section id="contact">
        <h2>連絡先</h2>
        <p>Email: example@example.com</p>
      </section>
    </main>
    <footer>
      <p>&copy; 2024 山口 雷太さんの自己紹介サイト</p>
    </footer>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
body {
  font-family: 'Arial', sans-serif;
  line-height: 1.6;
  margin: 0;
  padding: 0;
  background-color: #f4f4f4;
}

header {
  background: #333;
  color: #fff;
  padding: 1rem 0;
  text-align: center;
}

header nav ul {
  list-style: none;
  padding: 0;
}

header nav ul li {
  display: inline;
  margin: 0 10px;
}

header nav ul li a {
  color: #fff;
  text-decoration: none;
}

main {
  padding: 1rem;
}

section {
  margin-bottom: 2rem;
}

h1, h2 {
  color: #333;
}

ul {
  list-style-type: none;
  padding: 0;
}

ul li {
  background: #ddd;
  margin: 0.5rem 0;
  padding: 0.5rem;
}

footer {
  background: #333;
  color: #fff;
  text-align: center;
  padding: 1rem 0;
  position: fixed;
  bottom: 0;
  width: 100%;
}
</style>