# simple-site
simple bootsrap tutorial site
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ephraim frst web page on bootstrap
    </title>
    <link rel="stylesheet" href="css/bootstrap.css">
</head>
<body>
    <header>
    <nav class="navbar navbar-expand-lg navbar-dark  bg-dark ">
        <div class="container-fluid">
          <a class="navbar-brand" href="#">Navbar</a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav me-auto mb-2 mb-lg-0">
              <li class="nav-item">
                <a class="nav-link active" aria-current="page" href="#">Home</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Link</a>
              </li>
              <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                  Dropdown
                </a>
                <ul class="dropdown-menu">
                  <li><a class="dropdown-item" href="#">Action</a></li>
                  <li><a class="dropdown-item" href="#">Another action</a></li>
                  <li><hr class="dropdown-divider"></li>
                  <li><a class="dropdown-item" href="#">Something else here</a></li>
                </ul>
              </li>
            </ul>
            <form class="d-flex" role="search">
              <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
              <button class="btn btn-outline-success" type="submit">Search</button>
            </form>
          </div>
        </div>
      </nav>
    </header>
    <main class="my-5">
        <div class="container">
            <div class="row">
                <div class="col-md-7">
                    <img src="ephraim1.jpg" alt="ephraim" class="img-fluid">
                </div>
                <div class="col-md-5">
                    <h1 >Tagline</h1>
                    <p class="mt-4">Lorem ipsum dolor sit amet consectetur adipisicing elit. Tempore, labore ea. Officia, delectus a obcaecati iste expedita facilis minus minima ea, doloribus beatae laboriosam deserunt eos placeat explicabo eius repellendus.
                    </p>
<button type="button" class="btn btn-primary mt-3">call to action</button>
                </div>
            </div>
            <div class="row">
                <div class="col">
                <div class="bg-secondary text-white my-5 py-4 card">
                    <div class="card-body">
                        Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptate, aliquam.
                    </div>
                </div>
                </div>
            </div>
            <div class="row">
                <div class="col">
                    <div class="card-group">
                        <div class="card">
                          <img src="ephraim1.jpg" class="card-img-top" alt="...">
                          <div class="card-body">
                            <h5 class="card-title">Card title</h5>
                            <p class="card-text">This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
                            <p class="card-text"><small class="text-muted">Last updated 3 mins ago</small></p>
                            <div class="text-center">
                                <button type="button" class="btn btn-primary">read more</button>
                            </div>
                          </div>
                        </div>
                        <div class="card">
                          <img src="ephraim1.jpg" class="card-img-top" alt="...">
                          <div class="card-body">
                            <h5 class="card-title">Card title</h5>
                            <p class="card-text">This card has supporting text below as a natural lead-in to additional content.</p>
                            <p class="card-text"><small class="text-muted">Last updated 3 mins ago</small></p>
                            <div class="text-center">
                                <button type="button" class="btn btn-primary">read more</button>
                            </div>
                          </div>
                        </div>
                        <div class="card">
                          <img src="ephraim1.jpg" class="card-img-top" alt="...">
                          <div class="card-body">
                            <h5 class="card-title">Card title</h5>
                            <p class="card-text">This is a wider card with supporting text below as a natural lead-in to additional content. This card has even longer content than the first to show that equal height action.</p>
                            <p class="card-text"><small class="text-muted">Last updated 3 mins ago</small></p>
                            <div class="text-center">
                                <button type="button" class="btn btn-primary">read more</button>
                            </div>
                          </div>
                        </div>
                      </div>
                </div>
            </div>
            <div class="row justify-content-center">
                <form action="" class="form-control w-50">
                  <p class="h1 text-center">Get In touch with us </p>
                <label for="email">Email</label>
                <input type="email" id="email" placeholder="etey@gmail.com" class="form-control">
                <label for="subject">please choose a subject</label>
                <select name="subject" class="form-control form-select">
                  <option value="complaint">complaint</option>
                  <option value="comment">comment</option>
                  <option value="appreciation">appreciation</option>
                  <option value="not sure">not sure</option>
                </select>
                <div >
                <label for="query">write your message here</label>
                <textarea name="query" id="query" cols="20" rows="5" class="form-control"></textarea>
                </div>
                <div class="text-center my-5">
                    <input type="submit" name="submit" placeholder="submit query" class="btn btn-primary">
                </div>
                </form>
                </div>
        </div>
    </main>
    <footer class="footer mt-auto py-3 bg-dark">
        <div class="container">
          <span class="text-muted">copyright@ephraim gethi 2022 </span>
        </div>
      </footer>
<script src="js/bootstrap.bundle.js"></script>
</body>
</html>
