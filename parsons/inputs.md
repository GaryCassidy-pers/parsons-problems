<div id="gary-sortableTrash" class="sortable-code"></div> 
<div id="gary-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="gary-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="gary-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "print(&quot;What is your first initial?&quot;)\n" +
    "initial = input()\n" +
    "print(initial)";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "gary-sortable",
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
  $("#gary-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#gary-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

<div id="gary2-sortableTrash" class="sortable-code"></div> 
<div id="gary2-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="gary2-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="gary2-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "print(&quot;What is your first initial?&quot;)\n" +
    "initial = input()\n" +
    "print(initial)";
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
