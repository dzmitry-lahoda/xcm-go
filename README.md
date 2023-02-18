# Overview

XCM message format and execution engine ported from [Polkadot](https://github.com/paritytech/polkadot/tree/master/xcm/xcm-executor) to IBC enabled Cosmos Go modules.

Consists of several packages:

`xcm-proto` - serialization and deserialization of XCM messages. XCM assumed to be ProtoBuf encoded by sender.

`xcm-executor-go` - IBC go module to execute XCM message

## Execution of message
