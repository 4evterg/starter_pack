# Starter-pack
Шаблон взятый у ["Фрилансер по жизни"](https://www.youtube.com/c/FreelancerLifeStyle) и подогнанный под себя.

## Оглавление
0. [Разделительная черта](#Основные-нюансы)
____
## Основные нюансы использования стартерпака

### Comment Anchors
Я использую плагин для VS code [Comment Anchors](https://marketplace.visualstudio.com/items?itemName=ExodiusStudios.comment-anchors). Только мои анкоры чуть изменены, просто добавьте этот кусок в VS code в settings.json

```
"commentAnchors.tags.list": [
  {
    "tag": "##",
    "iconColor": "default",
    "highlightColor": "#A8C023",
    "scope": "file"
  },
  {
    "tag": "#T",
    "iconColor": "blue",
    "highlightColor": "#3ea8ff",
    "scope": "workspace"
  },
  {
    "tag": "#X",
    "iconColor": "red",
    "highlightColor": "#F44336",
    "scope": "workspace"
  },
  {
    "tag": "#Z",
    "iconColor": "purple",
    "highlightColor": "#BA68C8",
    "scope": "file"
  },
  {
    "tag": "#N",
    "iconColor": "orange",
    "highlightColor": "#FFB300",
    "scope": "file"
  },
  {
    "tag": "#R",
    "iconColor": "blurple",
    "highlightColor": "#896afc",
    "scope": "workspace"
  },
  {
    "tag": "#S",
    "iconColor": "green",
    "highlightColor": "#64DD17",
    "scope": "workspace",
    "behavior": "region",
    "styleComment": true,
  },
  {
    "tag": "#L",
    "iconColor": "#696284",
    "highlightColor": "#696284",
    "scope": "workspace",
    "behavior": "link",
  }
],
```
