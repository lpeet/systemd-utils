systemd-utils
=============

Random systemd utilities

On Failure
----------

* Allows users to specify `OnFailure=failure-email@%i.service` under `[Unit]` section of systemd files.
* The failure-email service will email the user when a service fails unexpectedly and include the `systemd status <svc>` output.
