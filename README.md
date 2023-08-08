# coffe-house
https://ajit7568.github.io/coffe-house/
<!-- This is an HTML document -->
<!DOCTYPE html>
<html lang="en">
<head>
    <!-- Set the character encoding for the document -->
    <meta charset="UTF-8" />
    <!-- Specify the version of Internet Explorer to be used -->
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <!-- Configure the viewport settings for responsive design -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <!-- Set the title of the webpage (displayed in the browser tab) -->
    <title>Document</title>
    <!-- Embed CSS styles directly within the <head> section -->
    <style>
        /* Reset default margin, padding, and box-sizing for all elements */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        /* Set the background color of the body */
        body {
            background-color: rgb(165, 42, 42, 0.2);
        }
        /* Style for the navigation bar */
        nav {
            background: url("https://i.pinimg.com/736x/e1/c2/3a/e1c23ac34847740f672717c89a62ae37.jpg");
            background-position: center;
            background-repeat: no-repeat;
            background-size: cover;
            height: 300px;
            width: 100%;
            box-shadow: 0px 0px 8px black;
            margin-bottom: 40px;
        }
        /* Style for the search input */
        nav > input {
            position: sticky;
            top: 60px;
            left: 15%;
            width: 70%;
            height: 60px;
            border-radius: 10px;
            background-color: rgb(99, 18, 18, 1);
            color: white;
            border: none;
            padding: 10px;
        }
        /* Style for the focused search input */
        input:focus {
            outline: none;
            background-color: rgb(99, 18, 18, 0.9);
        }
        /* Style for the coffee menu section */
        .coffee_menu {
            display: flex;
            justify-content: space-evenly;
            align-items: center;
        }
        /* Style for individual coffee menu items */
        .coffee_menu > div {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            color: rgba(0, 0, 0, 0.8);
        }
        /* Style for the coffee menu item images */
        .img {
            height: 150px;
            width: 150px;
        }
        /* Style for the coffee menu item images (circle with shadow) */
        img {
            width: 100%;
            height: 100%;
            border-radius: 50%;
            box-shadow: 0px 8px 8px black;
        }
        /* Hover effect for coffee menu item images */
        img:hover {
            box-shadow: 0px 18px 18px black;
            height: 152px;
            width: 152px;
        }
        /* Style for coffee menu item text */
        .coffee_menu > div > h4 {
            margin-block: 15px;
        }
        /* Style for the description sections */
        .des {
            width: 90%;
            margin: auto;
            margin-block: 50px;
            background-color: rgb(165, 42, 42, 0.3);
            padding: 30px;
            border-radius: 5px;
            box-shadow: 0px 0px 8px brown;
        }
        /* Style for text within description sections */
        .des>p, .des>ol {
            line-height: 20px;
            color: brown;
        }
        /* Style for ordered list items */
        ol>li {
            padding: 5px;
        }
    </style>
