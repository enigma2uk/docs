## Dish

Almost all satellite dishes in the UK are the Sky minidish variety (currently version/mark 4). These dishes are all perfectly acceptable for receiving all UK OTA broadcasts. However, depending on your dish, the LNB may need changing due to incompatibilities between the various platforms.

It's also worth noting that any existing cabling through your property will work just fine, regardless of your satellite dish configuration. It is all standard [coaxial satellite cable](https://en.wikipedia.org/wiki/Coaxial_cable) with [F-connectors](https://en.wikipedia.org/wiki/F_connector).

## LNB

| LNB      | Sky Q              | Sky Legacy         | Freesat            | Enigma2            |
| -------- | ------------------ | ------------------ | ------------------ | ------------------ |
| Sky Q    | :white_check_mark:	|                    |                    |                    |
| Freesat  |                    | :white_check_mark: | :white_check_mark: | :white_check_mark: |
| Unicable |                    |                    |                    | :white_check_mark: |

### Sky Q

Sky Q uses Wideband LNB's which are currently only compatible with Sky Q receivers. If instructed prior to Sky Q installation, Sky will sometimes install a [Hybrid LNR](https://www.amazon.co.uk/Visiblewave-Hybrid-Output-Wideband-Freesat/dp/B07GS1Z2YP) which supports both the required inputs for the Sky Q receivers plus *Legacy* outputs for Freesat compatibility. In most situations, the standard LNB (usually with two cables) on a standard Sky Q installation will not work with any Freesat branded or Enigma2 receiver.

### Freesat / Sky Legacy

Current Freesat (and Sky legacy LNBs) are usually Dual, Quad or Octo LNBs, which provide separate discrete outputs to each receiving box.

### Unicable

[Unicable](https://en.wikipedia.org/wiki/Unicable) LNBs allow a single output and cable to carry the entire frequency range received from the dish. To use a Unicable LNB, you must have a tuner capable of receiving a FCB (Full Channel Broadcast) or SCR (Single Cable Receiver) signal. Unfortunately, currently all Freesat receivers as well as Sky legacy boxes are INCOMPATIBLE with a Unicable LNB and signal.

However, many Unicable LNB's are available with additional *Legacy* outputs, allowing a single Unicable/SCR feed from the LNB, plus separate legacy outputs to connect to standard Freesat receivers.
