# basic-settings

налаштування hbs (для створення розмітки hbs)

                npm install --save-dev parcel-transformer-hbs

уфайлі .parcelrc треба добавити налаштування (при використані збірки парсел)

                "transformers": {
                "\*.hbs": [
                "parcel-transformer-hbs"
                ]
                }

налаштування axios (для https запитів)
https://axios-http.com/docs/intro

                npm install axios

                const axios = require('axios').default;

приклад axios

            axios.get('/user', {
            params: {
            ID: 12345
            }

            })
            .then(function (response) {
            console.log(response);
            })
            .catch(function (error) {
            console.log(error);
            })
