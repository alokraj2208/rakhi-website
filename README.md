<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy Raksha Bandhan to My Wonderful Sister</title>
    <style>
        :root {
            --primary-color: #e53935;
            --secondary-color: #f48fb1;
            --accent-color: #fdd835;
            --light-color: #fff9c4;
            --dark-color: #b71c1c;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background-color: var(--light-color);
            color: #333;
            overflow-x: hidden;
            position: relative;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        
        header {
            background: linear-gradient(135deg, var(--primary-color), var(--dark-color));
            color: white;
            text-align: center;
            padding: 40px 0;
            position: relative;
            box-shadow: 0 4px 12px rgba(0,0,0,0.1);
        }
        
        h1 {
            font-size: 3rem;
            margin-bottom: 20px;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.2);
        }
        
        .hero-image {
            width: 100%;
            max-width: 800px;
            margin: 30px auto;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 8px 16px rgba(0,0,0,0.2);
            position: relative;
        }
        
        .hero-image img {
            width: 100%;
            display: block;
            transition: transform 0.3s ease;
        }
        
        .hero-image:hover img {
            transform: scale(1.03);
        }
        
        .content-section {
            padding: 40px 20px;
            text-align: center;
        }
        
        .message-box {
            background-color: white;
            border-radius: 8px;
            padding: 30px;
            margin: 30px auto;
            max-width: 800px;
            box-shadow: 0 4px 12px rgba(0,0,0,0.1);
            position: relative;
            border: 4px solid var(--accent-color);
        }
        
        .message-box:before {
            content: "";
            position: absolute;
            top: -10px;
            left: -10px;
            right: -10px;
            bottom: -10px;
            border: 2px dashed var(--secondary-color);
            border-radius: 12px;
            pointer-events: none;
            z-index: -1;
        }
        
        p {
            font-size: 1.2rem;
            line-height: 1.6;
            margin-bottom: 20px;
        }
        
        .special-message {
            font-size: 1.4rem;
            font-weight: bold;
            color: var(--dark-color);
            margin: 30px 0;
        }
        
        .rakhi-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin: 40px auto;
            max-width: 1000px;
        }
        
        .rakhi-item {
            background: white;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        
        .rakhi-item:hover {
            transform: translateY(-10px);
            box-shadow: 0 10px 20px rgba(0,0,0,0.2);
        }
        
        .rakhi-item img {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }
        
        .rakhi-item .caption {
            padding: 15px;
            text-align: center;
            background: linear-gradient(to right, var(--secondary-color), var(--light-color));
            color: #333;
        }
        
        .interactive-section {
            margin: 50px auto;
            text-align: center;
        }
        
        .virtual-rakhi {
            width: 150px;
            height: 150px;
            background-color: var(--accent-color);
            border-radius: 50%;
            margin: 0 auto 30px;
            position: relative;
            cursor: pointer;
            box-shadow: 0 8px 16px rgba(0,0,0,0.2);
            transition: transform 0.3s ease;
            display: flex;
            align-items: center;
            justify-content: center;
            color: var(--dark-color);
            font-weight: bold;
            font-size: 1.2rem;
        }
        
        .virtual-rakhi:hover {
            transform: scale(1.1);
        }
        
        #greeting-display {
            min-height: 100px;
            margin: 20px auto;
            padding: 20px;
            background-color: white;
            border-radius: 8px;
            border: 2px dashed var(--primary-color);
            max-width: 600px;
        }
        
        .btn {
            background-color: var(--primary-color);
            color: white;
            border: none;
            padding: 12px 24px;
            font-size: 1.1rem;
            border-radius: 50px;
            cursor: pointer;
            transition: all 0.3s ease;
            margin: 10px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
        }

        .btn:hover {
            background-color: var(--dark-color);
            transform: translateY(-2px);
            box-shadow: 0 6px 12px rgba(0,0,0,0.2);
        }
        
        .btn-secondary {
            background-color: var(--accent-color);
            color: var(--dark-color);
        }
        
        footer {
            background: linear-gradient(135deg, var(--dark-color), var(--primary-color));
            color: white;
            text-align: center;
            padding: 30px;
            margin-top: 50px;
        }
        
        @keyframes float {
            0%, 100% {
                transform: translateY(0);
            }
            50% {
                transform: translateY(-20px);
            }
        }
        
        .floating {
            animation: float 3s ease-in-out infinite;
        }
        
        .heart {
            color: var(--primary-color);
            font-size: 1.5rem;
            display: inline-block;
            margin: 0 5px;
        }
        
        @media (max-width: 768px) {
            h1 {
                font-size: 2rem;
            }
            
            .rakhi-grid {
                grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>Happy Raksha Bandhan</h1>
            <p>To My Dearest Sister</p>
        </div>
    </header>
    
    <div class="hero-image">
        <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/999b8306-a029-4fae-998e-a6a22664238a.png" alt="Beautiful Indian sisters celebrating Raksha Bandhan, tying colorful Rakhi on brother's wrist in a warmly decorated room with diyas and flowers" />
    </div>
    
    <div class="content-section container">
        <div class="message-box">
            <p>Dear Sister,</p>
            <p>On this special occasion of Raksha Bandhan, I want to take a moment to express how grateful I am to have you in my life.</p>
            <p class="special-message">You are not just my sister, but my best friend, my confidant, and my greatest supporter.</p>
            <p>This Rakhi, I promise to always be there for you, to protect you, and to cherish our bond forever.</p>
            <p>May our relationship continue to grow stronger with each passing year.</p>
        </div>
        
        <h2>Celebrating Our Bond</h2>
        <div class="rakhi-grid">
            <div class="rakhi-item">
                <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/bc3e6ac6-bfe8-429e-ba55-826d0c9b3cda.png" alt="Close-up of beautifully decorated traditional Rakhi with beads and golden thread on a red velvet background" />
                <div class="caption">The Sacred Thread of Love</div>
            </div>
            <div class="rakhi-item">
                <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/ed170742-4e32-43c2-beb6-6db5dced5937.png" alt="Brother and sister smiling while celebrating Raksha Bandhan with sweets and gifts on a decorated table" />
                <div class="caption">Moments of Togetherness</div>
            </div>
            <div class="rakhi-item">
                <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/a178fcfc-fa21-4e9c-88bc-2e6db3fa6b0c.png" alt="Siblings posing for photograph during Raksha Bandhan in traditional Indian attire with festive decorations" />
                <div class="caption">Memories to Cherish</div>
            </div>
        </div>
    </div>
    
    <div class="interactive-section container">
        <h2>Virtual Rakhi Ceremony</h2>
        <div class="virtual-rakhi floating" id="virtualRakhi">
            Tie Virtual Rakhi
        </div>
        
        <h3>Receive a Special Greeting</h3>
        <div id="greeting-display">
            Click below to receive a special Raksha Bandhan wish!
        </div>
        <button class="btn" id="generateGreeting">Generate Greeting</button>
        <button class="btn btn-secondary" id="resetGreeting">Reset</button>
    </div>
    
    <footer>
        <div class="container">
            <p>With all my love, on this Raksha Bandhan <span class="heart">❤</span></p>
            <p>May our bond remain strong forever</p>
        </div>
    </footer>
    
    <script>
        document.addEventListener('DOMContentLoaded', function() {
            const virtualRakhi = document.getElementById('virtualRakhi');
            const greetingDisplay = document.getElementById('greeting-display');
            const generateBtn = document.getElementById('generateGreeting');
            const resetBtn = document.getElementById('resetGreeting');
            
            const greetings = [
                "Dear sister, you are the most precious gift in my life. Thank you for always being there for me. Happy Raksha Bandhan!",
                "No matter how far apart we are, our sibling bond remains unbreakable. Wishing you a very happy Rakhi!",
                "You're not just my sister, you're my lifelong friend. May our bond grow stronger with each passing year. Happy Raksha Bandhan!",
                "On this Rakhi, I promise to always be your pillar of strength. Thank you for everything you do. Love you always!",
                "The love between siblings is truly special. Thank you for making my life so much brighter. Happy Raksha Bandhan!"
            ];
            
            virtualRakhi.addEventListener('click', function() {
                this.textContent = "Rakhi Tied!";
                this.style.backgroundColor = '#4CAF50';
                
                setTimeout(() => {
                    this.textContent = "Tie Again";
                    this.style.backgroundColor = '';
                }, 2000);
            });
            
            generateBtn.addEventListener('click', function() {
                const randomIndex = Math.floor(Math.random() * greetings.length);
                greetingDisplay.textContent = greetings[randomIndex];
                greetingDisplay.style.backgroundColor = '#fff9c4';
            });
            
            resetBtn.addEventListener('click', function() {
                greetingDisplay.textContent = "Click below to receive a special Raksha Bandhan wish!";
                greetingDisplay.style.backgroundColor = 'white';
            });
        });
    </script>
</body>
</html>

