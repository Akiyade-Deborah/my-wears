<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="shortcut icon" href="../images/my wear logo.png" type="image/x-icon">
  <link rel="stylesheet" href="index.css">
  <link rel="stylesheet" href="../assets/fontawesome-free-6.6.0-web/css/all.css">
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap" rel="stylesheet">
  <link href="https://fonts.googleapis.com/css2?family=Josefin+Sans:ital,wght@0,100..700;1,100..700&family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap" rel="stylesheet">
  <link rel="preload" href="../images/129.JPG" as="image">
  <link rel="stylesheet" href="../assets/dist/assets/owl.theme.default.min.css">
 <title>My Wears</title>
</head>

<body id="top">

<header class="header" data-header>
   <div class="container">
    <div class="overlay" data-overlay></div>
  <a href="#" class="logo">
    <img src="../images/my wear logo.png" width="160" height="50" alt="mywears logo">
  </a>
  <button class="nav-open-btn" data-nav-open-btn aria-label="Open Menu">
    <i class="fa fa-bars" aria-hidden="true"></i>
  </button>
  <nav class="navbar" data-navbar>
    <button class="nav-close-btn" data-nav-close-btn aria-label="Close Menu">
      <i class="fa fa-times" aria-hidden="true"></i>
    </button>
    <a href="#" class="logo">
      <img src="../images/my wear logo.png" width="190" height="50" alt="Mywears Logo">
    </a>
    <ul class="navbar-list">
      <li class="navbar-item">
        <a href="../codes/index.html" class="navbar-link">Home</a>
      </li>
      <li class="navbar-item">
        <a href="../codes/aboutus.html" class="navbar-link">About Us</a>
      </li>
      <li class="navbar-item">
        <a href="../codes/ourproduct.html" class="navbar-link">Our Products</a>
      </li>
      <li class="navbar-item">
        <a href="../codes/shop.html" class="navbar-link">Shop</a>
      </li>
      <li class="navbar-item">
        <a href="../codes/reviews.html" class="navbar-link">Reviews</a>
      </li>
    </ul>

    <ul class="nav-action-list">
     <li>
      <button class="nav-action-btn">
        <i class="fa fa-search" aria-hidden="true"></i>
        <span class="nav-action-text">Search</span>
      </button>
     </li>
     <li>
      <button class="nav-action-btn">
        <i class="fa-regular fa-user"></i>
        <span class="nav-action-text">Login/Register</span>
      </button>
     </li>
     <li>
      <button class="nav-action-btn">
        <i class="fa-regular fa-heart"></i>
        <span class="nav-action-text">Whishlist</span>
        <data class="nav-action-badge" value="5" aria-hidden="true">5</data>
      </button>
     </li>
     <li>
      <button class="nav-action-btn">
        <i class="fa fa-suitcase" aria-hidden="true"></i>
        <data class="nav-action-text" value="50,000.00">Basket: <strong>#50,000.00</strong></data>
        <data class="nav-action-badge" value="4" aria-hidden="true">4</data>
      </button>
     </li>
    </ul>
  </nav>
  </div>
  </header>

