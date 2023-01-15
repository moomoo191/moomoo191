<!DOCTYPE html>
<html lang="cn">

<head>

    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <meta name="description" content="">
    <meta name="author" content="">

    <title>生前预嘱</title>

    <!-- Bootstrap core CSS -->
    <link href="vendor/bootstrap/css/bootstrap.min.css" rel="stylesheet">
    <style>
        .icon-bar{
            width: 100%;
            background-color: #ddd;
            overflow: auto;
        }
        a{
            width: 100%;
            text-align: center;
            color: white;
            font-size: 16px;

        }
        a:hover{
            background-color: #ccc;
        }
        .active{
            background-color: thistle !important;
        }
        .nav-item{
          width: 80px;
        }
        .a{
          color:red;
          width:8px;
          height: 8px;
          margin: 10px;
          padding: 10px;
          text-align: center;
          font-size: 12px;
          font-weight: blod;
          font-family: 'Courier New', Courier, monospace;
          /* flex布局 */
          display: flex;
          /* 水平局中 */
          justify-content: center;
          /* 垂直局中 */
          align-items: center;
          /* 将标签显示为块级 */
          display: block;
          /* 将标签显示为行内 */
          display: inline;
          /* 将标签浮动 */
          float: left;

        }
        .choiceList{
          display: flex;
          flex-wrap: wrap;
          justify-content: center;
        }
        .imgPosition{
            position: relative;
            height: 380px;
            background-color: #212529 !important;
            
        }
        .imgPosition .gifImg{
            position: absolute;
            right:3cm!important;
           top:27em!important;
        }
        .imgPosition .Img1{
            position: absolute;
            width: 100%;
            height: 100%;
            left:13em!important;
            top:25em!important;
        }
        .imgPosition .Img2{
            position: absolute;
            right:11em!important;
           top:10em!important;
        }
        .imgPosition span,.imgPosition p{
            color: #fff!important;
        }
        .imgPosition1 .Img1{

            width: 100%;
            height: 100%;

        }
        .imgPosition1 .gifImg{
            margin-top: 30px;
            width: 100%;
            height: 130%;

        }
        .echarts{
            margin-left: 6em;
          
            /* width: 100%; */
            /* height: 600px; */
        }
        #services a,#services p{
            color: #fff!important;
        }
        #question{
            font-size: 20px !important;
            
        }
        #textShow{
            font-size: 30px !important;
            font-weight: bold!important;
            
        }
        .renshu{
            position: relative;
            height: 560px;
            
        }
        .renshu .img2{
            position: absolute;
            left:7em;
            top:10em;
        }
        .renshu .img1{
            position: absolute;
            right:7em!important;
            top:13em!important
        }
        .renshu .biaoti{
            position: absolute;
            left:3em;
            top:3em;
        }
        .fagui{
            position: relative;
            height: 200px;
            
        }
    
        .yuanwang{
            position: relative;
            height: 900px;
            
        }
        .yuanwang .gifImg{
            position: absolute;
            right:2cm!important;
           top:22em!important;
        }
        .yuanwang .Img1{
            position: absolute;
            left:25em!important;
            top:2em!important;
        }
        .renzhixianzhuang p{
            text-align: left;
        }
    </style>
    <!-- Custom fonts for this template -->
    <link href="font-awesome-4.7.0/css/font-awesome.css" rel="stylesheet" type="text/css">

    <link href='https://fonts.googleapis.com/css?family=Open+Sans:300italic,400italic,600italic,700italic,800italic,400,300,600,700,800' rel='stylesheet' type='text/css'>
    <link href='https://fonts.googleapis.com/css?family=Merriweather:400,300,300italic,400italic,700,700italic,900,900italic' rel='stylesheet' type='text/css'>

    <!-- Plugin CSS -->
    <link href="vendor/magnific-popup/magnific-popup.css" rel="stylesheet">

    <!-- Custom styles for this template -->
    <link href="css/creative.css" rel="stylesheet">
    <link rel="stylesheet" href="css/Quiz.css">
