# Тестируем

Записки с инфой лежат [тут](drafts/drafts.md)

[other.md](other.md)


<button class="btn js-change-theme">Change theme</button>

<script>
const changeTheme = document.querySelector('.js-change-theme');

jtd.addEvent(changeTheme, 'click', function()
{
    if (jtd.getTheme() === 'light') // cur text - 'Change theme to dark'
    {
        changeTheme.textContent = 'Dark. Change theme to mdr';
        jtd.setTheme('dark');
    }
    else if (jtd.getTheme() === 'dark') // cur text - 'Change theme to mdr'
    {
        changeTheme.textContent = 'Mdr. Change theme to light';
        jtd.setTheme('mdr');
    }
    else // =='mdr'  // cur text - 'Change theme to light'
    {
        changeTheme.textContent = 'Light. Change theme to dark';
        jtd.setTheme('light');
    }
});
</script>