<main>
  <article>
    <section class="section hero" style="background-image: url('../images/129.JPG');">
      <div class="container">
        <h2 class="h1 hero-title"> My Wears <strong>Handmade Quality</strong>
        </h2>

        <p class="hero-text">My Wears brings you a  trendy collection of stylish and comfortable   shoes for all ages. Whether you're dressing
          up for a special occasion or looking for casual everyday wear, we have the perfect pair that suits your needs.
        </p>

          <button class="btn btn-primary">
            <span>Shop Now</span>
            <i class="fa fa-long-arrow-right" aria-hidden="true"></i>
          </button>

      </div>
    </section>

    <!-- <section class="section collection">
      <div class="container">
        <ul class="collection-list has-scrollbar">
          <li>
            <div class="collection-card" style="background-image: url(../images/boot.jpg);">
              <h3 class="h4 card-tiitle">Men Collection</h3>
              <a href="#" class="btn-secondary">
                <span>Explore All</span>
                <i class="fa fa-long-arrow-right" aria-hidden="true"></i>
              </a>
            </div>
          </li>

          <li>
            <div class="collection-card" style="background-image: url(../images/woman.jpg)">
              <h3 class="h4 card-tiitle">WoMen Collection</h3>
              <a href="#" class="btn-secondary">
                <span>Explore All</span>
                <i class="fa fa-long-arrow-right" aria-hidden="true"></i>
              </a>
            </div>
          </li>

          <li>
            <div class="collection-card" style="background-image: url(../images/kids.jpg)">
              <h3 class="h4 card-tiitle">Kids</h3>
              <a href="#" class="btn-secondary">
                <span>Explore All</span>
                <i class="fa fa-long-arrow-right" aria-hidden="true"></i>
              </a>
            </div>
          </li>
        </ul>
      </div>
    </section> -->

    <!-- <section class="section product">
    <div class="container">
      <h2 class="h2 section-title">Bestselling Products</h2>

      <ul class="filter-list">

        <li>
          <button class="filter-btn">Bespoke</button>
        </li>

        <li>
          <button class="filter-btn">Loafers</button>
        </li>

        <li>
          <button class="filter-btn">Slides</button>
        </li>

        <li>
          <button class="filter-btn">Berkinstock</button>
        </li>

        <li>
          <button class="filter-btn">Men`s Purse</button>
        </li>

        <li>
          <button class="filter-btn active">Heels</button>
        </li>
      </ul>

    <ul class="product-list">
      <li class="product-item">
        <div class="product-card" tabindex="0">

          <figure class="card-banner">
            <img src="../images/217.png" width="312" height="350" loading="lazy" alt="bag" class="image-contain">

            <div class="card-badge">New</div>

            <ul class="card-action-list">

              <li class="card-action-item">
              <button class="card-action-btn" aria-labelledby="card-label-1">
                <i class="fa fa-shopping-cart" aria-hidden="true"></i>
              </button>
              <div class="card-action-tooltip" id="card-label-1">Add to Cart</div>
              </li>

              <li class="card-action-item">
                <button class="card-action-btn" aria-labelledby="card-label-2">
                  <i class="fa-regular fa-heart"></i>
                </button>
                <div class="card-action-tooltip" id="card-label-2">Add to Whishlist</div>
              </li>

                <li class="card-action-item">
                  <button class="card-action-btn" aria-labelledby="card-label-3">
                  <i class="fa fa-eye" aria-hidden="true"></i>
                  </button>
                  <div class="card-action-tooltip" id="card-label-3">Quick View</div>
                  </li>

                  <li class="card-action-item">
                    <button class="card-action-btn" aria-labelledby="card-label-4">
                    <i class="fa fa-refresh" aria-hidden="true"></i>
                    </button>
                    <div class="card-action-tooltip" id="card-label-4">compare</div>
                  </li>
            </ul>
          </figure>

          <div class="card-content">
            <div class="card-cat">
             <a href="#" class="card-cat-link">Men</a> /
             <a href="#" class="card-cat-link">Women</a>
            </div>
            <h3 class="h3 card-title">
              <a href="#">My Wears Bag</a>
            </h3>
           <data class="card-price" value="50,000.00">#50,000.00</data>
          </div> 
        </div>
      </li>

        <li class="product-item">
          <div class="product-card" tabindex="0">
  
            <figure class="card-banner">
              <img src="../images/suede.jpg" width="312" height="350" loading="lazy" alt="suede" class="image-contain">
  
              <div class="card-badge">New</div>
  
              <ul class="card-action-list">
  
                <li class="card-action-item">
                <button class="card-action-btn" aria-labelledby="card-label-1">
                  <i class="fa fa-shopping-cart" aria-hidden="true"></i>
                </button>
                <div class="card-action-tooltip" id="card-label-1">Add to Cart</div>
                </li>
  
                <li class="card-action-item">
                  <button class="card-action-btn" aria-labelledby="card-label-2">
                    <i class="fa-regular fa-heart"></i>
                  </button>
                  <div class="card-action-tooltip" id="card-label-2">Add to Whishlist</div>
                  </li>
  
                  <li class="card-action-item">
                    <button class="card-action-btn" aria-labelledby="card-label-3">
                    <i class="fa fa-eye" aria-hidden="true"></i>
                    </button>
                    <div class="card-action-tooltip" id="card-label-3">Quick View</div>
                    </li>
  
                    <li class="card-action-item">
                      <button class="card-action-btn" aria-labelledby="card-label-4">
                      <i class="fa fa-refresh" aria-hidden="true"></i>
                      </button>
                      <div class="card-action-tooltip" id="card-label-4">compare</div>
                    </li>
              </ul>
            </figure>
  
             <div class="card-content">
              <div class="card-cat">
               <a href="#" class="card-cat-link">Men</a> /
               <a href="#" class="card-cat-link">Women</a>
              </div>
              <h3 class="h3 card-title">
                <a href="#">Men Suede Slide</a>
              </h3>
             <data class="card-price" value="15,000.00">#15,000.00</data>
            </div> 
          </div>
          </li>
  
          <li class="product-item">
            <div class="product-card" tabindex="0">
    
              <figure class="card-banner">
                <img src="../images/woman.jpg" width="312" height="350" loading="lazy" alt="shoe" class="image-contain">
    
    
                <ul class="card-action-list">
    
                  <li class="card-action-item">
                  <button class="card-action-btn" aria-labelledby="card-label-1">
                    <i class="fa fa-shopping-cart" aria-hidden="true"></i>
                  </button>
                  <div class="card-action-tooltip" id="card-label-1">Add to Cart</div>
                  </li>
    
                  <li class="card-action-item">
                    <button class="card-action-btn" aria-labelledby="card-label-2">
                      <i class="fa-regular fa-heart"></i>
                    </button>
                    <div class="card-action-tooltip" id="card-label-2">Add to Whishlist</div>
                    </li>
    
                    <li class="card-action-item">
                      <button class="card-action-btn" aria-labelledby="card-label-3">
                      <i class="fa fa-eye" aria-hidden="true"></i>
                      </button>
                      <div class="card-action-tooltip" id="card-label-3">Quick View</div>
                      </li>
    
                      <li class="card-action-item">
                        <button class="card-action-btn" aria-labelledby="card-label-4">
                        <i class="fa fa-refresh" aria-hidden="true"></i>
                        </button>
                        <div class="card-action-tooltip" id="card-label-4">compare</div>
                      </li>
                </ul>
              </figure>
    
               <div class="card-content">
                <div class="card-cat">
                 <a href="#" class="card-cat-link">Women</a> /
                 <a href="#" class="card-cat-link">Men</a>
                </div>
                <h3 class="h3 card-title">
                  <a href="#">Cover Shoe</a>
                </h3>
               <data class="card-price" value="30,000.00">#30,000.00</data>
              </div> 
            </div>
            </li>

            <li class="product-item">
              <div class="product-card" tabindex="0">
      
                <figure class="card-banner">
                  <img src="../images/kids.jpg" width="312" height="350" loading="lazy" alt="kids" class="image-contain">
      
                  <div class="card-badge">-25%</div>
      
                  <ul class="card-action-list">
      
                    <li class="card-action-item">
                    <button class="card-action-btn" aria-labelledby="card-label-1">
                      <i class="fa fa-shopping-cart" aria-hidden="true"></i>
                    </button>
                    <div class="card-action-tooltip" id="card-label-1">Add to Cart</div>
                    </li>
      
                    <li class="card-action-item">
                      <button class="card-action-btn" aria-labelledby="card-label-2">
                        <i class="fa-regular fa-heart"></i>
                      </button>
                      <div class="card-action-tooltip" id="card-label-2">Add to Whishlist</div>
                      </li>
      
                      <li class="card-action-item">
                        <button class="card-action-btn" aria-labelledby="card-label-3">
                        <i class="fa fa-eye" aria-hidden="true"></i>
                        </button>
                        <div class="card-action-tooltip" id="card-label-3">Quick View</div>
                        </li>
      
                        <li class="card-action-item">
                          <button class="card-action-btn" aria-labelledby="card-label-4">
                          <i class="fa fa-refresh" aria-hidden="true"></i>
                          </button>
                          <div class="card-action-tooltip" id="card-label-4">compare</div>
                        </li>
                  </ul>
                </figure>
      
                 <div class="card-content">
                  <div class="card-cat">
                   <a href="#" class="card-cat-link">Kids</a> /
                   <a href="#" class="card-cat-link">Kids</a>
                  </div>
                  <h3 class="h3 card-title">
                    <a href="#">Kids Shoe</a>
                  </h3>
                 <data class="card-price" value="20,000.00">#20,000.00 <del>#30,000.00</del></data>
                </div> 
              </div>
              </li>

              <li class="product-item">
                <div class="product-card" tabindex="0">
        
                  <figure class="card-banner">
                    <img src="../images/download.jpg" width="312" height="350" loading="lazy" alt="bespoke" class="image-contain">
        
                    <div class="card-badge">New</div>
        
                    <ul class="card-action-list">
        
                      <li class="card-action-item">
                      <button class="card-action-btn" aria-labelledby="card-label-1">
                        <i class="fa fa-shopping-cart" aria-hidden="true"></i>
                      </button>
                      <div class="card-action-tooltip" id="card-label-1">Add to Cart</div>
                      </li>
        
                      <li class="card-action-item">
                        <button class="card-action-btn" aria-labelledby="card-label-2">
                          <i class="fa-regular fa-heart"></i>
                        </button>
                        <div class="card-action-tooltip" id="card-label-2">Add to Whishlist</div>
                        </li>
        
                        <li class="card-action-item">
                          <button class="card-action-btn" aria-labelledby="card-label-3">
                          <i class="fa fa-eye" aria-hidden="true"></i>
                          </button>
                          <div class="card-action-tooltip" id="card-label-3">Quick View</div>
                          </li>
        
                          <li class="card-action-item">
                            <button class="card-action-btn" aria-labelledby="card-label-4">
                            <i class="fa fa-refresh" aria-hidden="true"></i>
                            </button>
                            <div class="card-action-tooltip" id="card-label-4">compare</div>
                          </li>
                    </ul>
                  </figure>
        
                  <div class="card-content">
                    <div class="card-cat">
                     <a href="#" class="card-cat-link">Men</a> /
                     <a href="#" class="card-cat-link">Men</a>
                    </div>
                    <h3 class="h3 card-title">
                      <a href="#">Bespoke Shoe</a>
                    </h3>
                   <data class="card-price" value="40,000.00">#40,000.00</data>
                  </div> 
                </div>
                </li>

                <li class="product-item">
                  <div class="product-card" tabindex="0">
          
                    <figure class="card-banner">
                      <img src="../images/images.jpg" width="312" height="350" loading="lazy" alt="purse" class="image-contain">
        
          
                      <ul class="card-action-list">
          
                        <li class="card-action-item">
                        <button class="card-action-btn" aria-labelledby="card-label-1">
                          <i class="fa fa-shopping-cart" aria-hidden="true"></i>
                        </button>
                        <div class="card-action-tooltip" id="card-label-1">Add to Cart</div>
                        </li>
          
                        <li class="card-action-item">
                          <button class="card-action-btn" aria-labelledby="card-label-2">
                            <i class="fa-regular fa-heart"></i>
                          </button>
                          <div class="card-action-tooltip" id="card-label-2">Add to Whishlist</div>
                          </li>
          
                          <li class="card-action-item">
                            <button class="card-action-btn" aria-labelledby="card-label-3">
                            <i class="fa fa-eye" aria-hidden="true"></i>
                            </button>
                            <div class="card-action-tooltip" id="card-label-3">Quick View</div>
                            </li>
          
                            <li class="card-action-item">
                              <button class="card-action-btn" aria-labelledby="card-label-4">
                              <i class="fa fa-refresh" aria-hidden="true"></i>
                              </button>
                              <div class="card-action-tooltip" id="card-label-4">compare</div>
                            </li>
                      </ul>
                    </figure>
          
                     <div class="card-content">
                      <div class="card-cat">
                       <a href="#" class="card-cat-link">Men</a> /
                       <a href="#" class="card-cat-link">Women</a>
                      </div>
                      <h3 class="h3 card-title">
                        <a href="#">Men`s Purse</a>
                      </h3>
                     <data class="card-price" value="20,000.00">#20,000.00</data>
                    </div> 
                  </div>
                  </li>
          
                  <li class="product-item">
                    <div class="product-card" tabindex="0">
            
                      <figure class="card-banner">
                        <img src="../images/051.JPG" width="312" height="350" loading="lazy" alt="berkinstock" class="image-contain">
            
                        <div class="card-badge">New</div>
            
                        <ul class="card-action-list">
            
                          <li class="card-action-item">
                          <button class="card-action-btn" aria-labelledby="card-label-1">
                            <i class="fa fa-shopping-cart" aria-hidden="true"></i>
                          </button>
                          <div class="card-action-tooltip" id="card-label-1">Add to Cart</div>
                          </li>
            
                          <li class="card-action-item">
                            <button class="card-action-btn" aria-labelledby="card-label-2">
                              <i class="fa-regular fa-heart"></i>
                            </button>
                            <div class="card-action-tooltip" id="card-label-2">Add to Whishlist</div>
                            </li>
            
                            <li class="card-action-item">
                              <button class="card-action-btn" aria-labelledby="card-label-3">
                              <i class="fa fa-eye" aria-hidden="true"></i>
                              </button>
                              <div class="card-action-tooltip" id="card-label-3">Quick View</div>
                              </li>
            
                              <li class="card-action-item">
                                <button class="card-action-btn" aria-labelledby="card-label-4">
                                <i class="fa fa-refresh" aria-hidden="true"></i>
                                </button>
                                <div class="card-action-tooltip" id="card-label-4">compare</div>
                              </li>
                        </ul>
                      </figure>
            
                       <div class="card-content">
                        <div class="card-cat">
                         <a href="#" class="card-cat-link">Men</a> /
                         <a href="#" class="card-cat-link">Women</a>
                        </div>
                        <h3 class="h3 card-title">
                          <a href="#">Berkinstock</a>
                        </h3>
                       <data class="card-price" value="20,000.00">#20,000.00</data>
                      </div> 
                    </div>
                    </li>

                    <li class="product-item">
                      <div class="product-card" tabindex="0">
              
                        <figure class="card-banner">
                          <img src="../images/053.JPG" width="312" height="350" loading="lazy" alt="wslide" class="image-contain">
              
                          <div class="card-badge">New</div>
              
                          <ul class="card-action-list">
              
                            <li class="card-action-item">
                            <button class="card-action-btn" aria-labelledby="card-label-1">
                              <i class="fa fa-shopping-cart" aria-hidden="true"></i>
                            </button>
                            <div class="card-action-tooltip" id="card-label-1">Add to Cart</div>
                            </li>
              
                            <li class="card-action-item">
                              <button class="card-action-btn" aria-labelledby="card-label-2">
                                <i class="fa-regular fa-heart"></i>
                              </button>
                              <div class="card-action-tooltip" id="card-label-2">Add to Whishlist</div>
                              </li>
              
                              <li class="card-action-item">
                                <button class="card-action-btn" aria-labelledby="card-label-3">
                                <i class="fa fa-eye" aria-hidden="true"></i>
                                </button>
                                <div class="card-action-tooltip" id="card-label-3">Quick View</div>
                                </li>
              
                                <li class="card-action-item">
                                  <button class="card-action-btn" aria-labelledby="card-label-4">
                                  <i class="fa fa-refresh" aria-hidden="true"></i>
                                  </button>
                                  <div class="card-action-tooltip" id="card-label-4">compare</div>
                                </li>
                          </ul>
                        </figure>
              
                         <div class="card-content">
                          <div class="card-cat">
                           <a href="#" class="card-cat-link">Women</a> /
                           <a href="#" class="card-cat-link">Women</a>
                          </div>
                          <h3 class="h3 card-title">
                            <a href="#">Women slide</a>
                          </h3>
                         <data class="card-price" value="15,000.00">#15,000.00</data>
                        </div> 
                      </div>
                    </li>

      </ul>
    </div>
    </section> -->

      <section class="section cta">
       <div class="container">
        <ul class="cta-list">
          <l1>
            <div class="cta-card" style="background-image: url(../images/135.JPG);">
              <p class="card-subtitle">Bespoke Shoes</p>
              <h3 class="h2-card-title">December Sales off 50%</h3>
              <a href="#" class="btn btn-link"><span>Shop Now</span>
                <i class="fa fa-long-arrow-right" aria-hidden="true"></i>
              </a>
            </div>
          </l1>

          <l1>
            <div class="cta-card" style="background-image: url(../images/028.JPG);">
              <p class="card-subtitle">High Heels</p>
              <h3 class="h2-card-title">Make Yourself Feel Classy</h3>
              <a href="#" class="btn btn-link"><span>Shop Now</span>
                <i class="fa fa-long-arrow-right" aria-hidden="true"></i>
              </a>
            </div>
          </l1>

        </ul>
       </div>
      </section>

    <section class="section special">
     <div class="container">
      <div class="special-banner" style="background-image: url(../images/608.JPG);">
        <h2 class="h3 banner-title">New Trend Edition</h2>
        <a href="#" class="btn btn-link">
          <span>Explore All</span>
          <i class="fa fa-long-arrow-right" aria-hidden="true"></i>
        </a>
      </div>

      <div class="special-product">

        <h2 class="h2 section-title">
          <span class="text"> My Wears Special</span>
          <span class="line"></span>
        </h2>
       
        <ul class="has-scrollbar">
          <li class="product-item">
            <div class="product-card" tabindex="0">
    
              <figure class="card-banner">
                <img src="../images/217.png" width="312" height="350" loading="lazy" alt="bag" class="image-contain">
    
                <div class="card-badge">New</div>
    
                <ul class="card-action-list">
    
                  <li class="card-action-item">
                  <button class="card-action-btn" aria-labelledby="card-label-1">
                    <i class="fa fa-shopping-cart" aria-hidden="true"></i>
                  </button>
                  <div class="card-action-tooltip" id="card-label-1">Add to Cart</div>
                  </li>
    
                  <li class="card-action-item">
                    <button class="card-action-btn" aria-labelledby="card-label-2">
                      <i class="fa-regular fa-heart"></i>
                    </button>
                    <div class="card-action-tooltip" id="card-label-2">Add to Whishlist</div>
                    </li>
    
                    <li class="card-action-item">
                      <button class="card-action-btn" aria-labelledby="card-label-3">
                      <i class="fa fa-eye" aria-hidden="true"></i>
                      </button>
                      <div class="card-action-tooltip" id="card-label-3">Quick View</div>
                      </li>
    
                      <li class="card-action-item">
                        <button class="card-action-btn" aria-labelledby="card-label-4">
                        <i class="fa fa-refresh" aria-hidden="true"></i>
                        </button>
                        <div class="card-action-tooltip" id="card-label-4">compare</div>
                      </li>
                </ul>
              </figure>
    
               <div class="card-content">
                <div class="card-cat">
                 <a href="#" class="card-cat-link">Men</a> /
                 <a href="#" class="card-cat-link">Women</a>
                </div>
                <h3 class="h3 card-title">
                  <a href="#">My Wears Bag</a>
                </h3>
               <data class="card-price" value="50,000.00">#50,000.00</data>
              </div> 
            </div>
          </li>
    
            <li class="product-item">
              <div class="product-card" tabindex="0">
      
                <figure class="card-banner">
                  <img src="../images/suede.jpg" width="312" height="350" loading="lazy" alt="suede" class="image-contain">
      
                  <div class="card-badge">New</div>
      
                  <ul class="card-action-list">
      
                    <li class="card-action-item">
                    <button class="card-action-btn" aria-labelledby="card-label-1">
                      <i class="fa fa-shopping-cart" aria-hidden="true"></i>
                    </button>
                    <div class="card-action-tooltip" id="card-label-1">Add to Cart</div>
                    </li>
      
                    <li class="card-action-item">
                      <button class="card-action-btn" aria-labelledby="card-label-2">
                        <i class="fa-regular fa-heart"></i>
                      </button>
                      <div class="card-action-tooltip" id="card-label-2">Add to Whishlist</div>
                      </li>
      
                      <li class="card-action-item">
                        <button class="card-action-btn" aria-labelledby="card-label-3">
                        <i class="fa fa-eye" aria-hidden="true"></i>
                        </button>
                        <div class="card-action-tooltip" id="card-label-3">Quick View</div>
                        </li>
      
                        <li class="card-action-item">
                          <button class="card-action-btn" aria-labelledby="card-label-4">
                          <i class="fa fa-refresh" aria-hidden="true"></i>
                          </button>
                          <div class="card-action-tooltip" id="card-label-4">compare</div>
                        </li>
                  </ul>
                </figure>
      
                 <div class="card-content">
                  <div class="card-cat">
                   <a href="#" class="card-cat-link">Men</a> /
                   <a href="#" class="card-cat-link">Women</a>
                  </div>
                  <h3 class="h3 card-title">
                    <a href="#">Men Suede Slide</a>
                  </h3>
                 <data class="card-price" value="15,000.00">#15,000.00</data>
                </div> 
              </div>
            </li>
      
              <li class="product-item">
                <div class="product-card" tabindex="0">
        
                  <figure class="card-banner">
                    <img src="../images/woman.jpg" width="312" height="350" loading="lazy" alt="shoe" class="image-contain">
        
        
                    <ul class="card-action-list">
        
                      <li class="card-action-item">
                      <button class="card-action-btn" aria-labelledby="card-label-1">
                        <i class="fa fa-shopping-cart" aria-hidden="true"></i>
                      </button>
                      <div class="card-action-tooltip" id="card-label-1">Add to Cart</div>
                      </li>
        
                      <li class="card-action-item">
                        <button class="card-action-btn" aria-labelledby="card-label-2">
                          <i class="fa-regular fa-heart"></i>
                        </button>
                        <div class="card-action-tooltip" id="card-label-2">Add to Whishlist</div>
                        </li>
        
                        <li class="card-action-item">
                          <button class="card-action-btn" aria-labelledby="card-label-3">
                          <i class="fa fa-eye" aria-hidden="true"></i>
                          </button>
                          <div class="card-action-tooltip" id="card-label-3">Quick View</div>
                          </li>
        
                          <li class="card-action-item">
                            <button class="card-action-btn" aria-labelledby="card-label-4">
                            <i class="fa fa-refresh" aria-hidden="true"></i>
                            </button>
                            <div class="card-action-tooltip" id="card-label-4">compare</div>
                          </li>
                    </ul>
                  </figure>
        
                   <div class="card-content">
                    <div class="card-cat">
                     <a href="#" class="card-cat-link">Women</a> /
                     <a href="#" class="card-cat-link">Men</a>
                    </div>
                    <h3 class="h3 card-title">
                      <a href="#">Cover Shoe</a>
                    </h3>
                   <data class="card-price" value="30,000.00">#30,000.00</data>
                  </div> 
                </div>
                </li>
    
                <li class="product-item">
                  <div class="product-card" tabindex="0">
          
                    <figure class="card-banner">
                      <img src="../images/kids.jpg" width="312" height="350" loading="lazy" alt="kids" class="image-contain">
          
                      <div class="card-badge">-25%</div>
          
                      <ul class="card-action-list">
          
                        <li class="card-action-item">
                        <button class="card-action-btn" aria-labelledby="card-label-1">
                          <i class="fa fa-shopping-cart" aria-hidden="true"></i>
                        </button>
                        <div class="card-action-tooltip" id="card-label-1">Add to Cart</div>
                        </li>
          
                        <li class="card-action-item">
                          <button class="card-action-btn" aria-labelledby="card-label-2">
                            <i class="fa-regular fa-heart"></i>
                          </button>
                          <div class="card-action-tooltip" id="card-label-2">Add to Whishlist</div>
                          </li>
          
                          <li class="card-action-item">
                            <button class="card-action-btn" aria-labelledby="card-label-3">
                            <i class="fa fa-eye" aria-hidden="true"></i>
                            </button>
                            <div class="card-action-tooltip" id="card-label-3">Quick View</div>
                            </li>
          
                            <li class="card-action-item">
                              <button class="card-action-btn" aria-labelledby="card-label-4">
                              <i class="fa fa-refresh" aria-hidden="true"></i>
                              </button>
                              <div class="card-action-tooltip" id="card-label-4">compare</div>
                            </li>
                      </ul>
                    </figure>
          
                     <div class="card-content">
                      <div class="card-cat">
                       <a href="#" class="card-cat-link">Kids</a> /
                       <a href="#" class="card-cat-link">Kids</a>
                      </div>
                      <h3 class="h3 card-title">
                        <a href="#">Kids Shoe</a>
                      </h3>
                     <data class="card-price" value="20,000.00">#20,000.00 <del>#30,000.00</del></data>
                    </div> 
                  </div>
                  </li>
                
        </ul>
       
      </div>

     </div>
    </section>

    <!-- <section class="section service">
      <div class="container">
        <ul class="service-list">
          <li class="service-item">
            <div class="service-card">
              <div class="card-icon">
                <i class="fa-solid fa-truck" width="53" height="28" loading="lazy"></i>
              </div>
              <div>
                <h3 class="h4 card-title">Free Delivery</h3>
                <p class="card-text">
                 All orders over <span>#20,000.00</span>
                </p>
              </div>
            </div>
          </li>

          <li class="service-item">
            <div class="service-card">
              <div class="card-icon">
                <i class="fa-regular fa-credit-card" width="43" height="35" loading="lazy" ></i>
              </div>
              <div>
                <h3 class="h4 card-title">Quick Payment</h3>
                <p class="card-text">
                 100% secure payment
                </p>
              </div>
            </div>
          </li>

          <li class="service-item">
            <div class="service-card">
              <div class="card-icon">
                <i class="fa-solid fa-money-bills" width="40" height="40" loading="lazy"></i>
              </div>
              <div>
                <h3 class="h4 card-title">Free Returns</h3>
                <p class="card-text">
                Money back in 30 days
                </p>
              </div>
            </div>
          </li>

          <li class="service-item">
            <div class="service-card">
              <div class="card-icon">
                <i class="fa-regular fa-circle-question" width="40" height="40" loading="lazy"></i>
              </div>
              <div>
                <h3 class="h4 card-title">24/7 Support</h3>
                <p class="card-text">
                Get Quick Support
                </p>
              </div>
            </div>
          </li>

        </ul>
      </div>
    </section> -->

    <section class="section insta-post">
      <ul class="insta-post-list has-scrollbar">
        <li class="insta-post-item">
          <img src="../images/801.PNG" width="100" height="100" alt="insta post" loading="lazy" class="insta-post-banner image-contain">
          <a href="#"class=insta-post-link>
            <i class="fa-brands fa-instagram"></i>
          </a>
        </li>

        <li class="insta-post-item">
          <img src="../images/011.PNG" width="100" height="100" alt="insta post" loading="lazy" class="insta-post-banner image-contain">
          <a href="#"class=insta-post-link>
            <i class="fa-brands fa-instagram"></i>
          </a>
        </li>

        <li class="insta-post-item">
          <img src="../images/004.JPG" width="100" height="100" alt="insta post" loading="lazy" class="insta-post-banner image-contain">
          <a href="#"class=insta-post-link>
            <i class="fa-brands fa-instagram"></i>
          </a>
        </li>

        <li class="insta-post-item">
          <img src="../images/287.jpg" width="100" height="100" alt="insta post" loading="lazy" class="insta-post-banner image-contain">
          <a href="#"class=insta-post-link>
            <i class="fa-brands fa-instagram"></i>
          </a>
        </li>

        <li class="insta-post-item">
          <img src="../images/813.JPG" width="100" height="100" alt="insta post" loading="lazy" class="insta-post-banner image-contain">
          <a href="#"class=insta-post-link>
            <i class="fa-brands fa-instagram"></i>
          </a>
        </li>

        <li class="insta-post-item">
          <img src="../images/819.JPG" width="100" height="100" alt="insta post" loading="lazy" class="insta-post-banner image-contain">
          <a href="#"class=insta-post-link>
            <i class="fa-brands fa-instagram"></i>
          </a>
        </li>

        <li class="insta-post-item">
          <img src="../images/217.png" width="100" height="100" alt="insta post" loading="lazy" class="insta-post-banner image-contain">
          <a href="#"class=insta-post-link>
            <i class="fa-brands fa-instagram"></i>
          </a>
        </li>

        <li class="insta-post-item">
          <img src="../images/download (3).jpg" width="100" height="100" alt="insta post" loading="lazy" class="insta-post-banner image-contain">
          <a href="#"class=insta-post-link>
            <i class="fa-brands fa-instagram"></i>
          </a>
        </li>

      </ul>

    </section>

    <footer class="footer">
      <div class="footer-top section">
        <div class="container">
          <div class="footer-brand">
            <a href="#" class="logo">
              <img src="../images/my wear logo.png" width="160" height="50" alt="logo">
            </a>
    
            <ul class="social-list">
              <li>
                <a  href="#" class="social-link">
                  <i class="fa-brands fa-facebook"></i>
                </a>
              </li>
    
              <li>
                <a  href="#" class="social-link">
                  <i class="fa-brands fa-instagram"></i>
                </a>
              </li>
    
              <li>
                <a  href="#" class="social-link">
                  <i class="fa-brands fa-whatsapp"></i>
                </a>
              </li>
    
              <li>
                <a  href="#" class="social-link">
                  <i class="fa-brands fa-twitter"></i>
                </a>
              </li>
    
            </ul>
    
          </div>
          <div class="footer-link-box">
            <ul class="footer-list">
              <li>
                <p class="footer-list-title">Contact Us</p>
              </li>
    
              <li>
                <address class="footer-link">
                  <i class="fa-solid fa-location-dot"></i>
                  <span class="footer-link-text">178a, Abesan Estate, Ipaja Road, Lagos.</span>
                </address>
              </li>
    
              <li>
                <a href="tel:2348150592930" class="footer-link">
                  <i class="fa-solid fa-phone"></i>
                  <span class="footer-link-text">+2348150592930</span>
                </a>
              </li>
    
              <li>
                <a href="mailto:akiyadedeborah@gmail.com" class="footer-link">
                  <i class="fa-solid fa-at"></i>
                  <span class="footer-link-text">akiyadedeborah@gmail.com</span>
                </a>
              </li>
            
              
            </ul>
            
            <ul class="footer-list">
              <li>
                <p class="footer-list-title">My Account</p>
              </li>
    
              <li>
              <a href="#" class="footer-link">
                <i class="fa solid fa-angle-right"></i>
                <span class="footer-link-text">My Account</span>
              </a>
              </li>
    
              <li>
                <a href="#" class="footer-link">
                  <i class="fa solid fa-angle-right"></i>
                  <span class="footer-link-text">View Cart</span>
                </a>
                </li>
    
                <li>
                  <a href="#" class="footer-link">
                    <i class="fa solid fa-angle-right"></i>
                    <span class="footer-link-text">Wishlist</span>
                  </a>
                  </li>
    
                  <li>
                    <a href="#" class="footer-link">
                      <i class="fa solid fa-angle-right"></i>
                      <span class="footer-link-text">Compare</span>
                    </a>
                    </li>
    
                    <li>
                      <a href="#" class="footer-link">
                        <i class="fa solid fa-angle-right"></i>
                        <span class="footer-link-text">New Products</span>
                      </a>
                    </li>
    
            </ul>
    
            <div class="footer-list">
              <p class="footer-list-title">Opening Time</p>
              <table class="footer-table">
                <tbody>
                  <tr class="table-row">
                     <th class="table-head" scope="row">Mon - Tue:</th>
                     <td class="table-data">8AM - 10PM</td>
                  </tr>
    
                  <tr class="table-row">
                    <th class="table-head" scope="row">Wed - Thurs:</th>
                    <td class="table-data">8AM - 7PM</td>
                 </tr>
    
                 <tr class="table-row">
                  <th class="table-head" scope="row">Fri:</th>
                  <td class="table-data">7AM - 12PM</td>
               </tr>
    
               <tr class="table-row">
                <th class="table-head" scope="row">Sat:</th>
                <td class="table-data">9AM - 8PM</td>
             </tr>
    
             <tr class="table-row">
              <th class="table-head" scope="row">Sun:</th>
              <td class="table-data">Closed</td>
           </tr>
    
                </tbody>
    
              </table>
    
            </div>
    
            <div class="footer-list">
              <p class="footer-list-title">Newsletter</p>
              <p class="newsletter-text">
                We'd love to hear from you
              </p>
    
              <form action="" class="newsletter-form">
                <input type="email" name="email" required placeholder="Email Address" class="newsletter-input">
                <button type="submit" class="btn btn-primary">Subscribe</button>
              </form>
    
            </div>
    
          </div>
    
        </div>
      </div>
    
      <div class="footer-bottom">
        <div class="container">
          <p class="copyright">
            &copy; 2024 <a href="#" class="copyright-link">My Codes</a>. All Rights Reserved
          </p>
        </div>
      </div>
    
    </footer>
    
    <a href="#top" class="go-top-btn" data-go-top>
      <p>&#8679;</p>
    </a>

  </article>
