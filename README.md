<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Digital Marketing Agency</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        primary: '#1E40AF',
                        secondary: '#FACC15',
                        dark: '#111827'
                    }
                }
            }
        };
    </script>
</head>
<body class="bg-gray-100">
    <!-- Navbar -->
    <nav class="bg-primary text-white p-4 flex justify-between items-center">
        <h1 class="text-2xl font-bold">DigiBoost</h1>
        <ul class="flex space-x-6">
            <li><a href="#" class="hover:text-secondary">Home</a></li>
            <li><a href="#" class="hover:text-secondary">Services</a></li>
            <li><a href="#" class="hover:text-secondary">About</a></li>
            <li><a href="#" class="hover:text-secondary">Contact</a></li>
        </ul>
    </nav>

    <!-- Hero Section -->
    <header class="text-center py-20 bg-dark text-white">
        <h2 class="text-4xl font-bold">Grow Your Business with Expert Digital Marketing</h2>
        <p class="mt-4 text-lg">We help brands reach their target audience and maximize ROI.</p>
        <button class="mt-6 bg-secondary text-dark px-6 py-3 rounded-lg font-semibold hover:bg-yellow-400">Get Started</button>
    </header>

    <!-- Services Section -->
    <section class="py-16 px-6">
        <h3 class="text-3xl font-bold text-center text-primary">Our Services</h3>
        <div class="mt-8 grid md:grid-cols-3 gap-6">
            <div class="p-6 bg-white shadow-lg rounded-lg text-center">
                <h4 class="text-xl font-semibold text-dark">SEO Optimization</h4>
                <p class="text-gray-600 mt-2">Boost your search rankings and increase visibility.</p>
            </div>
            <div class="p-6 bg-white shadow-lg rounded-lg text-center">
                <h4 class="text-xl font-semibold text-dark">Social Media Marketing</h4>
                <p class="text-gray-600 mt-2">Engage and grow your audience on social platforms.</p>
            </div>
            <div class="p-6 bg-white shadow-lg rounded-lg text-center">
                <h4 class="text-xl font-semibold text-dark">Pay-Per-Click Advertising</h4>
                <p class="text-gray-600 mt-2">Maximize conversions with targeted ad campaigns.</p>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-primary text-white text-center p-4 mt-12">
        <p>&copy; 2025 DigiBoost. All rights reserved.</p>
    </footer>
</body>
</html>

