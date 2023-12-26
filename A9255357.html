<!DOCTYPE html>
<html lang="zh-TW">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Trivago</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }

        #header {
            background-color: #4CAF50;
            width: 1437px;
            height: 50px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 0 20px;
        }

        #title {
            color: white;
            font-size: 24px;
            text-decoration: none;
        }

        #subtitle {
            color: white;
            font-size: 18px;
        }

        #currencyBtn {
            position: absolute;
            left: 200px;
            top: 2px;
            width: 105px;
            height: 49px;
            background-color: #4CAF50;
            color: white;
            border: none;
            cursor: pointer;
        }

        #weatherBtn {
            position: absolute;
            left: 411px;
            top: 3px;
            width: 100px;
            height: 47px;
            background-color: #4CAF50;
            color: white;
            border: none;
            cursor: pointer;
        }

        #content {
            margin: 20px;
        }

        #bookingForm {
            display: flex;
            gap: 10px;
            align-items: center;
        }

        #bookingForm label {
            min-width: 80px;
            text-align: right;
        }

        #addBookingBtn,
        #exportBtn {
            margin-top: 10px;
            padding: 10px;
            background-color: #4CAF50;
            color: white;
            border: none;
            cursor: pointer;
            width: 150px; /* 調整寬度 */
        }

        #travelInfo {
            margin-top: 20px;
        }

        #bookingList {
            margin-top: 20px;
        }
    </style>
</head>

<body>
    <div id="header">
        <a id="title" href="https://www.trivago.com.tw/zh-Hant-TW/lm?themeId=280&search=200-194&sem_keyword=trivago&sem_creativeid=558327359175&sem_matchtype=e&sem_network=g&sem_device=c&sem_placement=&sem_target=&sem_adposition=&sem_param1=&sem_param2=&sem_campaignid=312135388&sem_adgroupid=114226555392&sem_targetid=kwd-5593367084&sem_location=9040379&cipc=br&cip=8861900005&gad_source=1&gclid=CjwKCAiAvoqsBhB9EiwA9XTWGbZaraZIm4tWmjOKjHixn_2TWlRktYUlKFr2icy_kn5pu9cq1aniSRoCjHkQAvD_BwE"
            target="_blank">trivago</a>
        <button id="currencyBtn" onclick="navigateToCurrency()">幣別</button>
        <button id="weatherBtn" onclick="navigateToWeather()">氣象局天氣查詢</button>
    </div>

    <div id="content">
        <form id="travelForm">
            <div id="bookingForm">
                <label for="destination">目的地:</label>
                <input type="text" id="destination" name="destination" required>

                <label for="checkIn">入住日期:</label>
                <input type="date" id="checkIn" name="checkIn" required>

                <label for="checkOut">退房日期:</label>
                <input type="date" id="checkOut" name="checkOut" required>

                <label for="guests">旅客數:</label>
                <input type="number" id="guests" name="guests" required>

                <label for="rooms">客房數:</label>
                <input type="number" id="rooms" name="rooms" required>

                <button type="button" id="addBookingBtn" onclick="addBooking()">添加訂房</button>
            </div>
            <button type="button" id="exportBtn" onclick="exportToTxt()">導出為TXT文件</button>
        </form>

        <div id="bookingList">
            <h2>訂房列表</h2>
            <ul id="bookingUl"></ul>
        </div>
    </div>

    <script>
        function exportToTxt() {
            // 取得訂房列表的內容
            var bookingList = document.getElementById('bookingUl').innerText;

            // 創建一個Blob對象
            var blob = new Blob([bookingList], { type: 'text/plain' });

            // 創建一個<a>元素，設置下載屬性和連結Blob對象
            var a = document.createElement('a');
            a.download = 'bookingList.txt';
            a.href = window.URL.createObjectURL(blob);

            // 將<a>元素添加到文檔中，觸發點擊事件
            document.body.appendChild(a);
            a.click();

            // 移除<a>元素
            document.body.removeChild(a);
        }

        function navigateToCurrency() {
            window.location.href = "https://www.stockq.org/market/currency.php";
        }

        function navigateToWeather() {
            window.location.href = "https://www.cwa.gov.tw/V8/C/";
        }

        function addBooking() {
            // 取得表單輸入值
            var destination = document.getElementById('destination').value;
            var checkIn = document.getElementById('checkIn').value;
            var checkOut = document.getElementById('checkOut').value;
            var guests = document.getElementById('guests').value;
            var rooms = document.getElementById('rooms').value;

            // 建立訂房內容
            var bookingContent = `${destination} - 入住日期: ${checkIn} 退房日期: ${checkOut} 旅客數: ${guests} 客房數: ${rooms}`;

            // 創建新的列表項目
            var bookingItem = document.createElement('li');
            bookingItem.textContent = bookingContent;

            // 將列表項目添加到列表中
            document.getElementById('bookingUl').appendChild(bookingItem);

            // 清空表單輸入值
            document.getElementById('destination').value = '';
            document.getElementById('checkIn').value = '';
            document.getElementById('checkOut').value = '';
            document.getElementById('guests').value = '';
            document.getElementById('rooms').value = '';
        }
    </script>
</body>

</html>
