---
layout: backend.html
# action: https://script.google.com/macros/s/AKfycbx4x-jvzx35vZAUiKHzkeB3hHCbqBPbaR09UD78_o3UtTGaqIM/dev
# action: https://script.google.com/macros/s/AKfycbwoVLxakcPYgo90LbiQ7F2P-ikPeKf3I0F9yFUjFvU/dev
---
<form action="https://script.google.com/macros/s/AKfycbx4x-jvzx35vZAUiKHzkeB3hHCbqBPbaR09UD78_o3UtTGaqIM/exec" method="post">
<input type="hidden" name="key" value="_data/builder/post-2.json" />
<div>
<label>Risorsa</label> <input type="text" name="resource" value="_data/builder/post-2.json" />
</div>
<div>
  <label>Dati</label> <textarea name="data">{{ site.data.builder["post-1"] }}</textarea>
</div>
<div class="text-center">
  <button name="submit_data" type="submit" class="btn btn-primary">salva</button>
</div>
</form>