</main>

<!-- <footer class="footer">
  <div class="footer-top section">
    <div class="container">
      <div class="footer-brand">
        <a href="#" class="logo">
          <img src="../images/my wear logo.png" width="160" height="50" alt="logo">
        </a>

        <ul class="social-list">
          <li>
            <a  href="#" class="social-link">
              <i class="fa-brands fa-facebook"></i>
            </a>
          </li>

          <li>
            <a  href="#" class="social-link">
              <i class="fa-brands fa-instagram"></i>
            </a>
          </li>

          <li>
            <a  href="#" class="social-link">
              <i class="fa-brands fa-whatsapp"></i>
            </a>
          </li>

          <li>
            <a  href="#" class="social-link">
              <i class="fa-brands fa-twitter"></i>
            </a>
          </li>

        </ul>

      </div>
      <div class="footer-link-box">
        <ul class="footer-list">
          <li>
            <p class="footer-list-title">Contact Us</p>
          </li>

          <li>
            <address class="footer-link">
              <i class="fa-solid fa-location-dot"></i>
              <span class="footer-link-text">178a, Abesan Estate, Ipaja Road, Lagos.</span>
            </address>
          </li>

          <li>
            <a href="tel:2348150592930" class="footer-link">
              <i class="fa-solid fa-phone"></i>
              <span class="footer-link-text">+2348150592930</span>
            </a>
          </li>

          <li>
            <a href="mailto:akiyadedeborah@gmail.com" class="footer-link">
              <i class="fa-solid fa-at"></i>
              <span class="footer-link-text">akiyadedeborah@gmail.com</span>
            </a>
          </li>
        
          
        </ul>
        
        <ul class="footer-list">
          <li>
            <p class="footer-list-title">My Account</p>
          </li>

          <li>
          <a href="#" class="footer-link">
            <i class="fa solid fa-angle-right"></i>
            <span class="footer-link-text">My Account</span>
          </a>
          </li>

          <li>
            <a href="#" class="footer-link">
              <i class="fa solid fa-angle-right"></i>
              <span class="footer-link-text">View Cart</span>
            </a>
            </li>

            <li>
              <a href="#" class="footer-link">
                <i class="fa solid fa-angle-right"></i>
                <span class="footer-link-text">Wishlist</span>
              </a>
              </li>

              <li>
                <a href="#" class="footer-link">
                  <i class="fa solid fa-angle-right"></i>
                  <span class="footer-link-text">Compare</span>
                </a>
                </li>

                <li>
                  <a href="#" class="footer-link">
                    <i class="fa solid fa-angle-right"></i>
                    <span class="footer-link-text">New Products</span>
                  </a>
                </li>

        </ul>

        <div class="footer-list">
          <p class="footer-list-title">Opening Time</p>
          <table class="footer-table">
            <tbody>
              <tr class="table-row">
                 <th class="table-head" scope="row">Mon - Tue:</th>
                 <td class="table-data">8AM - 10PM</td>
              </tr>

              <tr class="table-row">
                <th class="table-head" scope="row">Wed - Thurs:</th>
                <td class="table-data">8AM - 7PM</td>
             </tr>

             <tr class="table-row">
              <th class="table-head" scope="row">Fri:</th>
              <td class="table-data">7AM - 12PM</td>
           </tr>

           <tr class="table-row">
            <th class="table-head" scope="row">Sat:</th>
            <td class="table-data">9AM - 8PM</td>
         </tr>

         <tr class="table-row">
          <th class="table-head" scope="row">Sun:</th>
          <td class="table-data">Closed</td>
       </tr>

            </tbody>

          </table>

        </div>

        <div class="footer-list">
          <p class="footer-list-title">Newsletter</p>
          <p class="newsletter-text">
            We'd love to hear from you
          </p>

          <form action="" class="newsletter-form">
            <input type="email" name="email" required placeholder="Email Address" class="newsletter-input">
            <button type="submit" class="btn btn-primary">Subscribe</button>
          </form>

        </div>

      </div>

    </div>
  </div>

  <div class="footer-bottom">
    <div class="container">
      <p class="copyright">
        &copy; 2024 <a href="#" class="copyright-link">My Codes</a>. All Rights Reserved
      </p>
    </div>
  </div>

</footer>

<a href="#top" class="go-top-btn" data-go-top>
  <p>&#8679;</p>
</a> -->

  <script src="../codes/index.js"></script>
  <script nomodule src="https://unpkg.com/ionicons@4.5.10-0/dist/ionicons.js"></script>
  </body>
  </html>
