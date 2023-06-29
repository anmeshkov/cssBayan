# cssBayan
Аккордеон создан только с помощью HTML и CSS.

[Task](https://github.com/DrDiman/CSS-Bayan-task/blob/main/README.md)  
[Demo](https://anmeshkov.github.io/cssBayan/cssBayan/index.html)

---
![image](https://user-images.githubusercontent.com/97451331/224489947-29f5c845-c6cd-4719-8fe7-27fb50d4062f.png)
---

## Техническое задание
1. Center the accordion component on the screen, with equal indents on the left and right;
2. Implement responsive design. Accordion is displayed correctly at `mobile 320x568, tablet 820x1180, desktop 1920×1080`.
3. Font size should be changed at each device (mobile, tablet, desktop).
4. Design is at your discretion, but the layout of an accordion should include a meme image, text, and an icon. The placement of these elements should match the provided above example image.
5. There should be icon for state of the expanded\collapsed item (you can choose your own icons e.g. from FontAwesome).
6. Smooth transitions are applied for changing of memes and for changing of icon.
7. Make the entire row (text, icon, and meme image) clickable.
8. Cursor over the memes (hover) effect only exists for devices that can support hover. [MDN Note](https://developer.mozilla.org/en-US/docs/Web/CSS/:hover), [MDN hover in media queries](https://developer.mozilla.org/en-US/docs/Web/CSS/@media/hover).
9. Change the cursor when it is hovering over the accordion.
10. Initially, the first meme should be chosen/selected.
11. Chosen/selected meme should be always expanded. Selecting another meme makes this unselected (and collapsed).
12. Click on meme makes it selected.
13. Implement visual effects when the cursor is hovering over the memes, when the mouse is down on a meme (moment of mouse down - for active effect):
    - When the cursor is out of the memes:
      - icons for state of the expanded/collapsed item must be hided (NB: only for devices that can support hover; for devices with touchpad icons are always visible);
      - text-color of expanded item is different than text-color of collapsed items.
    - When the cursor is hovering over the memes:
        - all icons of all items becomes visible;
        - text-color of collapsed items changes to text-color of expanded item, text-color of expanded item doesn't change;
        - meme, over which cursor is moving, becomes expanded; icon of this meme changes to expanded icon;
        - when cursor moved out of meme, item becomes collapsed, expanded-icon changes to collapsed icon; choosen/selected meme shouldn't change to collapsed (see point #11).
    - When user clicks on meme-item (moment of mouse down - for active effect):
        - text-color and icon-color changes;
        - item opacity changes.

## Пояснение:
- аккордеон корректно работает в Chrome; 
- нет JavaScript; 
- дизайн и поведение аккордеона соответствует макету; 
- аккордеон корректно отображается на mobile 320x568, tablet 820x1180, desktop 1920×1080;
- курсор над эффектом мемов (hover) существует только для устройств, поддерживающих наведение, mobile 320x568, tablet 820x1180, а именно аккордеон разворачивается автоматически только на desktop 1920×1080 версии сайта

  ## Стек
- HTML
- CSS
- no JS
