# Assignment 4.5 — Multi-Page College Club Website

## 1. Aim

To design and develop a complete multi-page college club website using HTML and CSS, including a home page, about page, student registration form, contact details, event schedule, consistent navigation, metadata, and favicon.

## 2. Technologies Used

- HTML5
- CSS3
- Visual Studio Code
- Google Chrome

## 3. Project Folder Structure

Create a folder named `Assignment-4.5` with the following files:

```text
Assignment-4.5/
│
├── index.html
├── about.html
├── registration.html
├── contact.html
├── style.css
└── favicon.svg
```

## 4. Home Page — index.html

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Welcome to the College Tech Club. Explore technology, coding activities, workshops, and upcoming college events.">
    <meta name="author" content="Shubham Yadav">
    <title>Home | College Tech Club</title>
    <link rel="icon" type="image/svg+xml" href="favicon.svg">
    <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
    <h1>College Tech Club</h1>
    <p>Learn, Create, Innovate Together</p>
</header>

<nav>
    <a href="index.html" aria-current="page">Home</a>
    <a href="about.html">About Us</a>
    <a href="registration.html">Registration</a>
    <a href="contact.html">Contact</a>
</nav>

<main>
    <section class="hero">
        <h2>Welcome to the College Tech Club</h2>
        <p>
            The College Tech Club is a student community that encourages
            creativity, teamwork, programming, and technical learning.
        </p>
        <a class="button" href="registration.html">Join Our Club</a>
    </section>

    <section>
        <h2>Our Activities</h2>
        <div class="cards">
            <article class="card">
                <h3>Coding Competitions</h3>
                <p>Improve programming and problem-solving skills through coding challenges.</p>
            </article>

            <article class="card">
                <h3>Technical Workshops</h3>
                <p>Learn HTML, CSS, programming, web development, and emerging technologies.</p>
            </article>

            <article class="card">
                <h3>Project Development</h3>
                <p>Work in teams to build useful projects and explore innovative ideas.</p>
            </article>
        </div>
    </section>

    <section>
        <h2>Upcoming Events Schedule</h2>
        <div class="table-container">
            <table>
                <thead>
                    <tr>
                        <th>Event Name</th>
                        <th>Date</th>
                        <th>Venue</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>Web Development Workshop</td>
                        <td>10 November 2026</td>
                        <td>Computer Lab</td>
                    </tr>
                    <tr>
                        <td>Coding Competition</td>
                        <td>18 November 2026</td>
                        <td>Seminar Hall</td>
                    </tr>
                    <tr>
                        <td>Project Exhibition</td>
                        <td>25 November 2026</td>
                        <td>College Auditorium</td>
                    </tr>
                </tbody>
            </table>
        </div>
        <p class="note">Note: The event dates and venues are sample details for this assignment.</p>
    </section>

    <section>
        <h2>Why Join Us?</h2>
        <ul>
            <li>Develop technical and communication skills.</li>
            <li>Participate in workshops and competitions.</li>
            <li>Collaborate with other students.</li>
            <li>Build projects and gain practical experience.</li>
        </ul>
    </section>
</main>

<footer>
    <p>&copy; 2026 College Tech Club. All rights reserved.</p>
</footer>

