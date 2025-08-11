    <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Enhanced Form and Content</title>
</head>
<body>

<header>
    <h1>Welcome to My Multi-Section Web Page</h1>
    <nav>
        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#table">Comparison Table</a></li>
            <li><a href="#media">Media Showcase</a></li>
            <li><a href="#form">Registration Form</a></li>
        </ul>
    </nav>
</header>

<main>
    <!-- ABOUT SECTION WITH LISTS -->
    <section id="about">
        <h2>About This Page</h2>
        <p>This page demonstrates:</p>
        <ol>
            <li>Using lists and tables for clarity</li>
            <li>Embedding media content</li>
            <li>Building accessible, validated HTML5 forms</li>
        </ol>
        <h3>Technologies Used</h3>
        <ul>
            <li>HTML5 semantic tags</li>
            <li>Native HTML5 form validation</li>
            <li>Accessible structures</li>
        </ul>
    </section>

    <!-- TABLE SECTION -->
    <section id="table">
        <h2>Comparison Table</h2>
        <table border="1">
            <caption>Feature Comparison</caption>
            <thead>
                <tr>
                    <th>Feature</th>
                    <th>Option A</th>
                    <th>Option B</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Cost</td>
                    <td>Low</td>
                    <td>High</td>
                </tr>
                <tr>
                    <td>Ease of Use</td>
                    <td>Medium</td>
                    <td>High</td>
                </tr>
                <tr>
                    <td>Performance</td>
                    <td>Good</td>
                    <td>Excellent</td>
                </tr>
            </tbody>
        </table>
    </section>

    <!-- MEDIA SECTION -->
    <section id="media">
        <h2>Media Showcase</h2>
        <figure>
            <img src="https://via.placeholder.com/300" alt="Sample placeholder image">
            <figcaption>Sample Image</figcaption>
        </figure>
        <figure>
            <audio controls>
                <source src="sample-audio.mp3" type="audio/mpeg">
                Your browser does not support the audio element.
            </audio>
            <figcaption>Sample Audio</figcaption>
        </figure>
        <figure>
            <video controls width="320">
                <source src="sample-video.mp4" type="video/mp4">
                Your browser does not support the video tag.
            </video>
            <figcaption>Sample Video</figcaption>
        </figure>
    </section>

    <!-- FORM SECTION -->
    <section id="form">
        <h2>Registration Form</h2>
        <form action="#" method="post">
            <fieldset>
                <legend>Personal Information</legend>
                <label for="fullname">Full Name:</label>
                <input type="text" id="fullname" name="fullname" placeholder="John Doe" required minlength="3">
                <br><br>

                <label for="email">Email:</label>
                <input type="email" id="email" name="email" placeholder="example@mail.com" required>
                <br><br>

                <label for="phone">Phone Number:</label>
                <input type="tel" id="phone" name="phone" placeholder="123-456-7890" pattern="[0-9]{3}-[0-9]{3}-[0-9]{4}" required>
                <small>Format: 123-456-7890</small>
                <br><br>

                <label for="dob">Date of Birth:</label>
                <input type="date" id="dob" name="dob" required>
                <br><br>

                <label for="gender">Gender:</label>
                <select id="gender" name="gender" required>
                    <option value="">--Select--</option>
                    <option value="male">Male</option>
                    <option value="female">Female</option>
                    <option value="other">Other</option>
                </select>
            </fieldset>

            <fieldset>
                <legend>Account Details</legend>
                <label for="username">Username:</label>
                <input type="text" id="username" name="username" required minlength="5" autocomplete="username">
                <br><br>

                <label for="password">Password:</label>
                <input type="password" id="password" name="password" required minlength="8" placeholder="At least 8 characters" autocomplete="new-password">
                <br><br>

                <label for="confirm-password">Confirm Password:</label>
                <input type="password" id="confirm-password" name="confirm-password" required minlength="8" autocomplete="new-password">
            </fieldset>

            <fieldset>
                <legend>Preferences</legend>
                <label><input type="checkbox" name="subscribe" value="newsletter"> Subscribe to newsletter</label>
                <br>
                <label><input type="radio" name="contact" value="email" required> Contact me by Email</label>
                <br>
                <label><input type="radio" name="contact" value="phone"> Contact me by Phone</label>
            </fieldset>

            <fieldset>
                <legend>Read-only Information</legend>
                <label for="refcode">Referral Code:</label>
                <input type="text" id="refcode" name="refcode" value="ABC123" readonly>
            </fieldset>

            <br>
            <button type="submit">Submit</button>
            <button type="reset">Reset</button>
        </form>
    </section>

</main>

<footer>
    <p>&copy; 2025 My Enhanced Web Page</p>
</footer>

</body>
</html>
