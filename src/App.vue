<template>
  <div id="app" >
<!--    Header Section Section....-->
    <div class="container">
      <nav class="navbar navbar-expand-lg navbar-light bg-white">

        <a class="navbar-brand" href="#">Navbar</a>

        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent"
                aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse">
          <ul class="navbar-nav" id="menu-header">

            <li class="nav-item active">
              <a class="nav-link" href="#">Dashboard <span class="sr-only">(current)</span></a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Orders</a>
            </li>

            <li class="nav-item">
              <a class="nav-link" href="#">Customers</a>
            </li>

            <li class="nav-item">
              <a class="nav-link" href="#">Inventory</a>
            </li>

            <li class="nav-item">
              <a class="nav-link" href="#">Setting</a>
            </li>

          </ul>


          <form class="form-inline my-2 my-lg-0">
            <ul class="navbar-nav">
              <li class="nav-item dropdown border-bottom">
                <i class="fas fa-bell mr-4 d-inline pointer-event"></i>
                <a class="nav-link dropdown-toggle d-inline" href="#" id="navbarDropdown" role="button" data-toggle="dropdown"
                   aria-haspopup="true" aria-expanded="false">

                  <img src="./assets/image/najmun.jpg" class="rounded-circle" height="30" width="30">
                </a>
                <div class="dropdown-menu" aria-labelledby="navbarDropdown">
                  <a class="dropdown-item" href="#">Najmun Nafiz</a>
                  <a class="dropdown-item" href="#">Change-Password</a>
                  <div class="dropdown-divider"></div>
                  <a class="dropdown-item" href="#">Change-Profile</a>
                </div>
              </li>
            </ul>
          </form>

        </div>

      </nav>

<!--      Order Create Section...-->
      <div class="order-create mt-5 mb-5">
        <h4 class="card-title float-left">Order List</h4>
        <div class="btn-crate float-right">
          <h3 class="d-inline mr-3">...</h3>
          <a href="#" class="btn btn-primary d-inline">Craete</a>
        </div>
      </div>

        <div class="chart mt-5">
            <div class="row">
                <div class="col-md-3">
                    <img src="./assets/image/chart.jpg" class="rounded" height="200" width="100%">
                </div>

                <div class="col-md-3">
                    <img src="./assets/image/chart2.jpg" class="rounded" height="200" width="100%">
                </div>

                <div class="col-md-3">
                    <img src="./assets/image/chart3.jpg" class="rounded" height="200" width="100%">
                </div>

                <div class="col-md-3">
                    <img src="./assets/image/chart4.jpg" class="rounded" height="200" width="100%">
                </div>
            </div>
        </div>



<!--      Table Header Section Start From Here...-->
        <div class="table-header mt-5">
            <div class="table-menu text-left">
                <ul class="navbar-nav">
                    <li class="nav-item">
                        <a class="nav-link" href="#">All Orders</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Active</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Unpaid</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Unfuldiled</a>
                    </li>
                </ul>
            </div>
            <div class="search-icon text-right">
                <i class="fas fa-search"></i>
            </div>
        </div>


