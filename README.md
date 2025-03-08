<!DOCTYPE html>
<html lang="en">
<head>
    <meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ibrahim Jibrin Yahaya</title>
    <style>
        body {
            font-family: Arial, sans-serif;
        }
        .header, .footer {
            text-align: center;
            background-color: rgb(28, 78, 28);
            color: rgb(231, 231, 78);
            padding: 20px;
        }
        .section {
            text-align: center;
            background-color: rgb(245, 241, 241);
            padding: 20px;
        }
        .section h1, .section h2 {
            margin: 10px;
        }
        .content {
            background-color: rgb(141, 135, 135);
            text-align: center;
            padding: 20px;
        }
        .form-container {
            background-color: #f1f1f1;
            padding: 20px;
            margin: 20px 0;
        }
        .form-container input, .form-container button {
            padding: 10px;
            margin: 10px 0;
            width: 100%;
            max-width: 300px;
            display: block;
        }
        .footer {
            background-color: black;
            color: yellow;
            padding: 20px;
        }
        .footer h2 {
            margin: 0;
        }

        /* 3D Cube rotation styles */
        .cube-container {
            position: relative;
            width: 300px;
            height: 300px;
            margin: 0 auto;
            transform-style: preserve-3d;
            animation: rotateCube 10s infinite;
        }

        /* Faces of the cube (the images) */
        .cube-face {
            position: absolute;
            width: 100%;
            height: 100%;
            backface-visibility: hidden;
        }

        .cube-face img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }

        /* Keyframes for rotating the cube */
        @keyframes rotateCube {
            0% {
                transform: rotateY(0deg);
            }
            33% {
                transform: rotateY(90deg);
            }
            66% {
                transform: rotateY(180deg);
            }
            100% {
                transform: rotateY(270deg);
            }
        }

        /* Set the positioning of each image face */
        .front  { transform: rotateY(  0deg) translateZ(150px); }
        .right  { transform: rotateY( 90deg) translateZ(150px); }
        .back   { transform: rotateY(180deg) translateZ(150px); }
        .left   { transform: rotateY(270deg) translateZ(150px); }
    </style>
</head>
<body>

<div class="header">
    <h2>Name: Ibrahim Jibrin Yahaya</h2>
    <h2>University Name: Phoenix University Agwada</h2>
    <h2>Semester: 1st Semester</h2>
</div>

<div class="section">
    <h1>IBRAHIM JIBRIN YAHAYA</h1>
    <h2>Phoenix University Agwada</h2>
    <h3>College Website Link: <a href="https://phoenixuniversity.edu.ng/">Click here</a></h3>
    <h3>Google Link: <a href="https://google.com/">Click here</a></h3>
</div>

