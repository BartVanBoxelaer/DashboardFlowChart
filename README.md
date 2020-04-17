# DashboardFlowChart
<header>
  <div class="container">
  <h1 class="text-center">Which Dashboarding tool should I use?</h1>
  </div>

<!-- Latest compiled and minified CSS -->
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" integrity="sha384-BVYiiSIFeK1dGmJRAkycuHAHRg32OmUcww7on3RYdg4Va+PmSTsz/K68vbdEjh4u" crossorigin="anonymous">

<!-- Optional theme -->
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap-theme.min.css" integrity="sha384-rHyoN1iRsVXV4nD0JutlnGaslCJuC7uwjduW9SVrLvRYooPp2bWYgmgJQIXwl/Sp" crossorigin="anonymous">

<!-- Latest compiled and minified JavaScript -->
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js" integrity="sha384-Tc5IQib027qvyjSMfHjOMaLkfuWVxZxUPnCJA7l2mCWNIpG9mGCD8wGNIcPD7Txa" crossorigin="anonymous"></script>

<link rel="stylesheet" href="DashboardCSS.css" type="text/css">

</header>

<div class="container">
  <h2 class="page-header">Step 1: Where is the data?</h2>
  <div class="row">
    <div class="col-xs-12">
  <p class="lead text-center bg-info btn text-info center-block">Is the data in a Borealis system (i.e. database)?</p>
      <div class="row">
        <div class="col-xs-6 text-center">
           <p class="btn"><span class="glyphicon glyphicon-arrow-down"></span>
        </div>
        <div class="col-xs-6 text-center">
          <p class="btn">
          <span class="glyphicon glyphicon-arrow-down"></span></p>
        </div>
      </div>

    </div>
  </div>
  <div class="row">
<!-- start step 1 >> Yes       -->  
    <div class="col-xs-6 text-center">
	  <p class="center-block"><span class="btn btn-success btn-lg" onclick="myFunctionBY1()">Yes</span></p>
      
	  <div id="buttonYes1" style="display: none">
		  <p class="btn center-block"><span class="glyphicon glyphicon-arrow-down"></span></p>
		  <p class="bg-info text-info btn">Is the data in SAP (i.e. SAP BW database)?</p>
		  <div class="row">
			<div class="col-xs-6 text-center">
			   <p class="btn"><span class="glyphicon glyphicon-arrow-down"></span>
			</div>
			<div class="col-xs-6 text-center">
			  <p class="btn">
			  <span class="glyphicon glyphicon-arrow-down"></span></p>
			</div>
		  </div>
		  <div class="row">
			<div class="col-xs-6">
				<p class="center-block"><span class="btn btn-success btn-lg">Yes</span></p>
				<p class="btn">
				<span class="glyphicon glyphicon-arrow-down"></span></p>
				<p class="bg-success text-success btn text-wrap">Okay! After the data is in the system, proceed to step 2.</p>
			</div>
			<div class="col-xs-6 text-center">
				<p class="center-block"><span class="btn btn-danger btn-lg">No</span></p>
				<p class="btn center-block"><span class="glyphicon glyphicon-arrow-down"></span></p>
				<p class="btn bg-danger text-danger text-wrap">Okay! Proceed to step 2.</p>
			</div>
		  </div>	  
	  </div>
	  <script>
	  function myFunctionBY1() {
		document.getElementById("buttonYes1").style="display";
		document.getElementById("buttonNo1").style="display: none";
  		}
	  </script>	  
    </div>
<!-- end step 1 >> Yes       -->
    
	<div class="col-xs-6 text-center">

	  <p class="center-block"><span class="btn btn-danger btn-lg" onclick="myFunctionBN1()">No</span></p>
      
	  <div id="buttonNo1" style="display: none">
	  <p class="btn center-block"><span class="glyphicon glyphicon-arrow-down"></span></p>
      <p class="bg-info text-info btn">Are you willing to put the data into the system?</p>
      
	  <div class="row">
        <div class="col-xs-6 text-center">
           <p class="btn"><span class="glyphicon glyphicon-arrow-down"></span>
        </div>
        <div class="col-xs-6 text-center">
          <p class="btn">
          <span class="glyphicon glyphicon-arrow-down"></span></p>
        </div>
      </div>
      <div class="row">
    <div class="col-xs-6">
    <p class="center-block"><span class="btn btn-success btn-lg">Yes</span></p>
          <p class="btn">
          <span class="glyphicon glyphicon-arrow-down"></span></p>
      <p class="bg-success text-success btn text-wrap">Okay! After the data is in the system, proceed to step 2.</p>
      
    </div>
    <div class="col-xs-6 text-center">
             <p class="center-block"><span class="btn btn-danger btn-lg">No</span></p>
       <p class="btn center-block"><span class="glyphicon glyphicon-arrow-down"></span></p>
      <p class="btn bg-danger text-danger text-wrap">The data must be in the system to use this service.</p>
    </div>
      </div>
	</div>
	  <script>
	  function myFunctionBN1() {
		document.getElementById("buttonYes1").style="display: none";
		document.getElementById("buttonNo1").style="display";
  		}
	  </script>
    </div>
  </div>
</div>
<div class="container">
  <h2 class="page-header">Step 2: What type of email is it?</h2>
  <div class="row">
    <div class="col-xs-12">
  <p class="lead text-center bg-info btn text-info center-block">What type of email do you want to send?</p>
      <div class="row">
        <div class="col-xs-6 text-center">
           <p class="btn"><span class="glyphicon glyphicon-arrow-down"></span>
        </div>
        <div class="col-xs-6 text-center">
          <p class="btn">
          <span class="glyphicon glyphicon-arrow-down"></span></p>
        </div>
      </div>
      <div class="row">
        <div class="col-xs-6 text-center">
              <p class="center-block"><span class="btn btn-warning btn-lg">Newsletter</span></p>
          <p class="btn center-block"><span class="glyphicon glyphicon-arrow-down"></span></p>
            <p class="center-block bg-info text-info btn">Is it directly related to fundraising?</p>
      <div class="row">
        <div class="col-xs-6 text-center">
           <p class="btn"><span class="glyphicon glyphicon-arrow-down"></span>
        </div>
        <div class="col-xs-6 text-center">
          <p class="btn">
          <span class="glyphicon glyphicon-arrow-down"></span></p>
        </div>
      </div>
      <div class="row">
    <div class="col-xs-6">
    <p class="center-block"><span class="btn btn-success btn-lg">Yes</span></p>
          <p class="btn">
          <span class="glyphicon glyphicon-arrow-down"></span></p>
      <p class="bg-success text-success btn text-wrap">Okay! You can proceed to step 3. </p>
      
    </div>
    <div class="col-xs-6 text-center">
             <p class="center-block"><span class="btn btn-danger btn-lg">No</span></p>
       <p class="btn center-block"><span class="glyphicon glyphicon-arrow-down"></span></p>
      <p class="btn bg-danger text-danger text-wrap">Content must be directly related to fundraising to use this service.</p>
    </div>
      </div>
        </div>
        <div class="col-xs-6 text-center">
              <p class="center-block"><span class="btn btn-success btn-lg">Solicitation</span></p>
           <p class="btn center-block"><span class="glyphicon glyphicon-arrow-down"></span></p>
      
      <p class="bg-success text-success btn">Okay! Proceed to step 3.</p>
    </div>
        </div>
          
    </div>
  </div>
</div>

<footer>
  <div class="container">
  <hr>
  <p>Footer information here. For more questions please call the person that you know to call with your questions. </p>
  </div>
</footer>
