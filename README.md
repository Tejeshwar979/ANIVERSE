<!DOCTYPE html>
<html>

<head>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css"
        integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous">
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"
        integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj"
        crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"
        integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN"
        crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"
        integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV"
        crossorigin="anonymous"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.7.2/css/all.min.css"
        integrity="sha512-Evv84Mr4kqVGRNSgIGL/F/aIDqQb7xQ2vcrdIwxfjThSH8CSR7PBEakCr51Ck+w+/U6swU2Im1vVX0SVk9ABhg=="
        crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link rel="stylesheet" href="ani.css">
</head>

<body>
    <div class="d-block d-none d-lg-none d-xl-none fixed-top">
        <nav class="navbar navbar-expand-lg navbar-dark navbar-background container-fluid">
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavAltMarkup"
                aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <a class="navbar-brand" href="#">
                <div class="d-flex flex-row card justify-content-end">
                    <img src="https://images.sftcdn.net/images/t_app-icon-m/p/7526fd60-1d8c-443f-97bd-8a35ee3b2846/1750902377/aniwatch-the-anime-app-onlin-logo"
                        class="nav-logo ml-5" />
                    <h1 class="nav-logo-heading mr-5">ANIVERSE</h1>
                    <button class="nav-button">Login</button>
                </div>
            </a>
            <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
                <div class="navbar-nav ml-auto">
                    <a class="nav-link active" href="#">Home<span class="sr-only">(current)</span></a>
                    <a class="nav-link" href="#sectiontrending">Trending</a>
                    <a class="nav-link" href="#section_new_releases">New releases</a>
                    <a class="nav-link" href="#section_upcoming">Upcoming</a>
                    <a class="nav-link" href="#section_about_us">About Us</a>
                </div>
            </div>
        </nav>
    </div>
    <div class=" d-none d-lg-block fixed-top ">
        <nav class="navbar navbar-expand-lg navbar-dark navbar-background container-fluid">
            <a class="navbar-brand" href="#">
                <div class="d-flex flex-row justify-content-center">
                    <img src="https://images.sftcdn.net/images/t_app-icon-m/p/7526fd60-1d8c-443f-97bd-8a35ee3b2846/1750902377/aniwatch-the-anime-app-onlin-logo"
                        class="nav-logo2  mt-2" />
                    <h2 class="nav-logo-heading2 mb-3">
                        ANIVERSE
                    </h2>
                </div>
            </a>
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavAltMarkup"
                aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
                <div class="navbar-nav ml-auto d-flex flex-row justify-content-center mt-3">
                    <a class="nav-link active" href="#">Home<span class="sr-only">(current)</span></a>
                    <a class="nav-link" href="#sectiontrending">Trending</a>
                    <a class="nav-link" href="#section_new_releases">New releases</a>
                    <a class="nav-link" href="#section_upcoming">Upcoming</a>
                    <a class="nav-link" href="#section_about_us">About Us</a>
                    <button class="nav-md-button ml-2">Login</button>
                </div>
            </div>
        </nav>
    </div>
    <div id="carouselExampleIndicators" class="carousel slide carousel-top " data-ride="carousel">
        <ol class="carousel-indicators">
            <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
            <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
            <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
            <li data-target="#carouselExampleIndicators" data-slide-to="3"></li>
        </ol>
        <div class="carousel-inner">
            <div class="carousel-item active">
                <a href=" ">
                    <img src="https://res.cloudinary.com/dgmfaki8z/image/upload/v1744988297/fabb1962-5939-4a08-9599-2cb41e067308_hvemu0.jpg"
                        class="d-block w-100 carousel-image" alt="one_piece">
                </a>
            </div>
            <div class="carousel-item">
                <a href=" ">
                    <img src="https://res.cloudinary.com/dgmfaki8z/image/upload/v1745151044/4be28398-fc00-441b-8b29-1afcf0d64162_ertyux.jpg "
                        class="d-block w-100 carousel-image" alt="Demon_slayer">
                </a>
            </div>
            <div class="carousel-item">
                <a href=" ">
                    <img src="https://res.cloudinary.com/dgmfaki8z/image/upload/v1748713481/e461b9f0-a10c-478b-a1cc-1e6cfec5550a_khxhdi.jpg"
                        class="d-block w-100 carousel-image" alt="Naruto_shippuden">
                </a>
            </div>
            <div class="carousel-item">
                <a href=" ">
                    <img src="https://res.cloudinary.com/dgmfaki8z/image/upload/v1748713640/attack_on_titan_r8giko.jpg"
                        class="d-block w-100 carousel-image" alt="Attack on titan">
                </a>
            </div>
        </div>
        <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="sr-only">Previous</span>
        </a>
        <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="sr-only">Next</span>
        </a>
    </div>
    <div class="container-fluid top-airing-section">
        <div class="row">
            <div class="col-12" id="sectiontrending">
                <h3 class="p-3">
                    Trending
                </h3>
            </div>
            <div class="col-4">
                <div class="card1">
                    <a>
                        <img src="https://res.cloudinary.com/dgmfaki8z/image/upload/v1745000022/bc9e50b8-5243-4d6d-b116-fa755c79f957_noapph.jpg "
                            class="top-section-image" />
                    </a>
                </div>
            </div>
            <div class="col-4">
                <div class="card1">
                    <a>
                        <img src="https://res.cloudinary.com/dgmfaki8z/image/upload/v1744997854/Blue_Lock_kcjvva.jpg "
                            class="top-section-image" />
                    </a>
                </div>
            </div>
            <div class="col-4">
                <div class="card1">
                    <a>
                        <img src="https://res.cloudinary.com/dgmfaki8z/image/upload/v1744999952/Kimetsu_no_Yaiba__Yuukaku-hen_pfoom3.jpg "
                            class="top-section-image" />
                    </a>
                </div>
            </div>
            <div class="col-12 most-viewed col-lg-6 col-md-6 col-xl-3">
                <div>
                    <h3 class="p-3">
                        Top Airing
                    </h3>
                </div>
                <div>
                    <div class="d-flex flex-row  grid-1">
                        <div class="ml-3">
                            <img src="https://res.cloudinary.com/dgmfaki8z/image/upload/v1746342587/One_piece_mptaec.jpg"
                                class="most-popualr-images " />
                        </div>
                        <div class="mt-3">
                            <h1 class="ml-3">One Piece</h1>
                            <a>
                                <div class="d-flex flex-row">
                                    <div class="d-flex flex-row ml-3 bg2 ">
                                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="black"
                                            class="bi bi-badge-cc-fill mr-1" viewBox="0 0 16 16">
                                            <path
                                                d="M2 2a2 2 0 0 0-2 2v8a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V4a2 2 0 0 0-2-2zm3.027 4.002c-.83 0-1.319.642-1.319 1.753v.743c0 1.107.48 1.727 1.319 1.727.69 0 1.138-.435 1.186-1.05H7.36v.114c-.057 1.147-1.028 1.938-2.342 1.938-1.613 0-2.518-1.028-2.518-2.729v-.747C2.5 6.051 3.414 5 5.018 5c1.318 0 2.29.813 2.342 2v.11H6.213c-.048-.638-.505-1.108-1.186-1.108m6.14 0c-.831 0-1.319.642-1.319 1.753v.743c0 1.107.48 1.727 1.318 1.727.69 0 1.139-.435 1.187-1.05H13.5v.114c-.057 1.147-1.028 1.938-2.342 1.938-1.613 0-2.518-1.028-2.518-2.729v-.747c0-1.7.914-2.751 2.518-2.751 1.318 0 2.29.813 2.342 2v.11h-1.147c-.048-.638-.505-1.108-1.187-1.108z" />
                                        </svg>
                                        <p class="pl-0">1130</p>
                                    </div>
                                    <div class="d-flex flex-row ml-1  bg1 ">
                                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="black"
                                            class="bi bi-mic-fill" viewBox="0 0 16 16">
                                            <path d="M5 3a3 3 0 0 1 6 0v5a3 3 0 0 1-6 0z" />
                                            <path
                                                d="M3.5 6.5A.5.5 0 0 1 4 7v1a4 4 0 0 0 8 0V7a.5.5 0 0 1 1 0v1a5 5 0 0 1-4.5 4.975V15h3a.5.5 0 0 1 0 1h-7a.5.5 0 0 1 0-1h3v-2.025A5 5 0 0 1 3 8V7a.5.5 0 0 1 .5-.5" />
                                        </svg>
                                        <p class="pl-1">1122</p>
                                    </div>
                                    <div class="ml-2 d-flex flex-row justify-content-between">
                                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="#cccccc"
                                            class="bi bi-dot mt-1" viewBox="0 0 16 16">
                                            <path d="M8 9.5a1.5 1.5 0 1 0 0-3 1.5 1.5 0 0 0 0 3" />
                                        </svg>
                                        <h5>TV</h5>
                                    </div>
                                </div>
                            </a>
                        </div>
                    </div>
                    <hr>
                    <div class="d-flex flex-row  grid-1">
                        <div class="ml-3">
                            <img src="https://res.cloudinary.com/dgmfaki8z/image/upload/v1748517536/Sakamoto_Days_y3amhb.jpg"
                                class="most-popualr-images " />
                        </div>
                        <div class="mt-3">
                            <h1 class="ml-3">Sakamoto Days</h1>
                            <a>
                                <div class="d-flex flex-row">
                                    <div class="d-flex flex-row ml-3 bg2 ">
                                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="black"
                                            class="bi bi-badge-cc-fill mr-1 ml-1" viewBox="0 0 16 16">
                                            <path
                                                d="M2 2a2 2 0 0 0-2 2v8a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V4a2 2 0 0 0-2-2zm3.027 4.002c-.83 0-1.319.642-1.319 1.753v.743c0 1.107.48 1.727 1.319 1.727.69 0 1.138-.435 1.186-1.05H7.36v.114c-.057 1.147-1.028 1.938-2.342 1.938-1.613 0-2.518-1.028-2.518-2.729v-.747C2.5 6.051 3.414 5 5.018 5c1.318 0 2.29.813 2.342 2v.11H6.213c-.048-.638-.505-1.108-1.186-1.108m6.14 0c-.831 0-1.319.642-1.319 1.753v.743c0 1.107.48 1.727 1.318 1.727.69 0 1.139-.435 1.187-1.05H13.5v.114c-.057 1.147-1.028 1.938-2.342 1.938-1.613 0-2.518-1.028-2.518-2.729v-.747c0-1.7.914-2.751 2.518-2.751 1.318 0 2.29.813 2.342 2v.11h-1.147c-.048-.638-.505-1.108-1.187-1.108z" />
                                        </svg>
                                        <p class="pl-1">11</p>
                                    </div>
                                    <div class="d-flex flex-row ml-1  bg1 ">
                                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="black"
                                            class="bi bi-mic-fill" viewBox="0 0 16 16">
                                            <path d="M5 3a3 3 0 0 1 6 0v5a3 3 0 0 1-6 0z" />
                                            <path
                                                d="M3.5 6.5A.5.5 0 0 1 4 7v1a4 4 0 0 0 8 0V7a.5.5 0 0 1 1 0v1a5 5 0 0 1-4.5 4.975V15h3a.5.5 0 0 1 0 1h-7a.5.5 0 0 1 0-1h3v-2.025A5 5 0 0 1 3 8V7a.5.5 0 0 1 .5-.5" />
                                        </svg>
                                        <p class="pl-1">11</p>
                                    </div>
                                    <div class="ml-2 d-flex flex-row justify-content-between">
                                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="#cccccc"
                                            class="bi bi-dot mt-1" viewBox="0 0 16 16">
                                            <path d="M8 9.5a1.5 1.5 0 1 0 0-3 1.5 1.5 0 0 0 0 3" />
                                        </svg>
                                        <h5>TV</h5>
                                    </div>
                                </div>
                            </a>
                        </div>
                    </div>
                    <hr>
                    <div class="d-flex flex-row  grid-1">
                        <div class="ml-3">
                            <img src="https://res.cloudinary.com/dgmfaki8z/image/upload/v1748517830/Kusuriya_no_hitorigoto_rgacsk.jpg"
                                class="most-popualr-images " />
                        </div>
                        <div class="mt-3">
                            <h1 class="ml-3">The Apotecary Diaries Season 2</h1>
                            <a>
                                <div class="d-flex flex-row">
                                    <div class="d-flex flex-row ml-3 bg2 ">
                                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="black"
                                            class="bi bi-badge-cc-fill mr-1 pl-1" viewBox="0 0 16 16">
                                            <path
                                                d="M2 2a2 2 0 0 0-2 2v8a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V4a2 2 0 0 0-2-2zm3.027 4.002c-.83 0-1.319.642-1.319 1.753v.743c0 1.107.48 1.727 1.319 1.727.69 0 1.138-.435 1.186-1.05H7.36v.114c-.057 1.147-1.028 1.938-2.342 1.938-1.613 0-2.518-1.028-2.518-2.729v-.747C2.5 6.051 3.414 5 5.018 5c1.318 0 2.29.813 2.342 2v.11H6.213c-.048-.638-.505-1.108-1.186-1.108m6.14 0c-.831 0-1.319.642-1.319 1.753v.743c0 1.107.48 1.727 1.318 1.727.69 0 1.139-.435 1.187-1.05H13.5v.114c-.057 1.147-1.028 1.938-2.342 1.938-1.613 0-2.518-1.028-2.518-2.729v-.747c0-1.7.914-2.751 2.518-2.751 1.318 0 2.29.813 2.342 2v.11h-1.147c-.048-.638-.505-1.108-1.187-1.108z" />
                                        </svg>
                                        <p class="pl-1">19</p>
                                    </div>
                                    <div class="d-flex flex-row ml-1  bg1 ">
                                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="black"
                                            class="bi bi-mic-fill" viewBox="0 0 16 16">
                                            <path d="M5 3a3 3 0 0 1 6 0v5a3 3 0 0 1-6 0z" />
                                            <path
                                                d="M3.5 6.5A.5.5 0 0 1 4 7v1a4 4 0 0 0 8 0V7a.5.5 0 0 1 1 0v1a5 5 0 0 1-4.5 4.975V15h3a.5.5 0 0 1 0 1h-7a.5.5 0 0 1 0-1h3v-2.025A5 5 0 0 1 3 8V7a.5.5 0 0 1 .5-.5" />
                                        </svg>
                                        <p class="pl-1">18</p>
                                    </div>
                                    <div class="ml-2 d-flex flex-row justify-content-between">
                                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="#cccccc"
                                            class="bi bi-dot mt-1" viewBox="0 0 16 16">
                                            <path d="M8 9.5a1.5 1.5 0 1 0 0-3 1.5 1.5 0 0 0 0 3" />
                                        </svg>
                                        <h5>TV</h5>
                                    </div>
                                </div>
                            </a>
                        </div>
                    </div>
                    <hr>
                    <div class="d-flex flex-row  grid-1">
                        <div class="ml-3">
                            <img src="https://res.cloudinary.com/dgmfaki8z/image/upload/v1748518005/DVD_Anime_Detective_Conan_Case_Closed_Season_21_-_25_English_Subtitle_All_Region_Complete_Box_Set_EXPRESS_r5hqtv.jpg"
                                class="most-popualr-images " />
                        </div>
                        <div class="mt-3">
                            <h1 class="ml-3">Case Closed</h1>
                            <a>
                                <div class="d-flex flex-row">
                                    <div class="d-flex flex-row ml-3 bg2 ">
                                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="black"
                                            class="bi bi-badge-cc-fill mr-1" viewBox="0 0 16 16">
                                            <path
                                                d="M2 2a2 2 0 0 0-2 2v8a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V4a2 2 0 0 0-2-2zm3.027 4.002c-.83 0-1.319.642-1.319 1.753v.743c0 1.107.48 1.727 1.319 1.727.69 0 1.138-.435 1.186-1.05H7.36v.114c-.057 1.147-1.028 1.938-2.342 1.938-1.613 0-2.518-1.028-2.518-2.729v-.747C2.5 6.051 3.414 5 5.018 5c1.318 0 2.29.813 2.342 2v.11H6.213c-.048-.638-.505-1.108-1.186-1.108m6.14 0c-.831 0-1.319.642-1.319 1.753v.743c0 1.107.48 1.727 1.318 1.727.69 0 1.139-.435 1.187-1.05H13.5v.114c-.057 1.147-1.028 1.938-2.342 1.938-1.613 0-2.518-1.028-2.518-2.729v-.747c0-1.7.914-2.751 2.518-2.751 1.318 0 2.29.813 2.342 2v.11h-1.147c-.048-.638-.505-1.108-1.187-1.108z" />
                                        </svg>
                                        <p class="pl-0">1163</p>
                                    </div>
                                    <div class="d-flex flex-row ml-1  bg1 ">
                                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="black"
                                            class="bi bi-mic-fill" viewBox="0 0 16 16">
                                            <path d="M5 3a3 3 0 0 1 6 0v5a3 3 0 0 1-6 0z" />
                                            <path
                                                d="M3.5 6.5A.5.5 0 0 1 4 7v1a4 4 0 0 0 8 0V7a.5.5 0 0 1 1 0v1a5 5 0 0 1-4.5 4.975V15h3a.5.5 0 0 1 0 1h-7a.5.5 0 0 1 0-1h3v-2.025A5 5 0 0 1 3 8V7a.5.5 0 0 1 .5-.5" />
                                        </svg>
                                        <p class="pl-1">123</p>
                                    </div>
                                    <div class="ml-2 d-flex flex-row justify-content-between">
                                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="#cccccc"
                                            class="bi bi-dot mt-1" viewBox="0 0 16 16">
                                            <path d="M8 9.5a1.5 1.5 0 1 0 0-3 1.5 1.5 0 0 0 0 3" />
                                        </svg>
                                        <h5>TV</h5>
                                    </div>
                                </div>
                            </a>
                        </div>
                    </div>
                    <hr>
                </div>
            </div>
            <div class="col-12 most-viewed col-lg-6 col-md-6 col-xl-3">
                <div>
                    <h3 class="p-3">
                        Most Popular
                    </h3>
                </div>
                <div>
                    <div class="d-flex flex-row  grid-1">
                        <div class="ml-3">
                            <img src="https://res.cloudinary.com/dgmfaki8z/image/upload/v1745581635/14a9b836-5c6c-47d6-acd3-22c76817b9ad_iero4a.jpg"
                                class="most-popualr-images " />
                        </div>
                        <div class="mt-3">
                            <h1 class="ml-3">One Piece</h1>
                            <a>
                                <div class="d-flex flex-row">
                                    <div class="d-flex flex-row ml-3 bg2 ">
                                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="black"
                                            class="bi bi-badge-cc-fill mr-1" viewBox="0 0 16 16">
                                            <path
                                                d="M2 2a2 2 0 0 0-2 2v8a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V4a2 2 0 0 0-2-2zm3.027 4.002c-.83 0-1.319.642-1.319 1.753v.743c0 1.107.48 1.727 1.319 1.727.69 0 1.138-.435 1.186-1.05H7.36v.114c-.057 1.147-1.028 1.938-2.342 1.938-1.613 0-2.518-1.028-2.518-2.729v-.747C2.5 6.051 3.414 5 5.018 5c1.318 0 2.29.813 2.342 2v.11H6.213c-.048-.638-.505-1.108-1.186-1.108m6.14 0c-.831 0-1.319.642-1.319 1.753v.743c0 1.107.48 1.727 1.318 1.727.69 0 1.139-.435 1.187-1.05H13.5v.114c-.057 1.147-1.028 1.938-2.342 1.938-1.613 0-2.518-1.028-2.518-2.729v-.747c0-1.7.914-2.751 2.518-2.751 1.318 0 2.29.813 2.342 2v.11h-1.147c-.048-.638-.505-1.108-1.187-1.108z" />
                                        </svg>
                                        <p class="pl-0">1130</p>
                                    </div>
                                    <div class="d-flex flex-row ml-1  bg1 ">
                                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="black"
                                            class="bi bi-mic-fill" viewBox="0 0 16 16">
                                            <path d="M5 3a3 3 0 0 1 6 0v5a3 3 0 0 1-6 0z" />
                                            <path
                                                d="M3.5 6.5A.5.5 0 0 1 4 7v1a4 4 0 0 0 8 0V7a.5.5 0 0 1 1 0v1a5 5 0 0 1-4.5 4.975V15h3a.5.5 0 0 1 0 1h-7a.5.5 0 0 1 0-1h3v-2.025A5 5 0 0 1 3 8V7a.5.5 0 0 1 .5-.5" />
                                        </svg>
                                        <p class="pl-1">1122</p>
                                    </div>
                                    <div class="ml-2 d-flex flex-row justify-content-between">
                                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="#cccccc"
                                            class="bi bi-dot mt-1" viewBox="0 0 16 16">
                                            <path d="M8 9.5a1.5 1.5 0 1 0 0-3 1.5 1.5 0 0 0 0 3" />
                                        </svg>
                                        <h5>TV</h5>
                                    </div>
                                </div>
                            </a>
                        </div>
                    </div>
                    <hr>
                    <div class="d-flex flex-row  grid-1">
                        <div class="ml-3">
                            <img src="https://res.cloudinary.com/dgmfaki8z/image/upload/v1748518240/Naruto__Shipp%C5%ABden_fewxek.jpg"
                                class="most-popualr-images " />
                        </div>
                        <div class="mt-3">
                            <h1 class="ml-3">Naruto Shippuden</h1>
                            <a>
                                <div class="d-flex flex-row">
                                    <div class="d-flex flex-row ml-3 bg2 ">
                                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="black"
                                            class="bi bi-badge-cc-fill mr-2" viewBox="0 0 16 16">
                                            <path
                                                d="M2 2a2 2 0 0 0-2 2v8a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V4a2 2 0 0 0-2-2zm3.027 4.002c-.83 0-1.319.642-1.319 1.753v.743c0 1.107.48 1.727 1.319 1.727.69 0 1.138-.435 1.186-1.05H7.36v.114c-.057 1.147-1.028 1.938-2.342 1.938-1.613 0-2.518-1.028-2.518-2.729v-.747C2.5 6.051 3.414 5 5.018 5c1.318 0 2.29.813 2.342 2v.11H6.213c-.048-.638-.505-1.108-1.186-1.108m6.14 0c-.831 0-1.319.642-1.319 1.753v.743c0 1.107.48 1.727 1.318 1.727.69 0 1.139-.435 1.187-1.05H13.5v.114c-.057 1.147-1.028 1.938-2.342 1.938-1.613 0-2.518-1.028-2.518-2.729v-.747c0-1.7.914-2.751 2.518-2.751 1.318 0 2.29.813 2.342 2v.11h-1.147c-.048-.638-.505-1.108-1.187-1.108z" />
                                        </svg>
                                        <p class="pl-0">500</p>
                                    </div>
                                    <div class="d-flex flex-row ml-1  bg-card mr-1">
                                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="black"
                                            class="bi bi-mic-fill" viewBox="0 0 16 16">
                                            <path d="M5 3a3 3 0 0 1 6 0v5a3 3 0 0 1-6 0z" />
                                            <path
                                                d="M3.5 6.5A.5.5 0 0 1 4 7v1a4 4 0 0 0 8 0V7a.5.5 0 0 1 1 0v1a5 5 0 0 1-4.5 4.975V15h3a.5.5 0 0 1 0 1h-7a.5.5 0 0 1 0-1h3v-2.025A5 5 0 0 1 3 8V7a.5.5 0 0 1 .5-.5" />
                                        </svg>
                                        <p class="pl-1">500</p>
                                    </div>
                                    <div>
                                        <p class="box-design">500</p>
                                    </div>
                                    <div class="ml-2 d-flex flex-row justify-content-between">
                                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="#cccccc"
                                            class="bi bi-dot mt-1" viewBox="0 0 16 16">
                                            <path d="M8 9.5a1.5 1.5 0 1 0 0-3 1.5 1.5 0 0 0 0 3" />
                                        </svg>
                                        <h5>TV</h5>
                                    </div>
                                </div>
                            </a>
                        </div>
                    </div>
                    <hr>
                    <div class="d-flex flex-row  grid-1">
                        <div class="ml-3">
                            <img src="https://res.cloudinary.com/dgmfaki8z/image/upload/v1747063034/MugiwaraSan_Shop___Redbubble_ayrbuq.jpg"
                                class="most-popualr-images " />
                        </div>
                        <div class="mt-3">
                            <h1 class="ml-3">Bleach</h1>
                            <a>
                                <div class="d-flex flex-row">
                                    <div class="d-flex flex-row ml-3 bg2 ">
                                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="black"
                                            class="bi bi-badge-cc-fill mr-1" viewBox="0 0 16 16">
                                            <path
                                                d="M2 2a2 2 0 0 0-2 2v8a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V4a2 2 0 0 0-2-2zm3.027 4.002c-.83 0-1.319.642-1.319 1.753v.743c0 1.107.48 1.727 1.319 1.727.69 0 1.138-.435 1.186-1.05H7.36v.114c-.057 1.147-1.028 1.938-2.342 1.938-1.613 0-2.518-1.028-2.518-2.729v-.747C2.5 6.051 3.414 5 5.018 5c1.318 0 2.29.813 2.342 2v.11H6.213c-.048-.638-.505-1.108-1.186-1.108m6.14 0c-.831 0-1.319.642-1.319 1.753v.743c0 1.107.48 1.727 1.318 1.727.69 0 1.139-.435 1.187-1.05H13.5v.114c-.057 1.147-1.028 1.938-2.342 1.938-1.613 0-2.518-1.028-2.518-2.729v-.747c0-1.7.914-2.751 2.518-2.751 1.318 0 2.29.813 2.342 2v.11h-1.147c-.048-.638-.505-1.108-1.187-1.108z" />
                                        </svg>
                                        <p class="pl-0">366</p>
                                    </div>
                                    <div class="d-flex flex-row ml-1  bg-card mr-1">
                                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="black"
                                            class="bi bi-mic-fill" viewBox="0 0 16 16">
                                            <path d="M5 3a3 3 0 0 1 6 0v5a3 3 0 0 1-6 0z" />
                                            <path
                                                d="M3.5 6.5A.5.5 0 0 1 4 7v1a4 4 0 0 0 8 0V7a.5.5 0 0 1 1 0v1a5 5 0 0 1-4.5 4.975V15h3a.5.5 0 0 1 0 1h-7a.5.5 0 0 1 0-1h3v-2.025A5 5 0 0 1 3 8V7a.5.5 0 0 1 .5-.5" />
                                        </svg>
                                        <p class="pl-1">366</p>
                                    </div>
                                    <div>
                                        <p class="box-design">366</p>
                                    </div>
                                    <div class="ml-2 d-flex flex-row justify-content-between">
                                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="#cccccc"
                                            class="bi bi-dot mt-1" viewBox="0 0 16 16">
                                            <path d="M8 9.5a1.5 1.5 0 1 0 0-3 1.5 1.5 0 0 0 0 3" />
                                        </svg>
                                        <h5>TV</h5>
                                    </div>
                                </div>
                            </a>
                        </div>
                    </div>
                    <hr>
                    <div class="d-flex flex-row  grid-1 ">
                        <div class="ml-3">
                            <img src="https://res.cloudinary.com/dgmfaki8z/image/upload/v1745000022/bc9e50b8-5243-4d6d-b116-fa755c79f957_noapph.jpg "
                                class="most-popualr-images " />
                        </div>
                        <div class="mt-2">
                            <h1 class="ml-3">Solo Leveling Season 2: Arise from the shadow</h1>
                            <a>
                                <div class="d-flex flex-row">
                                    <div class="d-flex flex-row ml-3 bg2 ">
                                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="black"
                                            class="bi bi-badge-cc-fill mr-2" viewBox="0 0 16 16">
                                            <path
                                                d="M2 2a2 2 0 0 0-2 2v8a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V4a2 2 0 0 0-2-2zm3.027 4.002c-.83 0-1.319.642-1.319 1.753v.743c0 1.107.48 1.727 1.319 1.727.69 0 1.138-.435 1.186-1.05H7.36v.114c-.057 1.147-1.028 1.938-2.342 1.938-1.613 0-2.518-1.028-2.518-2.729v-.747C2.5 6.051 3.414 5 5.018 5c1.318 0 2.29.813 2.342 2v.11H6.213c-.048-.638-.505-1.108-1.186-1.108m6.14 0c-.831 0-1.319.642-1.319 1.753v.743c0 1.107.48 1.727 1.318 1.727.69 0 1.139-.435 1.187-1.05H13.5v.114c-.057 1.147-1.028 1.938-2.342 1.938-1.613 0-2.518-1.028-2.518-2.729v-.747c0-1.7.914-2.751 2.518-2.751 1.318 0 2.29.813 2.342 2v.11h-1.147c-.048-.638-.505-1.108-1.187-1.108z" />
                                        </svg>
                                        <p class="pl-0">13</p>
                                    </div>
                                    <div class="d-flex flex-row ml-1  bg-card mr-1">
                                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="black"
                                            class="bi bi-mic-fill" viewBox="0 0 16 16">
                                            <path d="M5 3a3 3 0 0 1 6 0v5a3 3 0 0 1-6 0z" />
                                            <path
                                                d="M3.5 6.5A.5.5 0 0 1 4 7v1a4 4 0 0 0 8 0V7a.5.5 0 0 1 1 0v1a5 5 0 0 1-4.5 4.975V15h3a.5.5 0 0 1 0 1h-7a.5.5 0 0 1 0-1h3v-2.025A5 5 0 0 1 3 8V7a.5.5 0 0 1 .5-.5" />
                                        </svg>
                                        <p class="pl-1">13</p>
                                    </div>
                                    <div>
                                        <p class="box-design">13</p>
                                    </div>
                                    <div class="ml-2 d-flex flex-row justify-content-between">
                                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="#cccccc"
                                            class="bi bi-dot mt-1" viewBox="0 0 16 16">
                                            <path d="M8 9.5a1.5 1.5 0 1 0 0-3 1.5 1.5 0 0 0 0 3" />
                                        </svg>
                                        <h5>TV</h5>
                                    </div>
                                </div>
                            </a>
                        </div>
                    </div>
                    <hr>
                </div>
            </div>
            <div class="col-12 most-viewed col-lg-6 col-md-6 col-xl-3">
                <div>
                    <h3 class="p-3">
                        Most Favourtie
                    </h3>
                </div>
                <div>
                    <div class="d-flex flex-row  grid-1">
                        <div class="ml-3">
                            <img src="https://res.cloudinary.com/dgmfaki8z/image/upload/v1745581635/14a9b836-5c6c-47d6-acd3-22c76817b9ad_iero4a.jpg"
                                class="most-popualr-images " />
                        </div>
                        <div class="mt-3">
                            <h1 class="ml-3">One Piece</h1>
                            <a>
                                <div class="d-flex flex-row">
                                    <div class="d-flex flex-row ml-3 bg2 ">
                                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="black"
                                            class="bi bi-badge-cc-fill mr-1" viewBox="0 0 16 16">
                                            <path
                                                d="M2 2a2 2 0 0 0-2 2v8a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V4a2 2 0 0 0-2-2zm3.027 4.002c-.83 0-1.319.642-1.319 1.753v.743c0 1.107.48 1.727 1.319 1.727.69 0 1.138-.435 1.186-1.05H7.36v.114c-.057 1.147-1.028 1.938-2.342 1.938-1.613 0-2.518-1.028-2.518-2.729v-.747C2.5 6.051 3.414 5 5.018 5c1.318 0 2.29.813 2.342 2v.11H6.213c-.048-.638-.505-1.108-1.186-1.108m6.14 0c-.831 0-1.319.642-1.319 1.753v.743c0 1.107.48 1.727 1.318 1.727.69 0 1.139-.435 1.187-1.05H13.5v.114c-.057 1.147-1.028 1.938-2.342 1.938-1.613 0-2.518-1.028-2.518-2.729v-.747c0-1.7.914-2.751 2.518-2.751 1.318 0 2.29.813 2.342 2v.11h-1.147c-.048-.638-.505-1.108-1.187-1.108z" />
                                        </svg>
                                        <p class="pl-0">1130</p>
                                    </div>
                                    <div class="d-flex flex-row ml-1  bg1 ">
                                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="black"
                                            class="bi bi-mic-fill" viewBox="0 0 16 16">
                                            <path d="M5 3a3 3 0 0 1 6 0v5a3 3 0 0 1-6 0z" />
                                            <path
                                                d="M3.5 6.5A.5.5 0 0 1 4 7v1a4 4 0 0 0 8 0V7a.5.5 0 0 1 1 0v1a5 5 0 0 1-4.5 4.975V15h3a.5.5 0 0 1 0 1h-7a.5.5 0 0 1 0-1h3v-2.025A5 5 0 0 1 3 8V7a.5.5 0 0 1 .5-.5" />
                                        </svg>
                                        <p class="pl-1">1122</p>
                                    </div>
                                    <div class="ml-2 d-flex flex-row justify-content-between">
                                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="#cccccc"
                                            class="bi bi-dot mt-1" viewBox="0 0 16 16">
                                            <path d="M8 9.5a1.5 1.5 0 1 0 0-3 1.5 1.5 0 0 0 0 3" />
                                        </svg>
                                        <h5>TV</h5>
                                    </div>
                                </div>
                            </a>
                        </div>
                    </div>
                    <hr>
                    <div class="d-flex flex-row  grid-1">
                        <div class="ml-3">
                            <img src="https://res.cloudinary.com/dgmfaki8z/image/upload/v1748519901/Chainsaw_Man_ljtdwg.jpg"
                                class="most-popualr-images " />
                        </div>
                        <div class="mt-3">
                            <h1 class="ml-3">ChainSaw Man</h1>
                            <a>
                                <div class="d-flex flex-row">
                                    <div class="d-flex flex-row ml-3 bg2 ">
                                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="black"
                                            class="bi bi-badge-cc-fill mr-2" viewBox="0 0 16 16">
                                            <path
                                                d="M2 2a2 2 0 0 0-2 2v8a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V4a2 2 0 0 0-2-2zm3.027 4.002c-.83 0-1.319.642-1.319 1.753v.743c0 1.107.48 1.727 1.319 1.727.69 0 1.138-.435 1.186-1.05H7.36v.114c-.057 1.147-1.028 1.938-2.342 1.938-1.613 0-2.518-1.028-2.518-2.729v-.747C2.5 6.051 3.414 5 5.018 5c1.318 0 2.29.813 2.342 2v.11H6.213c-.048-.638-.505-1.108-1.186-1.108m6.14 0c-.831 0-1.319.642-1.319 1.753v.743c0 1.107.48 1.727 1.318 1.727.69 0 1.139-.435 1.187-1.05H13.5v.114c-.057 1.147-1.028 1.938-2.342 1.938-1.613 0-2.518-1.028-2.518-2.729v-.747c0-1.7.914-2.751 2.518-2.751 1.318 0 2.29.813 2.342 2v.11h-1.147c-.048-.638-.505-1.108-1.187-1.108z" />
                                        </svg>
                                        <p class="pl-0">12</p>
                                    </div>
                                    <div class="d-flex flex-row ml-1  bg-card mr-1">
                                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="black"
                                            class="bi bi-mic-fill" viewBox="0 0 16 16">
                                            <path d="M5 3a3 3 0 0 1 6 0v5a3 3 0 0 1-6 0z" />
                                            <path
                                                d="M3.5 6.5A.5.5 0 0 1 4 7v1a4 4 0 0 0 8 0V7a.5.5 0 0 1 1 0v1a5 5 0 0 1-4.5 4.975V15h3a.5.5 0 0 1 0 1h-7a.5.5 0 0 1 0-1h3v-2.025A5 5 0 0 1 3 8V7a.5.5 0 0 1 .5-.5" />
                                        </svg>
                                        <p class="pl-1">12</p>
                                    </div>
                                    <div>
                                        <p class="box-design">12</p>
                                    </div>
                                    <div class="ml-2 d-flex flex-row justify-content-between">
                                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="#cccccc"
                                            class="bi bi-dot mt-1" viewBox="0 0 16 16">
                                            <path d="M8 9.5a1.5 1.5 0 1 0 0-3 1.5 1.5 0 0 0 0 3" />
                                        </svg>
                                        <h5>TV</h5>
                                    </div>
                                </div>
                            </a>
                        </div>
                    </div>
                    <hr>
                    <div class="d-flex flex-row  grid-1">
                        <div class="ml-3">
                            <img src="https://res.cloudinary.com/dgmfaki8z/image/upload/v1744987171/Jujutsu_Kaisen_Season_2_e2tsa8.jpg"
                                class="most-popualr-images " />
                        </div>
                        <div class="mt-3">
                            <h1 class="ml-3">Jijutsu Kaisen(TV)</h1>
                            <a>
                                <div class="d-flex flex-row">
                                    <div class="d-flex flex-row ml-3 bg2 ">
                                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="black"
                                            class="bi bi-badge-cc-fill mr-1" viewBox="0 0 16 16">
                                            <path
                                                d="M2 2a2 2 0 0 0-2 2v8a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V4a2 2 0 0 0-2-2zm3.027 4.002c-.83 0-1.319.642-1.319 1.753v.743c0 1.107.48 1.727 1.319 1.727.69 0 1.138-.435 1.186-1.05H7.36v.114c-.057 1.147-1.028 1.938-2.342 1.938-1.613 0-2.518-1.028-2.518-2.729v-.747C2.5 6.051 3.414 5 5.018 5c1.318 0 2.29.813 2.342 2v.11H6.213c-.048-.638-.505-1.108-1.186-1.108m6.14 0c-.831 0-1.319.642-1.319 1.753v.743c0 1.107.48 1.727 1.318 1.727.69 0 1.139-.435 1.187-1.05H13.5v.114c-.057 1.147-1.028 1.938-2.342 1.938-1.613 0-2.518-1.028-2.518-2.729v-.747c0-1.7.914-2.751 2.518-2.751 1.318 0 2.29.813 2.342 2v.11h-1.147c-.048-.638-.505-1.108-1.187-1.108z" />
                                        </svg>
                                        <p class="pl-0">24</p>
                                    </div>
                                    <div class="d-flex flex-row ml-1  bg-card mr-1">
                                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="black"
                                            class="bi bi-mic-fill" viewBox="0 0 16 16">
                                            <path d="M5 3a3 3 0 0 1 6 0v5a3 3 0 0 1-6 0z" />
                                            <path
                                                d="M3.5 6.5A.5.5 0 0 1 4 7v1a4 4 0 0 0 8 0V7a.5.5 0 0 1 1 0v1a5 5 0 0 1-4.5 4.975V15h3a.5.5 0 0 1 0 1h-7a.5.5 0 0 1 0-1h3v-2.025A5 5 0 0 1 3 8V7a.5.5 0 0 1 .5-.5" />
                                        </svg>
                                        <p class="pl-1">24</p>
                                    </div>
                                    <div>
                                        <p class="box-design">24</p>
                                    </div>
                                    <div class="ml-2 d-flex flex-row justify-content-between">
                                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="#cccccc"
                                            class="bi bi-dot mt-1" viewBox="0 0 16 16">
                                            <path d="M8 9.5a1.5 1.5 0 1 0 0-3 1.5 1.5 0 0 0 0 3" />
                                        </svg>
                                        <h5>TV</h5>
                                    </div>
                                </div>
                            </a>
                        </div>
                    </div>
                    <hr>
                    <div class="d-flex flex-row  grid-1">
                        <div class="ml-3">
                            <img src="https://res.cloudinary.com/dgmfaki8z/image/upload/v1745150541/Kimetsu_no_Yaiba_icon_1_2_vsojtb.jpg "
                                class="most-popualr-images " />
                        </div>
                        <div class="mt-2">
                            <h1 class="ml-3">Demon Slayer: Kimetsu no yaiba swordsmith village arc</h1>
                            <a>
                                <div class="d-flex flex-row">
                                    <div class="d-flex flex-row ml-3 bg2 ">
                                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="black"
                                            class="bi bi-badge-cc-fill mr-1" viewBox="0 0 16 16">
                                            <path
                                                d="M2 2a2 2 0 0 0-2 2v8a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V4a2 2 0 0 0-2-2zm3.027 4.002c-.83 0-1.319.642-1.319 1.753v.743c0 1.107.48 1.727 1.319 1.727.69 0 1.138-.435 1.186-1.05H7.36v.114c-.057 1.147-1.028 1.938-2.342 1.938-1.613 0-2.518-1.028-2.518-2.729v-.747C2.5 6.051 3.414 5 5.018 5c1.318 0 2.29.813 2.342 2v.11H6.213c-.048-.638-.505-1.108-1.186-1.108m6.14 0c-.831 0-1.319.642-1.319 1.753v.743c0 1.107.48 1.727 1.318 1.727.69 0 1.139-.435 1.187-1.05H13.5v.114c-.057 1.147-1.028 1.938-2.342 1.938-1.613 0-2.518-1.028-2.518-2.729v-.747c0-1.7.914-2.751 2.518-2.751 1.318 0 2.29.813 2.342 2v.11h-1.147c-.048-.638-.505-1.108-1.187-1.108z" />
                                        </svg>
                                        <p class="pl-0">11</p>
                                    </div>
                                    <div class="d-flex flex-row ml-1  bg-card mr-1">
                                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="black"
                                            class="bi bi-mic-fill" viewBox="0 0 16 16">
                                            <path d="M5 3a3 3 0 0 1 6 0v5a3 3 0 0 1-6 0z" />
                                            <path
                                                d="M3.5 6.5A.5.5 0 0 1 4 7v1a4 4 0 0 0 8 0V7a.5.5 0 0 1 1 0v1a5 5 0 0 1-4.5 4.975V15h3a.5.5 0 0 1 0 1h-7a.5.5 0 0 1 0-1h3v-2.025A5 5 0 0 1 3 8V7a.5.5 0 0 1 .5-.5" />
                                        </svg>
                                        <p class="pl-1">11</p>
                                    </div>
                                    <div>
                                        <p class="box-design">11</p>
                                    </div>
                                    <div class="ml-2 d-flex flex-row justify-content-between">
                                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="#cccccc"
                                            class="bi bi-dot mt-1" viewBox="0 0 16 16">
                                            <path d="M8 9.5a1.5 1.5 0 1 0 0-3 1.5 1.5 0 0 0 0 3" />
                                        </svg>
                                        <h5>TV</h5>
                                    </div>
                                </div>
                            </a>
                        </div>
                    </div>
                    <hr>
                </div>
            </div>
            <div class="col-12 most-viewed col-lg-6 col-md-6 col-xl-3">
                <div>
                    <h3 class="p-3">
                        Latest Completed
                    </h3>
                </div>
                <div>
                    <div class="d-flex flex-row  grid-1">
                        <div class="ml-3">
                            <img src="https://res.cloudinary.com/dgmfaki8z/image/upload/v1748537296/d1c3e3f6-9255-4b95-a6f3-a9929a3e023d_lh34br.jpg"
                                class="most-popualr-images " />
                        </div>
                        <div class="mt-2">
                            <h1 class="ml-3 text-capitalize">Code Geass:Lelouch of the rebellion picture dramas</h1>
                            <a>
                                <div class="d-flex flex-row">
                                    <div class="d-flex flex-row ml-3 bg2 ">
                                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="black"
                                            class="bi bi-badge-cc-fill mr-2" viewBox="0 0 16 16">
                                            <path
                                                d="M2 2a2 2 0 0 0-2 2v8a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V4a2 2 0 0 0-2-2zm3.027 4.002c-.83 0-1.319.642-1.319 1.753v.743c0 1.107.48 1.727 1.319 1.727.69 0 1.138-.435 1.186-1.05H7.36v.114c-.057 1.147-1.028 1.938-2.342 1.938-1.613 0-2.518-1.028-2.518-2.729v-.747C2.5 6.051 3.414 5 5.018 5c1.318 0 2.29.813 2.342 2v.11H6.213c-.048-.638-.505-1.108-1.186-1.108m6.14 0c-.831 0-1.319.642-1.319 1.753v.743c0 1.107.48 1.727 1.318 1.727.69 0 1.139-.435 1.187-1.05H13.5v.114c-.057 1.147-1.028 1.938-2.342 1.938-1.613 0-2.518-1.028-2.518-2.729v-.747c0-1.7.914-2.751 2.518-2.751 1.318 0 2.29.813 2.342 2v.11h-1.147c-.048-.638-.505-1.108-1.187-1.108z" />
                                        </svg>
                                        <p class="pl-0">9</p>
                                    </div>
                                    <div class="d-flex flex-row ml-1  bg-card mr-1">
                                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="black"
                                            class="bi bi-mic-fill" viewBox="0 0 16 16">
                                            <path d="M5 3a3 3 0 0 1 6 0v5a3 3 0 0 1-6 0z" />
                                            <path
                                                d="M3.5 6.5A.5.5 0 0 1 4 7v1a4 4 0 0 0 8 0V7a.5.5 0 0 1 1 0v1a5 5 0 0 1-4.5 4.975V15h3a.5.5 0 0 1 0 1h-7a.5.5 0 0 1 0-1h3v-2.025A5 5 0 0 1 3 8V7a.5.5 0 0 1 .5-.5" />
                                        </svg>
                                        <p class="pl-1">9</p>
                                    </div>
                                    <div>
                                        <p class="box-design">9</p>
                                    </div>
                                    <div class="ml-2 d-flex flex-row justify-content-between">
                                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="#cccccc"
                                            class="bi bi-dot  mt-1" viewBox="0 0 16 16">
                                            <path d="M8 9.5a1.5 1.5 0 1 0 0-3 1.5 1.5 0 0 0 0 3" />
                                        </svg>
                                        <h5>Special</h5>
                                    </div>
                                </div>
                            </a>
                        </div>
                    </div>
                    <hr>
                    <div class="d-flex flex-row  grid-1">
                        <div class="ml-3">
                            <img src="https://res.cloudinary.com/dgmfaki8z/image/upload/v1748538350/Seihou_Tenshi_Angel_Links_%E6%98%9F%E6%96%B9%E5%A4%A9%E4%BD%BF%E3%82%A8%E3%83%B3%E3%82%B8%E3%82%A7%E3%83%AB%E3%83%AA%E3%83%B3%E3%82%AF%E3%82%B9_1999_uunbju.jpg"
                                class="most-popualr-images " />
                        </div>
                        <div class="mt-2">
                            <h1 class="ml-3 text-capitalize">seihou tenshi angel links:meifon no special kaisetsu corner
                            </h1>
                            <a>
                                <div class="d-flex flex-row">
                                    <div class="d-flex flex-row ml-4 bg2 " id="border-card">
                                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="black"
                                            class="bi bi-badge-cc-fill mr-2" viewBox="0 0 16 16">
                                            <path
                                                d="M2 2a2 2 0 0 0-2 2v8a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V4a2 2 0 0 0-2-2zm3.027 4.002c-.83 0-1.319.642-1.319 1.753v.743c0 1.107.48 1.727 1.319 1.727.69 0 1.138-.435 1.186-1.05H7.36v.114c-.057 1.147-1.028 1.938-2.342 1.938-1.613 0-2.518-1.028-2.518-2.729v-.747C2.5 6.051 3.414 5 5.018 5c1.318 0 2.29.813 2.342 2v.11H6.213c-.048-.638-.505-1.108-1.186-1.108m6.14 0c-.831 0-1.319.642-1.319 1.753v.743c0 1.107.48 1.727 1.318 1.727.69 0 1.139-.435 1.187-1.05H13.5v.114c-.057 1.147-1.028 1.938-2.342 1.938-1.613 0-2.518-1.028-2.518-2.729v-.747c0-1.7.914-2.751 2.518-2.751 1.318 0 2.29.813 2.342 2v.11h-1.147c-.048-.638-.505-1.108-1.187-1.108z" />
                                        </svg>
                                        <p class="pl-0 ">1</p>
                                    </div>

                                    <div class="ml-2 d-flex flex-row justify-content-between">
                                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="#cccccc"
                                            class="bi bi-dot mt-1" viewBox="0 0 16 16">
                                            <path d="M8 9.5a1.5 1.5 0 1 0 0-3 1.5 1.5 0 0 0 0 3" />
                                        </svg>
                                        <h5>Special</h5>
                                    </div>
                                </div>
                            </a>
                        </div>
                    </div>
                    <hr>
                    <div class="d-flex flex-row  grid-1">
                        <div class="ml-3">
                            <img src="https://res.cloudinary.com/dgmfaki8z/image/upload/v1748538011/All_Purpose_Cultural_Cat_Girl_Nuku_Nuku_yt3vtj.jpg "
                                class="most-popualr-images " />
                        </div>
                        <div class="mt-2">
                            <h1 class="ml-3 text-capitalize">all purpose cultural cat girl nuku nuku</h1>
                            <a>
                                <div class="d-flex flex-row">
                                    <div class="d-flex flex-row ml-3 bg2 ">
                                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="black"
                                            class="bi bi-badge-cc-fill mr-1" viewBox="0 0 16 16">
                                            <path
                                                d="M2 2a2 2 0 0 0-2 2v8a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V4a2 2 0 0 0-2-2zm3.027 4.002c-.83 0-1.319.642-1.319 1.753v.743c0 1.107.48 1.727 1.319 1.727.69 0 1.138-.435 1.186-1.05H7.36v.114c-.057 1.147-1.028 1.938-2.342 1.938-1.613 0-2.518-1.028-2.518-2.729v-.747C2.5 6.051 3.414 5 5.018 5c1.318 0 2.29.813 2.342 2v.11H6.213c-.048-.638-.505-1.108-1.186-1.108m6.14 0c-.831 0-1.319.642-1.319 1.753v.743c0 1.107.48 1.727 1.318 1.727.69 0 1.139-.435 1.187-1.05H13.5v.114c-.057 1.147-1.028 1.938-2.342 1.938-1.613 0-2.518-1.028-2.518-2.729v-.747c0-1.7.914-2.751 2.518-2.751 1.318 0 2.29.813 2.342 2v.11h-1.147c-.048-.638-.505-1.108-1.187-1.108z" />
                                        </svg>
                                        <p class="pl-0">6</p>
                                    </div>
                                    <div class="d-flex flex-row ml-1  bg-card mr-1">
                                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="black"
                                            class="bi bi-mic-fill" viewBox="0 0 16 16">
                                            <path d="M5 3a3 3 0 0 1 6 0v5a3 3 0 0 1-6 0z" />
                                            <path
                                                d="M3.5 6.5A.5.5 0 0 1 4 7v1a4 4 0 0 0 8 0V7a.5.5 0 0 1 1 0v1a5 5 0 0 1-4.5 4.975V15h3a.5.5 0 0 1 0 1h-7a.5.5 0 0 1 0-1h3v-2.025A5 5 0 0 1 3 8V7a.5.5 0 0 1 .5-.5" />
                                        </svg>
                                        <p class="pl-1">6</p>
                                    </div>
                                    <div>
                                        <p class="box-design">6</p>
                                    </div>
                                    <div class="ml-2 d-flex flex-row justify-content-between">
                                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="#cccccc"
                                            class="bi bi-dot mt-1" viewBox="0 0 16 16">
                                            <path d="M8 9.5a1.5 1.5 0 1 0 0-3 1.5 1.5 0 0 0 0 3" />
                                        </svg>
                                        <h5>TV</h5>
                                    </div>
                                </div>
                            </a>
                        </div>
                    </div>
                    <hr>
                    <div class="d-flex flex-row  grid-1 ">
                        <div class="ml-3">
                            <img src="https://res.cloudinary.com/dgmfaki8z/image/upload/v1748538502/Miracle_of_Endymion_yek8nh.jpg "
                                class="most-popualr-images " />
                        </div>
                        <div class="mt-2">
                            <h1 class="ml-3 text-capitalize">a certain magical index the movies: the miracle of endymion
                            </h1>
                            <a>
                                <div class="d-flex flex-row">
                                    <div class="d-flex flex-row ml-3 bg2 ">
                                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="black"
                                            class="bi bi-badge-cc-fill mr-1" viewBox="0 0 16 16">
                                            <path
                                                d="M2 2a2 2 0 0 0-2 2v8a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V4a2 2 0 0 0-2-2zm3.027 4.002c-.83 0-1.319.642-1.319 1.753v.743c0 1.107.48 1.727 1.319 1.727.69 0 1.138-.435 1.186-1.05H7.36v.114c-.057 1.147-1.028 1.938-2.342 1.938-1.613 0-2.518-1.028-2.518-2.729v-.747C2.5 6.051 3.414 5 5.018 5c1.318 0 2.29.813 2.342 2v.11H6.213c-.048-.638-.505-1.108-1.186-1.108m6.14 0c-.831 0-1.319.642-1.319 1.753v.743c0 1.107.48 1.727 1.318 1.727.69 0 1.139-.435 1.187-1.05H13.5v.114c-.057 1.147-1.028 1.938-2.342 1.938-1.613 0-2.518-1.028-2.518-2.729v-.747c0-1.7.914-2.751 2.518-2.751 1.318 0 2.29.813 2.342 2v.11h-1.147c-.048-.638-.505-1.108-1.187-1.108z" />
                                        </svg>
                                        <p class="pl-0">1</p>
                                    </div>
                                    <div class="d-flex flex-row ml-1  bg1 ">
                                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="black"
                                            class="bi bi-mic-fill" viewBox="0 0 16 16">
                                            <path d="M5 3a3 3 0 0 1 6 0v5a3 3 0 0 1-6 0z" />
                                            <path
                                                d="M3.5 6.5A.5.5 0 0 1 4 7v1a4 4 0 0 0 8 0V7a.5.5 0 0 1 1 0v1a5 5 0 0 1-4.5 4.975V15h3a.5.5 0 0 1 0 1h-7a.5.5 0 0 1 0-1h3v-2.025A5 5 0 0 1 3 8V7a.5.5 0 0 1 .5-.5" />
                                        </svg>
                                        <p class="pl-1">1</p>
                                    </div>
                                    <div class="ml-2 d-flex flex-row justify-content-between">
                                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="#cccccc"
                                            class="bi bi-dot mt-1" viewBox="0 0 16 16">
                                            <path d="M8 9.5a1.5 1.5 0 1 0 0-3 1.5 1.5 0 0 0 0 3" />
                                        </svg>
                                        <h5>Movie</h5>
                                    </div>
                                </div>
                            </a>
                        </div>
                    </div>
                    <hr>
                </div>
            </div>
            <div class="col-12" id="section_new_releases">
                <h3 class="mb-2 p-3">
                    Latest Episodes
                </h3>
            </div>
            <div class="col-12 col-sm-6 col-md-6 col-lg-6 col-xl-2 mb-3">
                <div class="bg-one-piece d-flex flex-column justify-content-end">
                    <div class="card-style d-flex flex-row">
                        <div class="d-flex flex-row justify-content-center card-design-1">
                            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="black"
                                class="bi bi-badge-cc-fill mt-1 ml-1 mr-1 pl-1" viewBox="0 0 16 16">
                                <path
                                    d="M2 2a2 2 0 0 0-2 2v8a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V4a2 2 0 0 0-2-2zm3.027 4.002c-.83 0-1.319.642-1.319 1.753v.743c0 1.107.48 1.727 1.319 1.727.69 0 1.138-.435 1.186-1.05H7.36v.114c-.057 1.147-1.028 1.938-2.342 1.938-1.613 0-2.518-1.028-2.518-2.729v-.747C2.5 6.051 3.414 5 5.018 5c1.318 0 2.29.813 2.342 2v.11H6.213c-.048-.638-.505-1.108-1.186-1.108m6.14 0c-.831 0-1.319.642-1.319 1.753v.743c0 1.107.48 1.727 1.318 1.727.69 0 1.139-.435 1.187-1.05H13.5v.114c-.057 1.147-1.028 1.938-2.342 1.938-1.613 0-2.518-1.028-2.518-2.729v-.747c0-1.7.914-2.751 2.518-2.751 1.318 0 2.29.813 2.342 2v.11h-1.147c-.048-.638-.505-1.108-1.187-1.108z" />
                            </svg>
                            <p class="mt-1 mr-2">1128</p>
                        </div>
                        <div class="d-flex flex-row justify-content-center card-design-2">
                            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="black"
                                class="bi bi-mic-fill mt-1 ml-1 mr-1 pl-1" viewBox="0 0 16 16">
                                <path d="M5 3a3 3 0 0 1 6 0v5a3 3 0 0 1-6 0z" />
                                <path
                                    d="M3.5 6.5A.5.5 0 0 1 4 7v1a4 4 0 0 0 8 0V7a.5.5 0 0 1 1 0v1a5 5 0 0 1-4.5 4.975V15h3a.5.5 0 0 1 0 1h-7a.5.5 0 0 1 0-1h3v-2.025A5 5 0 0 1 3 8V7a.5.5 0 0 1 .5-.5" />
                            </svg>
                            <p class="mt-1 mr-2">1122</p>
                        </div>
                    </div>
                </div>
                <div class="ml-2">
                    <h2 class="text-white mt-2 heading-bg-design text-capitalize">One Piece</h2>
                    <div class="d-flex flex-row">
                        <p class="bg-para-design">TV</p>
                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="#7A7A7A"
                            class="bi bi-dot mt-2" viewBox="0 0 16 16">
                            <path d="M8 9.5a1.5 1.5 0 1 0 0-3 1.5 1.5 0 0 0 0 3" />
                        </svg>
                        <p class="bg-para-design">24m</p>
                    </div>
                </div>
            </div>
            <div class="col-12 col-sm-6 col-md-6  col-lg-6 col-xl-2 mb-3">
                <div class="bg-blue-lock d-flex flex-column justify-content-end">
                    <div class="card-style d-flex flex-row">
                        <div class="d-flex flex-row justify-content-center card-design-1">
                            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="black"
                                class="bi bi-badge-cc-fill mt-1 ml-1 mr-1 pl-1" viewBox="0 0 16 16">
                                <path
                                    d="M2 2a2 2 0 0 0-2 2v8a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V4a2 2 0 0 0-2-2zm3.027 4.002c-.83 0-1.319.642-1.319 1.753v.743c0 1.107.48 1.727 1.319 1.727.69 0 1.138-.435 1.186-1.05H7.36v.114c-.057 1.147-1.028 1.938-2.342 1.938-1.613 0-2.518-1.028-2.518-2.729v-.747C2.5 6.051 3.414 5 5.018 5c1.318 0 2.29.813 2.342 2v.11H6.213c-.048-.638-.505-1.108-1.186-1.108m6.14 0c-.831 0-1.319.642-1.319 1.753v.743c0 1.107.48 1.727 1.318 1.727.69 0 1.139-.435 1.187-1.05H13.5v.114c-.057 1.147-1.028 1.938-2.342 1.938-1.613 0-2.518-1.028-2.518-2.729v-.747c0-1.7.914-2.751 2.518-2.751 1.318 0 2.29.813 2.342 2v.11h-1.147c-.048-.638-.505-1.108-1.187-1.108z" />
                            </svg>
                            <p class="mt-1 mr-2">24</p>
                        </div>
                        <div class="d-flex flex-row justify-content-center card-design-2">
                            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="black"
                                class="bi bi-mic-fill mt-1 ml-1 mr-1 pl-1" viewBox="0 0 16 16">
                                <path d="M5 3a3 3 0 0 1 6 0v5a3 3 0 0 1-6 0z" />
                                <path
                                    d="M3.5 6.5A.5.5 0 0 1 4 7v1a4 4 0 0 0 8 0V7a.5.5 0 0 1 1 0v1a5 5 0 0 1-4.5 4.975V15h3a.5.5 0 0 1 0 1h-7a.5.5 0 0 1 0-1h3v-2.025A5 5 0 0 1 3 8V7a.5.5 0 0 1 .5-.5" />
                            </svg>
                            <p class="mt-1 mr-2">24</p>
                        </div>
                    </div>
                </div>
                <div class="ml-2">
                    <h2 class="text-white mt-2 heading-bg-design text-capitalize">Blue Lock</h2>
                    <div class="d-flex flex-row">
                        <p class="bg-para-design">TV</p>
                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="#7A7A7A"
                            class="bi bi-dot mt-2" viewBox="0 0 16 16">
                            <path d="M8 9.5a1.5 1.5 0 1 0 0-3 1.5 1.5 0 0 0 0 3" />
                        </svg>
                        <p class="bg-para-design">23m</p>
                    </div>
                </div>
            </div>
            <div class="col-12 col-sm-6 col-md-6  col-lg-6 col-xl-2 mb-3">
                <div class="bg-demon-slayer d-flex flex-column justify-content-end">
                    <div class="card-style d-flex flex-row">
                        <div class="d-flex flex-row justify-content-center card-design-1">
                            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="black"
                                class="bi bi-badge-cc-fill mt-1 ml-1 mr-1 pl-1" viewBox="0 0 16 16">
                                <path
                                    d="M2 2a2 2 0 0 0-2 2v8a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V4a2 2 0 0 0-2-2zm3.027 4.002c-.83 0-1.319.642-1.319 1.753v.743c0 1.107.48 1.727 1.319 1.727.69 0 1.138-.435 1.186-1.05H7.36v.114c-.057 1.147-1.028 1.938-2.342 1.938-1.613 0-2.518-1.028-2.518-2.729v-.747C2.5 6.051 3.414 5 5.018 5c1.318 0 2.29.813 2.342 2v.11H6.213c-.048-.638-.505-1.108-1.186-1.108m6.14 0c-.831 0-1.319.642-1.319 1.753v.743c0 1.107.48 1.727 1.318 1.727.69 0 1.139-.435 1.187-1.05H13.5v.114c-.057 1.147-1.028 1.938-2.342 1.938-1.613 0-2.518-1.028-2.518-2.729v-.747c0-1.7.914-2.751 2.518-2.751 1.318 0 2.29.813 2.342 2v.11h-1.147c-.048-.638-.505-1.108-1.187-1.108z" />
                            </svg>
                            <p class="mt-1 mr-2">26</p>
                        </div>
                        <div class="d-flex flex-row justify-content-center card-design-2">
                            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="black"
                                class="bi bi-mic-fill mt-1 ml-1 mr-1 pl-1" viewBox="0 0 16 16">
                                <path d="M5 3a3 3 0 0 1 6 0v5a3 3 0 0 1-6 0z" />
                                <path
                                    d="M3.5 6.5A.5.5 0 0 1 4 7v1a4 4 0 0 0 8 0V7a.5.5 0 0 1 1 0v1a5 5 0 0 1-4.5 4.975V15h3a.5.5 0 0 1 0 1h-7a.5.5 0 0 1 0-1h3v-2.025A5 5 0 0 1 3 8V7a.5.5 0 0 1 .5-.5" />
                            </svg>
                            <p class="mt-1 mr-2">26</p>
                        </div>
                    </div>
                </div>
                <div class="ml-2">
                    <h2 class="text-white mt-2 heading-bg-design text-capitalize">Demon Slayer</h2>
                    <div class="d-flex flex-row">
                        <p class="bg-para-design">TV</p>
                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="#7A7A7A"
                            class="bi bi-dot mt-2" viewBox="0 0 16 16">
                            <path d="M8 9.5a1.5 1.5 0 1 0 0-3 1.5 1.5 0 0 0 0 3" />
                        </svg>
                        <p class="bg-para-design">24m</p>
                    </div>
                </div>
            </div>
            <div class="col-12 col-sm-6 col-md-6  col-lg-6 col-xl-2 mb-3">
                <div class="bg-dragon-ball d-flex flex-column justify-content-end">
                    <div class="card-style d-flex flex-row">
                        <div class="d-flex flex-row justify-content-center card-design-1">
                            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="black"
                                class="bi bi-badge-cc-fill mt-1 ml-1 mr-1 pl-1" viewBox="0 0 16 16">
                                <path
                                    d="M2 2a2 2 0 0 0-2 2v8a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V4a2 2 0 0 0-2-2zm3.027 4.002c-.83 0-1.319.642-1.319 1.753v.743c0 1.107.48 1.727 1.319 1.727.69 0 1.138-.435 1.186-1.05H7.36v.114c-.057 1.147-1.028 1.938-2.342 1.938-1.613 0-2.518-1.028-2.518-2.729v-.747C2.5 6.051 3.414 5 5.018 5c1.318 0 2.29.813 2.342 2v.11H6.213c-.048-.638-.505-1.108-1.186-1.108m6.14 0c-.831 0-1.319.642-1.319 1.753v.743c0 1.107.48 1.727 1.318 1.727.69 0 1.139-.435 1.187-1.05H13.5v.114c-.057 1.147-1.028 1.938-2.342 1.938-1.613 0-2.518-1.028-2.518-2.729v-.747c0-1.7.914-2.751 2.518-2.751 1.318 0 2.29.813 2.342 2v.11h-1.147c-.048-.638-.505-1.108-1.187-1.108z" />
                            </svg>
                            <p class="mt-1 mr-2">291</p>
                        </div>
                        <div class="d-flex flex-row justify-content-center card-design-2">
                            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="black"
                                class="bi bi-mic-fill mt-1 ml-1 mr-1 pl-1" viewBox="0 0 16 16">
                                <path d="M5 3a3 3 0 0 1 6 0v5a3 3 0 0 1-6 0z" />
                                <path
                                    d="M3.5 6.5A.5.5 0 0 1 4 7v1a4 4 0 0 0 8 0V7a.5.5 0 0 1 1 0v1a5 5 0 0 1-4.5 4.975V15h3a.5.5 0 0 1 0 1h-7a.5.5 0 0 1 0-1h3v-2.025A5 5 0 0 1 3 8V7a.5.5 0 0 1 .5-.5" />
                            </svg>
                            <p class="mt-1 mr-2">291</p>
                        </div>
                    </div>
                </div>
                <div class="ml-2">
                    <h2 class="text-white mt-2 heading-bg-design text-capitalize">Dragon Ball Z</h2>
                    <div class="d-flex flex-row">
                        <p class="bg-para-design">TV</p>
                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="#7A7A7A"
                            class="bi bi-dot mt-2" viewBox="0 0 16 16">
                            <path d="M8 9.5a1.5 1.5 0 1 0 0-3 1.5 1.5 0 0 0 0 3" />
                        </svg>
                        <p class="bg-para-design">24m</p>
                    </div>
                </div>
            </div>
            <div class="col-12 col-sm-6 col-md-6  col-lg-6 col-xl-2 mb-3">
                <div class="bg-jjk d-flex flex-column justify-content-end">
                    <div class="card-style d-flex flex-row">
                        <div class="d-flex flex-row justify-content-center card-design-1">
                            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="black"
                                class="bi bi-badge-cc-fill mt-1 ml-1 mr-1 pl-1" viewBox="0 0 16 16">
                                <path
                                    d="M2 2a2 2 0 0 0-2 2v8a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V4a2 2 0 0 0-2-2zm3.027 4.002c-.83 0-1.319.642-1.319 1.753v.743c0 1.107.48 1.727 1.319 1.727.69 0 1.138-.435 1.186-1.05H7.36v.114c-.057 1.147-1.028 1.938-2.342 1.938-1.613 0-2.518-1.028-2.518-2.729v-.747C2.5 6.051 3.414 5 5.018 5c1.318 0 2.29.813 2.342 2v.11H6.213c-.048-.638-.505-1.108-1.186-1.108m6.14 0c-.831 0-1.319.642-1.319 1.753v.743c0 1.107.48 1.727 1.318 1.727.69 0 1.139-.435 1.187-1.05H13.5v.114c-.057 1.147-1.028 1.938-2.342 1.938-1.613 0-2.518-1.028-2.518-2.729v-.747c0-1.7.914-2.751 2.518-2.751 1.318 0 2.29.813 2.342 2v.11h-1.147c-.048-.638-.505-1.108-1.187-1.108z" />
                            </svg>
                            <p class="mt-1 mr-2">24</p>
                        </div>
                        <div class="d-flex flex-row justify-content-center card-design-2">
                            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="black"
                                class="bi bi-mic-fill mt-1 ml-1 mr-1 pl-1" viewBox="0 0 16 16">
                                <path d="M5 3a3 3 0 0 1 6 0v5a3 3 0 0 1-6 0z" />
                                <path
                                    d="M3.5 6.5A.5.5 0 0 1 4 7v1a4 4 0 0 0 8 0V7a.5.5 0 0 1 1 0v1a5 5 0 0 1-4.5 4.975V15h3a.5.5 0 0 1 0 1h-7a.5.5 0 0 1 0-1h3v-2.025A5 5 0 0 1 3 8V7a.5.5 0 0 1 .5-.5" />
                            </svg>
                            <p class="mt-1 mr-2">24</p>
                        </div>
                    </div>
                </div>
                <div class="ml-2">
                    <h2 class="text-white mt-2 heading-bg-design text-capitalize">Jijutsu Kaisen Season 1</h2>
                    <div class="d-flex flex-row">
                        <p class="bg-para-design">TV</p>
                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="#7A7A7A"
                            class="bi bi-dot mt-2" viewBox="0 0 16 16">
                            <path d="M8 9.5a1.5 1.5 0 1 0 0-3 1.5 1.5 0 0 0 0 3" />
                        </svg>
                        <p class="bg-para-design">24m</p>
                    </div>
                </div>
            </div>
            <div class="col-12 col-sm-6 col-md-6  col-lg-6 col-xl-2 mb-3">
                <div class="bg-death-note d-flex flex-column justify-content-end">
                    <div class="card-style d-flex flex-row">
                        <div class="d-flex flex-row justify-content-center card-design-1">
                            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="black"
                                class="bi bi-badge-cc-fill mt-1 ml-1 mr-1 pl-1" viewBox="0 0 16 16">
                                <path
                                    d="M2 2a2 2 0 0 0-2 2v8a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V4a2 2 0 0 0-2-2zm3.027 4.002c-.83 0-1.319.642-1.319 1.753v.743c0 1.107.48 1.727 1.319 1.727.69 0 1.138-.435 1.186-1.05H7.36v.114c-.057 1.147-1.028 1.938-2.342 1.938-1.613 0-2.518-1.028-2.518-2.729v-.747C2.5 6.051 3.414 5 5.018 5c1.318 0 2.29.813 2.342 2v.11H6.213c-.048-.638-.505-1.108-1.186-1.108m6.14 0c-.831 0-1.319.642-1.319 1.753v.743c0 1.107.48 1.727 1.318 1.727.69 0 1.139-.435 1.187-1.05H13.5v.114c-.057 1.147-1.028 1.938-2.342 1.938-1.613 0-2.518-1.028-2.518-2.729v-.747c0-1.7.914-2.751 2.518-2.751 1.318 0 2.29.813 2.342 2v.11h-1.147c-.048-.638-.505-1.108-1.187-1.108z" />
                            </svg>
                            <p class="mt-1 mr-2">37</p>
                        </div>
                        <div class="d-flex flex-row justify-content-center card-design-2">
                            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="black"
                                class="bi bi-mic-fill mt-1 ml-1 mr-1 pl-1" viewBox="0 0 16 16">
                                <path d="M5 3a3 3 0 0 1 6 0v5a3 3 0 0 1-6 0z" />
                                <path
                                    d="M3.5 6.5A.5.5 0 0 1 4 7v1a4 4 0 0 0 8 0V7a.5.5 0 0 1 1 0v1a5 5 0 0 1-4.5 4.975V15h3a.5.5 0 0 1 0 1h-7a.5.5 0 0 1 0-1h3v-2.025A5 5 0 0 1 3 8V7a.5.5 0 0 1 .5-.5" />
                            </svg>
                            <p class="mt-1 mr-2">37</p>
                        </div>
                    </div>
                </div>
                <div class="ml-2">
                    <h2 class="text-white mt-2 heading-bg-design text-capitalize">Death Note</h2>
                    <div class="d-flex flex-row">
                        <p class="bg-para-design">TV</p>
                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="#7A7A7A"
                            class="bi bi-dot mt-2" viewBox="0 0 16 16">
                            <path d="M8 9.5a1.5 1.5 0 1 0 0-3 1.5 1.5 0 0 0 0 3" />
                        </svg>
                        <p class="bg-para-design">24m</p>
                    </div>
                </div>
            </div>
            <div class="col-12 col-sm-6 col-md-6  col-lg-6 col-xl-2 mb-3">
                <div class="bg-attack-on-titan d-flex flex-column justify-content-end">
                    <div class="card-style d-flex flex-row">
                        <div class="d-flex flex-row justify-content-center card-design-1">
                            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="black"
                                class="bi bi-badge-cc-fill mt-1 ml-1 mr-1 pl-1" viewBox="0 0 16 16">
                                <path
                                    d="M2 2a2 2 0 0 0-2 2v8a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V4a2 2 0 0 0-2-2zm3.027 4.002c-.83 0-1.319.642-1.319 1.753v.743c0 1.107.48 1.727 1.319 1.727.69 0 1.138-.435 1.186-1.05H7.36v.114c-.057 1.147-1.028 1.938-2.342 1.938-1.613 0-2.518-1.028-2.518-2.729v-.747C2.5 6.051 3.414 5 5.018 5c1.318 0 2.29.813 2.342 2v.11H6.213c-.048-.638-.505-1.108-1.186-1.108m6.14 0c-.831 0-1.319.642-1.319 1.753v.743c0 1.107.48 1.727 1.318 1.727.69 0 1.139-.435 1.187-1.05H13.5v.114c-.057 1.147-1.028 1.938-2.342 1.938-1.613 0-2.518-1.028-2.518-2.729v-.747c0-1.7.914-2.751 2.518-2.751 1.318 0 2.29.813 2.342 2v.11h-1.147c-.048-.638-.505-1.108-1.187-1.108z" />
                            </svg>
                            <p class="mt-1 mr-2">25</p>
                        </div>
                        <div class="d-flex flex-row justify-content-center card-design-2">
                            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="black"
                                class="bi bi-mic-fill mt-1 ml-1 mr-1 pl-1" viewBox="0 0 16 16">
                                <path d="M5 3a3 3 0 0 1 6 0v5a3 3 0 0 1-6 0z" />
                                <path
                                    d="M3.5 6.5A.5.5 0 0 1 4 7v1a4 4 0 0 0 8 0V7a.5.5 0 0 1 1 0v1a5 5 0 0 1-4.5 4.975V15h3a.5.5 0 0 1 0 1h-7a.5.5 0 0 1 0-1h3v-2.025A5 5 0 0 1 3 8V7a.5.5 0 0 1 .5-.5" />
                            </svg>
                            <p class="mt-1 mr-2">25</p>
                        </div>
                    </div>
                </div>
                <div class="ml-2">
                    <h2 class="text-white mt-2 heading-bg-design text-capitalize">Attack ON Titan Season 1</h2>
                    <div class="d-flex flex-row">
                        <p class="bg-para-design">TV</p>
                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="#7A7A7A"
                            class="bi bi-dot mt-2" viewBox="0 0 16 16">
                            <path d="M8 9.5a1.5 1.5 0 1 0 0-3 1.5 1.5 0 0 0 0 3" />
                        </svg>
                        <p class="bg-para-design">24m</p>
                    </div>
                </div>
            </div>
            <div class="col-12 col-sm-6 col-md-6  col-lg-6 col-xl-2 mb-3">
                <div class="bg-hunterxhunter d-flex flex-column justify-content-end">
                    <div class="card-style d-flex flex-row">
                        <div class="d-flex flex-row justify-content-center card-design-1">
                            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="black"
                                class="bi bi-badge-cc-fill mt-1 ml-1 mr-1 pl-1" viewBox="0 0 16 16">
                                <path
                                    d="M2 2a2 2 0 0 0-2 2v8a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V4a2 2 0 0 0-2-2zm3.027 4.002c-.83 0-1.319.642-1.319 1.753v.743c0 1.107.48 1.727 1.319 1.727.69 0 1.138-.435 1.186-1.05H7.36v.114c-.057 1.147-1.028 1.938-2.342 1.938-1.613 0-2.518-1.028-2.518-2.729v-.747C2.5 6.051 3.414 5 5.018 5c1.318 0 2.29.813 2.342 2v.11H6.213c-.048-.638-.505-1.108-1.186-1.108m6.14 0c-.831 0-1.319.642-1.319 1.753v.743c0 1.107.48 1.727 1.318 1.727.69 0 1.139-.435 1.187-1.05H13.5v.114c-.057 1.147-1.028 1.938-2.342 1.938-1.613 0-2.518-1.028-2.518-2.729v-.747c0-1.7.914-2.751 2.518-2.751 1.318 0 2.29.813 2.342 2v.11h-1.147c-.048-.638-.505-1.108-1.187-1.108z" />
                            </svg>
                            <p class="mt-1 mr-2">148</p>
                        </div>
                        <div class="d-flex flex-row justify-content-center card-design-2">
                            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="black"
                                class="bi bi-mic-fill mt-1 ml-1 mr-1 pl-1" viewBox="0 0 16 16">
                                <path d="M5 3a3 3 0 0 1 6 0v5a3 3 0 0 1-6 0z" />
                                <path
                                    d="M3.5 6.5A.5.5 0 0 1 4 7v1a4 4 0 0 0 8 0V7a.5.5 0 0 1 1 0v1a5 5 0 0 1-4.5 4.975V15h3a.5.5 0 0 1 0 1h-7a.5.5 0 0 1 0-1h3v-2.025A5 5 0 0 1 3 8V7a.5.5 0 0 1 .5-.5" />
                            </svg>
                            <p class="mt-1 mr-2">148</p>
                        </div>
                    </div>
                </div>
                <div class="ml-2">
                    <h2 class="text-white mt-2 heading-bg-design text-capitalize">Hunter X Hunter </h2>
                    <div class="d-flex flex-row">
                        <p class="bg-para-design">TV</p>
                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="#7A7A7A"
                            class="bi bi-dot mt-2" viewBox="0 0 16 16">
                            <path d="M8 9.5a1.5 1.5 0 1 0 0-3 1.5 1.5 0 0 0 0 3" />
                        </svg>
                        <p class="bg-para-design">24m</p>
                    </div>
                </div>
            </div>
            <div class="col-12 col-sm-6 col-md-6  col-lg-6 col-xl-2 mb-3">
                <div class="bg-bleach d-flex flex-column justify-content-end">
                    <div class="card-style d-flex flex-row">
                        <div class="d-flex flex-row justify-content-center card-design-1">
                            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="black"
                                class="bi bi-badge-cc-fill mt-1 ml-1 mr-1 pl-1" viewBox="0 0 16 16">
                                <path
                                    d="M2 2a2 2 0 0 0-2 2v8a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V4a2 2 0 0 0-2-2zm3.027 4.002c-.83 0-1.319.642-1.319 1.753v.743c0 1.107.48 1.727 1.319 1.727.69 0 1.138-.435 1.186-1.05H7.36v.114c-.057 1.147-1.028 1.938-2.342 1.938-1.613 0-2.518-1.028-2.518-2.729v-.747C2.5 6.051 3.414 5 5.018 5c1.318 0 2.29.813 2.342 2v.11H6.213c-.048-.638-.505-1.108-1.186-1.108m6.14 0c-.831 0-1.319.642-1.319 1.753v.743c0 1.107.48 1.727 1.318 1.727.69 0 1.139-.435 1.187-1.05H13.5v.114c-.057 1.147-1.028 1.938-2.342 1.938-1.613 0-2.518-1.028-2.518-2.729v-.747c0-1.7.914-2.751 2.518-2.751 1.318 0 2.29.813 2.342 2v.11h-1.147c-.048-.638-.505-1.108-1.187-1.108z" />
                            </svg>
                            <p class="mt-1 mr-2">366</p>
                        </div>
                        <div class="d-flex flex-row justify-content-center card-design-2">
                            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="black"
                                class="bi bi-mic-fill mt-1 ml-1 mr-1 pl-1" viewBox="0 0 16 16">
                                <path d="M5 3a3 3 0 0 1 6 0v5a3 3 0 0 1-6 0z" />
                                <path
                                    d="M3.5 6.5A.5.5 0 0 1 4 7v1a4 4 0 0 0 8 0V7a.5.5 0 0 1 1 0v1a5 5 0 0 1-4.5 4.975V15h3a.5.5 0 0 1 0 1h-7a.5.5 0 0 1 0-1h3v-2.025A5 5 0 0 1 3 8V7a.5.5 0 0 1 .5-.5" />
                            </svg>
                            <p class="mt-1 mr-2">366</p>
                        </div>
                    </div>
                </div>
                <div class="ml-2">
                    <h2 class="text-white mt-2 heading-bg-design text-capitalize">Bleach</h2>
                    <div class="d-flex flex-row">
                        <p class="bg-para-design">TV</p>
                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="#7A7A7A"
                            class="bi bi-dot mt-2" viewBox="0 0 16 16">
                            <path d="M8 9.5a1.5 1.5 0 1 0 0-3 1.5 1.5 0 0 0 0 3" />
                        </svg>
                        <p class="bg-para-design">24m</p>
                    </div>
                </div>
            </div>
            <div class="col-12 col-sm-6 col-md-6  col-lg-6 col-xl-2 mb-3">
                <div class="bg-naruto-shippuden d-flex flex-column justify-content-end">
                    <div class="card-style d-flex flex-row">
                        <div class="d-flex flex-row justify-content-center card-design-1">
                            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="black"
                                class="bi bi-badge-cc-fill mt-1 ml-1 mr-1 pl-1" viewBox="0 0 16 16">
                                <path
                                    d="M2 2a2 2 0 0 0-2 2v8a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V4a2 2 0 0 0-2-2zm3.027 4.002c-.83 0-1.319.642-1.319 1.753v.743c0 1.107.48 1.727 1.319 1.727.69 0 1.138-.435 1.186-1.05H7.36v.114c-.057 1.147-1.028 1.938-2.342 1.938-1.613 0-2.518-1.028-2.518-2.729v-.747C2.5 6.051 3.414 5 5.018 5c1.318 0 2.29.813 2.342 2v.11H6.213c-.048-.638-.505-1.108-1.186-1.108m6.14 0c-.831 0-1.319.642-1.319 1.753v.743c0 1.107.48 1.727 1.318 1.727.69 0 1.139-.435 1.187-1.05H13.5v.114c-.057 1.147-1.028 1.938-2.342 1.938-1.613 0-2.518-1.028-2.518-2.729v-.747c0-1.7.914-2.751 2.518-2.751 1.318 0 2.29.813 2.342 2v.11h-1.147c-.048-.638-.505-1.108-1.187-1.108z" />
                            </svg>
                            <p class="mt-1 mr-2">500</p>
                        </div>
                        <div class="d-flex flex-row justify-content-center card-design-2">
                            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="black"
                                class="bi bi-mic-fill mt-1 ml-1 mr-1 pl-1" viewBox="0 0 16 16">
                                <path d="M5 3a3 3 0 0 1 6 0v5a3 3 0 0 1-6 0z" />
                                <path
                                    d="M3.5 6.5A.5.5 0 0 1 4 7v1a4 4 0 0 0 8 0V7a.5.5 0 0 1 1 0v1a5 5 0 0 1-4.5 4.975V15h3a.5.5 0 0 1 0 1h-7a.5.5 0 0 1 0-1h3v-2.025A5 5 0 0 1 3 8V7a.5.5 0 0 1 .5-.5" />
                            </svg>
                            <p class="mt-1 mr-2">500</p>
                        </div>
                    </div>
                </div>
                <div class="ml-2">
                    <h2 class="text-white mt-2 heading-bg-design text-capitalize">Naruto Shippuden</h2>
                    <div class="d-flex flex-row">
                        <p class="bg-para-design">TV</p>
                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="#7A7A7A"
                            class="bi bi-dot mt-2" viewBox="0 0 16 16">
                            <path d="M8 9.5a1.5 1.5 0 1 0 0-3 1.5 1.5 0 0 0 0 3" />
                        </svg>
                        <p class="bg-para-design">24m</p>
                    </div>
                </div>
            </div>
            <div class="col-12 col-sm-6 col-md-6  col-lg-6 col-xl-2 mb-3">
                <div class="bg-tokyo-revengers d-flex flex-column justify-content-end">
                    <div class="card-style d-flex flex-row">
                        <div class="d-flex flex-row justify-content-center card-design-1">
                            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="black"
                                class="bi bi-badge-cc-fill mt-1 ml-1 mr-1 pl-1" viewBox="0 0 16 16">
                                <path
                                    d="M2 2a2 2 0 0 0-2 2v8a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V4a2 2 0 0 0-2-2zm3.027 4.002c-.83 0-1.319.642-1.319 1.753v.743c0 1.107.48 1.727 1.319 1.727.69 0 1.138-.435 1.186-1.05H7.36v.114c-.057 1.147-1.028 1.938-2.342 1.938-1.613 0-2.518-1.028-2.518-2.729v-.747C2.5 6.051 3.414 5 5.018 5c1.318 0 2.29.813 2.342 2v.11H6.213c-.048-.638-.505-1.108-1.186-1.108m6.14 0c-.831 0-1.319.642-1.319 1.753v.743c0 1.107.48 1.727 1.318 1.727.69 0 1.139-.435 1.187-1.05H13.5v.114c-.057 1.147-1.028 1.938-2.342 1.938-1.613 0-2.518-1.028-2.518-2.729v-.747c0-1.7.914-2.751 2.518-2.751 1.318 0 2.29.813 2.342 2v.11h-1.147c-.048-.638-.505-1.108-1.187-1.108z" />
                            </svg>
                            <p class="mt-1 mr-2">24</p>
                        </div>
                        <div class="d-flex flex-row justify-content-center card-design-2">
                            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="black"
                                class="bi bi-mic-fill mt-1 ml-1 mr-1 pl-1" viewBox="0 0 16 16">
                                <path d="M5 3a3 3 0 0 1 6 0v5a3 3 0 0 1-6 0z" />
                                <path
                                    d="M3.5 6.5A.5.5 0 0 1 4 7v1a4 4 0 0 0 8 0V7a.5.5 0 0 1 1 0v1a5 5 0 0 1-4.5 4.975V15h3a.5.5 0 0 1 0 1h-7a.5.5 0 0 1 0-1h3v-2.025A5 5 0 0 1 3 8V7a.5.5 0 0 1 .5-.5" />
                            </svg>
                            <p class="mt-1 mr-2">24</p>
                        </div>
                    </div>
                </div>
                <div class="ml-2">
                    <h2 class="text-white mt-2 heading-bg-design text-capitalize">Tokyo Revengers</h2>
                    <div class="d-flex flex-row">
                        <p class="bg-para-design">TV</p>
                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="#7A7A7A"
                            class="bi bi-dot mt-2" viewBox="0 0 16 16">
                            <path d="M8 9.5a1.5 1.5 0 1 0 0-3 1.5 1.5 0 0 0 0 3" />
                        </svg>
                        <p class="bg-para-design">24m</p>
                    </div>
                </div>
            </div>
            <div class="col-12 col-sm-6 col-md-6  col-lg-6 col-xl-2 mb-3">
                <div class="bg-black-clover d-flex flex-column justify-content-end">
                    <div class="card-style d-flex flex-row">
                        <div class="d-flex flex-row justify-content-center card-design-1">
                            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="black"
                                class="bi bi-badge-cc-fill mt-1 ml-1 mr-1 pl-1" viewBox="0 0 16 16">
                                <path
                                    d="M2 2a2 2 0 0 0-2 2v8a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V4a2 2 0 0 0-2-2zm3.027 4.002c-.83 0-1.319.642-1.319 1.753v.743c0 1.107.48 1.727 1.319 1.727.69 0 1.138-.435 1.186-1.05H7.36v.114c-.057 1.147-1.028 1.938-2.342 1.938-1.613 0-2.518-1.028-2.518-2.729v-.747C2.5 6.051 3.414 5 5.018 5c1.318 0 2.29.813 2.342 2v.11H6.213c-.048-.638-.505-1.108-1.186-1.108m6.14 0c-.831 0-1.319.642-1.319 1.753v.743c0 1.107.48 1.727 1.318 1.727.69 0 1.139-.435 1.187-1.05H13.5v.114c-.057 1.147-1.028 1.938-2.342 1.938-1.613 0-2.518-1.028-2.518-2.729v-.747c0-1.7.914-2.751 2.518-2.751 1.318 0 2.29.813 2.342 2v.11h-1.147c-.048-.638-.505-1.108-1.187-1.108z" />
                            </svg>
                            <p class="mt-1 mr-2">170</p>
                        </div>
                        <div class="d-flex flex-row justify-content-center card-design-2">
                            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="black"
                                class="bi bi-mic-fill mt-1 ml-1 mr-1 pl-1" viewBox="0 0 16 16">
                                <path d="M5 3a3 3 0 0 1 6 0v5a3 3 0 0 1-6 0z" />
                                <path
                                    d="M3.5 6.5A.5.5 0 0 1 4 7v1a4 4 0 0 0 8 0V7a.5.5 0 0 1 1 0v1a5 5 0 0 1-4.5 4.975V15h3a.5.5 0 0 1 0 1h-7a.5.5 0 0 1 0-1h3v-2.025A5 5 0 0 1 3 8V7a.5.5 0 0 1 .5-.5" />
                            </svg>
                            <p class="mt-1 mr-2">170</p>
                        </div>
                    </div>
                </div>
                <div class="ml-2">
                    <h2 class="text-white mt-2 heading-bg-design ">Black Clover</h2>
                    <div class="d-flex flex-row">
                        <p class="bg-para-design">TV</p>
                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="#7A7A7A"
                            class="bi bi-dot mt-2" viewBox="0 0 16 16">
                            <path d="M8 9.5a1.5 1.5 0 1 0 0-3 1.5 1.5 0 0 0 0 3" />
                        </svg>
                        <p class="bg-para-design">24m</p>
                    </div>
                </div>
            </div>
            <div class="col-12" id="section_upcoming">
                <h3 class="p-3">
                    Top Upcoming
                </h3>
            </div>
            <div class="col-6 col-sm-6 col-md-4 col-lg-4 col-xl-2 mb-3">
                <img src="https://res.cloudinary.com/dgmfaki8z/image/upload/v1748594912/2018d92a573a8077463893a0c9daec7a_soceiy.jpg"
                    class="top-upcoming-image-section" />
                <h1 class="text-capitalize p-1 mt-1 top-upcoming-head-section">
                    welcome to magical girl...
                </h1>
                <div class="ml-2 d-flex flex-row mb-3">
                    <p class="top-upcoming-para-section">
                        TV(13eps)
                    </p>
                    <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="#cccccc" class="bi bi-dot mt-1"
                        viewBox="0 0 16 16">
                        <path d="M8 9.5a1.5 1.5 0 1 0 0-3 1.5 1.5 0 0 0 0 3" />
                    </svg>
                    <p class="top-upcoming-para-section">April 4, 2025</p>
                </div>
            </div>
            <div class="col-6 col-sm-6 col-md-4 col-lg-4 col-xl-2 mb-3">
                <img src="https://res.cloudinary.com/dgmfaki8z/image/upload/v1748594984/b637a0d05cdec5e596f5c8a3d9fb5228_dzvhvc.jpg "
                    class="top-upcoming-image-section" />
                <h1 class="text-capitalize p-1 mt-1 top-upcoming-head-section">
                    My senior brother is too...
                </h1>
                <div class="ml-2 d-flex flex-row mb-3">
                    <p class="top-upcoming-para-section">
                        OVA(?eps)
                    </p>
                    <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="#cccccc" class="bi bi-dot mt-1"
                        viewBox="0 0 16 16">
                        <path d="M8 9.5a1.5 1.5 0 1 0 0-3 1.5 1.5 0 0 0 0 3" />
                    </svg>
                    <p class="top-upcoming-para-section">Apr 1,2025</p>
                </div>
            </div>
            <div class="col-6 col-sm-6 col-md-4 col-lg-4 col-xl-2 mb-3">
                <img src="https://res.cloudinary.com/dgmfaki8z/image/upload/v1748595196/a1d85dbe80457636ed63ce69990576fc_hxok69.jpg"
                    class="top-upcoming-image-section" />
                <h1 class="text-capitalize p-1 mt-1 top-upcoming-head-section">
                    Word of Honor 2nd..
                </h1>
                <div class="ml-2 d-flex flex-row mb-3">
                    <p class="top-upcoming-para-section">
                        ONA(32 eps)
                    </p>
                    <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="#cccccc" class="bi bi-dot mt-1"
                        viewBox="0 0 16 16">
                        <path d="M8 9.5a1.5 1.5 0 1 0 0-3 1.5 1.5 0 0 0 0 3" />
                    </svg>
                    <p class="top-upcoming-para-section">...</p>
                </div>
            </div>
            <div class="col-6 col-sm-6 col-md-4 col-lg-4 col-xl-2 mb-3">
                <img src="https://res.cloudinary.com/dgmfaki8z/image/upload/v1748595412/5a4e1157b99a71b0d8d5d4ceb65a6846_cw5hxj.jpg "
                    class="top-upcoming-image-section" />
                <h1 class="text-capitalize p-1 mt-1 top-upcoming-head-section">
                    king of prism : your...
                </h1>
                <div class="ml-2 d-flex flex-row mb-3">
                    <p class="top-upcoming-para-section">
                        Movie(1eps)
                    </p>
                    <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="#cccccc" class="bi bi-dot mt-1"
                        viewBox="0 0 16 16">
                        <path d="M8 9.5a1.5 1.5 0 1 0 0-3 1.5 1.5 0 0 0 0 3" />
                    </svg>
                    <p class="top-upcoming-para-section">...</p>
                </div>
            </div>
            <div class="col-6 col-sm-6 col-md-4 col-lg-4 col-xl-2 mb-3">
                <img src="https://res.cloudinary.com/dgmfaki8z/image/upload/v1748595546/28c06ef09d841f55e84e654cfc04686e_foth6s.jpg"
                    class="top-upcoming-image-section" />
                <h1 class="text-capitalize p-1 mt-1 top-upcoming-head-section">
                    Mumei no jinsei
                </h1>
                <div class="ml-2 d-flex flex-row mb-3">
                    <p class="top-upcoming-para-section">
                        Movie(?eps)
                    </p>
                    <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="#cccccc" class="bi bi-dot mt-1"
                        viewBox="0 0 16 16">
                        <path d="M8 9.5a1.5 1.5 0 1 0 0-3 1.5 1.5 0 0 0 0 3" />
                    </svg>
                    <p class="top-upcoming-para-section">...</p>
                </div>
            </div>
            <div class="col-6 col-sm-6 col-md-4 col-lg-4 col-xl-2 mb-3">
                <img src="https://res.cloudinary.com/dgmfaki8z/image/upload/v1748595658/71f1f4df6b41c5446e74eee473c72ae7_vthyam.jpg "
                    class="top-upcoming-image-section" />
                <h1 class="text-capitalize p-1 mt-1 top-upcoming-head-section">
                    dragon heart:...
                </h1>
                <div class="ml-2 d-flex flex-row mb-3">
                    <p class="top-upcoming-para-section">
                        Movie(1eps)
                    </p>
                    <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="#cccccc" class="bi bi-dot mt-1"
                        viewBox="0 0 16 16">
                        <path d="M8 9.5a1.5 1.5 0 1 0 0-3 1.5 1.5 0 0 0 0 3" />
                    </svg>
                    <p class="top-upcoming-para-section">...</p>
                </div>
            </div>
            <div class="col-6 col-sm-6 col-md-4 col-lg-4 col-xl-2 mb-3">
                <img src="https://res.cloudinary.com/dgmfaki8z/image/upload/v1748595784/88137690195e2025d746287b15759423_fa28s5.jpg"
                    class="top-upcoming-image-section" />
                <h1 class="text-capitalize p-1 mt-1 top-upcoming-head-section">
                    mirage queen vacance...
                </h1>
                <div class="ml-2 d-flex flex-row mb-3">
                    <p class="top-upcoming-para-section">
                        Movie(1eps)
                    </p>
                    <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="#cccccc" class="bi bi-dot mt-1"
                        viewBox="0 0 16 16">
                        <path d="M8 9.5a1.5 1.5 0 1 0 0-3 1.5 1.5 0 0 0 0 3" />
                    </svg>
                    <p class="top-upcoming-para-section">...</p>
                </div>
            </div>
            <div class="col-6 col-sm-6 col-md-4 col-lg-4 col-xl-2 mb-3">
                <img src="https://res.cloudinary.com/dgmfaki8z/image/upload/v1748595897/32e9575de6ae40a1d1863944d7713cfa_xfxdl6.jpg"
                    class="top-upcoming-image-section" />
                <h1 class="text-capitalize p-1 mt-1 top-upcoming-head-section">
                    me & robaco movie
                </h1>
                <div class="ml-2 d-flex flex-row mb-3">
                    <p class="top-upcoming-para-section">
                        Movie(?eps)
                    </p>
                    <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="#cccccc" class="bi bi-dot mt-1"
                        viewBox="0 0 16 16">
                        <path d="M8 9.5a1.5 1.5 0 1 0 0-3 1.5 1.5 0 0 0 0 3" />
                    </svg>
                    <p class="top-upcoming-para-section">...</p>
                </div>
            </div>
            <div class="col-6 col-sm-6 col-md-4 col-lg-4 col-xl-2 mb-3">
                <img src="https://res.cloudinary.com/dgmfaki8z/image/upload/v1748596025/ecb445812628e03b9f638296a8eb7818_ux6p9f.jpg "
                    class="top-upcoming-image-section" />
                <h1 class="text-capitalize p-1 mt-1 top-upcoming-head-section">
                    Uta no Prince -sama...
                </h1>
                <div class="ml-2 d-flex flex-row mb-3">
                    <p class="top-upcoming-para-section">
                        Movie(1eps)
                    </p>
                    <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="#cccccc" class="bi bi-dot mt-1"
                        viewBox="0 0 16 16">
                        <path d="M8 9.5a1.5 1.5 0 1 0 0-3 1.5 1.5 0 0 0 0 3" />
                    </svg>
                    <p class="top-upcoming-para-section">....</p>
                </div>
            </div>
            <div class="col-6 col-sm-6 col-md-4 col-lg-4 col-xl-2 mb-3">
                <img src="https://res.cloudinary.com/dgmfaki8z/image/upload/v1748596326/953be7ad257da53272b03646de460634_aywudy.jpg"
                    class="top-upcoming-image-section" />
                <h1 class="text-capitalize p-1 mt-1 top-upcoming-head-section">
                    Detective canan movie ...
                </h1>
                <div class="ml-2 d-flex flex-row mb-3">
                    <p class="top-upcoming-para-section">
                        Movie(1eps)
                    </p>
                    <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="#cccccc" class="bi bi-dot mt-1"
                        viewBox="0 0 16 16">
                        <path d="M8 9.5a1.5 1.5 0 1 0 0-3 1.5 1.5 0 0 0 0 3" />
                    </svg>
                    <p class="top-upcoming-para-section">....</p>
                </div>
            </div>
            <div class="col-6 col-sm-6 col-md-4 col-lg-4 col-xl-2 mb-3">
                <img src="https://res.cloudinary.com/dgmfaki8z/image/upload/v1748596445/6f3d441589f469e11e2bf78109ee0770_fe6e4t.jpg "
                    class="top-upcoming-image-section" />
                <h1 class="text-capitalize p-1 mt-1 top-upcoming-head-section">
                    princess principal : crow...
                </h1>
                <div class="ml-2 d-flex flex-row mb-3">
                    <p class="top-upcoming-para-section">
                        Movie(1eps)
                    </p>
                    <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="#cccccc" class="bi bi-dot mt-1"
                        viewBox="0 0 16 16">
                        <path d="M8 9.5a1.5 1.5 0 1 0 0-3 1.5 1.5 0 0 0 0 3" />
                    </svg>
                    <p class="top-upcoming-para-section">....</p>
                </div>
            </div>
            <div class="col-6 col-sm-6 col-md-4 col-lg-4 col-xl-2 mb-3">
                <img src="https://res.cloudinary.com/dgmfaki8z/image/upload/v1748596582/9090e69faf3fbe3479473385650e6d43_tyqhug.jpg"
                    class="top-upcoming-image-section" />
                <h1 class="text-capitalize p-1 mt-1 top-upcoming-head-section">
                    clockwork girl
                </h1>
                <div class="ml-2 d-flex flex-row mb-3">
                    <p class="top-upcoming-para-section">
                        Movie(1eps)
                    </p>
                    <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="#cccccc" class="bi bi-dot mt-1"
                        viewBox="0 0 16 16">
                        <path d="M8 9.5a1.5 1.5 0 1 0 0-3 1.5 1.5 0 0 0 0 3" />
                    </svg>
                    <p class="top-upcoming-para-section">....</p>
                </div>
            </div>
            <footer class="m-auto footer" id="section_about_us">
                <div class="d-flex flex-row justify-content-center channel-background m-auto pl-4 pr-4">
                    <a href="">
                        <div class="m-2 icon-bg-1-discord">
                            <i class="fa-brands fa-discord icon-color"></i>
                        </div>
                    </a>
                    <a href="">
                        <div class="m-2 icon-bg-2-telegram">
                            <i class="fa-brands fa-telegram icon-color"></i>
                        </div>
                    </a>
                    <a href="">
                        <div class="m-2 icon-bg-3-reddit">
                            <i class="fa-brands fa-reddit icon-color"></i>
                        </div>
                    </a>
                    <a href="">
                        <div class="m-2 icon-bg-4-twitter">
                            <i class="fa-brands fa-twitter icon-color"></i>
                        </div>
                    </a>
                </div>
                <div class="d-flex flex-row justify-content-center">
                    <ul class="d-flex flex-row">
                        <a>
                            <li class="pr-1">
                                Terms of services
                            </li>
                        </a>
                        <a>
                            <li>DMCA</li>
                        </a>
                        <a>
                            <li>Contact</li>
                        </a>
                        <a>
                            <li>Aniverse App</li>
                        </a>
                    </ul>
                </div>
                <div class="d-flex flex-column justify-content-center">
                    <p class="footer-paragraph text-center p-2">
                        Aniverse doesnot store any files on our server , we only linked to the media which is hosted on
                        3rd party services
                    </p>
                    <div class="d-flex flex-row justify-content-center">
                        <i class="fa-regular fa-copyright cc-icon mt-2"></i>
                        <p class="footer-paragraph text-center p-2">
                            Aniverse.to.All rights reserved.
                        </p>
                    </div>
                </div>
            </footer>
        </div>
    </div>
</body>

</html>
