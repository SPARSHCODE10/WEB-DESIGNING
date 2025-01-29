# WEB-DESIGNING
Web Page Design
Have created a single web page with technologies using HTML, CSS, JS. CSS and JS are been used with external linking method.
Following below is the code for reference:

index.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Republic Day Celebration">
    <meta name="keywords" content="Republic Day, India, Celebration">
    <meta name=viewport content="width=device-width, chrom=1">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <link rel="shortcut icon" type="image/x-icon" href="favicon.ico">
    <link rel="icon" type="image/x-icon" href="favicon.ico">
    
    <link rel="stylesheet" href="style.css">
    <script src="script.js" defer></script>
    <title>Republic Day Celebration</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #ffffff;
            background-image: url('https://img.etimg.com/photo/msid-117562068/happy-republic-day-images-pics.jpg');
            background-repeat: no-repeat;
            background-attachment: fixed;
            background-size: cover;
            background-color: #0c0c0c;
            color: #ffffff;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            font-family: 'Arial', sans-serif;
            padding : 0;
            overflow: hidden;
            transition: background-color 0.5s ease-in-out;
        }
        .container {
            background-color: rgba(0, 0, 0, 0.5);
            padding: 20px;
            border-radius: 10px;
            text-align: center;
        }
       
        #text-container {
            margin: 0 auto;
            font-size: 24px;
            font-weight: bold;
            color: #ffffff;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
            animation: textAnimation 5s infinite;
        }
        .container {
            background-color: rgba(0, 0, 0, 0.5);
            padding: 20px;
            border-radius: 10px;
            text-align: center;
        }
       
        #text-container {
            margin: 0 auto;
            width: 80%;
            text-align: center;
        }
        h1 {
            font-size: 24px;
            color: #000000;
            margin: auto;
            padding: 10px;
            border-radius: 10px;
            
        }   
        h2 {
            font-size: 20px;
            color: #000000;
            margin: 10px;
            padding: auto;
            border-radius: 10px;
        }
        p {
            font-size: 16px;
            color: #000000;
            margin : auto;
            padding: 10px;
            border-radius: 10px;
        }
        #date {
            font-size: 14px;
            color: #000000;
        }
       
        #pole, #flag {
            display: block; /* Ensure images are block elements */
            margin: 0 auto; /* Center images horizontally */
            background: transparent; /* Ensure background is transparent */
        }
        #pole {
            margin-top: 20px;
            margin-left: -200px;
            height: 700px;
        }
        #flag {
            border-radius: 5px;
            width: 161px;
            height: 100px;
            position: absolute;
            left: 150px;
            top: 500px;
            animation: mymove 5s forwards forwards; 
           
        }
        @keyframes mymove {
            0% { top: 500px; }
            100% { top: 90px; }

        }
        #caption {
            position: absolute;
            top: 153px;
            left: 299px;
            height: auto; /* Adjust height to auto */
            font-family: Garamond, serif;
            line-height: 1em;
            color: #9ACE15;
            font-weight: bold;
            font-size: 60px; /* Adjusted to a readable size */
            text-shadow: 0px 0px 0 rgb(46,91,170), 1px 1px 0 rgb(31,76,155), 2px 2px 0 rgb(17,62,141), 3px 3px 0 rgb(2,47,126), 4px 4px 0 rgb(-12,33,112), 5px 5px 0 rgb(-27,18,97), 6px 6px 0 rgb(-41,4,83), 7px 7px 6px rgba(0,0,0,0.6), 7px 7px 1px rgba(0,0,0,0.5), 0px 0px 6px rgba(0,0,0,.2);
            text-align: center;
            animation: multicolor 3s infinite;
            padding: 10px; /* Apply padding uniformly */
            margin: 10px;
            white-space: nowrap; /* Prevent text wrapping */
        }
        @keyframes multicolor {
            0% { color: #ff9933; }
            33% { color: #ffffff; }
            66% { color: #138808; }
            100% { color: #ff9933; }
        }
        #caption span {
            display: block;
            font-size: 0.3em;
            line-height: 0.6em;
        }
        canvas {
            position: absolute;
            top: 0;
            left: 0;
            z-index: -1; /* Ensure canvas is behind other elements */
        }
        h1 {
            margin-top: 0;
            color: #ffffff;
            font-size: 32px;
            padding: 10px;
            margin: auto;
        }
        footer {
            text-align: center;
            margin-top: 20px;
            background-color: hsl(0, 0%, 100%);
        }
        canvas {
            width: 100%;
            height: 100%;
        }
        b{
            color: #000000;
            padding: 10px;
            font-size: 20px;
            font-family: Arial, sans-serif;
            font-weight: bold;
            margin: auto;
        }
    </style>
</head>
<body>
        <img id="pole" src="C:\Users\spars\Downloads\flag_pole-removebg-preview.png"alt="Flag Pole">
        <img id="flag" src="https://upload.wikimedia.org/wikipedia/en/thumb/4/41/Flag_of_India.svg/1350px-Flag_of_India.svg.png" alt="Flag of India">
    </div>
    <article>
        <br>
        <div>
            <p>On the 26th day of January, 1950, India officially became a republic. This day is a holiday celebrated by all Indians, with the aim of strengthening the nation's unity and fostering peace.</p>
            <p>India is a country that embraces various religions, including Hinduism, Islam, Sikhism, Christianity, and others. The country has a rich history and culture, known for its diverse languages and traditions. It is also home to many famous monuments, temples, and historical sites.</p>
        </div>
        <div>
            <h2>Republic Day Parade</h2>
            <p>The Republic Day Parade is a grand event that takes place in New Delhi, the capital of India. The parade showcases India's rich culture, heritage, and traditions, attended by thousands from all over the country. It symbolizes India's strength and diversity.</p>
            <p>The parade is a spectacle of color, music, and dance, celebrating India's rich history and culture. It also displays the country's military might, representing unity and heritage.</p>
        </div>
    </article>
    </div>
    <div id="caption"></div> <!-- Added caption div -->
    <canvas id="rainingFlowerCanvas"></canvas>
    <script>
        // Flower's rain code
        function startRainingFlower() {
            const canvas = document.getElementById('rainingFlowerCanvas');
            const ctx = canvas.getContext('2d');
            const flowers = [];
            const numberOfFlowers = 100;
            const petalColors = ['#FF671F', '#fff', '#046A38'];
            canvas.width = window.innerWidth;
            canvas.height = window.innerHeight;

            function newFlower() {
                this.x = canvas.width * Math.random();
                this.y = -20; // Start above the canvas
                this.rotation = Math.random() * 360;
                this.petalColor = petalColors[Math.floor(Math.random() * petalColors.length)];
                this.centerColor = petalColors[Math.floor(Math.random() * petalColors.length)];
                this.petalSize = Math.random() * 10 + 3;
                this.centerSize = this.petalSize / 3;
                this.speed = this.petalSize / 2;
                this.angle = 0;
            }

            for (let i = 0; i < numberOfFlowers; i++) {
                flowers.push(new newFlower());
            }

            function changeFlower(flower) {
                flower.angle += 0.01;
                flower.y += flower.speed;
                if (flower.y >= canvas.height + 20) {
                    flower.y = -20;
                    flower.x = Math.random() * canvas.width;
                }
            }

            function drawFlower(flower) {
                // Draw flower petals
                for (let i = 0; i < 6; i++) {
                    const angle = (i * Math.PI) / 3;
                    const petalX = flower.x + Math.cos(angle) * flower.petalSize;
                    const petalY = flower.y + Math.sin(angle) * flower.petalSize;
                    ctx.beginPath();
                    ctx.lineWidth = flower.petalSize / 4;
                    ctx.strokeStyle = flower.petalColor;
                    ctx.moveTo(petalX + flower.petalSize / 4, petalY);
                    ctx.lineTo(petalX, petalY + flower.petalSize / 4);
                    ctx.stroke();
                    ctx.closePath();
                }

                // Draw flower center
                ctx.beginPath();
                ctx.arc(flower.x, flower.y, flower.centerSize, 0, 2 * Math.PI, false);
                ctx.fillStyle = flower.centerColor;
                ctx.fill();
                ctx.closePath();
            }

            function animateFlowerConfetti() {
                ctx.clearRect(0, 0, canvas.width, canvas.height);
                flowers.forEach(flower => {
                    changeFlower(flower);
                    drawFlower(flower);
                });
                requestAnimationFrame(animateFlowerConfetti);
            }
            animateFlowerConfetti();
        }

        // Listener function to update caption
        function listener(e) {
            if (document.getElementById("caption").childNodes.length == 0) {
                document.getElementById("caption").innerText = "Happy Republic Day";
            }
        }

        // Add event listeners to the flag image
        var flagElement = document.getElementById("flag");
        flagElement.addEventListener("webkitAnimationIteration", listener, false);
        flagElement.addEventListener("animationiteration", listener, false);
        flagElement.addEventListener("MSAnimationIteration", listener, false);
        flagElement.addEventListener("oAnimationIteration", listener, false);
        flagElement.addEventListener("animationiteration", listener, false);
        window.onload = startRainingFlower; // Start the animation when the window loads

        const flag = document.getElementById('flag');

        flag.addEventListener('animationend', () => {
            flag.style.animation = 'none';
            flag.style.top = '90px'; // Ensure it stays at the top after animation
        });
    </script>
</body>
</html>


style.css
body{
    background-color: #ffffff;
    margin: 0px;
    padding: 0px;
}

#pole{
    margin-top: 20px;
    margin-left: -200px;
    height: 700px;
}
#flag{
    border-radius: 5px;
    width: 161px;
    height: 100px;
    position: absolute;
    left: 150px;
    top: 500px;
    -webkit-animation: mymove 5s infinite; 
}

@-webkit-keyframes mymove {
    0%   {top: 500px;}
    100% {top: 90px;}
}

#caption{
position: absolute;
top: 153px;
left: 299px;
height: 104px;
font-family: Garamond, serif;
line-height: 1em;
color: #9ACE15;
font-weight: bold;
font-size: 104px;
text-shadow: 0px 0px 0 rgb(46,91,170),1px 1px 0 rgb(31,76,155),2px 2px 0 rgb(17,62,141),3px 3px 0 rgb(2,47,126),4px 4px 0 rgb(-12,33,112),5px 5px 0 rgb(-27,18,97), 6px 6px 0 rgb(-41,4,83),7px 7px 6px rgba(0,0,0,0.6),7px 7px 1px rgba(0,0,0,0.5),0px 0px 6px rgba(0,0,0,.2);
border-bottom-width: 20px;
text-align: center;
-webkit-animation: 3s multicolor infinite;
}

@-webkit-keyframes multicolor{
0%{
color:#ff9933;
}
33%{
color:#ffffff;
}
66%{
color:#138808;
}
100%{
color:#ff9933;
}	
}

script.js
function listener(e)
		{
				if(document.getElementById("caption").childNodes.length == 0)
				document.getElementById("caption").innerText = "Happy Republic Day 2025";
//document.getElementById("caption").style.color = "color:#9ACE15"
		}
		var e = document.getElementById("flag");
		e.addEventListener("webkitAnimationIteration",listener,false);
		e.addEventListener("animationiteration",listener,false);
		e.addEventListener("MSAnimationIteration",listener,false);
		e.addEventListener("oAnimationIteration",listener,false);
		e.addEventListener("animationiteration",listener,false);
        const flag = document.getElementById('flag');

        flag.addEventListener('animationend', () => {
            flag.style.animation = 'none';
            flag.style.top = '100px'; // Ensure it stays at the top after animation
        });
		