</body>
</html>
```

## 5. About Page — about.html

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Learn about the College Tech Club, its mission, activities, and student team.">
    <meta name="author" content="Shubham Yadav">
    <title>About Us | College Tech Club</title>
    <link rel="icon" type="image/svg+xml" href="favicon.svg">
    <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
    <h1>About Our Club</h1>
    <p>Discover Our Mission and Community</p>
</header>

<nav>
    <a href="index.html">Home</a>
    <a href="about.html" aria-current="page">About Us</a>
    <a href="registration.html">Registration</a>
    <a href="contact.html">Contact</a>
</nav>

<main>
    <section>
        <h2>Introduction</h2>
        <p>
            The College Tech Club is a student-led community designed to
            promote technical knowledge, creativity, innovation, and
            collaboration among college students.
        </p>
        <p>
            The club provides opportunities to learn new technologies,
            participate in competitions, attend workshops, and develop
            real-world projects.
        </p>
    </section>

    <section>
        <h2>Our Mission</h2>
        <p>
            Our mission is to create a supportive environment where students
            can improve their technical skills, share ideas, solve problems,
            and prepare for future careers.
        </p>
    </section>

    <section>
        <h2>Our Activities</h2>
        <ul>
            <li>Web development workshops</li>
            <li>Programming and coding competitions</li>
            <li>Group projects and hackathons</li>
            <li>Technology seminars and presentations</li>
            <li>Peer learning and knowledge-sharing sessions</li>
        </ul>
    </section>

    <section>
        <h2>Club Members</h2>
        <div class="table-container">
            <table>
                <thead>
                    <tr>
                        <th>Member Name</th>
                        <th>Role</th>
                        <th>Responsibility</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>Rahul Sharma</td>
                        <td>Club President</td>
                        <td>Leadership and coordination</td>
                    </tr>
                    <tr>
                        <td>Priya Singh</td>
                        <td>Event Coordinator</td>
                        <td>Workshop and event management</td>
                    </tr>
                    <tr>
                        <td>Aman Verma</td>
                        <td>Technical Lead</td>
                        <td>Technical activities and projects</td>
                    </tr>
                    <tr>
                        <td>Shubham Yadav</td>
                        <td>Student Member</td>
                        <td>Learning and project participation</td>
                    </tr>
                </tbody>
            </table>
        </div>
        <p class="note">Note: Member names and roles are illustrative examples.</p>
    </section>

    <section class="center">
        <h2>Become a Member</h2>
        <p>Join our community and start your technical learning journey.</p>
        <a class="button" href="registration.html">Register Now</a>
    </section>
</main>

<footer>
    <p>&copy; 2026 College Tech Club. All rights reserved.</p>
</footer>

</body>
</html>
```

## 6. Registration Page — registration.html

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Register as a student member of the College Tech Club using our student registration form.">
    <meta name="author" content="Shubham Yadav">
    <title>Registration | College Tech Club</title>
    <link rel="icon" type="image/svg+xml" href="favicon.svg">
    <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
    <h1>Club Registration</h1>
    <p>Become a Part of Our Community</p>
</header>

<nav>
    <a href="index.html">Home</a>
    <a href="about.html">About Us</a>
    <a href="registration.html" aria-current="page">Registration</a>
    <a href="contact.html">Contact</a>
</nav>