<div class="content">
    <h1>Ibrahim Jibrin Yahaya</h1>
    <h3>College Website: <a href="https://phoenixuniversity.edu.ng/">Click here</a></h3>
    <h3>Google Link: <a href="https://google.com/">Click here</a></h3>
    <h3>Admission Form: <a href="https://phoenixuniversity.edu.ng/apply-to-phoenix/">Click here</a></h3>

    <!-- 3D rotating cube container -->
    <div class="cube-container">
        <!-- Front Face -->
        <div class="cube-face front">
            <img src="https://scontent-los2-1.xx.fbcdn.net/v/t39.30808-6/356875100_703516335123122_974593013472938200_n.jpg?_nc_cat=104&ccb=1-7&_nc_sid=6ee11a&_nc_ohc=YFzgTYPeXwkQ7kNvgEH7xyi&_nc_oc=Adio08h5EwoGwxxNdlpMj246lC9QL9OkPWGFj-RSt6Bpdn6ewODQv1HUtmNdRtrbxXs&_nc_zt=23&_nc_ht=scontent-los2-1.xx&_nc_gid=AEt93ddEgoNmeTzorTq8MtL&oh=00_AYFKKSmJZ22ja2YLY7_EclvZmxtX9yY_TDFebRRwKMNFWg&oe=67D22436" alt="Facebook Profile">
        </div>

        <!-- Right Face -->
        <div class="cube-face right">
            <img src="https://scontent-los2-1.xx.fbcdn.net/v/t1.15752-9/429952480_716210887294109_6532318400483501924_n.jpg?_nc_cat=107&ccb=1-7&_nc_sid=0024fc&_nc_eui2=AeHSfUy4OzbMIKQNdem4HX35ddpUTswYN3x12lROzBg3fERMpit4LsiGIzf45X4s1Y03nAAvBXLLCuD36s1Dg_TN&_nc_ohc=ZJbT5reXoroQ7kNvgHjynvH&_nc_oc=AdhN990DfK4auw76NQ3Rhdnd1tJQY9jB46mYbh5iOzhuWw-gmf2eg_2AHDGLwwbpA3wgnwbwlfHttKx8PIUKBzZ6&_nc_ad=z-m&_nc_cid=0&_nc_zt=23&_nc_ht=scontent-los2-1.xx&oh=03_Q7cD1wEiEgGg9CxAPuk3nYkhfvm_ea8WBFG3aYllWzDe2nz_Ww&oe=67F3B828" alt="Second Facebook Profile">
        </div>

        <!-- Back Face -->
        <div class="cube-face back">
            <img src="https://scontent-los2-1.xx.fbcdn.net/v/t39.30808-6/356875100_703516335123122_974593013472938200_n.jpg?_nc_cat=104&ccb=1-7&_nc_sid=6ee11a&_nc_ohc=YFzgTYPeXwkQ7kNvgEH7xyi&_nc_oc=Adio08h5EwoGwxxNdlpMj246lC9QL9OkPWGFj-RSt6Bpdn6ewODQv1HUtmNdRtrbxXs&_nc_zt=23&_nc_ht=scontent-los2-1.xx&_nc_gid=AEt93ddEgoNmeTzorTq8MtL&oh=00_AYFKKSmJZ22ja2YLY7_EclvZmxtX9yY_TDFebRRwKMNFWg&oe=67D22436" alt="Facebook Profile">
        </div>

        <!-- Left Face -->
        <div class="cube-face left">
            <img src="https://scontent-los2-1.xx.fbcdn.net/v/t1.15752-9/429952480_716210887294109_6532318400483501924_n.jpg?_nc_cat=107&ccb=1-7&_nc_sid=0024fc&_nc_eui2=AeHSfUy4OzbMIKQNdem4HX35ddpUTswYN3x12lROzBg3fERMpit4LsiGIzf45X4s1Y03nAAvBXLLCuD36s1Dg_TN&_nc_ohc=ZJbT5reXoroQ7kNvgHjynvH&_nc_oc=AdhN990DfK4auw76NQ3Rhdnd1tJQY9jB46mYbh5iOzhuWw-gmf2eg_2AHDGLwwbpA3wgnwbwlfHttKx8PIUKBzZ6&_nc_ad=z-m&_nc_cid=0&_nc_zt=23&_nc_ht=scontent-los2-1.xx&oh=03_Q7cD1wEiEgGg9CxAPuk3nYkhfvm_ea8WBFG3aYllWzDe2nz_Ww&oe=67F3B828" alt="Second Facebook Profile">
        </div>
    </div>

    <h1 style="text-align: center;">Ibrahim Jibrin Yahaya</h1>
    <h2 style="text-align: center;">Phoenix University Agwada</h2>
    <h2 style="text-align: center;">Semester: First (1st)</h2>

    <div class="content">
        <h1>Branch: Computer Science and Technology</h1>
    </div>

    <div style="background: green; text-align: center;">
        <h1 style="color: yellow;">I am a Student of Phoenix University Agwada</h1>
    </div>

    <div class="form-container">
        <form>
            <input type="text" placeholder="Username" required><br>
            <input type="text" placeholder="Email Address" required><br>
            <input type="password" placeholder="Password" required><br>
            <button type="submit">Send</button>
        </form>

        <p><a href="forgot password.html" style="color: blue; font-weight: bold; text-decoration: none;">Forgot password?</a></p>
        
        <input type="file">
        <input type="text" id="username" placeholder="Add a new task...">
        <button id="send">Add Task</button>
    </div>

    <div class="footer">
        <center>
            <h2>About Ibrahim Jibrin Yahaya</h2>
        </center>
        <p><b>Ibrahim Jibrin Yahaya</b> is a passionate student from Nigeria, studying at <b>Phoenix University Agwada.</b> With an interest in the ever-evolving world of technology, <b>Jibrin</b> is focusing on cybersecurity, <b>specifically in the area of ethical hacking.</b></p>
        <p>Ethical hacking, also known as penetration testing, involves simulating cyberattacks to find vulnerabilities in systems, helping organizations strengthen their security before malicious hackers can exploit them.</p>
        <p><b>Phoenix University Agwada:</b> Phoenix University Agwada is a higher education institution located in Agwada, Nigeria, offering a range of academic programs with an emphasis on developing practical and technical skills essential for the digital age.</p>
        <p><b>Course: Cybersecurity</b></p>
        <p>The cybersecurity program at Phoenix University Agwada prepares students for growing digital threats, including network security, cryptography, ethical hacking, and incident response. This combination of practical and theoretical knowledge makes Jibrin’s path toward becoming an ethical hacker exciting and highly relevant.</p>
    </div>
</div>

</body>
</html>

