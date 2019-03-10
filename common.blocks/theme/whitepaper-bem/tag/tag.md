# Тэг

Идентификатор для категоризации, описания, поиска данных и задания внутренней структуры. В отличие от бейджа не имеет статуса. [Пример](https://codepen.io/whitepapertools/pen/093f2fd999b676a1986b847dc827945d/)

```js
{
	block: 'tag',
	mods: { view: 'default' },
	content: [
	{
		elem: 'text',
		content'Design'
	},
	{
		elem: 'delete',
		mix: { block: 'icon', mods: { name: 'delete-2', size: 's', view: 'ghost' } }
	}]
}
```

Тег может быть информационным, а может быть ссылкой. Также тег может быть редактируемым и нет. Если тег можно редактировать, то к нему в контент можно положить контрол, как в примере выше.

| Модификатор | Значение                 |
|-------------|--------------------------|
| view        | default / disable / link |
| size        | m / s                    |