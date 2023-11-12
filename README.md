# Delvina
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Document</title>
   <link rel="stylesheet" href="Detyre.css">
    <style>
        .headeri{
            display: flex;
            align-content: center;
        }

        .catalog{
            padding-left: 10px;
            font-family:Verdana, Geneva, Tahoma, sans-serif;
            color:rgb(39, 132, 132);
        }

        ul{
            display: flex;
            justify-content: flex-end;
            align-items: baseline;
            font-family:Verdana, Geneva, Tahoma, sans-serif;
            color:rgb(39, 132, 132);
            list-style: none;
        }
        .butoni_bg img{
        background-color: rgb(39, 132, 132);
      }

      .latestvideo{
        display: flex;
        justify-content:space-between;
        color: rgb(39, 132, 132);
        margin-left: 30px;
        margin-right: 30px;
      }

      .fotografit{
        display: flex;
        flex-wrap: wrap;
        padding: 20px;
        column-gap: 20px;
        justify-content: center;
      }

      .rubrika{
        display: flex;
        width: 300px;
        height: 250px;
        flex-direction: column;
      }

        .bgfoto{
            display: flex;
            background-image: url(hero.jpg);
            background-size: 100% 100%;
            width: 100%;
            height: 280px;
            justify-content: center;
            align-items: center;
        }

        .butoni_bg img{
            color: rgb(39, 132, 132);
        }
    </style>
</head>
<body>
    <header>
        <div class="headeri">
            <img src="logo.png" height="45px" >
            <div class="catalog"> 
                <p>Catalog-Z</p>
            </div>
        </div>
        <ul>
            <li>Photos</li>
            <li>Videos</li>
            <li>About</li>
            <li>Contact</li>
        </ul>
    </header>
    <main>
        <div class="bgfoto">
            <input type="text" placeholder="Search" style="height: 20px;">
            <button class="butoni_bg"><img src="search.png" alt=""></button>
        </div>
        <div class="latestvideo">
            <h3>Latest Videos</h3>
            <p>Page <button value="1">1</button> of 180</p>
        </div>
        <div class="fotografit">
            <div class="rubrika">
                <img src="img-01.jpg" alt="" class="img">
                <div class="views_date">
                    <p>24 Oct 2020</p>
                    <p>10,460 Views</p>
                </div>
            </div>
            <div class="rubrika">
                <img src="img-02.jpg" alt="" class="img">
                <div class="views_date">
                    <p>22 Oct 2020</p>
                    <p>14,502 Views</p>
                </div>
            </div>
            <div class="rubrika">
                <img src="img-03.jpg" alt="" class="img">
                <div class="views_date">
                    <p>18 Oct 2020</p>
                    <p>11,906 Views</p>
                </div>
            </div>
            <div class="rubrika">
                <img src="img-04.jpg" alt="" class="img">
                <div class="views_date">
                    <p>12 Oct 2020</p>
                    <p>16,100 Views</p>
                </div>
            </div>
            <div class="rubrika">
                <img src="img-05.jpg" alt="" class="img">
                <div class="views_date">
                    <p>24 Sep 2020</p>
                    <p>16,008 Views</p>
                </div>
            </div>
            <div class="rubrika">
                <img src="img-06.jpg" alt="" class="img">
                <div class="views_date">
                    <p>21 Sep 2020</p>
                    <p>12,860 Views</p>
                </div>
            </div>
            <div class="rubrika">
                <img src="img-07.jpg" alt="" class="img">
                <div class="views_date">
                    <p>18 Sep 2020</p>
                    <p>10,900 Views</p>
                </div>
            </div>
            <div class="rubrika">
                <img src="img-08.jpg" alt="" class="img">
                <div class="views_date">
                    <p>14 Sep 2020</p>
                    <p>10,820 Views</p>
                </div>
            </div>
            <div class="rubrika">
                <img src="img-09.jpg" alt="" class="img">
                <div class="views_date">
                    <p>12 Sep 2020</p>
                    <p>42,700 Views</p>
                </div>
            </div>
            <div class="rubrika">
                <img src="img-10.jpg" alt="" class="img">
                <div class="views_date">
                    <p>9 Sep 2020</p>
                    <p>11,420 Views</p>
                </div>
            </div>
            <div class="rubrika">
                <img src="img-11.jpg" alt="" class="img">
                <div class="views_date">
                    <p>8 Sep 2020</p>
                    <p>32,906 Views</p>
                </div>
            </div>
            <div class="rubrika">
                <img src="img-12.jpg" alt="" class="img">
                <div class="views_date">
                    <p>6 Sep 2020</p>
                    <p>50,700 Views</p>
                </div>
            </div>
            <div class="rubrika">
                <img src="img-13.jpg" alt="" class="img">
                <div class="views_date">
                    <p>28 Aug 2020</p>
                    <p>107,510 Views</p>
                </div>
            </div>
            <div class="rubrika">
                <img src="img-14.jpg" alt="" class="img">
                <div class="views_date">
                    <p>24 Aug 2020</p>
                    <p>118,006 Views</p>
                </div>
            </div>
            <div class="rubrika">
                <img src="img-15.jpg" alt="" class="img">
                <div class="views_date">
                    <p>20 Aug 2020</p>
                    <p>121,300 Views</p>
                </div>
            </div>
            <div class="rubrika">
                <img src="img-16.jpg" alt="" class="img">
                <div class="views_date">
                    <p>14 Aug 2020</p>
                    <p>21,204 Views</p>
                </div>
            </div>
        </div>
        <div class="permifooter">
            <div class="previous">
                <button class="btn_prev_next" style="background-color: rgb(34, 255, 244);">Previous</button>
            </div>
            <div class="numrat">
                <button class="btn" style="background-color: lightseagreen;">1</button>
                <button class="btn">2</button>
                <button class="btn">3</button>
                <button class="btn">4</button>
            </div>
            <div class="NextPage">
                <button class="btn_prev_next" style="background-color: lightseagreen;">Next Page</button>
            </div>
        </div>
    </main>
    <footer>
        <div class="f">
            <h2>About Catalog-Z</h2>
            <h2>Our Links</h2>
            <div class="ff">
                <a href=""><img src="facebook.png" alt=""></a>
                <a href=""><img src="twitter.png" alt=""></a>
                <a href=""><img src="instagram.png" alt=""></a>
                <a href=""><img src="pinterest.png" alt=""></a>
            </div>
        </div>
        <div class="footermain">
            <div class="footerleft">
                <p>Catalog-Z is free Bootstrap 5 Alpha 2 HTML Template for video and foto websites. You can freely use this TemplateMo layout for a front-end integration with any kind of CMS website.</p>
            </div>
            <div class="footercenter">
                <p>Advertise</p>
                <p>Support</p>
                <p>Our Company</p>
                <p>Contact</p>
            </div>
            <div class="footerright">
                <p>Terms of use</p>
                <p>Privacy Policy</p>
            </div>
        </div>
        <div class="fundi">
            <p>Copyright 2020 Catalog-Z Company. All rights reserved.</p>
            <p>Designed by TemplateMo</p>
        </div>
    </footer>
</body>
</html>
