[@etclabscore/ethereum-json-rpc - v1.3.13](../README.md) › [Block](block.md)

# Interface: Block

The Block is the collection of relevant pieces of information (known as the block header), together with information corresponding to the comprised transactions, and a set of other block headers that are known to have a parent equal to the present block’s parent’s parent.

## Hierarchy

* **Block**

## Indexable

* \[ **k**: *string*\]: any

The Block is the collection of relevant pieces of information (known as the block header), together with information corresponding to the comprised transactions, and a set of other block headers that are known to have a parent equal to the present block’s parent’s parent.

## Index

### Properties

* [difficulty](block.md#optional-difficulty)
* [extraData](block.md#optional-extradata)
* [gasLimit](block.md#optional-gaslimit)
* [gasUsed](block.md#optional-gasused)
* [hash](block.md#optional-hash)
* [logsBloom](block.md#optional-logsbloom)
* [miner](block.md#optional-miner)
* [nonce](block.md#optional-nonce)
* [number](block.md#optional-number)
* [parentHash](block.md#optional-parenthash)
* [receiptsRoot](block.md#optional-receiptsroot)
* [sha3Uncles](block.md#optional-sha3uncles)
* [size](block.md#optional-size)
* [stateRoot](block.md#optional-stateroot)
* [timestamp](block.md#optional-timestamp)
* [totalDifficulty](block.md#optional-totaldifficulty)
* [transactions](block.md#optional-transactions)
* [transactionsRoot](block.md#optional-transactionsroot)
* [uncles](block.md#optional-uncles)

## Properties

### `Optional` difficulty

• **difficulty**? : *[BlockDifficulty](../README.md#blockdifficulty)*

Defined in index.d.ts:281

___

### `Optional` extraData

• **extraData**? : *[BlockExtraData](../README.md#blockextradata)*

Defined in index.d.ts:283

___

### `Optional` gasLimit

• **gasLimit**? : *[BlockGasLimit](../README.md#blockgaslimit)*

Defined in index.d.ts:285

___

### `Optional` gasUsed

• **gasUsed**? : *[BlockGasUsed](../README.md#blockgasused)*

Defined in index.d.ts:286

___

### `Optional` hash

• **hash**? : *[BlockHashOrNull](../README.md#blockhashornull)*

Defined in index.d.ts:272

___

### `Optional` logsBloom

• **logsBloom**? : *[BlockLogsBloom](../README.md#blocklogsbloom)*

Defined in index.d.ts:276

___

### `Optional` miner

• **miner**? : *[AddressOrNull](../README.md#addressornull)*

Defined in index.d.ts:280

___

### `Optional` nonce

• **nonce**? : *[NonceOrNull](../README.md#nonceornull)*

Defined in index.d.ts:274

___

### `Optional` number

• **number**? : *[BlockNumberOrNull](../README.md#blocknumberornull)*

Defined in index.d.ts:271

___

### `Optional` parentHash

• **parentHash**? : *[BlockHash](../README.md#blockhash)*

Defined in index.d.ts:273

___

### `Optional` receiptsRoot

• **receiptsRoot**? : *[BlockReceiptsRoot](../README.md#blockreceiptsroot)*

Defined in index.d.ts:279

___

### `Optional` sha3Uncles

• **sha3Uncles**? : *[BlockShaUncles](../README.md#blockshauncles)*

Defined in index.d.ts:275

___

### `Optional` size

• **size**? : *[BlockSize](../README.md#blocksize)*

Defined in index.d.ts:284

___

### `Optional` stateRoot

• **stateRoot**? : *[BlockStateRoot](../README.md#blockstateroot)*

Defined in index.d.ts:278

___

### `Optional` timestamp

• **timestamp**? : *[BlockTimeStamp](../README.md#blocktimestamp)*

Defined in index.d.ts:287

___

### `Optional` totalDifficulty

• **totalDifficulty**? : *[BlockTotalDifficulty](../README.md#blocktotaldifficulty)*

Defined in index.d.ts:282

___

### `Optional` transactions

• **transactions**? : *[TransactionsOrHashes](../README.md#transactionsorhashes)*

Defined in index.d.ts:288

___

### `Optional` transactionsRoot

• **transactionsRoot**? : *[BlockTransactionsRoot](../README.md#blocktransactionsroot)*

Defined in index.d.ts:277

___

### `Optional` uncles

• **uncles**? : *[UncleHashes](../README.md#unclehashes)*

Defined in index.d.ts:289
