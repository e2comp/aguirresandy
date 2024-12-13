<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Website</title>
    <style>
        body {
            background-color: #e1bee7; /* light violet */
            color: #5e35b1; /* deep violet */
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            text-align: center;
            padding: 20px;
            background-color: #673ab7; /* deep violet */
            color: white;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #5e35b1; /* deep violet */
            padding: 10px;
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 10px 20px;
            margin: 0 10px;
            border-radius: 5px;
            background-color: #7e57c2; /* lighter violet */
        }
        nav a:hover {
            background-color: #9c27b0; /* hover effect */
        }
        main {
            text-align: center;
            padding: 50px 20px;
        }
        button {
            padding: 15px 30px;
            margin: 10px;
            background-color: #7e57c2;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        button:hover {
            background-color: #9c27b0;
        }
        .content {
            padding: 20px;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin-bottom: 20px;
        }
        table,
        th,
        td {
            border: 1px solid #5e35b1;
        }
        th,
        td {
            padding: 10px;
            text-align: left;
        }
        th {
            background-color: #7e57c2;
        }
        iframe {
            width: 100%;
            height: 400px;
        }
        form {
            max-width: 500px;
            margin: auto;
            padding: 20px;
            border: 1px solid #5e35b1;
            border-radius: 8px;
            background-color: #7e57c2;
            color: white;
        }
        label {
            display: block;
            margin: 10px 0 5px;
        }
        input[type="text"],
        input[type="password"],
        select,
        textarea {
            width: 100%;
            padding: 8px;
            border-radius: 5px;
            border: 1px solid #5e35b1;
            margin-bottom: 15px;
            background-color: #9c27b0;
            color: white;
        }
        input[type="radio"],
        input[type="checkbox"] {
            margin-right: 5px;
        }
        img {
            max-width: 100%;
            height: auto;
            margin: 20px 0;
        }
        audio {
            display: block;
            margin: 40px auto;
            width: 100%;
        }
    </style>
</head>

