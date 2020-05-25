<template>
  <div class="reveal">
    <div class="slides">
      <section data-background-color="#42b883">
        <div class="block-user-info">
          <img class="user-info__photo" src="../assets/img/ggnk.jpg" width="186" height="186" alt="">
          <div class="user-info__name">Nurlan Kurbandurdyev</div>
          <div class="user-info__position">JavaScript Developer</div>
          <div class="user-info__social">
            <a href="https://github.com/ggnk" target="_blank" class="github">Github</a>
            <a href="https://profile.codersrank.io/user/ggnk" target="_blank" class="linkedin">Codersrank</a>
          </div>
        </div>
      </section>
      <section data-background-color="#ffffff">
        <div class="vue-logo">
          <svg class="vue-logo__svg" width="256px" height="221px" viewBox="0 0 256 221" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" preserveAspectRatio="xMidYMid">
            <g>
              <path d="M204.8,0 L256,0 L128,220.8 L0,0 L50.56,0 L97.92,0 L128,51.2 L157.44,0 L204.8,0 Z" fill="#41B883"></path>
              <path d="M0,0 L128,220.8 L256,0 L204.8,0 L128,132.48 L50.56,0 L0,0 Z" fill="#41B883"></path>
              <path d="M50.56,0 L128,133.12 L204.8,0 L157.44,0 L128,51.2 L97.92,0 L50.56,0 Z" fill="#35495E"></path>
            </g>
          </svg>
          <br>
          <h3 class="vue-logo__title">Vue.JS</h3>
        </div>
      </section>
      <section data-background-color="#42b883">
        <div class="block-user-info">
          <img class="user-info__photo" src="../assets/img/photo-evan-you.jpeg" alt="">
          <div class="user-info__name">
            Evan You
          </div>
          <div class="user-info__position">Creator <a href="https://vuejs.org/" target="_blank">@Vue.js</a></div>
          <div class="user-info__position">Core Dev at Meteor</div>
          <div class="user-info__position">Previously worked as a Creative Technologist at Google</div>
          <div class="user-info__position">From 2016 working full-time on Vue.JS framework.</div>
          <div class="user-info__social">
            <a href="https://twitter.com/youyuxi" target="_blank" class="twitter">Twitter</a>
            <a href="https://github.com/yyx990803/" target="_blank" class="github">Github</a>
          </div>
        </div>
      </section>
      <section data-background-color="#42b883">
        <div class="history">
          <h2 style="color: #fff">History</h2>
          <ul>
            <li class="fragment">Started in late 2013</li>
            <li class="fragment">First release Feb. 2014 (v0.6)</li>
            <li class="fragment">v1.0.0 Evangelion Oct. 2015</li>
            <li class="fragment">Latest release v2.6</li>
          </ul>
        </div>
      </section>
      <section data-background-color="#ffffff">
        <h2>Stars</h2>
        <img src="../assets/img/stars.jpg" alt="Stars">
      </section>
      <section data-background-color="#ffffff">
        <h2>Web Frameworks Benchmark</h2>
        <h4>Round 8</h4>
        <a href="https://stefankrause.net/js-frameworks-benchmark8/table.html">www.stefankrause.net</a>
      </section>
      <section data-background-color="#42b883">
        <section>
          <h2 class="white">Advantages</h2>
          <ul>
            <li class="fragment">Very Small Size</li>
            <li class="fragment">Easy to Understand <br>and Develop Applications</li>
            <li class="fragment">Simple Integration</li>
            <li class="fragment">Detailed Documentation</li>
            <li class="fragment">Flexibility</li>
            <li class="fragment">Right to choose</li>
          </ul>
        </section>
        <section>
          <h2 class="white">Information</h2>
          <ul>
            <li>Progressive framework</li>
            <li>Component oriented</li>
            <li>Mix the best of React and Angular</li>
          </ul>
        </section>
        <section>
          <h2 class="white">Very Small Size</h2>
          <div>jsize react + react-dom angular vue</div>
          <br>
          <table>
            <tr>
              <th>Name</th>
              <th>Size</th>
            </tr>
            <tr>
              <td>React + react-dom</td>
              <td>34.4 kB (gzipped)</td>
            </tr>
            <tr>
              <td>Angular</td>
              <td>62.2 kB (gzipped)</td>
            </tr>
            <tr>
              <td>Vue.js</td>
              <td>23.8 kB (gzipped)</td>
            </tr>
            <tr>
              <td>jquery</td>
              <td>31.1 kB (gzipped)</td>
            </tr>
          </table>
        </section>
        <section data-background-color="#ffffff">
          <h2>Easy to Understand and Develop Applications</h2>
          <pre class="code"><code v-pre>
