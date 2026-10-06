# Registration-form
Create Registration form using HTML,CSS in Anudip

Problem Statement
A college wants to develop a Student Registration Form using HTML and CSS to collect the following student details:
•	Student ID
•	Student Name
•	Email Address
•	Mobile Number
•	Course
•	Date of Birth
The form should validate the information before allowing the student to submit the registration

Approach to the Problem
1.	Create the HTML structure: Use the <form> tag to create the registration form.
2.	Add input fields: Use <input> for Student ID, Name, Email, Mobile Number, and Date of Birth.
3.	Add a course dropdown: Use <select> and <option> to allow students to choose their course.
4.	Apply validation: Use HTML attributes such as required, type="email", type="date", minlength, maxlength, and pattern.
5.	Style using CSS: Use colors, padding, margins, borders, and a clean layout to make the form attractive. We use the external CSS here
6.	Add buttons: Use Submit and Reset buttons to submit the form or clear the entered information.

Validation :

Field	          HTML validation	          Purpose
Student ID      required, pattern	        Requires 3–15 letters or numbers
Student Name	  required, pattern	        Allows 3–50 letters and spaces
Email	          type="email", required	  Checks basic email format
Mobile	        type="tel", pattern	      Requires a 10-digit Indian mobile number starting with 6–9
Course	        required	                Requires the student to select a course
Date of Birth 	type="date", required	    Requires a date to be selected

HTML tags and attributes for each column : 

Field 	          HTML tag	            Attributes used	                            Purpose
Student ID	      <input>	              type="text", id, name, required, pattern	Accepts a unique student ID in the required format
Student Name	    <input>	              type="text", id, name, required, pattern	Accepts the student's name
Email          	  <input>	              type="email", id, name, required	        Checks the basic email format
Mobile Number	    <input>       	      type="tel", id, name, required, pattern	  Accepts a 10-digit Indian mobile number
Course	          <select>,<option>	    id, name, required, value	                Allows the student to select a course
Date of Birth	    <input>	              type="date", id, name, required	          Allows the student to select a date
Field Labels	    <label>          	    for	                                      Identifies each input field
Form          	  <form>	              action, method	                          Groups fields and defines where and how the form is submitted
Register Button	  <button>	            type="submit"	                            Submits the form after browser validation
Reset Button	    <button>	            type="reset"	                            Resets the fields to their initial values
Form Container	  <div>	                class	                                    Groups form elements for CSS styling








CSS selectors and properties :

 CSS code        	Explanation	                                     Purpose
 body	            Selects the entire webpage body.	               Applies the background color to the page.
 .container	      Selects an element with class="container".	     Styles the registration form container.
 h2	              Selects all level-two headings.	                 Styles the Student Registration heading.
 label	          Selects all <label> elements.	                   Styles Student ID, Name, Email, etc.
 input, select	  Selects all input fields and dropdowns.	         Applies common styles to form fields.
 button	          Selects all buttons.	                           Styles Register and Reset buttons.
 .reset-btn	      Selects an element with class="reset-btn".	     Gives the Reset button a different background color.


CSS properties used :

CSS property	         Meaning
font-family	           Specifies the font style.
background-color	     Sets the background color.
text-align	           Aligns text horizontally.
width	                 Sets the element's width.
border	               Adds a border around an element.
border-radius        	 Rounds the corners of an element.
color	                 Sets the text color.
font-weight	           Controls the thickness of text.
border-color	         Sets the border color separately.


