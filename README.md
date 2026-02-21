<html lang="zh-CN">
 <head> 
  <meta charset="UTF-8"> 
  <title>钛风🐾来財版</title> 
  <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: "Microsoft YaHei", sans-serif;
        }
        body {
            background: #ffffff;
            color: #000;
            text-align: center;
            padding: 50px 20px;
        }
        .container {
            max-width: 400px;
            margin: 0 auto;
        }
        h1 {
            font-size: 28px;
            margin-bottom: 20px;
            color: #000;
        }
        .goods-img {
            width: 100%;
            border-radius: 12px;
            margin-bottom: 20px;
            object-fit: cover;
        }
        .tags {
            display: flex;
            justify-content: center;
            gap: 15px;
            margin-bottom: 25px;
            font-size: 26px;
            font-weight: bold;
            color: #ff4d4f;
        }
        .buy-btn {
            padding: 14px 40px;
            font-size: 18px;
            background: #ff4d4f;
            color: #fff;
            border: none;
            border-radius: 8px;
            cursor: pointer;
            font-weight: bold;
        }

        /* 弹窗样式 */
        .modal {
            position: fixed;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            background: #fff;
            padding: 30px 40px;
            border-radius: 12px;
            box-shadow: 0 0 20px rgba(0,0,0,0.3);
            font-size: 24px;
            font-weight: bold;
            color: #ff4d4f;
            display: none;
            z-index: 999;
        }
    </style> 
  <script src="js/jq.js"></script> 
 </head> 
 <body id="v1"> 
  <div id="v2" class="container"> 
   <h1 id="v3">钛风🐾来財版</h1> 
   <img id="v4" class="goods-img" src="/sdcard/Pictures/QQ/Image_1770534776020.png" alt="钛风来財版"> 
   <div id="v5" class="tags"> 
    <span id="v6">5折优惠</span> 
    <span id="v7">当天发货</span> 
    <span id="v8">现在就能订购</span> 
   </div> 
   <button id="v9" class="buy-btn" onclick="showModal()">点击购买</button> 
   <div class="modal" id="modal">
     我只能是🐾灰澜🐾的 
   </div> 
  </div> 
  <script>
    function showModal() {
        var modal = document.getElementById("modal");
        modal.style.display = "block";
        setTimeout(function() {
            modal.style.display = "none";
        }, 3000);
    }
</script> }  
 </body>
</html> 
