<?php
$filename = './tweet_log.txt';
 if (isset($_POST['comment']) === TRUE) {
    $fp = fopen($filename, 'a');
    $log = date('Hi)');
    fwrite($fp , $log);
    fclose($fp);
}

if ($_SERVER['REQUEST_METHOD'] === 'POST'){
  $comment = $_POST['comment']."\n";
  if (($fp = fopen($filename, 'a')) !== FALSE) {
    if (fwrite($fp, $comment) === FALSE) {
      print 'ファイル書き込み失敗:  ' . $filename;
    }
    fclose($fp);
  }
}

$data = array();

if (is_readable($filename) === TRUE) {
  if (($fp = fopen($filename, 'r')) !== FALSE) {
    while (($tmp = fgets($fp)) !== FALSE) {
      $data[] = htmlspecialchars($tmp, ENT_QUOTES, 'UTF-8');
    }
    fclose($fp);
  }
} else {
  $data[] = 'ファイルがありません';
}
?>

<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8">
  <title>Simple tweet</title>
</head>
<body>
  <h1>Simple tweet</h1>
  <form method="post">
    <p>tweet：<input type="text" name="comment">
    <input type="submit" name="submit" value="送信"></p>
  </form>
  <p>◉tweet一覧</p>
<?php foreach ($data as $fp) { ?>
  <p><?php print $fp; ?></p>
<?php } ?>
</body>
</html>
