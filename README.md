# Web Design for a Software Product Company

## AIM:

To design a static website for a software product company company.

## DESIGN STEPS:

### Step 1:

Requirement collection.

### Step 2:

Creating the layout using HTML and CSS.

### Step 3:

Updating the sample content.

### Step 4:

Choose the appropriate style and color scheme.

### Step 5:

Validate the layout in various browsers.

### Step 6:

Validate the HTML code.

### Step 6:

Publish the website in the given URL.

## PROGRAM :

### Home Page:
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>AMAR PRIVATE LIMITED.</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">AMAR PRIVATE LIMITED</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a>People</a></div>
        <div class="menuitem"><a>Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="./img/FG.png" alt="Building" />
          <div class="contenttext">
            At Tally, we believe in the power of technology to make business
            owners efficient, empowered and happier, so they can focus on what
            matters most for their business. We design our products to focus on
            just that to make our products work for you, and not the other way
            around.
            <br />
            Our new product TallyPrime takes this to a new level, making your
            start to automation, or your switch to Tally simpler than ever
            before. You can now discover the product much more easily and make
            the product do more for you, without learning anything new. There is
            greater flexibility as the product adapts to your business and your
            way of working. And the transformed look and feel will only make you
            love the product even more.
            <ul>
              <li>Simple to learn, easier to use</li>
              <li>Insightful , actionable & customizable reports</li>
              <li>Anywhere, anytime and secure access</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 AMAR PRIVATE LIMITED, Developed by Amarnath.
      </div>
    </div>
  </body>
</html>
~~~

### Product Page:
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>AMAR PRIVATE LIMITED.</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/ico.jpeg" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">AMAR PRIVATE LIMITED.</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/People.html">People</a></div>
        <div class="menuitem"><a href="/static/contact us.html">contact us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Premium Products</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="https://c1.neweggimages.com/ProductImage/83-360-190-01.jpg" alt="product image">
                  </div>
                  <div class="itemname">Draft 6000</div>
                  <div class="itemprice">Price: Rs.90,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="https://media.wired.com/photos/5ed56dac0164ade5f2950d7f/125:94/w_2375,h_1786,c_limit/Gear-Buying-Guide-HP-Omen-Desktop-SOURCE-HP.jpg"  alt="product image">
                  </div>
                  <div class="itemname">AMIS 5000</div>
                  <div class="itemprice">Price: Rs.40,000.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="https://www.techquila.co.in/wp-content/uploads/2019/10/antec-nx300-white-argb.jpg"  alt="product image">
                </div>
                <div class="itemname">FXG3000</div>
                <div class="itemprice">Price: Rs.55,000.00 </div>
             </div>
             <div class="productitem"> 
              <div class="itemimage">
              <img src="https://www.xda-developers.com/files/2021/11/Skytech-Shiva-Gaming-Desktop.jpg"  alt="product image">
              </div>
              <div class="itemname">Zominic</div>
              <div class="itemprice">Price: Rs.70,000.00 </div>
             </div>
           <div class="productitem"> 
            <div class="itemimage">
            <img src="https://www.gamingscan.com/wp-content/uploads/2020/09/Cheap-Gaming-PC-Under-500-1200x900.jpg"  alt="product image">
            </div>
            <div class="itemname">BS7600 </div>
            <div class="itemprice">Price: Rs.60,000.00 </div>
           </div>
           <div class="productitem"> 
            <div class="itemimage">
            <img src="https://www.newegg.com/insider/wp-content/uploads/2018/09/FSP-CMT520-CASE-3-1024x576.jpg"  alt="product image">
            </div>
            <div class="itemname">Zominic 300</div>
            <div class="itemprice">Price: Rs.70,000.00 </div>
        </div>
        <div class="productitem"> 
          <div class="itemimage">
          <img src="/static/img/ASUS.png" alt="product image">
          </div>
          <div class="itemname">Drfts 567</div>
          <div class="itemprice">Price: Rs.61,000.00 </div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSrpOVAt-3poeXnrCaBoU7-Ug5ekxZj61iZ6Q&usqp=CAU" alt="product image">
        </div>
        <div class="itemname">Dawns</div>
        <div class="itemprice">Price: Rs.99,000.00 </div>
    </div>
    <div class="productitem"> 
      <div class="itemimage">
      <img src="https://5.imimg.com/data5/LI/DR/ZV/SELLER-9654901/dvr-adapter-500x500.jpg" alt="product image">
      </div>
      <div class="itemname">HYPER 4300</div>
      <div class="itemprice">Price: Rs.50,999.00 </div>
   </div>
  <div class="productitem"> 
    <div class="itemimage">
    <img src=" https://assets1.ignimgs.com/2020/07/29/budget-gaming-pc-1596057852331_160w.jpg?width=1280"  alt="product image">
    </div>
    <div class="itemname">TA47GH</div>
    <div class="itemprice">Price: Rs.19,999.00 </div>
  </div>
  <div class="productitem"> 
    <div class="itemimage">
    <img src="https://cdn1.dotesports.com/wp-content/uploads/2021/11/19140651/MXZ-Gaming-PC-Entry-Level.jpg" alt="product image">
    </div>
    <div class="itemname">SPERO RT7000</div>
    <div class="itemprice">Price: Rs.80,000.00 </div>
