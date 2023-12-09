# anishahlawat-mapup.ai
<!DOCTYPE html>
<html>

<head>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous">
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>
</head>

<body>
    <div class="bg-container">
        <div id="carouselExampleSlidesOnly" class="carousel slide" data-ride="carousel">
            <div class="carousel-inner">
                <div class="carousel-item active">
                    <img class="d-block w-100" src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/nemo-c1-img.png" alt="First slide">
                </div>
                <div class="carousel-item">
                    <img class="d-block w-100" src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/nemo-c2-img.png" alt="Second slide">
                </div>
                <div class="carousel-item">
                    <img class="d-block w-100" src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/nemo-c3-img.png" alt="Third slide">
                </div>
            </div>
        </div>
        <div class="d-flex flex-row justify-content-between">
            <h1 class="main-heading"> Finding Nemo</h1>
            <button class="button"> Watch Now</button>
        </div>
        <p class="p"> A clown fish,is overly cautious with his son, Nemo who has a foreshortend fin.when Nemoswims too close to suface to prove himself,he is caught by diver,and horrified marlin must set out to find him.A blue reef fish named Dory jions marlin and complicates the encounters with sharks , jellyfish ,and a host of ocean dangers.Meanwhile ,Nemoplots his escape from a dentist's fish tank.</p>
        <h1 class="heading similar-movies"> Similar Movies</h1>
        <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/finding-dory-img.png" />
        <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/bugslife-img.png" />
        <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/ratatouille-movie-img.png" />
    </div>
</body>

</html>


CSS code:
@import url('https://fonts.googleapis.com/css2?family=Bree+Serif&family=Caveat:wght@400;700&family=Lobster&family=Monoton&family=Open+Sans:ital,wght@0,400;0,700;1,400;1,700&family=Playfair+Display+SC:ital,wght@0,400;0,700;1,700&family=Playfair+Display:ital,wght@0,400;0,700;1,700&family=Roboto:ital,wght@0,400;0,700;1,400;1,700&family=Source+Sans+Pro:ital,wght@0,400;0,700;1,700&family=Work+Sans:ital,wght@0,400;0,700;1,700&display=swap');

.bg-container {
    background-image: url("https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/orange-color-bg.png");
    background-size: cover;
    height: 100vh;
    padding: 20px;
    font-family: Roboto;
}

.main-heading {
    color: white;
    margin-top: 0px;
    font-family: "Roboto";
    font-size: 30px;
    padding: 5px;
}

.button {
    background-color: white;
    border-radius: 12px;
    padding: 5px;
    margin: 12px;
}

.p {
    color: #ffffff;
    font-size: 16px;
    padding: 5px;
}

.heading {
    color: white;
    font-family: "Roboto";
    font-size: 30px;
    padding: 5px;
    margin-left: 5px;
    margin-right: 5px;
}
