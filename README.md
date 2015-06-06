# synctranslit

Plugin for generating transliterated slugs (Cyrillic symbols: Ukrainian or Russian). It synchronizes two fields on the form. Data from field-source are beign transliterated to destination field.


## Usage

```js
$(document).ready(function(){
    $('#articleTitle').syncTranslit({destination: 'slug'});
});
```

### Available options:

1. **destination** - id of the destination element
2. **type** - url (default) or raw: transliteration type. url - for slug transliteration (no special characters). raw is used for raw transliteration
3. **caseStyle** - lower (default), normal, upper: case of transliterated data
4. **urlSeparator** - words separator for slug (default: '-')

### Copyright
- Author: *Roman Snitko snowcore.net@gmail.com*
- Maintainer: *Chilic*