<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Home</title>
    <style>
      img {
        width: 900px;
        height: 450px;
      }
      body {
        text-align: center;
        background-color: rgb(139, 231, 231);
      }

      h2 {
        font-size: 50px;
        border-bottom: 2px dotted black;
        border-radius: 50px;
      }
      body {
        scroll-behavior: smooth;
      }
      nav {
        text-align: center;
        background-color: aqua;
        border-radius: 50px;
        padding: 3px;
        position: fixed;
        top: 0;
        left: 0;
        width: 100%;
        text-align: center;
        z-index: 100;
      }
      ul {
        display: flex;
        justify-content: space-between;
        font-size: xx-large;
        list-style: none;
        font-size: 40px;
      }
      a {
        text-decoration: none;
        color: black;
        font-weight: bold;
      }
      a:hover {
        color: blue;
      }
      .Courses {
        background-color: aqua;
        border-radius: 50px;
      }
      .Home {
        background-color: aqua;
        border-radius: 50px;
        font-size: xx-large;
      }
      .course-list {
        display: flex;
        flex-direction: column;
        align-items: center;
        gap: 15px;
        background-color: aqua;
        font-weight: bold;
        border-radius: 50px;
      }
      span {
        font-size: xx-large;
      }
      #Contact-Us {
        background-color: aqua;
        border-radius: 50px;
      }
    </style>
  </head>
  <body>
    <nav>
      <ul>
        <li><a href="#Home">Home</a></li>
        <li><a href="#Courses">Courses</a></li>
        <li><a href="#Contact-Us">Contact-Us</a></li>
        <li><a href="Login.html">Login</a></li>
        <li><a href="register.html">Register</a></li>
        </ul>
    </nav>
    <img src="vit logo 1.jpeg" alt="logo" id="logo" />
    <div class="Home" id="Home">
      <h2>Home</h2>
      <p>
        VIT-AP University (VIT-AP), also known as Vellore Institute of Technology, Andhra Pradesh or VIT University, Andhra Pradesh, is a private research university located in Inavolu, Amaravati, the capital of Andhra Pradesh, India. The university was established in 2017 by the Vellore Institute of Technology through the Andhra Pradesh Private Universities (Establishment and Regulation) Act, 2016.[

The institution offers 19 Undergraduate,4 Postgraduate, 4 Integrated, 4 dual and 16 Research programs.
      </p>
      </div>
    <div class="Courses" id="Courses">
      <h2>Courses offered</h2>
      <ul class="course-list">
        <li>B.Tech</li>
        <li>BBA</li>
        <li>LAW</li>
        <li>B.A.-M.A.</li>
        <li>B.Sc.</li>
        <li>M.Sc.</li>
        <li>B.Com.</li>
        <li>M.TECH.</li>
        <li>International</li>
        <li>Ph.D.</li>
      </ul>
    </div>
    <div id="Contact-Us">
      <h2>Contact Us</h2>
      <span> Email : vitap123@gmail.com </span>
      <br />
      <span> Mobile : 9494502400</span>
    </div>
  </body>
</html>
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Register</title>

    <style>
      body {
        background-color: rgb(139, 231, 231);
      }
      .container {
        position: absolute;
        text-align: center;
        transform: translate(-50%, -50%);
        top: 50%;
        left: 50%;
        padding: 25px;
        border: solid 10px;
        border-width: 15px;
        width: 700px;
        height: 900px;
        font-weight: bold;
        margin: 5px;
        background-color: black;
      }
      options ul li a {
        text-decoration: none;
        color: black;
      }

      .robo {
        display: flex;
        padding: 20px;
        gap: 20px;
        flex-direction: column;
      }

      .hero {
        margin: 0 auto;
        font-size: 20px;
        font-weight: bold;
      }

      .hero-1 {
        display: flex;
        justify-content: center;
        gap: 8px;
      }
      ul li {
        list-style: none;
      }
      .options ul {
        display: flex;
        justify-content: space-between;
        list-style: none;
      }
    </style>
  </head>
  <body>
    <div class="container">
      <h1>Welcome to VIT-AP</h1>
      <h2>Register</h2>
      <img src="vit logo 1.jpeg" alt="logo" id="logo" />
      <form action="" class="robo">
        <div class="hero">
          <label for="name">Name:</label>
          <input type="text" id="name" name="name" required /><br />
        </div>

        <div class="hero">
          <label for="email">Email:</label>
          <input type="email" id="email" name="email" /><br />
        </div>

        <div class="hero">
          <label for="dob">Date of Birth:</label>
          <input type="date" id="dob" name="dob" required /><br />
          </div>

        <div class="hero">
          <label>Gender:</label>
        </div>

        <div class="hero hero-1">
          <label for="male">Male</label>
          <input type="radio" id="male" name="gender" value="male" required />
        </div>

        <div class="hero hero-1">
          <label for="female">Female</label>
          <input
            type="radio"
            id="female"
            name="gender"
            value="female"
            required
          />
        </div>

        <div class="hero hero-1">
          <label for="other">Other</label>
          <input
            type="radio"
            id="other"
            name="gender"
            value="other"
            required
          /><br />
        </div>

        <div class="hero">
          <label for="address">Address:</label>
          <input type="text" id="address" />
          <br />
        </div>

        <div class="hero">
          <label for="phone">Phone Number:</label>
          <input type="tel" id="phone" name="phone" required /><br />
        </div>

        <div class="hero">
          <label for="password">Password:</label>
          <input type="password" id="password" name="password" required /><br />
        </div>

        <div class="hero">
          <label for="confirm-password">Confirm Password:</label>
          <input
            type="password"
            id="confirm-password"
            name="confirm-password"
            required
          /><br />
        </div>

        <div class="hero">
          <input type="submit" value="Register" />
        </div>

        <div class="options">
          <ul>
            <li><a href="home.html">Home page</a></li>
            <li><a href="Login.html">Login page</a></li>
          </ul>
        </div>
      </form>
    </div>
  </body>
</html>
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Login</title>
    <style>
      body {
        background-color: rgb(139, 231, 231);
        text-align: center;
        margin: 5px;
      }
      #login {
        padding: 20px;
        font-size: x-large;
        border: 5px solid rgb(41, 41, 37);
        border-width: 15px;
        width: 500px;
        height: 500px;
        align-items: center;
        position: absolute;
        transform: translate(-50%, -50%);
        top: 50%;
        left: 50%;
        background-color: aqua;
      }
      .info {
        font-weight: bold;
      }

      .options ul {
        display: flex;
        justify-content: space-between;
        list-style: none;
      }
      .options ul li a {
        text-decoration: none;
        color: black;
      }

      h1 {
        border: 5px;
      }
      options:hover {
        color: red;
        cursor: pointer;
      }

      .robo {
        display: flex;
        padding: 20px;
        gap: 20px;
        flex-direction: column;
      }

      .hero {
        margin: 0 auto;
        font-size: 20px;
        font-weight: bold;
      }
    </style>
  </head>
  <body>
    <section id="login">
      <form>
      <h1>Welcome to VIT-AP</h1>
        <p>Learn and Explore</p>
        <img src="vit logo 1.jpeg" alt="logo" id="logo" />
        <br />
        <div class="info robo">
          <div class="hero">
            <label for="Email-id">Email-id</label>
            <input type="text" name="username" placeholder="Email-id" />
            <br />
          </div>

          <div class="hero">
            <label for="password">Password</label>
            <input type="password" placeholder="password" />
            <br />
          </div>
          </div>
        <input type="submit" value="login" />
        <br />
        <div class="options">
          <ul>
            <li><a href="#">forget password</a></li>
            <li><a href="register.html">Register now</a></li>
            <li><a href="home.html">Home page</a></li>
          </ul>
        </div>
      </form>
    </section>
  </body>
</html>
