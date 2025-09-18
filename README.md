# MESUK

## PHP

### เชื่อมต่อฐานข้อมูล frontend
``` php
<?php
  	// include ที่ต้องมี
	include("connect.php"); //เชื่อมต่อฐานข้อมูล
	include("Function/runnig.php");
	include("Function/SQLADMIN.php");
	include("Function/showdate.php");

  	$tUserName=$_SESSION['USERLOGIN']; // ชื่อผู้ใช้

?>
```

### เชื่อมต่อฐานข้อมูล backend
``` php
<?php
include("../connect.php");
?>
```

### Query แสดงข้อมูล นับจำนวน
``` php
$objQuery = mysql_query($strSQL);
$Num_Rows = mysql_num_rows($objQuery);
```