<meta http-equiv="Content-Type" content="text/html; charset=utf-8">
<style type="text/css">
body,td,th {
	font-family: Merriweather, "Helvetica Neue", Arial, sans-serif;
}
body {
	background-color: #FFF;
}
</style>
</head>

<body id="page-top">

    <!-- Navigation -->
   <nav class="navbar navbar-expand-lg navbar-light fixed-top" id="mainNav">
        <div class="container">
            <a class="navbar-brand js-scroll-trigger" href="#page-top" ><p align="left" style="font-size: 26px;">生前预嘱:57201份数据背后的故事</p> </a>
            <button class="navbar-toggler navbar-toggler-right" type="button" data-toggle="collapse" data-target="#navbarResponsive" aria-controls="navbarResponsive" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
            <div class="collapse navbar-collapse" id="navbarResponsive">
                <ul class="navbar-nav ">
                    <li id="text" class="nav-item">
                        <a class="nav-link js-scroll-trigger" href="#daoyu" style="font-size: 20px;"><b>导语 </b></a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link js-scroll-trigger" href="#services" style="font-size: 20px;">简述</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link js-scroll-trigger" href="#renzhixianzhuang" style="font-size: 20px;">认知</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link js-scroll-trigger" href="#fagui" style="font-size: 20px;">法规</a>
                    <li class="nav-item">
                        <a class="nav-link js-scroll-trigger" href="#contact" style="font-size: 20px;">争议</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <header class="masthead text-center text-white d-flex">
       <p><p> <div class="container my-auto" id="shouye">
            <div class="row">
                <div class="col-lg-10 mx-auto">
                    <p class="text-uppercase" style="margin-top: 100px;">
                        <span style="font-size: 72px;font-family:'Microsoft YaHei UI';font-weight:900;"><strong >生前预嘱</strong></span>
                    </p>
                </div>
                <div class="col-lg-8 mx-auto">
                    <p class="text-faded mb-5"><span style="font-size:40px;font-weight:bold;font-family:'华文行楷'">————</span> <span style="font-size:40px;font-weight:bold;font-family:'字魂193号-文宋复古体'">57201份数据背后的故事</span></p>
                    <a class="btn btn-light btn-xl js-scroll-trigger" style="width: 25%;background: #526377;color: #fff;" href="#test">点击查看</a>
                </div></p></p>
            </div>
        </div>
    </header>
<section class="" style="background-color: #526377 !important;" id="test">      
        <div class="container">
            <div class="row">
                <div class="col-lg-8 mx-auto text-center">
                    <h2 class="section-heading "><span style="color:#fff;font-family:'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;font-weight: bold;">在正式进入之前，让我们先来做个小测试吧！</h2></span>
                    
                    
                    <form name="form1" method="post" action="">
                  </form>
                  <div class="grid">
                    
                    <div id="question"></div>
                  
                    <div id="choices" class="choiceList" class="quizMessage" class="answer">
                      <button class="btn single-choice" id="choice0"></button>
                      <button class="btn single-choice" id="choice1"></button>
                      <button class="btn single-choice" id="choice2"></button>
                      <button class="btn single-choice" id="choice3"></button>
                    </div>
                    <br>
                    <div id="textShow" style="padding-bottom: 50px;display: none;"></div>
                    <button class="nextBtn" id="button">Next Question</button>
                
                    
                    <!-- <footer>
                    </footer> -->
                  </div>
                </div>
            </div>
        </div>
    </section>
    
    <section class=" imgPosition" id="jieshao">
        <div class="container" >
            <div class="row">
              <div class="col-lg-12" >
                <h2 class="section-heading"><p align="center"><span style="color: #FFF;font-weight:bold">导语</span></p></h2>
                <div class="col-lg-10 mx-auto text-center">
                    <p class="text-faded mb-4"; style="line-height: 32px; font-size:19px">通过上面的小测试，你是不是也发现自己有一些潜在的生前预嘱愿望呢？
                        <br>其实也有很多人和你一样，希望能有一个平静而有尊严的临终。
                        <br>到2022年9月为止，我国已经有<strong><span style="color: #FFFFFF; font-size: 24px">超过50000人</span></strong>填写了生前预嘱，
                        <br>让我们来看看填写的人群画像和他们的愿望吧!</p>
                
                </div><p align="center"><a class="btn btn-light btn-xl js-scroll-trigger" style="width: 20%;background: #526377;color: #fff;margin: 0;" href="#daoyu">点击继续</a></p>
                </div>
                 
                </div>
            </div>
        </div>
        
