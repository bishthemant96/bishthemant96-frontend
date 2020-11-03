<template>
  <div id="app">
    <div id="text-introduction">
      <div id="salutation"> Hi, there! </div>
      <br />
      <div id="name"> I am Hemant Singh Bisht. </div>
      <br />
      <div id="introduction"> 
        A software engineer with ~2 years of experience in building responsive and modular web-appl
        ications using various JavaScript frameworks such as React.js and Vue.js, is eager to use 
        his technical skills in building the future of web.

        <br />
        <br />

        I wanted to be a magician ever since I saw that transparent-body cathode-ray-tube monitor, 
        back in 2006, and wrote my first magical glittery-moving-text HTML on it. So, Here I am wor
        king as an associate magician in a booming company with a few tricks up my sleeve. 
        
        <br />
        <br />

        Wanna see some magic? <a id="link-linkedin" href="https://www.linkedin.com/in/bishthemant96/"> Contact me. </a> 

      </div>
    </div>

    <div id="image-introduction"> 
      <img id="image" src="./assets/display.jpg"/>
    </div>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style scoped>
  #app {
    display: flex;

    padding: 50px 100px;

    font-family: 'Roboto', sans-serif;
    font-size: 1.5em;
    font-weight: 300;
  }

  #text-introduction {
    width: 50%;
  }

  #image-introduction{
    display: flex;
    justify-content: space-around;
    align-items: center;

    width: 50%;
  }

  #image {
    width: 500px;
    height: 500px;
  }

  #salutation {
    width: auto;

    font-size: 2.5em;
    font-weight: 500;
  }

  #name {
    width: auto;

    font-size: 1.5em;
    font-weight: 400;
  }

  #introduction {
    text-align: justify;
    text-justify: inter-word;
  }

  #link-linkedin {
    text-decoration: none;
  }
</style>>