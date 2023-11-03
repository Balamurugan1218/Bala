<Html>  
    <head>
    <h1>EMPLOYEE FORM</h1>
    <title>  
    Registration Page  
    </title>  
    </head>  
    <br>  
    <br>
    <body>

        <script>
          // Function to generate a random color in hexadecimal format
          function getRandomColor() {
            const letters = '0123456789ABCDEF';
            let color = '#';
            for (let i = 0; i < 6; i++) {
              color += letters[Math.floor(Math.random() * 16)];
            }
            return color;
          }
        
          // Function to change the background color
          function changeBackgroundColor() {
            document.body.style.backgroundColor = getRandomColor();
          }
        
          // Set an interval to change the background color every 3 seconds (3000 milliseconds)
          setInterval(changeBackgroundColor, 3000);
        </script>
        
        </body>
    <form>
    <label>Enter your Name </label>         
    <input type="text" name="Enter your Name" size="15"/> <br> <br>  
    <label>Enter your Department </label>     
    <input type="text" name="Enter your Department" size="15"/> <br> <br>           
    Tell me a about yourself
    <textarea cols="80" rows="5" value="Tell me about yourself">  
    </textarea> <br><br>
    Do you Exercise at home?
    <input type="radio" name="Yes"/> Yes   
    <input type="radio" name="No"/> No <br><br>
    How do you like to read about your favourite topics?<br><br>
    <input type="checkbox" name="Books"/> Books   
    <input type="checkbox" name="Online Resources"/> Online Resources
    <input type="checkbox" name="Phone apps"/> Phone apps  
    <input type="checkbox" name="Magazines"/> Magazines<br><br>
    What genere of movies do you like ? 
    <select>
        <option value="Comedy">Comedy</option>
        <option value="Horror">Horror</option>
        <option value="Crime">Crime</option>
        <option value="Devotional">Devotional</option>
      </select><br><br>
      <button onclick="myalert()">
        Submit Form
     </button>
     <script>
          function myalert() {
              alert("Submitted Succesfully");
          }
     </script>
    </form>  
    </body>  
    </html>
