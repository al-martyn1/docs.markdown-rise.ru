# Тестируем

Записки с инфой лежат [тут](drafts/drafts.md)

[other.md](other.md)


<button class="btn js-change-theme">Change theme</button>

<script>
const changeTheme = document.querySelector('.js-change-theme');

jtd.addEvent(changeTheme, 'click', function(){
  if (jtd.getTheme() === 'light') {
    jtd.setTheme('dark');
    changeTheme.textContent = 'Change theme to dark';
  } else if (jtd.getTheme() === 'dark') {
    jtd.setTheme('mdr');
    changeTheme.textContent = 'Change theme to mdr';
  }
  } else {
    jtd.setTheme('dark');
    changeTheme.textContent = 'Change theme to light';
  }
});
</script>
