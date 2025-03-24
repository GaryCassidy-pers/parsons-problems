---
title: Python Fundamentals 2
---
<h2>Drag or shuffle the blocks of code in the practice problems below. Remember to indent where appropriate by dragging blocks to the right.
To check your work, press the "Get Feedback" button. To start over, press the "Reset Problem" button.</h2>
<h1>Iteration</h1>
<h1>1</h1>
<p>Counting down from 5 to 1</p>
<div id="gary1-sortableTrash" class="sortable-code"></div> 
<div id="gary1-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="gary1-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="gary1-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var puzzlenum = 1;
  var initial = "num = 5\n" +
    "while num > 0:\n" +
    "    print(num)\n" +
    "    num -= 1\n" +
    "print(\"Blast off!\")\n" +
    "num == 0 #distractor\n" +
    "print num #distractor";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "gary" + puzzlenum + "-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true,
    "trashId": "gary" + puzzlenum + "-sortableTrash"
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

<h1>2</h1>
<p>Keep asking for a number until user enters 0</p>
<div id="gary2-sortableTrash" class="sortable-code"></div> 
<div id="gary2-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="gary2-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="gary2-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var puzzlenum = 2;
  var initial =
    "num = int(input(\"Enter a number: \"))\n" +
    "while num != 0:\n" +
    "    print(\"You entered:\", num)\n" +
    "    num = int(input(\"Enter a number: \"))\n" +
    "if num > 0: #distractor\n" +
    "print(\"Loop ended\")\n" +
    "while num = 0 #distractor";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "gary" + puzzlenum + "-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true,
    "trashId": "gary" + puzzlenum + "-sortableTrash"
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

<h1>3</h1>
<p>Repeating password input until correct</p>
<div id="gary3-sortableTrash" class="sortable-code"></div> 
<div id="gary3-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="gary3-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="gary3-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var puzzlenum = 3;
  var initial =
    "password = \"python123\"\n" +
    "guess = input(\"Enter password: \")\n" +
    "while guess != password:\n" +
    "    print(\"Wrong password. Try again.\")\n" +
    "    guess = input(\"Enter password: \")\n" +
    "print(\"Access granted!\")\n" +
    "while guess = password: #distractor\n" +
    "print(\"Wrong password\") #distractor";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "gary" + puzzlenum + "-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true,
    "trashId": "gary" + puzzlenum + "-sortableTrash"
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

<h1>4</h1>
<p>Printing even numbers up to 10</p>
<div id="gary4-sortableTrash" class="sortable-code"></div> 
<div id="gary4-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="gary4-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="gary4-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var puzzlenum = 4;
  var initial = 
    "num = 2\n" +
    "while num <= 10:\n" +
    "    print(num)\n" +
    "    num += 2\n" +
    "num += 3 #distractor\n" +
    "print(num) #distractor";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "gary" + puzzlenum + "-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true,
    "trashId": "gary" + puzzlenum + "-sortableTrash"
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

<h1>5</h1>
<p>Ask for positive numbers, stop when negative</p>
<div id="gary5-sortableTrash" class="sortable-code"></div> 
<div id="gary5-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="gary5-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="gary5-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var puzzlenum = 5;
  var initial = "# Ask for positive numbers, stop when negative\n" +
    "num = int(input(\"Enter a positive number: \"))\n" +
    "while num >= 0:\n" +
    "    print(\"You entered:\", num)\n" +
    "    num = int(input(\"Enter a positive number: \"))\n" +
    "print(\"Negative number entered. Stopping.\")\n" +
    "num > 0 #distractor\n" +
    "while num < 0: #distractor";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "gary" + puzzlenum + "-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true,
    "trashId": "gary" + puzzlenum + "-sortableTrash"
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

<h1>6</h1>
<p>Print numbers 1 to 5</p>
<div id="gary6-sortableTrash" class="sortable-code"></div> 
<div id="gary6-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="gary6-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="gary6-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var puzzlenum = 6;
  var initial = 
    "for num in range(1, 6):\n" +
    "    print(num)\n" +
    "print(\"Done!\")\n" +
    "range(6, 1) #distractor\n" +
    "for num in range 1,6: #distractor";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "gary" + puzzlenum + "-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true,
    "trashId": "gary" + puzzlenum + "-sortableTrash"
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

<h1>7</h1>
<p>Sum of numbers from 1 to 10</p>
<div id="gary7-sortableTrash" class="sortable-code"></div> 
<div id="gary7-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="gary7-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="gary7-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var puzzlenum = 7;
  var initial =
    "total = 0\n" +
    "for num in range(1, 11):\n" +
    "    total += num\n" +
    "print(\"Sum:\", total)\n" +
    "total = num + total #distractor\n" +
    "for num in (1,10): #distractor";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "gary" + puzzlenum + "-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true,
    "trashId": "gary" + puzzlenum + "-sortableTrash"
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

<h1>8</h1>
<p>Print every third number from 1 to 20</p>
<div id="gary8-sortableTrash" class="sortable-code"></div> 
<div id="gary8-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="gary8-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="gary8-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var puzzlenum = 8;
  var initial = 
    "for num in range(1, 21, 3):\n" +
    "    print(num)\n" +
    "print(\"Sequence complete.\")\n" +
    "range(1,20,2) #distractor\n" +
    "for num range(1,21,3): #distractor";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "gary" + puzzlenum + "-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true,
    "trashId": "gary" + puzzlenum + "-sortableTrash"
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

<h1>9</h1>
<p>Count down from 10</p>
<div id="gary9-sortableTrash" class="sortable-code"></div> 
<div id="gary9-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="gary9-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="gary9-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var puzzlenum = 9;
  var initial = 
    "for num in range(10, 0, -1):\n" +
    "    print(num)\n" +
    "print(\"Liftoff!\")\n" +
    "for num in range(0,10,-1): #distractor\n" +
    "print(num) = #distractor";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "gary" + puzzlenum + "-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true,
    "trashId": "gary" + puzzlenum + "-sortableTrash"
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

<h1>10</h1>
<p>Print squares of numbers 1 to 5</p>
<div id="gary10-sortableTrash" class="sortable-code"></div> 
<div id="gary10-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="gary10-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="gary10-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var puzzlenum = 10;
  var initial = 
    "for num in range(1, 6):\n" +
    "    print(num ** 2)\n" +
    "print(\"All squares printed!\")\n" +
    "num ** 3 #distractor\n" +
    "for num range(1,6): #distractor";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "gary" + puzzlenum + "-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true,
    "trashId": "gary" + puzzlenum + "-sortableTrash"
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
