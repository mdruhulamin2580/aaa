<!doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">
    <!-- custom css -->
    <link rel="stylesheet" href="style.css">
    <title>Hello, world!</title>
</head>
<body>
    <!-- navbar -->
    <div class="container-fluid">
      <div class="row">
          <div class="col-md-12">
              <nav class="navbar navbar-expand-lg navbar-light heads ">
                  <div class="container-fluid wwww">
                    <a class="navbar-brand" href="#">
                        <img src="https://i.ibb.co/YpCwBCq/92-925298-blue-atom-transparent-background-uc-leads-clipart-removebg-preview.png" alt="">
                    </a>
                    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                      <span class="navbar-toggler-icon"></span>
                    </button>
                    <div class="collapse navbar-collapse" id="navbarSupportedContent">
                      <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                        <li class="nav-item">
                          <a class="nav-link active" aria-current="page" href="#">Home</a>
                        </li>
                        <li class="nav-item">
                          <a class="nav-link" href="#">Blog</a>
                        </li>
                        <li class="nav-item">
                          <a class="nav-link" href="#">Portfolio</a>
                        </li>
                        <li class="nav-item">
                          <a class="nav-link" href="#">My Resume</a>
                        </li>
                        <li class="nav-item">
                          <a class="nav-link" href="#">Contact</a>
                        </li>
                        
                      </ul>
                      <form class="d-flex">
                        <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
                        <button class="btn btn-outline-success" type="submit">Search</button>
                      </form>
                    </div>
                  </div>
                </nav>
          </div>
      </div>
  </div>
  <!-- breadcrumb-section -->
  <div class="container mt-4">
      <div class="row">
          <div class="col-md-7">
              <nav aria-label="breadcrumb">
                  <ol class="breadcrumb mt-3 bg-light">
                    <li class="breadcrumb-item active" aria-current="page">Home</li>
                  </ol>
                </nav>
                
                <nav aria-label="breadcrumb">
                  <ol class="breadcrumb bg-light">
                    <li class="breadcrumb-item"><a href="#">Home</a></li>
                    <li class="breadcrumb-item active" aria-current="page">Library</li>
                  </ol>
                </nav>
          </div>
          <div class="col-md-5">
              <!-- Note: A custom script is used to activate toasts:

            var toastElList = [].slice.call(document.querySelectorAll('.toast'))
            var toastList = toastElList.map(function (toastEl) {
              return new bootstrap.Toast(toastEl, {
                autohide: false
              }).show()
            })
            -->
            <div class="toast toast-demo fade show" role="alert" aria-live="assertive" aria-atomic="true">
              <div class="toast-header">
                <strong class="me-auto">Bootstrap</strong>
                <small>11 mins ago</small>
                <button type="button" class="btn-close" data-bs-dismiss="toast" aria-label="Close"></button>
              </div>
              <div class="toast-body">
                Hello, world! This is a toast message.
              </div>
            </div>
          </div>
      </div>
  </div>
  <!-- carousel-section -->
  <div class="container-fluid mt-4">
      <div class="row">
          <div class="col-md-12">
              <div id="carouselExampleIndicators" class="carousel slide" data-bs-ride="carousel">
                  <div class="carousel-indicators">
                    <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
                    <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1" aria-label="Slide 2"></button>
                    <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2" aria-label="Slide 3"></button>
                  </div>
                  <div class="carousel-inner">
                    <div class="carousel-item active">
                      <img src="https://i.ibb.co/synfwJ7/workplace-with-smartphone-laptop-black-table-top-view-copyspace-background-144627-24860.jpg" class="d-block w-100" alt="...">
                      <div class="carousel-caption d-none d-md-block">
                          <h5>First slide label</h5>
                          <p>Lorem ipsum dolor sit amet.</p>
                      </div>
                    </div>
                    <div class="carousel-item">
                      <img src="https://i.ibb.co/synfwJ7/workplace-with-smartphone-laptop-black-table-top-view-copyspace-background-144627-24860.jpg" class="d-block w-100" alt="...">
                      <div class="carousel-caption d-none d-md-block">
                          <h5>First slide label</h5>
                          <p>Lorem ipsum dolor sit amet.</p>
                      </div>
                    </div>
                    <div class="carousel-item">
                      <img src="https://i.ibb.co/synfwJ7/workplace-with-smartphone-laptop-black-table-top-view-copyspace-background-144627-24860.jpg" class="d-block w-100" alt="...">
                      <div class="carousel-caption d-none d-md-block">
                          <h5>First slide label</h5>
                          <p>Lorem ipsum dolor sit amet.</p>
                      </div>

                    </div>
                  </div>
                  <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="prev">
                    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                    <span class="visually-hidden">Previous</span>
                  </button>
                  <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="next">
                    <span class="carousel-control-next-icon" aria-hidden="true"></span>
                    <span class="visually-hidden">Next</span>
                  </button>
                </div>
          </div>
      </div>
  </div>
  <!-- alart-section -->
  <div class="container">
      <div class="row">
          <div class="col-md-12">
              <div class="alert alert-info alert-dismissible fade show mt-3" role="alert">
                  <strong>Well done!</strong> <br> You sucesfully read this important alart massage.
                  <button type="button" class="btn-close" data-bs-dismiss="alert" aria-label="Close"></button>
                </div>
          </div>
      </div>
  </div>
  <!-- progress-section -->
  <div class="container">
      <div class="row">
          <div class="col-md-6">
              <div class="progress mt-3">
                  <div class="progress-bar progress-bar-striped" role="progressbar" style="width: 10%" aria-valuenow="10" aria-valuemin="0" aria-valuemax="100"></div>
                </div>
                <div class="progress mt-3">
                  <div class="progress-bar progress-bar-striped bg-success" role="progressbar" style="width: 25%" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100"></div>
                </div>
                <div class="progress mt-3">
                  <div class="progress-bar progress-bar-striped bg-info" role="progressbar" style="width: 50%" aria-valuenow="50" aria-valuemin="0" aria-valuemax="100"></div>
                </div>
                <div class="progress mt-3">
                  <div class="progress-bar progress-bar-striped bg-warning" role="progressbar" style="width: 75%" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100"></div>
                </div>
                <div class="progress mt-3">
                  <div class="progress-bar progress-bar-striped bg-danger" role="progressbar" style="width: 100%" aria-valuenow="100" aria-valuemin="0" aria-valuemax="100"></div>
                </div>
          </div>
          <div class="col-md-6">
              <div class="accordion accordion-flush" id="accordionFlushExample">
                  <div class="accordion-item">
                    <h2 class="accordion-header" id="flush-headingOne">
                      <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#flush-collapseOne" aria-expanded="false" aria-controls="flush-collapseOne">
                        <div class="text-primary">
                          <strong>Colallapsible group item #1</strong>
                        </div>
                      </button>
                    </h2>
                    <div id="flush-collapseOne" class="accordion-collapse collapse" aria-labelledby="flush-headingOne" data-bs-parent="#accordionFlushExample">
                      <div class="accordion-body">Placeholder content for this accordion, which is intended to demonstrate the <code>.accordion-flush</code> class. This is the first item's accordion body.</div>
                    </div>
                  </div>
                  <div class="accordion-item">
                    <h2 class="accordion-header" id="flush-headingTwo">
                      <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#flush-collapseTwo" aria-expanded="false" aria-controls="flush-collapseTwo">
                          <div class="text-primary">
                              <strong>Colallapsible group item #2</strong>
                            </div>
                      </button>
                    </h2>
                    <div id="flush-collapseTwo" class="accordion-collapse collapse" aria-labelledby="flush-headingTwo" data-bs-parent="#accordionFlushExample">
                      <div class="accordion-body">Placeholder content for this accordion, which is intended to demonstrate the <code>.accordion-flush</code> class. This is the second item's accordion body. Let's imagine this being filled with some actual content.</div>
                    </div>
                  </div>
                  <div class="accordion-item">
                    <h2 class="accordion-header" id="flush-headingThree">
                      <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#flush-collapseThree" aria-expanded="false" aria-controls="flush-collapseThree">
                          <div class="text-primary">
                              <strong>Colallapsible group item #3</strong>
                            </div>
                      </button>
                    </h2>
                    <div id="flush-collapseThree" class="accordion-collapse collapse" aria-labelledby="flush-headingThree" data-bs-parent="#accordionFlushExample">
                      <div class="accordion-body">Placeholder content for this accordion, which is intended to demonstrate the <code>.accordion-flush</code> class. This is the third item's accordion body. Nothing more exciting happening here in terms of content, but just filling up the space to make it look, at least at first glance, a bit more representative of how this would look in a real-world application.</div>
                    </div>
                  </div>
                </div>
          </div>
      </div>
  </div>
  <!-- modal-section -->
  <div class="container mt-4">
      <div class="row">
          <div class="col-md-5">
              <!-- Button trigger modal -->
