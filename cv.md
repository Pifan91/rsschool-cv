# __[rsschool-cv](https://kryvetski-andrei.github.io/rsschool-cv/)__

# __Nikolay Epifanov__

## __Contacts__
- __Location:__ Naro-Fominsk, Russia
- __Telegram:__ https://t.me/pifan91
- __Email:__ nepifanov91@gmail.com
- __GitHub:__ [Pifan91](https://github.com/Pifan91)

## __About Me__
  Hello!
  I am 31 years old and I work as a network engineer. Most recently, I decided to change my profession and started studying development.
  At the moment I am going through intensives at HTML Academy, studying basic JS.

## __Skills__
- HTML
- BEM
- CSS
- SASS
- Figma
- JavaScript (Basic)
- Gulp (Basic)
- Git

## __Code Example__
_DOM rendering example_
```
const createPictureElement = ({ url, likes, comments, description }) => {
  const pictureElement = pictureTemplateElement.cloneNode(true);
  pictureElement.querySelector('.picture__img').src = url;
  pictureElement.querySelector('.picture__likes').textContent = likes;
  pictureElement.querySelector('.picture__comments').textContent = comments.length;
  pictureElement.addEventListener('click', () => openPictureModal(url, likes, comments, description));

  return pictureElement;
};
```
*********

_Random integer from range_
```
const getRandomInteger = (min, max) => {
  const lower = Math.ceil(Math.min(Math.abs(min), Math.abs(max)));
  const upper = Math.floor(Math.max(Math.abs(min), Math.abs(max)));
  const result = Math.random() * (upper - lower + 1) + lower;
  return Math.floor(result);
};
```