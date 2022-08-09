<script>
  
</script>

<main>
  <div class="header">
    <h1 class="title">
        This website is for you! <span>Johis!</span> 
    </h1>

    <div class="card-photo">
        <div class="logo-header">
            
        </div>
    </div>
</div>


<div class="container">
    <div id="sunflower">
        <div class="circle">
            <div class="petal1"></div>
            <div class="petal2"></div>
            <div class="petal3"></div>
            <div class="petal4"></div>
            <div class="petal5"></div>
            <div class="petal6"></div>
            <div class="petal7"></div>
            <div class="petal8"></div>
            <div class="petal9"></div>
            <div class="petal10"></div>
            <div class="petal11"></div>
        </div>
        <div>
            <div class="stern"></div>
            <div class="leaf"></div>
            <div class="pot"></div>
            <div class="pot-top"></div>
        </div>
    </div>
    <div class="girasol-text">
        <h2>Girasol, una flor hermosa con un gran significado</h2>
        <p>El girasol, es una flor hermosa, cuyo nombre científico es Helianthus annus. También se lo conoce como maravilla, mirasol, maíz de teja, calom, tlapololote, jáquima, acahual, etcétera. Es nativo de América y se mueve en dirección al sol para abrazar sus rayos. Francisco Pizarro, fue un noble y explorador castellano que conquistó el Perú, donde encontró la flor y la llevó hasta Europa, extendiéndose por todo el mundo.</p>
    </div>
    <div class="girasol-text">
        <h2>¿Por qué regalar girasoles?</h2>
        <p>
            Regalar girasoles tiene diversos significados, pero el que más destaca es sin duda alguna que quien reciba las flores será un sol para ti, que te guía, ilumina y acaricia con sus hermosos y cálidos rayos.
        </p>
        <p>
            Aunque las flores y las plantas dependen del sol, el girasol tiene una estrecha relación con esta maravillosa estrella, dado que no la espera, sino que va en busca de ella. Los girasoles jóvenes, persiguen al sol desde que nace hasta que muere al anochecer.
        </p>
        <p>
            Si alguna vez te encuentras con girasoles que no están mirando al sol, es porque se trata de girasoles de avanzada edad que se orientan al este y por la noche se inclinan como si durmieran.
        </p>
    </div>
    <div></div>
    <div class="girasol-text">
        <h2>¿Cuál es el significado del girasol?</h2>
        <p>
            El color amarillo del girasol representa la fe inquebrantable y está asociado con el chakra del plexo solar. Es un símbolo en la meditación y sus flores expresan la fidelidad, la amistad incondicional y el amor profundo. Por otro lado, regalar un ramo de girasoles puede resultar ideal para abrazar a quienes hayan conseguido una meta, inaugurado un negocio o comenzando un emprendimiento.            
        </p>
    </div>
</div>
</main>

<style>
  .header {
    display:grid;
    justify-content: center;
    align-items: center;
    grid-gap: 17rem;
}

.title {
    text-align: center;
    margin-top: 7rem;
    font-weight: 700;
    font-size: 50px;
    color: white;
}

span {
    display: block;
    font-family: monospace;
    white-space: nowrap;
    border-right: 4px solid;
    width: 6ch;
    
    animation: typing 2s infinite alternate steps(6), blink .5s infinite step-end alternate;
    overflow:hidden;
    }
    
@keyframes typing {
    
    from { width: 0}
}
    
@keyframes blink {
     50% { border-color: transparent}
}

.logo-header {
    background-image: url("./assets/johis.jpg");
    margin:10px auto;
    border-radius:5px;
    border: 1px solid #999;
    padding:13px;
    width:220px;
    height:220px;
    background-repeat:no-repeat;
    background-size: cover;
    box-shadow:  26px 26px 52px #a1a1a1,
                -26px -26px 52px #ffffff;
}

.logo-header:hover {
    height: 300px;
    width: 300px;
}


.container {
    display: grid;
    justify-content: center;
    grid-template-columns: 1fr 1fr;
    grid-template-rows: auto;
    padding: 10rem;
}

#sunflower {
    display: grid;
    place-items: center;
    padding: 19rem;
}

.circle {
    background-image: radial-gradient(brown 20%, transparent 20%);
    background-color: #592d0d;
    /* background-position: 0 0, 50px 50px; */
    background-size: 22px 22px;
    height: 12rem;
    width: 12rem;
    border-radius: 50%;
    /* position: relative; */
    border: 10px solid brown;
}

.petal1 {
    border: 10px solid rgb(199, 199,33);
    border-radius: 50px 50px 20px 20px / 100px 100px 40px;
    background-color: yellow;
    width: 50px;
    height: 150px;
    position: relative;
    bottom: 154px;
    left: 10px;
    transform: rotate(-8deg);  
}

