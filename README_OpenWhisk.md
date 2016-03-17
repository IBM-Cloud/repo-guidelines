# 'OpenWhisk Example Action' Overview

<Include an overview of the functionality which this sample is built for
developers to leverage. Go over what the example actually does and how certain
OpenWhisk features are utilized.>

## Architecture Diagram

<If this example is more complex than a single action, include an architecture
diagram here>

## Accepted Params

<In addition to including the `.js` or `.swift` file, or the docker image for
the action in this repo, explain what `params` (if any) can be utilized in this
action>

  - `Param1` (accepted type) - what this param is and what it does
    - an example
  - `Param2` (accepted type) - what this param is and what it does
    - an example
  - `Param3` (accepted type) - what this param is and what it does
    - an example

## Creating the Action on OpenWhisk

<Any additional knowledge that isn't in the OpenWhisk getting started guide
should go here>

~~~sh
> wsk action create example-action example.js
ok: created action example-action
~~~

## Invoking the Action on OpenWhisk

~~~sh
> wsk action invoke --blocking --result example-action --param example-parm 'example'
{
  "payload": "hi mom!"
}
~~~

## Package, Feed, Event, or Trigger Creation

<If this example is more complex than a single action, any other creation of
feeds or events or triggers or use of packages should go here>

~~~sh
> wsk trigger create example --feed /whisk.system/alarms/alarm -p cron '*/8 * * * * *' -p trigger_payload '{"example":"param"}'
ok: created trigger feed everyEightSeconds
~~~
