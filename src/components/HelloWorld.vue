<template>
  <div id="container">
    <div id="header">
      <h1>{{ msg }}</h1>
    </div>
    <div id="content" class="episodes">
      <div class="episode">
        <h2>Episode 1: Hello World! </h2>
        <audio controls style="width: 50%;">
          <source src="../assets/Hardcoded_E01_Hello_World.mp3" type="audio/mpeg">
        </audio>
      </div>
        <div class="content_list">
          <ul>
            <li>
              <article>
                Hardcoded 表示工程师辛勤写代码，为什么最后又在后面加上了d呢? 当大家写完了代码，自己挖了坑，自己的狗粮自己吃了之后, 聊过一些创业的辛酸苦辣，写代码做产品，努力寻找方向, 同时HBO《硅谷》第5季25号就要开播了，有很多有意思技术梗，程序员鄙视链，同时也真实的反应了创业公司的辛酸，刺激和无奈. Stay tuned.
              </article>
            </li>
            <br>
            <li>
              <a
                href="https://www.hbo.com/silicon-valley"
                target="_blank"
              >
                Silicon Valley
              </a>
            </li>
            <br>
            <li>
              <a
                href="https://www.amazon.com/Hard-Thing-About-Things-Building/dp/0062273205"
                target="_blank"
              >
                The Hard Thing About Hard Things
              </a>
            </li>
          </ul>
        </div>
      </div>
      </div>

</template>

<script>
export default {
  name: 'Hardcoded',
  data () {
    return {
      msg: 'a podcast for hard coders'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2, h3 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}

.episode {
}

.content_list {
  display: inline-table;
  width: 50%;
  text-align: left;
}

</style>
