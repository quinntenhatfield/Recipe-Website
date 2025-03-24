<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple Recipe Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f8f8;
            color: #333;
        }
        .container {
            max-width: 800px;
            margin: 20px auto;
            padding: 20px;
            background: white;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
        }
        h1, h2 {
            text-align: center;
        }
        .recipe {
            margin-bottom: 20px;
            padding: 10px;
            border-bottom: 1px solid #ddd;
        }
        .recipe:last-child {
            border-bottom: none;
        }
        .recipe-title {
            font-size: 1.5em;
            margin-bottom: 10px;
        }
        .ingredients, .instructions {
            margin: 10px 0;
        }
        .ingredients ul, .instructions ol {
            padding-left: 20px;
        }
        @media (max-width: 600px) {
            .container {
                padding: 10px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Recipe Website</h1>
        <div class="recipe">
            <div class="recipe-title">Spaghetti Carbonara</div>
            <div class="ingredients">
                <h2>Ingredients</h2>
                <ul>
                    <li>200g spaghetti</li>
                    <li>100g pancetta</li>
                    <li>2 large eggs</li>
                    <li>50g parmesan cheese</li>
                    <li>Black pepper</li>
                    <li>Salt</li>
                </ul>
            </div>
            <div class="instructions">
                <h2>Instructions</h2>
                <ol>
                    <li>Cook spaghetti according to package instructions.</li>
                    <li>Fry pancetta in a pan until crispy.</li>
                    <li>Beat eggs and mix with grated parmesan.</li>
                    <li>Drain spaghetti and mix with pancetta.</li>
                    <li>Remove from heat, then stir in egg mixture.</li>
                    <li>Season with black pepper and serve.</li>
                </ol>
            </div>
        </div>
    </div>
</body>
</html>
