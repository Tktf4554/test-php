<?php

require_once('connections/mysqli.php');



session_start();



if ($_SESSION != NULL) {

  $strSQL = "SELECT * FROM tb_member WHERE member_username = '".$_SESSION['member_username']."'";

  $objQuery = mysqli_query($Connection,$strSQL);

  $objResult = mysqli_fetch_array($objQuery,MYSQLI_ASSOC);

}

?>

<!DOCTYPE html>

<html lang="en">

<head>

  <meta charset="UTF-8">

  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>Khidaeng System</title>

  <link rel="stylesheet" type="text/css" href="css/body.css">

</head>

<body>

  <header>

    <h2>Khidaeng System</h2>

  </header>

  <section>

    <nav>

      <ul>

        <li><a href="index.php">หน้าหลัก</a></li>

        <?php

        if ($_SESSION == NULL) {

        ?>

        <li><a href="login.php">เข้าสู่ระบบ</a></li>

        <li><a href="register.php">สมัครสมาชิก</a></li>

        <?php

        }

        if ($_SESSION != NULL) {

          if ($_SESSION['member_level'] == "admin") {

          ?>

          <li><a href="admin/index.php">ระบบหลังบ้าน</a></li>

          <?php

          }

        ?>

        <li><a href="logout.php">ออกจากระบบ</a></li>

        <?php

        }

        ?>

      </ul>

    </nav>

    <article>

      <h1>หน้าหลัก (ทำขึ้นเพื่อการศึกษา)</h1>

      <?php

      if ($_SESSION == NULL) {

        echo "คุณยังไม่ได้เข้าสู่ระบบ";

      }else{

        echo "ยินดีต้อนรับ ".$objResult["member_name"];

      }

      ?>

    </article>

  </section>

  <footer>

    <p>Mr.Wayut Janduan | <a href="https://www.khidaeng.com/" style="text-decoration: underline; color: #FFF;">Khidaeng.com</a></p>

  </footer>

  <?php mysqli_close($Connection); ?>

</body>

</html>