<main>
    <section class="form-section">
        <h2>Student Registration Form</h2>
        <p>Fill in the following details to register for the College Tech Club.</p>

        <form action="#" method="get">
            <div class="form-group">
                <label for="fullname">Full Name:</label>
                <input type="text" id="fullname" name="fullname"
                       placeholder="Enter your full name"
                       autocomplete="name" required>
            </div>

            <div class="form-group">
                <label for="email">Email Address:</label>
                <input type="email" id="email" name="email"
                       placeholder="Enter your email"
                       autocomplete="email" required>
            </div>

            <div class="form-group">
                <label for="phone">Mobile Number:</label>
                <input type="tel" id="phone" name="phone"
                       placeholder="Enter your mobile number"
                       autocomplete="tel" pattern="[0-9]{10}"
                       title="Enter a 10-digit mobile number" required>
            </div>

            <div class="form-group">
                <label for="studentid">Student ID:</label>
                <input type="text" id="studentid" name="studentid"
                       placeholder="Enter your student ID" required>
            </div>

            <div class="form-group">
                <label for="course">Course:</label>
                <select id="course" name="course" required>
                    <option value="">Select your course</option>
                    <option value="BTech CSE">B.Tech CSE</option>
                    <option value="BTech IT">B.Tech IT</option>
                    <option value="BCA">BCA</option>
                    <option value="BBA">BBA</option>
                    <option value="Other">Other</option>
                </select>
            </div>

            <fieldset>
                <legend>Year of Study:</legend>

                <label class="radio-label">
                    <input type="radio" name="year" value="First Year" required>
                    First Year
                </label>

                <label class="radio-label">
                    <input type="radio" name="year" value="Second Year">
                    Second Year
                </label>

                <label class="radio-label">
                    <input type="radio" name="year" value="Third Year">
                    Third Year
                </label>

                <label class="radio-label">
                    <input type="radio" name="year" value="Fourth Year">
                    Fourth Year
                </label>
            </fieldset>

            <div class="form-group">
                <label for="interest">Area of Interest:</label>
                <select id="interest" name="interest" required>
                    <option value="">Select an area</option>
                    <option value="Web Development">Web Development</option>
                    <option value="Programming">Programming</option>
                    <option value="Artificial Intelligence">Artificial Intelligence</option>
                    <option value="Cybersecurity">Cybersecurity</option>
                    <option value="Other">Other</option>
                </select>
            </div>

            <div class="form-group">
                <label for="reason">Why do you want to join?</label>
                <textarea id="reason" name="reason" rows="4"
                          placeholder="Write a few lines about your interests"
                          required></textarea>
            </div>

            <div class="form-group checkbox-group">
                <label>
                    <input type="checkbox" name="agreement" value="yes" required>
                    I confirm that the information provided is correct.
                </label>
            </div>

            <button type="submit" class="button">Submit Registration</button>
            <button type="reset" class="button secondary">Reset Form</button>
        </form>

        <p class="note">
            This is a front-end demonstration form. It does not store or send
            registration details to a server.
        </p>
    </section>
</main>

<footer>
    <p>&copy; 2026 College Tech Club. All rights reserved.</p>
</footer>

</body>
</html>
```

## 7. Contact Page — contact.html

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Contact the College Tech Club for information about membership, workshops, activities, and events.">
    <meta name="author" content="Shubham Yadav">
    <title>Contact Us | College Tech Club</title>
    <link rel="icon" type="image/svg+xml" href="favicon.svg">
    <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
    <h1>Contact Us</h1>
    <p>We Would Love to Hear From You</p>
</header>

<nav>
    <a href="index.html">Home</a>
    <a href="about.html">About Us</a>
    <a href="registration.html">Registration</a>
    <a href="contact.html" aria-current="page">Contact</a>
</nav>

<main>
    <section>
        <h2>Get in Touch</h2>
        <p>
            If you want to join the club, participate in our activities,
            or learn more about upcoming events, contact us using the
            details below.
        </p>

        <div class="contact-card">
            <h3>Email Address</h3>
            <p><a href="mailto:techclub@example.com">techclub@example.com</a></p>

            <h3>College Location</h3>
            <p>College Campus, Bareilly, Uttar Pradesh, India</p>

            <h3>Contact Number</h3>
            <p><a href="tel:+910000000000">+91 00000 00000</a></p>

            <h3>Office Hours</h3>
            <p>Monday to Friday: 10:00 AM – 4:00 PM</p>
        </div>

        <p class="note">
            Note: The email, telephone number, location, and office hours
            are sample details. Replace them with verified college club
            contact information before publishing.
        </p>
    </section>

    <section>
        <h2>Quick Links</h2>
        <ul>
            <li><a href="index.html">Visit the Home Page</a></li>
            <li><a href="about.html">Learn About Our Club</a></li>
            <li><a href="registration.html">Register as a Member</a></li>
        </ul>
    </section>
</main>

<footer>
    <p>&copy; 2026 College Tech Club. All rights reserved.</p>
</footer>

</body>
</html>
```

## 8. CSS File — style.css

Create `style.css` in the same folder and paste the complete code below. All four pages use this single stylesheet to maintain a consistent design.

