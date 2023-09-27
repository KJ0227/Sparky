<html>
  <h1>
    Introduction: Meet Sparky
  </h1>
  <p>
    Sparky is a <a href="https://www.akc.org/dog-breeds/american-staffordshire-terrier/">American Staffordshire Terrier.</a> He was born on March 5, 2023. I adopted him on May 15, 2023. He was originally named Zenith before we renamed him. Ever since that day, he has become the center of my attention. He is full of energy and always wants to play. He has beige and white fur. He used to have bright blue eyes (which are now light green) when he was a baby, which gave him his name. He is a very aggressive chewer, and destroys any soft toy with ease. 
  </p>
   <img>
  <a href="https://imgbb.com/"><img src="https://i.ibb.co/cCn7w2c/Sparky.jpg" alt="Sparky" border="0"></a>
  <h1>
    Sparky's Daily Life
  </h1>
    <P>
      Sparky loves to play everyday, but he also sleeps just as much. A day in the life of Sparky would look something like this:
    </P>
    <li>
      <b>6:30am</b>🕡 - Wake up with Krish to get ready for school. Then go back to sleep.
    </li>
      <li>
      <b>7:30am</b>🕢 - Say bye to Krish and Dad.
    </li>
  <li>
    <b>8:30am</b>🕣 - Eat breakfast.
  </li>
  <li>
    <b>9:00am</b>🕘 - Say bye to Mom. 
    <li>
      <b>9:30am</b>🕤 - Since I'm alone, I take multiple naps, chase and eat a bunch of flies, and bark at anyone that tries to come near my house.
  </li>
  <li>
    <b>1:30pm</b>🕜 - I eat the lunch that they left in my bowl.
  <li>
    <b>3:30pm</b>🕞 - Krish is back! Time to run around the house! 
  </li>
  <li>
      <b>5:30pm</b>🕠 - Mom and Dad are back!
  </li>
  <li>
    <b>6:00pm</b>🕕 - Time to go for a walk!
  </li>
  <li>
    <b>7:30pm</b>🕢 - Dinner time.
  </li>
  <li>
    <b>10:00pm</b>🕙 - This is my bedtime.
  </li>
 <!DOCTYPE html>
<html>
<head>
    <title>Guessing if Sparky has chewed that</title>
    <style>
        body {
            text-align: center;
            font-family: Arial, sans-serif;
        }
        h1 {
            color: #333;
        }
        #game-container {
            margin: 20px auto;
            padding: 20px;
            border: 1px solid #333;
            max-width: 400px;
            background-color: #f7f7f7;
        }
        button {
            padding: 10px 20px;
            margin: 10px;
            font-size: 18px;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <h1>Guessing if Sparky has chewed that</h1>
    <div id="game-container">
        <p>Choose the correct option:</p>
        <button id="option1" onclick="checkAnswer('option1')">Metal Pipe</button>
        <button id="option2" onclick="checkAnswer('option2')">AirPods</button>
        <button id="option3" onclick="checkAnswer('option3')">Couch</button>
        <button id="option4" onclick="checkAnswer('option4')">Math Homework</button>
        <button id="option5" onclick="checkAnswer('option5')">Napkin</button>
        <button id="option6" onclick="checkAnswer('option6')">Bed</button>
        <p id="result"></p>
    </div>

    <script>
        const correctOptions = ['option1', 'option2', 'option5']; // Correct options

        function checkAnswer(selectedOption) {
            if (correctOptions.includes(selectedOption)) {
                document.getElementById('result').innerText = 'Correct! Sparky did not chew that.';
            } else {
                document.getElementById('result').innerText = 'Oops! Sparky might have chewed that. Try again.';
            }
        }
    </script>
</body>
</html>
