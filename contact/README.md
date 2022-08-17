# contact-form
In Part II of our series on Contact Us Page Designs, [Solodev](https://www.solodev.com/) will provide a mobile responsive contact us form for your website. Simply place the design between your header and footer and you've got a brand new contact us page!

## Tutorial

For detailed instructions, view Solodev's [Designing a Responsive Contact Us Page](https://www.solodev.com/blog/web-design/designing-a-responsive-contact-us-page.stml) article.

## Demo

Check out a working example on [JSFiddle](https://jsfiddle.net/solodev/em78hq4h/).

## HTML

The contact form has the following basic HTML markup.
```
<div class="container">
<div class="contact-section">
<h2 class="ct-section-head">
   CONTACT US
</h2>
<div class="row contact-fields">
<div class="col-md-8 left-form">
   <form method="post" action="">
      <div class="form-group">
         <label class="sr-only" for="fname">First Name *</label>
         <input class="required form-control" id="fname" name="fname" placeholder="First Name&nbsp;*" type="text">
      </div>
      <div class="form-group">
         <label class="sr-only" for="lname">Last Name *</label>
         <input class="required form-control" id="lname" name="lname" placeholder="Last Name&nbsp;*" type="text">
      </div>
      <div class="form-group">
         <label class="sr-only" for="contactEmail">Email *</label>
         <input class="required form-control h5-email" id="contactEmail" name="contactEmail" placeholder="Email&nbsp;*" type="text">
      </div>
      <div class="form-group">
         <label class="sr-only" for="contactPhone">Phone *</label>
         <input class="required form-control h5-phone" id="contactPhone" name="contactPhone" placeholder="Phone&nbsp;*" type="text">
      </div>
      <div class="form-group">
         <label class="sr-only" for="comment">Type your message here</label>
         <textarea class="required form-control" id="comment" name="comment" placeholder="Type your message here&nbsp;*" rows="6"></textarea>
      </div>
      <button class="btn btn-accent" type="submit">Submit</button>  
   </form>
</div>
<div class="col-md-4 contact-info">
<div class="phone">
   <h2>Call</h2>
   <a href="tel:+4046872730">555.555.5555</a>
</div>
<div class="email">
   <h2>Email</h2>
   <a href="mailto:info@decidedekalb.com">info@webcorpco.com</a>
</div>
<div class="location">
   <h2>Visit</h2>
   <p>One Town Center </br>
      123 Easy Street </br>
      Suite 1000 </br>
      Orlando, FL 32803
      <br>
      <a class="btn btn-accent" href="" target="_blank"><img src="https://www.solodev.com/assets/contact-us-page/map-marker.png" alt="Map Marker">Google Maps</a>
   </p>
</div>
```
## CSS

All necessary CSS is in contact-form.css

## External Includes
```
<link href="https://fonts.googleapis.com/css?family=Oswald" rel="stylesheet">
<link href="https://fonts.googleapis.com/css?family=Raleway" rel="stylesheet">
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
<link rel="stylesheet" href="contact-form.css">

<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
```
