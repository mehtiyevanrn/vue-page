<template>
      <section class="services">
        <div class="container">
            <nav class="navbar navbar-expand-lg my-nav navbar-dark">
                <a class="navbar-brand text-lowercase" href="#">acrostia</a>
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarCollap"
                    aria-controls="navbarCollap" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarCollap">
                    <ul class="navbar-nav ms-auto">
                        <li class="nav-item">
                            <a href="index.html" class="nav-link " id="home">Home</a>
                        </li>
                        <li class="nav-item">
                            <a href="services.html" class="nav-link active" id="services">Services</a>
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
            <div class="section-heading" data-aos="fade-right" data-aos-delay="200" data-aos-duration="1000">
                <h1>OUR SERVICES</h1>
                <h3> Cras commodo mattis justo nec lobortis. Nam ut tellus lobortis, ullamcorper massa sit amet</h3>
                <p>Cras suscipit porttitor porttitor. Morbi sit amet tincidunt sapien. Curabitur posuere lectus aliquet
                    erat rutrum sollicitudin. In enim diam, ullamcorper quis libero et, ultricies commodo est. Quisque
                    at ante vitae justo fermentum viverra ac eu justo. Ut luctus imperdiet lacus, eget laoreet erat
                    posuere quis.</p>
            </div>
            <div class="row d-flex justify-content-center aling-items-center" data-aos="zoom-in-down" data-aos-delay="200" data-aos-duration="1000">
                <div class="col-md-3 services-blog">
                    <div class="logo">
                        <i class="fa-solid fa-lightbulb"></i>
                    </div>
                    <h2>researching</h2>
                    <p>Praesent interdum blandit quam. Asunt in anim uis aute irure dolor in reprehenderit in voluptate
                        velit esse cillum dolore.</p>
                </div>
                <div class="col-md-3 services-blog">
                    <div class="logo">
                        <i class="fa-solid fa-wand-magic-sparkles"></i>
                    </div>
                    <h2>design</h2>
                    <p>Praesent interdum blandit quam. Asunt in anim uis aute irure dolor in reprehenderit in voluptate
                        velit esse cillum dolore.</p>
                </div>
                <div class="col-md-3 services-blog">
                    <div class="logo">
                        <i class="fa-solid fa-gears"></i>
                    </div>
                    <h2>development</h2>
                    <p>Praesent interdum blandit quam. Asunt in anim uis aute irure dolor in reprehenderit in voluptate
                        velit esse cillum dolore.</p>
                </div>
                <div class="col-md-3 services-blog">
                    <div class="logo">
                        <i class="fa-solid fa-rocket"></i>
                    </div>
                    <h2>launch</h2>
                    <p>Praesent interdum blandit quam. Asunt in anim uis aute irure dolor in reprehenderit in voluptate
                        velit esse cillum dolore.</p>
                </div>
            </div>
        </div>
    </section>
</template>

<style scoped>
.services {
    background-image: url(../assets/img/home_bg.png);
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center;
}



.services-blog {
    width: 240px;
    margin-right: 15px;
    border-radius: 5px;
    background-color: rgb(195, 81, 88, 0.5);
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    padding: 40px 10px 20px;
    margin-bottom: 20px;
}



.services-blog .logo {
    background-color: white;
    width: 80px;
    height: 80px;
    border-radius: 50%;
    outline: 5px solid white;
    outline-offset: 5px;
    display: flex;
    align-items: center;
    justify-content: center;
    color: #c35158;
    font-size: 45px;
}

.services-blog h2 {
    font-size: 30px;
    margin: 25px 0 35px 0;
    color: #ffffff;
    font-weight: 300;
    font-family: "Lato";
    text-transform: uppercase;
}

.services-blog p {
    font-size: 14px;
    line-height: 20px;
    color: #fefefe;
    font-weight: 400;
    font-family: "Lato";
    text-align: center;
}
</style>