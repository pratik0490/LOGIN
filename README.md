
<!DOCTYPE html>
<html lang="en">
<head><style>
    form{display: flex;
        justify-content: center;
        /* width: 50vh; */
        /* height: 50%; */
        text-align: center;

    }.bit{font-size: larger;
 transition: 0.3s;
 background-color: rgb(161, 190, 191);
}.bit:hover{
    background-color: rgb(199, 201, 199);
}

.radioc{padding: 10px;
    margin: 123px;
}
    
.pp{
    font-size: 16px;
}

    input{border-radius: 10px;
        text-align: center;
       
        
    }

</style>
<script>
    // This function will be called when the form is submitted
    function redirectToNextPage(event) {
        event.preventDefault(); // Prevents the form from submitting the normal way

        // Normally you would want to process the form data here (or send it via AJAX)

        // After submission, redirect the user to another page
        window.location.href = 'dashboard.html'; // Redirect to the next page
    }
</script>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>  
    <form action="https://api.web3forms.com/submit" method="POST" style="background-color: azure;">
        <input type="hidden" name="access_key" value="6c8da399-0a1a-4dda-ac10-c65d40dd17be">
    <fieldset><legend><b>Personal Detail's </b>
    </legend>
        <table >

            <marquee behavior="" direction="right" style="background-color: rgb(166, 150, 195);"><b><h3>Well-Come To Login Page ...!</h3></b> </marquee>
<tr>
    <td><label for="name">Name :</label></td>
    <td><input type="text" placeholder="Name As Per Aadhar"  name="name" class="pp"></td>
</tr>
<tr><td></td></tr>
<tr>
    <td>
        <label for="cotact">Contact :</label>
    </td>
    <td>
        <input type="tel" class="pp" placeholder="Moblie Number " name="phone" maxlength="13" minlength="0">
    </td>
</tr>
<tr>
    <td ></td>
</tr>
<tr>
    <td><label for="prn">PRN :</label></td>
    <td><input type="number"class="pp" placeholder="PRN" name="PRN"maxlength="10" minlength="10" ><br></td>
</tr>
<tr>
    <td ></td>
</tr>
<tr>
    <td><label for="email">E-mail Id :</label></td>
    <td><input type="email"name="Gmail" class="pp"placeholder="E-mail Id "></td>
</tr>
<tr>
    <td ></td>
</tr>
<tr>
    <td ></td>
</tr>
<tr class="radioci" style="margin-right: 10px; padding: 0;">
    <td><label for="gendder">Gender :</label></td>
    <td><input type="radio" name="Male" name="gender"> Male</td>
    <td><label for="gendder"></label></td>
    <td><input type="radio" name="Female" name="gender">Female</td>
</tr>
<tr>
    <td></td>
</tr>
<tr>
    
</tr>
<tr>
    <td>State        :</td>
    <td>
    <select name="STATE" id=""  class="pp">
    <option value="STATE" name=""> SELECT STATE</option>
    <option value="MAHARASTRA" >MAHARASTRA</option>
    <option value="GOA">GOA</option>
    <option value="HIMACHAL">HIMACHAL</option>
    <option value="KARNATAKA">KARNATAKA</option>
</select></td></tr>
<tr><td></td></tr>
</td><tr>
    <td><label for="Address ">Address : </label></td>
    <td><textarea name="Address" id=""  class="pp"rows="4" cols="30"></textarea></td>
</tr>






</table>
<input type="submit" value="SUBMIT" class="bit">
<input type="reset" value="RESET" class="bit">      
</fieldset>
    
    </form>
</body>
</html>