&lt;template&gt;
    &lt;div class=&quot;example&quot;&gt;{{ msg }}&lt;/div&gt;
&lt;/template&gt;

&lt;script&gt;
    export default {
        data () {
            return {
                msg: 'Hello world!'
            }
        }
    }
&lt;/script&gt;
                </code></pre>
        </section>
        <section>
          <h2 class="white">Simple Integration</h2>
          <ul>
            <li class="fragment">tag script (Vue.js runtime)</li>
            <li class="fragment">webpack</li>
            <li class="fragment">web components</li>
            <li class="fragment">browserify</li>
            <li class="fragment">requirejs</li>
          </ul>
        </section>
        <section data-background-color="#ffffff">
          <h2>Detailed Documentation</h2>
          <img src="../assets/img/doc.png" alt="">
        </section>
        <section>
          <h2 class="white">Flexibility</h2>
          <ul>
            <li class="fragment">Write your template in an HTML file</li>
            <li class="fragment">Write your template in a string in a Javascript file</li>
            <li class="fragment">Use JSX in a Javascript file</li>
            <li class="fragment">Make your template in pure Javascript using virtual nodes</li>
          </ul>
          <p class="fragment">
            This flexibility makes it easy to switch to Vue because React developers,
            Angular developers, or developers new to JS frameworks would all find Vue’s design familiar.
          </p>
        </section>
        <section>
          <h2 class="white">Right to choose</h2>
          <ul>
            <li class="fragment">
              Template
              <ul>
                <li>html binding</li>
                <li>jsx</li>
                <li>jade</li>
              </ul>
            </li>

            <li class="fragment">
              Component class
              <ul>
                <li>es5</li>
                <li>es6 / es7</li>
                <li>es6 + flow</li>
                <li>TypeScript</li>
              </ul>
            </li>
          </ul>
        </section>
      </section>
      <section data-background-color="#42b883">
        <h2 class="white">Ecosystem</h2>
        <table class="ecosystem">
          <tr>
            <th>Project</th>
            <th>Description</th>
          </tr>
          <tr>
            <td><a class="ecosystem__link" href="https://github.com/vuejs/vue-router">vue-router</a></td>
            <td>Single-page application routing</td>
          </tr>
          <tr>
            <td><a class="ecosystem__link" href="https://github.com/vuejs/vuex">vuex</a></td>
            <td>Large-scale state management</td>
          </tr>
          <tr>
            <td><a class="ecosystem__link" href="https://github.com/vuejs/vue-cli">vue-cli</a></td>
            <td>Project scaffolding</td>
          </tr>
          <tr>
            <td><a class="ecosystem__link" href="https://github.com/vuejs/vue-loader">vue-loader</a></td>
            <td>Single File Component (<code>*.vue</code> file) loader for webpack</td>
          </tr>
          <tr>
            <td><a class="ecosystem__link" href="https://github.com/vuejs/vue/tree/dev/packages/vue-server-renderer">vue-server-renderer</a></td>
            <td>Server-side rendering support</td>
          </tr>
          <tr>
            <td><a class="ecosystem__link" href="https://github.com/vuejs/vue-class-component">vue-class-component</a></td>
            <td>TypeScript decorator for a class-based API</td>
          </tr>
          <tr>
            <td><a class="ecosystem__link" href="https://github.com/vuejs/vue-rx">vue-rx</a></td>
            <td>RxJS integration</td>
          </tr>
          <tr>
            <td><a class="ecosystem__link" href="https://github.com/vuejs/vue-devtools">vue-devtools</a></td>
            <td>Browser DevTools extension</td>
          </tr>
        </table>
      </section>
      <section data-background-color="#ffffff">
        <h2>Native app</h2>
        <ul class="black">
          <li>NativeScript with Vue.js</li>
          <li>Weex - Mobile cross-platform UIs</li>
        </ul>
      </section>
      <section data-background-color="#ffffff">
        <h2>Server-side Rendering (SSR)</h2>
        <img src="../assets/img/nuxt.png" alt="">
      </section>
      <section data-background-color="#42b883">
        <h2 class="white">Who is using it?</h2>
        <ul class="white">
          <li>GitLab</li>
          <li>NativeScript</li>
          <li>Weex</li>
          <li>Baidu</li>
        </ul>
      </section>
      <section>
        <section data-background-color="#42b883">
          <h2 class="white">How it works?</h2>
        </section>
        <section data-background-color="#ffffff">
          <img src="../assets/img/MVVM.png" alt="">
        </section>
        <section data-background-color="#ffffff">
          <h2>Components</h2>
          <img src="../assets/img/components.png" alt="">
        </section>
        <section data-background-color="#ffffff">
          <h2>Lifecycle</h2>
          <img src="../assets/img/lifecycle.png" alt="">
        </section>
        <section data-background-color="#ffffff">
          <h2>Reactivity</h2>
          <img src="../assets/img/reactivity.png" alt="">
        </section>
      </section>
      <section>
        <section data-background-color="#42b883">
          <h2 class="white">Interpolations</h2>
        </section>
        <section data-background-color="#ffffff">
          <h2>Text</h2>
          <pre class="code"><code v-pre>