</section>
    <section class="bg-primary imgPosition1"id="daoyu" style="padding: 2.5rem 0;" >
        <div class="container">
            <div class="row">
                   <img src="img/资源 3.png" class="Img1" >
                  
                </div>
                <p class="text-faded mb-4"; style="line-height: 32px; font-size:18px;color: #FFF;">这57201份生前预嘱大致包含了<span style=" font-size:26px;font-weight: bold;color: #B28DAF">5种愿望</span>，分别是“我要或不要什么医疗服务”、“我希望使用或不适用生命支持治疗”、“我希望别人怎样对待我”、“我想让我的家人和朋友知道什么”、“我希望谁帮助我”，根据北京生前预嘱推广协会给出的数据，可以看到每种愿望的强烈程度有所不同，每份生前预嘱背后的选择各有差异。
   
                    <img src="img/yuanwang2.png" class="gifImg" >
            </div>
        
</section>

    <section id="services" style="background:#212529 !important;color: #fff;padding: 2.5rem 0;">
        <div class="container">
            <div class="row">
              <div class="col-lg-12">
                <h2 class="section-heading"><p align="center"><b>简述</b></p></h2>
                 <p >&nbsp;</p>
                 <p align="left"><span style="line-height: 32px; font-size:19px;"><b>“生前预嘱”是什么</span></b>？</p>
                   <p ><span style="line-height: 32px; font-size:19px;">生前预嘱（Advanced Directives，ADs) 也被称为预立 / 先指示、预立医疗指示，是指个人在具有表意能力和决定能力时，事先对失去表意能力时想要进行的医疗救治和手段的一种指示，这种决定受法律保护。患者的临终期医疗救治方案常由医务人员及家属决定，而 ADs 是在患者对疾病及治疗充分知情同意基础上，事先进行自主选择，是临终期制定救治方案的依据。</span></p> 
                </div>
            </div>
        </div>


        <div class="container " >
            <div class="row">
              <div class="col-lg-4 col-md-6 text-center">
              <div class="service-box mt-5 mx-auto">
                  <a href="time line.html">
                      <i class="fa fa-line-chart fa-5x mb-7 sr-icon-1" aria-hidden="true" ></i>
                      <a href="time line.html"><h3 class="mb-3">When</h3>
                        <p class="text-muted mb-0"><span style="line-height: 32px; font-size:19px;">发展时序与历程</span></p></a><p>&nbsp;</p>
                <p class="text-muted mb-0">&nbsp;</p>
                    </div>
                </div>
                 <div class="col-lg-4 col-md-6 text-center">
                    <div class="service-box mt-5 mx-auto">
                        <a href="为什么要推广.html">
                            <i class="fa fa-5x fa-question-circle" aria-hidden="true" ></i>
                        <h3 class="mb-3">Why</h3>
                        <p class="text-muted mb-0">为什么要推广</p></a>
                    </div>
                </div>
                <div class="col-lg-4 col-md-6 text-center">
                    <div class="service-box mt-5 mx-auto"><a href="采访.html">
                        <i class="fa fa-5x fa-user" aria-hidden="true" ></i>
                        <h3 class="mb-3">How</h3>
                        <p class="text-muted mb-0">听听TA说</p><p>&nbsp;&nbsp;&nbsp;</p></a>
                      <p class="text-muted mb-0">&nbsp;</p>
                    </div>
                </div>
               
            </div>
        </div>
    </section>
    <section class="text-white renzhixianzhuang"id="renzhixianzhuang" style="background:#526377 !important ;text-align: center;">
        <div class="container">
            <div class="row">
              <div class="col-lg-12">
                <h2 class="section-heading"><p align="center" style="text-align: center;"><b>国内外认知现状</b></p></h2>
                 <p >&nbsp;</p>
                   <p style="width:1100px"><span style="line-height: 32px; font-size:19px;">国内的“生前预嘱”的发展较晚，国民认知程度还不高，目前的了解途径主要是生前预嘱网站，而认知度高的成员也集中在网站的会员中；而国外有些国家起源较早，“生前预嘱”的概念已经在国民中拥有了较大的认知度和传播度，基于此，我们挑选了3个普及面广并且比较有代表性的国家：日本、瑞士、美国进行分析。</span></p> 
                  <p>&nbsp;</p>
                  <br>
               
                </div>
            </div>
            <h3 class="section-heading biaoti" style="text-align: center;"><b>国内现状</b></h3>
            <p>&nbsp;</p>
        <div style="display: flex;align-items: center;justify-content: center;">
            <div class="img2" id="number" style="width: 550px;height: 350px"></div>
            <script src="js/echarts.js" ></script>
            <script src="js/人数.js"></script>
            <p style="width:36px">&nbsp;</p>
            <p style="width:350px; "><span style="line-height: 32px; font-size:18px;">截至2022年9月，登陆网站人数为<span style=" font-weight: bold;color: #B28DAF">184959人</span>，
                注册用户人数为<span style=" font-weight: bold;color: #B28DAF">113289人</span>，预嘱填写有效人数为
                <span style="font-weight: bold;color: #B28DAF">57201人</span>。总人数在不断增长，但是从2019年开始，
                3个数据的年平均人数都开始下滑，反映出我国生
                前预嘱的推广到达瓶颈期。</span></p>
                <p style="width:20px">&nbsp;</p>
        </div>
        <p >&nbsp;</p>
       
       
        <div style="display: flex;align-items: center;justify-content: center;">
            <p style="width:400px;"><span style="line-height: 32px; font-size:18px;">目前“生前预嘱”相关内容在生前预嘱推广微信公众号的浏览量约为<span style=" font-weight: bold;color: #B28DAF">130万人</span>，微博相关话题浏览量<span style=" font-weight: bold;color: #B28DAF">180万人次</span>，搜狐相关文章有<span style=" font-weight: bold;color: #B28DAF">超过500篇</span>，文章累计浏览量约为<span style=" font-weight: bold;color: #B28DAF">80万人次</span>，目前全网相关信息浏览量<span style=" font-size:26px;font-weight: bold;color: #B28DAF">超过500万人次</span>，且人数仍在上升中.说明虽然国内目前对"生前预嘱"的认知还比较缺乏,但是越来越多人开始了解和接触“生前预嘱”理念，也有越来越多媒体开始关注聚焦相关话题。<br> <span style="color: darkgray">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;数据来源:生前预嘱推广协会</span></p>
           <p style="width:20px">&nbsp;</p>
            <img src="img/媒体.png" alt="" width="500" height="250">
        </div>
        <p >&nbsp;</p>
        <p >&nbsp;</p>
       <br>
        <h3 class="section-heading"><b><span style="color:#FFF">国外现状</span> </b></h3>
        <p >&nbsp;</p>
     
        <div style="display: flex;justify-content: center;align-items: center;">
            <div id="America1" style="width:450px;height: 370px;"></div>
          <script src="js/echarts.js alt=" width="350" height="280"></script>
          <script src="js/America1.js"></script><br>
          <div id="America2" style="width: 490px;height: 370px"></div>
          <script src="js/echarts.js"></script>
          <script src="js/America2.js"></script>
          &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
        </div>
        <div>
            <span style="color: darkgray">
                数据来源：HealthAffairs：
             Approximately One In Three US Adults Completes Any Type Of Advance Directive For End-Of-Life Care</span>  
          </div>

          <div>
    
       <br>
           
                <p ><span style="line-height: 32px; font-size:18px;"><span style="font-size: 28px;color: #B28DAF "><b>美国</b></span>民众中，有36.7%的人完成了一些预先指示，29.3%的人完成了包含实际护理愿望的生前预嘱，33.4%的人指定了医疗保健授权书。患者（38.2%）的完成率高于健康成年人（32.7%），65岁及以上患者（45.6%）的完成率明显高于年轻人（31.6%）。对于慢性病患者，神经系统疾病患者的预先指示完成率最高（56.5%），艾滋病毒/艾滋病患者最低（17.3%）。
            总之,美国的预设医疗指示完成度在 <span style="font-weight: bold;color: #B28DAF">1/3左右，总体停滞不前，但相对其他国家而言较高，说明意愿相对较高，政策普及度较广。</span>
        文章中也说，目前美国提供了几种提高完成率的策略，其中包括将患者的价值观和目标纳入这些文档，并简化程序，减少不一致的法律障碍。</span></p>
              
          </div>
        <p>&nbsp;</p>
          <div style="display: flex;justify-content: center;align-items: center;">
            <div id="Switzerland2" style="width: 400px;height: 375px"></div>
          <script src="js/echarts.js"></script>
          <script src="js/Switzerland2.js"></script>&nbsp;<br>
          <div id="Switzerland1" style="width: 450px;height:375px"></div>
          <script src="js/echarts.js"></script>
          <script src="js/Switzerland1.js"></script>&nbsp;
          </div>
          <br>
          <div>
            <span style="color: darkgray">
                数据来源：swiss medical weekly：
                Awareness, approval and completion of advance directives in older adults in Switzerland</span>  
          </div>