<button type="button" class="btn btn-primary" data-bs-toggle="modal" data-bs-target="#staticBackdrop">
  Launch static backdrop modal
</button>

<!-- Modal -->
<div class="modal fade" id="staticBackdrop" data-bs-backdrop="static" data-bs-keyboard="false" tabindex="-1" aria-labelledby="staticBackdropLabel" aria-hidden="true">
  <div class="modal-dialog">
    <div class="modal-content">
      <div class="modal-header">
        <h5 class="modal-title" id="staticBackdropLabel">Modal title</h5>
        <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
      </div>
      <div class="modal-body">
       <strong>Hello Sattar</strong>
      </div>
      <div class="modal-footer">
        <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
        <button type="button" class="btn btn-primary">Understood</button>
      </div>
    </div>
  </div>
</div>
          </div>
          <div class="col-md-7">
              <button type="button" class="btn btn-secondary" data-bs-toggle="tooltip" data-bs-placement="top" title="Tooltip on top">
                  Tooltip on top
                </button>
                <button type="button" class="btn btn-secondary" data-bs-toggle="tooltip" data-bs-placement="right" title="Tooltip on right">
                  Tooltip on right
                </button>
                <button type="button" class="btn btn-secondary" data-bs-toggle="tooltip" data-bs-placement="bottom" title="Tooltip on bottom">
                  Tooltip on bottom
                </button>
                <button type="button" class="btn btn-secondary" data-bs-toggle="tooltip" data-bs-placement="left" title="Tooltip on left">
                  Tooltip on left
                </button>
          </div>
      </div>
  </div>
    <!-- scro -->

    <div class="container mt-4">
        <div class="row">
            <div class="col-md-12">
                <!-- Custom css that makes this example work like it does: -->
                <style type="text/css">
                    .scrollspy-example {
                    position: relative;
                    height: 200px;
                    margin-top: .5rem;
                    overflow: auto;
                    }
                </style>
                    <nav id="navbar-scrollspy" class="navbar navbar-light bg-light px-3 mt-4">
                    <a class="navbar-brand" href="#">Project Name</a>
                    <ul class="nav nav-pills">
                        <li class="nav-item">
                        <a class="nav-link" href="#fat">Varse 1</a>
                        </li>
                        <li class="nav-item">
                        <a class="nav-link" href="#mdo">Varse 2</a>
                        </li>
                    </ul>
                    </nav>
                    <div data-bs-spy="scroll" data-bs-target="#navbar-scrollspy" data-bs-offset="0" tabindex="0" class="scrollspy-example">
                    <h4 id="fat">varse 1</h4>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatem corrupti perspiciatis distinctio, officia ipsam debitis animi hic? Iusto autem est accusantium quas recusandae consectetur eligendi at et praesentium placeat dignissimos, quasi ipsum neque explicabo non, maxime nemo reprehenderit corporis doloribus amet ab omnis dolorum, debitis ipsam? Nulla veritatis, fugiat cum possimus minima reiciendis eos exercitationem numquam a officia sunt voluptatibus. Ducimus et porro non necessitatibus quae possimus voluptate libero ratione, iure sint! Aspernatur autem saepe doloribus perferendis eos eaque quo ex. Reiciendis neque quidem odio, beatae, similique eaque iusto voluptatem quae eveniet unde accusamus iure pariatur consequatur distinctio qui error?</p>
                    <h4 id="mdo">Verse 2</h4>
                    <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Quisquam corporis esse fugiat alias, aut libero assumenda saepe neque doloribus ducimus sit pariatur repudiandae sequi sed dolore culpa vero itaque! Iure quos rerum odit, ducimus culpa quidem nisi voluptas possimus accusantium iusto, harum hic vel? Unde illum, odit repellendus impedit magni dolores. Minus sunt laboriosam quisquam eligendi cumque aliquam quas pariatur minima ut ea odio ipsum accusamus amet nostrum, consectetur ullam deleniti esse debitis repellat harum nemo illum saepe. Molestias autem inventore libero nam aliquam molestiae, aliquid temporibus magnam quod iste ut laudantium, adipisci illo enim mollitia cupiditate reiciendis veniam pariatur.</p>
                </div>
            </div>
        </div>
    </div>

