# login-page
In Part II of our User Portal Series, we will walk you through building a login page. Your login page is the most frequented web page of your website so make it as intuitive and user friendly as possible. Solodev provides you with the code required to build an intuitive login page for your website.

## Tutorial

For detailed instructions, view Solodev's [Designing an Effective Login Page](https://www.solodev.com/blog/web-design/designing-an-effective-login-page.stml) article.

## Demo

Check out a working example on [JSFiddle](https://jsfiddle.net/solodev/zu78zywm/).

## HTML

The login page has the following basic HTML markup.
```
<div id="highlighted" class="hl-basic hidden-xs">
   <div class="container-fluid">
      <div class="row">
         <div class="col-sm-9 col-sm-offset-3 col-md-9 col-md-offset-3 col-lg-10 col-lg-offset-2">
            <h1>Login</h1>
         </div>
      </div>
   </div>
</div>
<div id="content" class="interior-page">
<div class="container-fluid">
<div class="row">
<!--Sidebar-->
<div class="col-sm-3 col-md-3 col-lg-2 sidebar equal-height interior-page-nav hidden-xs">
   <div class="dynamicDiv panel-group" id="dd.0.1.0">
      <div id="subMenu" class="panel panel-default">
         <ul class="subMenuHighlight panel-heading">
            <li class="subMenuHighlight panel-title" id="subMenuHighlight">
               <a id="li_291" class="subMenuHighlight" href=""><span>Register</span></a>
            </li>
         </ul>
         <ul class="panel-heading">
            <li class="panel-title">
               <a class="subMenu1" href=""><span>Forgot Password</span></a>
            </li>
         </ul>
         <ul class="panel-heading">
            <li class="panel-title">
               <a class="subMenu1" href=""><span class="subMenuHighlight">Login</span></a>
            </li>
         </ul>
      </div>
      <div class="item item-nopad item-noborder item-gold">
         <a style="padding: 5% 0px;" href="" class="btn btn-primary btn-block" role="button">LEARN MORE</a> 
      </div>
   </div>
</div>
<!--Content-->
<div class="col-sm-9 col-md-9 col-lg-10 content equal-height">
   <div class="content-area-right">
      <div class="content-crumb-div">
         <a href="">Home</a> / <a href="">Your Account</a> / Login
      </div>
      <div class="row row-divider">
         <div class="col-md-5">
            <form id="login-form">
               <p>
                  I am a returning guest
               </p>
               <label class="label-default" for="un">Username or Email Address</label> <input id="un" name="un" class="form-control" type="text"> <label class="label-default" for="pass">Password</label> <input id="pass" name="pass" class="form-control" type="password"><br>
               <a id="login" class="btn btn-primary login" role="button">LOGIN</a> 
            </form>
         </div>
         <div class="col-md-2"></div>
         <div class="col-md-5">
            <h3>
               To create an account
            </h3>
            <a href="" id="register" class="btn btn-primary register" role="button">REGISTER</a>
         </div>
      </div>    
   </div>
</div>
```

## CSS

All necessary CSS is in login.css

## External Includes
```
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
<link rel="stylesheet" href="login.css">
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>

```
