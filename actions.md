# Actions

Actions simply sends data to store. This is the only source of info for the Store. This is JUST A PLAIN JS OBJECT.

Each action object must have a type prop that describes the action being performed.

## Send it to the store

  `store.dispatch(action)