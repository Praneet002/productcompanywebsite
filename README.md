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
    <title>AutoDesk</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/Contact.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="./img/images.jpg" alt="Building" />
          <div class="contenttext">
            Autodesk is changing how the world is designed and made.
From greener buildings to smarter products to mesmerizing blockbusters, Autodesk software helps our customers to design and make a better world for all.
            <br />
            Autodesk mission is to empower innovators with design and make technology so they can achieve the new possible.
Our technology spans architecture, engineering and construction, product design and manufacturing, and media and entertainment, empowering innovators everywhere to solve challenges big and small.
            <ul>
              <li>Simple to learn, easier to use</li>
              <li>Insightful , actionable & customizable reports</li>
              <li>Anywhere, anytime and secure access</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 AutoDesk, Developed by Praneet.
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
    <title>Autodesk</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/images.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected">
          <a href="/static/products.html">Products</a>
        </div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/Contact.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Premium Products</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/images (4).png" alt="product image">
                  </div>
                  <div class="itemname">AUTODESK SMOKE</div>
                  <div class="itemprice">Price: Rs.40,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/images (3).png"  alt="product image">
                  </div>
                  <div class="itemname">AUTOCAD MAP 3D</div>
                  <div class="itemprice">Price: Rs.10,000.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/images (2).jpg" alt="product image">
                </div>
                <div class="itemname">AUTODESK MAYA</div>
                <div class="itemprice">Price: Rs.60,000.00 </div>
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="/static/img/images (1).png"  alt="product image">
              </div>
              <div class="itemname">AUTOCAD NAVISWORKS</div>
              <div class="itemprice">Price: Rs.10,000.00 </div>
          </div>
          <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/images (3).jpg" alt="product image">
            </div>
            <div class="itemname">AUTODESK EAGLE</div>
            <div class="itemprice">Price: Rs.60,000.00 </div>
          </div>
          <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/images (1).jpg" alt="product image">
            </div>
            <div class="itemname">AUTODESK FUSION 360</div>
            <div class="itemprice">Price: Rs.60,000.00 </div>
          </div>
          <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/images(4).jpg" alt="product image">
            </div>
            <div class="itemname">AUTODESK ARNOLD</div>
            <div class="itemprice">Price: Rs.80,000.00 </div>
          </div>         
        <div class="productitem"> 
          <div class="itemimage">
          <img src="/static/img/images(5).jpg" alt="product image">
          </div>
          <div class="itemname">AUTODESK MAYA</div>
          <div class="itemprice">Price: Rs.86,000.00 </div>
        </div>         
        <div class="productitem"> 
          <div class="itemimage">
          <img src="/static/img/image(9).jpg" alt="product image">
          </div>
          <div class="itemname">AUTODESK INVENTOR</div>
          <div class="itemprice">Price: Rs.96,000.00 </div> 
        </div> 
          <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/image(10).png" alt="product image">
            </div>
            <div class="itemname">AUTODESK REVIT</div>
            <div class="itemprice">Price: Rs.96,000.00 </div>
          </div>    
            <div class="productitem"> 
              <div class="itemimage">
              <img src="/static/img/images(12).png" alt="product image">
              </div>
              <div class="itemname">AUTODESK POWERMILL</div>
              <div class="itemprice">Price: Rs.96,000.00 </div>
            </div>   
              <div class="productitem">
                <div class="itemimage">
                <img src="/static/img/1.jpg" alt="product image">
              </div>
              <div class="itemname">AUTODESK VAULT</div>
              <div class="itemprice">Price: Rs.96,000.00 </div>
                </div>
              </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 AutoDesk, Developed by Praneet.
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
    <title>Autodesk</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/images.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem">
          <a href="/static/products.html">Products</a>
        </div>
        <div class="menuitemselected"><a href="/static/people.html">people</a></div>
        <div class="menuitem"><a href="/static/Contact.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Team Members</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/2.jpg" alt="product image">
                  </div>
                  <div class="itemname">ELON MUSK</div>
                  <div class="itemprice">CEO </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/3.jpg"  alt="product image">
                  </div>
                  <div class="itemname">JEFF BEZOS</div>
                  <div class="itemprice">PRESIDENT </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/4.jpg" alt="product image">
                </div>
                <div class="itemname">MARK</div>
                <div class="itemprice">VICE PRESIDENT </div>
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="/static/img/5.jpg"  alt="product image">
              </div>
              <div class="itemname">ANTONY STARK</div>
              <div class="itemprice">AI SPECIALIST </div>
          </div>
          <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/6.jpg" alt="product image">
            </div>
            <div class="itemname">TOM HOLLAND</div>
            <div class="itemprice">WEB DESIGNER </div>
          </div>
          <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/7.jpg" alt="product image">
            </div>
            <div class="itemname">NICK FURY</div>
            <div class="itemprice">CHAIRMAN </div>
          </div>
          
                </div>
              </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 AutoDesk, Developed by Praneet.
      </div>
    </div>
  </body>
</html>
~~~
### Contact Page:
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>AutoDesk</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>
<body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitemselected"><a href="/static/Contact.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>For Further Details:</h1>
          <img src="/static/img/8.png" alt="BUILDING">
          <div class="contenttext">
            ADDRESS
            Worldwide Headquarters
            Autodesk, Inc.
            111 McInnis Parkway
            San Rafael, CA 94903
            USA



            <br>
            Contact NO: 112345908234
            <br>
            Landline: 044 2355 8976
            <br>
            Our Email: autodesk@gmail.com
        </div>
    </div>
  </div>
  <div class="footer">
    Copyright &#169; 2021 AutoDesk, Developed by PRANEET.S
  </div>
</div>
</body>
</html>
~~~

## OUTPUT:

### Home Page:

![output](./images/9.png)

### Product Page:

![output](./images/10.png)

![output](./images/11.png)

### People Page:

![output](./images/12.png)

### Contact Page:

![output](./images/13.png)



## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
