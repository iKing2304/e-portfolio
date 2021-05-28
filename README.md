<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSIT e-Portfolio</title>
    <link rel="stylesheet" href="Style.css">
    <link rel = "icon" href = "logo.png" type = "image/x-icon"> 

</head>

<body>  
    <!--Slideshow-->
    <div class="slider">
        <div class="slides">
            <input type="radio" name="radio-btn" id="radio1">
            <input type="radio" name="radio-btn" id="radio2">
            <input type="radio" name="radio-btn" id="radio3">

            <div class="slide first">
                <img src="!aHomepage/1.png" alt="">
            </div>

            <div class="slide">
                <img src="!aHomepage/CSITpage2.png" alt="">
            </div>

            <div class="slide">
                <img src="!aHomepage/CSITpage3.png" alt="">
            </div>

            <div class="navigation-auto">
                <div class="auto-btn1"></div>
                <div class="auto-btn2"></div>
                <div class="auto-btn3"></div>
            </div>
        </div>
        <div class="navigation-manual">
            <label for="radio1" class="manual-btn"></label>
            <label for="radio2" class="manual-btn"></label>
            <label for="radio3" class="manual-btn"></label>
        </div>

    </div>
   
    <script type="text/javascript">
        var counter = 1;
        setInterval(function() {
          document.getElementById('radio' + counter).checked = true;
          counter++;
          if(counter > 3) {
            counter = 1;
                         }
                            }, 5000);
    </script>

    <!--Navigation-->
    <ul>
        <nav class="nav">
          <a href="Homepage.html" class="leftfloat"><img  class="icon-size" src="logo.png"></a>
          <a href="AboutUs.html" class="rightfloat pad hover">The Team</a>
          <a href="Journal.html" class="rightfloat pad hover">Journal</a>
          <a href="Lessons2.html" class="rightfloat hover pad ">Second Sem</a>
          <a href="Lessons.html" class="rightfloat pad hover">First Sem</a>
          <a href="Homepage.html" class="rightfloat pad hover active"> Home </a>
        </nav>
          
    </ul>

    
        
        <div class="gridCSIT">
            <div>
                <img class="CSimg" src="!aHomepage/CompScie1.png" alt="Comp Scie">
            </div>
    
            <div class="compscie ">
                <h4 class="title">Computer Science</h4>
                <h5 class="description"> The Bachelor of Science in Computer Science program includes the study of computing concepts and theories,
                    algorithmic foundations and new developments in computing. The program prepares students to design and create algorithmically complex
                    software and develop new and effective algorithms for solving computing problems.<br><br>

                    The program also includes the study of the standards and practices in Software Engineering. It prepares students
                    to acquire skills and disciplines required for designing, writing and modifying software components, modules and
                    applications that comprise software solutions.<br></h5>
             </div>
        </div>


        <div class="gridIT">

            <div class="it">
                <h4 class="title">Information Technology</h4>
                <h5 class="description"> The Bachelor of Science in Information Technology program includes the study of the
                                        utilization of both hardware and software technologies involving planning, installing,
                                        customizing, operating, managing and administering and maintaining information technology
                                        infrastructure that provides computing solutions to address the needs of an organization. <br> <br>

                                        The program prepares graduates to address various user needs involving the selection,
                                        development, application, integration and management of computing technologies within an organization.
                    </h5>
            </div>

            <div>
                <img class="ITimg" src="!aHomepage/IT1.png" alt="IT">
            </div>

        </div>
    
       <div class="goals">
            <h4 class="title">Program Goals</h4>
                <h5 class="description"> The Bachelor of Science in Information Technology program includes the study of the
                                        utilization of both hardware and software technologies involving planning, installing,
                                        customizing, operating, managing and administering and maintaining information technology
                                        infrastructure that provides computing solutions to address the needs of an organization. <br> <br>

                                        The program prepares graduates to address various user needs involving the selection,
                                        development, application, integration and management of computing technologies within an organization.
                    </h5>
        </div>




    <footer>

        <div class="gridfooter">
            <h1 class="references"> References: <br> Commission on Higher Education (CHED) Memorandum Order No. 25, Series of 2015 
            </h1>

            <h1 class="foot"><br>Copyright &copy; 2020. St. Paul University Manila.
                <br>All rights reserved.
            </h1>
        </div>
        
    </footer>

    
</body>
</html>

<!--Earl David Ong & Don Lean Sanchez-->