&lt;span&gt;Message: {{ msg }}&lt;/span&gt;
&lt;span v-once&gt;This will never change: {{ msg }}&lt;/span&gt;
                </code></pre>
        </section>
        <section data-background-color="#ffffff">
          <h2>Raw HTML</h2>
          <pre class="code"><code v-pre>
&lt;p&gt;Using mustaches: {{ rawHtml }}&lt;/p&gt;
&lt;p&gt;Using v-html directive: &lt;span v-html="rawHtml"&gt;&lt;/span&gt;&lt;/p&gt;
                </code></pre>
        </section>
        <section data-background-color="#ffffff">
          <h2>Attributes</h2>
          <pre class="code"><code v-pre>
&lt;div v-bind:id="dynamicId"&gt;&lt;/div&gt;
&lt;button v-bind:disabled="isButtonDisabled"&gt;Button&lt;/button&gt;
                </code></pre>
        </section>
        <section data-background-color="#ffffff">
          <h2>Using JavaScript Expressions</h2>
          <pre class="code"><code v-pre>
{{ number + 1 }}
{{ ok ? 'YES' : 'NO' }}
{{ message.split('').reverse().join('') }}
&lt;div v-bind:id="'list-' + id"&gt;&lt;/div&gt;
                </code></pre>
        </section>
      </section>
      <section data-background-color="#ffffff">
        <h2>Directives</h2>
        <div class="row">
          <div class="col-md-6">
            <h5>v-bind</h5>
            <pre class="code"><code v-pre>
&lt;!-- full syntax --&gt;
&lt;a v-bind:href="url"&gt;&lt;/a&gt;
&lt;!-- shorthand --&gt;
&lt;a :href="url"&gt;&lt;/a&gt;
                    </code></pre>
          </div>
          <div class="col-md-6">
            <h5>v-on</h5>
            <pre class="code"><code v-pre>
&lt;!-- full syntax --&gt;
&lt;a v-on:click="doMethod"&gt;&lt;/a&gt;
&lt;!-- shorthand --&gt;
&lt;a @click="doMethod"&gt;&lt;/a&gt;
                    </code></pre>
          </div>
        </div>
        <h5>Modifiers</h5>
        <pre class="code"><code v-pre>
&lt;form v-on:submit.prevent="onSubmit"&gt; ... &lt;/form&gt;
            </code></pre>
      </section>
      <section>
        <section data-background-color="#42b883">
          <h2 class="white">Computed Properties and Watchers</h2>
        </section>
        <section data-background-color="#ffffff">
          <h2>Watch</h2>
          <pre class="code"><code class="lang-javascript">
var vm = new Vue({
  el: '#demo',
  data: {
    firstName: 'Foo',
    lastName: 'Bar',
    fullName: 'Foo Bar'
  },
  watch: {
    firstName: function (val) {
      this.fullName = val + ' ' + this.lastName
    },
    lastName: function (val) {
      this.fullName = this.firstName + ' ' + val
    }
  }
})
                </code></pre>
        </section>
        <section data-background-color="#ffffff">
          <h2>Computed</h2>
          <pre class="code"><code v-pre>
&lt;div id="demo"&gt;{{ fullName }}&lt;/div&gt;
                </code></pre>
          <pre class="code"><code class="lang-javascript">
var vm = new Vue({
  el: '#demo',
  data: {
    firstName: 'Foo',
    lastName: 'Bar'
  },
  computed: {
    fullName: function () {
      return this.firstName + ' ' + this.lastName
    }
  }
})
            </code></pre>
        </section>
        <section data-background-color="#ffffff">
          <h2>Computed Setter</h2>
          <pre class="code"><code class="lang-javascript">
//...
computed: {
  fullName: {
    // getter
    get: function () {
      return this.firstName + ' ' + this.lastName
    },
    // setter
    set: function (newValue) {
      var names = newValue.split(' ')
      this.firstName = names[0]
      this.lastName = names[names.length - 1]
    }
  }
}
//...
            </code></pre>
        </section>
      </section>
      <section data-background-color="#ffffff">
        <h2>Binding HTML Classes</h2>
        <div class="row">
          <div class="col-md-6">
                    <pre class="code"><code v-pre>
