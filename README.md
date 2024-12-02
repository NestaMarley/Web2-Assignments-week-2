# Web2-Assignments-week-2
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Multimedia Webpage</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
            text-align: center;
        }
        audio, video {
            width: 100%;
            max-width: 600px;
            margin: 20px 0;
        }
    </style>
</head>
<body>
    <h1>My Multimedia Webpage</h1>

    <h2>Audio Player</h2>
    <audio controls>
        <source src="/storage/emulated/0/Download/gunna_banking_on_me_official_lyric_video_mp3_44682.mp3" type="audio/mpeg">
        
    </audio>

    <h2>Video Player</h2>
    <video controls poster="/storage/emulated/0/Pictures/Twitter/20241108_184337.jpg">
        <source src="/storage/emulated/0/Download/toosii_gunna_champs_elysees_h264_44712.mp4" type="video/mp4">
        
    </video>

</body>
</html>

Part2

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>User Registration Form</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }
        .form-container {
            background: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h2 {
            margin-bottom: 20px;
        }
        input[type="text"], input[type="email"], input[type="password"], input[type="number"] {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        input[type="radio"] {
            margin-right: 5px;
        }
        .terms {
            margin: 10px 0;
        }
        button {
            background-color: #28a745;
            color: white;
            border: none;
            padding: 10px;
            border-radius: 4px;
            cursor: pointer;
            width: 100%;
        }
        button:hover {
            background-color: #218838;
        }
    </style>
</head>
<body>

<div class="form-container">
    <h2>Register</h2>
    <form id="registrationForm">
        
        <label for="fullName">Full Name:</label>
        <input type="text" id="fullName" name="fullName" required maxlength="50" placeholder="Enter your full name">

        <!-- Email Input -->
        <label for="email">Email Address:</label>
        <input type="email" id="email" name="email" required placeholder="Enter your email">

        <!-- Password Input -->
        <label for="password">Password:</label>
        <input type="password" id="password" name="password" required minlength="8" placeholder="Enter your password">

        
        <label for="age">Age:</label>
        <input type="number" id="age" name="age" required min="18" placeholder="Enter your age">

        
        <label>Gender:</label>
        <label><input type="radio" name="gender" value="male" required> Male</label>
        <label><input type="radio" name="gender" value="female" required> Female</label>
        <label><input type="radio" name="gender" value="other" required> Other</label>

        <!-- Terms and Conditions Checkbox -->
        <div class="terms">
            <label><input type="checkbox" required> I agree to the Terms and Conditions</label>
        </div>

        <!-- Submit Button -->
        <button type="submit">Register</button>
    </form>
</div>

</body>
</html>