</head>
<body>
    <!-- Navigation section with a search input -->
    <nav>
        <input type="text" value="Search" />
    </nav>

    <!-- Main content section -->
  <main>
        <!-- Coffee menu section -->
        <section class="coffee_menu">
            <!-- Coffee item: Cappuccino -->
  <div>
                <div class="img">
                    <img src="https://t3.gstatic.com/licensed-image?q=tbn:ANd9GcTiCxXcyNxBKgWT2_t-TQQ_DTFFEnfQz9p1OT5WTg4vaJ4eUE_OPh6Vvd4qxWJop6-w" alt="Cappuccino" />
                </div>
                <h4>Cappuccino</h4>
            </div>
            <!-- Coffee item: Espresso -->
 <div>
                <div class="img">
                    <img src="https://upload.wikimedia.org/wikipedia/commons/a/a5/Tazzina_di_caff%C3%A8_a_Ventimiglia.jpg" alt="Espresso" />
                </div>
                <h4>Espresso</h4>
            </div>
            <!-- Coffee item: Latte -->
   <div>
                <div class="img">
                    <img src="https://encrypted-tbn2.gstatic.com/images?q=tbn:ANd9GcQJppQpvbjiWse0QeBv0e2EstBXGOP1K80eAv9S0qPks2CDkhhc" alt="Latte" />
                </div>
                <h4>Latte</h4>
            </div>
            <!-- Coffee item: Flat White -->
  <div>
                <div class="img">
                    <img src="https://upload.wikimedia.org/wikipedia/commons/6/6b/Flat_white_coffee_with_pretty_feather_pattern.jpg" alt="Flat White" />
                </div>
                <h4>Flat White</h4>
            </div>
        </section>
        <!-- Description section: Coffee-House -->
   <section class="des">
            <h1 style="color: brown;">Coffee-House</h1>
            <!-- Description text -->
   <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Distinctio
                error recusandae iure illum nihil non reiciendis laborum et
                consequatur fugit. Lorem ipsum dolor, sit amet consectetur adipisicing
                elit. Ex illum earum maiores necessitatibus vero officia expedita, ad
                odio omnis distinctio facere perferendis quas repellat alias quos
                incidunt dolor beatae quia. Numquam aliquam molestias nostrum sequi.
                Doloremque libero ex voluptas natus, corporis provident esse,
                obcaecati tenetur inventore, odit labore pariatur officia corrupti
                suscipit debitis sequi quod nihil? Adipisci vel laborum voluptate
                iusto optio commodi quibusdam repudiandae accusantium molestiae
                officiis reprehenderit nulla nostrum dolore corporis libero, quaerat
                accusamus cupiditate ex quisquam enim eum id cum. Neque, eaque?
                Accusantium quae magnam laudantium necessitatibus, neque praesentium
                ullam voluptates fugit unde, aliquam dignissimos? Asperiores,
                blanditiis.
            </p>
            <!-- Additional paragraphs -->
  <br>
            <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Distinctio
                error recusandae iure illum nihil non reiciendis laborum et
                consequatur fugit. Lorem ipsum, dolor sit amet consectetur adipisicing
                elit. Consequatur numquam fugiat quibusdam voluptates inventore,
                corrupti assumenda pariatur, maiores est eius sunt ipsa et quasi
                labore voluptatem odit adipisci molestiae esse, dicta illum? Natus,
                tempora doloribus! Ab molestias quidem alias, assumenda perferendis
                mollitia aliquam dolor totam voluptatem? Beatae nisi fugit cupiditate.
            </p>
            <br>
            <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Distinctio
                error recusandae iure illum nihil non reiciendis laborum et
                consequatur fugit. Lorem ipsum dolor, sit amet consectetur adipisicing
                elit. Ex illum earum maiores necessitatibus vero officia expedita, ad
                odio omnis distinctio facere perferendis quas repellat alias quos
                incidunt dolor beatae quia. Numquam aliquam molestias nostrum sequi.
                Doloremque libero ex voluptas natus, corporis provident esse,
                obcaecati tenetur inventore, odit labore pariatur officia corrupti
                suscipit debitis sequi quod nihil? Adipisci vel laborum voluptate
                iusto optio commodi quibusdam repudiandae accusantium molestiae
                officiis reprehenderit nulla nostrum dolore corporis libero, quaerat
                accusamus cupiditate ex quisquam enim eum id cum. Neque, eaque?
                Accusantium quae magnam laudantium necessitatibus, neque praesentium
                ullam voluptates fugit unde, aliquam dignissimos? Asperiores,
                blanditiis.
            </p>
        </section>
        <!-- Description section: Coffee list -->
   <section class="des">
  <h1 style="color: brown;">Coffee list</h1>
            <!-- Ordered list of coffee items -->
            <ol>
                <li>Coffee-1</li>
                <li>Coffee-2</li>
                <li>Coffee-3</li>
                <li>Coffee-4</li>
                <li>Coffee-5</li>
                <li>Coffee-6</li>
            </ol>
            <br>
            <!-- Additional description text -->
   <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Distinctio
                error recusandae iure illum nihil non reiciendis laborum et
                consequatur fugit. Lorem ipsum dolor, sit amet consectetur adipisicing
                elit. Ex illum earum maiores necessitatibus vero officia expedita, ad
                odio omnis distinctio facere perferendis quas repellat alias quos
                incidunt dolor beatae quia. Numquam aliquam molestias nostrum sequi.
                Doloremque libero ex voluptas natus, corporis provident esse,
                obcaecati tenetur inventore, odit labore pariatur officia corrupti
                suscipit debitis sequi quod nihil? Adipisci vel laborum voluptate
                iusto optio commodi quibusdam repudiandae accusantium molestiae
                officiis reprehenderit nulla nostrum dolore corporis libero, quaerat
                accusamus cupiditate ex quisquam enim eum id cum. Neque, eaque?
                Accusantium quae magnam laudantium necessitatibus, neque praesentium
                ullam voluptates fugit unde, aliquam dignissimos? Asperiores,
                blanditiis.
            </p>
        </section>
    </main>
</body>
</html>
