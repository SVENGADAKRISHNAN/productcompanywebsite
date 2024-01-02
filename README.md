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

    Banner was changed.
    12 products (tally books) were added.
    6 users were added to the staff page.
    Contact address, email were added in the contact us section.

### Step 4:

Choose the appropriate style and color scheme.
--> The Color scheme used in this website was a combination of yellow and light blue for content area, and a dark blue colour for menu text and footer text.

### Step 5:

Validate the layout in various browsers.

### Step 6:

Validate the HTML code.

### Step 6:

Publish the website in the given URL.

## PROGRAM :
  ### CSS LAYOUT CODE :
  * {
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
}
body {
  background-color: whitesmoke;
  color: #20df39;
}
.container {
  width: 1080px;
  margin-left: auto;
  margin-right: auto;
  border-width: 1px 1px 1px 1px;
  border-style: solid;
  box-shadow: 15px 15px 8px gray;
}

.banner {
  display: block;
  width: 100%;
  height: 250px;
  text-align: center;
  font-size: 60px;
  background-image: url("");
  background-size: 100% 100%;
  margin: 0px 0px 0px 0px;
  padding-top: 150px;
  color: #7ccf10;
}

.menu {
  display: block;
  width: 100%;
  height: 50px;
  font-size: larger;
  background-color: #5bb045;
  text-align: center;
  padding-top: 15px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
}

.menuitem {
  display: inline-block;
  margin-left: 10px;
  margin-right: 10px;
}
.menuitemselected {
  display: inline-block;
  margin-left: 10px;
  margin-right: 10px;
  color: #a34cb4;
}

.menuitem a {
  text-decoration: none;
  color: #9c1018;
}

.content {
  display: block;
  width: 100%;
  background-color: #cffffd;
  min-height: 500px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
  border-color: white;
  border-style: solid;
}
.homecontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}
.homecontent h1 {
  text-align: left;
}
.homecontent img {
  float: right;
  width: 400px;
  height: 300px;
  margin-left: 10px;
}

.contenttext {
  text-align: justify;
}

.productcontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}

.productcontent h1 {
  text-align: left;
}

.productitems {
  display: block;
}

.productitem {
  display: inline-block;
  width: 30%;
  height: 250px;
  text-align: center;
}

.productitem img {
  width: 100px;
  height: 100px;
  display: block;
}
.productitem .itemimage {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 100px;
  margin-bottom: 5px;
}

.productitem .itemname {
  display: block;
}
.productitem .itemprice {
  display: block;
}

.footer {
  display: block;
  width: 100%;
  height: 40px;
  background-color: #5bb045;
  text-align: center;
  padding-top: 10px;
  margin: 0px 0px 0px 0px;
  color: #9c1018;
}
## HTML CODE:
 ### 1.home.html:
 <!DOCTYPE html>
<html lang="en">
  <head>
    <title>EduSoft Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">EduSoft Private Limited.</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href = "/static/people.html">People</a></div>
        <div class="menuitem"><a href = "/static/contactus.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="./img/building.png" alt="Building" />
          <div class="contenttext">
            At Edusoft, we take pride in being a leading provider of high-quality
            tally books that cater to a diverse range of industries and professionals.
            Our commitment to excellence, innovation, and customer satisfaction 
            sets us apart in the market, making us your go-to destination for all 
            your tally book needs.
            <br />
            Why Choose Edusoft?
            <ul>
              <li>Quality Assurance: Our tally books undergo rigorous quality checks to ensure accuracy and durability.</li>
              <li>Innovation: We embrace new technologies and offer customizable solutions to streamline your work.</li>
              <li>Customer-Centric: Your satisfaction is our priority.</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2023 EduSoft Private Limited, Developed by S.VENGADA KRISHNAN
      </div>
    </div>
  </body>
</html>

 ### 2.products.html
 
 <!DOCTYPE html>
