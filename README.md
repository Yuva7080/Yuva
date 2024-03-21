# <!DOCTYPE html>
<html lang="en">
<head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <title>YUVARAJ J</title>
        <link rel="stylesheet" href="css/bootstrap.min.css" />
        <link rel="stylesheet" href="css/materialdesignicons.min.css">
        <link rel="stylesheet" href="css/animate.min.css">
        <link rel="stylesheet" href="css/style.css">
    </head>

    <body>

        <nav class="navbar navbar-expand-lg fixed-top custom-nav sticky">
            <div class="container">
                <a class='navbar-brand logo' href="#">
                        <h1>Yuvaraj J</h1>
                    </a>
                    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="true" aria-label="Toggle navigation">
                        <i class="mdi mdi-menu"></i>
                    </button>
                <div class="collapse navbar-collapse" id="navbarSupportedContent">
                    <ul class="navbar-nav ms-auto">
                        <li class="nav-item active">
                            <a href="#" class="nav-link">Home</a>
                        </li>
                        <li class="nav-item">
                            <a href="#Services" class="nav-link">Services</a>
                        </li>
                        <li class="nav-item">
                            <a href="#" class="nav-link">Portfolio</a>
                        </li>

                        <li class="nav-item">
                            <a href="#" class="nav-link">Blog</a>
                        </li>
                        <li class="nav-item">
                            <a href="#" class="nav-link">Contact</a>
                        </li>
                    </ul>
                </div>
            </div>
        </nav>

        <section class="home-bg section h-100vh" id="home">
            <div class="bg-overlay"></div>
                <div class="container z-index">
                    <div class="row justify-content-center">
                        <div class="col-lg-12">
                            <div class="text-white text-center">
                                <h4>Hello & Welcome</h4>
                                <h1 class="header_title mb-0 mt-3">I Am <span class="element fw-bold" data-elements="A Designer.,A Developer."></span></h1>
                                <ul class="social_home list-unstyled text-center pt-4">
                                    <li class="list-inline-item"><a href=""><i class="mdi mdi-facebook"></i></a></li>
                                    <li class="list-inline-item"><a href=""><i class="mdi mdi-linkedin"></i></a></li>
                                    <li class="list-inline-item"><a href=""><i class="mdi mdi-whatsapp"></i></a></li>
                                    <li class="list-inline-item"><a href=""><i class="mdi mdi-instagram"></i></a></li>
                                    <li class="list-inline-item"><a href=""><i class="mdi mdi-twitter"></i></a></li>
                                </ul>
                                <div class="header_btn">
                                    <a href="Yuvaraj J (Resume).pdf" class="btn btn-outline-custom btn-rounded mt-4 text-white">Download CV</a>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            <div class="scroll_down ">
                <a href="#Services" class="scroll">
                    <i class="mbri-arrow-down text-white"></i>
                </a>
            </div>
        </section>
        <section class="Services-bg h-100vh" id="Services">
            <div class="bg-overlayer"></div>
            <div class="container z-index">
                    <div class="row justify-content-center">
                        <div class="col-lg-12 row-cols-sm-auto">
                            <div class="box text-white"> Our Skills & Services</div>
                            <div class="row justify-content-center box-1">
                                <div class="col-sm-3">
                                    <img src="images/download (1).jpg" alt="">
                                    <Figcaption class="card-title text-white">FIGMA</Figcaption>
                                </div>
                                <div class="col-sm-3">
                                    <img src="images/download (3).jpg" alt="">
                                    <Figcaption class="card-title text-white">HTML</Figcaption>
                                </div>
                                <div class="col-sm-3">
                                    <img src="images/download (4).jpg" alt="">
                                    <Figcaption class="card-title text-white">CSS</Figcaption>
                                </div>
                                <div class="col-sm-3">
                                    <img src="images/download (5).jpg" alt="">
                                    <Figcaption class="card-title text-white">BOOTSTRAP</Figcaption>
                                </div>
                                <div class="col-sm-3">
                                    <img src="images/images.png" alt="">
                                    <Figcaption class="card-title text-white">JAVASCRIPT</Figcaption>
                                </div>
                                <div class="col-sm-3">
                                    <img src="images/download.jpg" alt="">
                                    <Figcaption class="card-title text-white">PHOTOSHOP</Figcaption>
                                </div>
                                <div class="col-sm-3">
                                    <img src="images/images (1).png" alt="">
                                    <Figcaption class="card-title text-white">REACT</Figcaption>
                                </div>
                                <div class="col-sm-3">
                                    <img src="images/download (2).jpg" alt="">
                                    <Figcaption class="card-title text-white">INDESIGN</Figcaption>
                                </div>
                            </div>
                        </div>
                    </div>
                    </div>
        </section>



        <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>

         <script src="js/jquery.min.js"></script>
         <script src="js/typed.js"></script>         
        <script>
            $(".element").each(function() {
                var $this = $(this);
                $this.typed({
                    strings: $this.attr('data-elements').split(','),
                    typeSpeed: 100,
                    backDelay: 3000
                });
            });
        </script>
    </body>
</html>
