# head

* Jame daugiausia yra **HTML** dokumento meta informacija, pvz., pavadinimas (ang. title), žymos (ang. tags) ar nuorodos (ang. links) į išteklius.
* Žyma (ang. tag) `<title> ... </title>` yra naršyklėje rodomo **HTML** dokumento pavadinimas.
* Žyma (ang. tag) `<link rel="" type ="" href="" />` apibrėžia nuorodą į kai kuriuos išorinius išteklius - dažniausiai **CSS**.
* Žyma (ang. tag) `<meta property="" content=""/>` apibrėžia papildomą informaciją apie puslapį.
* Žyma (ang. tag) `<script type="" src=""></script>` apibrėžia nuorodą į screnarijaus kalbą - dažniausiai **JavaScript**. 

```html
<head>
    <title>Dokumento pavadinimas</title>
    <meta property="author" content="Viktor Nareiko">
    <link rel="stylesheet" type="text/css" href="https://g2.dcdn.lt/scms/?g=dc.css&amp;1629956120">
    <script type="text/javascript" src="https://g2.dcdn.lt/scms/?g=dfp.js&amp;1627473508"></script>
    <script type="text/javascript">
        console.log("Hello world!!!");
    </script>
</head>
```
