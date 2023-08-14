# Platinum_Properties
Platinum Properties - A new property management service in the city wants to have a web page designed, which will enable its customers to furnish details associated with property-booking. Help them in designing the same. 
 <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Platinum Properties</title>
    <link rel="stylesheet" href="Platinum Properties.css">
</head>
<body>
    <table  class="b">
     <tr> 
        <td class="left">
            <img src="Screenshot 2023-08-08 124202.png" alt="image" id="image">
        </td>
        <td class="right">
            <div class="Platinum">
            <h3>Platinum Properties</h3>
    <table>
        <!--1 row-->
        <tr>
            <td><a href="#property" id="property_info">Property-info</a></td>
            <td><a href="#personal" id="personal_info">Personal-info</a></td>
            <td><a href="#features" id="Extra_Features">Extra-Features </a></td>
        </tr>
        <!--2nd row-->
        <tr>
            <td colspan="3" id="property" class="heading">Property Information</td>
        </tr>
        <!--3rd row-->
        <tr>
            <td><label for="Select property Type" id="Select property Type">Select property Type:</label><br>
                <select name="" id="Select property Type" >
                    <option value="select" class="h">Select</option>
                    <option value="Apartment">Apartment</option>
                    <option value="Independent House">Independent House</option>
                    <option value="Vila">Vila</option>
                    <option value="Compact Home">Compact Home</option>
                </select>
            <td><label for="BHK Type">BHK Type</label><br>
                <select name="" id="bhk" class="h">
                <option value="select">Select</option>
                <option value="1BHK">1BHK</option>
                <option value="2BHK">2BHK</option>
                <option value="3BHK">3BHK</option>
                <option value="4BHK">1BHK</option>
            </select>
            <td><label for="Select the possession status">Select the possession status</label><br>
                <select name="" id="status " class="h">
                <option value="select">Select</option>
                <option value="Plot">Plot</option>
                <option value="Under Construction">Under Construction</option>
                <option value="Semi Furnished">Semi Furnished</option>
                <option value="Ready To Move">Ready To Move</option>
            </select>
            <!--4th row-->
            <tr>
                <td><label for="Price Range">Price Range</label></td>
                <td id="from"><input type="number" class="h" id="Price Range"></td>
                <td id="to"><input type="number" class="h" id="Price Range"></td>
            </tr>
            <!--5th row-->
            <tr>
                <td ><label for="Location" >Location</label></td>
                <td colspan="2"><input type="text" id="Location" placeholder="Enter location " class="h"></td>
            </tr>
            <!--6th row-->
            <tr>
                <td colspan="3" class="heading" id="personal">Personal Information</td>
            </tr>
            <!--7th row-->
            <tr>
                <td><label for="cname">Customer Name</label></td>
                <td colspan="2"><input type="text" class="full" id="cname"></td>
            </tr>
            <!--8th row-->
            <tr>
                <td><label for="phno">Phone Number</label></td>
                <td colspan="2"><input type="text" pattern="10" id="phno" class="full"></td>
            </tr>
            <!--9th row-->
            <tr>
                <td><label for="Email ID">Email ID</label></td>
                <td colspan="3"><input type="email" class="full" id="Email ID"></td>
            </tr>
            <!--10th row-->
            <tr>
                <td colspan="3"><label for="Extra Features" id="features" class="heading">Extra Features</label></td>
            </tr>
            <!--11th row-->
            <tr>
                <td> <label for="parking" ></label><input type="checkbox" id="parking">parking</td>
                <td><input type="checkbox" id="parking">swimming pool</td>
                <td><input type="checkbox" id="parking">super market</td>
            </tr>
            <!--12th row-->
            <tr>
                <td><input type="checkbox" id="park">park</td>
                <td><input type="checkbox" id="library">library</td>
                <td><input type="checkbox" id="playground">playground</td>
            </tr>
            <!--13th row-->
            <tr>
                <td colspan="3"><a href="#submit" id="offers"  >**Click here to unlock exclusive offers</a></td>
            </tr>
        </table>
            <button type="submit" id="submit">CHECK AVAILABILITY</button>
            </div>
        </td>
    </tr>
</table>
</body>
</html>


#css
.left
{
    left: 0px;
    background-color:white ;
}
.right
{
    right:0px;
    background-color: #74b14e;
    width: 60%;
    padding: 10px;
}
.b
{
    color:#6600FF;
}
h3
{
    text-align: center;
    font-size: 20px;
    font-family:Georgia, 'Times New Roman', Times, serif;
    border-radius: 6px;
    padding: 5px;
    background-color: #FFFFFF;
    color: #C21807;
}
table
{
    border-spacing: 2px;
    width: 97%;
    margin:auto;
}
td
{
    color: #6600FF;
    background-color: #dfbf9f;
    border-spacing: 5px;
    border-radius: 6px;
    padding: 5px;
    font-size: 15px;
    font-family: Georgia, 'Times New Roman', Times, serif;
}
#submit
{
    color: #C21807;
    font-weight:bold ;
    background-color:#FFFFFF;
    text-decoration:none;
    margin-top: 25px;
    margin-left: 20px;
    border-radius: 6px;
}
#submit:hover
{
 color: #FFFFFF;
 background-color:#C21807;
}
.Platinum
{
    width: 100%;
    height: 100%;
    float: right;
    background-color: #74b14e;
}
.heading
{
    color: #C21807;
    font-size: 15px;
    font-family: Georgia, 'Times New Roman', Times, serif;
    font-weight: bold;
    width: 80%;
}
.full
{
    width: 97%;
    color: #6600FF;
}
img
{
    height:600px;
}
.h
{
    width:95%;

}
