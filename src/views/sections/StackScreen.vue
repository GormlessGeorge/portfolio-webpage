<template>
  <section class="stack" id="stack">
    <TheContainer>
<<<<<<< HEAD
      <div class="stack__main_wrapper fade-in" data-fade-in-time="0.6s">
=======
      <div class="stack__main_wrapper">
>>>>>>> 12bd3b50cfa8cea9a29099f1569d67e2cbb123ff
        <div class="stack__tabs_wrapper">
          <div class="stack__tabs">
            <div class="stack__tab_title" @click="selectedTab = 'tab1'"
              :class="{ 'stack__tab_title-active': selectedTab === 'tab1', [currentColorClass]: selectedTab === 'tab1' }">
              Frontend</div>
            <p class="stack__delimiter"
              :class="{ 'stack__delimiter-active': selectedTab === 'tab1' || selectedTab === 'tab2', [currentColorClass]: selectedTab === 'tab1' || selectedTab === 'tab2' }">
              |</p>
            <div class="stack__tab_title" @click="selectedTab = 'tab2'"
              :class="{ 'stack__tab_title-active': selectedTab === 'tab2', [currentColorClass]: selectedTab === 'tab2' }">
              Backend</div>
            <p class="stack__delimiter"
              :class="{ 'stack__delimiter-active': selectedTab === 'tab2' || selectedTab === 'tab3', [currentColorClass]: selectedTab === 'tab2' || selectedTab === 'tab3' }">
              |</p>
            <div class="stack__tab_title" @click="selectedTab = 'tab3'"
              :class="{ 'stack__tab_title-active': selectedTab === 'tab3', [currentColorClass]: selectedTab === 'tab3' }">
              Tools</div>
          </div>

          <div class="stack__tab_content">
            <transition name="fade" mode="out-in">
              <div v-if="selectedTab === 'tab1'" key="tab1" class="stack__tab">
                <div class="stack__icon" @click="store.applyJsColor">
<<<<<<< HEAD
                  <img src="@/assets/icons/tech_icons/png/js_icon.png" alt="javascript_icon" />
                </div>
                <div class="stack__icon" @click="store.applyTsColor">
                  <img src="@/assets/icons/tech_icons/png/ts_icon.png" alt="typescript_icon" />
                </div>
                <div class="stack__icon" @click="store.applyVueColor">
                  <img src="@/assets/icons/tech_icons/png/vue_icon.png" alt="vue_icon" />
                </div>
                <div class="stack__icon" @click="store.applyHtmlColor">
                  <img src="@/assets/icons/tech_icons/png/html_icon.png" alt="html_icon" />
                </div>
                <div class="stack__icon" @click="store.applyCssColor">
                  <img src="@/assets/icons/tech_icons/png/css_icon.png" alt="css_icon" />
                </div>
                <div class="stack__icon" @click="store.applySassColor">
                  <img src="@/assets/icons/tech_icons/png/sass_icon.png" alt="sass_icon" />
                </div>
                <div class="stack__icon" @click="store.applyInertiaColor">
                  <img src="@/assets/icons/tech_icons/png/inertia_icon.png" alt="inertia_icon" />
                </div>
                <div class="stack__icon" @click="store.applyViteColor">
                  <img src="@/assets/icons/tech_icons/png/vite_icon.png" alt="vitejs_icon" />
