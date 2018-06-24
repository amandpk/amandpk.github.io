---
layout: page
title: Resume
description: Resume of Amandeep Kaur
---

Total of six years of backend operator experience in IBM and Mercer.
Good knowledge of working in health industry.
Good interpersonal and communication skills and a team player.

<!-- Skills -->
<section class="row">
	<header class="col-md-3">
		<h3 style="text-transform:uppercase;color:gray; margin-top:21px; margin-bottom:10.5px">Skills</h3>
	</header>
	<div class="col-md-9">
		<div class="row">
			<div class="col-md-6">
				<ul class="list-group">
					<li class="list-group-item active"><h4 style="margin-top:10.5px; margin-bottom:10.5px"><strong>Main</strong></h4></li>
					<li class="list-group-item">MS Office</li>
					<li class="list-group-item">SQL</li>
					<li class="list-group-item">English: Fluent professional level -> <a href="{{ site.url_ielts_marksheet_2018 }}" title="IELTS General 2018 marksheet">IELTS</a> </li>
					<li class="list-group-item">Windows OS</li>
					<li class="list-group-item"></li>
				</ul>
			</div>
			<div class="col-md-6">
				<ul class="list-group">
					<li class="list-group-item active"><h4 style="margin-top:10.5px; margin-bottom:10.5px"><strong>Others</strong></h4></li>
					<li class="list-group-item">Hindi & Punjabi: Native</li>
					<li class="list-group-item">Good team player</li>
					<li class="list-group-item">Problem solver</li>
					<li class="list-group-item">Decision maker</li>
				</ul>
			</div>
		</div>
	</div>
</section>
<hr style="margin-top:21px; margin-bottom:21px" />
<!-- Education -->
<section class="row">
	<header class="col-md-3">
		<h3 style="text-transform:uppercase;color:gray; margin-top:21px; margin-bottom:10.5px">Education</h3>
	</header>
	<div class="col-md-9">
		<ul style="padding-left: 40px; margin-bottom: 10.5px">
			<li>
				<h4 style="margin-top:10.5px; margin-bottom:10.5px">IELTS General 2018 bands - Appeared in Aug-2018 <a href="{{ site.url_ielts_marksheet_2018 }}" title="IELTS General 2018 marksheet"><span class="glyphicon glyphicon-book"></span></a></h4>
				<h5 style="margin-top:10.5px; margin-bottom:10.5px">Reading: </h5>
				<h5 style="margin-top:10.5px; margin-bottom:10.5px">Listening: </h5>
				<h5 style="margin-top:10.5px; margin-bottom:10.5px">Writing: </h5>
				<h5 style="margin-top:10.5px; margin-bottom:10.5px">Speaking: </h5>
			</li>
			<li>
				<h4 style="margin-top:10.5px; margin-bottom:10.5px">Bachelor of Commerce (B.Com.) - Business studies and Accounts <a href="{{ site.url_courses_bachelors }}" title="Relevant courses undertaken during Bachelors"><span class="glyphicon glyphicon-book"></span></a></h4>
				<h5 style="margin-top:10.5px; margin-bottom:10.5px">Amongst top 10 in the college</h5>
				<p style="margin-bottom:10.5px">2008 - 2011 . <a href="http://www.mjpru.ac.in/" target="_blank">MJP Rohilkhand University Bareilly, India</a></p>
			</li>
			<li>
				<h4 style="margin-top:10.5px; margin-bottom:10.5px">GNIIT <a href="{{ site.url_courses_niit }}" title="Relevant courses undertaken during GNIIT"><span class="glyphicon glyphicon-book"></span></a></h4>
				<p style="margin-bottom:10.5px">2008 - 2011 . <a href="http://www.niit.com/en/" target="_blank">National Institute of Information Technology (NIIT Limited) New Delhi, India</a></p>
			</li>
		</ul>
	</div>
</section>
<hr style="margin-top:21px; margin-bottom:21px" />
<!-- Online Courses -->
<section class="row">
	<header class="col-md-3">
		<h3 style="text-transform:uppercase;color:gray; margin-top:21px; margin-bottom:10.5px">Online Courses</h3>
	</header>
	<div class="col-md-9">
		<ul style="padding-left: 40px; margin-bottom: 10.5px">
			<li>
				<h4 style="margin-top:10.5px; margin-bottom:10.5px">See full list and certificates <a href="{{ site.url_courses_online }}">here &rarr;</a></h4>
			</li>
		</ul>
	</div>
</section>
<!-- Work -->
<!-- section class="row">
	<header class="col-md-3">
		<h3 style="text-transform:uppercase;color:gray; margin-top:21px; margin-bottom:10.5px">Work Experience</h3>
	</header>
	<div class="col-md-9">
		<ul style="padding-left: 40px; margin-bottom: 10.5px">
			<li>
				<h4 style="margin-top:10.5px; margin-bottom:10.5px">ABC company</h4>
				<h5 style="margin-top:10.5px; margin-bottom:10.5px">May 1000 - March 1000</h5>
				<p style="margin-bottom:10.5px">Worked as Web Developer with ABC team</p>
			</li>
		</ul>
	</div>
</section -->


<script>
$(document).ready(function(){
	$("#full_resume").mouseover(function(){
		$("#resume_envelope").addClass("glyphicon-send").removeClass("glyphicon-envelope");
	});
	$("#full_resume").mouseout(function(){
		$("#resume_envelope").addClass("glyphicon-envelope").removeClass("glyphicon-send");
	});
});

$(document).ready(function() {
	$('.click_apar').click(function() {
		$('#desc_master_thesis').slideToggle("fast");
		$('#desc_idp').slideToggle("fast");
		$('#desc_si2011').slideToggle("fast");
	});
	$('.click_apar').mouseover(function() {
		$('.apar_up').addClass("glyphicon-triangle-bottom").removeClass("glyphicon-triangle-top");
	});
	$('.click_apar').mouseout(function() {
		$('.apar_up').addClass("glyphicon-triangle-top").removeClass("glyphicon-triangle-bottom");
	});
});
</script>
