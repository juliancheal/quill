# Quill
## Guardian of your own galaxy

Quill protects and serves your smart home. Keeping important devices running, switching off power hogs, protecting against outside influences[*](#1).

In Quill devices are called `Orbs`. It is Quill's job to protect all the `Orbs` in the `Galaxy`.

`activate_orbs()` or `galaxy_shutdown()`

## Description

Register an `Orb` with Quill, set up the `Orbs` parameters and let Quill do the rest.

For example if you're using a smart plug with energy monitoring to monitor your fridge's power usage. You wouldn't want the fridge to be turned off by an accidental "Hey Siri, switch off all plugs". In this scenario, Quill will check the power status of your fridge and switch it back on, saving your food and the day.


## TODO

* Register orb
* Setup rules
* Schedule checks

## Works with

* Nest
* Smart plugs
* Siri
* Amazon Echo

## Powered by

* [Consul](https://github.com/hashicorp/consul)
* [Kala](https://github.com/ajvb/kala)

### Footnotes

[1]: Outside influences means you turning something off by mistake, Quill can't protect you from an army of Botnets. Not yet at least.
