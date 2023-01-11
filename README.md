# Developer-Portfolio
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Assignment</title>
    <link rel="stylesheet" href="styles.css">
</head>
<header class="header">
    <h1>All Thinks Are<br>
        Possible If You<br>
        believe</h1>
        <p>There are many variations of passages of Lorem Ipsum<br>
            available, but the majority have suffered alteration in some<br>
            form, by injected humour, or randomised words</p>
            <button class="button">Contact Us</button>
</header>
<body>
    <section class="second">
        <h1>
            My failures of<br>
    previous year
        </h1>
        <p>Contrary to popular belief, Lorem Ipsum is not<br>
            simply random text. It has roots in a piece of<br>
            classical Latin literature from 45 BC, making it over<br>
            2000 years old. Richard McClintock.</p>
    </section>
    <section class="plans">
        <h1>My Plans</h1>
    </section>
    <section>
        <div class="plans-container">
            <div class="plans-info">
                <img src="Image/web.png" alt="">
                <p class="plans-title">Web Development</p>
                <p class="plan-description">I want to start</p>
            </div>
            <div class="plans-info">
                <img src="Image/js.png" alt="">
                <p class="plans-title">Javascript</p>
                <p class="plan-description">I want to learn</p>
            </div>
            <div class="plans-info">
                <img src="Image/smoke.png" alt="">
                <p class="plans-title">Smoking Habit</p>
                <p class="plan-description">I want to end</p>
            </div>
            <div class="plans-info">
                <img src="Image/ecom.png" alt="">
                <p class="plans-title">Ecommerce</p>
                <p class="plan-description">I want to develop</p>
            </div>
        </div>
    </section>
    <section>
        <div class="gradient">
        <h1>Awlays keep a positive<br>
            mindset</h1>
            <button>Call Now</button>
        </div>
    </section>
    <section>
        <footer>
            <h1>Future</h1>
            <p>There are many variations of passages of Lorem Ipsum<br>
                available, but the majority have suffered alteration in some<br>
                form, by injected humour, or randomised words</p>

                <a href="mailto:info@gmail.com">Email : info@gmail.com</a>
                <p>Phone : 01500 00 00 00</p>
                <img src="Image/fb.png" alt="">
                <img src="Image/twitter.png" alt="">
                <img src="Image/youtube.png" alt="">
                <div class="send">
                    <h2>Subscribe</h2>
                    <input type="text" placeholder="Enter your email"><br>
                    <button class="last">Subscribe</button>
                </div>
        </footer>
    </section>
</body>
</html>

#CSS
.header{
    height: 950px;
    background-image: url(../Projects-01/Image/banner1.png);
    background-size: cover;
    background-repeat: no-repeat;
    text-align: right;
    font-size: 30px;
    border-radius: 5px;
}
button{
    background-color: orange;
    color: white;
    text-align: center;
    font-weight: bold;
    font-size: 18px;
    border-radius: 5px;
    text-decoration: none;
    width: 160px;
    padding: 20px;
    border: none;
    text-transform: capitalize;
    cursor: pointer;
}
.second {
    background-image: url(../Projects-01/Image/person.png);
    background-size: contain;
    background-repeat: no-repeat;
    background-position: center;
    top: 600px;
    text-align: right;
}
.plans {
    text-align: center;
    font-size: 40px;
}
.plans-container {
    justify-content: center;
    display: flex;
    text-align: center;
}
.plans-title {
    text-align: center;
    font-weight: bold;
    font-size: 22px;
    font-size: 20px;
    box-shadow: 0px 6px 50px rgba(rgb(17, 0, 0), green, blue, alpha);
    border-radius: 5px;
    padding-inline: 80px;
}
.plan-description {
    text-align: center;
    font-size: medium;
    color: darkgrey;
    box-shadow: 0px 6px 50px rgba(rgb(17, 0, 0), green, blue, alpha);
    border-radius: 5px;
    padding-inline: 80px;
}
.gradient {
    background-image: url(../Projects-01/Image/watch.png);
    background-origin: padding-box;
    background-repeat: no-repeat;
    background-size: cover;
    height: 45vh;
    justify-content: space-between;
    padding-top: 50px;
    font-size: 50px;
    color: white;
}
footer, a {
    text-decoration: white;
    font-size: 25px;
    background-color: black;
    color: white;
}
.send {
    text-align: right;
}
.last {
    background-color: white;
    color: orange;
    margin-top: 50px;
}
input{
    color: white;
    border-color: white;
    border-radius: 5px;
    padding: 15px;
    background-color: black;
}
