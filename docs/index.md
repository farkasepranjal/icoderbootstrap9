<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>

  <!-- CSS only -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0/dist/css/bootstrap.min.css" rel="stylesheet"
    integrity="sha384-gH2yIJqKdNHPEq0n4Mqa/HGKIhSkIHeL5AyhkYV8i59U5AR6csBvApHHNl/vI1Bx" crossorigin="anonymous">
  <!-- JavaScript Bundle with Popper -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0/dist/js/bootstrap.bundle.min.js"
    integrity="sha384-A3rJD856KowSb7dwlZdYEkO39Gagi7vIsF0jrRAoQmDKKtQBHUuLZ9AsSv4jD4Xa"
    crossorigin="anonymous"></script>
</head>

<body>
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">iCoder</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav me-auto mb-2 mb-lg-0">
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="home.html">Home</a>
          </li>
          <li class="nav-item active">
            <a class="nav-link active" href="about.html">About</a>

          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle active" href="#" role="button" data-bs-toggle="dropdown"
              aria-expanded="false">
              Topics
            </a>
            <ul class="dropdown-menu">
              <li><a class="dropdown-item" href="#"> Technology</a></li>
              <li><a class="dropdown-item" href="#">Web Development</a></li>
              <li>
                <hr class="dropdown-divider">
              </li>

              <li><a class="dropdown-item" href="#">Support</a></li>
              <li><a class="dropdown-item" href="#">Write for us</a></li>
            </ul>
          <li class="nav-item">
            <a class="nav-link active" href="contact.html">Contact Us</a>
          </li>
          </li>

        </ul>
        <form class="d-flex" role="search">
          <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
          <button class="btn btn-outline-success" type="submit">Search</button>
        </form>
        <div class="mx-2">
        <!-- Button trigger modal -->
<button type="button" class="btn btn-primary" data-bs-toggle="modal" data-bs-target="#exampleModal">
  Signup
</button>

<!-- Modal -->
<div class="modal fade" id="exampleModal" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
  <div class="modal-dialog">
    <div class="modal-content">
      <div class="modal-header">
        <h5 class="modal-title" id="exampleModalLabel">iCoder Signup</h5>
        <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
      </div>
      <div class="modal-body">
        <div class="mb-3 row">
          <label for="inputEmail" class="col-sm-2 col-form-label">Email</label>
          <div class="col-sm-10">
            <input type="text"  class="form-control" id="inputEmail"  >
          </div>
          </div>
          <div class="mb-3 row">
            <label for="inputEmail" class="col-sm-2 col-form-label"> re-enter Email</label>
            <div class="col-sm-10">
              <input type="text"  class="form-control" id="inputEmail"  >
            </div>
        </div>
        <div class="mb-3 row">
          <label for="inputPassword" class="col-sm-2 col-form-label">Password</label>
          <div class="col-sm-10">
            <input type="password" class="form-control" id="inputPassword" >
          </div>
        </div>
        <div class="mb-3 row">
          <label for="inputPassword" class="col-sm-2 col-form-label"> confirm Password</label>
          <div class="col-sm-10">
            <input type="password" class="form-control" id="inputPassword" >
          </div>
        
      </div>

      <div class="modal-footer">
        <button type="button" class="btn btn-secondary" data-bs-dismiss="modal" >Close</button>
        <button type="button"class="btn btn-primary" data-bs-dismiss="modal">submit</button>

      </div>
    </div>
  </div>
</div>
</div>

<!-- Button trigger modal -->
<button type="button" class="btn btn-primary" data-bs-toggle="modal" data-bs-target="#cexampleModal">
  Login 

</button>

<!-- Modal -->
<div class="modal fade" id="cexampleModal" tabindex="-1" aria-labelledby="cexampleModalLabel" aria-hidden="true">
  <div class="modal-dialog">
    <div class="modal-content">
      <div class="modal-header">
        <h5 class="modal-title" id="cexampleModalLabel">login iCoder</h5>
        <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
      </div>
      <div class="modal-body">
        <div class="mb-3 row">
          <label for="staticEmail" class="col-sm-2 col-form-label">Email</label>
          <div class="col-sm-10">
            <input type="text" class="form-control" id="staticEmail">
          </div>
        </div>
        <div class="mb-3 row">
          <label for="inputPassword" class="col-sm-2 col-form-label">Password</label>
          <div class="col-sm-10">
            <input type="password" class="form-control" id="inputPassword">
          </div>
        </div>
      </div>
      <div class="modal-footer">
        <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
        <button type="button" class="btn btn-primary">submit</button>
      </div>
    </div>
  </div>
