---
layout: default
---
<form action="" method="get" class="form-example">
  <div class="form-example">
    <label for="name">nafn: </label>
    <input type="text" name="name" id="name" required>
  </div>
  <div class="form-example">
    <label for="símanúmer">símanúmer: </label>
    <input type="number" name="number" id="number" required>
  </div>
  <div class="form-example">
    <label for="email">tölvupóst: </label>
    <input type="email" name="email" id="email" required>
  </div>
  <div>
    hvaða dagur er í dag?
  <select name="dagar">
    <option value="sunnudagur" selected>sunnudagur</option>
    <option value="mánudagur">mánudagur</option>
    <option value="þriðjudagur">þriðjudagur</option>
    <option value="miðvikudagur">miðvikudagur</option>
    <option value="fimtudagur">fimtudagur</option>
    <option value="föstudagur">föstudagur</option>
    <option value="laugardagur">laugardagur</option>
    

  </select>
  </div>
  <fieldset>
    <legend>click click</legend>
    <input type="radio" name="radio" id="radio">
    <label for="radio">clickaðu hérna</label>
  </fieldset>
  <div class="form-example">
    <input type="submit" value="skrá inn!">
  </div>

</form>
