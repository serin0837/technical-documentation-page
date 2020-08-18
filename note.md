# CSS

- border right : only right of border change

- min width:아무리 작아져도 예를 들어 500px이면 500px까지만 작아짐 그래도 화면이 500px보다 작아지면 그냥 화면에 꽉참//
  I commented out because i dont think i need in my web page

- overflow-x,y
  overflow-x:The overflow-x property specifies whether to clip the content, add a scroll bar, or display overflow content of a block-level element, when it overflows at the left and right edges.

The overflow-y property specifies whether to clip the content, add a scroll bar, or display overflow content of a block-level element, when it overflows at the top and bottom edges.

ex)
div.ex1 {
overflow-y: scroll;
}

div.ex2 {
overflow-y: hidden;
}

div.ex3 {
overflow-y: auto;
}

div.ex4 {
overflow-y: visible;
}
