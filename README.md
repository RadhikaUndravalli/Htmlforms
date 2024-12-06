# Htmlforms
#I build basic html form while learning
<!DOCTYPE html>
<html>
  <head>
    <title>Survey Form</title>
    <link rel="stylesheet" href="style.css">
      </head>
<body>
<h1 id="title"> Survey Form</h1>
<p id="description">Thank you for taking the time to fill the form.</p>
<form id="survey-form">
  <label for="name" id="name-label">Name</label>
  <input id="name" type="text" placeholder="Enter your name" required></input><br>
  <label for="email" id="email-label">Email</label>
  <input id="email" type="email" placeholder="Enter your Email" required></input><br>
  <label for="number" id="number-label">Age</label>
  <input id="number" type="number" min="10" max="99" placeholder="Age"></input><br>
  <label for="dropdown">Which option best describes your current role?</label>
  <select id="dropdown">
    <option value="" disabled selected>Select current role</option>
<option value="Student">Student</option>
<option value="Full Time JOb">Full Time Job</option>
<option value="Full Time Learner">Full Time Learner</option>
<option value="Prefer Not to Say">Prefer Not to Say</option>
<option value="Other">Other</option>
  </select><br>
<label>Would you recommend freeCodeCamp to a friend?</label><br>
<input type="radio" id="definitely" name="radiobutton" value="Definitely"></input>
<label for="definitely">Definitely</label><br>
<input type="radio" id="maybe" name="radiobutton" value="Maybe"></input>
<label for="maybe">Maybe</label><br>
<input type="radio" id="notsure" name="radiobutton" value="Not Sure"></input>
<label for="notsure">Not Sure</label><br>
<label for="drop">What is your favorite feature of freeCodeCamp?</label><br>
<select id="drop">
  <option value="" disabled selected>Select an option</option>
  <option value="Challenges">Challenges</option>
  <option value="Projects">Projects</option>
  <option value="Community">Community</option>
  <option value="Open source">Open Source</option>
</select><br>
<label for="checkbox">What would you like to see improved? (Check all that apply)</label><br>
<input type="checkbox" id="Front-end Projects" name="check" value="Front-end Projects"></input>
<label for="Front-end Projects">Front-end Projects</label><br>
<input type="checkbox" id="checkbox" name="check" value="Back-end Projects"></input>
<label for="Back-end Projects">Back-end Projects</label><br>
<input type="checkbox" id="Data Visualization" name="check" value="Data Visualization"></input>
<label for="Data Visualization">Data Visualization</label><br>
<input type="checkbox" id="Challenges" name="check" value="Challenges"></input>
<label for="Challenges">Challenges</label><br>
<input type="checkbox" id="Open Source Community" name="check" value="Open Source Community"></input>
<label for="Open Source Community">Open Source Community</label><br>
<input type="checkbox" id="Gitter help rooms" name="check" value="Gitter help rooms"></input>
<label for="Gitter help rooms">Gitter help rooms</label><br>
<input type="checkbox" id="Videos" name="check" value="Videos"></input>
<label for="Videos">Videos</label><br>
<input type="checkbox" id="City Meetups" name="check" value="City Meetups"></input>
<label for="City Meetups">City Meetups</label><br>
<input type="checkbox" id="Wiki" name="check" value="Wiki"></input>
<label for="Wiki">Wiki</label><br>
<input type="checkbox" id="Forum" name="check" value="Forum"></input>
<label for="Forum">Forum</label><br>
<input type="checkbox" id="Additional Courses" name="check" value="Additional Courses"></input>
<label for="Additional Courses">Additional Courses</label><br>
<label for="text">Any comments or suggestions?</label><br>
<textarea id="text" name="textarea" placeholder="Enter your comment here..."></textarea><br>
<button type="submit" id="submit">Submit</button>

</form>
</body>
</html>
