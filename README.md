💻 Snippet ==================================

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Crocodile Facts</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f8ff;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }

        .container {
            text-align: center;
            background-color: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        .fact-display {
            margin: 20px 0;
            font-size: 18px;
            color: #333;
        }

        .fact-button {
            padding: 10px 20px;
            font-size: 16px;
            color: #fff;
            background-color: #007bff;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s;
        }

        .fact-button:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Crocodile Facts</h1>
        <div id="fact-display" class="fact-display">
            Click the button to see a random fact about crocodiles!
        </div>
        <button id="fact-button" class="fact-button">Show Random Fact</button>
    </div>
    <script>
        const facts = [
            {
                fact: "Ancient Survivors",
                detail: "Crocodiles have been around for over 200 million years, making them one of the oldest living reptiles, surviving even the dinosaurs."
            },
            {
                fact: "Powerful Jaws",
                detail: "Crocodiles have one of the strongest bites in the animal kingdom, with a force of up to 3,700 pounds per square inch (psi)."
            },
            {
                fact: "Ambush Predators",
                detail: "They are excellent hunters, using stealth and patience to ambush their prey at the water's edge."
            },
            {
                fact: "Cold-Blooded",
                detail: "As ectothermic animals, crocodiles rely on external heat sources to regulate their body temperature."
            },
            {
                fact: "Variety of Species",
                detail: "There are 23 different species of crocodiles, including the saltwater crocodile, which is the largest living reptile."
            },
            {
                fact: "Parental Care",
                detail: "Female crocodiles are known to guard their nests and even help their hatchlings reach the water after they are born."
            },
            {
                fact: "Communication",
                detail: "Crocodiles communicate with each other through vocalizations, such as growls, hisses, and roars."
            },
            {
                fact: "Longevity",
                detail: "Crocodiles can live for several decades, with some species living up to 70 years or more in the wild."
            },
            {
                fact: "Unique Teeth",
                detail: "Crocodiles continuously replace their teeth throughout their lives, with some species having up to 3,000 teeth in a lifetime."
            },
            {
                fact: "Efficient Swimmers",
                detail: "They can swim at speeds of up to 20 miles per hour (32 kilometers per hour) using their powerful tails."
            }
        ];

        document.getElementById('fact-button').addEventListener('click', () => {
            const randomIndex = Math.floor(Math.random() * facts.length);
            const randomFact = facts[randomIndex];
            document.getElementById('fact-display').innerHTML = `<strong>${randomFact.fact}:</strong> ${randomFact.detail}`;
        });
    </script>
</body>
</html>

🔤 Title ====================================

HTML Snippet

📝 Description ==============================

Code snippet from a conversation with Pieces for Developers Copilot

🌐 Language Classifications with Confidence ===============

HTML 100.00%
UNKNOWN LANGUAGE 0.00%
BATCHFILE 0.00%
C 0.00%
UNKNOWN LANGUAGE 0.00%

🏷️ Tags =====================================

##F0F8FF, ##FFF, ##333, ##007BFF, ##0056B3, #ALICEBLUE, #GHOSTWHITE, #WHITESMOKE, #AZURE, #WHITE, #SNOW, #MINTCREAM, #DARKSLATEGRAY, #BLACK, #DIMGRAY, #GRAY, #SLATEGRAY, #ROYALBLUE, #DODGERBLUE, #MEDIUMSLATEBLUE, #SLATEBLUE, #MEDIUMPURPLE, #DARKSLATEBLUE, #CORNFLOWERBLUE

👥 People ===================================

Ali Mustafa Shaikh - ali@pieces.app

➡️ Origin ===================================

Pieces for Developers

❤️ Made with love by the Pieces Team ========
