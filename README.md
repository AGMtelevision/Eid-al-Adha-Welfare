<html lang="en"><head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AGM South Africa - Eid al-Adha Special Benefits</title>
    <!-- Tailwind CSS v3 -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Font Awesome -->
    <link href="https://cdn.jsdelivr.net/npm/font-awesome@4.7.0/css/font-awesome.min.css" rel="stylesheet">
    <!-- AOS Animation Library -->
    <link href="https://cdn.jsdelivr.net/npm/aos@2.3.4/dist/aos.css" rel="stylesheet">
    <script src="https://cdn.jsdelivr.net/npm/aos@2.3.4/dist/aos.js"></script>
    
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        primary: '#FF6B00',
                        secondary: '#0033CC',
                        dark: '#333333',
                        light: '#F8F9FA',
                        accent: '#8B0000'
                    },
                    fontFamily: {
                        sans: ['Inter', 'system-ui', 'sans-serif'],
                    },
                    animation: {
                        'spin-slow': 'spin 20s linear infinite',
                    }
                }
            }
        }
    </script>
    <style type="text/tailwindcss">
        @layer utilities {
            .text-shadow {
                text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
            }
            .bg-gradient-primary {
                background: linear-gradient(135deg, #FF6B00 0%, #FF8C00 100%);
            }
            .bg-gradient-secondary {
                background: linear-gradient(135deg, #FFD700 0%, #FFA500 100%);
            }
            .card-shadow {
                box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1), 0 4px 6px -2px rgba(0, 0, 0, 0.05);
            }
        }
        
        /* Custom styles for the lottery wheel */
        .wheel-container {
            position: relative;
            width: 100%;
            max-width: 400px;
            margin: 0 auto;
        }
        
        .wheel {
            width: 100%;
            height: 0;
            padding-bottom: 100%;
            background-image: url('https://p11-flow-imagex-download-sign.byteimg.com/tos-cn-i-a9rns2rl98/af92eb16bed84389b3c2e6b54f51614b.png~tplv-a9rns2rl98-24:720:720.png?lk3s=8e244e95&rcl=2026052717163770E36C0F073117CCC387&rrcfp=8a172a1a&x-expires=1780478197&x-signature=V%2B85UXgbMk4OFF8%2Fyqwbq9mAmYM%3D');
            background-size: contain;
            background-repeat: no-repeat;
            background-position: center;
            animation: spin-slow 20s linear infinite;
            border-radius: 50%;
        }
        
        /* Wheel center style removed */
        
        .wheel-pointer {
            position: absolute;
            top: -20px;
            left: 50%;
            transform: translateX(-50%);
            width: 0;
            height: 0;
            border-left: 20px solid transparent;
            border-right: 20px solid transparent;
            border-bottom: 40px solid #8B0000;
            z-index: 5;
        }
        
        @keyframes spin-slow {
            from {
                transform: rotate(0deg);
            }
            to {
                transform: rotate(360deg);
            }
        }
        
        /* Confetti animation */
        .confetti-container {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            pointer-events: none;
            z-index: 9999;
            overflow: hidden;
        }
        
        .confetti {
            position: absolute;
            width: 10px;
            height: 10px;
            background-color: #f00;
            border-radius: 50%;
            animation: confetti-fall 3s ease-in-out infinite;
        }
        
        .confetti:nth-child(odd) {
            width: 15px;
            height: 15px;
        }
        
        @keyframes confetti-fall {
            0% {
                transform: translateY(-10vh) rotate(0deg);
                opacity: 1;
            }
            100% {
                transform: translateY(100vh) rotate(360deg);
                opacity: 0;
            }
        }
        
        /* Custom pulse animation for reward titles */
        @keyframes pulse-slow {
            0%, 100% {
                transform: scale(1);
                text-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            }
            50% {
                transform: scale(1.05);
                text-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            }
        }
        
        .animate-pulse-slow {
            animation: pulse-slow 3s ease-in-out infinite;
        }
        
        .reward-title {
            display: inline-block;
            transition: all 0.3s ease;
        }
        
        .reward-title:hover {
            transform: scale(1.1);
            color: #FF6B00;
        }
        
        /* Countdown timer styles */
        .countdown-item {
            position: relative;
            background-color: #FF6B00;
            border-radius: 8px;
            padding: 1rem;
            color: white;
            font-weight: bold;
            text-align: center;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        
        .countdown-item::after {
            content: '';
            position: absolute;
            top: 50%;
            right: -10px;
            transform: translateY(-50%);
            width: 10px;
            height: 10px;
            background-color: #FF6B00;
            border-radius: 50%;
        }
        
        .countdown-item:last-child::after {
            display: none;
        }
        
        /* Card hover effects */
        .benefit-card {
            transition: all 0.3s ease;
        }
        
        .benefit-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 15px 30px rgba(0, 0, 0, 0.1);
        }
    </style>
</head>
<body class="bg-light font-sans">
    <!-- Header Section -->
    <header class="bg-gradient-primary text-white py-6 shadow-md">
        <div class="container mx-auto px-4">
            <div class="flex flex-col md:flex-row justify-between items-center">
                <div class="flex items-center mb-4 md:mb-0">
                    <img src="https://p3-flow-imagex-sign.byteimg.com/tos-cn-i-a9rns2rl98/rc/pc/code_assistant/c1eba4623a0a41fc8be5a2043c4403ed~tplv-a9rns2rl98-image.image?lk3s=8e244e95&amp;rcl=20260527163252F20F0DEA909797AF5108&amp;rrcfp=e75484ac&amp;x-expires=1780475574&amp;x-signature=6Iwhqq7USPqYuJPCQQo6B%2BglEeQ%3D" alt="AGM Logo" class="h-12 mr-3" style="border-radius: 0px;">
                    <h1 class="text-2xl md:text-3xl font-bold">AGM South Africa</h1>
                </div>
                <div class="flex items-center">
                    <div id="countdown" class="flex space-x-4">
                        <div class="countdown-item">
                            <span id="days" class="text-2xl">00</span>
                            <span class="block text-sm">Days</span>
                        </div>
                        <div class="countdown-item">
                            <span id="hours" class="text-2xl">00</span>
                            <span class="block text-sm">Hours</span>
                        </div>
                        <div class="countdown-item">
                            <span id="minutes" class="text-2xl">00</span>
                            <span class="block text-sm">Minutes</span>
                        </div>
                        <div class="countdown-item">
                            <span id="seconds" class="text-2xl">00</span>
                            <span class="block text-sm">Seconds</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="py-12 md:py-20 bg-white">
        <div class="container mx-auto px-4">
            <div class="flex flex-col md:flex-row items-center">
                <div class="md:w-1/2 mb-8 md:mb-0" data-aos="fade-right" data-aos-duration="1000">
                    <h2 class="text-3xl md:text-4xl font-bold text-dark mb-4" style="color: rgb(50, 5, 252);">Eid al-Adha Special Benefits</h2>
                    <p class="text-lg text-gray-700 mb-6" style="color: rgb(122, 12, 166); font-weight: bold;">
                        To all AGM APP users in South Africa:
                    </p>
                    <p class="text-lg text-gray-700 mb-6" style="color: rgb(95, 5, 128); font-weight: bold;">
                        Eid al-Adha is a major Islamic festival cherished locally, fostering family harmony, community unity and mutual support.
                    </p>
                    <p class="text-lg text-gray-700 mb-6" style="color: rgb(78, 0, 212); font-weight: bold;">
                        To mark this festival (May 27), AGM is launching special benefits for all staff, lasting May 27 – 30 (4 days only).
                    </p>
                    <div class="bg-yellow-50 border-l-4 border-primary p-4 mb-6">
                        <p class="text-sm text-gray-700">
                            <strong>Notice:</strong> Lottery prizes: R20 – R10,000. Please apply for draws via your hiring manager or Telegram admin. Don't miss out!
                        </p>
                    </div>
                </div>
                <div class="md:w-1/2 flex justify-center" data-aos="fade-left" data-aos-duration="1000">
                    <div class="wheel-container">
                        <div class="wheel-pointer"></div>
                        <div class="wheel"></div>
                        <!-- Wheel center removed -->
                        <div class="mt-8 text-center">
                            <p class="text-sm text-gray-500" style="color: rgb(250, 2, 2); font-weight: bold;">Prize range: R20 - R10,000</p>
                            <p class="text-sm text-gray-500 mt-2" style="color: rgb(0, 67, 224); font-weight: bold;">This is a display only. Please apply for draws through your hiring manager.</p>
                        </div>
                        
                        <!-- Invite friends button -->
                        <div class="mt-6 text-center">
                            <a href="https://agmzatv.com/xml/index.html#/user" target="_blank" id="inviteBtn" class="bg-gradient-primary text-white font-bold py-3 px-8 rounded-full shadow-lg transform transition-all duration-300 hover:scale-105 hover:shadow-xl focus:outline-none focus:ring-2 focus:ring-primary focus:ring-opacity-50 animate-pulse inline-block">
                                Invite your friends to join now and participate in the lucky draw!
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Benefits Section -->
    <section class="py-12 md:py-20 bg-gray-50">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl font-bold text-center text-dark mb-12" data-aos="fade-up">Festival Benefits</h2>
            
            <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                <!-- Referral Rewards Card -->
                <div class="bg-white rounded-lg p-6 card-shadow benefit-card" data-aos="fade-up" data-aos-delay="100">
                    <div class="flex items-center mb-4">
                        <div class="w-12 h-12 bg-primary rounded-full flex items-center justify-center mr-4">
                            <i class="fa fa-users text-white text-xl"></i>
                        </div>
                        <h3 class="text-2xl font-bold text-dark reward-title animate-pulse-slow" style="color: rgb(73, 10, 125);">Referral Rewards</h3>
                    </div>
                    <p class="text-gray-700 mb-4" style="color: rgb(242, 33, 5); font-weight: bold;">
                        G-level full-time staff who invite A-level interns to upgrade:
                    </p>
                    <ul class="space-y-3">
                        <li class="flex items-start">
                            <i class="fa fa-check-circle text-primary mt-1 mr-2"></i>
                            <span style="color: rgb(0, 58, 247);">Invite interns to join G1 and receive: platform bonus (R54) + 1 lottery draw
</span>
                        </li>
                        <li class="flex items-start">
                            <i class="fa fa-check-circle text-primary mt-1 mr-2"></i>
                            <span style="color: rgba(5, 17, 250, 0.99);">Inviting interns to G2 will earn you: a platform bonus (R216) + 2 lottery draws.
</span>
                        </li>
                    </ul>
                </div>
                
                <!-- Promotion Rewards Card -->
                <div class="bg-white rounded-lg p-6 card-shadow benefit-card" data-aos="fade-up" data-aos-delay="200">
                    <div class="flex items-center mb-4">
                        <div class="w-12 h-12 bg-secondary rounded-full flex items-center justify-center mr-4">
                            <i class="fa fa-arrow-up text-dark text-xl"></i>
                        </div>
                        <h3 class="text-2xl font-bold text-dark reward-title animate-pulse-slow" style="color: rgb(100, 14, 143);">Promotion Rewards</h3>
                    </div>
                    <p class="text-gray-700 mb-4" style="color: rgb(245, 2, 2); font-weight: bold;">
                        Interns promoted to G-level full-time staff:
                    </p>
                    <ul class="space-y-3">
                        <li class="flex items-start">
                            <i class="fa fa-check-circle text-secondary mt-1 mr-2"></i>
                            <span style="color: rgb(0, 158, 8); font-weight: bold;">Intern joins G1: Receives 1 lottery draw
</span>
                        </li>
                        <li class="flex items-start">
                            <i class="fa fa-check-circle text-secondary mt-1 mr-2"></i>
                            <span style="color: rgb(14, 161, 70); font-weight: bold;">Intern joins G2: Receives 2 lottery draw
</span>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- Notice Section -->
    <section class="py-12 md:py-16 bg-gradient-primary text-white">
        <div class="container mx-auto px-4">
            <div class="max-w-3xl mx-auto text-center" data-aos="fade-up">
                <h2 class="text-3xl font-bold mb-6">Important Notice</h2>
                <div class="bg-white bg-opacity-20 rounded-lg p-6 backdrop-blur-sm">
                    <p class="text-lg mb-4" style="color: rgb(61, 8, 252); font-weight: bold;">
                        Lottery prizes range from R20 to R10,000. To participate, please apply for draws through your hiring manager or Telegram admin.
                    </p>
                    <p class="text-lg" style="color: rgb(255, 8, 8); font-weight: bold;">
                        This special Eid al-Adha promotion runs from May 27 to May 30, 2026. Don't miss this opportunity!
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-dark text-white py-8">
        <div class="container mx-auto px-4">
            <div class="flex flex-col md:flex-row justify-between items-center">
                <div class="mb-4 md:mb-0">
                    <div class="flex items-center">
                        <img src="https://p3-flow-imagex-sign.byteimg.com/tos-cn-i-a9rns2rl98/rc/pc/code_assistant/4b810794860b4fda9e03e681be6f005f~tplv-a9rns2rl98-image.image?lk3s=8e244e95&amp;rcl=20260527164407BC482DB6D636A5D69563&amp;rrcfp=e75484ac&amp;x-expires=1780476248&amp;x-signature=gnILijJOtY%2FUpsyodAIuGf89GHc%3D" alt="AGM Logo" class="h-10 mr-3">
                        <span class="text-xl font-bold">AGM South Africa</span>
                    </div>
                </div>
                <div class="text-center md:text-right">
                    <p class="text-sm text-gray-400">© 2026 AGM. All rights reserved.</p>
                    <p class="text-sm text-gray-400 mt-1">Eid al-Adha Special Promotion</p>
                </div>
            </div>
        </div>
    </footer>

    <script>
        // Initialize AOS animation library
        document.addEventListener('DOMContentLoaded', function() {
            AOS.init();
            startCountdown();
            createConfetti();
            initInviteButton();
        });

        // Countdown timer function
        function startCountdown() {
            // Set the countdown date to May 30, 2026 at 23:59:59
            const countdownDate = new Date('May 30, 2026 23:59:59').getTime();
            
            // Update the countdown every 1 second
            const countdownInterval = setInterval(function() {
                // Get today's date and time
                const now = new Date().getTime();
                
                // Find the distance between now and the countdown date
                const distance = countdownDate - now;
                
                // Time calculations for days, hours, minutes and seconds
                const days = Math.floor(distance / (1000 * 60 * 60 * 24));
                const hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
                const minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
                const seconds = Math.floor((distance % (1000 * 60)) / 1000);
                
                // Display the result in the elements with id="days", "hours", "minutes", "seconds"
                document.getElementById("days").innerText = days.toString().padStart(2, '0');
                document.getElementById("hours").innerText = hours.toString().padStart(2, '0');
                document.getElementById("minutes").innerText = minutes.toString().padStart(2, '0');
                document.getElementById("seconds").innerText = seconds.toString().padStart(2, '0');
                
                // If the countdown is over, write some text
                if (distance < 0) {
                    clearInterval(countdownInterval);
                    document.getElementById("countdown").innerHTML = "<p class='text-center text-primary font-bold'>Promotion Ended</p>";
                }
            }, 1000);
        }
        
        // Confetti animation function
        function createConfetti() {
            // Create confetti container
            const container = document.createElement('div');
            container.className = 'confetti-container';
            document.body.appendChild(container);
            
            // Colors for confetti
            const colors = ['#FF6B00', '#0033CC', '#FFD700', '#8B0000', '#00CC00', '#CC00CC'];
            
            // Create confetti pieces
            for (let i = 0; i < 100; i++) {
                createConfettiPiece(container, colors);
            }
            
            // Create new confetti every 3 seconds
            setInterval(() => {
                for (let i = 0; i < 20; i++) {
                    createConfettiPiece(container, colors);
                }
            }, 3000);
        }
        
        function createConfettiPiece(container, colors) {
            const confetti = document.createElement('div');
            confetti.className = 'confetti';
            
            // Random properties
            const color = colors[Math.floor(Math.random() * colors.length)];
            const size = Math.random() * 10 + 5;
            const left = Math.random() * 100;
            const duration = Math.random() * 3 + 2;
            const delay = Math.random() * 2;
            const rotation = Math.random() * 360;
            
            // Apply styles
            confetti.style.backgroundColor = color;
            confetti.style.width = `${size}px`;
            confetti.style.height = `${size}px`;
            confetti.style.left = `${left}%`;
            confetti.style.animationDuration = `${duration}s`;
            confetti.style.animationDelay = `${delay}s`;
            confetti.style.transform = `rotate(${rotation}deg)`;
            
            // Add to container
            container.appendChild(confetti);
            
            // Remove after animation completes
            setTimeout(() => {
                confetti.remove();
            }, (duration + delay) * 1000);
        }
        
        // Initialize invite button functionality
        function initInviteButton() {
            const inviteBtn = document.getElementById('inviteBtn');
            
            // Add click event to trigger confetti before navigation
            inviteBtn.addEventListener('click', function(e) {
                // Trigger confetti celebration before navigation
                for (let i = 0; i < 50; i++) {
                    createConfettiPiece(document.querySelector('.confetti-container'), ['#FF6B00', '#0033CC', '#FFD700']);
                }
                
                // No need to prevent default as we want the link to navigate
            });
        }
    </script>

</body></html>
