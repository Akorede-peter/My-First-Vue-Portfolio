<script>
    import { ref } from 'vue';

</script>
<template>
    <!-- SECTION ONE STARTS FROM HERE -->
    <section class="section_one">
        <div class="section_one_text">
            <h2>Discover And Collect Rare NFTs</h2>
            <p>The most secure place for buying and selling unique crypto assets.</p>
            <div class="section_one_buttons">
                <button class="section_one_btn1">Buy NFTs</button>
                <button class="section_one_btn2">Sell NFTs</button>
            </div>
        </div>
        <div class="section_one_img">
            <img src="/images/Other 07.png" alt="image" />
        </div>
    </section>
    <!-- SECTION ONE ENDS HERE -->
     <!-- SECTION TWO STARTS FROM HERE -->
    <section class="section_two">
        <h2>FEATURED ON</h2>
        <div class="section_two_imgs">
            <img src="/images/image 6.png" alt="Featured 1">
            <img src="/images/image 5.png" alt="Featured 4">
            <img src="/images/image 7.png" alt="Featured 2">
            <img src="/images/image 8.png" alt="Featured 3">
        </div>
    </section>
    <!-- SECTION TWO ENDS HERE -->
    <!-- SECTION THREE STARTS FROM HERE -->
    <section class="section_three">
        <div>
            <img src="/images/Other 18.png" alt="image" />
        </div>
        <div class="section_three_text">
            <h2>Analytics</h2>
            <span class="section_three_span">Built-In Analytics To Track Your Nfts</span>
            <p>Use our built-in analytics dashboard to pull valuable insights and monitor the value of your krypto portfolio over time.</p>
            <button class="section_three_btn">VIEW OUR PRICING</button>
        </div>

    </section>
    <!-- SECTION THREE ENDS HERE -->
    <!-- SECTION FOUR STARTS FROM HERE -->
    <section class="section_four">
        <div class="section_four_text">
            <h2>Get Our App</h2>
            <span class="section_four_span">Browse NFTs From Your smartphone</span>
            <p>Use our built-in analytics dashboard to pull valuable insights and monitor the value of your krypto portfolio over time.</p>
            <button class="section_three_btn">VIEW OUR PRICING</button>
        </div>
        <div>
            <img src="/images/Other 17.png" alt="image" />
        </div>
        
    </section>
    <!-- SECTION FOUR ENDS HERE -->
    <!-- SECTION FIVE STARTS FROM HERE -->
    <section class="section_five">
        <h2>TESTIMONIALS</h2>
        <div class="head_span">
            <span >Read What Others Have To Say</span>
        </div>
        <div class="sec_five_flexbox">
            <div class="sec_five_flexboxes">
                <div>
                    <img src="/images/Ellipse 3.png" alt="Image">
                </div>
                <span>OLIVIA COLE</span>
                <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Accusamus cumque animi consequatur aut! Veritatis, sit?</p>
            </div>
            <div class="sec_five_flexboxes">
                <div>
                    <img src="/images/Ellipse 4.png" alt="Image">
                </div>
                <span>EVEN WHITE</span>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatum libero blanditiis recusandae voluptate similique.</p>
            </div>
            <div class="sec_five_flexboxes">
                <div>
                    <img src="/images/Ellipse 5.png" alt="Image">
                </div>
                <span>JOHN MILLER</span>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolor unde laboriosam quidem nobis dicta obcaecati.</p>
            </div>
        </div>
    </section>
    <!-- SECTION FIVE ENDS HERE -->
    <!-- SECTION SIX STARTS FROM HERE -->
    <section class="section_six">
        <p class="ready-label">ARE YOU READY?</p>
        <h2>Be A Part Of The<br />Next Big Thing</h2>
        <a class="get-started" href="#get-started">GET STARTED</a>
    </section>
    <!-- SECTION SIX ENDS HERE -->
        
