# Reel-Foundation-survey-Form
To get feedback from participant
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>Survey Form</title>
  </head>
<h1 id="title"> REEL FOUNDATION  SURVEY FORM </h1>
<body>
  <p id="description"> This survey is to help us get your feedback on our service.</p>
<form id="survey-form"> 
 <fieldset> 
  <legend> Personal Information</legend>
  <label for="name" id="name-label"> Full Name: </label>
 <input id="name" type="text" required placeholder="e.g Johh Doe">  
 </input>
 </fieldset>

 <fieldset> <label for="email" id="email-label"> E-mail</label>
 <input id="email" type="email" required placeholder="e.g agsjjrb@email.com"> </input> </fieldset>

 <fieldset> <label for="number" id="number-label"> Phone Number <input id="number" type="number" min="11" max="11" placeholder ="e.g 08027855698" > </input>
 </fieldset> 

 <fieldset>
 <label for="option" id="option"> Have you attended any program organized by REEL Foundation? </label>
 <select id="dropdown"> 
  <option type="radio" id="yes-option"> Yes</option>
  <option type="radio" id="No-option"> No</option></select> </fieldset>
  
 <fieldset>
  <legend>Ratings</legend>
 <label for="program" id="program"> Which of the program have you attended? Select & Rate:</label></br></fieldset>

 <fieldset>
 <input type="checkbox" id="program" value="rating"> Agbado Spelling Bee Competition</input></br></fieldset>
 <fieldset>
 <input id="satisfactory" value="satisfactory" type="checkbox"> Satisfactory<input id="poor" value="poor" type="checkbox">Poor </input>
 </input><input id="very-good" value="very-good" type="checkbox"> Very Good</input><input id="good" value="good" type="checkbox"> Good</input><input id="excellent" value="excellent" type="checkbox"> Excellent</input>
 </fieldset>

 <fieldset>
 <input type="checkbox"id="program"value="program"> Ultimate Mind Challenge, Magboro</input></br></fieldset>
 <fieldset>
  <input id="satisfactory" value="satisfactory" type="checkbox"> Satisfactory</input>
  <input id="poor" value="poor" type="checkbox">Poor </input>
  <input id="very-good" value="very-good" type="checkbox" value="verygood"> Very Good</input>
  <input id="good" value="good" type="checkbox"> Good</input>
  <input id="excellent" value="excellent" type="checkbox"> Excellent</input>
  
   </fieldset>
 <fieldset> 
    <input type="checkbox" id="program"value="program"> Iyabo Osinuga Tournament, Ikorodu </input></fieldset>
    <fieldset>
    <input id="satisfactory" value="satisfactory" type="checkbox"> Satisfactory</input>
    
<input id="satisfactory" value="satisfactory" type="checkbox"> Satisfactory</input>
<input id="poor" value="poor" type="checkbox">Poor </input>
<input id="very-good" value="very-good" type="checkbox"> Very Good</input>
<input id="good" value="good" type="checkbox"> Good</input>
<input id="excellent" value="excellent" type="checkbox"> Excellent</input></fieldset>

<fieldset>
  <label for="attend" id="attend"> I will attend the next program.</br>
<input type="radio" value="yes"name="yes"> Yes</input>
<input type="radio" value="no" name="no"> No </input>
</fieldset>
<fieldset>
  <label for="volunteer" id="volunteer"> Will you like to be a volunteer for our next event?</label>
  <input type="radio" value="yes" name="yes"> Yes</input>
<input type="radio" value="no" name="no">No</input></fieldset>

<fieldset><legend> Additional information</legend> <textarea> </textarea>
</fieldset>
<button id="submit" type="submit"> Submit</button>

</form>
  </body>
</html>
