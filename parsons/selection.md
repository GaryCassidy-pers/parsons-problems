---
title: Python Fundamentals 2
---
<h1>1. Input and Output - 1</h1>
<div id="gary1-sortableTrash" class="sortable-code"></div> 
<div id="gary1-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="gary1-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="gary1-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "print(&quot;Hello, World!&quot;)\n" +
    "print(&quot;Welcome to Python!&quot;)\n" +
    "print(Hello) #distractor";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "gary1-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true,
    "trashId": "gary1-sortableTrash"
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

<h1>2. Input and Output - 2</h1>
<div id="gary2-sortableTrash" class="sortable-code"></div> 
<div id="gary2-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="gary2-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="gary2-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "name = input(&quot;What is your name? &quot;)\n" +
    "print(&quot;Nice to meet you, &quot; + name + &quot;!&quot;)\n" +
    "print(&quot;Enter your age:&quot;) #distractor";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "gary2-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true,
    "trashId": "gary2-sortableTrash"
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

<h1>3. Input and Output - 3</h1>
<div id="gary3-sortableTrash" class="sortable-code"></div> 
<div id="gary3-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="gary3-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="gary3-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "num = input(&quot;Enter a number: &quot;)\n" +
    "print(&quot;You entered: &quot; + num)\n" +
    "print(num + 5) #distractor";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "gary3-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true,
    "trashId": "gary3-sortableTrash"
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

<h1>4. Input and Output - 4</h1>
<div id="gary4-sortableTrash" class="sortable-code"></div> 
<div id="gary4-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="gary4-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="gary4-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "age = input(&quot;How old are you? &quot;)\n" +
    "print(&quot;You are &quot; + age + &quot; years old.&quot;)\n" +
    "print(Your age is: age) #distractor";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "gary4-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true,
    "trashId": "gary4-sortableTrash"
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

<h1>5. Input and Output - 5</h1>
<div id="gary5-sortableTrash" class="sortable-code"></div> 
<div id="gary5-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="gary5-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="gary5-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "color = input(&quot;What is your favorite color? &quot;)\n" +
    "print(&quot;Wow! &quot; + color + &quot; is a great color!&quot;)\n" +
    "print(&quot;Your color is cool&quot;) #distractor";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "gary5-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true,
    "trashId": "gary5-sortableTrash"
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

<h1>6. Arithmetic Operators - 1</h1>
<div id="gary6-sortableTrash" class="sortable-code"></div> 
<div id="gary6-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="gary6-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="gary6-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "a = int(input(&quot;Enter first number: &quot;))\n" +
    "b = int(input(&quot;Enter second number: &quot;))\n" +
    "print(&quot;Sum:&quot;, a + b)\n" +
    "print(a plus b) #distractor";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "gary6-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true,
    "trashId": "gary6-sortableTrash"
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

