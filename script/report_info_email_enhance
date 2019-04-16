<!--
Author: 		Joe K
Version Date:	2019/02/15 v1
Description:

Adds the report # to the subject line of the DataHelp email link. Intended for any screens with the report info text.

ASSUMPTIONS: 	1) There is an HTML object with a tag directly to the *right* of the report number in the header area, 
				and the tag's ID='reportNumber'.

				2) There is a tag with ID='emailLink' on the page, and the tag can accept an 'href' parameter.
-->

<script>

	//grab user-defined report number di_Report_Number via custom HTML target
	var num = document.getElementById("reportNumber").previousElementSibling.innerText;
	
	//grab the custom email link HTML object
	var emailLink = document.getElementById("emailLink");

	//define the href text
	var text = ("mailto:DataHelp@uff.ufl.edu?subject=AP Report Support - Report # " + num) 

	//set the subject line
	emailLink.href = (text);

	//ensure that the actual text rendered to the user is the email address
	emailLink.innerText = "DataHelp@uff.ufl.edu"

</script>
