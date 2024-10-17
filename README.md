<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rock paper and scissors</title>
</head>
<body>
    <p>Rock paper and scissors</p>
    <button onclick="
   myfunction();
    ">Rock</button>
    <button onclick="
   myFunction();
    ">Paper</button>
    <button onclick="
   myFunction2();
    ">Scissors</button>
   <script>
      function myfunction(){
        let randNum =Math.floor(Math.random()*3);
  if(randNum == 0 ){
      alert('Tie');
    }
    else if(randNum == 1){
        alert('you loss');
    }
    else{
        alert('you win');
    }
    alert(`Computer choose${randNum} `);
    alert(`Which means that 0= Rock ,1 = Paper and 2 = scissors`);
  
      }
      function myFunction(){
        let randNums = Math.floor(Math.random()*3);
    if(randNums == 0 ){
        alert('win');
    }
    else if(randNums == 1){
        alert('tie');
    }
    else{
        alert('loss');
        
    }
    alert(`Computer choose${randNums}`);
    alert(`Which means that 0= Rock ,1 = Paper and 2 = scissors`);
    
      }
      function myFunction2(){
        let randNumss =Math.floor(Math.random()*3);
    if(randNumss == 0 ){
        alert('loss');
    }
    else if(randNumss == 1){
        alert('win');
    }
    else{
        alert('tie');
        
    }
    alert(`Computer choose${randNumss}`);
    alert(`Which means that 0= Rock ,1 = Paper and 2 = scissors`);
      }
   </script>
</body>
</html>