<br>
          <div>
            
            <blockquote>
                <p ><span style="line-height: 32px; font-size:18px;"><span style="color:#B28DAF ;font-size: 28px"><b>瑞士</b></span>居民对生前预嘱的了解程度和同意度很高， <span style="font-weight: bold;color: #B28DAF">达到了90%左右，但是完成度不高，大约只有1/3。</span>另外，在瑞士各群体之间的数据也存在较大差异，德语地区的认知程度明显比法语和意大利语地区高；女性意识普遍比男性高；老年人比年轻人更容易完成生前预嘱的填写。说明生前预嘱在瑞士总体的普及度较高，但各地区可能因文化差异等因素影响了认知水平。认知程度高但是完成度不高，说明居民虽然了解，但是付诸行动的意愿偏低。</span></p>
              </blockquote>
          </div>
          <p>&nbsp;</p>
          <table width="100%" border="0" cellspacing="0" cellpadding="0">
            <tbody>
              <tr>
                
              </tr>
              <tr>
                <td>&nbsp;</td>
                <td align="right"><div id="Japan1" style="width: 500px;height: 425px"></div>
          <script src="js/echarts.js"></script>
          <script src="js/Japan1.js"></script>
          <br><span style="color: darkgray">数据来源：日本卫生、劳动与福利部门2014年关于临终医疗的调查</span>&nbsp;</td>
                <td><div id="Japan2" style="width: 450px; height: 400px;"></div>
          <script src="js/echarts.js"></script>
          <script src="js/Japan2.js"></script>
          <br><span style="color: darkgray">数据来源：BMC：Survey of the general public's attitudes toward advance directives in Japan: How to respect patients' preferences</span>&nbsp;</td>
                <td>&nbsp;</td>
              </tr>
              <tr>
                <td>&nbsp;</td>
                <td colspan="2"><br><p ><span style="line-height: 32px; font-size:18px;"><span style="color:#B28DAF ;font-size: 28px"><b>日本</b></span>民众除了普通人，其他三类职业人群在各个年龄段的非常关心选项都接近50%，几乎都是首选；普通人“非常关心”大概在20%左右，但“有点关心”占比大，在40%-60%，而所有人群中，选择“完全不关心”的比例都在6%以下，说明大部分的民众都关心这个概念。而在表达意愿上，可以看到民众对治疗偏好、指定护理决定人等与生前预嘱相关内容的表达意愿，丝毫不亚于甚至超过已经成为约定程序的遗产遗嘱相关内容，可见日本民众对于“生前预嘱”的表达欲望也较高。总体来说，日本民众对于“生前预嘱”的关心程度和填写欲望都比较高。</p></td>
                <td>&nbsp;</td>
            </tr>
            </tbody>
          </table>
        </div>
        
