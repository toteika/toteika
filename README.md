# toteika.github.io
<script language = 'javascript'>
  var flag = 0;
  function changeImage() {
    if (flag == 0) {
      document.img.src = '1.jpg';
      flag = 1;
    }
    else {
      document.img.src = '2.jpg';
      flag = 0;
    }
  }
</script>
<img name = 'img' src = '1.jpg' />
<form>
  <input type = 'button' value = 'Click' onClick = 'changeImage()' />
</form>