<!-- pargenation -->
<div class="container">
    <div class="row">
        <div class="col-md-6">
            <div class="sattar">
                <nav aria-label="..." >
                    <ul class="pagination ">
                        <li class="page-item disabled">
                            <span class="page-link">Previous</span>
                        </li>
                        <li class="page-item"><a class="page-link" href="#">1</a></li>
                        <li class="page-item active" aria-current="page">
                            <span class="page-link">2</span>
                        </li>
                        <li class="page-item"><a class="page-link" href="#">3</a></li>
                        <li class="page-item">
                            <a class="page-link" href="#">Next</a>
                        </li>
                    </ul>
              </nav>
            </div>

        </div>
        <div class="col-md-6">
            <div class="dropdown text-center">
                <button class="btn btn-secondary dropdown-toggle" type="button" id="dropdownMenuButton1" data-bs-toggle="dropdown" aria-expanded="false">
                  Dropdown
                </button>
                <ul class="dropdown-menu" aria-labelledby="dropdownMenuButton1">
                  <li><a class="dropdown-item" href="#">Action</a></li>
                  <li><a class="dropdown-item" href="#">Another action</a></li>
                  <li><a class="dropdown-item" href="#">Something else here</a></li>
                </ul>
              </div>
        </div>
    </div>
</div>
<!-- footer -->

<div class="footer bg-info p-3">
    <p class="text-center h5 text-white">&copy; All right reserved by Sattar</p>
</div>


 <!-- Option 1: Bootstrap Bundle with Popper -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>

    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.10.2/dist/umd/popper.min.js" integrity="sha384-7+zCNj/IqJ95wo16oMtfsKbZ9ccEh31eOz1HGyDuCQ6wgnyJNSYdrPa03rtR1zdB" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.min.js" integrity="sha384-QJHtvGhmr9XOIpI6YVutG+2QOK9T+ZnN4kzFN1RtK3zEFEIsxhlmWl5/YESvpZ13" crossorigin="anonymous"></script>
   <script>
     var tooltipTriggerList = [].slice.call(document.querySelectorAll('[data-bs-toggle="tooltip"]'))
var tooltipList = tooltipTriggerList.map(function (tooltipTriggerEl) {
  return new bootstrap.Tooltip(tooltipTriggerEl)
})
   </script>
  </body>
</html>
