# live-sketch


Procedure followed:
1.The video camera access permission will be requested before opening window for live-sketch window.
2.the main program runs as follows:
  > Color image is converted into gray image.
  > Gray image to Gray blur image(to reduce unwanted edges)
  > Gray-blur image into cannon form(to obtain edges)
  >Cannon form image will be of black background and white edges
  >To get white background with black edges binary_inv is applied to image.
  >continuous of these images gives you a live video sketch.
3. To exit from live sketch press enter.
