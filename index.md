# Scrypted Development

Scrypted offers many different ways to interact with the platform.

* `Plugins` - Create and publish packages that can add new devices or interact with the platform.
* `Scripts` - Similar to plugins, and can be done without a development environment by using the built in `Script` editor.
* `Webhook Plugin` - Interact with existing devices in Scrypted: turn on switches, retrieve snapshots, etc.
* `MQTT Plugin` - Publish Scrypted events (motion sensors, object detections, etc) to an MQTT broker. Can also be used to create devices similar to Scripts.

Regardless of which method is used to interact with Scrypted, the underlying data structures and methods are the same.

