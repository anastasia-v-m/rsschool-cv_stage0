### Matushevskaya Anastasia ###

**Contact information**

matushevskayaanastasia@gmail.com


**About me**

I graduated from Polotsk State University with a degree in Finance and Credit. Now I work in technical support in a large holding. Working in the IT sphere fascinated me and I want to further develop in this direction. Thus, I decided to master the front-end direction.
Now I study technology:
1. HTML
1. CSS
1. JS

**Code example**

[full work] (https://rolling-scopes-school.github.io/anastasia-v-m-JSFEPRESCHOOL/js30-2/)

```function changeImg() {
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

I work in technical support for 7 years.

**English language**

B1
