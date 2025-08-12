<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
            <title>Cafe Menu & feedback form</title>
            <style>
                table{
                    font-family:Arial, san serif;
                    border-collapse:collapse;
                    width: 100%;
                }
                th, td {
                    border: 1px solid #9acec5;
                    text-align: center;
                    paddling:8px;
                }
                tr:nth-child(even) {
                        background-color: #daebcf;
                }

            </style>
    </head>

    <h1>Ai's Cafe &#9749;</h1>
    <p>
        <strong>Welcome to Ai's Cafe</strong> &#9749; &#127828;
    </p>
    <section>
        <h1>Ai's Menu &#128220;</h1>
        <table>
            <caption><strong>Our Specialty</strong> &#127860;</caption>
            <thead>
                <tr>
                    <th>Item</th>
                    <th>Price</th>
                    <th>Availability</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Coffee &#9749;</td>
                    <td>&#8369;89.00</td>
                    <td>&#10004;</td>
                </tr>
                <tr>
                    <td>Tea &#127861;</td>
                    <td>&#8369;89.00</td>
                    <td>&#10006;</td>
                </tr>
                <tr>
                    <td>Burger &#127828;</td>
                    <td>&#8369;50.00</td>
                    <td>&#10004;</td>
                </tr>
                <tr>
                    <td>Sandwich &#129386;</td>
                    <td>&#8369;89.00</td>
                    <td>&#10004;</td>
                </tr>
                <tr>
                    <td>Pancakes &#129374;</td>
                    <td>&#8369;89.00</td>
                    <td>&#10004;</td>
                </tr>
                <tr>
                    <td>Shortcake &#127856;</td>
                    <td>&#8369;60.00</td>
                    <td>&#10006;</td>
                </tr>
                <tr>
                    <td>Pizza &#127829;</td>
                    <td>&#8369;109.00</td>
                    <td>&#10006;</td>
                </tr>
                <tr>
                    <td>Ramen with Egg &#127836;</td>
                    <td>&#8369;179.00</td>
                    <td>&#10004;</td>
                </tr>
                <tr>
                    <td>French fries &#127839;</td>
                    <td>&#8369;89.00</td>
                    <td>&#10004;</td>
                </tr>
                <tr>
                    <td>Ice Cream &#127848;</td>
                    <td>&#8369;79.00</td>
                    <td>&#10004;</td>
                </tr>
            </tbody>
        </table>
    </section>

    <section>
            <h2>Customer Feedback</h2>
            <form>
                <label for="Name">Name:</label>
                <input type="text" id="name" name="name" required>
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>


            <h3>What's your favorite menu?</h3>
            <dropdown>
                <select>
                    <option value="select">Select your favorite menu</option>
                    <option value="coffee">Coffee</option>
                    <option value="tea">Tea</option>
                    <option value="burger">Burger</option>
                    <option value="sandwich">Sandwich</option>
                    <option value="pancakes">Pancakes</option>
                    <option value="shortcake">Shortcake</option>
                    <option value="pizza">Pizza</option>
                    <option value="ramen">Ramen</option>
                    <option value="french fries">French fries</option>
                </select>
            </dropdown>
        <form>
            </p>Please rate our cafe:</p>
            <input type="radio" id="5 Star"rating value="excellent">
            <label for="excellent">&star;&nbsp;&star;&nbsp;&star;&nbsp;&star;&nbsp;&star;</label>
            <input type="radio" id="4 star"rating value="very good">
            <label for="very good">&star;&nbsp;&star;&nbsp;&star;&nbsp;&star;</label>
            <input type="radio" id="3 star"rating value="good">
            <label for="good">&star;&nbsp;&star;&nbsp;&star;</label>
            <input type="radio" id="2 star"rating value="fair">
            <label for="fair">&star;&nbsp;&star;</label>
            <input type="radio" id="1 star"rating value="poor">
            <label for="poor">&star;</label>
  
            <p>
                <label for="comments">Comments:</label>
                <textarea id="comments" name="comments" rows="4"cols="50" placeholder="Your feedback here..."></textarea>
            </p>
            <button>Submit</button>
            
            <footer>
                <p>&copy; 2023 Ai's Cafe. All rights reserved.</p>
            </footer>
           
    </section>
</html>