=======
                  <img src="../../assets/icons/tech_icons/js_icon.svg" alt="javascript_icon" />
                </div>
                <div class="stack__icon" @click="store.applyTsColor">
                  <img src="../../assets/icons/tech_icons/ts_icon.svg" alt="typescript_icon" />
                </div>
                <div class="stack__icon" @click="store.applyVueColor">
                  <img src="../../assets/icons/tech_icons/vue_icon.svg" alt="vue_icon" />
                </div>
                <div class="stack__icon" @click="store.applyHtmlColor">
                  <img src="../../assets/icons/tech_icons/html_icon.svg" alt="html_icon" />
                </div>
                <div class="stack__icon" @click="store.applyCssColor">
                  <img src="../../assets/icons/tech_icons/css_icon.svg" alt="css_icon" />
                </div>
                <div class="stack__icon" @click="store.applySassColor">
                  <img src="../../assets/icons/tech_icons/sass_icon.svg" alt="sass_icon" />
                </div>
                <div class="stack__icon" @click="store.applyInertiaColor">
                  <img src="../../assets/icons/tech_icons/inertia_icon.svg" alt="inertia_icon" />
                </div>
                <div class="stack__icon" @click="store.applyViteColor">
                  <img src="../../assets/icons/tech_icons/vitejs_icon.svg" alt="vitejs_icon" />
>>>>>>> 12bd3b50cfa8cea9a29099f1569d67e2cbb123ff
                </div>

                <div class="stack__icon">
                  And more!
                </div>
              </div>


              <div v-else-if="selectedTab === 'tab2'" key="tab2" class="stack__tab">
                <div class="stack__icon" @click="store.applyJavaColor">
<<<<<<< HEAD
                  <img loading="lazy" src="@/assets/icons/tech_icons/java_icon.svg" alt="java_icon" />
                </div>
                <div class="stack__icon" @click="store.applyKotlinColor">
                  <img loading="lazy" src="@/assets/icons/tech_icons/kotlin_icon.svg" alt="kotlin_icon" />
                </div>
                <div class="stack__icon" @click="store.applyPhpColor">
                  <img loading="lazy" src="@/assets/icons/tech_icons/php_icon.svg" alt="php_icon" />
                </div>
                <div class="stack__icon" @click="store.applyLaravelColor">
                  <img loading="lazy" src="@/assets/icons/tech_icons/laravel_icon.svg" alt="laravel_icon" />
                </div>
                <div class="stack__icon" @click="store.applyMysqlColor">
                  <img loading="lazy" src="@/assets/icons/tech_icons/mysql_icon.svg" alt="mysql_icon" />
                </div>
                <div class="stack__icon" @click="store.applyPostgresColor">
                  <img loading="lazy" src="@/assets/icons/tech_icons/postgresql_icon.svg" alt="postgresql_icon" />
                </div>
                <div class="stack__icon" @click="store.applyRabbitColor">
                  <img loading="lazy" src="@/assets/icons/tech_icons/rabbit_icon.svg" alt="rabbitmq_icon" />
                </div>
                <div class="stack__icon" @click="store.applyRedisColor">
                  <img loading="lazy" src="@/assets/icons/tech_icons/redis_icon.svg" alt="redis_icon" />
=======
                  <img src="../../assets/icons/tech_icons/java_icon.svg" alt="java_icon" />
                </div>
                <div class="stack__icon" @click="store.applyKotlinColor">
                  <img src="../../assets/icons/tech_icons/kotlin_icon.svg" alt="kotlin_icon" />
                </div>
                <div class="stack__icon" @click="store.applyPhpColor">
                  <img src="../../assets/icons/tech_icons/php_icon.svg" alt="php_icon" />
                </div>
                <div class="stack__icon" @click="store.applyLaravelColor">
                  <img src="../../assets/icons/tech_icons/laravel_icon.svg" alt="laravel_icon" />
                </div>
                <div class="stack__icon" @click="store.applyMysqlColor">
                  <img src="../../assets/icons/tech_icons/mysql_icon.svg" alt="mysql_icon" />
                </div>
                <div class="stack__icon" @click="store.applyPostgresColor">
                  <img src="../../assets/icons/tech_icons/postgresql_icon.svg" alt="postgresql_icon" />
                </div>
                <div class="stack__icon" @click="store.applyRabbitColor">
                  <img src="../../assets/icons/tech_icons/rabbit_icon.svg" alt="rabbitmq_icon" />
                </div>
                <div class="stack__icon" @click="store.applyRedisColor">
                  <img src="../../assets/icons/tech_icons/redis_icon.svg" alt="redis_icon" />
