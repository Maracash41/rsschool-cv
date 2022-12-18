# Andrey Akimov
## Junior Frontend Developer
****
### Contact information:
E-mail: 9531945@gmail.com
Telegram: @mcash41
Phone: +7 921 9531945
---
### Skills and Proficiency:

- Adobe Photoshop, Figma, Corel Draw
- HTML5, CSS3, SCSS, BEM
- JavaScript(ES5-6)
- Knowledge about System Administration
- English - Intermediate
- Heigh learning ability
- Ability to listen
- Self-discipline
- Goal-oriented
- Sociable


### English level:

- B1

### About me:

I like to create new things, develop a mind, communicate with people, go in for sports, read books, write code. Computers took over my mind early. When I was 7 years old, I was already doing light PC repairs at my mom's work.

### Courses:

- [freeCodeCamp](https://freecodecamp.org/)
- [YouTube](https://youtube.com/)
- [Learn JavaScript](https://learn.javascript.ru/)
- [RS School](https://rs.school/js/)


### Code:

```sh
function brightest(colors) {
    let maxColor,
    colorIndex,
    currentValueColor = 0;
    for (let i = 0; i < colors.length; i++) {
        let color = colors[i],
        r = parseInt(color.slice(1, 3), 16);
        g = parseInt(color.slice(3, 5), 16);
        b = parseInt(color.slice(5, 7), 16);
        maxColor = Math.max(r,g,b);
        if (maxColor > currentValueColor ) {
            currentValueColor = maxColor;
            colorIndex = i;
        }
    }
    return colors[colorIndex];
}
```

