Przykładowe formatowanie wiadomości najczęściej w pliku messages.yml

### Przykład
```yaml
przyklad:
  chat: Jestem wiadomością na czacie
  actionbar: Wyświetlam się na actionbar
  title:
    title: Wyświetlam tytuł
    subtitle: Wyświetlam podtytuł
    fade-in: 10
    stay: 20
    fade-out: 10
  bossbar:
    name: Wyświetlam się na bossbarze
    color: GREEN
    overlay: PROGRESS
    progress: 0.5
    stay: 20
  sound:
    name: minecraft:ui.button.click
    source: MASTER
    volume: 1.0
    pitch: 1.0
```

---

### Wiadomość tylko na czacie
```yaml
# Przykładowa wiadomość
przyklad: Jakaś tam wiadomość standardowa

# Lista wiadomości
przykladlisty:
- To jest wiadomość 1
- To jest wiadomość 2
  
# Przykład wyświetlanej wiadomości tylko dla konsoli 
przyklad:
  console: true
  message: To jest wiadomość tylko dla konsoli
