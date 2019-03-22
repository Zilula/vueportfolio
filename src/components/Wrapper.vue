<template>
    <div id="content">
        <img id="logo" src="../assets/logo.png" alt="lance merril`s logo">
        <h1 class="text">Lance<br>Merrill</h1>
        <div class="break"></div>
        <p class="text">Software engineer and general nerd.</p>
        <div class="break"></div>
        <section class="text">
            <p>
                Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s
            </p>
        </section>
        <div class="break"></div>
        <section>
            <h3 class="text">Inquisitive</h3>
            <p class="text">
                I have a legitimate passion for new technology and am committed to being a life long learner.  
            </p>
            <div class="dualContainer">
                <img id="mernImage" src="../assets/mern.png" alt="Mern Tech Stack">
                <div>
                <h4 class="text">Stack</h4>
                    <div class="break"></div>
                    <ul class="text">
                        <li>Node</li>
                        <li>Express</li>
                        <li>React</li>
                        <li>Redux</li>
                        <li>Vue</li>
                        <li>MongoDB</li>
                        <li>mySQL</li>
                        <li>Firebase</li>
                    </ul>
                </div>
            </div>
            
        </section>
    </div>
</template>

<script>

export default {

};
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css?family=Montserrat');
@media only screen and (min-width: 600px) {
  #content {
      max-width: 50%;
  }
}
#logo {
    max-width: 150px;
    max-height: 150px;
  margin-left: auto;
  margin-right: auto;}

#content {
    background-color: rgba(0, 0, 0, 0.502);
    margin: auto;
    border-radius: 1em;
}
h1 {
    letter-spacing: .3em;
    font-size: 2.3em;
    text-align: center;
    bottom: 25%;
    text-transform: uppercase;
}
h2 {
    font-size: 1.1em;
}
h3 {
      text-transform: uppercase;

}
.text {
    font-family:'Montserrat', sans-serif;
    color: white;
    text-align: center;
    margin: .3em;

}
.break {
    border-bottom: rgba(255, 255, 255, 0.495) solid 1px;
    margin: 2em;
}
.dualContainer {
    display: grid;
    grid-template-columns: 50% 50%;
}
#mernImage {
    width: 100%;
    height: auto;
    margin:auto;

}
ul {
    list-style-type: none;
    align-items: center;
    padding:0;
}



</style>
