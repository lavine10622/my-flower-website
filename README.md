# my-flower-website
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Multimedia Webpage</title>
</head>
<body style="background-color:coral;">

    <h1>Welcome to My Multimedia Webpage</h1>

    
    <h2>FLOWER</h2>
    <img src="media/yawa.jpg"Sample Image" height="400" width="850">

    <!-- ✅ Embed Audio -->
    <h2>Audio</h2>
    <audio controls>
        <source src="media/music.mp3" type="audio/mpeg">
        Your browser does not support the audio element.
    </audio>

    
    <h2>Video</h2>
    <video width="400" controls>
        <source src="media/flower.mp4" >
        Your browser does not support the video tag.
    </video>300

    
    <h2>Registration Form</h2>
    <form>
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required><br><br>

        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required><br><br>

        <label for="password">Password:</label>
        <input type="password" id="password" name="password" required minlength="6"><br><br>

        <input type="submit" value="Register">
    </form>

    
    <h2>Sample Table</h2>
    <table border="1">
        <tr>
            <th>name</th>
            <th>Course</th>
        </tr>
        <tr>
            <td>lavine</td>
            <td>cyber security</td>
        </tr>
        <tr>
            <td>adhiambo</td>
            <td>computer science</td>
        </tr>
    </table>

    
    <h2> course list</h2>
    <ul>
        <li>Data science</li>
        <li>information comunication technology</li>
        <li>computer science</li>
    </ul>

</body>
</html>

