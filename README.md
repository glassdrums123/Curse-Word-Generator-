<html>
  <body>
    <h1> Hello This is a curse words generater <h1>  
       <style>
    
   
    
    #output {
    
      font-family:fantisy;
    }
  </style>
</head>
<body>

  <h2>random word generator</h2>
  <div>
    <button>generate</button>
  </div>
  <div>
   
  

  <div id="output"></div>

  <script>
   
    var btn = document.querySelector("button");
    var out = document.getElementById("output");
    
  
    btn.addEventListener("click", getWord);
   
    function getWord(){
     
      
      var theWord= [
        'dog',
        'potato',
        'cow',
        'parrot',
        'stone',
        'watch',
         'house',
         'biolumonesance',
        'brake',
        'potato/salad',
        'trip',
        'hipopotomus',
        'mask',
        'chicken',
        'Pneumonoultramicroscopicsilicovolcanoconiosis',
      ];

      
      var wordNum = Math.floor(Math.random() * theWord.length);
      
     
      output.textContent = theWord[wordNum];
    }
</script>
  </body>
</html>
