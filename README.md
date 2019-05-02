# QRL Message transaction encoding
List of supported encoding bytes for various services using QRL message transactions. 

Based upon [QIP002.](https://github.com/theQRL/qips/tree/master/2.Proposals/1.%20Open/2%20-%20MessageTransaction%20Encoded%20Message%20Standard)

For an encoded message transaction to be valid, the first two bytes of the 80 byte message body must be (in hex), "0x0F0F".
The next **two bytes** of the message denote the encoding of the **specific message type**.

i.e. where the encoding for specific message type is (in hex) "0x0000", a valid hexstring message would be:
 
`0F0F 0000 <remaining 76 bytes of message>`

## Supported encoding bytes for specific message type (hex)

- 0000 - reserved
- 0001 - reserved



