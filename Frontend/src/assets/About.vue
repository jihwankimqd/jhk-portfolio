<template>
  <div id="app">
    <!-- <div class="container"> -->
        <section id="intro">
                <div id="text">
                <!-- <a href="about.html">about</a> -->
                <h3>Ji Hwan KIM</h3>
                <br>
                <p>Pursuing a BSc in Physics at <b>HKUST</b> (2022/June).<br/>
                Software Engineer Intern at <b>Intel</b> for one year. <br>
                Strong background in teamwork and communication. <br>
                </p>
                </div> 
        </section>

        <section id="programming">
                <div id="text">
                    <h3>Software Engineer</h3>
                    <br>
                    <p>Self-taught, <b>Intel</b> trained.<br>
                    <br>
                        Self-taught in Python, C++, JavaScript, CSS, HTML,<br>
                        along with other languages/libraries/frameworks <br>
                        and mastered them in a professional environment <br>
                        during my 1 year Software Engineer Internship at <b>Intel</b>.                        
                    <br>
                    </p>
                </div> 
        </section>

        <section id="Interpersonal">
                <div id="text">
                    <h3>Communicator and Leader</h3>
                    <br>
                    <p>
                        I have spent 21 months with US Forces Korea interpreting and translating <br>
                        military language and documents for high ranking US/ROK officers under <br>
                        intense training environments. I am trained to perform under pressure.<br>
                        Furthermore, as a former band leader, I have organised and performed <br>
                        concerts in front of hundreds while leading and managing the members.   
                    </p>
                </div> 
        </section>

        <section id="background">
                <div id="text">
                    <h3>International</h3>
                    <br>
                    <p>
                        I have lived in 6 different countries- Korea, Malaysia, China,<br>
                        Indonesia, Hong Kong, and the Philippines. I speak Korean (Native), <br> 
                        English (Fluent), Mandarin (Basic), Indonesian (Basic). I really <br>
                        get along with everyone from any background and culture.
                    </p>
                </div> 
        </section>

        <section id="background">
                <div id="text">
                    <h3><a href="https://github.com/jihwankimqd/jhk-portfolio/raw/main/Frontend/docs/JIHWANKIM_CV.pdf">Resume</a></h3>
                    <br>
                    <p>
                    </p>
                </div> 
        </section>
    <!-- </div> -->
  </div>
</template>

<script>

export default {
  name: 'App',
  components: {
    
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  height: 100vh;
  line-height: 1.6;
  overflow: hidden;
    /* width: 100%; */
    /* height: 100%; */
    /* CSS Smooth Scroll */
    overflow-y: scroll; 
    scroll-behavior: smooth;
    scroll-snap-type: y mandatory;
}
    * {
      margin: 0;
      padding: 0;
    }


    .container {

    }

    .lead {
      font-size: 1.5rem;
    }

    section {
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      text-align: center;
      width: 100%;
      height: 100vh;
    
      /* Scroll Snap */
      scroll-snap-align: center;
    }


  #text {
    /* margin-top: -250px; */
    text-align: center;
  }

  a, u {
  text-decoration: none;
  }

</style>
