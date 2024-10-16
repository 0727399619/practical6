<!Doctype html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport"content="width=device-width,initial -scale=1.0">
    <title>DOCUMENT</title>

    <style>
        .login{
           margin: 40px; 
        }
    input[type=button]{
            border-radius:10px;
            padding: auto;
            
        }
    </style>
    <body>
       <div class="login">
       <h1>"Pimp My Shoes" Contest Entry Form</h1>
        <form>
            Contest Entry Information<br><br>
            Name:<input type="name"value=""/><br>
            Email Adress:<input type="email"value=""/><br>
            Telephone Number:<input type="telephone number"value=""/><br>
            My shoes are SO old...<br>
           <textarea name="text">No more than 300 characters long</textarea>
           <h2>Design your Forcefields:</h2>
           <fieldset>
            <legend>Custom Shoe Design</legend>
          <fieldset>
           <legend>Color(choose one):</legend>
           <input type="radio"name="Red"value=""/>Red<br>
           <input type="radio"name="Blue"value=""/>Blue<br>
           <input type="radio"name="Black"value=""/>Black<br>
           <input type="radio"name="Sliver"value=""/>Sliver<br>
        </fieldset>
        <fieldset>
        <legend>Features(choose as many as you want)</legend>
        <input type="checkbox"name="Sparkley laces"value=""/>Sparkley laces<br>
        <input type="checkbox"name="Metallic logo" checked=""checked=""value=""/>Metallic logo<br>
        <input type="checkbox"name="Light-up heels"value=""/>Light-up heels<br>
        <input type="checkbox"name="Mp3-enabled"value=""/>Mp3-enabled<br>
    </fieldset>
   
    <fieldset>
    <legend>Size</legend>
    Sizes reflect standard men's sizes:<input type="number" name="numdays" value="5"min="5" max="5">
</fieldset>
</fieldset>
        </form>
        <input type="button" value="Pimp My Shoes!"/>&nbsp;
        <input type="button" value="Reset"/>
       </div>
    </body>
</head>
</html>