<body>
    <!-- Home Page -->
    <header>
        <h1>AGUIRRE, SANDRA JOANNA</h1>
        <h2>II-INDIA</h2>
        <h3>E2 COMPUTER LAB EXERCISES</h3>
    </header>
    <main>
        <h2>Choose a Section to Explore</h2>
        <button onclick="document.getElementById('article').scrollIntoView()">Go to Article</button>
        <button onclick="document.getElementById('blog').scrollIntoView()">Go to Blog</button>
        <button onclick="document.getElementById('form').scrollIntoView()">Go to Form</button>
    </main>
    <!-- Article Page -->
    <div id="article" class="content">
        <h2>What is Plagiarism?</h2>
        <p>Plagiarism, the act of presenting someone else's work or ideas as your own without proper attribution, is a pervasive issue across various fields, from academia to journalism and even politics. It undermines the integrity of intellectual property and erodes trust in the originality of creative works. This article delves into the nature of plagiarism, explores notable cases, and examines the legal consequences in different countries.</p>
        <h3>Notable Cases of Plagiarism and its Consequences</h3>
        <ul>
            <li><strong>Stephen Ambrose (2002):</strong> The renowned historian was accused of plagiarizing passages from other authors' works in several of his books. While he apologized and admitted to errors, the scandal tarnished his reputation.</li>
            <li><strong>Alex Haley (1978):</strong> The author of "Roots" was sued for plagiarism after it was discovered that portions of his book were strikingly similar to Harold Courlander's "The African." Haley eventually admitted to borrowing material without proper attribution.</li>
            <li><strong>"Blurred Lines" (2013):</strong> The popular song by Robin Thicke and Pharrell Williams was found to have significant similarities to Marvin Gaye's "Got to Give It Up." Gaye's family sued for copyright infringement, and a jury ultimately ruled in their favor.</li>
        </ul>
        <h3>International Perspectives: IP Laws and Penalties</h3>
        <table>
            <tr>
                <th>Country</th>
                <th>IP Laws and Penalties</th>
            </tr>
            <tr>
                <td>India</td>
                <td>While there is no specific "plagiarism act," plagiarism falls under copyright infringement provisions. The Copyright Act of 1957 includes sections that address unauthorized reproduction and distribution of copyrighted works. Penalties can range from imprisonment for 6 months to 3 years.</td>
            </tr>
            <tr>
                <td>United States</td>
                <td>Copyright law in the US protects original works of authorship, including literary, dramatic, musical, and artistic works. Plagiarism can be considered copyright infringement, with penalties including fines and imprisonment.</td>
            </tr>
            <tr>
                <td>United Kingdom</td>
                <td>The Copyright, Designs and Patents Act 1988 protects original literary, dramatic, musical, and artistic works. Plagiarism can be considered copyright infringement, with penalties including fines and imprisonment.</td>
            </tr>
        </table>
        <h3>Watch the Video on Plagiarism</h3>
        <iframe src="https://m.youtube.com/watch?v=uAmm5YSe_us&pp=ygUKcGxhZ2lhcmlzbQ%3D%3D" frameborder="0" allowfullscreen></iframe>
    </div>
    <!-- Blog Page -->
    <div id="blog" class="content">
        <h2>Viruses, Malware, Spam, and Antiviruses</h2>
        <h3>What are Computer Viruses?</h3>
        <p>Viruses are malicious programs designed to replicate themselves and spread to other systems. They can corrupt files, steal personal information, or even take control of your computer. Think of them as digital parasites, latching onto your system and causing damage.</p>
        <img src="Messenger_creation_4F30216D-5834-43D2-BC19-36F83B035DFB.jpeg" alt="Computer Virus Image" />
        <h3>What is Malware?</h3>
        <p>Malware encompasses a broader range of malicious software, including viruses, worms, Trojans, and spyware. While viruses primarily replicate themselves, malware can perform various malicious actions, such as stealing data, monitoring keystrokes, or even launching denial-of-service attacks. Malware often enters your system through infected downloads, phishing emails, or malicious websites.</p>
        <h3>What is Spam?</h3>
        <p>Spam, also known as junk mail, refers to unsolicited and unwanted electronic messages, primarily emails. While not inherently malicious, spam can be annoying, clog up your inbox, and potentially lead to phishing attacks. It often promotes dubious products, services, or scams, attempting to lure you into clicking on malicious links or providing personal information.</p>
        <h3>What are Antiviruses?</h3>
        <p>Antiviruses are software programs designed to protect your computer from malicious threats. They work by identifying and removing viruses, malware, and other harmful programs. Antiviruses typically use a combination of techniques, including signature-based detection, heuristic analysis, and behavioral monitoring.</p>
    </div>
    <!-- Form Page -->
    <div id="form" class="content">
        <h2>Volleyball Feedback Form</h2>
        <form action="#" method="POST">
            <label for="name">Full Name:</label>
            <input type="text" id="name" name="name" placeholder="Enter your full name" required>
            <label for="password">Password:</label>
            <input type="password" id="password" name="password" placeholder="Enter a password" required>
            <label for="team">Select Your Team:</label>
            <select id="team" name="team">
                <option value="TeamA">Team A</option>
                <option value="TeamB">Team B</option>
                <option value="TeamC">Team C</option>
            </select>
            <label>Preferred Position:</label>
            <input type="radio" id="setter" name="position" value="Setter" required>
            <label for="setter">Setter</label>
            <input type="radio" id="spiker" name="position" value="Spiker">
            <label for="spiker">Spiker</label>
            <input type="radio" id="libero" name="position" value="Libero">
            <label for="libero">Libero</label>
            <label for="feedback">Feedback:</label>
            <textarea id="feedback" name="feedback" rows="4" placeholder="Your feedback about volleyball..." required></textarea>
            <label for="newsletter">
                <input type="checkbox" id="newsletter" name="newsletter" value="Yes">
                Subscribe to the Volleyball Newsletter
            </label>
            <button type="submit">Submit</button>
        </form>
    </div>
    <!-- Embedded Audio -->
    <audio controls>
        <source src="videoplayback (8).webm" type="audio/mp3">
        Your browser does not support the audio element.
    </audio>

</body>

</html>
