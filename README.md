### Repository oveview

This is a categorized overview of the repositories I have worked on (created or contributed to).  

<details><summary>Controller Area Network bus</summary>

- [hardbyte/python-can](https://github.com/hardbyte/python-can) - Alongside a [PCAN-USB](https://www.peak-system.com/PCAN-USB.199.0.html?L=1) (physical bus) or [SocketCAN](https://docs.kernel.org/networking/can.html) alone (virtual bus), I use this package to send, recieve and log [CAN](https://en.wikipedia.org/wiki/CAN_bus) messages.
- [j-c-cook/cross-compile-python.md](https://gist.github.com/j-c-cook/2a291dc0bfaa2f6639272e344ff66e62) - Includes an outline for how to cross compile the Python language (the [cpython](https://github.com/python/cpython) implementation) for use on an obscure processor (armv7l). After cross-compiling, I was able to utilize `python-can`'s `SizedRolloverLogging` functionality on a remote device.  

</details>

<details><summary>Ground heat exchangers</summary>

- [pygfunction](https://github.com/MassimoCimmino/pygfunction) served as the backbone for a first of kind ground heat exchanger design tool [ghedt](https://github.com/j-c-cook/ghedt). 
- [cpgfunctionEP](https://github.com/j-c-cook/cpgfunctionEP) has been integrated into [EnergyPlus](https://github.com/NREL/EnergyPlus) as a third party application.
- [cpgfunction](https://github.com/j-c-cook/cpgfunction) was used to compute g-functions on a high performance computing cluster (HPCC).

</details>
