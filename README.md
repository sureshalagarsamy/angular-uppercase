# Convert Text To Uppercase Using AngularJS

AngularJS provides a feature for converting all the letters of text into uppercase letters.

```html
<!DOCTYPE html>
<html>
<head>
	<meta charset="UTF-8">
	<title>AngularJS sample application</title>
	<link rel="shortcut icon" href="images/icon.png" />
	<link rel="stylesheet" href="css/styles.css">
	
	<script src="js/angular-1.5.4.js"></script>
</head>

<body ng-app>
	<p>Name : <input type="text" ng-model="name"></p>
	<h1>Hello {{name | uppercase}}</h1>
</body>

</html>
```

![image](https://user-images.githubusercontent.com/6780840/27904833-a9c2dca6-625b-11e7-8849-57235b56ba5b.png)