>>>>>>> 12bd3b50cfa8cea9a29099f1569d67e2cbb123ff
                </div>
                <div class="stack__icon">
                  And more!
                </div>
              </div>

              <div v-else-if="selectedTab === 'tab3'" key="tab3" class="stack__tab">
                <div class="stack__icon" @click="store.applyFigmaColor">
<<<<<<< HEAD
                  <img loading="lazy" src="@/assets/icons/tech_icons/figma_icon.svg" alt="figma_icon" />
                </div>
                <div class="stack__icon" @click="store.applyPsColor">
                  <img loading="lazy" src="@/assets/icons/tech_icons/ps_icon.svg" alt="photoshop_icon" />
                </div>
                <div class="stack__icon" @click="store.applyVscodeColor">
                  <img loading="lazy" src="@/assets/icons/tech_icons/vscode_icon.svg" alt="vscode_icon" />
                </div>
                <div class="stack__icon" @click="store.applyIjColor">
                  <img loading="lazy" src="@/assets/icons/tech_icons/ij_icon.svg" alt="ij_icon" />
                </div>
                <div class="stack__icon" @click="store.applyWebstormColor">
                  <img loading="lazy" src="@/assets/icons/tech_icons/webstorm_icon.svg" alt="webstorm_icon" />
                </div>
                <div class="stack__icon" @click="store.applyPhpstormColor">
                  <img loading="lazy" src="@/assets/icons/tech_icons/phpstorm_icon.svg" alt="phpstorm_icon" />
                </div>
                <div class="stack__icon" @click="store.applyGitColor">
                  <img loading="lazy" src="@/assets/icons/tech_icons/git_icon.svg" alt="git_icon" />
                </div>
                <div class="stack__icon" @click="store.applyPostmanColor">
                  <img loading="lazy" src="@/assets/icons/tech_icons/postman_icon.svg" alt="postman_icon" />
=======
                  <img src="../../assets/icons/tech_icons/figma_icon.svg" alt="figma_icon" />
                </div>
                <div class="stack__icon" @click="store.applyPsColor">
                  <img src="../../assets/icons/tech_icons/ps_icon.svg" alt="photoshop_icon" />
                </div>
                <div class="stack__icon" @click="store.applyGptColor">
                  <img src="../../assets/icons/tech_icons/gpt_icon.svg" alt="gpt_icon" />
                </div>
                <div class="stack__icon" @click="store.applyIjColor">
                  <img src="../../assets/icons/tech_icons/ij_icon.svg" alt="ij_icon" />
                </div>
                <div class="stack__icon" @click="store.applyVscodeColor">
                  <img src="../../assets/icons/tech_icons/vscode_icon.svg" alt="vscode_icon" />
                </div>
                <div class="stack__icon" @click="store.applyPhpstormColor">
                  <img src="../../assets/icons/tech_icons/phpstorm_icon.svg" alt="phpstorm_icon" />
                </div>
                <div class="stack__icon" @click="store.applyGitColor">
                  <img src="../../assets/icons/tech_icons/git_icon.svg" alt="git_icon" />
                </div>
                <div class="stack__icon" @click="store.applyPostmanColor">
                  <img src="../../assets/icons/tech_icons/postman_icon.svg" alt="postman_icon" />
>>>>>>> 12bd3b50cfa8cea9a29099f1569d67e2cbb123ff
                </div>
                <div class="stack__icon">
                  And more!
                </div>
              </div>
            </transition>
          </div>
        </div>

        <div class="stack__descr">
          <div :class="store.currentColorClass" class="stack__light"></div>
          <h2 :class="store.currentColorClass" class="stack__title">Tech <span>stack</span></h2>
          <transition name="fade" mode="out-in">
