<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title>Dhinesh's portfolio</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-+0n0xVW2eSR5OomGNYDnhzAbDsOXxcvSN1TPprVMTNDbiYZCxYbOOl7+AMvyTG2x" crossorigin="anonymous">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" >
  </head>
  <body>
    <nav class="navbar sticky-top navbar-expand-lg navbar-dark bg-primary">
      <div class="container-fluid">
        <a class="navbar-brand text-white" href="#">Dhinesh M</a>
        <button class="navbar-toggler" typse="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav me-auto mb-2 mb-lg-0">
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="#hero">Home</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#skills">My Skills</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#works">My Works</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#contact">Cotact Me</a>
            </li>
        </div>
      </div>
    </nav>
    <main class="container mt-3">
      <section id="hero" class="d-flex justify-content-sm-center justify-content-md-evenly align-items-center flex-column-reverse gap-3 flex-md-row">
        <div class="d-flex justify-content-sm-center align-items-center flex-column justify-content-md-start align-items-md-start">
          <h5>I'm Dhinesh M</h5>
          <p>An engineering Student</p>
          <button class="btn btn-primary btn-sm" type="button" name="button">My cool resume</button>
        </div>
        <div class="d-md-none w-50 w-50">
          <img src="https://images.unsplash.com/photo-1494548162494-384bba4ab999?ixid=MnwxMjA3fDB8MHxzZWFyY2h8MXx8ZGF3bnxlbnwwfHwwfHw%3D&ixlib=rb-1.2.1&w=1000&q=80" alt="Dhinesh M" class="w-100 h-100 rounded-circle shadow">
        </div>
        <div class="d-none d-md-block w-25 h-25" >
          <img src="https://images.unsplash.com/photo-1494548162494-384bba4ab999?ixid=MnwxMjA3fDB8MHxzZWFyY2h8MXx8ZGF3bnxlbnwwfHwwfHw%3D&ixlib=rb-1.2.1&w=1000&q=80" alt="Dhinesh M" class="w-100 h-100 rounded-circle shadow">
        </div>
      </section>
      <section id="skills" class="mt-5 p-4 ">
        <h1 class="text-primary text-center">My Skill set</h1>
        <div class="mt-4 d-md-none d-flex justify-content-evenly">
          <i class="fab fa-html5 fa-3x"style="color:#f4470b"></i>
          <i class="fab fa-css3-alt fa-3x text-primary"></i>
          <i class="fab fa-bootstrap fa-3x" style="color:#730fef"></i>
        </div>
        <div class="mt-4 d-none d-md-flex justify-content-evenly">
          <i class="fab fa-html5 fa-7x"style="color:#f4470b"></i>
          <i class="fab fa-css3-alt fa-7x text-primary"></i>
          <i class="fab fa-bootstrap fa-7x" style="color:#730fef"></i>
        </div>
      </section>
      <section id="works" class="mt-4 p-4">
        <h1 class="text-primary text-center">My Work</h1>
        <div class="row">
          <div class="col-sm col-md-4">
        <div class="card mb-2">
          <img src="https://images.unsplash.com/photo-1488590528505-98d2b5aba04b?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=750&q=80" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title">Portfolio Website</h5>
            <p class="card-text">Built an amazing responsive website with Bootstrap.</p>
            <a href="#" class="btn btn-dark">view Source <i class="fab fa-github"></i></a>
          </div>
        </div>
      </div>
      <div class="col-sm col-md-4">
    <div class="card mb-2">
      <img src="https://images.unsplash.com/photo-1488590528505-98d2b5aba04b?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=750&q=80" class="card-img-top" alt="...">
      <div class="card-body">
        <h5 class="card-title">Portfolio Website</h5>
        <p class="card-text">Built an amazing responsive website with Bootstrap.</p>
        <a href="#" class="btn btn-dark">view Source <i class="fab fa-github"></i></a>
      </div>
    </div>
  </div>
  <div class="col-sm col-md-4">
<div class="card mb-2">
  <img src="https://images.unsplash.com/photo-1488590528505-98d2b5aba04b?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=750&q=80" class="card-img-top" alt="...">
  <div class="card-body">
    <h5 class="card-title">Portfolio Website</h5>
    <p class="card-text">Built an amazing responsive website with Bootstrap.</p>
    <a href="#" class="btn btn-dark">view Source <i class="fab fa-github"></i></a>
  </div>
</div>
</div>
      </div>
      </section>
      <section id="contact" class="mt-4 py-4">
      <h1 class="text-primary text-center">Contact Form</h1>
      <div class="row">
        <div class="col-sm col-md-8">
      <form>
        <div class="mb-3">
          <label for="exampleFormControlInput1" class="form-label">Email address</label>
          <input type="email" required class="form-control" id="exampleFormControlInput1" placeholder="name@example.com">
        </div>
        <div class="mb-3">
          <label for="exampleFormControlTextarea1" class="form-label">Your message</label>
          <textarea class="form-control" id="exampleFormControlTextarea1" required placeholder="enter you amazing message!" rows="3"></textarea>
        </div>
        <button type="submit" class="btn btn-primary" >
          submit
        </button>
      </forms>
      </div>
      <div class="col-sm col-md-4">
      <div class="mt-3">
        <h4>
          <i class="fas fa-at"></i>
          mdhinesh@gmail.com
        </h4>
        <button type="button" class="btn btn-link">
          <a href="https://github.com/">
            <i class="fab fa-github"></i>
          </a>
        </button>
      </div>
    </div>

      </section>
    </main>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.1/dist/js/bootstrap.bundle.min.js" integrity="sha384-gtEjrD/SeCtmISkJkNUaaKMoLD0//ElJ19smozuHV6z3Iehds+3Ulb9Bn9Plx0x4" crossorigin="anonymous"></script>
  </body>
</html>
