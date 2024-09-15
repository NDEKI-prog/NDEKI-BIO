#include <stdio.h>

//Compiler version gcc  6.3.0

int main()
{
  printf("Hello, World!");
  return 0;
}
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cosmas Ndeki - EVERYTHING</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 1em 0;
            text-align: center;
        }
        main {
            padding: 20px;
            max-width: 800px;
            margin: auto;
            background-color: #fff;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        section {
            margin-bottom: 20px;
        }
        h2 {
            color: #333;
        }
        .gallery img {
            width: 100%;
            height: auto;
            margin-bottom: 10px;
        }
        form {
            display: flex;
            flex-direction: column;
        }
        form input, form textarea {
            margin-bottom: 10px;
            padding: 10px;
            font-size: 16px;
        }
        form button {
            padding: 10px;
            background-color: #333;
            color: #fff;
            border: none;
            cursor: pointer;
        }
        form button:hover {
            background-color: #555;
        }
    </style>
</head>
<body>

<header>
    <h1>Cosmas Ndeki - EVERYTHING</h1>
    <p>University Graduate | Universe Enthusiast</p>
</header>

<main>
    <section>
        <h2>About Me</h2>
        <p>Hello! My name is Cosmas Ndeki, but you can call me EVERYTHING. I am a university graduate with a deep passion for universe and space exploration. As my name suggests "Cosmos", I am fascinated by the mysteries of the universe and love studying and researching about it.</p>
    </section>

    <section>
        <h2>My Interests and Hobbies</h2>
        <p>I have a keen interest in factual content, whether it’s through watching documentaries, serious tutorials, or globe expeditions. Here are some of my main hobbies and interests:</p>
        <ul>
            <li>Universe space exploration</li>
            <li>Watching documentaries</li>
            <li>Globe expeditions</li>
            <li>Playing the keyboard</li>
            <li>Playing video games</li>
        </ul>
    </section>

    <section class="gallery">
        <h2>Gallery</h2>
        <p>Here are some images representing my interests:</p>
        <img src="https://via.placeholder.com/800x400" alt="Universe Exploration">
        <img src="https://via.placeholder.com/800x400" alt="Documentary Watching">
        <img src="https://via.placeholder.com/800x400" alt="Globe Expedition">
        <img src="https://via.placeholder.com/800x400" alt="Playing Keyboard">
        <img src="https://via.placeholder.com/800x400" alt="Playing Video Games">
    </section>

    <section>
        <h2>Contact Me</h2>
        <form>
            <input type="text" name="name" placeholder="Your Name" required>
            <input type="email" name="email" placeholder="Your Email" required>
            <textarea name="message" rows="5" placeholder="Your Message" required></textarea>
            <button type="submit">Send Message</button>
        </form>
    </section>
</main>

</body>
</html>

