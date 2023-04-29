# monstersirentextchange
一个仿照塞壬唱片MSR官网制作切歌文字动画制作的网页文本变换实例。（虽说应该有更加简便的方法）
<a href="https://monster-siren.hypergryph.com/about">塞壬唱片MSR官网</a>
代码：
    <!DOCTYPE html>
    <html>
        <head>
            <meta charset="gbk">
            <title>text change test</title>
    
        </head>
        <body>
            <p id="text1" style="font-size: 100px;font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;text-align: center;">
            //////////
            </p><br>
            <input type="button" onclick="changeall()" value="change the text">
            <script>
            function changeall(){
                setTimeout(function(){changea1();},50);
                setTimeout(function(){changea2();},150);
                setTimeout(function(){changea3();},180);
                setTimeout(function(){changea4();},210);
                setTimeout(function(){changea5();},240);
                setTimeout(function(){changea6();},270);
                setTimeout(function(){changea7();},300);
                setTimeout(function(){changea8();},330);
                setTimeout(function(){changea9();},360);
                setTimeout(function(){changea10();},390);
                }
                function changea1(){
                    document.getElementById('text1').innerHTML="a/////////";
                }
                function changea2(){
                    document.getElementById('text1').innerHTML="nd////////";
                }
                function changea3(){
                    document.getElementById('text1').innerHTML="brj///////";
                }
                function changea4(){
                    document.getElementById('text1').innerHTML="nkiv//////";
                }
                function changea5(){
                    document.getElementById('text1').innerHTML="bdjvb/////";
                }
                function changea6(){
                    document.getElementById('text1').innerHTML="nfvhfd////";
                }
                function changea7(){
                    document.getElementById('text1').innerHTML="idhjfki///";
                }
                function changea8(){
                    document.getElementById('text1').innerHTML="j.fdekgc//";
                }
                function changea9(){
                    document.getElementById('text1').innerHTML="locd..k.e/";
                }
                function changea10(){
                    document.getElementById('text1').innerHTML="loading...";
                }
            </script>
        </body>
    </html>
