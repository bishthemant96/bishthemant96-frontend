<template>
  <div id="app">
    <div id="text-introduction">
      <div id="salutation"> Hi, there! </div>
      <br />
      <div id="name"> I am Hemant Singh Bisht. </div>
      <br />
      <div id="introduction"> A software engineer with ~2 years of experience in building responsive and modular web-applicat
      ions using various JavaScript frameworks such as React.js and Vue.js, is eager to use his techn
      ical skills in building the future of web. </div>
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
</style>>