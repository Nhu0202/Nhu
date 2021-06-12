<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>ENEWS</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-+0n0xVW2eSR5OomGNYDnhzAbDsOXxcvSN1TPprVMTNDbiYZCxYbOOl7+AMvyTG2x" crossorigin="anonymous">
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.5.0/font/bootstrap-icons.css">
</head>
<body>
  <header class="p-3 mb-3 border-bottom">
    <div class="container">
      <div class="d-flex flex-wrap align-items-center justify-content-center justify-content-lg-start">
        <a href="/" class="d-flex align-items-center mb-2 mb-lg-0 text-dark text-decoration-none">
          <svg class="bi me-2" width="40" height="32" role="img" aria-label="Bootstrap"><use xlink:href="#bootstrap"></use></svg>
        </a>

        <ul class="nav col-12 col-lg-auto me-lg-auto mb-2 justify-content-center mb-md-0">
          <li><a href="index.html" class="nav-link px-2 link-secondary">Trang chủ</a></li>
          <li><a href="#" class="nav-link px-2 link-dark">Inventory</a></li>
          <li><a href="#" class="nav-link px-2 link-dark">Customers</a></li>
          <li><a href="#" class="nav-link px-2 link-dark">Products</a></li>
        </ul>

        <form class="col-12 col-lg-auto mb-3 mb-lg-0 me-lg-3">
          <input type="search" class="form-control" placeholder="Search..." aria-label="Search">
        </form>

        <div class="dropdown text-end">
          <a href="#" class="d-block link-dark text-decoration-none dropdown-toggle" id="dropdownUser1" data-bs-toggle="dropdown" aria-expanded="false">
            <i class="bi bi-person-circle"></i>
          </a>
          <ul class="dropdown-menu text-small" aria-labelledby="dropdownUser1">
            <li><a class="dropdown-item" href="login.html">Sign in</a></li>
            <li><hr class="dropdown-divider"></li>
            <li><a class="dropdown-item" href="signin.html">registration</a></li>
          </ul>
        </div>
      </div>
    </div>
  </header>
  <div class="container-fluid mt-3">
    <div class="row">
      <div class="col-3">
        <div class="card shadow">
          <h4 class="card-header">
            Categories
          </h4>
          <div class="list-group list-group-flush">
            <a href="#" class="list-group-item list-group-item-action active" aria-current="true">
              Nông sản
            </a>
            <a href="#" class="list-group-item list-group-item-action">
              Thuỷ sản
            </a>
            <a href="#" class="list-group-item list-group-item-action disabled" tabindex="-1" aria-disabled="true">A
              disabled link
              item</a>
          </div>
        </div>
        <div class="card mt-3 shadow">
          <h4 class="card-header">
            Tag
           </h4>
          <div class="list-group list-group-flush">
            <a href="#" class="list-group-item list-group-item-action active" aria-current="true">
              Trái cây
            </a>
            <a href="#" class="list-group-item list-group-item-action">Rau củ</a>
            <a href="#" class="list-group-item list-group-item-action">Chăn nuôi</a>
            <a href="#" class="list-group-item list-group-item-action">Đánh bắt</a>
            <a href="#" class="list-group-item list-group-item-action disabled" tabindex="-1" aria-disabled="true">A
              disabled link
              item</a>
          </div>
        </div>
      </div>
    </div>
  </div>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.1/dist/js/bootstrap.bundle.min.js" integrity="sha384-gtEjrD/SeCtmISkJkNUaaKMoLD0//ElJ19smozuHV6z3Iehds+3Ulb9Bn9Plx0x4" crossorigin="anonymous"></script>
</body>
</html>
