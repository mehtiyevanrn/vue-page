<template>
      <header id="home">
        <div class="container">
            <nav class="navbar navbar-expand-lg navbar-dark  my-nav">
                <a class="navbar-brand text-uppercase" href="#">YOU-PS.Ru - Best PSD</a>
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarCollap"
                    aria-controls="navbarCollap" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarCollap">
                    <ul class="navbar-nav ms-auto">
                        <li class="nav-item">
                            <a href="index.html" class="nav-link active " id="home">Home</a>
                        </li>
                        <li class="nav-item">
                            <a href="services.html" class="nav-link" id="services">Services</a>
                        </li>
                        <li class="nav-item">
                            <a href="about.html" class="nav-link " id="about">About</a>
                        </li>
                        <li class="nav-item">
                            <a href="work.html" class="nav-link" id="work">Work</a>
                        </li>
                        <li class="nav-item">
                            <a href="contact.html" class="nav-link" id="contacts">Contacts</a>
                        </li>
                    </ul>
                </div>
            </nav>
        </div>
        <div id="carouselExampleIndicators" class="carousel slide" data-bs-ride="carousel">
            <div class="carousel-indicators">
                <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0"
                    class=" slide-btn active" aria-current="true" aria-label="Slide 1"></button>
                <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1"
                    aria-label="Slide 2" class=" slide-btn"></button>
                <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2"
                    aria-label="Slide 3" class=" slide-btn"></button>
            </div>
            <div class="carousel-inner">
                <div class="carousel-item active">
                    <img src="../assets/img/Layer 2.png" class="d-block w-100" alt="picture">
                    <div class="img-overlay">
                        <div>
                            <h1>good ideas </h1><span>comes</span>
                        </div>
                        <div>
                            <h2>first!</h2>
                        </div>
                    </div>
                </div>
                <div class="carousel-item">
                    <img src="../assets/img/Layer 2.png" class="d-block w-100" alt="picture">
                    <div class="img-overlay">
                        <div>
                            <h1>good ideas </h1><span>comes</span>
                        </div>
                        <div>
                            <h2>first!</h2>
                        </div>
                    </div>
                </div>
                <div class="carousel-item">
                    <img src="../assets/img/Layer 2.png" class="d-block w-100" alt="picture">
                    <div class="img-overlay">
                        <div>
                            <h1>good ideas </h1><span>comes</span>
                        </div>
                        <div>
                            <h2>first!</h2>
                        </div>
                    </div>
                </div>
            </div>
            <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleIndicators"
                data-bs-slide="prev">
                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Previous</span>
            </button>
            <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleIndicators"
                data-bs-slide="next">
                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Next</span>
            </button>
        </div>
      
    </header>

</template>

<style scoped>
header nav {
    background-color: transparent;
    position: absolute !important;
    top: 0;
    width:85%;
    z-index:999;
 }

.navbar{
    padding: 0 !important;
}
.my-nav .navbar-nav {
    margin-right: 80px;
    padding:0 !important;
}


.my-nav .navbar-brand {
    font-size: 40px;
    line-height: 70px;
    color: #fff;
    font-weight: 400;
    font-family: "Damion";
    text-align: center;
    padding:0 !important
}

.my-nav .nav-link {
    font-size: 18px;
    color: #fff !important;
    font-weight: 400;
    font-family: "Lato";
    text-align: center;
    margin-right: 20px;
    width: 82px;
    height: 70px;
    line-height: 70px;
    border-radius: 0 0 5px 5px;
    

}

.my-nav .nav-link:hover {
    color: #fff;
}

.my-nav #home.active {
    background-color: #74c7d5
}

.my-nav #services.active {
    background-color: #df5c64;
}

.my-nav #about.active {
    background-color: #91778e;
}

.my-nav #work.active {
    background-color: #a1ca6c;
}

.my-nav #contacts.active {
    background-color: #82c8bd;
}

.carousel {
    height: 100vh;
    width:100vw

}

.carousel-item img {
    height: 100vh;
    width:100vw
}

.carousel .img-overlay {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    background-color: rgba(255, 255, 255, 0.4);
    width: 65%;
    height: 22% ;
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    justify-content: center;
}

.carousel .img-overlay h1 {
    font-size:60px;
    line-height: 58px;
    color: #74c7d5;
    font-weight: 300;
    font-family: "Lato";
    text-transform: uppercase;
}

.carousel .img-overlay span {
    font-size: 60px;
    line-height: 30px;
    color: #74c7d5;
    font-weight: 300;
    font-family: "Lato";
    margin-left: 200px;
    text-transform: lowercase;
}

.carousel .img-overlay h2 {
    font-size: 128px;
    line-height: 128px;
    color: #74c7d5;
    font-weight: 900;
    font-family: "Lato";
    text-align: right;
    text-transform: uppercase;
}

.carousel .slide-btn {
    border-radius: 50%;
    width: 13px;
    height: 13px;
    margin-right: 15px;
    margin-bottom: 10px;
}

.carousel .slide-btn.active {
    background-color: #74c7d5;
}
</style>