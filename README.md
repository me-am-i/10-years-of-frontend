# Больше 10 лет фронтенда

Содержимое нуждается в доработке, дополнения можно предложить через ишью или пулреквест. 

В предлагаемых данных обязательно должны быть код запуска и ссылка на источник этой информации.

Новые события добавляются в `data.js` в следующем формате:

```js
{
  name: 'Git',
  years: {
    start: 2005,
    end: 2015, // если есть
  },
  group: 'git',
  links: [
    {
      name: 'contributors',
      url: 'https://github.com/git/git/graphs/contributors'
    }
  ]
}
```

- Для CSS-свойства указывается год, когда большинство современных браузеров поддерживало его без префикса.
- Для всех остальных – дата релиза или начало работы (по логам или коммитам)
