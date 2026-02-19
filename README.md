# super-fortnight
A simple personal blog website to share thoughts, services, and a gallery.
<!DOCTYPE html><html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Alphonso Blog</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #ffffff;
            color: #333;
        }
        header {
            background-color: #c1121f;
            color: white;
            text-align: center;
            padding: 20px;
        }
        nav {
            background-color: #0033a0;
            text-align: center;
            padding: 10px;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }
        nav a:hover {
            text-decoration: underline;
        }
        section {
            padding: 40px 20px;
            text-align: center;
        }
        .services, .gallery {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
        }
        .card {
            background: #f4f4f4;
            padding: 20px;
            width: 250px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
        }
        .gallery-box {
            background: #e9ecef;
            height: 150px;
            display: flex;
            align-items: center;
            justify-content: center;
            border-radius: 10px;
        }
        .contact-form input,
        .contact-form textarea {
            width: 90%;
            padding: 10px;
            margin: 10px 0;
            border-radius: 5px;
            border: 1px solid #ccc;
        }
        .contact-form button {
            background-color: #c1121f;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .contact-form button:hover {
            background-color: #a50f1a;
        }
        footer {
            background-color: #c1121f;
            color: white;
            text-align: center;
            padding: 15px;
        }
    </style>
</head>
<body><header>
    <h1>Alphonso Blog</h1>
    <p>Sharing Ideas, Stories & Inspiration</p>
</header><nav>
    <a href="#services">Services</a>
    <a href="#gallery">Gallery</a>
    <a href="#contact">Contact</a>
</nav><section>
    <h2 style="color:#0033a0;">Welcome to Alphonso Blog</h2>
    <p>A simple space where I share my thoughts, experiences, and professional services.</p>
</section><section id="services">
    <h2 style="color:#c1121f;">Services</h2>
    <div class="services">
        <div class="card">
            <h3>Content Writing</h3>
            <p>Professional blog posts and creative writing tailored to your needs.</p>
        </div>
        <div class="card">
            <h3>Public Speaking</h3>
            <p>Motivational and educational speaking engagements.</p>
        </div>
        <div class="card">
            <h3>Consultation</h3>
            <p>Guidance and advisory services for personal and project growth.</p>
        </div>
    </div>
</section><section id="gallery">
    <h2 style="color:#0033a0;">Gallery</h2>
    <div class="gallery">
        <div class="gallery-box">Image 1</div>
        <div class="gallery-box">Image 2</div>
        <div class="gallery-box">Image 3</div>
    </div>
</section><section id="contact">
    <h2 style="color:#c1121f;">Contact</h2>
    <div class="contact-form">
        <input type="text" placeholder="Your Name">
        <input type="email" placeholder="Your Email">
        <textarea rows="5" placeholder="Your Message"></textarea>
        <br>
        <button>Send Message</button>
    </div>
</section><footer>
    <p>© 2026 Alphonso Blog. All Rights Reserved.</p>
</footer></body>
</html>
