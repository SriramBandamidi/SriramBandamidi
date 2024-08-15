HTML 

<!DOCTYPE html>
<html>

<head>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous">
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>
</head>

<body>

    <div id="sectionHomepage">
        <p class="conference-page-top-container">Conference Home Page :</p>
        <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/conference-img.png" class="conference-image" />

        <div class="conference-bottom-card-container">
            <h1 class="conference-bottom-heading"> The Things Conference</h1>
            <p>Readefining the future of IOT with LORAWAN</p>
            <button class="btn btn-primary" onclick="display('sectionDetailspage')">Know More</button>
        </div>
    </div>

    <div id="sectionDetailspage" class="conference-2page-heading">
        <p>Conference Details page:</p>
        <div class="embed-responsive embed-responsive-16by9">
            <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/vKJ6nXE_6Hc?rel=0" allowfullscreen></iframe>
        </div>

        <div class="conference-2page-card-container">
            <h1 class="conference-2page-2heading">The Thing Conference</h1>

            <p class="conference-2page-2para">Join Asia's Largest Conference on Lorawan</p>
        </div>

        <div class="d-flex flex-row">
            <div class="conferance-2page-card-items">
                <h1 class="conferance-2page-card-prices">1400+</h1>
                <p class="conferance-2page-card-description">Attendees</p>
            </div>

            <div class="conferance-2page-card-items">
                <h1 class="conferance-2page-card-prices">100+</h1>
                <p class="conferance-2page-card-description">Workshops</p>
            </div>
        </div>

        <div class="d-flex flex-row">
            <div class="conferance-2page-card-items">
                <h1 class="conferance-2page-card-prices">120+</h1>
                <p class="conferance-2page-card-description">Speakers</p>
            </div>

            <div class="conferance-2page-card-items">
                <h1 class="conferance-2page-card-prices">10+</h1>
                <p class="conferance-2page-card-description">Contries</p>
            </div>
        </div>
        <div class="conference-2page-back-button">
            <button class="btn btn-primary" onclick="display('sectionHomepage')">Back</button>
        </div>
    </div>
    <div>
    </div>
    <script type="text/javascript" src="https://new-assets.ccbp.in/frontend/content/static-ccbp-ui-kit/static-ccbp-ui-kit.js"></script>
</body>

</html>



CSS

@import url('https://fonts.googleapis.com/css2?family=Bree+Serif&family=Caveat:wght@400;700&family=Lobster&family=Monoton&family=Open+Sans:ital,wght@0,400;0,700;1,400;1,700&family=Playfair+Display+SC:ital,wght@0,400;0,700;1,700&family=Playfair+Display:ital,wght@0,400;0,700;1,700&family=Roboto:ital,wght@0,400;0,700;1,400;1,700&family=Source+Sans+Pro:ital,wght@0,400;0,700;1,700&family=Work+Sans:ital,wght@0,400;0,700;1,700&display=swap');

.conference-page-top-container {
    font-weight: 500;
    font-family: "Roboto";
    color: #5a7184;
    padding: 20px;
    font-size: 20px;
}
.conference-image {
    height: 50vh;
    margin-left: 45px;
}
.conference-bottom-card-container {
     width: 280px;
    text-align: center;
    margin-left: 100px;
    padding: 20px;
}
.conference-2page-heading {
    font-family: "Roboto";
    font-size: 20px;
    padding: 20px;
}
.conference-2page-card-container {
    text-align: center;
    padding: 20px;
}
.conference-2page-2heading {
    font-family: "Roboto";
    font-size: 30px;
    font-weight: bold;

}
.conference-2page-2para {
    color: gray;
    font-size: 18px;
}
.conferance-2page-card-items {
    width: 100px;
    padding: 20px;
    margin-left: 80px;
}
.conferance-2page-card-prices {
    font-size: 25px;
    font-weight: bold;
}
.conferance-2page-card-description {
    font-size: 18px;
    color: gray;
    text-align: center;
}
.conference-2page-back-button {
    text-align: center;
}

.conferance-2page-card-prices {
    
    
    font-size: 25px;
    font-weight: bold;
}
   

 
