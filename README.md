<!DOCTYPE html>
<html>
    <head>
        <title>Page Title</title>
    </head>
    <body>
        <div class="a">
            <form name="forms">
                <input type="text"                              name="answer" id="b" > <br> </br>
    
    <input type="button" value="1" onclick="form.answer.value += '1'"">
        <input type="button" value="2" onclick="form.answer.value += '2'"">
            <input type="button" value="3" onclick="form.answer.value += '3'"">
            <br><br>
                <input type="button" value="4" onclick="form.answer.value += '4'"">
        <input type="button" value="5" onclick="form.answer.value += '5'"">
            <input type="button" value="6" onclick="form.answer.value += '6'"">
            <br><br>
                <input type="button" value="7" onclick="form.answer.value += '7'"">
        <input type="button" value="8" onclick="form.answer.value += '8'"">
            <input type="button" value="9" onclick="form.answer.value += '9'"">
            <br><br>
             <input type="button" value="+" onclick="form.answer.value += '+'"">
        <input type="button" value="0" onclick="form.answer.value += '0'"">
            <input type="button" value="-" onclick="form.answer.value += '-'"">
            <br><br>
                <input type="button" value="*" onclick="form.answer.value += '*'"">
        <input type="button" value="/" onclick="form.answer.value += '/'"">
            <input type="button" value="=" onclick="form.answer.value = eval(form.answer.value)">
            <br><br>
            <input type="button" value="Clear All" onclick="form.answer.value=''" id="clear">
            </form>
        </div>
    </body>
</html>
