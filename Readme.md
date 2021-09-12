# bd-geojs

a npm package to get all divisions, districts, upazillas and unions of Bangladesh.

Thanks to [nuhil](https://nuhil.net) ❤️ author of github repository [bangladesh-geocode](https://github.com/nuhil/bangladesh-geocode)

import with es6 and later:

```
import { divisions, districts, upazillas, unions } from 'bd-geojs'
```

import with nodejs

```
const { unions } = require('bd-geojs')
```

You will get sorted (by name) array of divisions, districts, upazillas, unions from your import.

Properties on every object:

- Division

  - id
  - name
  - bn_name
  - url

- District

  - id
  - name
  - bn_name
  - url
  - division_id
  - lat
  - long

- Upazilla

  - id
  - name
  - bn_name
  - url
  - district_id

- Union
  - id
  - name
  - bn_name
  - url
  - upazilla_id
