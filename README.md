<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Personal Website</title>

  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
  <style>

    .gradient-background {
  background: linear-gradient(300deg, #cccccc, #868d94, #000000);
  background-size: 180% 180%;
  animation: gradient-animation 18s ease infinite;
}

@keyframes gradient-animation {
  0% {
    background-position: 0% 50%;
  }
  50% {
    background-position: 100% 50%;
  }
  100% {
    background-position: 0% 50%;
  }
}


h1 {
  font-family: "Playwrite AU SA", cursive;
  font-optical-sizing: auto;
  font-weight: 400;
  font-style: normal;
}


p {
  font-family: "Plus Jakarta Sans", sans-serif;
  font-optical-sizing: auto;
} 

li {
  font-family: "Plus Jakarta Sans", sans-serif;
}

  </style>

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Playwrite+AU+SA:wght@100..400&family=Playwrite+IE:wght@100..400&family=Plus+Jakarta+Sans:ital,wght@0,200..800;1,200..800&display=swap" rel="stylesheet">
</head>

<body>
    <section id="title" class="gradient-background">
    <div class="container col-xxl-8 px-4 py-5">
        <div class="row flex-lg-row-reverse align-items-center g-5 py-5">
          <div class="col-10 col-sm-8 col-lg-6">
            <img src="./assets/images/Circle Artsy Sparrow Circle.png" class="d-block mx-lg-auto img-fluid" alt="Artsy Sparrow Logo" width="700" height="500" loading="lazy">
          </div>
          <div class="col-lg-6">
            <h1 class="display-5 fw-bold text-body-emphasis lh-1 mb-3">Hello! I'm Erin.</h1>
            <p class="lead">Welcome to Artsy Sparrow Designs.</p>
            <div class="d-grid gap-2 d-md-flex justify-content-md-start">
            </div>
          </div>
        </div>
      </div>
    </section>

    <div class="profile-pic">
    <div class="px-4 py-5 my-5 text-center">
        <img class="d-block mx-auto mb-4" src="./assets/images/project pic.jpg" alt="profile pic" width="300" height="400">
        <h1 class="display-5 fw-bold text-body-emphasis">I'm a programmer.</h1>
        <div class="col-lg-6 mx-auto">
          <p class="lead mb-4">Well, I'm learning how to be one. This site is to show off some of my work and to build my portfolio. </p>
          <div class="d-grid gap-2 d-sm-flex justify-content-sm-center">
          </div>
        </div>
      </div>
    </div>

    <div class="card-group">
        <div class="card">
          <img src="./assets/images/Poster.jpeg" class="card-img-top" alt="pup poster">
          <div class="card-body">
            <h5 class="card-title">Motivational Poster</h5>
            <p class="card-text">One of my favorite projects so far!</p>
          </div>
          <div class="card-footer">
          </div>
        </div>
        <div class="card">
          <img src="./assets/images/Mondrian.jpeg" class="card-img-top" alt="mondrian project">
          <div class="card-body">
            <h5 class="card-title">Mondrian Project</h5>
            <p class="card-text">Looks simple enough but this whole picture was made with CSS.</p>
          </div>
          <div class="card-footer">
          </div>
        </div>
        <div class="card">
          <img src="./assets/images/Checker.jpeg" class="card-img-top" alt="checkerboard">
          <div class="card-body">
            <h5 class="card-title">CSS Checkerboard Project</h5>
            <p class="card-text">HTML and CSS can make some beautiful designs!</p>
          </div>
          <div class="card-footer">
          </div>
        </div>
      </div>

      <div class="card-group">
        <div class="card">
          <a href="./Big Papi Cigar/index.html"> <img src="./assets/images/Cigar.jpeg" class="card-img-top" alt="cigar website"></a>
          <div class="card-body">
            <h5 class="card-title">Big Papi Cigar Co.</h5>
            <p class="card-text">A fictional website I created for my man using Bootstrap.</p>
          </div>
          <div class="card-footer">
          </div>
        </div>
        <div class="card">
          <a href="./Move It/index2.html"><img src="./assets/images/Move It.jpeg" class="card-img-top" alt="Move It Website"></a>
          <div class="card-body">
            <h5 class="card-title">Move It</h5>
            <p class="card-text">Another fictional website using Bootstrap.</p>
          </div>
          <div class="card-footer">
          </div>
        </div>
        <div class="card">
          <a href="./TinDog/index.html"><img src="./assets/images/TinDog.jpeg" class="card-img-top" alt="Tin Dog project"></a>
          <div class="card-body">
            <h5 class="card-title">Tin Dog Website</h5>
            <p class="card-text">A creative website idea for dogs to meet new friends.</p>
          </div>
          <div class="card-footer">
          </div>
        </div>
      </div>

      <footer class="py-3 my-4">
        <ul class="nav justify-content-center border-bottom pb-3 mb-3">
          <li class="nav-item"><a href="./public/about.html" class="nav-link px-2 text-body-secondary">About Me</a></li>
          <li class="nav-item"><a href="./public/favs.html" class="nav-link px-2 text-body-secondary">Favorite Things</a></li>
          <li class="nav-item"><a href="./Resume.html" class="nav-link px-2 text-body-secondary">Resumé</a></li>
        </ul>
        <p class="text-center text-body-secondary">© Artsy Sparrow Designs. All rights reserved.</p>
      </footer>




<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>
</body>

</html>
