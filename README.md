
<nav class="navbar navbar-expand-lg navbar-light bg-dark"  style="background-color: #e3f2fd;">
  <a class="navbar-brand ml-4" href="#"><span style="color:white;">Navbar</span></a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>

  <div class="collapse navbar-collapse" id="navbarSupportedContent">
    <ul class="navbar-nav mr-auto">
      <li class="nav-item active ml-4">
        <a class="nav-link" href="#"><span style="color:white;">Home</span> <span class="sr-only">(current)</span></a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#"><span style="color:white">Link</span></a>
      </li>
      	<li class="nav-item dropdown" dropdown>
					<a class="nav-link dropdown-toggle" href (click)="false" id="navbarDropdown" role="button" aria-controls="navbarDropdown" dropdownToggle>
					<span style="color:white;">	Dropdown</span> <span class="caret"></span>
					</a>
					<ul class="dropdown-menu" aria-labelledby="navbarDropdown" *dropdownMenu role="menu" aria-labelledby="navbarDropdown">
						<li>
							<a class="dropdown-item" href="#">Action</a>
						</li>
						<li>
							<a class="dropdown-item" href="#">Another action</a>
						</li>
					</ul>
				</li>
      
    </ul>
    <form class="form-inline my-2 my-lg-0">
      <input class="form-control mr-sm-2" type="search" placeholder="Search" aria-label="Search">
      <button class="btn btn-outline-success my-2 my-sm-0" type="submit">Search</button>
    </form>
  </div>
</nav>
<div class="card-body">
        <div class="col-md-12">
            <div class="row justify-content-center">
                <div class="col-8">
<a class="row justify-content-center">User Registration Form</a>
<form style="background-color:powderblue;">
  
  <div class="form-row">
    <div class="form-group col-md-6">
      <label for="inputEmail4">Email</label>
      <input type="email" class="form-control" id="inputEmail4" placeholder="Email">
    </div>
    <div class="form-group col-md-6">
      <label for="inputPassword4">Password</label>
      <input type="password" class="form-control" id="inputPassword4" placeholder="Password">
    </div>
  </div>
  <div class="form-group">
    <label for="inputAddress">Address</label>
    <input type="text" class="form-control" id="inputAddress" placeholder="1234 Main St">
  </div>
  <div class="form-group">
    <label for="inputAddress2">Address 2</label>
    <input type="text" class="form-control" id="inputAddress2" placeholder="Apartment, studio, or floor">
  </div>
  <div class="form-row">
    <div class="form-group col-md-6">
      <label for="inputCity">City</label>
      <input type="text" class="form-control" id="inputCity">
    </div>
    <div class="form-group col-md-4">
      <label for="inputState">State</label>
      <select id="inputState" class="form-control">
        <option selected>Choose...</option>
        <option>...</option>
      </select>
    </div>
    <div class="form-group col-md-2">
      <label for="inputZip">Zip</label>
      <input type="text" class="form-control" id="inputZip">
    </div>
  </div>
  <div class="form-group">
    <div class="form-check">
      <input class="form-check-input" type="checkbox" id="gridCheck">
      <label class="form-check-label" for="gridCheck">
        Check me out
      </label>
    </div>
  </div>
  <div class="row justify-content-center" >
  <button  type="submit" class="btn btn-primary">Sign in</button>
  </div>
</form>
                </div>
            </div>
        </div>
