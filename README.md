# Basic-Html-Form-Project
This is about how you can use html tags to create simple projects.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Project 2</title>
</head>
<body>
    <form>
        <fieldset>
            <legend>User details!!</legend>
            <label for="name">Enter your name:</label>
        <input type="text" id="name" name="username">
        <br>
        <br>

        <label for="address">Enter your address:</label>
        <textarea rows="2" cols="10" id="address" id="adress" name="user address"></textarea>
        <br>
        <br>

        <label for="dob">Enter your date of birth:</label>
        <input type="date" id="dob" name="userdob">
        <br>
        <br>

        <label for="password">Enter your password:</label>
        <input type="password" id="password" name="userpassword">
        <br>
        <br>
          
        <p><u>Select gender:</u></p>
        <br>

        <label for="Male">Male</label>
        <input type="radio" id="Male" name="usergender">
        <br>


        <label for="Female">Female</label>
        <input type="radio" id="Female" name="usergender">
        <br>
        
        
        <label for="Other">Other</label>
        <input type="radio" id="Other" name="usergender">
        <br>
    
         
        <p><u>Select favourite movie:</u></p>
        <br>
    

        
        <label for="Avengers">Avengers</label>
        <input type="checkbox" name="Avengers" id="Avengers">
        <br>
        

        <label for="Thor">Thor</label>
        <input type="checkbox" name="Thor" id="Thor">
        <br>
        

        <label for="Ironman">Ironman</label>
        <input type="checkbox" name="Ironman" id="Ironman">
        <br>
        <br>
    
        
        <input type="submit">

        </fieldset>
        

    </form>
</body>
</html>
