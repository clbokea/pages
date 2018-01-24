# DAT17I - SWC SPRING 2018

  
<table id="tbl">
  <tr>
      <th>Week</th>
      <th>Date</th>
      <th>Time</th>
      <th>Day</th>
      <th>Topic</th>
  </tr>
   <tr>
     <td></td>
     <td></td>
     <td></td>
     <td>Test</td>
     <td>Test</td>
  </tr>
  </table>

  <script>  

var dates = [{week : 5, date : '5/2 - 2016'}, {week : 6, date : '12/2 - 2016'}, {week : 7, date : '<b>15/2 - 2016</b>'}, {week : 7, date : '<b>18/2 - 2016</b>'}, {week : 8, date : '26/2 - 2016'}, {week : 9, date : '4/3 - 2016'}, {week : 10, date : '11/3 - 2016'}, {week : 11, date : '18/3 - 2016'}, {week : 12, date : '25/3 - 2016'}, {week : 13, date : '1/4 - 2016'}, {week : 14, date : '8/4 - 2016'}, {week : 15, date : '15/4 - 2016'}, {week : 16, date : '22/4 - 2016'}, {week : 17, date : '29/4 - 2016'}, {week : 18, date : '6/5 - 2016'}, {week : 19, date : '13/5 - 2016'},{week : 20, date :  '20/5 - 2016'}];

var table = document.getElementId("tbl");  
var rows = table.getElementsByTagName("tr");  
for(i = 1; i < rows.length; i++){  
  var tds = rows[i].getElementsByTagName("td"); 
  tds[0].innerHTML= dates[i-1].week;
  tds[1].innerHTML= dates[i-1].date;
  alert("hello");

}

</script>
  
      