<html lang="en">
  <head>
    <title>EduSoft Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">EduSoft Private Limited.</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected">
          <a href="/static/products.html">Products</a>
        </div>
        <div class="menuitem"><a href = "/static/people.html">People</a></div>
        <div class="menuitem"><a href = "/static/contactus.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Premium Products</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/redmi.jpeg" alt="product image" >
                  </div>
                  <div class="itemname">Redmi note 12</div>
                  <div class="itemprice">Price: Rs.20,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/oneplus.jpeg"  alt="product image">
                  </div>
                  <div class="itemname">Oneplus 9 pro</div>
                  <div class="itemprice">Price: Rs.50,000.00 </div>  
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/iphone 14 .jpeg"  alt="product image">
                </div>
                <div class="itemname">Iphone 14 pro</div>
                <div class="itemprice">Price: Rs.150,000.00 </div>  
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/pixel 8 pro.jpeg"  alt="product image">
                </div>
                <div class="itemname">Pixel 8 pro</div>
                <div class="itemprice">Price: Rs.115,000.00 </div>  
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/s23 ultra.jpeg"  alt="product image">
                </div>
                <div class="itemname">S23 ultra</div>
                <div class="itemprice">Price: Rs.135,000.00 </div>  
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/oneplus 12.jpeg"  alt="product image">
                </div>
                <div class="itemname">Oneplus 12</div>
                <div class="itemprice">Price: Rs.65,000.00 </div>  
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/13 mini.jpeg"  alt="product image">
                </div>
                <div class="itemname">Iphone 13 mini</div>
                <div class="itemprice">Price: Rs.45,000.00 </div>  
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/s22 plus.jpeg"  alt="product image">
                </div>
                <div class="itemname">S22 plus</div>
                <div class="itemprice">Price: Rs.95,000.00 </div>  
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/plus.jpeg"  alt="product image">
                </div>
                <div class="itemname">Iphone 8 plus</div>
                <div class="itemprice">Price: Rs.105,000.00 </div>  
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/10r.jpeg"  alt="product image">
                </div>
                <div class="itemname">Oneplus 10r</div>
                <div class="itemprice">Price: Rs.45,000.00 </div>  
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/15 pro.jpeg"  alt="product image">
                </div>
                <div class="itemname">Iphone 15 pro max</div>
                <div class="itemprice">Price: Rs.160,000.00 </div>  
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/iphonw.jpeg"  alt="product image">
                </div>
                <div class="itemname">Iphone 15 plus</div>
                <div class="itemprice">Price: Rs.95,000.00 </div>  
              </div>
          </div>
          </div>        
      <div class="footer">
        Copyright &#169; 2023 EduSoft Private Limited, Developed by S.VENGADA KRISHNAN
      </div>
    </div>
    </div>
  </body>
</html>

### 3.people.html:
<!DOCTYPE html>
<html lang="en">
<head>
  <title>EduSoft Private Limited</title>
  <link rel="stylesheet" href="./css/layout.css" />
  <link rel="icon" href="./img/icon.png" type="image/x-icon" />
</head>
<body>
  <div class="container">
    <div class="banner">EduSoft Private Limited.</div>
    <div class="menu">
      <div class="menuitem"><a href="/static/home.html">Home</a></div>
      <div class="menuitem"><a href="/static/products.html">Products</a></div>
      <div class="menuitemselected"><a href = "/static/people.html">People</a></div>
      <div class="menuitem"><a href = "/static/contactus.html">Contact Us</a></div>
    </div>
  <div class="content">
    <div class="productcontent">    
      <h1>Our Staff !!</h1>
      <div class="productitems">
          <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/p1.jpeg"  alt="product image">
            </div>
            <div class="itemname">VK - CEO</div> 
          </div>
          <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/p2.jpeg"  alt="product image">
            </div>
            <div class="itemname">person-2 - Head developer</div>
          </div>
          <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/p3.jpeg"  alt="product image">
            </div>
            <div class="itemname">person-3 - HR</div>
          </div>
          <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/p4.jpeg"  alt="product image">
            </div>
            <div class="itemname">person-4 - Project manager</div>  
          </div>
          <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/p5.jpeg"  alt="product image">
            </div>
            <div class="itemname">person-5 - Receptionist</div>  
          </div>
          <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/p6.jpeg"  alt="product image">
            </div>
            <div class="itemname">person-6 - Salesman</div>
          </div>
      </div>
    </div>        
  </div>
  <div class="footer">
      Copyright &#169; 2023 EduSoft Private Limited, Developed by S.VENGADA KRISHNAN
  </div>
  </div>
  </body>
  </html>

  ### 4.contactus.html:
  <!DOCTYPE html>
