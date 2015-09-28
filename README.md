# COMP422-TripNotes

 Add the following modifications to this app
•	update the app's design so the footer bar is always rendered at the foot of the screen
  o	fixed by adding:  data-position="fixed" to footer tags

•	add a new page container, and link to it from the home screen (page1) with a pop transition
<!-- Italian Cities -->
            <ul data-role="listview" data-inset="true">
	<li data-role="list-divider" role="heading">Italian Cities</li>
	  <li>
	    <a href="#page4" data-transition="pop">
	      <h3>Rome</h3>
	      <p><strong>Principality of Rome</strong></p>
	      <p>Rome is the capital of Italy and of the Lazio region. With 2.9 million residents in 1,285 km2 (496.1 sq mi), it is also the country's largest and most populated comune...</p>
	      <p class="ui-li-aside"><strong>1</strong> image</p>
	    </a>
	  </li>
	</ul>
 <!-- End of Italian Cities -->

•	add a new list item to the list on the home screen (page1) for this new link
<!-- page4 -->
	<div data-role="page" id="page4">
		<div data-role="header">
	    <h3>page 4</h3>
		</div><!-- /header -->
		<div role="main" class="ui-content">
			<p><a data-rel="back" class="ui-btn">Return</a></p>
		<section class="image-view">
			<img src="media/images/rome1.jpg">
		<section>
		</div><!-- /content -->
		<div data-role="footer" data-position="fixed">
                		<h5>footer - page 4</h5>
		</div><!-- /footer -->
</div><!-- /page4 -->

•	send this updated code to the course' TA, Tyler Bobella, by the start of the next class
o	either a link to the code on GitHub or Bitbucket
o	or shared via a storage service such as Drive, Dropbox, Box, or OneDrive
o	or a zipped file attached to an email

