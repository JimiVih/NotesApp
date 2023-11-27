<script>
    let isDown = false;
    const mouseDown = (element) => {
      console.log(element.target.id);

      let elementID = element.target.id;
      isDown = true;


      document.getElementById(elementID).classList.remove("button");

      console.log("done");
      
    }

    const mouseUp = (element) => {
        
      
    }

  </script>
  
  <div class="button" class:down={isDown} id="addNotes" on:mousedown={mouseDown} on:mouseup={}>Create notes for class</div>


  <style>
    .button {
      border: solid 2px black;
      border-radius: 5px;
      text-align: center;
      width: 150px;
      box-shadow: 0px 5px 0px 0px;
    }
  
    .button:hover {
      cursor: pointer;
      transform: translateY(2px);
      box-shadow: 0px 3px 0px 0px;
    }

    .down {
        border: solid 2px black;
      border-radius: 5px;
      text-align: center;
      width: 150px;
      transform: translateY(5px);
      box-shadow: 0px 0px 0px 0px;
    }
    .mouseDown:hover{
        cursor: pointer;
    }

  </style>
  




