# Finnish Translations for Admin-on-rest

Finnish translations for [admin-on-rest](https://github.com/marmelab/admin-on-rest), the frontend framework for building admin applications on top of REST services.

![admin-on-rest demo](http://static.marmelab.com/admin-on-rest.gif)

## Installation

```sh
npm install --save aor-language-finnish
```

## Usage

```js
import finnishMessages from 'aor-language-finnish';

const messages = {
    'fi': finnishMessages,
};

<Admin locale="fi" messages={messages}>
  ...
</Admin>
```

## License

This translation is licensed under the [MIT Licence](LICENSE).