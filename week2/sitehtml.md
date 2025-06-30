# CODE
>INDEX.HTML
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>ELVI'S WEBSITE</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <h1>ELVI'S WEBSITE</h1>

  <!-- About Me -->
  <div class="about-box">
    <h2>About Me</h2>
    <p>
      I'm a B.Tech Computer Science student from Kerala, studying at VJCET.<br>
      I'm passionate about exploring the latest trends in technology.<br>
      I enjoy analyzing, visualizing, and strategizing data to solve real-world problems.
    </p>
  </div>

  <!-- Skills -->
  <div class="skills-section">
    <h2>Skills</h2>
    <div class="skills-grid">
      <div class="skill-box">
        <strong>Python</strong>
        <p>Intermediate level</p>
      </div>
      <div class="skill-box">
        <strong>Excel</strong>
        <p>Intermediate level</p>
      </div>
      <div class="skill-box">
        <strong>SQL</strong>
        <p>Intermediate level</p>
      </div>
      <div class="skill-box">
        <strong>C</strong>
        <p>Intermediate level</p>
      </div>
      <div class="skill-box">
        <strong>CSS</strong>
        <p>Beginner level</p>
      </div>
      <div class="skill-box">
        <strong>Java</strong>
        <p>Beginner level</p>
      </div>
    </div>
  </div>

  <!-- Contact -->
  <div class="contact">
    <h2>Contact</h2>
    <p>LinkedIn: <a href="https://www.linkedin.com/in/elvi-rose-joshi" target="_blank">linkedin.com/in/elvi-rose-joshi</a></p>
    <p>Email: <a href="mailto:elvirose351@gmail.com">elvirose351@gmail.com</a></p>
  </div>

</body>
</html>
```
>STYLE.CSS
```
body {
  font-family: Arial, sans-serif;
  background-color: pink;
  color: #000;
  margin: 0;
  padding: 20px;
}

h1 {
  text-align: center;
  font-size: 36px;
  font-weight: bold;
  margin-bottom: 40px;
}

/* About Me Box */
.about-box {
  background-color: #fff;
  border-radius: 10px;
  padding: 20px;
  max-width: 700px;
  margin: 0 auto 40px auto;
  text-align: center;
  box-shadow: 0 0 10px rgba(0,0,0,0.1);
}

.about-box h2 {
  font-size: 24px;
  font-weight: bold;
  color: #000;
  margin-bottom: 10px;
}

/* Skills Section */
.skills-section {
  max-width: 900px;
  margin: 0 auto 40px auto;
  text-align: center;
}

.skills-section h2 {
  font-size: 24px;
  font-weight: bold;
  color: #000;
  margin-bottom: 20px;
}

.skills-grid {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 20px;
}

.skill-box {
  background-color: #fff;
  border: 2px solid #ff99cc;
  border-radius: 8px;
  padding: 15px;
  width: 200px;
  text-align: center;
  box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}

.skill-box strong {
  display: block;
  font-size: 18px;
  margin-bottom: 5px;
}

.skill-box p {
  margin: 0;
  font-size: 14px;
}

/* Contact Section */
.contact {
  text-align: center;
  margin-top: 40px;
}

.contact h2 {
  font-size: 24px;
  font-weight: bold;
  color: #000;
  margin-bottom: 10px;
}

a {
  color: darkblue;
  text-decoration: none;
}

a:hover {
  text-decoration: underline;
}
```
>OUTPUT
![image](https://github.com/user-attachments/assets/e263d083-0e5f-40e3-a607-b8e9d0a20957)
![image](https://github.com/user-attachments/assets/4b03ef86-23e6-48ea-926d-48cdd0695d96)