<!--      Table Body Section Start From Here...-->
          <div class="order-table mt-3">
              <table class="table table-striped">
                  <thead>
                  <tr>
                      <th scope="col"><input type="checkbox" class="mr-3"> Order Id</th>
                      <th scope="col">Created</th>
                      <th scope="col">Customer</th>
                      <th scope="col">FullName</th>
                      <th scope="col">Total</th>
                      <th scope="col">Profit</th>
                      <th scope="col">Status</th>
                      <th scope="col">Updated</th>
                  </tr>
                  </thead>
                  <tbody>

                  <tr class="bg-white table-border">
                      <th scope="row" id="order-id"><input type="checkbox" class="mr-3"> 101</th>
                      <td>Aug 1, 2020</td>
                      <td>
                          <img src="./assets/image/img-2.jpg" class="rounded-circle" height="30" width="30">
                          <p class="float-right">Sumaya Akhter</p>
                      </td>
                      <td>
                          <div class="btn-group">
                              <button type="button" class="btn btn-warning dropdown-toggle" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                                  Undefined
                              </button>
                              <div class="dropdown-menu">
                                  <a class="dropdown-item" href="#">Action</a>
                                  <a class="dropdown-item" href="#">Another action</a>
                              </div>
                          </div>
                      </td>
                      <td>$100.90</td>
                      <td>$40.70</td>
                      <td>
                          <div class="btn-group">
                              <button type="button" class="btn btn-secondary dropdown-toggle" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                                  Authorized
                              </button>
                              <div class="dropdown-menu">
                                  <a class="dropdown-item" href="#">Action</a>
                                  <a class="dropdown-item" href="#">Another action</a>
                              </div>
                          </div>
                      </td>
                      <td>Today</td>
                  </tr>

                  <tr class="bg-white">
                      <th scope="row" id="order-id"><input type="checkbox" class="mr-3"> 102</th>
                      <td>Aug 2, 2020</td>
                      <td>
                          <img src="./assets/image/img-1.jpg" class="rounded-circle" height="30" width="30">
                          <p class="float-right">Anamul Islam</p>
                      </td>
                      <td>
                          <div class="btn-group">
                              <button type="button" class="btn btn-danger dropdown-toggle" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                                  PendingProject
                              </button>
                              <div class="dropdown-menu">
                                  <a class="dropdown-item" href="#">Action</a>
                                  <a class="dropdown-item" href="#">Another action</a>
                                  <a class="dropdown-item" href="#">Something else here</a>
                              </div>
                          </div>
                      </td>
                      <td>$676.34</td>
                      <td>$200.23</td>
                      <td>
                          <div class="btn-group">
                              <button type="button" class="btn btn-success dropdown-toggle" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                                  Paid
                              </button>
                              <div class="dropdown-menu">
                                  <a class="dropdown-item" href="#">Action</a>
                                  <a class="dropdown-item" href="#">Another action</a>
                                  <a class="dropdown-item" href="#">Something else here</a>
                              </div>
                          </div>
                      </td>
                      <td>Yesterday</td>
                  </tr>

                  <tr class="bg-white table-border">
                      <th scope="row" id="order-id"><input type="checkbox" class="mr-3"> 103</th>
                      <td>Aug 1, 2020</td>
                      <td>
                          <img src="./assets/image/img-3.jpg" class="rounded-circle" height="30" width="30">
                          <p class="float-right">Safiur Rahman</p>
                      </td>
                      <td>
                          <div class="btn-group">
                              <button type="button" class="btn btn-primary dropdown-toggle" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                                  Undefined
                              </button>
                              <div class="dropdown-menu">
                                  <a class="dropdown-item" href="#">Action</a>
                                  <a class="dropdown-item" href="#">Another action</a>
                              </div>
                          </div>
                      </td>
                      <td>$100.90</td>
                      <td>$40.70</td>
                      <td>
                          <div class="btn-group">
                              <button type="button" class="btn btn-warning dropdown-toggle" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                                  Authorized
                              </button>
                              <div class="dropdown-menu">
                                  <a class="dropdown-item" href="#">Action</a>
                                  <a class="dropdown-item" href="#">Another action</a>
                              </div>
                          </div>
                      </td>
                      <td>Today</td>
                  </tr>

                  <tr class="bg-white table-border">
                      <th scope="row" id="order-id"><input type="checkbox" class="mr-3"> 101</th>
                      <td>Aug 1, 2020</td>
                      <td>
                          <img src="./assets/image/img-2.jpg" class="rounded-circle" height="30" width="30">
                          <p class="float-right">Sumaya Akhter</p>
                      </td>
                      <td>
                          <div class="btn-group">
                              <button type="button" class="btn btn-warning dropdown-toggle" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                                  Undefined
                              </button>
                              <div class="dropdown-menu">
                                  <a class="dropdown-item" href="#">Action</a>
                                  <a class="dropdown-item" href="#">Another action</a>
                              </div>
                          </div>
                      </td>
                      <td>$100.90</td>
                      <td>$40.70</td>
                      <td>
                          <div class="btn-group">
                              <button type="button" class="btn btn-danger dropdown-toggle" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                                  Authorized
                              </button>
                              <div class="dropdown-menu">
                                  <a class="dropdown-item" href="#">Action</a>
                                  <a class="dropdown-item" href="#">Another action</a>
                              </div>
                          </div>
                      </td>
                      <td>Today</td>
                  </tr>

                  </tbody>
              </table>
          </div>

      </div>
  </div>
</template>

<script>


export default {
  name: 'App',
  components: {

  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;

}
</style>
