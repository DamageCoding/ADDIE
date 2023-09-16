<!DOCTYPE html>
<html>

<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, shrink-to-fit=no">
    <title>Addie</title>
    <meta name="description" content="THE DISCORD BOT OF THE YEAR">
    <meta name="theme-color" content="#f54254">
    <link rel="icon" type="image/png" sizes="300x250" href="assets/img/superthumb.png">
    <link rel="stylesheet" href="assets/bootstrap/css/bootstrap.min.css">
    <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Alfa+Slab+One">
    <link rel="stylesheet" href="assets/fonts/font-awesome.min.css">
    <link rel="stylesheet" href="assets/fonts/ionicons.min.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/3.5.2/animate.min.css">
    <link rel="stylesheet" href="assets/css/styles.css">

    <!-- Loading Screen Styles -->
    <style>
        #loading-screen {
            position: fixed;
            display: flex;
            justify-content: center;
            align-items: center;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0, 0, 0, 0.8);
            color: white;
            z-index: 9999;
        }

        #loading-spinner {
            border: 4px solid rgba(255, 255, 255, 0.3);
            border-radius: 50%;
            border-top: 4px solid #f54254;
            width: 50px;
            height: 50px;
            animation: spin 1s linear infinite;
        }

        @keyframes spin {
            0% {
                transform: rotate(0deg);
            }

            100% {
                transform: rotate(360deg);
            }
        }
    </style>

    <!-- Bot Features Styles -->
    <style>
        .features-boxed {
            background-color: var(--background);
            padding: 80px 0;
            text-align: center;
        }

        .features-boxed h2 {
            margin-bottom: 50px;
            color: var(--text-color);
        }

        .features-boxed .item {
            margin-bottom: 30px;
        }

        .features-boxed .box {
            background-color: #fff;
            padding: 40px;
            border-radius: 10px;
            box-shadow: 0px 0px 20px rgba(0, 0, 0, 0.1);
        }

        .features-boxed .icon {
            font-size: 50px;
            margin-bottom: 20px;
            color: var(--main-color);
        }

        .features-boxed .name {
            font-size: 24px;
            margin-bottom: 15px;
            color: green; /* Change title text color to green */
        }

        .features-boxed .description {
            font-size: 16px;
            color: black; /* Change text color to black */
        }
    </style>
</head>

