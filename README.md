<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>CHRXS HOODS</title>
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: "Poppins", Arial, sans-serif;
      background: #000000;
      color: #111;
    }

    header {
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 15px 60px;
      border-bottom: 1px solid #e5e7eb;
      box-shadow: 0 2px 8px rgba(0, 0, 0, 0.05);
    }

    .logo a {
      font-size: 30px;
      font-weight: 800;
      letter-spacing: 3px;
      color: #ffffff;
      text-decoration: none;
    }

    .search-container {
      flex: 1;
      display: flex;
      justify-content: center;
    }

    .search-box {
      position: relative;
      width: 50%;
      max-width: 500px;
    }

    .search-box input {
      width: 100%;
      padding: 10px 45px 10px 20px;
      border: 1px solid #d1d5db;
      border-radius: 30px;
      background-color: #f9f9f9;
      font-size: 15px;
      transition: all 0.3s ease;
    }

    .search-box input:focus {
      background-color: #fff;
      outline: none;
      border-color: #111;
      box-shadow: 0 0 5px rgba(0, 0, 0, 0.15);
    }

    .search-box svg {
      position: absolute;
      right: 15px;
      top: 50%;
      transform: translateY(-50%);
      width: 20px;
      height: 20px;
      fill: #555;
      pointer-events: none;
    }

    nav ul {
      list-style: none;
      display: flex;
      align-items: center;
      gap: 25px;
    }

    nav ul li a {
      text-decoration: none;
      display: inline-flex;
      align-items: center;
      justify-content: center;
      width: 35px;
      height: 35px;
      border-radius: 50%;
      transition: background 0.3s ease, transform 0.2s ease;
    }

    nav ul li a:hover {
      background: #f1f1f1;
      transform: translateY(-2px);
    }

    nav svg {
      width: 22px;
      height: 22px;
      stroke: #000;
      stroke-width: 2;
      fill: none;
    }

    .login-btn {
      border: 1px solid #ffffff;
      padding: 8px 16px;
      border-radius: 30px;
      text-decoration: none;
      color: #ffffff;
      font-weight: 500;
      transition: all 0.3s ease;
    }

    .login-btn:hover {
      background: #000;
      color: #fff;
    }

    .products-container {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      align-items: center;
      gap: 150px;
      padding: 60px;

    }


    .product-card {
      width: 250px;
      background: #313131;
      border: 1px solid #292929;
      border-radius: 12px;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.05);
      overflow: hidden;
      text-align: center;
      transition: transform 0.2s ease, box-shadow 0.2s ease;
    }

    .product-card:hover {
      transform: translateY(-6px);
      box-shadow: 0 6px 15px rgba(0, 0, 0, 0.1);
    }

    .product-card a {
      text-decoration: none;
      color: inherit;
      display: block;
    }

    .product-card img {
      width: 100%;
      height: auto;
      border-bottom: 1px solid #222222;
      transition: transform 0.3s ease;
    }

    .product-card:hover img {
      transform: scale(1.05);
    }

    .product-info {
      padding: 15px;
    }

    .product-info h3 {
      font-size: 16px;
      font-weight: 600;
      margin-bottom: 6px;
      color: #fff;
    }

    .price {
      font-size: 15px;
      font-weight: 500;
      color: #ffffff;
      margin-bottom: 10px;
    }

    .add-cart {
      border: none;
      background: #111;
      color: #fff;
      padding: 8px 16px;
      border-radius: 25px;
      cursor: pointer;
      font-size: 14px;
      transition: background 0.3s ease;
    }

    .add-cart:hover {
      background: #444;
    }

    @media (max-width: 900px) {
      header {
        flex-direction: column;
        gap: 10px;
      }

      .search-box {
        width: 80%;
      }
    }
  </style>
</head>
<body>
  <header>
    <div class="logo">
      <a href="index.html">CHRXS</a>
    </div>

    <div class="search-container">
      <div class="search-box">
        <input type="text" placeholder="Search for products...">
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
          <path d="M21 21l-4.35-4.35M10.5 17a6.5 6.5 0 1 1 0-13 6.5 6.5 0 0 1 0 13z" stroke="#555" stroke-width="2" fill="none" stroke-linecap="round" stroke-linejoin="round"/>
        </svg>
      </div>
    </div>

    <nav>
      <ul>
        <li><a href="#settings" title="Shirt">👚</a></li>
        <li><a href="#settings" title="Jacker">🧥</a></li>
        <li><a href="#settings" title="Pants">👖</a></li>
        <li><a href="#settings" title="Cart">🛒</a></li>
        <li><a href="#voucher" title="Voucher">🎟️</a></li>
        <li><a href="#account" title="Account">👤</a></li>
        <li><a href="#settings" title="Settings">⚙️</a></li>
      </ul>
    </nav>

    <a href="login.html" class="login-btn">Login / Sign Up</a>
  </header>

