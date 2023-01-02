<html>
    <head>
        <title>Login-Darksouls</title>
        <link rel="icon" type="image/jpg" href="image/favicon.jpg">
        <style>
            body{
                background-image:url("dark soul.jpg");
                background-repeat: no-repeat;
                background-size: cover;
            }
            h1{
                color:rgb(255, 149, 0);
                font-family:Arial, Helvetica, sans-serif;
                border-bottom-style:double;
                border-top-width:1px;
                border-bottom-width: 4px;
                border-right-width: 4px;
                border-right:2px solid rgb(244, 163, 17);
                border-left:3px solid rgb(244, 47, 17);
                border-top:0px solid orangered;
                border-color:rgba(232, 40, 22, 0.984);
                border-radius: 10px;
                margin-top:25px;
                margin-bottom:100px;
                margin-right:50px;
                margin-left:50px;
                line-height:60px;
                word-spacing:50px;
                letter-spacing: 15px;
                text-indent:0px;
                text-shadow:2px 2px 5px rgba(12, 12, 12, 0.818), 0 0 25px rgba(255, 136, 0, 0.977),0 0 50px rgb(43, 6, 251);
                cursor:none;
            }  
            #box{
                display:flex;
            }
            #column1{
                height:460px;
                width:200px;
                display:flex;
                background-color: rgba(249, 6, 6, 0);
                margin-right:1px;
                margin-left:6cm;
                padding-left: 15px;
            }
            #column2{
                background-color:rgba(137, 43, 226, 0);
                height:450px;
                width:250px;
                margin-right:1px;
                margin-left:5px;
                padding-left:-500px;
            }
            #description{
                background-color:rgba(220, 20, 60, 0);
                height:300px;
                width:450px;
                margin-top:5ch;
                margin-right:5px;
                margin-left:160px;
                margin-top: -100px;
                display: flex;
                flex-direction: row;
            }
            #signin{
                margin-top: 300px;
                margin-left:-600px;
                height: 250px;
                width:270px;
                background-color: rgba(255, 13, 0, 0.014);
            }
            #designation{
                margin-top: 471.5px;
                margin-left:425px;
                padding-left: 10px;
                padding-right:10px;
                height:60px;
                width:120px;
                color:brown;
                background-color: rgba(255, 13, 0, 0.014);
            }
            .f{
                padding-top: 3px;
                padding-bottom: 3px;
            }
            .l{
                padding-top: 3px;
                padding-bottom: 3px;
            }
            .ag{
                padding-top: 3px;
                padding-bottom: 3px;
            }
            .db{
                padding-top: 3px;
                padding-bottom: 3px;
            }
            .em{
                padding-top: 3px;
                padding-bottom: 5px;
            }
            .pas{
                padding-top: 1px;
                padding-bottom: 3px;
                margin-bottom: 25px;
            }
            .fn{
                margin-top: -4px;
                margin-bottom:12px;
                padding-top: 3px;
                padding-bottom: 3px;
                border-radius:25px;
                border-style:solid;
                border-color: orangered;
                border-right-width: 2px;
                border-left-width: 3px;
            }
            .ln{
                margin-top:8px;
                margin-bottom:5px;
                padding-top: 3px;
                padding-bottom: 3px;
                border-radius:25px;
                border-style:solid;
                border-color: orangered;
                border-right-width: 2px;
                border-left-width: 3px;
            }
            .age{
                margin-top:23px;
                margin-bottom:15px;
                padding-top: 5px;
                padding-bottom: 3px;
                border-radius:25px;
                border-style:solid;
                border-color: orangered;
                border-right-width: 2px;
                border-left-width: 3px;
            }
            .birth{
                margin-top:8px;
                margin-bottom:15px;
                padding-top: 3px;
                padding-bottom: 3px;
                padding-right:55px;
                border-radius:25px;
                border-style:solid;
                border-color: orangered;
                border-right-width: 2px;
                border-left-width: 3px;
            }
            .email{
                margin-top:12px;
                margin-bottom:15px;
                padding-top: 3px;
                padding-bottom: 3px;
                border-radius:25px;
                border-style:solid;
                border-color: orangered;
                border-right-width: 2px;
                border-left-width: 3px;
            }
            .pass{
                margin-top:14px;
                margin-bottom:20px;
                padding-top: 3px;
                padding-bottom: 3px;
                border-radius:25px;
                border-style:solid;
                border-color: orangered;
                border-right-width: 2px;
                border-left-width: 3px;
            }
            .sb{
              padding:12px 40px;
              margin-left:-25px;
              border-color:orangered;
              font-size: 2ch;
            }
            .cb{
                margin-top:48px;
                margin-bottom:25px;
                margin-left:10px;
                padding:12px 40px;
                border-color:orangered;
                font-size: 2ch;
            }
        </style>
        <style>
            .f,.l,.ag,.db,.em,.pas{
                border-style: none;
                padding:5px 10px 5px 10px;
                border-top-width: 5px;
                border-bottom-width: 5px;
                transition-duration: .2s;
            }
            .f:hover{
                color:rgb(250, 162, 9);
                text-shadow:2px 2px 5px rgb(255, 21, 0), 5px 5px 25px  rgb(255, 177, 9), 0px 5px 50px rgb(255, 0, 0);
                cursor:none;
                font-size: .5cm;
            }
            .l:hover{
                color:rgb(250, 162, 9);
                text-shadow:2px 2px 5px rgb(255, 21, 0), 5px 5px 25px  rgb(255, 177, 9), 0px 5px 50px rgb(255, 0, 0);
                cursor:none;
                font-size: .5cm;
            }
            .ag:hover{
                color:rgb(250, 162, 9);
                text-shadow:2px 2px 5px rgb(255, 21, 0), 5px 5px 25px  rgb(255, 177, 9), 0px 5px 50px rgb(255, 0, 0);
                cursor:none;
                font-size: .5cm;
            }
            .db:hover{
                color:rgb(250, 162, 9);
                text-shadow:2px 2px 5px rgb(255, 21, 0), 5px 5px 25px  rgb(255, 177, 9), 0px 5px 50px rgb(255, 0, 0);
                cursor:none;
                font-size: .5cm;
            }
            .em:hover{
                color:rgb(250, 162, 9);
                text-shadow:2px 2px 5px rgb(255, 21, 0), 5px 5px 25px  rgb(255, 177, 9), 0px 5px 50px rgb(255, 0, 0);
                cursor:none;
                font-size: .5cm;
            }
            .pas:hover{
                color:rgb(250, 162, 9);
                text-shadow:2px 2px 5px rgb(255, 21, 0), 5px 5px 25px  rgb(255, 177, 9), 0px 5px 50px rgb(255, 0, 0);
                cursor:none;
                font-size: .5cm;
            }
            .fn,.ln,.age,.birth,.email,.pass{
                transition-duration: .5s;
                animation:inputeffect 3s infinite;
                border-style: solid;
                background-color: rgba(0, 0, 0, 0.393);
                border-color:ghostwhite;
                color:gold;
            }
            .fn:hover{
                background-color: rgba(0, 255, 255, 0);
                cursor:text;
                color:darkorange;
                border-style:dashed;
                font-size: 2ch;
                border-color:antiquewhit e;
                animation:inputhover 3s infinite;
            }
            .ln:hover{
                background-color: rgba(0, 255, 255, 0);
                cursor:text;
                color:darkorange;
                border-style:dashed;
                font-size: 2ch;
                border-color:antiquewhite;
                animation:inputhover 3s infinite;
            }
            .age:hover{
                background-color: rgba(0, 255, 255, 0);
                cursor:text;
                color:darkorange;
                border-style:dashed;
                font-size: 2ch;
                border-color:antiquewhite;
                animation:inputhover 3s infinite;
            }
            .birth:hover{
                background-color: rgba(0, 255, 255, 0);
                cursor:text;
                color:darkorange;
                border-style:dashed;
                font-size: 2ch;
                border-color:antiquewhite;
                animation:inputhover 3s infinite;
            }
            .email:hover{
                background-color: rgba(0, 255, 255, 0);
                cursor:text;
                color:darkorange;
                border-style:dashed;
                font-size: 2ch;
                border-color:antiquewhite;
                animation:inputhover 3s infinite;
            }
            .pass:hover{
                background-color: rgba(0, 255, 255, 0);
                cursor:default;
                color:darkorange;
                border-style:dashed;
                font-size: 2ch;
                border-color:antiquewhite;
                animation:inputhover 2s infinite;
            }
            @keyframes inputhover{
                
                90%{border-top-color:rgba(253, 245, 230, 0.003);}
                20%{border-bottom-color:rgba(253, 245, 230, 0.003);}
                10%{border-right-color:rgba(253, 245, 230, 0.003);}
                47%{border-left-color:rgba(253, 245, 230, 0.003);}
                74%{border-right-color:rgba(253, 245, 230, 0.003);}

            }
            @keyframes inputeffect{
                10%{border-top-color:rgba(253, 245, 230, 0.003);}
                30%{border-right-color:rgba(253, 245, 230, 0.003);}
                50%{border-left-color:rgba(253, 245, 230, 0.003);}
                80%{border-bottom-color:rgba(253, 245, 230, 0.003);}
            }
            #button{
                transition-duration: 0.5s;
                color:rgb(255, 196, 0);
                background-color: rgba(9, 9, 9, 0);
                animation:button 3s infinite;
            }
            #button:hover{
                background-color: rgba(0, 0, 0, 0.43);
                color:rgb(238, 128, 19);
                cursor: pointer;
                text-shadow:2px 2px 5px rgb(255, 111, 0), 0px 0px 25px  rgb(10, 110, 241), 0px 0px 50px rgb(255, 0, 0);
                padding:14px 50px;
                border-color:goldenrod;
                border-style:"dashed";
                animation:buttonhover 2s infinite;
            }
            @keyframes button{
                10%{border-top-color:rgba(253, 245, 230, 0.003);}
                30%{border-right-color:rgba(253, 245, 230, 0.003);}
                50%{border-left-color:rgba(253, 245, 230, 0.003);}
                80%{border-bottom-color:rgba(253, 245, 230, 0.003);}
            }
            @keyframes buttonhover{
                75%{background-color: rgba(70, 69, 68, 0);}
                55%{background-color:rgba(16, 16, 16, 0.301)}
                50%{color: rgb(255, 196, 0);}     
                10%{border-top-color:rgba(253, 245, 230, 0.003);}
                30%{border-right-color:rgba(253, 245, 230, 0.003);}
                50%{border-left-color:rgba(253, 245, 230, 0.003);}
                80%{border-bottom-color:rgba(253, 245, 230, 0.003);}
            }
        </style>
        <style>
            .title{
                animation:intro 5s infinite;
            }
            @keyframes intro{
                25%{border-right-color:rgba(0, 0, 0, 0.012);}
                10%{border-top-color:rgba(253, 245, 230, 0.003);}
                30%{border-right-color:rgba(253, 245, 230, 0.003);}
                50%{border-left-color:rgba(253, 245, 230, 0.003);}
                80%{border-bottom-color:rgba(253, 245, 230, 0.003);}
                75%{color: rgba(255, 149, 0, 0);}
                50%{color: rgba(255, 149, 0, 0.325);}
                5%{color: rgba(255, 149, 0, 0.944);}
                25%{color: rgba(255, 149, 0, 0.97);}   
            }
            #icon{
                height:20px;
                width:20px;
            }
            #oricon{
                margin-top:5px;
                height:25px;
                width:25px;
            }
            #signbutton{
                font-size: 1.9ch;
                border-style: none;
                padding-top: 5px;
                padding-bottom: 5px;
            }
            .google{
                background-color: rgba(240, 248, 255, 0);
                transition-duration: .5s;
            }
            .google:hover{
                float: right;
                cursor: pointer;
                color:azure;
            }
            .fb{
                background-color: rgba(240, 248, 255, 0);
                transition-duration: .5s;
            }
            .fb:hover{
                float:right;
                cursor: pointer;
                color:azure;
            }
            .ios{
                background-color: rgba(240, 248, 255, 0);
                transition-duration: .5s;
            }
            .ios:hover{
                float: right;
                cursor: pointer;
                color:azure;
            }
            .microsoft{
                background-color: rgba(240, 248, 255, 0);
                transition-duration: .5s;
            }
            .microsoft:hover{
                float: right;
                cursor: pointer;
                color:azure;
            }
            .othersignin{
                margin-left:-100px;
                font-family:Courier New, Courier, monospace;
            }
            #sign{
                font-family:Courier New, Courier, monospace;
                margin-top: -38.5px;
                margin-left: 105px;  
            }
            .desigination{
                color:crimson;
                font-size:x-small;
                padding-top: -1000px;
            }
            .name{
                font-family:Courier New, Courier, monospace;
                font-size: small;
                animation: name .8s infinite;
            }
            .name:hover{
                color: rgb(234, 226, 226);
            }
            @keyframes name{
                50%{color:gray;}
            }
            #by{
                margin-top: -14px;
                margin-left: 15px;
            }
            #des{
                margin-bottom: -1.2px;
                margin-left:-40px;
            }
        </style>
    </head>
    <body>
        <h1 id="title" class="title"><center><marquee direction="right">Welcome to Darksouls</marquee></center></h1><br>
        <div id="box">
            <div id="column1" class="tag">
               <table style="color:goldenrod">
                <tr>
                    <td><p id="fname" class="f" style="margin-right:10px"> <i> First Name : </i></p></td>
                </tr>
                <tr>
                    <td><p id="lname" class="l"><i> Last Name : </i></p></td>
                </tr>
                <tr>
                    <td><p id="age" class="ag"><i> Age : </i></p></td>
                </tr>
                <tr>
                    <td><p id="dob" class="db"><i> Date of Birth : </i></p></td>
                </tr>
                <tr>
                    <td><p id="email" class="em"><i> Email : </i></p></td>
                </tr>
                <tr>
                    <td><p id="password" class="pas"><i> Password : </i></p></td><br>
                </tr>
                <tr>
                    <td><button id="button" class="sb">
                        <img src="ca.png"id=icon>
                        &nbsp;&nbsp;Submit</button></td>
                </tr>
               </table>
            </div>

            <div id="column2" class="tagans" >
                <table style="color:gold">
                <tr>
                    <td><input type="text" id="fname" class="fn" placeholder="   First Name"></td>
                </tr>
                <tr>
                    <td><input type="text" id="lname" class="ln" placeholder="   Last Name"></td>
                </tr>
                <tr>
                    <td><input type="number" id="age" class="age" placeholder="   Age  "></td>
                </tr>
                <tr>
                    <td><input type="date" id="dob" class="birth" ></td>
                </tr>
                <tr>
                    <td><input type="eamil" id="eamil" class="email" placeholder="   Email"></td>
                </tr>
                <tr>
                    <td><input type="password" id="password" class="pass"></td><br>
                </tr>
                <tr>
                    <td><button id="button" class="cb">
                        <img src="exit.png" id="icon">
                        &nbsp;&nbsp;   Canacel</button></td>
                </tr>
            </table>
            </div>
            <div id="description" class="description">
                <video id="video" class="dsv" width="400px" height="250px" autoplay muted loop>
                     <source src="dsv.mp4" >
                </video>
            </div>
            <div id="signin">
                <center><h4 class="othersignin" id="other" style="color:rgb(255, 253, 252)" >Other  ways t</h4> <h4 class="othersignin" id="sign" >o   Sign  In</h4></center>
                <table id="signtable" width="280px">
                    <tr>
                        <td><img src="google.png" id="oricon"> &nbsp;&nbsp;</td>
                        <td><input type="submit" id="signbutton" class="google" value="Sign in  with  Google Account"></td>
                    </tr>
                    <tr>
                        <td><img src="facebook.png" id="oricon"> &nbsp;&nbsp;</td>
                        <td><input type="submit" id="signbutton" class="fb" value="Sign in with Facebook Account"></td>
                    </tr>
                    <tr>
                        <td><img src="apple-logo.png" id="oricon"> &nbsp;&nbsp;</td>
                        <td><input type="submit" id="signbutton" class="ios" value="Sign in with Apple/ios Account"></td>
                    </tr>
                    <tr>
                        <td><img src="microsoft.png" id="oricon" > &nbsp;&nbsp;</td>
                        <td><input type="submit" id="signbutton" class="microsoft" value="Sign in with Microsoft Account"></td>
                    </tr>
                </table>
            </div>
            <div id="designation">
                <center><p id="des" class="desigination">Design</p><p class="desigination" id="by">by :</p></center>
                <marquee direction="right"><center><p class="name"><i>ROGUL.J</i></p></center></marquee>
            </div>
        </div>
    </body>
</html>
