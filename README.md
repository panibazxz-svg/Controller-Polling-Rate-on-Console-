# [Controller-Polling-Rate-on-Console-](https://benchmarksetups.com/1000hz-wireless-polling-rate-console-tested/)
Controller Polling Rate on Console: Does 1000Hz Wireless Actually Work on PS5 and Xbox?
A third-party dongle promises 1000Hz wireless polling on your PS5 controller. That assertion is true and measurable on PC. It’s harder on console, and sometimes the number on the box doesn’t match anything you can truly feel.

Instead of relying on the stated polling number, we measured actual round-trip latency by testing official wireless connections against third-party “1000Hz” dongles on both PS5 and Xbox.

Polling Rate Vs Input Processing Rate: Two Different Things
1000Hz wireless polling console frequency with which a controller reports its state to the device it is connected to is called its polling rate. 1000 times per second is reported by a 1000Hz controller.

The frequency with which the receiving device, in this case, the operating system of a console and the game that runs on it, actually reads and processes the reported data is known as the input processing rate.

Most console games read controller input about once per rendered frame. At 120fps, that means new input can affect what you see roughly 120 times per second, so the extra reports from a 1000Hz controller go unused. Sony and Microsoft don’t publish exact input-sampling rates, so this is an inference from frame-rate behavior.

Why PC and Console Handle This Differently
Because PC frame rates can reach 240 frames per second or more in certain games, the operating system and game engine can process input far more frequently on PCs, especially in competitive shooters running at high frame rates.

Frame rates on consoles are typically capped at 60 or 120 frames per second, depending on the game’s performance mode. No matter how quickly the controller polls, this puts a practical limit on how often new input can significantly change what you see.
