# 08. База обучения на примерах (Successful & Unsuccessful Prompt Examples)

## Как работает этот файл
Агент учится на реальных примерах из практики. Перед генерацией нового промпта агент просматривает этот файл, чтобы повторить удачные художественные приёмы и не наступить на старые грабли. После удачных или неудачных экспериментов мы добавляем сюда новые записи.

---

## Раздел 1. Примеры для изображений (Image Prompts)

### Пример №1: Городская сцена после дождя
- ❌ **Неудачный промпт:**
  `Beautiful European street after rain, evening, lights, woman walking, cinematic, 8k, masterpiece, photorealistic, ultra detailed.`
- **Почему не сработало:**
  Слишком общие слова и «мусорные» теги (*8k, masterpiece*). Нет ни ракурса, ни характера света, ни настроения — нейросеть выдаёт скучную, «пластиковую» открытку без души.
- ✅ **Удачный промпт:**
  `35mm film photograph of a solitary woman in a long wool coat walking along a wet cobblestone street in an old European town during blue hour. Soft warm light spilling from small café windows onto the damp stones, subtle reflections in puddles, light evening mist. Medium wide shot, shallow depth of field, Kodak Portra 400 grain, melancholic poetic atmosphere.`
- **Почему сработало:**
  Указан конкретный медиум (*35mm film photograph, Kodak Portra 400*), точное время суток (*blue hour*), понятный контраст света (тёплые окна кафе на фоне холодных сумерек) и план (*medium wide shot*).

---

## Раздел 2. Примеры для видео (Video & Image-to-Video Prompts)

### Пример №2: Оживление портрета у окна (Image-to-Video)
- ❌ **Неудачный промпт:**
  `A woman sitting by the window in a cozy room with a cup of tea, she suddenly stands up, turns around, smiles broadly and walks away quickly, dynamic camera zooming fast.`
- **Почему не сработало:**
  Слишком много резких действий сразу и пересказ исходной картинки. Видео-нейросеть исказила лицо при резком развороте, а быстрый зум сломал спокойную атмосферу кадра.
- ✅ **Удачный промпт:**
  `The woman remains seated calmly by the window, blinking softly and taking a slow, subtle breath as she gazes outside. Gentle breeze slightly moves a strand of her hair and the sheer curtain. Steam rises slowly from the warm cup on the table. Very slow, smooth camera push-in, calm natural motion, consistent soft daylight.`
- **Почему сработало:**
  Сохранена исходная композиция, описано одно деликатное естественное движение, добавлена микродинамика фона (пар, занавеска) и задан медленный, плавный наезд камеры.

---

## Шаблон для добавления новых примеров (заполняется вместе с агентом)
- **Задача / Сцена:** (кратко, что хотели получить)
- ❌ **Неудачный вариант:** (текст промпта, который сработал плохо)
- **Причина неудачи:** (что пошло не так в кадре)
- ✅ **Удачный вариант:** (исправленный промпт, который дал отличный результат)
- **Главный вывод / Урок:** (какое правило запоминаем на будущее)
