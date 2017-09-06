# local-storage

Basic useful feature list:

```javascript
const storage = require('json-local-storage')
const users = storage('users')

users.create({name:'Simon'})
users.update({name:'Simon Madsen'},{name:'Simon'})
users.delete({name:'Simon Madsen'})
users.select() //: []
users.select({name: 'Simon Madsen'}) //: []
users.find({name: 'Simon Madsen'}) //: {}

```
