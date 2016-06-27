orchestration README
---

This is a docker-compose which starts all services and builds the base images being used by the app.

It relies on the images of `repl`, `integrity` and `platform` being built, already as per their READMEs.

---

To build the repos (after any changes in the other docker images):

`docker-compose up` 

after everything has been built, cancel the console.

---

To start all services:

`docker-compose start`