<<<<<<< HEAD
            <p v-if="selectedTab === 'tab1'" class="stack__text" :class="store.currentColorClass">I work with a robust
              stack of frontend technologies.
              Starting with <span>JavaScript</span>
              for dynamic and interactive content, <span>TypeScript</span> adds type
              safety and efficiency.
              <span>Vue.js</span> is my go-to for building user interfaces.
              <br><br><span :class="store.currentColorClass">HTML</span> and <span
                :class="store.currentColorClass">CSS</span> lay the foundation
              for structure and design,
              with <span :class="store.currentColorClass">Sass</span> enhancing the maintainability and
              flexibility.<br><br> <span :class="store.currentColorClass">Inertia.js</span> paired with Laravel
              simplifies
              single-page application development, while <span :class="store.currentColorClass">Vite</span> ensures a
              fast and efficient build process.
            </p>
            <p v-else-if="selectedTab === 'tab2'" class="stack__text" :class="store.currentColorClass">
              I have a solid foundation in backend technologies. While I have extensive experience with
              <span>Java</span> and <span>Kotlin</span>,
              my current focus is primarily on <span>PHP</span> and the <span>Laravel</span> framework, which I use
              extensively for most of my
              projects.<br><br><span>MySQL</span> serves as my primary database system, and I have a working knowledge
              of <span>PostgreSQL</span>, which
              I utilize when specific project requirements call for it. <br><br>Additionally, I’m familiar with
              <span>RabbitMQ</span>
              for
               message queuing and <span>Redis</span> for caching.
            </p>
=======
            <p v-if="selectedTab === 'tab1'" class="stack__text">Lorem ipsum dolor sit amet consectetur. Egestas libero
              nascetur nibh dictumst quis id curabitur. Tellus turpis est turpis nibh senectus nisi tincidunt nibh.
              Lectus
              vel cras risus vestibulum. Tortor urna orci sed sodales amet nibh congue quisque ut.</p>
            <p v-else-if="selectedTab === 'tab2'" class="stack__text">2efwef</p>
>>>>>>> 12bd3b50cfa8cea9a29099f1569d67e2cbb123ff
            <p v-else-if="selectedTab === 'tab3'" class="stack__text">3wdawd</p>
          </transition>
        </div>

      </div>
    </TheContainer>

  </section>
</template>

<script setup lang="ts">
import { ref } from 'vue';
import { usePortfolioStore } from '../../store/portfolio-store';
import { storeToRefs } from 'pinia';
const store = usePortfolioStore();
const { currentColorClass } = storeToRefs(store);
const selectedTab = ref('tab1');
</script>

<style scoped lang="scss">
svg {
  position: absolute;
}

<<<<<<< HEAD

