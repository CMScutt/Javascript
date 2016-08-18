# Javascript
Javascript code for Ubuntu
This entry is to determine why the "reponse to a click" is not executing in Firefox V48.0.
Thank you,
Christine

<!doctype html>
<html>
    <head>
        <title>Learning Javascript</title>

        <meta charset="utf-8">
        <meta http-equiv="Content-type" content="text/html; charset=utf-8"/>
        <meta name="viewport" contet="width=device-width, initial-scale=1"/>

    </head>

    <body>
        <button id="textChanger">Change first div text.</button>
        <div id="firstDiv">This is some text.</div>
        <script type="text/javascript">
            document.getElementById("textChanger").oneclick=function()  {
                document.getElementById("firstDiv").innerHTML="This is awesome!";
            }   
        </script>
    </body>

</html>
