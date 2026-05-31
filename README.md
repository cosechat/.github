# cosechat

Post-quantum mesh chat protocol. Inspired by [Reticulum](https://reticulum.network/) / LXMF.

Wire format is CBOR. Crypto is COSE.

The basic idea is to follow existing standards, remain light enough to run well on lora and microcontrollers, and resist quantum attacks. Packets are small, and not really made for carrying larger amounts of data. Primary usecase is long-distance communication over lora and internet.