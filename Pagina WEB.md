#Dashboard
We used Gentellela template that is licensed under The MIT License (MIT). Colorlib is the original author of this template. [https://github.com/puikinsh/gentellela](https://github.com/puikinsh/gentellela)
	

All the stylesheets and animations scripts were imported 

	<!DOCTYPE html>
	<html lang="en">
	
	<head>
	  <meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
	  <!-- Meta, title, CSS, favicons, etc. -->
	  <meta charset="utf-8">
	  <meta http-equiv="X-UA-Compatible" content="IE=edge">
	  <meta name="viewport" content="width=device-width, initial-scale=1">
	
	  <title>KarPort | Dashboard </title>
	
	  <!-- Bootstrap core CSS -->
	
	  <link href="css/bootstrap.min.css" rel="stylesheet">
	
	  <link href="fonts/css/font-awesome.min.css" rel="stylesheet">
	  <link href="css/animate.min.css" rel="stylesheet">
	
	  <!-- Custom styling plus plugins -->
	  <link href="css/custom.css" rel="stylesheet">
	  <link rel="stylesheet" type="text/css" href="css/maps/jquery-jvectormap-2.0.3.css" />
	  <link href="css/icheck/flat/green.css" rel="stylesheet" />
	  <link href="css/floatexamples.css" rel="stylesheet" type="text/css" />
	  <link href="css/datepicker.css" rel="stylesheet">
	
	
	  <script src="js/jquery.min.js"></script>
	  <script src="js/nprogress.js"></script>
	
	
	  <!--[if lt IE 9]>
	        <script src="../assets/js/ie8-responsive-file-warning.js"></script>
	        <![endif]-->
	
	  <!-- HTML5 shim and Respond.js for IE8 support of HTML5 elements and media queries -->
	  <!--[if lt IE 9]>
	          <script src="https://oss.maxcdn.com/html5shiv/3.7.2/html5shiv.min.js"></script>
	          <script src="https://oss.maxcdn.com/respond/1.4.2/respond.min.js"></script>
	        <![endif]-->
	
	</head>
	
	<body class="nav-md">
	
	  <div class="container body">
	
	
	    <div class="main_container">
	
	      <div class="col-md-3 left_col">
	        <div class="left_col scroll-view">


----------
Here we started the navigation bar. It contains the logo, the profile picture and information of the user that is using the dashboard 
	
	          <div class="navbar nav_title" style="border: 0;">
	            <a href="index.html" class="site_title">&nbsp;<img src="images/KarPort.png" width="35">&nbsp;&nbsp;<img src="images/KarPortText.png" width="105"></a>
	          </div>
	          <div class="clearfix"></div>
	
	          <!-- menu prile quick info -->
	          <div class="profile">
	            <div class="profile_pic">
	              <img src="images/JuanAndres.jpg" alt="..." class="img-circle profile_img">
	            </div>
	            <div class="profile_info">
	              <span>Welcome,</span>
	              <h2>Juan Andrés</h2>
	            </div>
	          </div>
	          <!-- /menu prile quick info -->
	
	          <br />
	
	          <!-- sidebar menu -->
	          <div id="sidebar-menu" class="main_menu_side hidden-print main_menu">

----------
Here starts the navigation options like the reports of all the zones in the parking lot and reports by day, month or year.  
	
	            <div class="menu_section">
	              <h3>General</h3>
	              <ul class="nav side-menu">
	                <li><a><i class="fa fa-clock-o"></i> Current Report <span class="fa fa-chevron-down"></span></a>
	                  <ul class="nav child_menu" style="display: none">
	                    <li><a href="index.html">All Zones</a>
	                    </li>
	                  </ul>
	                </li>
	                <li><a><i class="fa fa-line-chart"></i> Reports by Date <span class="fa fa-chevron-down"></span></a>
	                  <ul class="nav child_menu" style="display: none">
	                    <li><a href="day_reports.html">Day</a>
	                    </li>
	                    <li><a href="week_reports.html">Week</a>
	                    </li>
	                    <li><a href="month_reports.html">Month</a>
	                    </li>
	                  </ul>
	                </li>


This navigation options shows the daily ages, gender, guests, users with disabilities and car models that has entered the parking lot.

	                <li><a><i class="fa fa-male"></i> Demographics <span class="fa fa-chevron-down"></span></a>
	                  <ul class="nav child_menu" style="display: none">
	                    <li><a href="ages.html">Ages (Daily)</a>
	                    </li>
	                    <li><a href="gender.html">Gender (Daily)</a>
	                    </li>
	                    <li><a href="guest_records.html">Guest Records (Daily)</a>
	                    </li>
	                    <li><a href="disabilities.html">Disabilities (Daily)</a>
	                    </li>
	                    <li><a href="car_models.html">Car Models</a>
	                    </li>
	                  </ul>
	                </li>
	            </div>
	            <div class="menu_section">

----------
Here is the option to send an email to tech support

	              <h3>Tech Support</h3>
	              <ul class="nav side-menu">
	                <li><a><i class="fa fa-bug"></i> Contact Tech Support <span class="fa fa-chevron-down"></span></a>
	                  <ul class="nav child_menu" style="display: none">
	                    <li><a href="mailto:techsupport@iotkali.com">Email</a>
	                    </li>
	                  </ul>
	                </li>
	              </ul>
	            </div>
	
	          </div>
	          <!-- /sidebar menu -->
This block contains the log out button

	          <!-- /menu footer buttons -->
	          <div class="sidebar-footer hidden-small">
	            <a href="login.html" data-toggle="tooltip" data-placement="top" title="Logout">
	              <span class="glyphicon glyphicon-off" aria-hidden="true"></span>
	            </a>
	          </div>
	          <!-- /menu footer buttons -->
	        </div>
	      </div>
	

This contains the top navigation bar with the user information, settings option, help option and a log out option 
	      <!-- top navigation -->
	      <div class="top_nav">
	
	        <div class="nav_menu">
	          <nav class="" role="navigation">
	            <div class="nav toggle">
	              <a id="menu_toggle"><i class="fa fa-bars"></i></a>
	            </div>
	
	            <ul class="nav navbar-nav navbar-right">
	              <li class="">
	                <a href="javascript:;" class="user-profile dropdown-toggle" data-toggle="dropdown" aria-expanded="false">
	                  <img src="images/JuanAndres.jpg" alt="">Juan Andr&eacute;s
	                  <span class=" fa fa-angle-down"></span>
	                </a>
	                <ul class="dropdown-menu dropdown-usermenu animated fadeInDown pull-right">
	                  <li><a href="javascript:;">  Profile</a>
	                  </li>
	                  <li>
	                    <a href="javascript:;">
	                      <span class="badge bg-red pull-right">50%</span>
	                      <span>Settings</span>
	                    </a>
	                  </li>
	                  <li>
	                    <a href="javascript:;">Help</a>
	                  </li>
	                  <li><a href="login.html"><i class="fa fa-sign-out pull-right"></i> Log Out</a>
	                  </li>
	                </ul>
	              </li>
	
	            </ul>
	          </nav>
	        </div>
	
	      </div>
	      <!-- /top navigation -->
	
	


This section contains a block with the actual date, time and current users.
	      <!-- page content -->
	      <div class="right_col" role="main">
	
	        <!-- top tiles -->
	        <div class="row tile_count">
	          <div class="animated flipInY col-md-3 col-sm-4 col-xs-4 tile_stats_count">
	            <div class="left"></div>
	            <div class="right">
	              <span class="count_top"><i class="glyphicon glyphicon-calendar fa fa-calendar"></i> Date:</span>
	              <div class="count"><span id ="date"></span></div>
	            </div>
	          </div>
	          <div class="animated flipInY col-md-3 col-sm-4 col-xs-4 tile_stats_count">
	            <div class="left"></div>
	            <div class="right">
	              <span class="count_top"><i class="fa fa-clock-o"></i> Actual Time</span>
	              <div class="count"><span id ="actualTime"></span></div>
	            </div>
	          </div>
	          <div class="animated flipInY col-md-2 col-sm-4 col-xs-4 tile_stats_count">
	            <div class="left"></div>
	            <div class="right">
	              <span class="count_top"><i class="fa fa-user"></i> Current Users</span>
	              <div class="count blue" id="cusers"> <script type="text/javascript" src="js/Custom/custom.js"></script> </div>
	            </div>
	          </div>
	
	        </div>
	        <!-- /top tiles -->
	        <!-- visualization and date pickers -->
	
	
	
	
	        <!-- /visualization and date pickers -->
	
	      </div>
	
	
	        <!-- footer content -->
	          <div class="copyright-info">
	            <p class="pull-right">KarPort Copyright 2016 - Powered by &nbsp;&nbsp; <img src="images/Kali%20idpi.png" width="25">&nbsp;<b>IoT Kali</b>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
	            </p>
	          </div>
	          <div class="clearfix"></div>
	
	        <!-- /footer content -->
	      </div>
	      <!-- /page content -->
	
	    </div>
	
	  </div>
	
	  <div id="custom_notifications" class="custom-notifications dsp_none">
	    <ul class="list-unstyled notifications clearfix" data-tabbed_notifications="notif-group">
	    </ul>
	    <div class="clearfix"></div>
	    <div id="notif-group" class="tabbed_notifications"></div>
	  </div>
	
	  <script src="js/bootstrap.min.js"></script>
	
	  <!-- gauge js -->
	  <script type="text/javascript" src="js/gauge/gauge.min.js"></script>
	  <script type="text/javascript" src="js/gauge/gauge_demo.js"></script>
	  <!-- bootstrap progress js -->
	  <script src="js/progressbar/bootstrap-progressbar.min.js"></script>
	  <script src="js/nicescroll/jquery.nicescroll.min.js"></script>
	  <!-- icheck -->
	  <script src="js/icheck/icheck.min.js"></script>
	  <!-- daterangepicker -->
	  <script type="text/javascript" src="js/moment/moment.min.js"></script>
	  <script type="text/javascript" src="js/datepicker/daterangepicker.js"></script>
	  <!-- chart js -->
	  <script src="js/chartjs/chart.min.js"></script>
	
	  <script src="js/custom.js"></script>
	
	  <!-- flot js -->
	  <!--[if lte IE 8]><script type="text/javascript" src="js/excanvas.min.js"></script><![endif]-->
	  <script type="text/javascript" src="js/flot/jquery.flot.js"></script>
	  <script type="text/javascript" src="js/flot/jquery.flot.pie.js"></script>
	  <script type="text/javascript" src="js/flot/jquery.flot.orderBars.js"></script>
	  <script type="text/javascript" src="js/flot/jquery.flot.time.min.js"></script>
	  <script type="text/javascript" src="js/flot/date.js"></script>
	  <script type="text/javascript" src="js/flot/jquery.flot.spline.js"></script>
	  <script type="text/javascript" src="js/flot/jquery.flot.stack.js"></script>
	  <script type="text/javascript" src="js/flot/curvedLines.js"></script>
	  <script type="text/javascript" src="js/flot/jquery.flot.resize.js"></script>
	  <script>
	    $(document).ready(function() {
	      // [17, 74, 6, 39, 20, 85, 7]
	      //[82, 23, 66, 9, 99, 6, 2]
	      var data1 = [
	        [gd(2012, 1, 1), 17],
	        [gd(2012, 1, 2), 74],
	        [gd(2012, 1, 3), 6],
	        [gd(2012, 1, 4), 39],
	        [gd(2012, 1, 5), 20],
	        [gd(2012, 1, 6), 85],
	        [gd(2012, 1, 7), 7]
	      ];
	
	      var data2 = [
	        [gd(2012, 1, 1), 82],
	        [gd(2012, 1, 2), 23],
	        [gd(2012, 1, 3), 66],
	        [gd(2012, 1, 4), 9],
	        [gd(2012, 1, 5), 119],
	        [gd(2012, 1, 6), 6],
	        [gd(2012, 1, 7), 9]
	      ];
	      $("#canvas_dahs").length && $.plot($("#canvas_dahs"), [
	        data1, data2
	      ], {
	        series: {
	          lines: {
	            show: false,
	            fill: true
	          },
	          splines: {
	            show: true,
	            tension: 0.4,
	            lineWidth: 1,
	            fill: 0.4
	          },
	          points: {
	            radius: 0,
	            show: true
	          },
	          shadowSize: 2
	        },
	        grid: {
	          verticalLines: true,
	          hoverable: true,
	          clickable: true,
	          tickColor: "#d5d5d5",
	          borderWidth: 1,
	          color: '#fff'
	        },
	        colors: ["rgba(38, 185, 154, 0.38)", "rgba(3, 88, 106, 0.38)"],
	        xaxis: {
	          tickColor: "rgba(51, 51, 51, 0.06)",
	          mode: "time",
	          tickSize: [1, "day"],
	          //tickLength: 10,
	          axisLabel: "Date",
	          axisLabelUseCanvas: true,
	          axisLabelFontSizePixels: 12,
	          axisLabelFontFamily: 'Verdana, Arial',
	          axisLabelPadding: 10
	            //mode: "time", timeformat: "%m/%d/%y", minTickSize: [1, "day"]
	        },
	        yaxis: {
	          ticks: 8,
	          tickColor: "rgba(51, 51, 51, 0.06)",
	        },
	        tooltip: false
	      });
	
	      function gd(year, month, day) {
	        return new Date(year, month - 1, day).getTime();
	      }
	    });
	  </script>
	
	  <!-- worldmap -->
	  <script type="text/javascript" src="js/maps/jquery-jvectormap-2.0.3.min.js"></script>
	  <script type="text/javascript" src="js/maps/gdp-data.js"></script>
	  <script type="text/javascript" src="js/maps/jquery-jvectormap-world-mill-en.js"></script>
	  <script type="text/javascript" src="js/maps/jquery-jvectormap-us-aea-en.js"></script>
	  <!-- pace -->
	  <script src="js/pace/pace.min.js"></script>
	  <script>
	    $(function() {
	      $('#world-map-gdp').vectorMap({
	        map: 'world_mill_en',
	        backgroundColor: 'transparent',
	        zoomOnScroll: false,
	        series: {
	          regions: [{
	            values: gdpData,
	            scale: ['#E6F2F0', '#149B7E'],
	            normalizeFunction: 'polynomial'
	          }]
	        },
	        onRegionTipShow: function(e, el, code) {
	          el.html(el.html() + ' (GDP - ' + gdpData[code] + ')');
	        }
	      });
	    });
	  </script>
	  <!-- skycons -->
	  <script src="js/skycons/skycons.min.js"></script>
	  <script>
	    var icons = new Skycons({
	        "color": "#73879C"
	      }),
	      list = [
	        "clear-day", "clear-night", "partly-cloudy-day",
	        "partly-cloudy-night", "cloudy", "rain", "sleet", "snow", "wind",
	        "fog"
	      ],
	      i;
	
	    for (i = list.length; i--;)
	      icons.set(list[i], list[i]);
	
	    icons.play();
	  </script>
	
	  <!-- dashbord linegraph -->
	  <script>
	    Chart.defaults.global.legend = {
	      enabled: false
	    };
	
	    var data = {
	      labels: [
	        "Symbian",
	        "Blackberry",
	        "Other",
	        "Android",
	        "IOS"
	      ],
	      datasets: [{
	        data: [15, 20, 30, 10, 30],
	        backgroundColor: [
	          "#BDC3C7",
	          "#9B59B6",
	          "#455C73",
	          "#26B99A",
	          "#3498DB"
	        ],
	        hoverBackgroundColor: [
	          "#CFD4D8",
	          "#B370CF",
	          "#34495E",
	          "#36CAAB",
	          "#49A9EA"
	        ]
	
	      }]
	    };
	
	    var canvasDoughnut = new Chart(document.getElementById("canvas1"), {
	      type: 'doughnut',
	      tooltipFillColor: "rgba(51, 51, 51, 0.55)",
	      data: data
	    });
	  </script>
	  <!-- /dashbord linegraph -->
	  <!-- datepicker -->
	  <script type="text/javascript">
	    $(document).ready(function() {
	
	      var cb = function(start, end, label) {
	        console.log(start.toISOString(), end.toISOString(), label);
	        $('#reportrange span').html(start.format('MMMM D, YYYY') + ' - ' + end.format('MMMM D, YYYY'));
	        //alert("Callback has fired: [" + start.format('MMMM D, YYYY') + " to " + end.format('MMMM D, YYYY') + ", label = " + label + "]");
	      }
	
	      var optionSet1 = {
	        startDate: moment().subtract(29, 'days'),
	        endDate: moment(),
	        minDate: '01/01/2012',
	        maxDate: '12/31/2015',
	        dateLimit: {
	          days: 60
	        },
	        showDropdowns: true,
	        showWeekNumbers: true,
	        timePicker: false,
	        timePickerIncrement: 1,
	        timePicker12Hour: true,
	        ranges: {
	          'Today': [moment(), moment()],
	          'Yesterday': [moment().subtract(1, 'days'), moment().subtract(1, 'days')],
	          'Last 7 Days': [moment().subtract(6, 'days'), moment()],
	          'Last 30 Days': [moment().subtract(29, 'days'), moment()],
	          'This Month': [moment().startOf('month'), moment().endOf('month')],
	          'Last Month': [moment().subtract(1, 'month').startOf('month'), moment().subtract(1, 'month').endOf('month')]
	        },
	        opens: 'left',
	        buttonClasses: ['btn btn-default'],
	        applyClass: 'btn-small btn-primary',
	        cancelClass: 'btn-small',
	        format: 'MM/DD/YYYY',
	        separator: ' to ',
	        locale: {
	          applyLabel: 'Submit',
	          cancelLabel: 'Clear',
	          fromLabel: 'From',
	          toLabel: 'To',
	          customRangeLabel: 'Custom',
	          daysOfWeek: ['Su', 'Mo', 'Tu', 'We', 'Th', 'Fr', 'Sa'],
	          monthNames: ['January', 'February', 'March', 'April', 'May', 'June', 'July', 'August', 'September', 'October', 'November', 'December'],
	          firstDay: 1
	        }
	      };
	      $('#reportrange span').html(moment().subtract(29, 'days').format('MMMM D, YYYY') + ' - ' + moment().format('MMMM D, YYYY'));
	      $('#reportrange').daterangepicker(optionSet1, cb);
	      $('#reportrange').on('show.daterangepicker', function() {
	        console.log("show event fired");
	      });
	      $('#reportrange').on('hide.daterangepicker', function() {
	        console.log("hide event fired");
	      });
	      $('#reportrange').on('apply.daterangepicker', function(ev, picker) {
	        console.log("apply event fired, start/end dates are " + picker.startDate.format('MMMM D, YYYY') + " to " + picker.endDate.format('MMMM D, YYYY'));
	      });
	      $('#reportrange').on('cancel.daterangepicker', function(ev, picker) {
	        console.log("cancel event fired");
	      });
	      $('#options1').click(function() {
	        $('#reportrange').data('daterangepicker').setOptions(optionSet1, cb);
	      });
	      $('#options2').click(function() {
	        $('#reportrange').data('daterangepicker').setOptions(optionSet2, cb);
	      });
	      $('#destroy').click(function() {
	        $('#reportrange').data('daterangepicker').remove();
	      });
	    });
	  </script>
	  <script>
	    NProgress.done();
	  </script>
	

This script gets the actual date with the day, month and year. Also, it returns the date with format MM/DD/YYYY.
	  <script>
	    var today = new Date();
	    var dd = today.getDate();
	    var mm = today.getMonth()+1;
	    var yy = today.getFullYear(); //January is 0!
	    var today = mm+'/'+dd+'/'+yy;
	    document.getElementById('date').innerHTML=today;
	  </script>

----------
This script gets the time in real time. And it returns a string with format hh:mm (am/pm).
	
	  <script>
	    function GetClock(){
	        var aTime = new Date();
	        var nhour=aTime.getHours(),nmin=aTime.getMinutes(),nsec=aTime.getSeconds(),ap;
	        if(nhour==0){ap=" AM";nhour=12;}
	        else if(nhour<12){ap=" AM";}
	        else if(nhour==12){ap=" PM";}
	        else if(nhour>12){ap=" PM";nhour-=12;}
	
	        if(nmin<=9) nmin="0"+nmin;
	        if(nsec<=9) nsec="0"+nsec;
	        var aTime = nhour+':'+nmin+''+ap;
	        document.getElementById('actualTime').innerHTML=aTime;
	      }
	      window.onload=function(){
	        GetClock();
	        setInterval(GetClock,1000);
	      }
	
	
	</script>
	  </script>
	  <!-- /datepicker -->
	  <!-- /footer content -->
	</body>
	
	</html>
This is [on GitHub](https://github.com/IoTKali/Web/blob/master/index%202.html) so let me know if I've worked it somewhere.
**---------------------------------------------------------------------------------------------------------------------------------------------------------------**

#Home Page

----------
Here we imported the stylesheets and the font Roboto from Google Fonts

	<!DOCTYPE html>
	<html>
	  <head>
	    <title>KarPort</title>
	    <!-- Bootstrap -->
	    <link href="css/bootstrap.min.css" rel="stylesheet">
	    <link href="css/custom.css" rel="stylesheet">
	    <link href='https://fonts.googleapis.com/css?family=Roboto:300' rel='stylesheet' type='text/css'>
	
	  </head>

----------
We inserted a background video and the app logo with a link to the promo video and another link with the administration panel.
	  <body>
	    <!-- Main DIV -->
	      <div class = "fsbg">
	        <!-- Background video -->
	        <video autoplay loop poster = "images/bg.png" id = "bgvideo">
	          <source src = "images/bg.mp4" type = "video/mp4">
	        </video>
	      <!-- Logo div -->
	        <div class = "row" style ="top: calc(50% - 25%); left: calc(50% - 8%); position: absolute;">
	          <div class = "col-md-12">
	            <img src="images/logo.png" id = "logo" class = "img-responsive">
	          </div>
	        </div>
	        <div class = "row" style ="top: 65%; left: calc(50% - 8%); position: absolute;">
	          <div class = "col-md-12">
	            <img src="images/cs.png" id = "logo" class = "img-responsive">
	          </div>
	        </div>
	        <div class = "row">
	          <div class = "col-md-12 text-center" style = "top: calc(50% + 40%); left: 35%; position: absolute;">
	            <a href="admin/login.html"><b class = "try">Demo</b></a>
	            <img src="images/kali.png" style = "width: 5%;">
	          </div>
	        </div>
	      </div>
	
	
	    <!-- jQuery (necessary for Bootstrap's JavaScript plugins) -->
	    <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.3/jquery.min.js"></script>
	    <!-- Include all compiled plugins (below), or include individual files as needed -->
	    <script src="js/bootstrap.min.js"></script>
	  </body>
	</html>


