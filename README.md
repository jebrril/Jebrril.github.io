<head>
    <meta charset="UTF-8">
    <title>Cats Page</title>
    <meta name="description" content="A page dedicated to adoption, food, sale, and care for cats">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        /* Your CSS styles can be added here for formatting */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
        }
        header {
            background-color: #f2f2f2;
            padding: 20px 0;
            text-align: center;
        }
        nav ul {
            list-style: none;
            padding: 0;
            margin: 0;
            display: flex;
            justify-content: center;
        }
        nav ul li {
            margin: 0 10px;
        }
        main {
            padding: 20px;
        }
        section {
            margin-bottom: 40px;
        }
        section h2 {
            border-bottom: 2px solid #ccc;
            padding-bottom: 5px;
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 20px 0;
        }
        .cat-image {
            width: 100%;
            height: auto;
            border-radius: 5px;
            margin-bottom: 10px;
        }
        .nav-buttons {
            text-align: center;
            margin-top: 20px;
        }
        .nav-buttons button {
            padding: 8px 16px;
            margin: 0 5px;
            border: none;
            border-radius: 5px;
            background-color: #3498db;
            color: #fff;
            cursor: pointer;
        }
    </style>
</head>

<body>
    <header>
        <h1>Welcome to the Cats Page</h1>
        <nav>
            <ul>
                <li><a href="#adoption">Adoption</a></li>
                <li><a href="#food">Food</a></li>
                <li><a href="#sale">Sale</a></li>
                <li><a href="#care">Care</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="adoption">
            <h2>Adoption</h2>
            <img class="cat-image" src="adoption-cat.jpg" alt="Adoption Cat">
            <p>Find your perfect furry companion for adoption. Our cats are waiting for a loving home where they can bring joy and happiness!</p>
            <div class="nav-buttons">
                <button><a href="#food">Food</a></button>
                <button><a href="#sale">Sale</a></button>
                <button><a href="#care">Care</a></button>
            </div>
        </section>

        <section id="food">
            <h2>Food</h2>
            <img class="cat-image" src="food-cat.jpg" alt="Food Cat">
            <p>Discover the best nutrition options for your furry friends. From premium brands to homemade recipes, keep your cats healthy and satisfied!</p>
            <div class="nav-buttons">
                <button><a href="#adoption">Adoption</a></button>
                <button><a href="#sale">Sale</a></button>
                <button><a href="#care">Care</a></button>
            </div>
        </section>

        <section id="sale">
            <h2>Sale</h2>
            <img class="cat-image" src="sale-cat.jpg" alt="Sale Cat">
            <p>Explore a variety of accessories and essentials for your cats. Choose from toys, grooming tools, and more to keep your cats entertained and healthy!</p>
            <div class="nav-buttons">
                <button><a href="#adoption">Adoption</a></button>
                <button><a href="#food">Food</a></button>
                <button><a href="#care">Care</a></button>
            </div>
        </section>

        <section id="care">
            <h2>Care</h2>
            <img class="cat-image" src="care-cat.jpg" alt="Care Cat">
            <p>Learn how to provide the best care for your cats. From grooming routines to health tips, ensure your cats lead happy and healthy lives!</p>
            <div class="nav-buttons">
                <button><a href="#adoption">Adoption</a></button>
                <button><a href="#food">Food</a></button>
                <button><a href="#sale">Sale</a></button>
            </div>
        </section>
    </main>

    <footer>
        <p>Contact us for any inquiries about cats</p>
    </footer>
</body>

</html>
