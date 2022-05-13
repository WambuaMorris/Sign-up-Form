# Sign-up-Form
simple sign-up form 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Survey form</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
   
    <section id="form">
        <form >
            <input type="text" placeholder="First Name">
            <input type="text" placeholder="Second Name">
            <input type="email" placeholder="example@gmail.com">
            <input type="date" name="Date of Birth" id="">

            <p>I agree to the <a href="#">terms and conditions.</a> I ensure that I am atleast 18 years of age.</p>

           

            <button type = "Submit" > <span id="checkbox"><input type="checkbox" required></span>Submit</button>

        </form>
    </section>
</body>
</html>

<--CSS-->
@import url('https://fonts.googleapis.com/css2?family=Open+Sans&display=swap');
#image{
    max-width: 100%;
    height: auto;
}
body{
    margin: 0%;
    padding: 0%;
    background-image: url( "https://img.freepik.com/free-vector/web-development-programmer-engineering-coding-website-augmented-reality-interface-screens-developer-project-engineer-programming-software-application-design-cartoon-illustration_107791-3863.jpg?size=626&ext=jpg&ga=GA1.1.547529467.1646408102" );
    background-position: center;
    background-size: cover;
}

#form{
    
   width: 300px;
    font-family: 'Open Sans';
    border-style: solid;
    border-width: 4px;
    border-radius: 10px;
    border-color: darkorchid;
    text-align: center;
    margin-left: 50%;

margin-top: 40px;
padding: 30px;
background-color: aliceblue;

}
input{
    margin: 5px;
}
p{
    text-align: center;
}
button {
    text-align: center;
    
    border-radius: 20px;
    cursor: pointer;
    margin-bottom: 6px;
    background-color: darkorchid;
    width: 100%;
    border:none;
    outline: none;
}
button:hover{
    background-color: aqua;
}