.stack {
  display: flex;
  align-items: center;
  position: relative;
  width: 100%;
  height: 100vh;
  overflow: auto;

  &__main_wrapper {
    // margin-top: 20vh;
    transform: translateY(100px);
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    opacity: 0;
=======
h2 {
  color: white;
}

.stack {
  position: relative;
  width: 100%;
  height: 100vh;
  // scroll-snap-align: center;
  overflow: auto;
  // scroll-behavior: smooth;

  &__main_wrapper {
    margin-top: 20vh;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
>>>>>>> 12bd3b50cfa8cea9a29099f1569d67e2cbb123ff
  }

  &__tabs_wrapper {
    width: 50%;
    display: flex;
    flex-direction: column;

    justify-content: space-between;
  }

  &__tabs {
    display: flex;
    flex-direction: row;
    gap: 20px;
    margin-top: 20px;
  }

  &__tab_title {
<<<<<<< HEAD
    align-content: center;
    transition: all 1s;
    cursor: pointer;
    width: 160px;
    color: var(--text-color);
=======
    transition: all 1s;
    cursor: pointer;
    width: 160px;
    color: white;
>>>>>>> 12bd3b50cfa8cea9a29099f1569d67e2cbb123ff
    text-align: center;
    font-weight: 600;
    font-size: 20px;

    &-active {
      transition: all 1s;
      color: var(--primary-color);
    }
  }

  &__delimiter {
    align-self: center;
<<<<<<< HEAD
    color: var(--text-color);
=======
    color: white;
>>>>>>> 12bd3b50cfa8cea9a29099f1569d67e2cbb123ff
    transition: all 1s;

    &-active {
      transition: all 1s;
      color: var(--primary-color);
    }
  }

  &__tab {
    display: flex;
    flex-wrap: wrap;
    gap: 70px;
<<<<<<< HEAD
    margin-top: 45px;
=======
    margin-top: 60px;
>>>>>>> 12bd3b50cfa8cea9a29099f1569d67e2cbb123ff
    padding-left: 5%;

  }

  &__icon {
    transition: transform 0.5s;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 120px;
    width: 120px;
    backdrop-filter: blur(4px);
<<<<<<< HEAD
    background: var(--stack-icon-bg);
    color: var(--text-color);

    &:hover {
      transition: transform 0.5s linear;
      transform: scale(1.05);
      cursor: pointer;
    }

    &:last-child {
      &:hover {
        transform: none;
        cursor: default
=======
    background: rgba(255, 255, 255, 0.05);
    color: white;

    &:hover {
      transition: transform 0.5s linear;
      transform: scale(1.1);
    }
    &:last-child {
      &:hover {
        transform:none;
>>>>>>> 12bd3b50cfa8cea9a29099f1569d67e2cbb123ff
      }
    }

  }

  &__descr {
    width: 50%;
    position: relative;

  }

  &__title {
<<<<<<< HEAD
    color: var(--text-color);
    font-size: 48px;
    font-weight: 700;
    text-align: center;
  }

  span {
    transition: all 1s;
    color: var(--primary-color);
    text-shadow: 5px 5px 20px var(--hover-color);
    font-weight: 600;
=======
    color: white;
    font-size: 48px;
    font-weight: 700;
    text-align: center;

    span {
      transition: all 1s;
      color: var(--primary-color);
      // background: linear-gradient(90deg, #765af8 0%, #b843ea 50%, #fd318e 100%);
      // -webkit-background-clip: text;
      // -webkit-text-fill-color: transparent;
      // background-size: 200% 200%;
      // -webkit-animation: gradientChange 10s ease infinite;
      // -moz-animation: gradientChange 10s ease infinite;
      // animation: gradientChange 10s ease infinite;
      text-shadow: 5px 5px 20px var(--hover-color);

    }
>>>>>>> 12bd3b50cfa8cea9a29099f1569d67e2cbb123ff
  }

  &__light {
    transition: all 1s;
    top: 60px;
    z-index: -5;
    position: absolute;
    border-radius: 100%;
    width: 500px;
    height: 500px;
    background-color: var(--light-color);
    filter: blur(50px);
<<<<<<< HEAD
=======
    // background: linear-gradient(0deg,
    //     rgba(148, 84, 233, 0.2) 0%,
    //     rgba(130, 100, 235, 0.2) 50%,
    //     rgba(109, 116, 237, 0.2) 100%);
    // filter: blur(75px);
    // background-size: 200% 200%;
    // -webkit-animation: gradientChange 10s ease infinite;
    // -moz-animation: gradientChange 10s ease infinite;
    // animation: gradientChange 10s ease infinite;
>>>>>>> 12bd3b50cfa8cea9a29099f1569d67e2cbb123ff
  }


  &__text {
    display: block;
    margin: 0 auto;
    margin-top: 40px;
<<<<<<< HEAD
    width: 470px;
    line-height: 2.2rem;
    font-weight: 300;
    font-size: 1.25rem;
    color: var(--text-color);
=======
    width: 440px;
    line-height: 2.2rem;
    font-weight: 300;
    font-size: 1.25rem;
    color: #fcfcfc;
>>>>>>> 12bd3b50cfa8cea9a29099f1569d67e2cbb123ff
  }
}

.fade-enter-active,
.fade-leave-active {
  transition: opacity 0.3s ease;
}

.fade-enter-from,
.fade-leave-to {
  opacity: 0;
}

p {
  color: white;
}
</style>