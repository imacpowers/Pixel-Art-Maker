
  //the event occurred

//height = document.getElementById("inputHeight");
//width = document.getElementById("inputWidth");
let color = document.getElementById("colorPicker");
let table = document.getElementById("pixelCanvas");
let sizePicker = document.getElementById('sizePicker');
 height = document.getElementById("inputHeight");
 width = document.getElementById("inputWidth");

  makeGrid(height, width);

document.addEventListener('DOMContentLoaded', function(event) {


sizePicker.addEventListener('submit', (event)=> {
  event.preventDefault();
  table.firstChild.remove();

let height = document.getElementById("inputHeight").value;
let width = document.getElementById("inputWidth").value;
  makeGrid(height, width)
  //console.log('The heading was clicked!');
});
// When size is submitted by the user, call makeGrid()
})
function makeGrid(x, y) {
  for (let i = 0; i < x; ++i) {
   let row=pixelCanvas .insertRow(i);
    // Your code goes here!
    for (let j = 0; j < y; ++j) {
      let cell=row.insertCell(j);
      cell.addEventListener("click", (e)=>{
       cell.style.backgroundColor = color.value;
      // Your code goes here!
    });
  }

}


}
}