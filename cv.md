# Seredin Christofor Daniilovich
> Junior Frontend Developer

## Connection with me
* Phone     +7 999 566 58 58
* Skype:    CrisRim
* Email     CrisRim@gmail.com
* Address   Rostov-on-don

## Summary of Qualification
* Nine year working with people as their manager trainer.
* Resourceful and insightful; adapt quickly to challenges.
* Commended for top-notch organizational and administration skills.

## Hard skills
* JavaScript
* Html5
* CSS3
* PHP7
* gulp
* npm 
* Task creation for gulp

## Code examples
> <?php

if ( !empty($_POST) && trim($_POST['name']) != '' && trim($_POST['email']) != '' && trim($_POST['tel']) != '' && trim($_POST['message']) != ''  ) {

    $message =  "Вам пришло новое сообщение с сайта: Территория окон \n" .
                "Имя отправителя: " . $_POST['name'] . "\n" .
                "Телефон отправителя: ". $_POST['tel'] . "\n" .
                "Email отправителя: ". $_POST['email'] . "\n" .
                "Сообщение: ". $_POST['message'];

    mail( '1234r@bk.ru', "Сообщение с сайта!", $message ); 

    header('location: thankyou.html');

}



function checkValue($item, $message ) {
    if ( isset($item) && trim($item) == ''  ) {
        echo '<div class="error">' . $message . '</div>';
    } 
}

function printPostValue($item){
    if ( isset($item) && strlen(trim($item)) > 0 ) {
        echo $item;
    }
}

?>
## Education 
> Diploma
* Information Security Specialist 2012-2016
* Lectures REST APP 2016
* Lectures Git 2016
* JavaScript course 2017-2018

## English
> A2+
* English courses in duolingo.com and reading literature

