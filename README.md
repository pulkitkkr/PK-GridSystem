# PK-GridSystem
This is a 16 bit grid system, 16 because 100/16 = 6.25 (non repeating & ending decimal) and provides more customization compared to 12-col system
<hr/>
<h3>installation</h3>
<ol>
  <li>Download the Zip from Git</li>
  <li>Copy 'grid.css' or 'grid.min.css' to your project</li>
  <li>Set < link href='path/to/grid.css'></li>
  <li>You are ready to go, use class name with reference to <b>Usage</b> section below, Happy hacking</li>
</ol>
<br/>
<h3>Device Codes:</h3>
<b>xs</b> : 0-768px <br/>
<b>s</b> : 768-992px <br/>
<b>md</b> : 992-1366px <br/>
<b>ld</b> : 1566-1920px <br/>
<b>xl</b> : more than 1920 px <br/>
<br/>
<hr/>
<h3>Usage</h3>
<ul>
  <li>All classes start with 'pk</li>
  <li>To designate columns to all screen sizes, use <b>'pk-col-all-<i>N</i>'</b> where <b><i>N</i></b> is number of columns and N is between <b>1 to 16</b></li>
  <li>For individual sizes us syntax : <b>'pk-col-<i>size-N</i>'</b>  where <b><i>size</i></b> can be <b>xs, s, md, ld, xl </b>, <b><i>N</i></b> is number of columns and N is between <b>1 to 16</b></li>
  <li>To hide element for any media device us <b>'pk-col-hidden-<i>size</i>'</b> where <b><i>size</i></b> can be <b>xs, s, md, ld, xl </b></li>
  <li>To set <b>LEFT MARGIN</b> for any element use  <b>pk-mg-l-<i>multiplier</i></b> where <b><i>multiplier</i></b> is a number between <b>1 to 10</b> For example <b>pk-mg-l-7</b> will set left margin to <i>7 x 10 =</i> <b>70%</b></li>
</ul>