&lt;div :class="{
  'active': isActive,
  'text-danger': HasError
}"&gt;
&lt;/div&gt;
                    </code></pre>
          </div>
          <div class="col-md-6">
                    <pre class="code"><code class="lang-javascript">
//...
data: {
  isActive: true,
  hasError: false
}
                    </code></pre>
          </div>
        </div>
      </section>
      <section data-background-color="#ffffff">
        <h2>Conditional Rendering</h2>
        <pre class="code"><code v-pre>
&lt;div v-if=&quot;type === 'A'&quot;&gt;A&lt;/div&gt;
&lt;div v-else-if=&quot;type === 'B'&quot;&gt;B&lt;/div&gt;
&lt;div v-else-if=&quot;type === 'C'&quot;&gt;C&lt;/div&gt;
&lt;div v-else&gt;Not A/B/C&lt;/div&gt;
            </code></pre>
      </section>
      <section data-background-color="#ffffff">
        <h2>Loops</h2>
        <pre class="code"><code v-pre>
&lt;ul id=&quot;example-1&quot;&gt;
  &lt;li v-for=&quot;item in items&quot;&gt;{{ item.message }}&lt;/li&gt;
&lt;/ul&gt;
            </code></pre>

        <pre class="code"><code class="lang-javascript">
var example1 = new Vue({
  el: '#example-1',
  data: {
    items: [
      { message: 'Foo' },
      { message: 'Bar' }
    ]
  }
})
            </code></pre>
      </section>
      <section data-background-color="#ffffff">
        <h2>Method Event Handlers</h2>
        <pre class="code"><code v-pre>
&lt;div id=&quot;example-2&quot;&gt;
  &lt;button v-on:click=&quot;greet&quot;&gt;Greet&lt;/button&gt;
&lt;/div&gt;
            </code></pre>

        <pre class="code"><code class="lang-javascript">
var example2 = new Vue({
  el: '#example-2',
  data: {
    name: 'Vue.js'
  },
  methods: {
    greet: function (event) {
      // `this` inside methods points to the Vue instance
    }
  }
})
            </code></pre>
      </section>
      <section data-background-color="#ffffff">
        <h2>Form Input Bindings</h2>
        <pre class="code"><code v-pre>
&lt;input v-model=&quot;message&quot; placeholder=&quot;edit me&quot;&gt;
&lt;p&gt;Message is: {{ message }}&lt;/p&gt;
            </code></pre>
      </section>
      <section data-background-color="#ffffff">
        <h2>Event & Key Modifiers</h2>
        <pre class="code"><code v-pre>
&lt;!-- the click event's propagation will be stopped --&gt;
&lt;a @click.stop=&quot;oThis&quot;&gt;&lt;/a&gt;
&lt;!-- the submit event will no longer reload the page --&gt;
&lt;form @submit.prevent=&quot;onSubmit&quot;&gt;&lt;/form&gt;
&lt;!-- modifiers can be chained --&gt;
&lt;a @click.stop.prevent=&quot;doThat&quot;&gt;&lt;/a&gt;
&lt;!-- also available .tab, .delete, .esc, .space, ...--&gt;
&lt;input @keyup.enter=&quot;submit&quot;&gt;
            </code></pre>
      </section>
      <section data-background-color="#ffffff">
        <h2>Component structure</h2>
        <pre class="code"><code class="lang-javascript">
export default {
    name: 'RangeSlider',
    mixins: [], // share common functionality with component mixins
    extends: {}, // compose new components
    props: {}, // component properties/variables
    data() {}, // variables
    computed: {},
    components: {}, // when component uses other components
    watch: {}, // watch wariables
    methods: {}, // methods
    // component Lifecycle hooks
    beforeCreate() {},
    created() {},
    beforeMount() {},
    mounted() {},
    beforeUpdate() {},
    updated() {},
    activated() {},
    deactivated() {},
    beforeDestroy() {},
    destroyed() {},
    errorCaptured() {},
};
            </code></pre>
      </section>
      <section class="etc" data-background-color="#42b883">
        <h2 class="white">Etc...</h2>
        <a class="etc__link" href="https://vuejs.org/v2/guide/">https://vuejs.org/v2/guide/</a>
      </section>

      <section data-background-color="#42b883">
        <h1 class="white">Thanks</h1>
      </section>
    </div>
  </div>
</template>

<script>
import Reveal from 'reveal.js/dist/reveal.esm';
import hljs from 'highlight.js/lib/index';

export default {
  name: 'Reveal',
  props: {},
  mounted() {
    hljs.initHighlightingOnLoad();
    Reveal.initialize({
      history: true,
      transition: 'slide',
    });
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>

</style>