</div>


       </div>
      </div>
    </div>
  </nav>


  <div id="carouselExampleCaptions" class="carousel slide carousel-fade " data-bs-ride="false">
    <div class="carousel-indicators">
      <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active"
        aria-current="true" aria-label="Slide 1"></button>
      <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1"
        aria-label="Slide 2"></button>
      <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2"
        aria-label="Slide 3"></button>
    </div>
    <div class="carousel-inner">
      <div class="carousel-item active">
        <img
          src="https://assets.entrepreneur.com/content/3x2/2000/1649279368-Ent-2022Python.jpeg?auto=webp&quality=95&crop=16:9&width=500"
          height="500px" width="800px" class="d-block w-100" alt="...">
        <div class="carousel-caption d-none d-md-block">
          <h2>Welcome to iCoder</h2>
          <p>Technology News,Development,and Trends</p>
          <button class="btn btn-primary"> Technology</button>
          <button class="btn btn-danger"> Web Development</button>
          <button class="btn btn-success"> Tech fund</button>
        </div>
      </div>
      <div class="carousel-item">
        <img
          src="https://www.freecodecamp.org/news/content/images/size/w500/2022/02/arnold-francisca-f77Bh3inUpE-unsplash.jpg"
          height="500px" width="800px" class="d-block w-100" alt="...">
        <div class="carousel-caption d-none d-md-block">
          <h2>Award Text Blog</h2>
          <p>Technology News,Development,and Trends</p>
          <button class="btn btn-primary"> Technology</button>
          <button class="btn btn-danger"> Web Development</button>
          <button class="btn btn-success"> Tech fund</button>
        </div>
      </div>
      <div class="carousel-item">
        <img
          src="https://www.itprotoday.com/sites/itprotoday.com/files/styles/article_featured_standard/public/programming%20evolution.jpg?itok=TnBIz21w"
          height="500px" width="800px" class="d-block w-100" alt="...">
        <div class="carousel-caption d-none d-md-block">
          <h2>The Best Coding Blog</h2>
          <p>Technology News,Development,and Trends</p>
          <button class="btn btn-primary"> Technology</button>
          <button class="btn btn-danger"> Web Development</button>
          <button class="btn btn-success"> Tech fund</button>
        </div>
      </div>
    </div>
    <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="prev">
      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Previous</span>
    </button>
    <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="next">
      <span class="carousel-control-next-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Next</span>
    </button>
  </div>

  <div class="container my-4">
    <div class="row mb-2">
      <div class="col-md-6">
        <div class="row g-0 border rounded overflow-hidden flex-md-row mb-4 shadow-sm h-md-250 position-relative">
          <div class="col p-4 d-flex flex-column position-static">
            <strong class="d-inline-block mb-2 text-primary">World</strong>
            <h3 class="mb-0">Featured post</h3>
            <div class="mb-1 text-muted">Nov 12</div>
            <p class="card-text mb-auto">This is a wider card with supporting text below as a natural lead-in to
              additional content.</p>
            <a href="https://img.freepik.com/premium-photo/autumn-forest-with-trees-yellow-leaves-autumn-river-city_577614-95.jpg?size=338&ext=jpg"
              class="stretched-link">Continue reading</a>
          </div>
          <div class="col-auto d-none d-lg-block">
            <img
              src="https://img.freepik.com/free-photo/vertical-shot-tree-background-white-sky_181624-59248.jpg?size=338&ext=jpg"
              height="300px" alt="">

          </div>
        </div>
      </div>
      <div class="col-md-6">
        <div class="row g-0 border rounded overflow-hidden flex-md-row mb-4 shadow-sm h-md-250 position-relative">
          <div class="col p-4 d-flex flex-column position-static">
            <strong class="d-inline-block mb-2 text-success">Design</strong>
            <h3 class="mb-0">Post title</h3>
            <div class="mb-1 text-muted">Nov 11</div>
            <p class="mb-auto">This is a wider card with supporting text below as a natural lead-in to additional
              content.</p>
            <a href="https://img.freepik.com/free-photo/vertical-shot-scenery-yellowstone-national-park-wyoming-usa_181624-9912.jpg?size=338&ext=jpg"
              class="stretched-link">Continue reading</a>
          </div>
          <div class="col-auto d-none d-lg-block">
            <img
              src="https://img.freepik.com/free-photo/beautiful-shot-small-lake-with-wooden-rowboat-focus-breathtaking-clouds-sky_181624-2490.jpg?size=626&ext=jpg"
              height="300px" alt="">

          </div>
        </div>
      </div>
    </div>

  </div>

  <div class="container my-4">
    <div class="row mb-2">
      <div class="col-md-6">
        <div class="row g-0 border rounded overflow-hidden flex-md-row mb-4 shadow-sm h-md-250 position-relative">
          <div class="col p-4 d-flex flex-column position-static">
            <strong class="d-inline-block mb-2 text-primary">World</strong>
            <h3 class="mb-0">Featured post</h3>
            <div class="mb-1 text-muted">Nov 12</div>
            <p class="card-text mb-auto">This is a wider card with supporting text below as a natural lead-in to
              additional content.</p>
            <a href="https://img.freepik.com/premium-photo/autumn-forest-with-trees-yellow-leaves-autumn-river-city_577614-95.jpg?size=338&ext=jpg"
              class="stretched-link">Continue reading</a>
          </div>
          <div class="col-auto d-none d-lg-block">
            <img
              src="https://img.freepik.com/free-photo/vertical-shot-tree-background-white-sky_181624-59248.jpg?size=338&ext=jpg"
              height="300px" alt="">

          </div>
        </div>
      </div>
      <div class="col-md-6">
        <div class="row g-0 border rounded overflow-hidden flex-md-row mb-4 shadow-sm h-md-250 position-relative">
          <div class="col p-4 d-flex flex-column position-static">
            <strong class="d-inline-block mb-2 text-success">Design</strong>
            <h3 class="mb-0">Post title</h3>
            <div class="mb-1 text-muted">Nov 11</div>
            <p class="mb-auto">This is a wider card with supporting text below as a natural lead-in to additional
              content.</p>
            <a href="https://img.freepik.com/free-photo/vertical-shot-scenery-yellowstone-national-park-wyoming-usa_181624-9912.jpg?size=338&ext=jpg"
              class="stretched-link">Continue reading</a>
          </div>
          <div class="col-auto d-none d-lg-block">
            <img
              src="https://img.freepik.com/free-photo/beautiful-shot-small-lake-with-wooden-rowboat-focus-breathtaking-clouds-sky_181624-2490.jpg?size=626&ext=jpg"
              height="300px" alt="">

          </div>
        </div>
      </div>
    </div>

  </div>

  <footer class="container">
    <p class="float-end"><a href="#">Back to top</a></p>
    <p>© 2021–2022 iCoder, Inc. · <a href="#">Privacy</a> · <a href="#">Terms</a></p>
  </footer>



</body>

</html>
