<?php
$lang = substr($_SERVER['HTTP_ACCEPT_LANGUAGE'], 0, 2);
switch ($lang){
    case "fr":

        include("index_az.php");
        break;
    case "az":

        include("index_tr.php");
        break;
    case "tr":

        include("index_en.php");
        break;        
    default:

        include("index_it.php");
        break;
}
?>