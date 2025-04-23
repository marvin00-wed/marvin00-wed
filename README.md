<!DOCTYPE html>
<html>
<head>
	<title>Harlex Gaming Hub</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        body {
            font-family: 'Arial', sans-serif;
        }
        .gallery-img {
        	<img src="">
            transition: transform 0.3s ease;
        }
        .gallery-img:hover {
            transform: scale(1.05);
        }
    </style>
</head>
<body class="bg-gray-900 text-white">
    <!-- Navigation -->
    <nav class="bg-gray-800 p-4 sticky top-0 z-10">
        <div class="container mx-auto flex justify-between items-center">
            <h1 class="text-2xl font-bold">Harlex Gaming Hub</h1>
            <ul class="flex space-x-6">
                <li><a href="#home" class="hover:text-purple-400">Home</a></li>
                <li><a href="#about" class="hover:text-purple-400">About Us</a></li>
                <li><a href="#gallery" class="hover:text-purple-400">Gallery</a></li>
                <li><a href="#contact" class="hover:text-purple-400">Contact Us</a></li>
            </ul>
        </div> </nav>

    <!-- Home Section -->
    <section id="home" class="min-h-screen flex items-center justify-center bg-gradient-to-b from-gray-900 to-gray-700">
        <div class="container mx-auto text-center">
            <h2 class="text-5xl font-bold mb-4">Welcome to Harlex Gaming Hub</h2>
            <p class="text-xl mb-6">Your ultimate destination for immersive gaming experiences!</p>
            <a href="#gallery" class="bg-purple-600 text-white px-6 py-3 rounded-lg hover:bg-purple-700">Explore Games</a>
        </div>
    </section>

    <!-- About Us Section -->
    <section id="about" class="py-16 bg-gray-800">
        <div class="container mx-auto px-4">
            <h2 class="text-4xl font-bold text-center mb-8">About Us</h2>
            <p class="text-lg max-w-3xl mx-auto text-center">
                Harlex Gaming Hub was founded by Kaya Marvin, a passionate gamer and developer dedicated to creating thrilling gaming experiences. 
                Our mission is to bring gamers together through innovative and exciting games that push the boundaries of fun and creativity.
            </p>
        </div>
    </section>

    <!-- Gallery Section -->
    <section id="gallery" class="py-16 bg-gray-900">
        <div class="container mx-auto px-4">
            <h2 class="text-4xl font-bold text-center mb-8">Game Gallery</h2>
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-6">
                <div class="rounded-lg overflow-hidden shadow-lg">
                    <img src="https://via.placeholder.com/400x300?text=Game+1" alt="Game 1" class="w-full gallery-img">
                    <div class="p-4 bg-gray-800">
                        <h3 class="text-xl font-semibold">Cyber Quest</h3>
                        <p>An action-packed sci-fi adventure.</p>
                    </div>
                </div>
                <div class="rounded-lg overflow-hidden shadow-lg">
                    <img src="https://via.placeholder.com/400x300?text=Game+2" alt="Game 2" class="w-full gallery-img">
                    <div class="p-4 bg-gray-800">
                        <h3 class="text-xl font-semibold">Mystic Realms</h3>
                        <p>Explore a magical world of fantasy.</p>
                    </div>
                </div>
                <div class="rounded-lg overflow-hidden shadow-lg">
                    <img src="https://via.placeholder.com/400x300?text=Game+3" alt="Game 3" class="w-full gallery-img">
                    <div class="p-4 bg-gray-800">
                        <h3 class="text-xl font-semibold">Racing Fury</h3>
                        <p>High-speed racing action.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Us Section -->
    <section id="contact" class="py-16 bg-gray-800">
        <div class="container mx-auto px-4">
            <h2 class="text-4xl font-bold text-center mb-8">Contact Us</h2>
            <div class="max-w-lg mx-auto">
                <div class="mb-4">
                    <label for="name" class="block text-lg mb-2">Name</label>
                    <input type="text" id="name" class="w-full p-3 rounded-lg bg-gray-700 text-white" placeholder="Your Name">
                </div>
                <div class="mb-4">
                    <label for="email" class="block text-lg mb-2">Email</label>
                    <input type="email" id="email" class="w-full p-3 rounded-lg bg-gray-700 text-white" placeholder="Your Email">
                </div>
                <div class="mb-4">
                    <label for="message" class="block text-lg mb-2">Message</label>
                    <textarea id="message" class="w-full p-3 rounded-lg bg-gray-700 text-white" rows="5" placeholder="Your Message"></textarea>
                </div>
                <button onclick="alert('Message sent!')" class="bg-purple-600 text-white px-6 py-3 rounded-lg hover:bg-purple-700 w-full">Send Message</button>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-900 p-4 text-center">
        <p>&copy; 2025 Harlex Gaming Hub. Developed by Kaya Marvin.</p>
    </footer>
</body>
</html></title>
</head>
<body>

</body>
</html>
