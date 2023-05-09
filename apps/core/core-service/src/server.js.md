## core-service

---

**server.js**

- creates express server
- loads
  - all [routers](./routes/)
  - required environment variables from [config.js](./config/config.js.md)
  - [mongodb configuration] from [db.js](db.js.md)
- registers with consul(service discovery)
