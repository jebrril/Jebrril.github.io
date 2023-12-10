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
            <p>Discover our loving cats available for adoption. They are looking for a forever home!</p>
        </section>

        <section id="food">
            <h2>Food</h2>
            <img class="cat-image" src="food-cat.jpg" alt="Food Cat">
            <p>Explore the best food options for your feline friend. Keep them happy and healthy!</p>
        </section>

        <section id="sale">
            <h2>Sale</h2>
            <img class="cat-image" src="sale-cat.jpg" alt="Sale Cat">
            <p>Find accessories and essentials for your cat. Choose from a variety of high-quality products!</p>
        </section>

        <section id="care">
            <h2>Care</h2>
            <img class="cat-image" src="care-cat.jpg" alt="Care Cat">
            <p>Learn how to take care of your cat's well-being. Tips for grooming, health, and happiness!</p>
        </section>
    </main>

    <footer>
        <p>Contact us for any inquiries about cats</p>
    </footer>
</body>

</html>
