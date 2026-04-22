## collectd

This flows converts messages received from collectd into thin-edge measurements

### Description

Messages are received from collectd over the MQTT topics `collectd/$HOSTNAME/$GROUP/$MEASUREMENT`.

These messages are CSV encoded (using `':'` column separators) and contains a unix timestamp followed by the measurement value.
