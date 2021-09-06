### Matushevskaya Anastasia ###

**Contact information**

e-mail: matushevskayaanastasia@gmail.com

git: anastasia-v-m


**About me**

I have a higher education in economics. And some experience in sales and economics let me understand that this is not what I want develop in future. 
Since 2015 I work as an 1S programmer. And I want to achieve more in programming. So I have started to study JavaScript by myself on learn.javascript.ru. Now during RSSchool course I am going to structure my knowledge, gain hands-on experience and master skills to apply for a position of a junior JavaScript developer.

My soft skills:
* Discipline
* Purposefulness
* Communication skills

My hard skills (base level):
* HTML
* CSS
* JavaScript
* Git
* SQL

**Code example**

[full work](https://rolling-scopes-school.github.io/anastasia-v-m-JSFEPRESCHOOL/js30-2/)

```javascript
function changeImg() {
            let prefix = (event.target.id);

            if (prefix === "reset_btn") {
                prefix = "normal";
            }

            const root = document.querySelector(':root');
            const rootStyles = getComputedStyle(root);
            
            const styleSepia = rootStyles.getPropertyValue('--' + prefix + '-sepia');
            const styleGrayscale = rootStyles.getPropertyValue('--' + prefix + '-grayscale');
            const styleBrightness = rootStyles.getPropertyValue('--' + prefix + '-brightness');
            const styleContrast = rootStyles.getPropertyValue('--' + prefix + '-contrast');
            const styleSaturate = rootStyles.getPropertyValue('--' + prefix + '-saturate');

            const mainImg = document.querySelector('.main-image');

            document.getElementsByName('sepia')[0].value = styleSepia.substr(0, styleSepia.length-1).trim();
            document.getElementsByName('grayscale')[0].value = styleGrayscale.substr(0, styleGrayscale.length-1).trim();
            document.getElementsByName('brightness')[0].value = styleBrightness.substr(0, styleBrightness.length-1).trim();
            document.getElementsByName('contrast')[0].value = styleContrast.substr(0, styleContrast.length-1).trim();
            document.getElementsByName('invert')[0].value = "0";
            document.getElementsByName('saturate')[0].value = styleSaturate.substr(0, styleSaturate.length-1).trim();
            document.getElementsByName('blur')[0].value = "0";

            inputs.forEach(input => handleUpdate.call(input));
        }
```
		
**Expirience**

I work in IT for 6 years.

**English language**

B1