</section>

</section>
<section style="background:#212529 !important;color: #fff;padding: 2.5rem 0;">
    <div class="container">
        <div class="row">
          <div class="col-lg-12">
            <h2 class="section-heading"><p align="center"><b>法规</b></p></h2>
             
               <p ><span style="line-height: 32px; font-size:19px;">除了认知的不同，目前国内外关于生前预嘱的法规保障也存在差异，下面我们将介绍和对比国内的台湾、香港、大陆地区，以及日本、瑞士、美国关于“生前预嘱”的法规及其发展情况，并附上这些国家或地区的法律文件和生前预嘱填写文件。</span></p> 
            </div>
        </div>
    </div>
</section>
    <section class="p-0" id="fagui">
        <div class="container-fluid p-0">
            <div class="row no-gutters ">
                <div class="col-lg-4 col-sm-6">
                    <a class="portfolio-box" href="台湾.html" target="_blank"title="中国台湾生前预嘱法规">
                        <img class="img-fluid" src="img/portfolio/thumbnails/1.jpg"  alt="">
                        <div class="portfolio-box-caption">
                            <div class="portfolio-box-caption-content">
                                <div class="project-category text-faded">
                                    国内</div>
                                <div class="project-name">
                              台湾</div>
                            </div>
                        </div>
                    </a>
                </div>
                <div class="col-lg-4 col-sm-6">
                    <a class="portfolio-box" href="香港.html" target="_blank" title="中国香港生前预嘱法规">
                        <img class="img-fluid" src="img/portfolio/thumbnails/2.jpg" alt="">
                        <div class="portfolio-box-caption">
                            <div class="portfolio-box-caption-content">
                                <div class="project-category text-faded">
                                    国内</div>
                                <div class="project-name">
                                    香港
                                </div>
                            </div>
                        </div>
                    </a>
                </div>
                <div class="col-lg-4 col-sm-6">
                    <a class="portfolio-box" href="大陆.html" target="_blank" title="中国大陆生前预嘱法规">
                        <img class="img-fluid" src="img/portfolio/fullsize/3.jpg" alt="">
                        <div class="portfolio-box-caption">
                          <div class="portfolio-box-caption-content">
                                <div class="project-category text-faded">
                                    国内</div>
                                <div class="project-name">
                                   大陆
                                </div>
                          </div>
                    </div>
                  </a>
            </div>
                <div class="col-lg-4 col-sm-6">
                    <a class="portfolio-box" href="日本.html" target="_blank" title="日本生前预嘱法规">
                        <img class="img-fluid" src="img/portfolio/thumbnails/4.jpg" alt="">
                        <div class="portfolio-box-caption">
                            <div class="portfolio-box-caption-content">
                                <div class="project-category text-faded">
                                    国外
                                </div>
                                <div class="project-name">
                                    亚洲--日本</div>
                            </div>
                        </div>
                    </a>
                </div>
                <div class="col-lg-4 col-sm-6">
                    <a class="portfolio-box" href="瑞士.html" target="_blank" title="瑞士生前预嘱法规">
                        <img class="img-fluid" src="img/portfolio/thumbnails/5.jpg" alt="">
                        <div class="portfolio-box-caption">
                            <div class="portfolio-box-caption-content">
                                <div class="project-category text-faded">
                                    国外</div>
                                <div class="project-name">
                                    欧洲--瑞士
                                </div>
                            </div>
                        </div>
                    </a>
                </div>
                <div class="col-lg-4 col-sm-6">
                    <a class="portfolio-box" href="美国.html" target="_blank" title="美国生前预嘱法规">
                        <img class="img-fluid" src="img/portfolio/thumbnails/6.jpg" alt="">
                        <div class="portfolio-box-caption">
                            <div class="portfolio-box-caption-content">
                                <div class="project-category text-faded">
                                    国外
                                </div>
                                <div class="project-name">
                                    美洲--美国</div>
                            </div>
                        </div>
                    </a>
                </div>
            </div>
        </div>
    </section>

    
    <section style="background-color: #fff"id="contact">
    <div class="col-lg-8 mx-auto ">
                    <h2 class="section-heading text-black"><p align="center">然而，生前预嘱的推广还存在一些争议</p></h2>
      <hr class="light my-4">
