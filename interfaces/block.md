[@etclabscore/ethereum-json-rpc - v1.3.13](../README.md) › [Block](block.md)

# Interface: Block

The Block is the collection of relevant pieces of information (known as the block header), together with information corresponding to the comprised transactions, and a set of other block headers that are known to have a parent equal to the present block’s parent’s parent.

## Hierarchy

- **Block**

## Indexable

- \[ **k**: _string_\]: any

The Block is the collection of relevant pieces of information (known as the block header), together with information corresponding to the comprised transactions, and a set of other block headers that are known to have a parent equal to the present block’s parent’s parent.

## Index

### Properties

- [difficulty](block.md#optional-difficulty)
- [extraData](block.md#optional-extradata)
- [gasLimit](block.md#optional-gaslimit)
- [gasUsed](block.md#optional-gasused)
- [hash](block.md#optional-hash)
- [logsBloom](block.md#optional-logsbloom)
- [miner](block.md#optional-miner)
- [nonce](block.md#optional-nonce)
- [number](block.md#optional-number)
- [parentHash](block.md#optional-parenthash)
- [receiptsRoot](block.md#optional-receiptsroot)
- [sha3Uncles](block.md#optional-sha3uncles)
- [size](block.md#optional-size)
- [stateRoot](block.md#optional-stateroot)
- [timestamp](block.md#optional-timestamp)
- [totalDifficulty](block.md#optional-totaldifficulty)
- [transactions](block.md#optional-transactions)
- [transactionsRoot](block.md#optional-transactionsroot)
- [uncles](block.md#optional-uncles)

## Properties

### `Optional` difficulty

• **difficulty**? : _[BlockDifficulty](../README.md#blockdifficulty)_

Defined in index.d.ts:281

---

### `Optional` extraData

• **extraData**? : _[BlockExtraData](../README.md#blockextradata)_

Defined in index.d.ts:283

---

### `Optional` gasLimit

• **gasLimit**? : _[BlockGasLimit](../README.md#blockgaslimit)_

Defined in index.d.ts:285

---

### `Optional` gasUsed

• **gasUsed**? : _[BlockGasUsed](../README.md#blockgasused)_

Defined in index.d.ts:286

---

### `Optional` hash

• **hash**? : _[BlockHashOrNull](../README.md#blockhashornull)_

Defined in index.d.ts:272

---

### `Optional` logsBloom

• **logsBloom**? : _[BlockLogsBloom](../README.md#blocklogsbloom)_

Defined in index.d.ts:276

---

### `Optional` miner

• **miner**? : _[AddressOrNull](../README.md#addressornull)_

Defined in index.d.ts:280

---

### `Optional` nonce

• **nonce**? : _[NonceOrNull](../README.md#nonceornull)_

Defined in index.d.ts:274

---

### `Optional` number

• **number**? : _[BlockNumberOrNull](../README.md#blocknumberornull)_

Defined in index.d.ts:271

---

### `Optional` parentHash

• **parentHash**? : _[BlockHash](../README.md#blockhash)_

Defined in index.d.ts:273

---

### `Optional` receiptsRoot

• **receiptsRoot**? : _[BlockReceiptsRoot](../README.md#blockreceiptsroot)_

Defined in index.d.ts:279

---

### `Optional` sha3Uncles

• **sha3Uncles**? : _[BlockShaUncles](../README.md#blockshauncles)_

Defined in index.d.ts:275

---

### `Optional` size

• **size**? : _[BlockSize](../README.md#blocksize)_

Defined in index.d.ts:284

---

### `Optional` stateRoot

• **stateRoot**? : _[BlockStateRoot](../README.md#blockstateroot)_

Defined in index.d.ts:278

---

### `Optional` timestamp

• **timestamp**? : _[BlockTimeStamp](../README.md#blocktimestamp)_

Defined in index.d.ts:287

---

### `Optional` totalDifficulty

• **totalDifficulty**? : _[BlockTotalDifficulty](../README.md#blocktotaldifficulty)_

Defined in index.d.ts:282

---

### `Optional` transactions

• **transactions**? : _[TransactionsOrHashes](../README.md#transactionsorhashes)_

Defined in index.d.ts:288

---

### `Optional` transactionsRoot

• **transactionsRoot**? : _[BlockTransactionsRoot](../README.md#blocktransactionsroot)_

Defined in index.d.ts:277

---

### `Optional` uncles

• **uncles**? : _[UncleHashes](../README.md#unclehashes)_

Defined in index.d.ts:289
