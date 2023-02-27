Элемент HTML `<audio>` используется для воспроизведения аудиофайла на веб-странице.

---

## HTML-элемент `<audio>`

Чтобы воспроизвести аудиофайл в формате HTML, используйте `<audio>`элемент:

### Пример

```html
<audio controls>  
  <source src="horse.ogg" type="audio/ogg">  
  <source src="horse.mp3" type="audio/mpeg">  
Your browser does not support the audio element.  
</audio>`
```

---

## HTML-аудио — как это работает

Атрибут `controls` добавляет элементы управления звуком, такие как воспроизведение, пауза и громкость.

Элемент `<source>` позволяет указать альтернативные аудиофайлы, из которых может выбирать браузер. Браузер будет использовать первый распознанный формат.

Текст между тегами `<audio>` и `</audio>` будет отображаться только в браузерах, которые не поддерживают этот `<audio>` элемент.

---

## HTML <аудио> Автовоспроизведение

Для автоматического запуска аудиофайла используйте атрибут `autoplay`:

### Пример

```html
<audio controls autoplay>  
  <source src="horse.ogg" type="audio/ogg">  
  <source src="horse.mp3" type="audio/mpeg">  
Your browser does not support the audio element.  
</audio>
```

**Примечание.** Браузеры Chromium в большинстве случаев не поддерживают автозапуск. Однако приглушенный автозапуск всегда разрешен.

Добавьте `muted` после `autoplay`, чтобы ваш аудиофайл начал воспроизводиться автоматически (но с отключенным звуком):

### Пример

```html
<audio controls autoplay muted>  
  <source src="horse.ogg" type="audio/ogg">  
  <source src="horse.mp3" type="audio/mpeg">  
Your browser does not support the audio element.  
</audio>
```

[API](obsidian://open?vault=Frontend&file=JavaScript%2FAPI%20Audio%20%D0%B8%20Video)