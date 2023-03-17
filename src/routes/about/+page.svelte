<style>
    /* main{
        text-align: center;
    } */

    h1{
        text-align: center;
    }

    /* h2{
        display: flex;
        flex-direction: column;
        justify-content: left;
        text-align: left;
        margin-left: 15px;
        width: 50%;
    } */

    /* .PresidentParagraph{
        display: flex;
        flex-direction: column;
        justify-content: left;
        text-align: left;
        margin-left: 15px;
        width: 50%;
    } */

    .members{
        display: flex;
        flex-direction: column;
        justify-content: left;
        text-align: left;
        margin-left: 45px;
        width: 50%;
    }

    .photoOfMembers{
        text-align: center;
    }

    /* .director{
        display: flex;
        flex-direction: column;
        justify-content: left;
        text-align: left;
        margin-left: 15px;
        width: 50%;
    }

    .director1{
    float:left;
    width:50%
    /* display: grid;
    align-items: center; 
    grid-template-columns: 1fr 1fr 1fr;
    column-gap: 5px; */
    /* } */

    /* .directorbox{
    display: flex;
    align-items: center;
    justify-content: center
    }

    .director1Para{
    border-radius:4px;
    }

    .director2Para{
    border-radius:4px;
    } */

    /* .directorbox2{
    display: flex;
    align-items: center;
    justify-content: right;
    float:right;
    width:50%
    } */

    /* .blank-profile-img.webp{
    width: 20px; 
    float: right; 
    margin-right: 10px; 
    } */

    /* .personimg{
        max-width: 100%
    } */

    /* .directorimg{
        flex-basis: 100%
    } */

    /* .director1info{
        font-size: 20px;
        text-align: left; */
    /* }  */

#wrapper ul {
   padding: 0;
   margin: auto;
   width: 100%;
   list-style-type: none;
 }

 #wrapper ul li {
   padding: 30px;
   margin-bottom: 20px;
   display: flex;
   width: 50%;
 }

 #wrapper ul li img {
   float: left;
 }

 #wrapper ul li .details {

   padding: 70px 0 0 20px;
   width: 75%;
   display: flex;
   flex-direction: column;
 }

 #p1 {
   font-weight: bold;
   margin-bottom: 5px;
 }

#p2{
    /* padding: 70px 0 0 20px; */
    width: 75%;
    display: flex;
    flex-direction: column;
}

 .column {
   float: left;
   flex-basis: 50%;
   flex-shrink:1;
 }

.column2{
    float: right;
    flex-basis: 50%;
    flex-shrink:1;
}

 #directors{
    display: flex;
    flex-direction: column;
    justify-content: left;
    text-align: left;
    /* margin-left: 15px; */
    width: 50%;
 }
</style>

<main class="main">
    <div class="aboutTitle">
        <h1>About the Team</h1>
    </div>
    <div class="members">
        <h2>Members</h2>
    </div>
    <div class="photoOfMembers">
        <img src="logo.png" height="150px" width="auto" alt="quant logo" >
    </div>

    <!-- <div class="directorbox1">
        <div class="director1">
            
        </div>
    </div> -->

    <div class="row">
        <div class="column">
          <div Id="wrapper">
            <section>
              <ul>
                <li>
                  <div class="details">
                    <h1 id="directors">Directors</h1>
                    <p id="p1">Daniel Archerson</p>
                    <p id="p2">Hello! I am Daniel and this is just some random text to test out what I am trying to create bodybodybodybodybodybodybodybodybodybodybodybodybodybody
                        bodybodybodybodybodybodybodybodybodybodybodybodybodybody
                        bodybodybodybodybodybodybodybodybodybodybodybodybodybody
                    </p>
                  </div>
                  <img src="logo.png" alt="" width=200px id="pic">
                </li>
              </ul>
            </section>
          </div>
        </div>
        <div class="column2">
            <div Id="wrapper">
              <section>
                <ul>
                  <li>
                    <img src="logo.png" alt="" width=200px id="pic">
                    <div class="details">
                      <p id="p1">John Doe</p>
                      <p id="p2"><a href="www.google.pl">More information</a></p>
                    </div>
                  </li>
                </ul>
              </section>
            </div>
          </div>
    </div>
        
        


















    <!-- Director -->
    <!-- <div class="director">
        <div class="directorbox">
            <div class="director1info" style="float: left">
                <h2>Director</h2>
                <p><strong>Daniel Archerson</strong></p>
            </div>
            <div class="directorimg">
                <img scr="logo.png" height="50px" width="100" alt="personimg">
            </div>
            <p class="director1Para">Hello! I am Daniel and this is just some random text to test out what I am trying to create bodybodybodybodybodybodybodybodybodybodybodybodybodybody
                bodybodybodybodybodybodybodybodybodybodybodybodybodybody
                bodybodybodybodybodybodybodybodybodybodybodybodybodybody
            </p> -->
            <!-- <h2>Director</h2>
            <div class="directorName"><strong>Daniel Archerson</strong></div> -->
            <!-- <p class="director1Para">Hello! I am Daniel and this is just some random text to test out what I am trying to create bodybodybodybodybodybodybodybodybodybodybodybodybodybody
                bodybodybodybodybodybodybodybodybodybodybodybodybodybody
                bodybodybodybodybodybodybodybodybodybodybodybodybodybody
            </p> -->
        <!-- </div>
        <div class="directorbox2">
            <div class="director2info" style="float: right">
                <h2>Director</h2>
                <p><strong>Daniel Archerson</strong></p>
            </div>
        </div> -->
        <!-- <div class="director2" style="float: right">
            <h2>Director</h2>
            <div class="directorName"><strong>Daniel Archerson</strong></div>
            <p class="director2Para">Hello! I am Daniel and this is just some random text to test out what I am trying to create bodybodybodybodybodybodybodybodybodybodybodybodybodybody
                bodybodybodybodybodybodybodybodybodybodybodybodybodybody
                bodybodybodybodybodybodybodybodybodybodybodybodybodybody
            </p>
        </div> -->

    <!-- </div>

    <div id="projectmanagers">

    </div> -->
    <!-- <h2>Project Managers</h2>
    <div id="gallery-text">
        <div id="gallery-text-left" style="float:left">
        <p id="gallery-text-quote-left"><b>I am not interested in shooting new things, I am interested to see things new.</b></p>
        </div>
        <div id="gallery-text-right" style="float: right">
        <p id="gallery-text-quote-right"><b>External photo albums</b></p>
        <p id="gallery-paragraph-2">
        </p>
        </div> -->
</main>