<h1>7. Arithmetic Operators - 2</h1>
<div id="gary7-sortableTrash" class="sortable-code"></div> 
<div id="gary7-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="gary7-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="gary7-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "x = 10\n" +
    "y = 3\n" +
    "result = x // y\n" +
    "print(&quot;Integer division result:&quot;, result)\n" +
    "print(x divided by y) #distractor";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "gary7-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true,
    "trashId": "gary7-sortableTrash"
  });
  parsonsPuzzle.init(initial);
  parsonsPuzzle.shuffleLines();
  $("#gary7-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#gary7-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

<h1>8. Arithmetic Operators - 3</h1>
<div id="gary8-sortableTrash" class="sortable-code"></div> 
<div id="gary8-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="gary8-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="gary8-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "num = 5\n" +
    "square = num ** 2\n" +
    "print(&quot;Square:&quot;, square)\n" +
    "print(num * num) #distractor";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "gary8-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true,
    "trashId": "gary8-sortableTrash"
  });
  parsonsPuzzle.init(initial);
  parsonsPuzzle.shuffleLines();
  $("#gary8-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#gary8-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

<h1>9. Arithmetic Operators - 4</h1>
<div id="gary9-sortableTrash" class="sortable-code"></div> 
<div id="gary9-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="gary9-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="gary9-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "n = 15\n" +
    "mod_result = n % 4\n" +
    "print(&quot;Remainder:&quot;, mod_result)\n" +
    "print(n mod 4) #distractor";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "gary9-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true,
    "trashId": "gary9-sortableTrash"
  });
  parsonsPuzzle.init(initial);
  parsonsPuzzle.shuffleLines();
  $("#gary9-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#gary9-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

<h1>10. Arithmetic Operators - 5</h1>
<div id="gary10-sortableTrash" class="sortable-code"></div> 
<div id="gary10-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="gary10-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="gary10-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "length = 7\n" +
    "width = 4\n" +
    "area = length * width\n" +
    "print(&quot;Area:&quot;, area)\n" +
    "print(length times width) #distractor";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "gary10-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true,
    "trashId": "gary10-sortableTrash"
  });
  parsonsPuzzle.init(initial);
  parsonsPuzzle.shuffleLines();
  $("#gary10-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#gary10-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

<h1>11. Logical Expressions - 1</h1>
<div id="gary11-sortableTrash" class="sortable-code"></div> 
<div id="gary11-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="gary11-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="gary11-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "age = 18\n" +
    "if age >= 18:\n" +
    "    print(&quot;You can vote.&quot;)\n" +
    "print(&quot;You are a child&quot;) #distractor";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "gary11-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true,
    "trashId": "gary11-sortableTrash"
  });
  parsonsPuzzle.init(initial);
  parsonsPuzzle.shuffleLines();
  $("#gary11-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#gary11-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

<h1>12. Logical Expression - 2</h1>
<div id="gary12-sortableTrash" class="sortable-code"></div> 
<div id="gary12-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="gary12-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="gary12-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "num = 10\n" +
    "if num % 2 == 0:\n" +
    "    print(&quot;Even number&quot;)\n" +
    "print(&quot;Odd number&quot;) #distractor";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "gary12-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true,
    "trashId": "gary12-sortableTrash"
  });
  parsonsPuzzle.init(initial);
  parsonsPuzzle.shuffleLines();
  $("#gary12-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#gary12-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

<h1>13. Logical Expression - 3</h1>
<div id="gary13-sortableTrash" class="sortable-code"></div> 
<div id="gary13-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="gary13-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="gary13-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "temperature = 25\n" +
    "if temperature > 30:\n" +
    "    print(&quot;It is hot.&quot;)\n" +
    "elif temperature < 10:\n" +
    "    print(&quot;It is cold.&quot;)\n" +
    "else:\n" +
    "    print(&quot;It is moderate.&quot;)\n" +
    "print(&quot;Check weather&quot;) #distractor";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "gary13-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true,
    "trashId": "gary13-sortableTrash"
  });
  parsonsPuzzle.init(initial);
  parsonsPuzzle.shuffleLines();
  $("#gary13-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#gary13-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

<h1>14. Logical Expression - 4</h1>
<div id="gary14-sortableTrash" class="sortable-code"></div> 
<div id="gary14-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="gary14-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="gary14-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "x = 5\n" +
    "y = 10\n" +
    "if x < y and y > 5:\n" +
    "    print(&quot;Both conditions are true&quot;)\n" +
    "print(&quot;At least one is false&quot;) #distractor";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "gary14-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true,
    "trashId": "gary14-sortableTrash"
  });
  parsonsPuzzle.init(initial);
  parsonsPuzzle.shuffleLines();
  $("#gary14-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#gary14-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

<h1>15. Logical Expression - 5</h1>
<div id="gary15-sortableTrash" class="sortable-code"></div> 
<div id="gary15-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="gary15-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="gary15-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "num = input(&quot;Enter a number:&quot;)\n" +
    "b = False\n" +
    "if (num != 10):\n" +
    "    print(&quot;b is False&quot;)\n" +
    "print(&quot;Your number is 10&quot;) #distractor" + 
    "if (num not 10) #distractor";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "gary15-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true,
    "trashId": "gary15-sortableTrash"
  });
  parsonsPuzzle.init(initial);
  parsonsPuzzle.shuffleLines();
  $("#gary15-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#gary15-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

<h1>16. Selection - 1</h1>
<div id="gary16-sortableTrash" class="sortable-code"></div> 
<div id="gary16-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="gary16-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="gary16-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "score = int(input(&quot;Enter your score: &quot;))\n" +
    "if score >= 50:\n" +
    "    print(&quot;You passed!&quot;)\n" +
    "else:\n" +
    "    print(&quot;You failed.&quot;)\n" +
    "elif: #distractor";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "gary16-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true,
    "trashId": "gary16-sortableTrash"
  });
  parsonsPuzzle.init(initial);
  parsonsPuzzle.shuffleLines();
  $("#gary16-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#gary16-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

<h1>17. Selection - 2</h1>
<div id="gary17-sortableTrash" class="sortable-code"></div> 
<div id="gary17-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="gary17-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="gary17-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "x = input(&quot;Enter a number:&quot;)\n" +
    "if x == 1:\n" +
    "    print(&quot;One&quot;)\n" +
    "elif x == 2:\n" +
    "    print(&quot;Two&quot;)\n" +
    "else:\n" +
    "    print(&quot;Your number is not recognised&quot;)\n" +
    "print(x is three) #distractor";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "gary17-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true,
    "trashId": "gary17-sortableTrash"
  });
  parsonsPuzzle.init(initial);
  parsonsPuzzle.shuffleLines();
  $("#gary17-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#gary17-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

<h1>18. Selection - 3</h1>
<div id="gary18-sortableTrash" class="sortable-code"></div> 
<div id="gary18-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="gary18-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="gary18-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "password = input(&quot;Enter password: &quot;)\n" +
    "if password == &quot;secure123&quot;:\n" +
    "    print(&quot;Access granted&quot;)\n" +
    "else:\n" +
    "    print(&quot;Access denied&quot;)\n" +
    ""if password = &quot;password123&quot;: #distractor";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "gary18-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true,
    "trashId": "gary18-sortableTrash"
  });
  parsonsPuzzle.init(initial);
  parsonsPuzzle.shuffleLines();
  $("#gary18-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#gary18-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

<h1>19. Selection - 4</h1>
<div id="gary19-sortableTrash" class="sortable-code"></div> 
<div id="gary19-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="gary19-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="gary19-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "height = int(input(&quot;Enter your height in cm: &quot;))\n" +
    "if height >= 120:\n" +
    "    print(&quot;You can ride the roller coaster!&quot;)\n" +
    "else:\n" +
    "    print(&quot;Sorry, you are too short.&quot;)\n" +
    "print(&quot;Height checked&quot;) #distractor";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "gary19-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true,
    "trashId": "gary19-sortableTrash"
  });
  parsonsPuzzle.init(initial);
  parsonsPuzzle.shuffleLines();
  $("#gary19-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#gary19-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

<h1>20. Selection - 5</h1>
<div id="gary20-sortableTrash" class="sortable-code"></div> 
<div id="gary20-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="gary20-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="gary20-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var puzzlenum = 20;
  var initial = "age = int(input(&quot;Enter age: &quot;))\n" +
    "if age < 13:\n" +
    "    print(&quot;Child&quot;)\n" +
    "elif age < 18:\n" +
    "    print(&quot;Teenager&quot;)\n" +
    "else:\n" +
    "    print(&quot;Adult&quot;)\n" +
    "print(&quot;Age group determined&quot;) #distractor";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "gary" + puzzlenum + "-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true,
    "trashId": "gary20-sortableTrash"
  });
  parsonsPuzzle.init(initial);
  parsonsPuzzle.shuffleLines();
  $("#gary" + puzzlenum + "-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#gary" + puzzlenum + "-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>
