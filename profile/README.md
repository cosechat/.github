# cosechat

Post-quantum mesh chat protocol. Inspired by [Reticulum](https://reticulum.network/) / LXMF.

Wire format is [CBOR](https://cbor.io/). Crypto is [COSE](https://www.rfc-editor.org/info/rfc9053/).

The basic idea is to follow existing standards, remain light enough to run well on lora and microcontrollers, and resist quantum attacks. Packets are small, and not really made for carrying larger amounts of data, like multimedia. Primary usecase is long-distance chat-message communication over lora and internet.