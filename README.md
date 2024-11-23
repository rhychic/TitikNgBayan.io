<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FILIPINO</title>
    <style>
        .open {
            text-align: center;
            background-color: #600707;
            color: yellow;
        }
        .sidenav {
            height: 100%;
            width: 0;
            position: fixed;
            z-index: 1;
            top: 0;
            left: 0;
            background-color: #111;
            overflow-x: hidden;
            transition: 0.5s;
            padding-top: 60px;
        }
        .sidenav a {
            padding: 8px 8px 8px 32px;
            text-decoration: none;
            font-size: 25px;
            color: #818181;
            display: block;
            transition: 0.3s;
        }
        .sidenav a:hover {
            color: #f1f1f1;
        }
        .sidenav .closebtn {
            position: absolute;
            top: 0;
            right: 25px;
            font-size: 36px;
            margin-left: 50px;
        }
        @media screen and (max-height: 450px) {
            .sidenav {
                padding-top: 15px;
            }
            .sidenav a {
                font-size: 18px;
            }
        }
        .head {
            text-align: center;
        }
        body {
            font-family: Arial, sans-serif;
            padding: 20px;
            background-color: white;
        }
        .header {
            background-color: #600b0b;
            padding: 30px;
            text-align: center;
        }
        #navbar {
            position: sticky;
            top: 0;
            overflow: hidden;
            background-image: radial-gradient(farthest-corner at 60% 55%, #3A6D8C, #003161, #001F3F);
        }
        #navbar a {
            float: left;
            display: block;
            color: #f2f2f2;
            text-align: center;
            padding: 14px 16px;
            text-decoration: none;
            font-size: 17px;
        }
        #navbar a:hover {
            background-color: #ddd;
            color: black;
        }
        #navbar a.active {
            background-color: #04AA6D;
            color: white;
        }
        .content {
            padding: 16px;
        }
    </style>
</head>

<body>
    <div id="navbar">
        <div class="head">
            <img src="https://i.postimg.cc/Qt9SrZKj/TITIK-NG-BAYAN-removebg-preview-2.png" alt="Titik ng Bayan logo" width="200" height="100">
            <div id="mySidenav" class="sidenav">
                <a href="javascript:void(0)" class="closebtn" onclick="closeNav()">&times;</a>
                <a href="#">About</a> <br>
                <a href="#">Services</a> <br>
                <a href="#">Clients</a> <br>
                <a href="#">Contact</a> <br>
            </div>
            <div class="open">
                <span style="font-size:30px;cursor:pointer" onclick="openNav()">☀︎</span>
            </div>
            <script>
                function openNav() {
                    document.getElementById("mySidenav").style.width = "250px";
                }
                function closeNav() {
                    document.getElementById("mySidenav").style.width = "0";
                }
            </script>
        </div>
    </div>

    <div class="w3-content" style="max-width:1400px">
        <header class="w3-container w3-center w3-padding-32">
            <h1><b><center><font size="30" face="Times New Roman"><span style="color:gray;font-weight:bold">Epekto ng Droga:</span><br> Pagpapakita ng Realidad</font></center></b></h1>
            <p><center>Maligayang pagdating sa blog ng <span class="w3-tag">Pangatlong Pangkat</span></center></p>
        </header>

        <div class="w3-row">
            <div class="w3-col l8 s12">
                <div class="w3-card-4 w3-margin w3-white">
                    <img src="https://i.postimg.cc/XNBbZNbL/img9955.jpg" alt="drugs" style="width:100%">
                    <div class="w3-container">
                        <h3><b>EPEKTO NG DROGA: PAGPAPAKITA NG REALIDAD</b></h3>
                        <h5>A photo taken by blah blah blah, <span class="w3-opacity">November 22, 2024</span></h5>
                    </div>

                    <div class="w3-container">
                        <p>A blog about the effects of drugs and the reality they portray...</p>
                        <div class="w3-row">
                            <div class="w3-col m8 s12">
                                <p><button class="w3-button w3-padding-large w3-white w3-border"><b>READ MORE »</b></button></p>
                            </div>
                            <div class="w3-col m4 w3-hide-small">
                                <p><span class="w3-padding-large w3-right"><b>Comments  </b><span class="w3-tag">0</span></span></p>
                            </div>
                        </div>
                    </div>
                </div>
                <hr>

                <div class="w3-card w3-margin">
                    <div class="w3-container w3-padding">
                        <h4>Popular Posts</h4>
                    </div>
                    <ul class="w3-ul w3-hoverable w3-white">
                        <li class="w3-padding-16">
                            <img src="https://via.placeholder.com/50" alt="Image" class="w3-left w3-margin-right" style="width:50px">
                            <span class="w3-large">Teenage Pregnancy</span><br>
                            <span>Napapanahon</span>
                        </li>
                        <li class="w3-padding-16">
                            <img src="https://via.placeholder.com/50" alt="Image" class="w3-left w3-margin-right" style="width:50px">
                            <span class="w3-large">Kahirapan</span><br>
                            <span>sa bansa</span>
                        </li> 
                        <li class="w3-padding-16">
                            <img src="https://via.placeholder.com/50" alt="Image" class="w3-left w3-margin-right" style="width:50px">
                            <span class="w3-large">Edukasyon</span><br>
                            <span>ngayon</span>
                        </li>   
                        <li class="w3-padding-16 w3-hide-medium w3-hide-small">
                            <img src="https://via.placeholder.com/50" alt="Image" class="w3-left w3-margin-right" style="width:50px">
                            <span class="w3-large">Noon at</span><br>
                            <span>Ngayon</span>
                        </li>  
                    </ul>
                </div>
                <hr> 

                <div class="w3-card w3-margin">
                    <div class="w3-container w3-padding">
                        <h4>Tags</h4>
                    </div>
                    <div class="w3-container w3-white">
                        <p><span class="w3-tag w3-black w3-margin-bottom">#napapanahongisyu</span> <span class="w3-tag w3-light-grey w3-small w3-margin-bottom">#Drugs</span> <span class="w3-tag w3-light-grey w3-small w3-margin-bottom">#Filipino</span> 
                        <span class="w3-tag w3-light-grey w3-small w3-margin-bottom">#PangatlongPangkat</span> </p>
                    </div>
                </div>

            </div>
        </div><br>

    </div>

    <footer class="w3-container w3-dark-grey w3-padding-32 w3-margin-top">
        <button class="w3-button w3-black w3-disabled w3-padding-large w3-margin-bottom">Previous</button>
        <button class="w3-button w3-black w3-padding-large w3-margin-bottom">Next »</button>
        <p>Isinagawa ni Layante ksksks</p>
    </footer>
</body>
</html>