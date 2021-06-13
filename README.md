# Nhu
Newspaper website
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


     <div class="col-5"> <!---Bài viết nổi bật + Bài viết được xem nhiều nhất-->
        <div class="card-body">
         <h5 class="card-title">
           Bài viết nổi bật
         </h5>
        </div>
          <div class="card mb-3" style="max-width: 560px;">
            <div class="row g-0">
              <div class="col-md-4">
                <img src="img/R3fb441f915b7db9d519dedd4c3261cfb.jpg" class="img-thumbnail" alt="mdo">
              </div>
              <div class="col-md-8">
                <div class="card-body">
                  <h5 class="card-title">
                    Thị trường nông lâm thuỷ sản
                  </h5>
                  <p class="card-text"><small class="text-muted">10/12/2020</small></p>
                  <p class="card-text">
                    Cục suất nhập khẩu , bộ công thương xin giới thiệu tới bạn đọc bản tin về thị trường nông lâm thuỷ sản 
                  </p>
                <div class="d-grid gap-2 d-md-flex justify-content-md-end">
                    <button class="btn btn-primary me-md-2" type="button">
                      <a href="https://bitly.com.vn/0nyfvj" class="nav-link px-2 link-dark">Details</a>
                    </button>
                </div>
                </div>
              </div>
            </div>
          </div>
          <div class="card mb-3" style="max-width: 560px;">
            <div class="row g-0">
              <div class="col-md-4">
                <img src="img/3.jpg" class="img-thumbnail" alt="mdo">
              </div>
              <div class="col-md-8">
                <div class="card-body">
                  <h5 class="card-title">
                    Tỉnh đoàn Tiền Giang hỗ trợ nông dân tiêu thụ nông sản
                  </h5>
                  <p class="card-text"><small class="text-muted">11/6/2021</small></p>
                  <p class="card-text">
                    Ban thường vụ tỉnh đoàn , uỷ ban hội liên hiệp , thanh niên tỉnh Tiền Giang tổ chức chương trình "hỗ trợ nông dân tiêu thụ nông sản"
                  </p>
                <div class="d-grid gap-2 d-md-flex justify-content-md-end">
                    <button class="btn btn-primary me-md-2" type="button">
                      <a href="https://bitly.com.vn/0nyfvj" class="nav-link px-2 link-dark">Details</a>
                    </button>
                </div>
                </div>
              </div>
            </div>
          </div>
          <div class="card mb-3" style="max-width: 560px;">
            <div class="row g-0">
              <div class="col-md-4">
                <img src="img/4.jpg" class="img-thumbnail" alt="mdo">
              </div>
              <div class="col-md-8">
                <div class="card-body">
                  <h5 class="card-title">
                    BigC và Grab Việt Nam chung tay hỗ trợ nông sản Bắc Giang 
                  </h5>
                  <p class="card-text"><small class="text-muted">11/6/2021</small></p>
                  <p class="card-text">
                    Hưởng ứng lời kêu gọi của Bộ Công thương và Bộ Nông nghiệp và Phát triển nông thôn, Big C Việt Nam và Grab Việt Nam vừa công bố triển khai chương trình Chung tay hỗ trợ nông sản Bắc Giang trên nền tảng GrabMart.
                  </p>
                <div class="d-grid gap-2 d-md-flex justify-content-md-end">
                    <button class="btn btn-primary me-md-2" type="button">
                      <a href="https://bitly.com.vn/0nyfvj" class="nav-link px-2 link-dark">Details</a>
                    </button>
                </div>
                </div>
              </div>
            </div>
          </div>
          <div class="card mb-3" style="max-width: 560px;">
            <div class="row g-0">
              <div class="col-md-4">
                <img src="img/3.jpg" class="img-thumbnail" alt="mdo">
              </div>
              <div class="col-md-8">
                <div class="card-body">
                  <h5 class="card-title">
                    Tỉnh đoàn Tiền Giang hỗ trợ nông dân tiêu thụ nông sản
                  </h5>
                  <p class="card-text"><small class="text-muted">11/6/2021</small></p>
                  <p class="card-text">
                    Ban thường vụ tỉnh đoàn , uỷ ban hội liên hiệp , thanh niên tỉnh Tiền Giang tổ chức chương trình "hỗ trợ nông dân tiêu thụ nông sản"
                  </p>
                <div class="d-grid gap-2 d-md-flex justify-content-md-end">
                    <button class="btn btn-primary me-md-2" type="button">
                      <a href="https://bitly.com.vn/0nyfvj" class="nav-link px-2 link-dark">Details</a>
                    </button>
                </div>
                </div>
              </div>
            </div>
          </div>
          <div class="card mb-3" style="max-width: 560px;">
            <div class="row g-0">
              <div class="col-md-4">
                <img src="img/3.jpg" class="img-thumbnail" alt="mdo">
              </div>
              <div class="col-md-8">
                <div class="card-body">
                  <h5 class="card-title">
                    Tỉnh đoàn Tiền Giang hỗ trợ nông dân tiêu thụ nông sản
                  </h5>
                  <p class="card-text"><small class="text-muted">11/6/2021</small></p>
                  <p class="card-text">
                    Ban thường vụ tỉnh đoàn , uỷ ban hội liên hiệp , thanh niên tỉnh Tiền Giang tổ chức chương trình "hỗ trợ nông dân tiêu thụ nông sản"
                  </p>
                <div class="d-grid gap-2 d-md-flex justify-content-md-end">
                    <button class="btn btn-primary me-md-2" type="button">
                      <a href="https://bitly.com.vn/0nyfvj" class="nav-link px-2 link-dark">Details</a>
                    </button>
                </div>
                </div>
              </div>
            </div>
          </div>
          <div class="card mb-3" style="max-width: 560px;">
            <div class="row g-0">
              <div class="col-md-4">
                <img src="img/3.jpg" class="img-thumbnail" alt="mdo">
              </div>
              <div class="col-md-8">
                <div class="card-body">
                  <h5 class="card-title">
                    Tỉnh đoàn Tiền Giang hỗ trợ nông dân tiêu thụ nông sản
                  </h5>
                  <p class="card-text"><small class="text-muted">11/6/2021</small></p>
                  <p class="card-text">
                    Ban thường vụ tỉnh đoàn , uỷ ban hội liên hiệp , thanh niên tỉnh Tiền Giang tổ chức chương trình "hỗ trợ nông dân tiêu thụ nông sản"
                  </p>
                <div class="d-grid gap-2 d-md-flex justify-content-md-end">
                    <button class="btn btn-primary me-md-2" type="button">
                      <a href="https://bitly.com.vn/0nyfvj" class="nav-link px-2 link-dark">Details</a>
                    </button>
                </div>
                </div>
              </div>
            </div>
          </div>
          <div class="card mb-3" style="max-width: 560px;">
            <div class="row g-0">
              <div class="col-md-4">
                <img src="img/3.jpg" class="img-thumbnail" alt="mdo">
              </div>
              <div class="col-md-8">
                <div class="card-body">
                  <h5 class="card-title">
                    Tỉnh đoàn Tiền Giang hỗ trợ nông dân tiêu thụ nông sản
                  </h5>
                  <p class="card-text"><small class="text-muted">11/6/2021</small></p>
                  <p class="card-text">
                    Ban thường vụ tỉnh đoàn , uỷ ban hội liên hiệp , thanh niên tỉnh Tiền Giang tổ chức chương trình "hỗ trợ nông dân tiêu thụ nông sản"
                  </p>
                <div class="d-grid gap-2 d-md-flex justify-content-md-end">
                    <button class="btn btn-primary me-md-2" type="button">
                      <a href="https://bitly.com.vn/0nyfvj" class="nav-link px-2 link-dark">Details</a>
                    </button>
                </div>
                </div>
              </div>
            </div>
          </div>
          <div class="card mb-3" style="max-width: 560px;">
            <div class="row g-0">
              <div class="col-md-4">
                <img src="img/3.jpg" class="img-thumbnail" alt="mdo">
              </div>
              <div class="col-md-8">
                <div class="card-body">
                  <h5 class="card-title">
                    Tỉnh đoàn Tiền Giang hỗ trợ nông dân tiêu thụ nông sản
                  </h5>
                  <p class="card-text"><small class="text-muted">11/6/2021</small></p>
                  <p class="card-text">
                    Ban thường vụ tỉnh đoàn , uỷ ban hội liên hiệp , thanh niên tỉnh Tiền Giang tổ chức chương trình "hỗ trợ nông dân tiêu thụ nông sản"
                  </p>
                <div class="d-grid gap-2 d-md-flex justify-content-md-end">
                    <button class="btn btn-primary me-md-2" type="button">
                      <a href="https://bitly.com.vn/0nyfvj" class="nav-link px-2 link-dark">Details</a>
                    </button>
                </div>
                </div>
              </div>
            </div>
          </div>
          
        </table>
        <nav aria-label="..."><!--Chọn trang-->
          <ul class="pagination justify-content-center">
            <li class="page-item disabled">
              <a class="page-link" href="#" tabindex="-1" aria-disabled="true">Previous</a>
            </li>
            <li class="page-item active"><a class="page-link" href="index.html">1</a>
            </li>
            <li class="page-item " aria-current="page">
              <a class="page-link" href="page2.html">2</a>
            </li>
            <li class="page-item"><a class="page-link" href="#">3</a></li>
            <li class="page-item">
              <a class="page-link" href="#">Next</a>
            </li>
          </ul>
        </nav>
        <div class="card-body"> <!--Bài viết có nhiều lượt xem nhất-->
           <h5 class="card-title">
             Bài viết nổi bật
           </h5>
         </div>
           <div class="card mb-3" style="max-width: 560px;">
             <div class="row g-0">
               <div class="col-md-4">
                 <img src="img/R3fb441f915b7db9d519dedd4c3261cfb.jpg" class="img-thumbnail" alt="mdo">
               </div>
               <div class="col-md-8">
                 <div class="card-body">
                   <h5 class="card-title">
                     Thị trường nông lâm thuỷ sản
                   </h5>
                   <p class="card-text"><small class="text-muted">10/12/2020</small></p>
                   <p class="card-text">
                     Cục suất nhập khẩu , bộ công thương xin giới thiệu tới bạn đọc bản tin về thị trường nông lâm thuỷ sản 
                   </p>
                 <div class="d-grid gap-2 d-md-flex justify-content-md-end">
                     <button class="btn btn-primary me-md-2" type="button">
                       <a href="https://bitly.com.vn/0nyfvj" class="nav-link px-2 link-dark">Details</a>
                     </button>
                 </div>
                 </div>
               </div>
             </div>
           </div>
           <div class="card mb-3" style="max-width: 560px;">
             <div class="row g-0">
               <div class="col-md-4">
                 <img src="img/3.jpg" class="img-thumbnail" alt="mdo">
               </div>
               <div class="col-md-8">
                 <div class="card-body">
                   <h5 class="card-title">
                     Tỉnh đoàn Tiền Giang hỗ trợ nông dân tiêu thụ nông sản
                   </h5>
                   <p class="card-text"><small class="text-muted">11/6/2021</small></p>
                   <p class="card-text">
                     Ban thường vụ tỉnh đoàn , uỷ ban hội liên hiệp , thanh niên tỉnh Tiền Giang tổ chức chương trình "hỗ trợ nông dân tiêu thụ nông sản"
                   </p>
                 <div class="d-grid gap-2 d-md-flex justify-content-md-end">
                     <button class="btn btn-primary me-md-2" type="button">
                       <a href="https://bitly.com.vn/0nyfvj" class="nav-link px-2 link-dark">Details</a>
                     </button>
                 </div>
                 </div>
               </div>
             </div>
           </div>
           <div class="card mb-3" style="max-width: 560px;">
             <div class="row g-0">
               <div class="col-md-4">
                 <img src="img/4.jpg" class="img-thumbnail" alt="mdo">
               </div>
               <div class="col-md-8">
                 <div class="card-body">
                   <h5 class="card-title">
                     BigC và Grab Việt Nam chung tay hỗ trợ nông sản Bắc Giang 
                   </h5>
                   <p class="card-text"><small class="text-muted">11/6/2021</small></p>
                   <p class="card-text">
                     Hưởng ứng lời kêu gọi của Bộ Công thương và Bộ Nông nghiệp và Phát triển nông thôn, Big C Việt Nam và Grab Việt Nam vừa công bố triển khai chương trình Chung tay hỗ trợ nông sản Bắc Giang trên nền tảng GrabMart.
                   </p>
                   <div class="d-grid gap-2 d-md-flex justify-content-md-end">
                     <button class="btn btn-primary me-md-2" type="button">
                       <a href="https://bitly.com.vn/0nyfvj" class="nav-link px-2 link-dark">Details</a>
                     </button>
                   </div>
                 </div>
 
               </div>
             </div>
           
           </div>
           <div class="card mb-3" style="max-width: 560px;">
            <div class="row g-0">
              <div class="col-md-4">
                <img src="img/3.jpg" class="img-thumbnail" alt="mdo">
              </div>
              <div class="col-md-8">
                <div class="card-body">
                  <h5 class="card-title">
                    Tỉnh đoàn Tiền Giang hỗ trợ nông dân tiêu thụ nông sản
                  </h5>
                  <p class="card-text"><small class="text-muted">11/6/2021</small></p>
                  <p class="card-text">
                    Ban thường vụ tỉnh đoàn , uỷ ban hội liên hiệp , thanh niên tỉnh Tiền Giang tổ chức chương trình "hỗ trợ nông dân tiêu thụ nông sản"
                  </p>
                <div class="d-grid gap-2 d-md-flex justify-content-md-end">
                    <button class="btn btn-primary me-md-2" type="button">
                      <a href="https://bitly.com.vn/0nyfvj" class="nav-link px-2 link-dark">Details</a>
                    </button>
                </div>
                </div>
              </div>
            </div>
          </div>           
          <div class="card mb-3" style="max-width: 560px;">
            <div class="row g-0">
              <div class="col-md-4">
                <img src="img/3.jpg" class="img-thumbnail" alt="mdo">
              </div>
              <div class="col-md-8">
                <div class="card-body">
                  <h5 class="card-title">
                    Tỉnh đoàn Tiền Giang hỗ trợ nông dân tiêu thụ nông sản
                  </h5>
                  <p class="card-text"><small class="text-muted">11/6/2021</small></p>
                  <p class="card-text">
                    Ban thường vụ tỉnh đoàn , uỷ ban hội liên hiệp , thanh niên tỉnh Tiền Giang tổ chức chương trình "hỗ trợ nông dân tiêu thụ nông sản"
                  </p>
                <div class="d-grid gap-2 d-md-flex justify-content-md-end">
                    <button class="btn btn-primary me-md-2" type="button">
                      <a href="https://bitly.com.vn/0nyfvj" class="nav-link px-2 link-dark">Details</a>
                    </button>
                </div>
                </div>
              </div>
            </div>
          </div>           
          <div class="card mb-3" style="max-width: 560px;">
            <div class="row g-0">
              <div class="col-md-4">
                <img src="img/3.jpg" class="img-thumbnail" alt="mdo">
              </div>
              <div class="col-md-8">
                <div class="card-body">
                  <h5 class="card-title">
                    Tỉnh đoàn Tiền Giang hỗ trợ nông dân tiêu thụ nông sản
                  </h5>
                  <p class="card-text"><small class="text-muted">11/6/2021</small></p>
                  <p class="card-text">
                    Ban thường vụ tỉnh đoàn , uỷ ban hội liên hiệp , thanh niên tỉnh Tiền Giang tổ chức chương trình "hỗ trợ nông dân tiêu thụ nông sản"
                  </p>
                <div class="d-grid gap-2 d-md-flex justify-content-md-end">
                    <button class="btn btn-primary me-md-2" type="button">
                      <a href="https://bitly.com.vn/0nyfvj" class="nav-link px-2 link-dark">Details</a>
                    </button>
                </div>
                </div>
              </div>
            </div>
          </div>           
          <div class="card mb-3" style="max-width: 560px;">
            <div class="row g-0">
              <div class="col-md-4">
                <img src="img/3.jpg" class="img-thumbnail" alt="mdo">
              </div>
              <div class="col-md-8">
                <div class="card-body">
                  <h5 class="card-title">
                    Tỉnh đoàn Tiền Giang hỗ trợ nông dân tiêu thụ nông sản
                  </h5>
                  <p class="card-text"><small class="text-muted">11/6/2021</small></p>
                  <p class="card-text">
                    Ban thường vụ tỉnh đoàn , uỷ ban hội liên hiệp , thanh niên tỉnh Tiền Giang tổ chức chương trình "hỗ trợ nông dân tiêu thụ nông sản"
                  </p>
                <div class="d-grid gap-2 d-md-flex justify-content-md-end">
                    <button class="btn btn-primary me-md-2" type="button">
                      <a href="https://bitly.com.vn/0nyfvj" class="nav-link px-2 link-dark">Details</a>
                    </button>
                </div>
                </div>
              </div>
            </div>
          </div>
          <div class="card mb-3" style="max-width: 560px;">
            <div class="row g-0">
              <div class="col-md-4">
                <img src="img/3.jpg" class="img-thumbnail" alt="mdo">
              </div>
              <div class="col-md-8">
                <div class="card-body">
                  <h5 class="card-title">
                    Tỉnh đoàn Tiền Giang hỗ trợ nông dân tiêu thụ nông sản
                  </h5>
                  <p class="card-text"><small class="text-muted">11/6/2021</small></p>
                  <p class="card-text">
                    Ban thường vụ tỉnh đoàn , uỷ ban hội liên hiệp , thanh niên tỉnh Tiền Giang tổ chức chương trình "hỗ trợ nông dân tiêu thụ nông sản"
                  </p>
                <div class="d-grid gap-2 d-md-flex justify-content-md-end">
                    <button class="btn btn-primary me-md-2" type="button">
                      <a href="https://bitly.com.vn/0nyfvj" class="nav-link px-2 link-dark">Details</a>
                    </button>
                </div>
                </div>
              </div>
            </div>
          </div>
          <div class="card mb-3" style="max-width: 560px;">
            <div class="row g-0">
              <div class="col-md-4">
                <img src="img/3.jpg" class="img-thumbnail" alt="mdo">
              </div>
              <div class="col-md-8">
                <div class="card-body">
                  <h5 class="card-title">
                    Tỉnh đoàn Tiền Giang hỗ trợ nông dân tiêu thụ nông sản
                  </h5>
                  <p class="card-text"><small class="text-muted">11/6/2021</small></p>
                  <p class="card-text">
                    Ban thường vụ tỉnh đoàn , uỷ ban hội liên hiệp , thanh niên tỉnh Tiền Giang tổ chức chương trình "hỗ trợ nông dân tiêu thụ nông sản"
                  </p>
                <div class="d-grid gap-2 d-md-flex justify-content-md-end">
                    <button class="btn btn-primary me-md-2" type="button">
                      <a href="https://bitly.com.vn/0nyfvj" class="nav-link px-2 link-dark">Details</a>
                    </button>
                </div>
                </div>
              </div>
            </div>
          </div>
          <div class="card mb-3" style="max-width: 560px;">
            <div class="row g-0">
              <div class="col-md-4">
                <img src="img/3.jpg" class="img-thumbnail" alt="mdo">
              </div>
              <div class="col-md-8">
                <div class="card-body">
                  <h5 class="card-title">
                    Tỉnh đoàn Tiền Giang hỗ trợ nông dân tiêu thụ nông sản
                  </h5>
                  <p class="card-text"><small class="text-muted">11/6/2021</small></p>
                  <p class="card-text">
                    Ban thường vụ tỉnh đoàn , uỷ ban hội liên hiệp , thanh niên tỉnh Tiền Giang tổ chức chương trình "hỗ trợ nông dân tiêu thụ nông sản"
                  </p>
                <div class="d-grid gap-2 d-md-flex justify-content-md-end">
                    <button class="btn btn-primary me-md-2" type="button">
                      <a href="https://bitly.com.vn/0nyfvj" class="nav-link px-2 link-dark">Details</a>
                    </button>
                </div>
                </div>
              </div>
            </div>
          </div>
         </table>
         <nav aria-label="..."><!--Chọn trang-->
           <ul class="pagination justify-content-center">
             <li class="page-item disabled">
               <a class="page-link" href="#" tabindex="-1" aria-disabled="true">Previous</a>
             </li>
             <li class="page-item active"><a class="page-link" href="index.html">1</a>
             </li>
             <li class="page-item " aria-current="page">
               <a class="page-link" href="page2.html">2</a>
             </li>
             <li class="page-item"><a class="page-link" href="#">3</a></li>
             <li class="page-item">
               <a class="page-link" href="#">Next</a>
             </li>
           </ul>
         </nav>
      </div>

       <div class="col-4"> <!----Bài viết mới nhất-->
         <h5 class="card-title">
           Bài viết mới nhất
         </h5>
        <div class="card mb-3">
          <img src="img/5.jpg" class="card-img-top img-thumbnail" alt="mdo">
          <div class="card-body">
            <h5 class="card-title">
              Kết nối yêu thương tiêu thụ nông sản
            </h5>
            <p class="card-text">
              <small class="text-muted">
                11/06/2021
              </small>
             <p class="card-text">
               Các sản phẩm tiêu thụ đảm bảo sản xuất sạch, an toàn theo tiêu chuẩn VietGAP, có nguồn gốc, xuất xứ rõ ràng, quá trình thu hoạch, đóng gói và vận chuyển được kiểm soát chặt chẽ, đảm bảo thực hiện nghiêm các biện pháp phòng, chống dịch bệnh Covid-19
             </p>
            </p>
            <div class="d-grid gap-2 d-md-flex justify-content-md-end">
              <button class="btn btn-primary me-md-2" type="button">
                <a href="https://bitly.com.vn/0nyfvj" class="nav-link px-2 link-dark">Details</a>
              </button> 
            </div>
          </div>
        </div>
        <div class="card mb-3">
          <img src="img/6.jpg" class="card-img-top img-thumbnail" alt="mdo">
          <div class="card-body">
            <h5 class="card-title">
              Khi nông sản an toàn vào bếp ăn tập thể
            </h5>
            <p class="card-text">
              <small class="text-muted">
                11/06/2021
              </small>
            <p class="card-text">
              Bên cạnh công tác tuyên truyền về lợi ích của việc sản xuất và sử dụng nông sản an toàn, 3 năm qua, Hội Nông dân và Liên đoàn Lao động (LĐLĐ) tỉnh An Giang còn phối hợp đưa nông sản sạch vào các bếp ăn tập thể của doanh nghiệp (DN), trường học.
            </p>
            </p>
            <div class="d-grid gap-2 d-md-flex justify-content-md-end">
              <button class="btn btn-primary me-md-2" type="button">
                <a href="https://bitly.com.vn/0nyfvj" class="nav-link px-2 link-dark">Details</a>
              </button> 
            </div>
          </div>
        </div>
        <div class="card mb-3">
          <img src="img/7.jpeg" class="card-img-top img-thumbnail" alt="mdo">
          <div class="card-body">
            <h5 class="card-title">
              Kinh doanh thu mua nông sản như thế nào để thành công?
            </h5>
            <p class="card-text">
              <small class="text-muted">
                08/06/2021
              </small>
            <p class="card-text">
              Kinh doanh thu mua nông sản đang là mô hình được nhiều người quan tâm do lợi nhuận lớn mà nó mang lại. Để dễ dàng đạt được thành công, người kinh doanh cần chú ý đảm bảo các nguyên tắc cơ bản trong thu mua nông sản.
            </p>
            </p>
            <div class="d-grid gap-2 d-md-flex justify-content-md-end">
              <button class="btn btn-primary me-md-2" type="button">
                <a href="https://bitly.com.vn/0nyfvj" class="nav-link px-2 link-dark">Details</a>
              </button> 
            </div>
          </div>
        </div>
        <div class="card mb-3">
          <img src="img/7.jpg" class="card-img-top img-thumbnail" alt="mdo">
          <div class="card-body">
            <h5 class="card-title">
              Kinh doanh thu mua nông sản như thế nào để thành công?
            </h5>
            <p class="card-text">
              <small class="text-muted">
                08/06/2021
              </small>
            <p class="card-text">
              Kinh doanh thu mua nông sản đang là mô hình được nhiều người quan tâm do lợi nhuận lớn mà nó mang lại. Để dễ dàng đạt được thành công, người kinh doanh cần chú ý đảm bảo các nguyên tắc cơ bản trong thu mua nông sản.
            </p>
            </p>
            <div class="d-grid gap-2 d-md-flex justify-content-md-end">
              <button class="btn btn-primary me-md-2" type="button">
                <a href="https://bitly.com.vn/0nyfvj" class="nav-link px-2 link-dark">Details</a>
              </button> 
            </div>
          </div>
        </div>
        <div class="card mb-3">
          <img src="img/9.jpg" class="card-img-top img-thumbnail" alt="mdo">
          <div class="card-body">
            <h5 class="card-title">
              Kết nối yêu thương tiêu thụ nông sản
            </h5>
            <p class="card-text">
              <small class="text-muted">
                11/06/2021
              </small>
            <p class="card-text">
              Các sản phẩm tiêu thụ đảm bảo sản xuất sạch, an toàn theo tiêu chuẩn VietGAP, có nguồn gốc, xuất xứ rõ ràng, quá trình thu hoạch, đóng gói và vận chuyển được kiểm soát chặt chẽ, đảm bảo thực hiện nghiêm các biện pháp phòng, chống dịch bệnh Covid-19
            </p>
            </p>
            <div class="d-grid gap-2 d-md-flex justify-content-md-end">
              <button class="btn btn-primary me-md-2" type="button">
                <a href="https://bitly.com.vn/0nyfvj" class="nav-link px-2 link-dark">Details</a>
              </button> 
            </div>
          </div>
        </div>
      </div>

   
    </div>
  </div>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.1/dist/js/bootstrap.bundle.min.js" integrity="sha384-gtEjrD/SeCtmISkJkNUaaKMoLD0//ElJ19smozuHV6z3Iehds+3Ulb9Bn9Plx0x4" crossorigin="anonymous"></script>
</body>
</html>