<div class="products-container">
  <div class="product-card">
    <a href="https://ph.shein.com/Manfinity-Roghcode-Men-s-Skull-Letter-Graphic-Hooded-Drop-Shoulder-Sweatshirt-For-Fall-p-26652904.html?src_identifier=st%3D5%60sc%3DHoodie%20For%20Men%60sr%3D0%60ps%3D1&src_module=search&src_tab_page_id=page_home1761535913558&pageListType=4&imgRatio=3-4&pageListType=4">
      <img src="Hood1.png" alt="New York Hoodie Exclucive">
      <div class="product-info">
        <h3>New York Hoodie Exclucive</h3>
        <p class="price">₱408</p>
      </div>
    </a>
    <button class="add-cart">🛒 Add to Cart</button>
  </div>

  <div class="product-card">
    <a href="https://ph.shein.com/Manfinity-ZONE917-Men-s-Autumn-Winter-Branch-Print-Long-Sleeve-Thermal-Lined-Casual-Loose-Hoodie-Sweatshirt-p-221068648.html?src_identifier=st%3D2%60sc%3DLEAF+HOODIE%60sr%3D0%60ps%3D1&src_module=search&src_tab_page_id=page_search1761540685074&pageListType=4&imgRatio=3-4&pageListType=4&main_attr=27_447&mallCode=1&shouldNoSendMallCode=1">
      <img src="Hood2.png" alt="Branch Exclusive Hoodie">
      <div class="product-info">
        <h3>Branch Exclusive Hoodie</h3>
        <p class="price">₱499</p>
      </div>
    </a>
    <button class="add-cart">🛒 Add to Cart</button>
  </div>

  <div class="product-card">
    <a href="https://ph.shein.com/AXEPEAK-Hooded-Loose-Fit-Long-Sleeve-Sweatshirt-For-Men-For-Fall-Winter-p-108468941.html?src_identifier=st%3D2%60sc%3DHoodie%20For%20Men%60sr%3D0%60ps%3D1&src_module=search&src_tab_page_id=page_search1761540376520&pageListType=4&imgRatio=3-4&pageListType=4">
      <img src="Hood3.png" alt="AXEPEAK Hooded Loose Fit">
      <div class="product-info">
        <h3>AXEPEAK Hooded Loose Fit</h3>
        <p class="price">₱650</p>
      </div>
    </a>
    <button class="add-cart">🛒 Add to Cart</button>
  </div>

  <div class="product-card">
    <a href="https://ph.shein.com/SWAVVY-Men-s-Knit-Casual-Daily-Young-Loose-Patchwork-Long-Sleeve-Hoodie-For-Fall-Winter-p-47697468.html?src_identifier=st%3D2%60sc%3DHoodie%20For%20Men%60sr%3D0%60ps%3D1&src_module=search&src_tab_page_id=page_search1761542517309&pageListType=4&imgRatio=3-4&pageListType=4">
      <img src="Hood4.png" alt="SWAVVY Men's Hoodie">
      <div class="product-info">
        <h3>SWAVVY Men's Hoodie</h3>
        <p class="price">₱520</p>
      </div>
    </a>
    <button class="add-cart">🛒 Add to Cart</button>
  </div>

  <div class="product-card">
    <a href="https://ph.shein.com/INAWLY-Women-s-Black-Hooded-Sweatshirt-With-Van-Gogh-Starry-Sky-Print-Autumn-Winter-Graduation-Back-To-School-Outfits-Graduation-Teacher-Outfits-For-Women-Back-To-School-Pullover-Fall-Outfit-p-47519441.html?src_identifier=st%3D2%60sc%3Dinawly%20hoodie%60sr%3D0%60ps%3D1&src_module=search&src_tab_page_id=page_search1761545652483&pageListType=4&imgRatio=3-4&pageListType=4">
      <img src="Hood5.png" alt="INAWLY Women's Hooded">
      <div class="product-info">
        <h3>INAWLY Women's Hooded</h3>
        <p class="price">₱560</p>
      </div>
    </a>
    <button class="add-cart">🛒 Add to Cart</button>
  </div>

    <div class="product-card">
    <a href="https://ph.shein.com/Manfinity-Dauomo-Men-s-Casual-Solid-Color-Blank-Hoodie-Zip-Up-Sweatshirt-For-Fall-p-40648330.html?src_identifier=st%3D2%60sc%3Dplain%20hoodie%60sr%3D0%60ps%3D1&src_module=search&src_tab_page_id=page_search1761543681629&pageListType=4&imgRatio=3-4&pageListType=4">
      <img src="Hood6.png" alt="Chrxs Exclusive Hoodie">
      <div class="product-info">
        <h3>Chrxs Exclusive Hoodie</h3>
        <p class="price">₱560</p>
      </div>
    </a>
    <button class="add-cart">🛒 Add to Cart</button>
  </div>

    <div class="product-card">
    <a href="https://ph.shein.com/Manfinity-Dauomo-Men-s-Hooded-Long-Sleeve-Letter-Print-Fashionable-Loose-Style-Casual-Sweatshirt-For-Fall-Winter-p-39723429.html?imgRatio=3-4">
      <img src="Hood7.png" alt="Manfinity Dauomo Hoodie">
      <div class="product-info">
        <h3>Manfinity Dauomo Hoodie</h3>
        <p class="price">₱560</p>
      </div>
    </a>
    <button class="add-cart">🛒 Add to Cart</button>
  </div>

    <div class="product-card">
    <a href="https://ph.shein.com/Manfinity-EMRG-Men-s-Hooded-Sweatshirt-Distinctive-Pullover-Sporty-Casual-Streetwear-Star-Hoodie-Black-Graphic-Hoodie-Cropped-Hoodie-Graphic-Hoodie-Hoodie-Men-s-Cropped-Hoodie-Cropped-Hoodie-Hoodie-Black-Hoodie-p-144120027.html?src_identifier=st%3D2%60sc%3Dhoodie%60sr%3D0%60ps%3D1&src_module=search&src_tab_page_id=page_search1761545664840&pageListType=4&imgRatio=3-4&pageListType=4">
      <img src="Hood8.png" alt="Manfinity EMRG Hoodie">
      <div class="product-info">
        <h3>Manfinity EMRG Hoodie</h3>
        <p class="price">₱560</p>
      </div>
    </a>
    <button class="add-cart">🛒 Add to Cart</button>
  </div>
</div>
  
</body>
</html>