</div>
<div class="productitem"> 
  <div class="itemimage">
  <img src="https://www.gamespot.com/a/uploads/square_medium/1701/17013431/3919288-3orion3000.jpg" alt="product image">
  </div>
  <div class="itemname">SPERO GT6888</div>
  <div class="itemprice">Price: Rs.30,000.00 </div>
</div>
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2021 AMAR PRIVATE LIMITED., Developed by Amarnath.
      </div>
    </div>
  </body>
</html>
~~~
### People Page:
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>AMAR Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">AMAR Private Limited.</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem">
          <a href="/static/products.html">Products</a>
        </div>
        <div class="menuitemselected"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contactus.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Council Members</h1>
          <div class="productitem"> 
            <div class="itemimage">
            <img src="https://upload.wikimedia.org/wikipedia/commons/1/18/Mark_Zuckerberg_F8_2019_Keynote_%2832830578717%29_%28cropped%29.jpg"  alt="product image">
            </div>
            <div class="itemname">Mark Zucekrberg</div>
            <div class="itemprice">CEO</div>
        </div>
          <div class="productitem"> 
          <div class="itemimage">
          <img src="https://pbs.twimg.com/profile_images/864282616597405701/M-FEJMZ0_400x400.jpg"  alt="product image">
          </div>
          <div class="itemname">Sundhar Pichai</div>
          <div class="itemprice">MD</div>
        </div>
        <div class="productitem"> 
          <div class="itemimage">
          <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/78/MS-Exec-Nadella-Satya-2017-08-31-22_%28cropped%29.jpg/1200px-MS-Exec-Nadella-Satya-2017-08-31-22_%28cropped%29.jpg"  alt="product image">
          </div>
          <div class="itemname">Satya Nadella</div>
          <div class="itemprice">VP of Marketing</div>
        </div>
        <div class="productitem"> 
          <div class="itemimage">
          <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/01/Shantanu_Narayen_-_the_CEO_of_Adobe_Inc.jpg/1200px-Shantanu_Narayen_-_the_CEO_of_Adobe_Inc.jpg"  alt="product image">
          </div>
          <div class="itemname">Shantanu Narayen</div>
          <div class="itemprice">Cheif Architect</div>
        </div>
        
      <div class="productitem"> 
        <div class="itemimage">
        <img src="https://thumbor.forbes.com/thumbor/fit-in/416x416/filters%3Aformat%28jpg%29/https%3A%2F%2Fspecials-images.forbesimg.com%2Fimageserve%2F5c7d7829a7ea434b351ba0b6%2F0x0.jpg%3Fbackground%3D000000%26cropX1%3D206%26cropX2%3D2043%26cropY1%3D250%26cropY2%3D2089"  alt="product image">
        </div>
        <div class="itemname">Mukesh Ambani</div>
        <div class="itemprice">Project Manager</div>
      </div>
      <div class="productitem"> 
      <div class="itemimage">
      <img src="https://upload.wikimedia.org/wikipedia/commons/f/ff/Gautam_Adani.jpg"  alt="product image">
      </div>
      <div class="itemname">Gautham Adani</div>
      <div class="itemprice">Technical Lead</div>
      </div>
      </div>
          </div>        
        </div>
      <div class="footer">
        Copyright &#169; 2021 AMAR Private Limited, Developed by Amarnath.
      </div>
    </div>
  </body>
</html>
~~~

### Contact Us Page:
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>AMAR Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">AMAR Private Limited.</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitemselected"><a href="/static/contactus.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>Contact Us</h1>
          <img src="./img/FG.png" alt="Building" />
          <div class="contenttext">
            Email: amarpvtltd@gmail.com
            <br>
            Phone: +919123456789
            <br>
            Address: New mark road , Gandhi Nagar , Mumbai 400004

          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 AMAR Private Limited, Developed by Amarnath.
      </div>
    </div>
  </body>
</html>
~~~

## OUTPUT:

### Home Page:


## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
