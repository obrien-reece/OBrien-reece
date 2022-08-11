.column {
  float: left;
  width: 50%;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}
<div class="row">
  <div class="column">
     <a href="https://app.daily.dev/DailyDevTips">
   <img src="https://github.com/OBrien-reece/OBrien-reece/blob/main/devcard.svg" width="400" alt="OBrien Reece's Dev Card"/>
 </a>
  </div>
  <div class="column">
  Test
  </div>
</div>



