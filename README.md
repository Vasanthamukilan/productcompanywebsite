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
```html
HOME .HTML
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>EduSoft Private Limited</title>
    <link rel="stylesheet" href="/static/layout.css">
    <link rel="icon" href="./img/icon.png" type="image/x-icon">
  </head>

  <body>
    <div class="container">
      <div class="banner">EduSoft Private Limited.</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/home/">Home</a></div>
        <div class="menuitemselected"><a href="/products/">Products</a></div>
        <div class="menuitemselected"><a href="/people/">People</a></div>
        <div class="menuitemselected"><a href="/contactus/">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          
          <div class="contenttext">
            At Edusoft, we understand the importance of technology in enhancing business efficiency and empowering 
            entrepreneurs. That's why we design our products to be user-friendly and adaptable to your specific needs.
            Our latest offering, Edusoft Prime, takes this to the next level by making the 
            transition to automation and our platform simpler than ever before.
            With an intuitive interface and customizable features, you can easily discover the 
            full potential of the product without needing to learn any new skills.
            Edusoft Prime adapts to your unique business and working style,
            providing greater flexibility and a transformed look and feel
            that will make you love it even more.

            Our new product takes this to a new level, making your
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
        Copyright &#169; 2023 EduSoft Private Limited, Developed by Priyanka.A
      </div>
    </div>
  </body>
</html>

PRODUCTS.HTML


<!DOCTYPE html>
<html lang="en">
  <head>
    <title>EduSoft Private Limited</title>
     <link rel="stylesheet" href="/static/layout.css">
    <link rel="icon" href="/static/icon.png" type="image/x-icon">
    
  </head>

  <body>
    <div class="container">
      <div class="banner">EduSoft Private Limited.</div>
      <div class="menu">
     <div class="menuitemselected"><a href="/home/">Home</a></div>
        <div class="menuitemselected"><a href="/products/">Products</a></div>
        <div class="menuitemselected"><a href="/people/">People</a></div>
        <div class="menuitemselected"><a href="/contactus/">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Premium Products</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/book12.jpeg" alt="product image">
                  </div>
                  <div class="itemname">Educated</div>
                  <div class="itemprice">Price: Rs.200 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/book2.jpeg"  alt="product image">
                  </div>
                  <div class="itemname">End of Watch</div>
                  <div class="itemprice">Price: Rs.350 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/book3.png" alt="product image">
                  </div>
                  <div class="itemname">The Mind of a Leader</div>
                  <div class="itemprice">Price: Rs.450 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/book4.png" alt="product image">
                  </div>
                  <div class="itemname">The Domestic Goddess</div>
                  <div class="itemprice">Price: Rs.290 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/book5.jpeg" alt="product image">
                  </div>
                  <div class="itemname">The Book Title</div>
                  <div class="itemprice">Price: Rs.500 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/book6.png" alt="product image">
                  </div>
                  <div class="itemname">Memory</div>
                  <div class="itemprice">Price: Rs.440 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/book7.jpeg" alt="product image">
                  </div>
                  <div class="itemname">Spiral</div>
                  <div class="itemprice">Price: Rs.300 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/book8.jpeg" alt="product image">
                  </div>
                  <div class="itemname">Small Blessings</div>
                  <div class="itemprice">Price: Rs.420 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/book9.jpeg" alt="product image">
                  </div>
                  <div class="itemname">Heart Spring Mountain</div>
                  <div class="itemprice">Price: Rs.280 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/book10.jpeg" alt="product image">
                  </div>
                  <div class="itemname">Needful Things</div>
                  <div class="itemprice">Price: Rs.400 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/book11.jpeg" alt="product image">
                  </div>
                  <div class="itemname">I Remember You</div>
                  <div class="itemprice">Price: Rs.250 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/book1.jpeg" alt="product image">
                  </div>
                  <div class="itemname">Another Side of the Moon</div>
                  <div class="itemprice">Price: Rs.370 </div>
              </div>
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2023 EduSoft Private Limited, Developed by Priyanka.
      </div>
    </div>
  </body>
</html>

PEOPLE.HTML

<!DOCTYPE html>
<html lang="en">
  <head>
    <title>EduSoft Private Limited</title>
    
     <link rel="stylesheet" href="/static/layout.css">
    <link rel="icon" href="/static/icon.png" type="image/x-icon">
    
  </head>

  <body>
    <div class="container">
      <div class="banner">EduSoft Private Limited.</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/home/">Home</a></div>
        <div class="menuitemselected"><a href="/products/">Products</a></div>
        <div class="menuitemselected"><a href="/people/">People</a></div>
        <div class="menuitemselected"><a href="/contactus/">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>PEOPLE AT EDUSOFT</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/people1.jpg" alt="product image">
                  </div>
                  <div class="itemname">Benjamin</div>
                  <div class="itemprice">Managing Director </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/people2.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Jonathan</div>
                  <div class="itemprice">Co-founder and Chairman of the Board </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/people3.jpg" alt="product image">
                  </div>
                  <div class="itemname">Daniel</div>
                  <div class="itemprice">Lead Independent Director </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/people4.jpg" alt="product image">
                  </div>
                  <div class="itemname">Ethan</div>
                  <div class="itemprice">Independent Director India </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/people5.jpg" alt="product image">
                  </div>
                  <div class="itemname">Michael</div>
                  <div class="itemprice">Independent Director </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/people6.jpg" alt="product image">
                  </div>
                  <div class="itemname">Charlotte</div>
                  <div class="itemprice">Independent Director</div>
              </div>
             
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2023 EduSoft Private Limited, Developed by B.Mohamed Athil.
      </div>
    </div>
  </body>
</html>

CONTACTUS.HTML

<!DOCTYPE html>
<html lang="en">
  <head>
    <title>EduSoft Private Limited</title>
   <link rel="stylesheet" href="/static/layout.css">
    <link rel="icon" href="/static/icon.png" type="image/x-icon">
     
  </head>

  <body>
    <div class="container">
      <div class="banner">EduSoft Private Limited.</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/home/">Home</a></div>
        <div class="menuitemselected"><a href="/products/">Products</a></div>
        <div class="menuitemselected"><a href="/people/">People</a></div>
        <div class="menuitemselected"><a href="/contactus/">Contact Us</a></div>
      </div>
      <div class="content">
          
            <h1>Contact Us</h1>
  <p>If you have any questions or feedback, please don't hesitate to reach out to us.</p>
  <ul>
    <li>Address: 123 Main Street,Buckingham,UK</li>
    <li>Phone: +91 8765432109</li>
    <li>Email: contact@edusoft.com</li></ul>
  
<h2> Sales Inquiries</h2>

<ul><li>UK 1800 103 11231800 572 3535</li></ul>
    <h2>Press Inquiries</h2> 
<ul><li>press@edusoft.com</li>

<li>Hannah</li>
<li>hannah@edusoft.com</li></ul>
    <h2>Analyst Relations</h2> 

    <ul><li>Sandra</li>
    <li>+1-925-924-9500</li>
    <li>pr@edosoft.com</li></ul>
        <h2>Customer Relations</h2> 

    <ul><li>Anderson</li>
    <li>Director of Sales & Customer Service</li>
    <li>anderson@edusoft.com</li>
    </ul>
    
  </div>
   <div class="footer">
        Copyright &#169; 2023 EduSoft Private Limited, Developed by B.Mohamed Athil.
      </div>
      </div>
</body>
</html>
```
## About us:
!['output'](/About.png)
## Product:
!['output'](/Product1.png)
!['output'](/Product2.png)
## Contact us:
!['output'](/Contact1.png)
!['output'](/Contact2.png)
## People:
!['output'](/People.png)
## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
