# freecodecamp
survey form project 
Solution for Build a Survey Form
HTML
<!DOCTYPE html>
<head>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <h1 id="title">Title</h1>
  <p id="description">paragraph</p>
  <form id="survey-form">
    <label id="name-label">Name
<input placeholder="Enter your name" required id="name" type="text"></input>
</label>
    <label id="email-label">Email
 <input placeholder="Enter your email" required id="email" type="email"></input>
 </label>
 <label id="number-label">Age
<input placeholder="Age" id="number" type='number' min="0" max="10"></input>
</label>

<select id="dropdown">
  <option>Option 1</option>
  <option>Option 2</option>
</select>


  <input value="test1" name='test' type='radio' /                >
  <input value="test2" name='test' type='radio' /                >
<input type="checkbox" value="checkbox1"/>
<input type="checkbox" value="checkbox2"/>
<input type="checkbox" value="checkbox3"/>

<textarea type="textarea"></textarea>

<button id="submit">Submit</button>

  </form>
</body>


CSS
* {

  background-color: green;
}
