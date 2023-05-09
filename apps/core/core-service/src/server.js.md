## core-service

---

**server.js**

- creates express server
- loads
  - all [routers](https://github.com/techmetrica/techmetrica-docs/blob/master/apps/core/core-service/src/routes/)
  - required environment variables from [config.js](https://github.com/techmetrica/techmetrica-docs/blob/master/apps/core/cor-service/src/config/config.js)
  - [mongodb configuration] from [db.js](https://github.com/techmetrica/techmetrica-docs/blob/master/apps/core/cor-service/src/db.js)
- registers with consul(service discovery)
