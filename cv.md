# Olexii Yevdoshchenko
## Contacts
* **Phone:** +38 096 842 22 70
* **E-mail:** olexiyewdoshchenko@gmail.com
* **GitHub:** Ewdoha
* **Discord:** Olexii Yevdoshchenko (@Ewdoha)
* **Linkedin:** [olexii-yevdoshchenko-025258133](linkedin.com/in/olexii-yevdoshchenko-025258133)
* **Telegram:** https://t.me/Ewdoha
## About Me
I have a great desire to master web development. I will do my best to gain the necessary knowledge and skills to become a developer and develop in this profession.
## Skills 
* HTML
* CSS
* JavaScript(fundamentals)
* GitHub, Git
* Figma(for web development), Photoshop
## Code examples
```
const mapImage = document.querySelector('.map-image');
const popupMap = document.querySelector('.popup-map');
const buttonPopupMapClose = document.querySelector('.button-popup-map-close');


        mapImage.addEventListener('click', function (evt) {
            evt.preventDefault();
            popupMap.classList.add('popup-map-show');
        });

        buttonPopupMapClose.addEventListener('click', function (evt) {
            evt.preventDefault();
            popupMap.classList.remove('popup-map-show');
        });

        window.addEventListener('keydown', function (evt) {
            if (evt.keyCode === 27) {
              if  (popupMap.classList.contains('popup-map-show')) {
                evt.preventDefault();  
                popupMap.classList.remove('popup-map-show');
              }
                
            }
        });
```
## Education
* National University of Water and Environmental Engineering
  * Mechanical Engineering, Master's degree
* Courses
  * HTML Academy
  * Sololearn
## Language
* **Ukrainian** - native
* **English** - A1 (in the process of studying)
* **Russian** - Intermediate