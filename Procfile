# Heroku uses a Procfile to determine which processes to run (babel required to compile ES6)
# Fine tune the GC as per https://devcenter.heroku.com/articles/node-best-practices
web: babel-node --optimize_for_size --max_old_space_size=920 --gc_interval=100 src/app.js
