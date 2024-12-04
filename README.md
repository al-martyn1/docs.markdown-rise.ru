# Тестируем

Записки с инфой лежат [тут](drafts/drafts.md)

[other.md](other.md)


<button class="btn js-change-theme">Change theme</button>

<script>
const changeTheme = document.querySelector('.js-change-theme');

jtd.addEvent(changeTheme, 'click', function()
{
    if (jtd.getTheme() === 'light')
    {
        changeTheme.textContent = 'Change theme to dark';
        jtd.setTheme('dark');
    }
    else if (jtd.getTheme() === 'dark')
    {
        changeTheme.textContent = 'Change theme to mdr';
        jtd.setTheme('mdr');
    }
    else
    {
        changeTheme.textContent = 'Change theme to light';
        jtd.setTheme('light');
    }
});
</script>
