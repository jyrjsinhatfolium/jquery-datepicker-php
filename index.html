<!DOCTYPE html>
<html lang="en">

<head>
  <title>JQuery Datepicker</title>
  <link rel="stylesheet" href="assets/css/jquery-ui.min.css">
  <link rel="stylesheet" href="assets/css/jquery-ui.multidatespicker.css">
</head>

<body>
  <div id="theme-switcher" style="margin-top:20px;">
    <label for="theme-select">Select Theme:</label>
    <select id="theme-select">
      <option value="base">Base Theme</option>
      <option value="black-tie">Black Tie</option>
      <option value="blitzer">Blitzer</option>
      <option value="cupertino">Cupertino</option>
      <option value="dark-hive">Dark Hive</option>
      <option value="dot-luv">Dot Luv</option>
      <option value="eggplant">Eggplant</option>
      <option value="excite-bike">Excite Bike</option>
      <option value="flick">Flick</option>
      <option value="hot-sneaks">Hot Sneaks</option>
      <option value="humanity">Humanity</option>
      <option value="le-frog">Le Frog</option>
      <option value="mint-choc">Mint Choc</option>
      <option value="overcast">Overcast</option>
      <option value="pepper-grinder">Pepper Grinder</option>
      <option value="redmond">Redmond</option>
      <option value="smoothness">Smoothness</option>
      <option value="south-street">South Street</option>
      <option value="start">Start</option>
      <option value="sunny">Sunny</option>
      <option value="swanky-purse">Swanky Purse</option>
      <option value="trontastic">Trontastic</option>
      <option value="ui-darkness">UI Darkness</option>
      <option value="ui-lightness">UI Lightness</option>
      <option value="vader">Vader</option>
    </select>
  </div>

  <div id="datePicker" style="margin-top:20px;"></div>

  <button id="submitDates" style="margin-top:20px;">Show Dates</button>

  <div id="selectedDatesArray" style="margin-top:20px;"></div>


  <script src="assets/js/jquery.min.js"></script>
  <script src="assets/js/jquery-ui.min.js"></script>
  <script src="assets/js/jquery-ui.multidatespicker.min.js"></script>

  <script>

    $(document).ready(function() {
      var dates = ["20/05/2024"];

      $('#datePicker').multiDatesPicker({
        dateFormat: "dd/mm/yy",
        numberOfMonths: [1, 2],
        beforeShowDay: function(date) {
          var formattedDate = $.datepicker.formatDate('dd/mm/yy', date);
          if ($.inArray(formattedDate, dates) !== -1) {
            return [false];
          }
          return [true];
        }
      });



      $('#submitDates').click(function() {
        var selectedDates = $('#datePicker').multiDatesPicker('getDates');
        $.ajax({
          url: 'process_dates.php',
          type: 'POST',
          data: {
            selectedDates: selectedDates
          },
          success: function(response) {
            $('#selectedDatesArray').html(response);
          }
        });
      });


      function changeTheme(theme) {
        $('#ui-theme').remove(); 
        $('<link>')
          .appendTo('head')
          .attr({
            type: 'text/css',
            rel: 'stylesheet',
            href: 'assets/css/themes/' + theme + '.min.css',
            id: 'ui-theme'
          });
      }


      $('#theme-select').on('change', function() {
        var selectedTheme = $(this).val();
        changeTheme(selectedTheme);
      });

    });
  </script>
</body>

</html>