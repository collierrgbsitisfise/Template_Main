### Вход
```
var tpl = `
    <div>
        <span class="title">
            {{title}}
        </span>
        <span class="text">
            {{text}}
        </span>
    </div>
`;

var list = [
    {
        title: 'qwerty',
        text: 'iuh'
    },
    {
        title: 'ytrewq',
        text: 'booooooooom'
    },
    {
        title: 'asdfgh',
        text: 'stradajte'
    }
];
```
### Выход
```
<div>
    <span class="title">
        qwerty
    </span>
    <span class="text">
        iuh
    </span>
</div>

<div>
    <span class="title">
        ytrewq
    </span>
    <span class="text">
        booooooooom
    </span>
</div>

<div>
    <span class="title">
        asdfgh
    </span>
    <span class="text">
        stradajte
    </span>
</div>
```