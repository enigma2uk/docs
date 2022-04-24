## Dish

Almost all satellite dishes in the UK are the Sky minidish variety (currently version/mark 4). These dishes are all perfectly acceptable for receiving all UK OTA broadcasts. However, depending on your dish, the LNB may need changing due to incompatibilities between the various platforms.

It's also worth noting that any existing cabling through your property will work just fine, regardless of your satellite dish configuration. It is all standard [coaxial satellite cable](https://en.wikipedia.org/wiki/Coaxial_cable) with [F-connectors](https://en.wikipedia.org/wiki/F_connector).

## LNB

The LNB, or [Low-Noise Block Downconverter](https://en.wikipedia.org/wiki/Low-noise_block_downconverter) is the little device, often called a gun that protrudes from your dish, to collect the signals reflected from the dish itself.

Obviously, all satellite signals are the same, but the LNB is responsible for receiving those signals and converting them into something that our set-top boxes understand. Some LNBs are considered dumb, and simply forward on everything to the tuner, assuming the tuner is capable of understanding and performing the conversion itself. Most LNBs are slightly smarter, in that they separate the various signal groups (high/low frequencies) before outputting to the receiver.

| LNB      | Sky Q        | Sky Legacy   | Freesat      | Enigma2 |
| -------- | ------------ | ------------ | ------------ | ------- |
| Sky Q    | Yes          |              |              |         |
| Freesat  | Partial [1]  | Yes          | Yes          | Yes [2] |
| Unicable |              | Possible [3] | Possible [3] | Yes     |

1. Some Sky Q installations may have a Hybrid LNR which is compatible with both Sky Q receivers and standard Freesat receivers.
2. Whilst Enigma2 can support Freesat LNBs, it is limited by the number of transponders, each provided to the tuner by the LNBs discrete outputs.
3. It is possible to purchase Unicode LNBs with Legacy outputs for supporting additional non-SCR receivers (e.g. Freesat).

### Sky Q (Wideband)

Sky Q uses Wideband LNB's which are currently only compatible with Sky Q receivers. If instructed prior to Sky Q installation, Sky will sometimes install a [Hybrid LNR](https://www.amazon.co.uk/Visiblewave-Hybrid-Output-Wideband-Freesat/dp/B07GS1Z2YP) which supports both the required inputs for the Sky Q receivers plus *Legacy* outputs for Freesat compatibility. In most situations, the standard LNB (usually with two cables) on a standard Sky Q installation will not work with any Freesat branded or Enigma2 receiver.

### Freesat (Dual/Quad/Octo Universal)

Current Freesat (and Sky legacy LNBs) are usually Dual, Quad or Octo LNBs, which provide separate discrete outputs to each receiving box.

Most Freesat tuners receive channels from multiple *Transponders* (called *Multiplexes* in the Freeview/DVB-T world). If your LNB has two discrete outputs and your receiver has two discrete inputs, it is capable of allowing the watching (or recording or streaming) of any channel on two transponders. These tuners are often looped back to allow additional channels on the same transponder to be watched (or recorded etc.) simultaneously.

There are currently three main satellite transponders used for UK OTA (Freesat) broadcasts:

* **Astra 2E**: BBC, ITV, Channel 4, etc.
* **Astra 2F**: CBS, Reality, GB News, etc.
* **Astra 2G**: Channel 5, BBC HD, ITV HD, Channel 4 HD, etc.

(Source: [https://en.satexpat.com/tv/uk/freesat/](https://en.satexpat.com/tv/uk/freesat/))

If your LNB and receiver only supports two transponders, you can only watch/record/stream from upto two transponders at a time, meaning you may not be able to record a programme on another transponder, if your tuner is currently tuned (or locked) to two already.

### Unicable (FCB/SCR)

[Unicable](https://en.wikipedia.org/wiki/Unicable) LNBs allow a single output and cable to carry the entire frequency range received from the dish. To use a Unicable LNB, you must have a tuner capable of receiving a FCB (Full Channel Broadcast) or SCR (Single Cable Receiver) signal. Unfortunately, currently all Freesat receivers as well as Sky legacy boxes are INCOMPATIBLE with a Unicable LNB and signal.

As Unicable LNBs deliver everything received from the dish in a single signal over a single cable, the tuner is responsible for processing the various different transponder feeds. FCB capable tuners mean that any combination of channels across any combination of transponders can be used for watching, recording and streaming etc.

Many Unicable LNB's are available with additional *Legacy* outputs, allowing a single Unicable/SCR feed from the LNB, plus separate legacy outputs to connect to standard Freesat receivers.
