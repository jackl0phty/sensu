## 0.9.7 - TBD

### Features

Event data mutators, manipulate event data and its format prior to
sending to a handler.

### Non-backwards compatible changes

AMQP handlers can no longer use `"send_only_check_output": true`, but
instead have access to the built-in mutators `"mutator": "only_check_output"` and
`"mutator": "only_check_output_split"`.
