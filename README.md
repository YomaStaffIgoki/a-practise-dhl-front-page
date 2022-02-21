# a-practise-dhl-front-page
Learning to use html and css to create front page of websites
<style>
.head
{
    height: 18vh;
    width: 100vw;
    padding: 1.5rem 2.8rem 0;
    display: flex;
    justify-content:space-between;
    align-items: center;
}
.logoo
{
    height: auto;
    max-height: 6.4rem;
    width: 14rem;
}

.first-list
{
    display: flex;
    flex-direction: row;
list-style-type: none;
padding-right: 1px;
}
.contact
{
    width: 35%;
}
.border
{
    border: 1px solid black;
}
.pr
{
    padding-right: 4px;
}
</style>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="./dhl-practise.css">
    <link rel="stylesheet" href="./normalize.css">
</head>
<body>
    <div class="head border">
    <div class="logo border"><img class="logoo" src="dhl.svg" alt=""> </div>
    <div class="contact border">
        <ul class="first-list pr" style="font-weight:bold; font-size: large;">
            <li class="pr">Contact Us</li>
            <li class="pr">Portal Login</li>
            <li class="pr">Nigeria</li>
            <li class="pr"><b>EN</b></li>
            <li>&#128269 Search</li>
        </ul>
    </div>
    <div class="track"></div>
</div>
</body>
</html>
