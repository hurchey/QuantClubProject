<style>
    h1{
        text-align: center;
    }

    .titlePositions{
        display: flex;
        flex-direction: column;
        justify-content: left;
        text-align: left;
        margin-left: 45px;
        width: 50%;
    }

    .p1{
        display: flex;
        flex-direction: column;
        justify-content: left;
        text-align: left;
        font-size: 20px;
        font-weight: bold;
        margin-bottom: 5px;
        margin-left: 45px;
        width: 50%;
    }

    .p2{
        flex-direction: column;
        justify-content: left;
        text-align: left;
        font-size: 17px;
        margin-bottom: 5px;
        margin-left: 45px;
        width: 50%;
    }

    .photoOfMembers{
        text-align: center;
    }

    /* .row{
        display: flex;
        flex-direction: row;
        justify-content: space-around;
        width: 50%;
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

/* #wrapper ul {
   padding: 2w0;
   margin: auto;
   width: 100%;
   list-style-type: none;
 } */

 /* #wrapper ul li {
   padding: 30px;
   margin-bottom: 20px;
   display: flex;
   width: 35%;
 } */

 /* #img { */
  /* text-align: end; */
   /* float: right; */
   /* margin-right: 0px; */
 /* } */

 /* #wrapper ul li .details {

   padding: 70px 0 0 20px;
   width: 75%;
   display: flex;
   flex-direction: column;
 } */

 #p1 {
   font-weight: bold;
   margin-bottom: 5px;
   margin-left: 45px;

 }

#p2{
    padding: 0 0 20px;
    width: 50%;
    display: flex;
    flex-direction: column;
    margin-left: 45px;
}

 /* .column {
  float: left;
  width: 50%;
 } */

 @media screen and (max-width: 600px) {
  .column {
    width: 50%;
  }
}

 .row::after{
  content: "";
  display: table;
  clear: both;
 }

.column2{
  width: 50%;
}

 /* #directors{
    display: flex;
    flex-direction: column;
    justify-content: left;
    text-align: left;
    /* margin-left: 15px; */
    /* width: 40%;
 } */ 

 #pic{
    margin-left: 25px;
 }

</style>



<main class="main">
  <div class="aboutTitle">
    <h1>About the Team</h1>
  </div>

  <div class="titlePositions">
    <h2>Members</h2>
  </div>

  <div class="photoOfMembers">
    <img src="logo.png" height="150px" width="auto" alt="quant logo" >
  </div>
  
  <div class="titlePositions">
    <h2>Directors</h2>
  </div>

  <div class="row">
    <div class="column">
      <p id="p1">Daniel Archerson
        <img src="logo.png" alt="" width=200px id="pic">
      </p>
      <p id="p2">Hello! I am Daniel and this is just some random text to test out what I am trying to create bodybodybodybodybodybodybodybodybodybodybodybodybodybody
        bodybodybodybodybodybodybodybodybodybodybodybodybodybody
        bodybodybodybodybodybodybodybodybodybodybodybodybodybody
      </p>
      <div class="column2">
        <p id="p1">Daniel Archerson
          <img src="logo.png" alt="" width=200px id="pic">
        </p>
        <p id="p2">Hello! I am Daniel and this is just some random text to test out what I am trying to create bodybodybodybodybodybodybodybodybodybodybodybodybodybody
          bodybodybodybodybodybodybodybodybodybodybodybodybodybody
          bodybodybodybodybodybodybodybodybodybodybodybodybodybody
        </p>
      </div>
    </div>

    <div class="column">

    </div>
  </div>
</main>









<!-- 
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

    <div class="directorbox1">
        <div class="director1">
            
        </div>
    </div> -->

    <!-- <div class="row">
        <div class="column">
          <div Id="wrapper">
            <section>
              <ul>
                <li>
                  <div class="details">
                    <h1 id="directors">Directors</h1>
                    <p id="p1">Daniel Archerson</p> -->
                    <!-- <p id="p2">Hello! I am Daniel and this is just some random text to test out what I am trying to create bodybodybodybodybodybodybodybodybodybodybodybodybodybody
                        bodybodybodybodybodybodybodybodybodybodybodybodybodybody
                        bodybodybodybodybodybodybodybodybodybodybodybodybodybody
                    </p> -->
                  <!-- </div>
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
                    <div class="details">
                      <p id="p1">Daniel Archerson</p> -->
                      <!-- <p id="p2">Hello! I am Daniel and this is just some random text to test out what I am trying to create bodybodybodybodybodybodybodybodybodybodybodybodybodybody
                        bodybodybodybodybodybodybodybodybodybodybodybodybodybody
                        bodybodybodybodybodybodybodybodybodybodybodybodybodybody
                      </p> -->
                    <!-- </div>
                    <img src="logo.png" alt="" width=200px id="pic">
                  </li>
                </ul>
              </section>
            </div>
          </div>
    </div> -->
         
        


















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
<!-- </main> -->