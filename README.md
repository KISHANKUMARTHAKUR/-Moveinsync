# -Moveinsync

Design a Stadium Seat Booking System 

In this system user has two role :

A.	ADMIN : He should be able to 

1.	Add , update and delete Stadium Details :
Stadium Details: 
-> Number of seats
-> Seat availability
-> Seat Price 
-> Category of Seat 

2.	Decide which match would take place in stadium 

      B) USER :  He should be able to
      
      
      
1.  Book a seat for match 

Constraints :

-> Block booking of seats in the stadium  if the Occupancy of that stadium  is more than  50% and show the same message to the user.
-> Users can book a single seat or multiple seats so calculate price according to the number of seats the user has booked.
-> After booking each user have unique seat number 








import java.io.IOException;
import java.util.List;








<!DOCTYPE html">
<html>
    <head>
        <meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
        <title>ETICKETING</title>
        <link href="../css/login.css" rel="stylesheet" type="text/css" />
    </head>
    <body><div align="center"><fieldset><legend align="center">Login</legend>
           <br>
           <br>
        <form action="loginscript.php" method="POST">
            <table border="0" align="center" width="30%">
                 <tr>
          <td colspan="2">
              <div align="center" class="please">Please enter your username and password</div>

          </td>
        </tr>


                    <tr>
                        <td>Username</td>
                        <td><input class="textfield" type="text" name="user_name" value="" class="textfield"/></td>
                    </tr>
                    <tr>
                        <td>Password</td>
                        <td><input class="textfield" type="password" name="password" value="" maxlength="30" class="textfield"/></td>
                    </tr>
                    <tr><td>&nbsp;</td><td><input class="formbutton" type="submit" value="Submit" maxlength="30" /></td></tr>
            </table>


        </form>
        </fieldset>
    </div>
        <br>
<div align="center" class="copyright">Copyright &copy; 2010 by <a href="http://www.netdatangr.com">Network Data Systems Limited</a></div>
<br>
   
    </body>
</html>
