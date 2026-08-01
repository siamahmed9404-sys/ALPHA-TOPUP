<style>
body{
    margin:0;
    font-family:Arial,sans-serif;
    background:#eef3fb;
}

/* Section */
.section{
    padding:20px 15px;
}

.section-title{
    text-align:center;
    color:#183b67;
    font-size:32px;
    font-weight:bold;
    margin-bottom:20px;
}

/* Grid */
.grid{
    display:grid;
    grid-template-columns:repeat(3,1fr);
    gap:15px;
}

/* Card */
.card{
    background:#fff;
    border-radius:12px;
    overflow:hidden;
    box-shadow:0 4px 10px rgba(0,0,0,.15);
    transition:.3s;
}

.card:hover{
    transform:translateY(-5px);
}

.card img{
    width:100%;
    height:110px;
    object-fit:cover;
    background:#5b21b6;
}

.card-title{
    padding:10px;
    text-align:center;
    font-weight:bold;
    color:#333;
    font-size:14px;
}

/* Colored Section */
.special{
    background:#f6f8ff;
}

.topup{
    background:#ffffff;
    border-radius:20px 20px 0 0;
}
</style>


<!-- Special Offers -->

<section class="section special">

<h2 class="section-title">Special Offers</h2>

<div class="grid">

<div class="card">
<img src="images/spin.jpg">
<div class="card-title">Free Offer</div>
</div>

<div class="card">
<img src="images/airdrop.jpg">
<div class="card-title">ID Password</div>
</div>

<div class="card">
<img src="images/bonus.jpg">
<div class="card-title">Daily Bonus</div>
</div>

</div>

</section>


<!-- Top Up -->

<section class="section topup">

<h2 class="section-title">Top Up</h2>

<div class="grid">

<div class="card">
<img src="images/ff1.jpg">
<div class="card-title">FF TopUp [BD]</div>
</div>

<div class="card">
<img src="images/pass.jpg">
<div class="card-title">Level Up Pass</div>
</div>

<div class="card">
<img src="images/member.jpg">
<div class="card-title">Weekly / Monthly</div>
</div>

<div class="card">
<img src="images/lite.jpg">
<div class="card-title">Weekly Lite</div>
</div>

<div class="card">
<img src="images/like.jpg">
<div class="card-title">FF Like</div>
</div>

<div class="card">
<img src="images/server.jpg">
<div class="card-title">Indonesia Server</div>
</div>

</div>

</section>
