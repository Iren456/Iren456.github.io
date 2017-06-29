# Iren456.github.io
<script type="text/javascript" src="https://www.google.com/jsapi"></script>
 <script type="text/javascript">
 google.load("visualization", "1.1", {packages:["wordtree"]});
 google.setOnLoadCallback(drawChart);

 function drawChart() {
 var data = google.visualization.arrayToDataTable(
 [ ['Фразы'],
 ['Праздники_Украины Празднуется 1_января Новый_год'],
 ['Праздники_Украины Празднуется 7_января Рождество'],
 ['Праздники_Украины Празднуется 22_января День_Соборности_Украины '],
 ['Праздники_Украины Празднуется 8_марта Международный_женский день'],
 ['Праздники_Украины Празднуется 1_и_2_мая День_солидарности_трудящим'],
 ['Праздники_Украины Празднуется 9_мая День_Победы'],
 ['Праздники_Украины Празднуется 28_июня День_Конституции'],
['Праздники_Украины Празднуется 24_августа День_Конституции'],
['Праздники_Украины Празднуется 11_октября День_защитника_Украины'],
 ['Праздники_Украины Празднуется дата_меняется Пасха'],
 ['Праздники_Украины Празднуется дата_меняется Тройца'],
  ]
 );

 var options = {
maxFontSize: 14,
 backgroundColor: '#F7F7F7',
 wordtree: {
 format: 'implicit',
 word: 'Праздники_Украины'
 }
 };


 var chart = new google.visualization.WordTree(document.getElementById('wordtree_basic'));
 chart.draw(data, options);
 }
 </script>
<div id="wordtree_basic" style="margin-bottom:10px;"></div>
