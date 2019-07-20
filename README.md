# node-red-contrib-runner
A Node for Node-RED that provides a comprehensive scheduler and task runner

**NO RELEASE AS YET**

## Why another scheduler?

While there are currently many schedulers for Node-RED, none of them seem to provide the flexibility needed for some tasks without either becoming very complex or being out of date (e.g. based on the `later` library that no longer seems to be in active development).

However, there are some really good Node.js task schedulers that might well be used in Node-RED and this is my attempt to create one.

It may take me a while though as I have many things going on and this is only one of several ideas I have in progress.

## Inspiration

Here is a list of some packages that might possibly find their way into this Node and that are providing some inspiration for the design.

* [node-schedule/node-schedule: A cron-like and not-cron-like job scheduler for Node.](https://github.com/node-schedule/node-schedule#readme)

   This seems like a good fit, not too complex but reasonably feature complete. Uses cron syntax for creating tasks/jobs/events at specific dates/times.

* [cronstrue - npm](https://www.npmjs.com/package/cronstrue)

   Translates cron syntax to human-readable form.

* [tasktimer - npm](https://www.npmjs.com/package/tasktimer)

   Timer-based instead of cron/datetime based. Might make a useful second Node.

* [controlled-schedule - npm](https://www.npmjs.com/package/controlled-schedule)

   Possible alternative to `node-schedule`.
