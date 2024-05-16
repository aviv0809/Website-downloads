<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <meta name="keywords" content="codecell, tsec, contact, contact us, harsh kapadia, html, css, js, vanilla css">
        <meta name="description" content="A static contact us page for TSEC CodeCell by Harsh Kapadia">
        <meta name="author" content="Harsh Kapadia">

        <link href="https://fonts.googleapis.com/css2?family=Overpass+Mono&display=swap" rel="stylesheet">
        <link rel="stylesheet" href="./static/css/base.css">
        <link rel="stylesheet" href="./static/css/navbar.css">
        <link rel="stylesheet" href="./static/css/main.css">
        <link rel="stylesheet" href="./static/css/footer.css">
        
        <link rel="shortcut icon" href="./static/img/codecell_logo.svg" type="image/x-icon" sizes="any">

        <script defer src="./static/js/account_dropdown.js"></script>
        <script defer src="./static/js/main.js"></script>
        <script defer src="./static/js/burger_menu_dropdown.js"></script>

        <title>TSEC CodeCell</title>
    </head>

    <body>
        <nav class="navbar">
            <div class="left-side">
                <div class="burger-menu">
                    <div class="line-1"></div>
                    <div class="line-2"></div>
                    <div class="line-3"></div>
                </div>
    
                <ul class="navbar-main-ul hide-burger-menu burger-menu-dropdown">
                    <a href="index.html"><li>Home</li></a>
                    <a href="#"><li>About</li></a>
                    <a href="#"><li>Challenges</li></a>
                    <a href="download.html"><li>Download</li></a>
                    <a href="contact.html"><li>Contact Us</li></a>
                </ul>
            </div>

            <div class="right-side">
                <div class="account">
                    <img src="./static/img/blank-profile-picture.jpg" alt="HK">
                    
                    <div class="dropdown-caret"></div>
                </div>
                
                <div class="dropdown hide">
                    <div class="user-name">UserName</div>

                    <ul>
                        <a href="#"><li>Your profile</li></a>
                        <a href="#"><li>Settings</li></a>
                        <a href="#"><li>Log Out</li></a>
                    </ul>
                </div>
            </div>
        </nav>

        <main class="container">
            <div class="title">Contact us</div>
            <div class="title-info">We'll get back to you soon!</div>

            <form action="https://api.web3forms.com/submit" method="POST" class="form">

                <input type="hidden" name="access_key" value="21bb7833-99c0-4155-83ca-e5be3fbc71c6">

                <div class="input-group">
                    <input type="text" name="first_name" id="first-name" placeholder="First name">
                    <label for="first-name">First name</label>
                </div>
                
                <div class="input-group">
                    <input type="text" name="last_name" id="last-name" placeholder="Last Name">
                    <label for="last-name">Last name</label>
                </div>

                <div class="input-group">
                    <input type="email" name="e-mail" id="e-mail" placeholder="e-mail">
                    <label for="e-mail">e-mail</label>
                </div>

                <div class="textarea-group">
                    <textarea name="message" id="message" rows="5" placeholder="Message"></textarea>
                    <label for="message">Message</label>
                </div>

                <div class="button-div">
                    <button type="submit">Send</button>
                </div>
            </form>
        </main>

        <footer>
            <a href="#" target="_blank"><img class="social-media-img" src="./static/img/social_media/facebook.svg" alt="Facebook"></a>
            <a href="#" target="_blank"><img class="social-media-img" src="./static/img/social_media/github.svg" alt="GitHub"></a>
            <a href="#" target="_blank"><img class="social-media-img" src="./static/img/social_media/instagram.svg" alt="Instagram"></a>

            <a href="#" target="_blank"><img class="social-media-img" src="./static/img/social_media/linkedin.svg" alt="LinkedIn"></a>
            <a href="#" target="_blank"><img class="social-media-img" src="./static/img/social_media/twitter.svg" alt="Twitter"></a>
            <a href="#" target="_blank"><img class="social-media-img" src="./static/img/social_media/youtube.svg" alt="YouTube"></a>
        </footer>
    </body>
</html>
