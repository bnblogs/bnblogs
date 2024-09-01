<?php $url = 'https://www.bajus.org/gold-price';
$content = file_get_contents($url);
$first_step = explode( '<div id="tick">' , $content );
$second_step = explode("</div>" , $first_step[1] );
echo '<ol>';
echo $second_step[0]; echo '</ol>';?> 


<?php $url = 'https://www.bajus.org/gold-price';
$content = file_get_contents($url);
$first_step = explode( '<table class="table table-bordered table-striped gold-table">' , $content );
$second_step = explode("</table>" , $first_step[1] );
echo '<style>td{width:30% !important;}</style><table border="1px" style="max-width:100% !important;" >';
echo $second_step[0]; echo '</table>';?>
