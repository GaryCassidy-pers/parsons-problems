---
title: Inputs and Data Types
---
<h1>1. Basic Input and Output</h1>
<div id="gary1-sortableTrash" class="sortable-code"></div> 
<div id="gary1-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="gary1-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="gary1-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "name = input(&quot;What is your name? &quot;)\n" +
    "print(&quot;Hello, &quot; + name + &quot;!&quot;)";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "gary1-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true
  });
  parsonsPuzzle.init(initial);
  parsonsPuzzle.shuffleLines();
  $("#gary1-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#gary1-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

<h1>2. Converting Input to an Integer</h1>
<div id="gary2-sortableTrash" class="sortable-code"></div> 
<div id="gary2-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="gary2-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="gary2-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "number = int(input(&quot;Enter a number: &quot;))\n" +
    "print(&quot;Double of your number is:&quot;, number * 2)";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "gary2-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true
  });
  parsonsPuzzle.init(initial);
  parsonsPuzzle.shuffleLines();
  $("#gary2-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#gary2-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

<h1>3. Int Conversion and Arithmetic</h1>
<div id="gary4-sortableTrash" class="sortable-code"></div> 
<div id="gary4-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="gary4-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="gary4-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "num1 = float(input(&quot;Enter the first number: &quot;))\n" +
    "num2 = int(input(&quot;Enter the second number: &quot;))\n" +
    "print(&quot;The sum is:&quot;, num1 + num2)";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "gary4-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true
  });
  parsonsPuzzle.init(initial);
  parsonsPuzzle.shuffleLines();
  $("#gary4-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#gary4-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

<h1>4. String Formatting with Inputs</h1>
<div id="gary5-sortableTrash" class="sortable-code"></div> 
<div id="gary5-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="gary5-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="gary5-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "name = input(&quot;First enter your name: &quot;)\n" +
    "age = int(input(&quot;Now enter your age: &quot;))\n" +
    "print(&quot;Hello &quot; + name + &quot;, you are &quot; + age + &quot; years old.&quot;)";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "gary5-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true
  });
  parsonsPuzzle.init(initial);
  parsonsPuzzle.shuffleLines();
  $("#gary5-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#gary5-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

<h1>5. Asking for Multiple User Inputs and Displaying Results</h1>
<div id="gary3-sortableTrash" class="sortable-code"></div> 
<div id="gary3-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="gary3-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="gary3-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "print(&quot;Calculate the area of a rectangle&quot;)\n" +
    "length = float(input(&quot;Enter the length: &quot;))\n" +
    "width = float(input(&quot;Enter the width: &quot;))\n" +
    "area = length * width\n" +
    "print(&quot;The area is:&quot;, area)"
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "gary3-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true
  });
  parsonsPuzzle.init(initial);
  parsonsPuzzle.shuffleLines();
  $("#gary3-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#gary3-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

<h1>6. Full Name Input and Display</h1>
<div id="gary6-sortableTrash" class="sortable-code"></div> 
<div id="gary6-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="gary6-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="gary6-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "first_name = input(&quot;Enter your first name: &quot;)\n" +
    "last_name = input(&quot;Enter your last name: &quot;)\n" +
    "full_name = first_name + &quot; &quot; + last_name\n" +
    "print(&quot;Your full name is:&quot;, full_name)"
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "gary6-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true
  });
  parsonsPuzzle.init(initial);
  parsonsPuzzle.shuffleLines();
  $("#gary6-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#gary6-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>
