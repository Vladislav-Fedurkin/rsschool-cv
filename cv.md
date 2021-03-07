# Vladislav Fedurkin
*** 
**Phone:** +375296426412  
**E-mail:** vladislav.fedurkin@gmail.com  
**Date of birth:** 05.07.2003  

_A motivated student who wants to be a good specialist frontend developer. Has such qualities as: Diligence, Ability to work in a team, responsiveness, responsibility._

#### Experience
- **01.08.2020-current time**
    - I started learning the HTML, CSS, JS, Git programming language in September. No experience in production.

#### Education
- **Belarusian National Technical University**
    - Theoretical mechanics and mechatronics
- **English A2**

#### Code example
The following part of the code I wrote for the button in Canvas 
```
export default class Button {
  constructor(options) {
    if (!options) throw new Error('Button options missing');

    this.x = options.x;
    this.y = options.y;
    this.height = options.height;
    this.width = options.width;
    this.iconUrl = options.iconUrl;
    this.clickHandler = options.clickHandler;

    if (options.iconUrl) {
      this.setIcon(options.iconUrl);
    } else {
      this.icon = null;
    }
  }

  setIcon(url) {
    const icon = new Image();
    icon.src = url;
    this.icon = icon;
  }

  render(context) {
    context.drawImage(this.icon, this.x, this.y);
  }
}
```