.petal2 {
    border: 10px solid rgb(199, 199,33);
    border-radius: 50px 50px 20px 20px / 100px 100px 40px;
    background-color: yellow;
    width: 50px;
    height: 150px;
    position: relative;
    bottom: 291px;
    left: 89px;
    transform: rotate(29deg); 
}

.petal3 {
    border: 10px solid rgb(199, 199,33);
    border-radius: 50px 50px 20px 20px / 100px 100px 40px;
    background-color: yellow;
    width: 50px;
    height: 150px;
    position: relative;
    bottom: 383px;
    left: 137px;
    transform: rotate(66deg);
}

.petal4 {
    border: 10px solid rgb(199, 199,33);
    border-radius: 50px 50px 20px 20px / 100px 100px 40px;
    background-color: yellow;
    width: 50px;
    height: 150px;
    position: relative;
    bottom: 465px;
    left: 150px;
    transform: rotate(90deg);
}

.petal5 {
    border: 10px solid rgb(199, 199,33);
    border-radius: 50px 50px 20px 20px / 100px 100px 40px;
    background-color: yellow;
    width: 50px;
    height: 150px;
    position: relative;
    bottom: 542px;
    left: 121px;
    transform: rotate(127deg);
}

.petal6 {
    border: 10px solid rgb(199, 199,33);
    border-radius: 50px 50px 20px 20px / 100px 100px 40px;
    background-color: yellow;
    width: 50px;
    height: 150px;
    position: relative;
    bottom: 645px;
    left: 59px;
    transform: rotate(160deg);
}

.petal7 {
    border: 10px solid rgb(199, 199,33);
    border-radius: 50px 50px 20px 20px / 100px 100px 40px;
    background-color: yellow;
    width: 50px;
    height: 150px;
    position: relative;
    bottom: 796px;
    left: 3px;
    transform: rotate(184deg);
}

.petal8 {
    border: 10px solid rgb(199, 199,33);
    border-radius: 50px 50px 20px 20px / 100px 100px 40px;
    background-color: yellow;
    width: 50px;
    height: 150px;
    position: relative;
    bottom: 972px;
    left: -55px;
    transform: rotate(210deg);
}

.petal9 {
    border: 10px solid rgb(199, 199,33);
    border-radius: 50px 50px 20px 20px / 100px 100px 40px;
    background-color: yellow;
    width: 50px;
    height: 150px;
    position: relative;
    bottom: 1172px;
    left: -98px;
    transform: rotate(240deg);
}

.petal10 {
    border: 10px solid rgb(199, 199,33);
    border-radius: 50px 50px 20px 20px / 100px 100px 40px;
    background-color: yellow;
    width: 50px;
    height: 150px;
    position: relative;
    bottom: 1393px;
    left: -104px;
    transform: rotate(275deg);
}

.petal11 {
    border: 10px solid rgb(199, 199,33);
    border-radius: 50px 50px 20px 20px / 100px 100px 40px;
    background-color: yellow;
    width: 50px;
    height: 150px;
    position: relative;
    bottom: 1616px;
    left: -66px;
    transform: rotate(312deg);
}

.stern {
    height: 400px;
    width: 40px;
    background-color: green;
    border: 10px solid rgb(1, 51, 1);
    position: relative;
    bottom: 100px;
    left: 132px;
    overflow: hidden;
    z-index: -1;
}

.leaf {
    width: 150px;
    height: 150px;
    border-radius: 0% 100% 0% 100% / 0% 100% 0% 100%;
    background-color: green;
    border: 10px solid rgb(1, 51, 1);
    position: relative;
    bottom: 363px;
    right: 14px;
    z-index: -1;
}

.pot {
    height: 300px;
    width: 150px;
    background-color: rgb(88, 38, 9);
    clip-path: polygon(1% 0, 100% 0, 93% 100%, 17% 100%);
    position: relative;
    bottom: 300px;
    right: -77px;
    border: 1px solid rgb(39, 13, 3);
}

.pot-top {
    height: 10px;
    width: 300px;
    background-color: rgb(88, 38, 9);
    border: 5px solid rgb(39, 13, 3);
    position: relative;
    bottom: 605px;
    right: -9px;
}

.girasol-text {
    display: flex;
    margin-top: 2rem;
    flex-direction: column;
    color: aliceblue;
    padding: 1rem;
}


@media  screen and (max-width: 375px) {

    h2 {
        font-size: 2.5rem;
    }

    p {
        font-size: 1.5rem;
    }

    .title {
        font-size: 3rem;
    }

    .container {
        grid-template-columns: none;
    }
}
</style>
