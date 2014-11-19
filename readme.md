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

and write out the variable $myTitle in <title> tag,
AND
on the main content part of the page.


```php
<?php
$myTitle = "HOME";
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


```php
<?php
$title = "HOME";
$showad = true;
include 'includes/header.php';
?>
```

---
#Simple PHP code examples



## echo
```php

<?php
  echo "Hello World";
}

?>


```


## Conditional
```php

<?php

if ($Name == "Bob") {
  echo "Have a good day Bob!";
}

?>


```


## Select
```php
<?php
$favcolor = "red";

switch ($favcolor) {
  case "red":
  echo "Your favorite color is red!";
  break;
  case "blue":
  echo "Your favorite color is blue!";
  break;
  case "green":
  echo "Your favorite color is green!";
  break;
  default:
  echo "Your favorite color is neither red, blue, or green!";
}
?>

```
