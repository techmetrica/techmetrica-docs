## core-service

---

**db.js**

- creates express server
- loads
  - all routers
  - environment variables(config.js)
  - mongodb configuration
- registers with consul(service discovery)