```css
/* Global Styles */
* {
    box-sizing: border-box;
}

html {
    scroll-behavior: smooth;
}

body {
    margin: 0;
    font-family: Arial, Helvetica, sans-serif;
    line-height: 1.6;
    color: #263238;
    background-color: #f3f6fb;
}

a {
    color: #1559a6;
}

a:hover {
    color: #0b376b;
}

/* Header */
header {
    background: linear-gradient(135deg, #12356a, #2879bd);
    color: #ffffff;
    text-align: center;
    padding: 35px 15px;
}

header h1 {
    margin: 0;
    font-size: 34px;
}

header p {
    margin-bottom: 0;
}

/* Navigation */
nav {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    gap: 8px;
    padding: 12px;
    background-color: #10294f;
}

nav a {
    color: #ffffff;
    text-decoration: none;
    padding: 9px 16px;
    border-radius: 5px;
    font-weight: bold;
}

nav a:hover,
nav a[aria-current="page"] {
    background-color: #2879bd;
    color: #ffffff;
}

/* Main Layout */
main {
    width: 92%;
    max-width: 1050px;
    margin: 28px auto;
}

section {
    background-color: #ffffff;
    padding: 25px;
    margin-bottom: 24px;
    border-radius: 10px;
    box-shadow: 0 3px 12px rgba(20, 50, 90, 0.08);
}

section h2 {
    margin-top: 0;
    color: #12356a;
}

section h3 {
    color: #205b98;
}

.hero {
    text-align: center;
    padding: 45px 25px;
    background-color: #e5efff;
}

.hero h2 {
    font-size: 30px;
}

.hero p {
    max-width: 700px;
    margin: 15px auto 25px;
}

/* Activity Cards */
.cards {
    display: grid;
    grid-template-columns: repeat(3, minmax(0, 1fr));
    gap: 18px;
}

.card {
    padding: 20px;
    background-color: #f3f7fd;
    border: 1px solid #dce7f5;
    border-radius: 8px;
}

.card h3 {
    margin-top: 0;
}

/* Buttons */
.button {
    display: inline-block;
    border: none;
    border-radius: 5px;
    padding: 11px 20px;
    margin: 5px 5px 5px 0;
    background-color: #1765ad;
    color: #ffffff;
    text-decoration: none;
    font-size: 15px;
    font-weight: bold;
    cursor: pointer;
}

.button:hover {
    background-color: #104879;
    color: #ffffff;
}

.button.secondary {
    background-color: #5d6877;
}

.button.secondary:hover {
    background-color: #3e4753;
}

/* Tables */
.table-container {
    overflow-x: auto;
}

table {
    width: 100%;
    border-collapse: collapse;
    margin-top: 15px;
}

th,
td {
    border: 1px solid #d5dfeb;
    padding: 12px;
    text-align: left;
}

th {
    background-color: #173b70;
    color: #ffffff;
}

tbody tr:nth-child(even) {
    background-color: #f1f5fa;
}

/* Registration Form */
.form-section {
    max-width: 760px;
    margin-left: auto;
    margin-right: auto;
}

.form-group {
    margin-bottom: 18px;
}

.form-group > label,
.form-group label:first-child {
    display: block;
    margin-bottom: 7px;
    font-weight: bold;
}

input:not([type="radio"]):not([type="checkbox"]),
select,
textarea {
    width: 100%;
    padding: 12px;
    border: 1px solid #bdc9d8;
    border-radius: 5px;
    font-family: inherit;
    font-size: 15px;
    background-color: #ffffff;
}

input:focus,
select:focus,
textarea:focus {
    outline: 2px solid #2879bd;
    outline-offset: 1px;
}

fieldset {
    border: 1px solid #bdc9d8;
    border-radius: 5px;
    padding: 15px;
    margin: 0 0 20px;
}

legend {
    padding: 0 6px;
    font-weight: bold;
}

.radio-label {
    display: inline-flex;
    align-items: center;
    gap: 6px;
    margin: 5px 14px 5px 0;
}

.checkbox-group label {
    display: flex;
    align-items: flex-start;
    gap: 8px;
    font-weight: normal;
}

.checkbox-group input {
    margin-top: 6px;
}

/* Contact Details */
.contact-card {
    padding: 20px;
    border-left: 4px solid #2879bd;
    background-color: #f3f7fd;
    border-radius: 5px;
}

.contact-card h3 {
    margin-bottom: 3px;
}

.contact-card p {
    margin-top: 3px;
}

.center {
    text-align: center;
}

.note {
    color: #5c6878;
    font-size: 13px;
}

/* Footer */
footer {
    margin-top: 35px;
    padding: 18px;
    text-align: center;
    background-color: #10294f;
    color: #ffffff;
}

footer p {
    margin: 0;
}

/* Responsive Design */
@media (max-width: 700px) {
    header h1 {
        font-size: 27px;
    }

    nav {
        gap: 4px;
    }

    nav a {
        padding: 9px 10px;
        font-size: 14px;
    }

    main {
        width: 94%;
        margin: 18px auto;
    }

    section {
        padding: 18px;
    }

    .cards {
        grid-template-columns: 1fr;
    }

    .hero h2 {
        font-size: 24px;
    }

    th,
    td {
        padding: 9px;
    }
}
```