<body style="background-color: var(--background);">

    <!-- Loading Screen -->
    <div id="loading-screen">
        <div id="loading-spinner"></div>
        <p>Loading...</p>
    </div>

    <!-- Navigation bar section -->
    <div id="top" style="height: 12px; border-bottom: 2px solid var(--main-color);">
        <nav class="navbar navbar-light navbar-expand fixed-top"
            style="color: var(--main-color); border-top-width: 6px; border-top-style: solid; background: var(--background);">
            <div class="container-fluid">
                <a class="navbar-brand" href="#" style="color: var(--main-color); font-family: 'Alfa Slab One', cursive;">Addie</a>
                <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navcol-1">
                    <span class="sr-only">Toggle navigation</span>
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navcol-1">
                    <ul class="nav navbar-nav">
                        <li class="nav-item">
                            <a class="nav-link active smoothScroll" href="#feature" style="color: var(--text-color);">Features</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="https://discords.com/bots/bot/1146975902262112287" style="color: var(--text-color);">Discords.com</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="https://top.gg/bot/1146975902262112287" style="color: var(--text-color);">top.gg</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="https://discord.bots.gg/bots/1146975902262112287" style="color: var(--text-color);">discord.bots.gg</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="https://discordbotlist.com/bots/addie" style="color: var(--text-color);">discordbotlist.com</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="https://discordlist.gg/bot/1146975902262112287" style="color: var(--text-color);">discordlist.gg</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#" style="color: var(--text-color);">Invite</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#bot-status" style="color: var(--text-color);">Bot Status</a>
                        </li>
                    </ul>
                </div>
            </div>
        </nav>
    </div>

    <!-- Header section -->
    <header class="d-xl-flex flex-column justify-content-xl-center align-items-xl-center"
        style="height: 418px; text-align: center; margin: 55px;">
        <img class="rounded"
            src="https://cdn.discordapp.com/attachments/1146997057584898120/1149181648005517322/0227b70ce63319556a19680416a29265.webp"
            width="150" height="150" style="margin-top: 30px;">
        <h1 class="d-xl-flex justify-content-xl-start"
            style="color: var(--text-color);">Addie</h1>
        <p style="color: var(--secondary-text-color);">A bot for mod and fun!</p>
        <div class="tada animated">
            <div role="group" class="btn-group">
                <a href="https://discord.com/api/oauth2/authorize?client_id=1146975902262112287&permissions=8&scope=bot"
                    class="btn btn-primary shadow-none" type="button"
                    style="margin: 5px; background-color: var(--main-color); border-color: var(--main-color); border-radius: 10px;">Invite
                    Me</a>
                <section>
                    <div class="container text-center">
                        <h2>Join Our Discord</h2>
                        <p>Join our Discord server to chat with the community and get the latest updates about our bot!</p>
                        <a href="https://discord.gg/Wddh4FMPKs" class="btn btn-primary"
                            target="_blank">Join Now</a>
                    </div>
                </section>
                <a class="btn btn-primary smoothScroll shadow-none" role="button"
                    style="margin: 5px; background-color: var(--main-color); border-color: var(--main-color); border-radius: 10px;"
                    href="#feature">Features</a>
            </div>
        </div>
    </header>

    <!-- Bot Features section -->
    <div class="features-boxed" style="border-top: 2px solid var(--main-color);">
        <div class="container">
            <div class="intro">
                <h2 class="text-center">Bot Features</h2>
            </div>
            <div class="row justify-content-center features">
                <div class="col-sm-6 col-md-4 item">
                    <div class="box">
                        <i class="fa fa-rocket icon"></i>
                        <h3 class="name">Lightning-Fast</h3>
                        <p class="description">Our bot is now lightning-fast with reduced latency.</p>
                    </div>
                </div>
                <div class="col-sm-6 col-md-4 item">
                    <div class="box">
                        <i class="fa fa-shield icon"></i>
                        <h3 class="name">Secure &amp; Private</h3>
                        <p class="description">We prioritize your security and privacy.</p>
                    </div>
                </div>
                <div class="col-sm-6 col-md-4 item">
                    <div class="box">
                        <i class="fa fa-smile-o icon"></i>
                        <h3 class="name">User-Friendly</h3>
                        <p class="description">Our users leave with smiles on their faces!</p>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- Set Icon section -->
    <div class="set-icon-section" style="border-top: 2px solid var(--main-color);">
        <div class="container">
            <h2>Set Your Icon</h2>
            <div class="icon-grid">
                <div class="icon-box">
                    <i class="fa fa-user-circle icon"></i>
                    <p class="icon-label">User Icon</p>
                </div>
                <div class="icon-box">
                    <i class="fa fa-bolt icon"></i>
                    <p class="icon-label">Lightning Bolt</p>
                </div>
                <div class="icon-box">
                    <i class="fa fa-heart icon"></i>
                    <p class="icon-label">Heart</p>
                </div>
                <div class="icon-box">
                    <i class="fa fa-star icon"></i>
                    <p class="icon-label">Star</p>
                </div>
                <!-- Add more icon boxes as needed -->
            </div>
        </div>
    </div>

    <!-- Social Media Links - Update the links -->
    <section id="social-media" style="border-top: 2px solid var(--main-color);">
        <div class="container text-center">
            <h2>Connect with Us</h2>
            <p>Stay updated with the latest news and announcements by following us on social media.</p>
            <a href="https://www.youtube.com/@ItsAddieBot" target="_blank" class="social-icon"><i class="fa fa-youtube"></i></a>
            <a href="https://www.tiktok.com/@itsaddiebot" target="_blank" class="social-icon"><i class="fa fa-tiktok"></i></a>
            <a href="https://twitter.com/ItsAddieBot" target="_blank" class="social-icon"><i class="fa fa-twitter"></i></a>
        </div>
    </section>

    <!-- Partner section -->
    <section id="partner-section" style="border-top: 2px solid var(--main-color); border-bottom: 2px solid var(--main-color);">
        <div class="container text-center">
            <h2>Partner Code Redemption (NONE YET)</h2>
            <p>Have a partner code? Redeem it below:</p>
            <div class="row justify-content-center">
                <div class="col-md-6">
                    <div class="input-group mb-3">
                        <input type="text" class="form-control" placeholder="Enter your code" aria-label="Enter your code" aria-describedby="redeem-button">
                        <div class="input-group-append">
                            <button class="btn btn-primary" type="button" id="redeem-button">Redeem</button>
                        </div>
                    </div>
                </div>
            </div>
            <p id="redeem-result"></p>
        </div>
    </section>

    <!-- Footer section -->
    <footer style="background: var(--background); padding: 20px; text-align: center; border-top: 2px solid var(--main-color);">
        <div class="container">
            <p>&copy; 2023 Addie. All rights reserved.</p>
            <a href="#top" class="btn btn-primary">Back to Top</a>
        </div>
    </footer>

    <!-- JavaScript to Hide Loading Screen After 6 Seconds -->
    <script>
        window.addEventListener("load", function () {
            var loadingScreen = document.getElementById("loading-screen");
            loadingScreen.style.display = "flex";
            setTimeout(function () {
                loadingScreen.style.display = "none";
            }, 6000); // 6,000 milliseconds = 6 seconds
        });
    </script>

<!-- JavaScript for Partner Code Redemption -->
<script>
    document.getElementById("redeem-button").addEventListener("click", function () {
        // Get the entered code
        var code = document.querySelector("input.form-control").value;
        // Check if the entered code matches any of the valid partner codes
        var validCodes = ["Repl", "DOXEDLUCAS", "LKIDS"];
        if (validCodes.includes(code)) {
            document.getElementById("redeem-result").textContent = "Code redeemed successfully!";
        } else {
            document.getElementById("redeem-result").textContent = "Invalid code. Please try again.";
        }
    });
</script>

</body>

</html>
