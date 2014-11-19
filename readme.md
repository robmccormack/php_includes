![](http://upload.wikimedia.org/wikipedia/en/1/1d/Confederation_college_logo.jpg)


---
##Mr. M.'s
# IM 315 Advanced PHP Includes

---
![](https://raw.githubusercontent.com/robmccormack/php_includes/master/ScreenShot.png)

---
Steps:

1. Duplicate this page as index.php  (you  have to use .php, since we'll be using PHP includes)
2. Create a folder called "/includes"  to hold the includes
3. Create a file called /includes/header.php with the header of this page
4. repeat above, for footer.php


At top of this index.php, use this
```php
<?php
$title = "BigSite.com .: HOME :.";
$showad = true;
include 'includes/header.php';
?>
```


5.  at bottom of this page use this
<?php include 'includes/footer.php'; ?>


7- Now create the pages..


8-  and fix this
<li class="current"><a href="index.html">Home</a></li>



HOME  

ABOUT

SERVICES

PROJECT

BLOG

CONTACT