<table border="0" cellpadding="0" cellspacing="0">
                      <tr>
                        <td><img src="img/争议/shijian.png" width="650" height="135"></td>
                        <td width="410"><img src="img/争议/yeqian.png" width="130" height="220"></td>
                      </tr>
                      <tr>
                        <td height="35"></td>
                        <td></td>
                      </tr>
                      <tr>
                        <td colspan="2" align="center"><img src="img/争议/meiguo.png" width="200" height="260">&nbsp;&nbsp;&nbsp;&nbsp;<img src="img/争议/bingqing.png" width="500" height="151"></td>
                      </tr>
                      <tr>
                        <td height="10"></td>
                        <td></td>
                      </tr>
                      <tr>
                        <td>&nbsp;</td>
                        <td rowspan="2"><img src="img/争议/zhangsi.png" width="190" height="250"></td>
                      </tr>
                      <tr>
                        <td rowspan="2" align="center"><img src="img/争议/canzhang - 副本.png" width="500" height="130"></td>
                      </tr>
                      <tr>
                        <td>&nbsp;</td>
                      </tr>
                      <tr>
                        <td colspan="2" align="center"><img src="img/争议/guyang - 副本.png" width="240" height="250"><img src="img/争议/xiaodao.png" width="600" height="145"></td>
                      </tr>
                      <tr>
                       
                      </tr>
                    </table>
                    </div>
                    <div class="container">
                        <p>&nbsp;</p>
                        <p style="margin-top: 20px;"><span style="font-weight: 500;line-height: 2em;font-size: 18px;">希望“利用一切手段生活”的人的意愿也应得到尊重，但是面对希望“平静地迎接那个时刻”的人，社会也应该把死亡的权利还给他们。在某种程度上，生前预嘱并非单纯的医疗和法律问题，无论对当事人、医护人员还是整个社会而言，都涉及到相关复杂的道德伦理，生前预嘱的推广与实践在中国依然还有很长的路要走。</span></p> 
                        <p>&nbsp;</p>
                        <p align="center"><a class="btn  " style="width: 18%;background: #526377;color: #fff;" href="#shouye"><span style="color:#fff">返回顶部</span></a></p>
                    </div>
                    
</section>

<section class=" text-white"id="services" style="background:linear-gradient(#897f85, #526578);padding: 1.5rem 0;">
    <div class="container">
        <div class="row">
          <div class="col-lg-12">
            
            <p align="center" ><span style="font-size: 28px;font-weight:700">华南理工大学</span><br><span style="font-weight: 500;line-height: 2em;font-size: 18px;">作者:莫舒童 朱雅泽<br>指导老师:吴小坤 李婉旖</span></p>
              
        </div>
    </div>
</section>

    


    <!-- Bootstrap core JavaScript -->
    <script src="vendor/jquery/jquery.min.js"></script>
    <script src="vendor/bootstrap/js/bootstrap.bundle.min.js"></script>

    <!-- Plugin JavaScript -->
    <script src="vendor/jquery-easing/jquery.easing.min.js"></script>
    <script src="vendor/scrollreveal/scrollreveal.min.js"></script>
    <script src="vendor/magnific-popup/jquery.magnific-popup.min.js"></script>

    <!-- Custom scripts for this template -->
    <script src="js/creative.min.js"></script>
    <script src="js/Quiz.js"></script>
</body>

</html>