</template>
<style scoped>
.section_one {
    display: flex;
    justify-content: space-between;
    align-items: center;
    gap: 10rem;
    width: 80%;
    margin: 0 auto;
    padding: 2rem 0;
}
.section_one_text{
    width: 100%;
}
.section_one h2 {
    font-size: 4rem;
    line-height: 1.2;
    color: #fff;
    margin: 0 0 1rem 0;
    padding: 0;
    text-align: left;
    width: 100%;
    max-width: 400px;
}
.section_one p {
    font-size: 1.2rem;
    line-height: 1.5;
    color: #fff;
    margin: 0 0 2rem 0;
    padding: 0;
    text-align: left;
    width: 100%;
    max-width: 400px;
}
    

.section_one_img{
    width: 100%;
}
.section_one_img img {
    width: 100%;
    height: auto;
}
.section_one_buttons{
    display: flex;
    gap: 1rem;
}
.section_one button{
    padding: 15px 50px;
    border-radius: 21px;
    cursor: pointer;
}
.section_one_btn1{
    background-color: #2d2879;
    color: #fff;
    border: none;
}
.section_one_btn1:hover{
    background-color: #fff;
    color: #2d2879;
}
.section_one_btn2{
    background-color: transparent;
    color: #fff;
    border: 1px solid #fff;
}
.section_one_btn2:hover{
    background-color: #fff;
    color: #2d2879;
}
.section_two{
    width: 80%;
    margin: 0 auto;
    padding: 2rem 0;

}
.section_two h2{
    padding: 0;
    margin: 0;
    color:#fff;
    text-align: left;

}
.section_two_imgs{
  display: flex;
  align-items: center;
  justify-content: space-around;
  gap: 32px;
  background: linear-gradient(110deg, #101447 0%, #0a0f46 65%, #131949 100%);
  color: #fff;
  padding: 10px 24px 20px;
  margin-top: 20px;
}
.section_two_imgs img{
    width: 100px;
    height: auto;
    display: block;
}
.section_three{
    display: flex;
    justify-content: space-between;
    align-items: center;
    gap: 9rem;
    width: 70%;
    margin: 0 auto;
    padding: 2rem 0;
}
.section_three img{
    width: 100%;
    height: auto;
}
.section_three_text{
    width: 100%;
    text-align: left;

}
.section_three h2{
    font-size: 1rem;
    color: #ABD9D9;
    margin: 0 0 .5rem 0;
    padding: 0;
    text-align: left;
    text-transform: uppercase;
}
.section_three_span{
    font-size: 2.3rem;
    line-height: 1;
    color: #fff;
    text-align: left;
    font-weight: bold;
}
.section_three p{
    font-size: 1rem;
    width: 100%;
    line-height: 1.4;
    color: #fff;
    margin: 1rem 0 1rem 0;
    padding: 0;
    text-align: left;
}
.section_three_btn{
    padding: 15px 50px;
    border-radius: 21px;
    cursor: pointer;
    background-color: #8D8DDA;
    color: #fff;
    border: none;
}
.section_three_btn:hover{
    background-color: #fff;
    color: #2d2879;
}
.section_four{
    display: flex;
    justify-content: space-between;
    align-items: center;
    gap: 9rem;
    width: 70%;
    margin: 0 auto;
    padding: 2rem 0;
}
.section_four img{
    width: 100%;
    height: auto;
}
.section_four_text{
    width: 100%;
    text-align: left;

}
.section_four h2{
    font-size: 1rem;
    color: #ABD9D9;
    margin: 0 0 .5rem 0;
    padding: 0;
    text-align: left;
}
.section_four_span{
    font-size: 2.3rem;
    line-height: 1;
    color: #fff;
    text-align: left;
    font-weight: bold;
}
.section_four p{
    font-size: 1rem;
    width: 100%;
    line-height: 1.4;
    color: #fff;
    margin: 1rem 0 1rem 0;
    padding: 0;
    text-align: left;
}
.section_five{
    width: 80%;
    margin: 0 auto;
    padding: 2rem 0;
}
.section_five h2{
    font-size: .7rem;
    color: #ABD9D9;
    margin: 0 0 .5rem 0;
    padding: 0;
}
/* section_five heading after Testimonials */
.head_span{
    font-size: 1.7rem;
    line-height: 1.2;
    color: #fff;
    font-weight: 500;
    width: 29%;
    margin: auto;
}
.sec_five_flexbox{
    display: flex;
    justify-content: space-between;
    align-items: center;
    gap: 2rem;
    width: 100%;
    margin: 2rem auto;
}   
.sec_five_flexboxes p{
    font-size: .9rem;
    width: 100%;
    line-height: 1.4;
    color: #fff;
    margin: 1rem 0 1rem 0;
    padding: 0;
    text-align: center;

}
.sec_five_flexboxes{
    width: 30%;
    text-align: center;
    background: linear-gradient(110deg, #151950 0%, #0f165a 65%, #1c245f 100%);
    color: #fff;
    padding: 1.3rem;
    border-radius: 15px;
}
.sec_five_flexbox img{
    width: 100%;
    max-width: 90px;
    height: auto;
    filter: sepia(35%) saturate(75%) contrast(90%);
    margin: 20px;
}
.section_six{
  width: 80%;
  max-width: 1100px;
  min-height: 270px;
  box-sizing: border-box;
  margin: 4rem auto;
  padding: 2rem;
  border-radius: 1.25rem;

  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  text-align: center;

  /* Purple on the left, light blue on the right, as in the Figma frame */
  background: linear-gradient(110deg, #625bd4 0%, #a8d3e8 100%);
}
.ready-label {
  margin: 0 0 1.2rem;
  color: #080923;
  font-size: 0.8rem;
  font-weight: 700;
  letter-spacing: 0.08em;
}
.section_six h2 {
  margin: 0 0 1.6rem;
  color: #fff;
  font-size: clamp(1.8rem, 4vw, 3rem);
  line-height: 1.05;
  font-weight: 700;
}
.get-started {
  min-width: 155px;
  padding: 0.85rem 1.5rem;
  border-radius: 999px;
  background: #050505;
  color: #fff;
  text-align: center;
  text-decoration: none;
  font-size: 0.75rem;
  font-weight: 600;
  letter-spacing: 0.08em;
}

.get-started:hover {
  background: #444444;
}
/* Tablets and smaller laptops */
@media (max-width: 900px) {
  .section_one {
    width: 88%;
    gap: 3rem;
  }

  .section_one h2 {
    font-size: clamp(2.5rem, 6vw, 4rem);
  }

  .section_three,
  .section_four {
    width: 82%;
    gap: 3rem;
  }

  .section_three_span,
  .section_four_span {
    font-size: clamp(1.8rem, 4vw, 2.3rem);
  }

  .section_five {
    width: 88%;
  }

  .head_span {
    width: 60%;
    text-align: center;
  }

  .sec_five_flexbox {
    gap: 1rem;
  }

  .sec_five_flexboxes {
    padding: 1rem;
  }
}

/* Phones */
@media (max-width: 650px) {
  .section_one,
  .section_three,
  .section_four {
    width: 88%;
    flex-direction: column;
    gap: 2rem;
    padding: 2rem 0;
  }

  .section_one_text,
  .section_one_img,
  .section_three_text,
  .section_four_text {
    width: 100%;
  }

  .section_one h2 {
    max-width: 100%;
    font-size: clamp(2.4rem, 11vw, 3.5rem);
  }

  .section_one p {
    max-width: 100%;
    font-size: 1rem;
  }

  .section_one_img img,
  .section_three img,
  .section_four img {
    display: block;
    width: 100%;
    height: auto;
  }

  .section_one_buttons {
    flex-wrap: wrap;
  }

  .section_one button,
  .section_three_btn {
    padding: 12px 24px;
  }

  .section_two {
    width: 88%;
  }

  .section_two_imgs {
    flex-wrap: wrap;
    justify-content: center;
    gap: 1.25rem;
    padding: 1rem;
  }

  .section_two_imgs img {
    width: min(35%, 100px);
  }

  .section_three_span,
  .section_four_span {
    font-size: clamp(1.8rem, 8vw, 2.3rem);
  }

  .section_five {
    width: 88%;
  }

  .head_span {
    width: 100%;
    font-size: 1.5rem;
    text-align: left;
  }

  .sec_five_flexbox {
    flex-direction: column;
    align-items: stretch;
    gap: 1rem;
  }

  .sec_five_flexboxes {
    width: auto;
  }

  .section_six {
    width: 88%;
    min-height: 230px;
    margin: 2rem auto;
    padding: 1.5rem;
  }
}
</style>