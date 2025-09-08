# Prince-
Html Projects
<!-- To create a Regisration form  -->

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>

<body>
    <h1> University Regisration Form </h1>
    <p> Please fill out the form below to register. </p>
    <hr>

    <h2> Personal Details</h2>

    <form>
        <label for="name"> First Name :</label>
        <input type="text" name="username" id="name" placeholder="e.g : John " required>
        <br><br>
        <label for="last name "> Last Name :</label>
        <input type="text" name="userlastname" id="name" placeholder="e.g: snow" required>

        <br><br>
        <label for="date of birth"> Date of birth :</label>
        <input type="Date" name="DoB" id="dob" required>

        <br><br>
        <h4>Gender :</h4>

        <label for="male">Male</label>
        <input type="radio" name="gender" id="male" value="male" required>

        <br><br>
        <label for="female"> Female</label>
        <input type="radio" name="gender" id="female" value="female">

        <br><br>
        <label for="Others">Others</label>
        <input type="radio" name="gender" id="others" value="other">
        <br><br>

        <h4>Upload your photo :</h4>

        <input type="file">


        <hr>

        <h3> Contact Information :</h3>

        <label for="email">Email Address :</label>
        <input type="email" name="email" id="email" placeholder="e.g: john@gmail.com" required>
        <br><br>
        <label for="moblie no."> Mobile Number :</label>
        <input type="number" name="mobile no." id="mobile no." placeholder="e.g: 8693928489" required>
        <br><br>
        <label for="address">Mailing Address :</label <br><br>
        <textarea name="address" id="address" row="20" cols="30"
            placeholder="e.g: street address, state, ZIP code  " required></textarea>


        <hr>
        <h3> Acadmic Information</h3>
        <label for="course">Select your course :</label>
        <select name="course" id="course ">
            <br>
              <option> Select Course - </option>
            <option value="CSE"> CSE</option>
            <option value="ME">ME </option>
            <option value="CE">CE </option>
            <option value="CSIT">CSIT</option>
            <option value="EC">EC </option>


        </select>
        <br>
           <h4>Extracaricular Activities :</h4>
               
           
           <input type="checkbox" value="sport" >
           <label >Sports</label >
            <br><br>
            <input type="checkbox" value=" Arts" >
           <label >Music & Arts</label >
            <br><br>
            <input type="checkbox" value="clubs" >
           <label > Technology clubs</label >
            <br><br>
            <input type="checkbox" value="volunteer" >
           <label >volunteering</label >

            <hr>
            <h3> Create Your Account :</h3>
            <label for=" pass"> Create your password :</label>
            <input type=" password" name="pass" id="pass" required>
            <br><br> 
            <label >Security Question :</label>
            <select  >
                <option > what's your pet name </option>
                <option value="Drogo"> Drogo</option>
                <option value="tyrion"> tyrion</option>
                <option value="Rocky"> Rocky </option>
            </select>
               <br><br>
             <label for="security ans :"> Security Answer :</label>
                <input type="text" name="security ans" id=" Security">

              <br><br>
               <button type="submit"> Register</button>
               <button type="reset"> Clear Form</button>


    </form>
</body>

</html>
