# **Maksim Navumovich**
# **Contacts**
* **Discord**: Junk#7813
* **E-mail**: <maks.naumovich@gmal.com>
* **Tel**: +48512008698
# **About myself**
My name is Maksim. I'm 15 years old. I'm from Belarus, but now I live in PLand. I want to improve yourself and became a nice coder. That's why I'm here.
# **Skills** 
* HTML
* CSS/CASS/BEM
* Git
* Figma (basics)
# **Code example** 
```
const ACTIVE_COLOR = "#6F6F6F";
const INACTIVE_COLOR = "#CDCDCD";
const SLIDESHOW_TIME = 5000;
let activeImageIndex = 0;
let shouldPauseAnimation = false;

function setColorForButton(imageIndex, color) {
  document.getElementById("button" + imageIndex).style.background = color;
}

function disableAllButtons() {
  for (let imageIndex of [0, 1, 2]) {
    setColorForButton(imageIndex, INACTIVE_COLOR);
  }
}

function selectImage(imageIndex) {
  // Updating image src
  let newSrcForImage = "img/bicycle-" + imageIndex + ".png";
  document.getElementById("myImage").src = newSrcForImage;

  // Updating buttons
  disableAllButtons();
  setColorForButton(imageIndex, ACTIVE_COLOR);

  activeImageIndex = imageIndex;
}

setInterval(toggleImageIfNotPaused, SLIDESHOW_TIME);

function toggleImageIfNotPaused() {
  if (shouldPauseAnimation === false) {
    toggleImage();
  }
}

function toggleImage() {
  let newImageIndex = (activeImageIndex + 1) % 3;
  selectImage(newImageIndex);
}

function changeDiv(nr) {
  let element = document.getElementById("sectdiv" + nr);
  let height = window.getComputedStyle(element).height;
  if (height == "96px") {
    document.getElementById("sectdiv" + nr).style.height = "846px";
    document.getElementById("imgIcon" + nr).src = "icons/Vector.svg";
  } else {
    document.getElementById("sectdiv" + nr).style.height = "96px";
    document.getElementById("imgIcon" + nr).src = "icons/Vector (1).svg";
  }
}
```
# **Work experience** 
Nothing yet
# **Education**
* Gimnasium №2, Brest
* Technikum nr 13, Gdansk
* Udemy HTML/CSS course
* RSS
# **Languages**
* **Russian**: Native
* **Belorussian**: Native
* **English**: B1
* **Polish**: B1
* **Deutsch**: A1