<html lang="en">
<head>
  <title>EduSoft Private Limited</title>
  <link rel="stylesheet" href="./css/layout.css" />
  <link rel="icon" href="./img/icon.png" type="image/x-icon" />
</head>
<body>
  <div class="container">
    <div class="banner">EduSoft Private Limited.</div>
    <div class="menu">
      <div class="menuitem"><a href="/static/home.html">Home</a></div>
      <div class="menuitem"><a href="/static/products.html">Products</a></div>
      <div class="menuitem"><a href = "/static/people.html">People</a></div>
      <div class="menuitemselected"><a href = "/static/contactus.html">Contact Us</a></div>
    </div>
  <div class="content">
      <div class="contactcontent">
        <h1>Contact Us</h1>
        <img src="./img/building.png" alt="Building" />
        <div class="contcontenttext">
                    We value your interest in Edusoft. If you want any kind of assistance regarding our services, reach out to us !!
          <br>
          <br>
          <b><u>Contact Information:</u></b>
          <br>
          <b><u>Email --></u></b> edusoft.help@gmail.com<br><br>

          Feel free to reach out to us via email at the address provided above.<br><br>

          <b><u>Office Address:</u></b><br>

          <b><i>*****Edusoft Private Limited*****</i></b><br>

                                                                      <pre>                                                             42 Wallaby Way, Sydney, Australia<br></pre>

                                                                      <b><u>Customer Support</u></b><br><br>

                                                                      For technical support or assistance with our products and services, please contact our support team at <u>edusoft.help@gmail.com</u>.<br><br>

                                                                      <b><u>Feedback and Suggestions:</u></b><br><br>

                                                                      We appreciate your feedback and suggestions. Feel free to share your thoughts by emailing us at edusoft.help@gmail.com.<br><br>

                                                                      <b> Thank you for choosing Edusoft Private Limited. We look forward to hearing from you and assisting you on your educational journey!</b>
        </div>
      </div>
    </div>
  <div class="footer">
      Copyright &#169; 2023 EduSoft Private Limited, Developed by S.VENGADA KRISHNAN
  </div>
  </div>
</body>
</html>

## OUTPUT:
### 1.home page:

![Screenshot from 2024-01-02 09-51-53](https://github.com/SVENGADAKRISHNAN/productcompanywebsite/assets/147473084/d073ba09-cf30-4495-83fd-f7f6bc61582e)

### 2.product page:


![Screenshot from 2024-01-02 09-52-06](https://github.com/SVENGADAKRISHNAN/productcompanywebsite/assets/147473084/46b14f8a-ecf3-4729-bc80-926a8c824ba2)

### 3.people page:

![Screenshot from 2024-01-02 09-52-14](https://github.com/SVENGADAKRISHNAN/productcompanywebsite/assets/147473084/8fa594bd-3ef6-4c0f-ac39-7b10448b1868)

### 4.contact us page:


![Screenshot from 2024-01-02 09-52-23](https://github.com/SVENGADAKRISHNAN/productcompanywebsite/assets/147473084/e1099342-1b6c-412f-9495-04ac266c0d63)

## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
