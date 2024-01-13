<!DOCTYPE html>
<html>

<head>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous">
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>
</head>

<body>
    <div id="sectionhomepage">
        <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/software-developer-img.png" class="img" />
        <h1 class="head">My Projects</h1>
        <p class="para">Hi, I'M Karthikeya Pantam,These are few of my static website projects that i have developed using HTML,CSS AND Bootstrap</p>
        <div class="d-flex flex-row justify-content-center">
            <div class="d-flex flex-row">
                <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/advanced-technologies-img.png" class="imgadv" onclick="display('sectionadvtech')" />
                <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/diwali-img.png" class="imgadv" onclick="display('sectiondiwali')" />
            </div>
            <div class="d-flex flex-row">
                <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/food-img.png" class="imgadv" onclick="display('sectionfood')" />
                <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/news-paper-img.png" class="imgadv" onclick="display('sectionpaper')" />
            </div>
        </div>
    </div>
    <div id="sectionadvtech">
        <div class="bg-containeradv d-flex flex-column justify-content-end ">
            <div class="d-flex ">
                <div class="detail-cardadv">
                    <h1> Advanced Technologies </h1>
                    <p class="paragraphadv">Machinery and equipment developed from the appilication of scientific knowledge.</p>

                    <button class="button1adv">learn more</button>
                    <button class="btn btn-primary" onclick="display('sectionhomepage')">Back</button>
                </div>
            </div>
        </div>
    </div>
    <div id="sectionpaper">
        <div class="bg-containerpap d-flex flex-column justify-content-end">
            <div class="headingpap">
                <h1>Main Heading</h1>
                <p class="heading1pap">NEWS OF THE DAY</p>
                <h5 class="heading2pap">iB Cricket annouunces World's first Virtual Reailty Cricket League</h5>
                <p class="paragraphpap">iB Cricket and viu together have announced the World's first virtual reality cricket Leaguefeautring 12 international cricketers,who will be completing against each other for the ib cricket super over league title in mumbai. iconic cricketers like virender sehwag,raina,brendon mccullum will will be competing in the league</p>
                <button class="buttonpap">Read more</button>
                <button class="btn btn-primary" onclick="display('sectionhomepage')">Back</button>
            </div>
        </div>
    </div>
    <div id="sectionfood">
        <div class="bg-containerfood d-flex flex-column justify-content-end">
            <div class="card1food">
                <h1 class="headingfood">Happy Meals</h1>
                <p>Discover the best foods over the 1,000</br>restaruants</p>
                <button class="buttonfood">Book Now </button>
                <button class="btn btn-primary" onclick="display('sectionhomepage')">Back</button>
            </div>
        </div>
    </div>
    <div id="sectiondiwali">
        <div class="diwali-top-section">
            <h1 class="diwali-top-section-heading">
                Celebrate Diwali with your friends
            </h1>
        </div>
        <div class="diwali-bottom-section">
            <div class="d-flex flex-row justify-content-center">
                <div class="diwali-card-item">
                    <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/lamp-img.png" class="diwali-card-image" />
                    <h1 class="diwali-card-name">Diwali Air Balloon</h1>
                    <p class="diwali-card-price">Rs 369</p>
                </div>

                <div class="diwali-card-item">
                    <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/diya-img.png" class="diwali-card-image" />
                    <h1 class="diwali-card-name">Diwali - Lamp</h1>
                    <p class="diwali-card-price">Rs 50</p>
                </div>
            </div>
            <div class="d-flex flex-row justify-content-center">
                <div class="diwali-card-item">
                    <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/firework-img.png" class="diwali-card-image" />
                    <h1 class="diwali-card-name">Sparklers</h1>
                    <p class="diwali-card-price">Rs 150</p>
                </div>

                <div class="diwali-card-item">
                    <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/firecracker-img.png" class="diwali-card-image" />
                    <h1 class="diwali-card-name">Fire Cracker</h1>
                    <p class="diwali-card-price">Rs 560</p>
                </div>
            </div>
            <button class="btn btn-primary" onclick="display('sectionhomepage')">Back</button>
        </div>
    </div>

    <script type="text/javascript" src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/js/ccbp-ui-kit.js"></script>
</body>

</html>
