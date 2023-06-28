<!DOCTYPE html>
<html>
    <head>
        <style>
             th, td {
                border: 1px solid black;
                border-collapse: collapse;
            }
            th,td {padding: 30px;}
        </style>
        <body>
            <table>
                <tr>
                    <th>Control Type</th>
                    <th>Data</th>
                    <th>Control</th>
                </tr>
                <tr>
                    <td>Text box</td>
                    <td>Name:</td>
                    <td>
                        <form>
                            <input type="text" value="Enter name"/>
                        </form>
                    </td>
                </tr>
                <tr>
                    <td>Password</td>
                    <td>Password:</td>
                    <td>
                        <form>
                            <input type="password"/>
                        </form>
                    </td>
                </tr>
                <tr>
                    <td>Text area</td>
                    <td>Address:</td>
                    <td><textarea name="message" rows="5" cols="40"> Enter address</textarea>
                </tr>
                <tr>
                    <td>Drop down list</td>
                    <td>Area:</td>
                    <td><select name="center">
                        <option value="center">Center</option>
                        <option value="center">right</option>
                        <option value="center">left</option>
                </tr>
                <tr>
                    <td>Check box</td>
                    <td>Hobbies:</td>
                    <td>
                        <input type="checkbox" name="Sport"/> Sport<br />
                        <input type="checkbox" name="Reading"/> Reading <br />
                        <input type="checkbox" name="T.V."/> T.V. <br />
                        <input type="checkbox" name="Internet"/> Internet
                    </td>
                </tr>
                <tr>
                    <td>Radio Buttons</td>
                    <td>Gender:</td>
                    <td>
                        <fieldset>
                            <legend>Gender selection</legend>
                        <input type="radio" name="radiobuton" /> Male <br />
                        <input type="radio" name="radiobuton" /> Female
                        </fieldset>
                    </td>
                </tr>
                <tr>
                    <td>File upload</td>
                    <td>Your image:</td>
                    <td><input type="submit" value="Choose file" /> No file chosen</td>
                </tr>
                <tr>
                    <td>Buttons</td>
                    <td>Actions:</td>
                    <td><input type="submit" value="submit" />
                        <input type="reset" value="reset"/>
                        <input type="Button" value="Button"/>
                        
                        
                </tr>

            

            </table>
        </body>
    </head>
</html>
