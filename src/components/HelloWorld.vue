<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      I created this vueJs app using the Vue cli. I then created a droplet in digital ocean and deployed there!
    </p>
     <h3>My Personal Links</h3>
    <ul>
      <li><a href="https://twitter.com/Domt301?ref_src=twsrc%5Etfw" title="Twitter" target="_blank" ><img src="../assets/Twitter-logo-2012.png"></a> 
    
      </li>&nbsp;
       <li><a href="https://domthecodingcaveman.wordpress.com/" title="Blog" target="_blank" ><img src="../assets/Blog.png"></a>
      
      </li>&nbsp;
        <li><a href="https://github.com/Domt301" title="Github" target="_blank" ><img src="../assets/Octocat.jpg"></a> 
        
      </li>
    </ul>
   
      <h3>.Net Core web api with swagger doc hosted on aws.</h3>
      <p>I created this project using the dotnet cli and I am using Azure Devops for a CI/CD pipeline</p>
    <ul>
       <li><a href="http://domnetcoreapiswagger.us-west-2.elasticbeanstalk.com/index.html" target="_blank" rel="noopener" title="WebApi"><img src="../assets/swagapi.png"></a></li>
    </ul>
   
     <h3>Blog Post I followed to deploy this project.</h3>
    <ul>
       <li><a href="https://medium.com/@Web_Bailey/deploy-a-vuejs-app-with-digitalocean-fd6e7af07e40" target="_blank" rel="noopener">Medium</a></li>
    </ul>
    <p>
      For guide and recipes on how to configure / customize this project,<br>
      check out the
      <a href="https://cli.vuejs.org" target="_blank" rel="noopener">vue-cli documentation</a>.
    </p>
    <h3>Installed CLI Plugins</h3>
    <ul>
      <li><a href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-babel" target="_blank" rel="noopener">babel</a></li>
      <li><a href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-eslint" target="_blank" rel="noopener">eslint</a></li>
    </ul>
    <h3>Essential Links</h3>
    <ul>
      <li><a href="https://vuejs.org" target="_blank" rel="noopener">Core Docs</a></li>
      <li><a href="https://forum.vuejs.org" target="_blank" rel="noopener">Forum</a></li>
      <li><a href="https://chat.vuejs.org" target="_blank" rel="noopener">Community Chat</a></li>
      <li><a href="https://twitter.com/vuejs" target="_blank" rel="noopener">Twitter</a></li>
      <li><a href="https://news.vuejs.org" target="_blank" rel="noopener">News</a></li>
    </ul>
    <h3>Ecosystem43</h3>
    <ul>
      <li><a href="https://router.vuejs.org" target="_blank" rel="noopener">vue-router</a></li>
      <li><a href="https://vuex.vuejs.org" target="_blank" rel="noopener">vuex</a></li>
      <li><a href="https://github.com/vuejs/vue-devtools#vue-devtools" target="_blank" rel="noopener">vue-devtools</a></li>
      <li><a href="https://vue-loader.vuejs.org" target="_blank" rel="noopener">vue-loader</a></li>
      <li><a href="https://github.com/vuejs/awesome-vue" target="_blank" rel="noopener">awesome-vue</a></li>
    </ul>
   
    
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
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
</style>