## 9. Favicon — favicon.svg

Create `favicon.svg` in the same folder and paste the following code:

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100">
    <rect width="100" height="100" rx="20" fill="#173b70"/>
    <text x="50" y="68"
          font-family="Arial, sans-serif"
          font-size="48"
          font-weight="bold"
          text-anchor="middle"
          fill="#ffffff">T</text>
</svg>
```

The favicon displays a white letter T on a blue background, representing the Tech Club.

All four HTML files include the following metadata:

```html
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="description" content="Page-specific description">
<link rel="icon" type="image/svg+xml" href="favicon.svg">
<link rel="stylesheet" href="style.css">
```

Each page also has its own meaningful `<title>` element and meta description.

## 10. Procedure

1. Created a project folder named `Assignment-4.5`.
2. Created four HTML files: `index.html`, `about.html`, `registration.html`, and `contact.html`.
3. Added consistent navigation links to all four pages.
4. Added the club introduction and activities to the home page.
5. Added club details and a member information table to the about page.
6. Created a student registration form with text fields, email, telephone, dropdowns, radio buttons, a checkbox, and submit/reset buttons.
7. Added email, location, telephone, and office hours to the contact page.
8. Created an event schedule table on the home page.
9. Added metadata, page titles, favicon links, and CSS links to every HTML page.
10. Applied common styling and responsive design using CSS.
11. Tested internal navigation and verified that the pages open correctly.

## 11. Testing Checklist

- [ ] Home page opens correctly.
- [ ] About Us link opens `about.html`.
- [ ] Registration link opens `registration.html`.
- [ ] Contact link opens `contact.html`.
- [ ] Navigation is consistent across all pages.
- [ ] Event schedule and member tables display correctly.
- [ ] Registration form validates required fields.
- [ ] CSS styling works on all pages.
- [ ] Favicon appears in the browser tab.
- [ ] Pages adapt to mobile screen sizes.
- [ ] No internal links point to missing files.

## 12. Result

A complete multi-page College Tech Club website was developed using HTML and CSS. It includes four interconnected pages, consistent navigation, club activities, member information, a student registration form, contact details, an event schedule, metadata, a favicon, and responsive styling.

## 13. Submission

Submit the following files:

1. `index.html`
2. `about.html`
3. `registration.html`
4. `contact.html`
5. `style.css`
6. `favicon.svg`
7. `Assignment-4.5.md`
8. Browser screenshots showing the website pages and favicon.

For screenshots, open each HTML page in Chrome, verify the page content and browser tab, and take screenshots using `Windows + Shift + S`. Save them as `home.png`, `about.png`, `registration.png`, and `contact.png`.

## Conclusion

This assignment demonstrates the practical use of HTML5 and CSS3 to create a structured, responsive, and interconnected college club website with reusable styling, metadata, forms, tables, and navigation.
