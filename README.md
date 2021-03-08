[@etclabscore/ethereum-json-rpc - v1.3.13](README.md)

# @etclabscore/ethereum-json-rpc - v1.3.13

## Index

### Classes

* [EthereumJSONRPC](classes/ethereumjsonrpc.md)

### Interfaces

* [Block](interfaces/block.md)
* [Filter](interfaces/filter.md)
* [Log](interfaces/log.md)
* [Options](interfaces/options.md)
* [ProofAccount](interfaces/proofaccount.md)
* [Receipt](interfaces/receipt.md)
* [StorageProof](interfaces/storageproof.md)
* [SyncingData](interfaces/syncingdata.md)
* [Transaction](interfaces/transaction.md)

### Type aliases

* [Address](README.md#address)
* [AddressOrNull](README.md#addressornull)
* [Addresses](README.md#addresses)
* [AnyOfDataTransactionBlockNumberOrTagTransactionAddressBlockNumberBlockHashIsTransactionsIncludedBlockNumberOrTagIsTransactionsIncludedBlockHashBlockNumberOrTagAddressBlockNumberFilterIdFilterIdTransactionHashBlockHashIntegerBlockNumberOrTagIntegerFilterAddressPositionBlockNumberOrTagBlockHashIntegerBlockNumberOrTagIntegerTransactionHashAddressBlockNumberOrTagTransactionHashBlockHashIntegerBlockNumberIntegerBlockHashBlockNumberOrTagAddressStorageKeysBlockNumberOrTagFilterBytesDataWordDataWordNoncePowHashMixHashFilterIdClientVersionKeccakIsNetListeningNumConnectedPeersNetworkIdBlockNumberOrTagBytesChainIdAddressIntegerGasPriceResultIntegerOrNullBlockOrNullBlockOrNullIntegerOrNullIntegerOrNullBytesLogResultSetOfLogsBytesBytesBytesSetOfLogsDataWordTransactionOrNullTransactionOrNullTransactionOrNullNonceOrNullTransactionReceiptOrNullBlockOrNullBlockOrNullIntegerOrNullIntegerOrNullProofAccountOrNullGetWorkResultsIntegerBooleanVyG3AEThFilterIdIntegerFilterIdTransactionsIntegerKeccakBooleanVyG3AEThBooleanVyG3AEThIsSyncingResultBooleanVyG3AETh](README.md#anyofdatatransactionblocknumberortagtransactionaddressblocknumberblockhashistransactionsincludedblocknumberortagistransactionsincludedblockhashblocknumberortagaddressblocknumberfilteridfilteridtransactionhashblockhashintegerblocknumberortagintegerfilteraddresspositionblocknumberortagblockhashintegerblocknumberortagintegertransactionhashaddressblocknumberortagtransactionhashblockhashintegerblocknumberintegerblockhashblocknumberortagaddressstoragekeysblocknumberortagfilterbytesdataworddatawordnoncepowhashmixhashfilteridclientversionkeccakisnetlisteningnumconnectedpeersnetworkidblocknumberortagbyteschainidaddressintegergaspriceresultintegerornullblockornullblockornullintegerornullintegerornullbyteslogresultsetoflogsbytesbytesbytessetoflogsdatawordtransactionornulltransactionornulltransactionornullnonceornulltransactionreceiptornullblockornullblockornullintegerornullintegerornullproofaccountornullgetworkresultsintegerbooleanvyg3aethfilteridintegerfilteridtransactionsintegerkeccakbooleanvyg3aethbooleanvyg3aethissyncingresultbooleanvyg3aeth)
* [BlockDifficulty](README.md#blockdifficulty)
* [BlockExtraData](README.md#blockextradata)
* [BlockGasLimit](README.md#blockgaslimit)
* [BlockGasUsed](README.md#blockgasused)
* [BlockHash](README.md#blockhash)
* [BlockHashOrNull](README.md#blockhashornull)
* [BlockLogsBloom](README.md#blocklogsbloom)
* [BlockNumber](README.md#blocknumber)
* [BlockNumberOrNull](README.md#blocknumberornull)
* [BlockNumberOrTag](README.md#blocknumberortag)
* [BlockNumberTag](README.md#blocknumbertag)
* [BlockOrNull](README.md#blockornull)
* [BlockReceiptsRoot](README.md#blockreceiptsroot)
* [BlockShaUncles](README.md#blockshauncles)
* [BlockSize](README.md#blocksize)
* [BlockStateRoot](README.md#blockstateroot)
* [BlockTimeStamp](README.md#blocktimestamp)
* [BlockTotalDifficulty](README.md#blocktotaldifficulty)
* [BlockTransactionsRoot](README.md#blocktransactionsroot)
* [BloomFilter](README.md#bloomfilter)
* [BooleanVyG3AETh](README.md#booleanvyg3aeth)
* [Bytes](README.md#bytes)
* [ChainId](README.md#chainid)
* [ClientVersion](README.md#clientversion)
* [Data](README.md#data)
* [DataWord](README.md#dataword)
* [Difficulty](README.md#difficulty)
* [EthBlockNumber](README.md#ethblocknumber)
* [EthCall](README.md#ethcall)
* [EthChainId](README.md#ethchainid)
* [EthCoinbase](README.md#ethcoinbase)
* [EthEstimateGas](README.md#ethestimategas)
* [EthGasPrice](README.md#ethgasprice)
* [EthGetBalance](README.md#ethgetbalance)
* [EthGetBlockByHash](README.md#ethgetblockbyhash)
* [EthGetBlockByNumber](README.md#ethgetblockbynumber)
* [EthGetBlockTransactionCountByHash](README.md#ethgetblocktransactioncountbyhash)
* [EthGetBlockTransactionCountByNumber](README.md#ethgetblocktransactioncountbynumber)
* [EthGetCode](README.md#ethgetcode)
* [EthGetFilterChanges](README.md#ethgetfilterchanges)
* [EthGetFilterLogs](README.md#ethgetfilterlogs)
* [EthGetLogs](README.md#ethgetlogs)
* [EthGetProof](README.md#ethgetproof)
* [EthGetRawTransactionByBlockHashAndIndex](README.md#ethgetrawtransactionbyblockhashandindex)
* [EthGetRawTransactionByBlockNumberAndIndex](README.md#ethgetrawtransactionbyblocknumberandindex)
* [EthGetRawTransactionByHash](README.md#ethgetrawtransactionbyhash)
* [EthGetStorageAt](README.md#ethgetstorageat)
* [EthGetTransactionByBlockHashAndIndex](README.md#ethgettransactionbyblockhashandindex)
* [EthGetTransactionByBlockNumberAndIndex](README.md#ethgettransactionbyblocknumberandindex)
* [EthGetTransactionByHash](README.md#ethgettransactionbyhash)
* [EthGetTransactionCount](README.md#ethgettransactioncount)
* [EthGetTransactionReceipt](README.md#ethgettransactionreceipt)
* [EthGetUncleByBlockHashAndIndex](README.md#ethgetunclebyblockhashandindex)
* [EthGetUncleByBlockNumberAndIndex](README.md#ethgetunclebyblocknumberandindex)
* [EthGetUncleCountByBlockHash](README.md#ethgetunclecountbyblockhash)
* [EthGetUncleCountByBlockNumber](README.md#ethgetunclecountbyblocknumber)
* [EthGetWork](README.md#ethgetwork)
* [EthHashrate](README.md#ethhashrate)
* [EthMining](README.md#ethmining)
* [EthNewBlockFilter](README.md#ethnewblockfilter)
* [EthNewFilter](README.md#ethnewfilter)
* [EthNewPendingTransactionFilter](README.md#ethnewpendingtransactionfilter)
* [EthPendingTransactions](README.md#ethpendingtransactions)
* [EthProtocolVersion](README.md#ethprotocolversion)
* [EthSendRawTransaction](README.md#ethsendrawtransaction)
* [EthSubmitHashrate](README.md#ethsubmithashrate)
* [EthSubmitWork](README.md#ethsubmitwork)
* [EthSyncing](README.md#ethsyncing)
* [EthUninstallFilter](README.md#ethuninstallfilter)
* [FilterId](README.md#filterid)
* [From](README.md#from)
* [GasPriceResult](README.md#gaspriceresult)
* [GetWorkResults](README.md#getworkresults)
* [Integer](README.md#integer)
* [IntegerOrNull](README.md#integerornull)
* [IsNetListening](README.md#isnetlistening)
* [IsSyncingResult](README.md#issyncingresult)
* [IsTransactionsIncluded](README.md#istransactionsincluded)
* [Keccak](README.md#keccak)
* [LogAddress](README.md#logaddress)
* [LogData](README.md#logdata)
* [LogIndex](README.md#logindex)
* [LogIsRemoved](README.md#logisremoved)
* [LogResult](README.md#logresult)
* [LogTopics](README.md#logtopics)
* [Logs](README.md#logs)
* [MixHash](README.md#mixhash)
* [NetListening](README.md#netlistening)
* [NetPeerCount](README.md#netpeercount)
* [NetVersion](README.md#netversion)
* [NetworkId](README.md#networkid)
* [Nonce](README.md#nonce)
* [NonceOrNull](README.md#nonceornull)
* [Null](README.md#null)
* [NumConnectedPeers](README.md#numconnectedpeers)
* [OneOrArrayOfAddresses](README.md#oneorarrayofaddresses)
* [Position](README.md#position)
* [PowHash](README.md#powhash)
* [ProofAccountAddress](README.md#proofaccountaddress)
* [ProofAccountBalance](README.md#proofaccountbalance)
* [ProofAccountCodeHash](README.md#proofaccountcodehash)
* [ProofAccountNonce](README.md#proofaccountnonce)
* [ProofAccountOrNull](README.md#proofaccountornull)
* [ProofAccountStorageHash](README.md#proofaccountstoragehash)
* [ProofNode](README.md#proofnode)
* [ProofNodes](README.md#proofnodes)
* [ReceiptContractAddress](README.md#receiptcontractaddress)
* [ReceiptCumulativeGasUsed](README.md#receiptcumulativegasused)
* [ReceiptGasUsed](README.md#receiptgasused)
* [ReceiptPostTransactionState](README.md#receiptposttransactionstate)
* [ReceiptStatus](README.md#receiptstatus)
* [SeedHash](README.md#seedhash)
* [SetOfLogs](README.md#setoflogs)
* [StorageKeys](README.md#storagekeys)
* [StorageProofKey](README.md#storageproofkey)
* [StorageProofSet](README.md#storageproofset)
* [StorageProofValue](README.md#storageproofvalue)
* [SyncingDataCurrentBlock](README.md#syncingdatacurrentblock)
* [SyncingDataHighestBlock](README.md#syncingdatahighestblock)
* [SyncingDataKnownStates](README.md#syncingdataknownstates)
* [SyncingDataPulledStates](README.md#syncingdatapulledstates)
* [SyncingDataStartingBlock](README.md#syncingdatastartingblock)
* [To](README.md#to)
* [Topic](README.md#topic)
* [TransactionGas](README.md#transactiongas)
* [TransactionGasPrice](README.md#transactiongasprice)
* [TransactionHash](README.md#transactionhash)
* [TransactionIndex](README.md#transactionindex)
* [TransactionInput](README.md#transactioninput)
* [TransactionNonce](README.md#transactionnonce)
* [TransactionOrNull](README.md#transactionornull)
* [TransactionOrTransactionHash](README.md#transactionortransactionhash)
* [TransactionReceiptOrNull](README.md#transactionreceiptornull)
* [TransactionSigR](README.md#transactionsigr)
* [TransactionSigS](README.md#transactionsigs)
* [TransactionSigV](README.md#transactionsigv)
* [TransactionValue](README.md#transactionvalue)
* [Transactions](README.md#transactions)
* [TransactionsOrHashes](README.md#transactionsorhashes)
* [UncleHash](README.md#unclehash)
* [UncleHashes](README.md#unclehashes)
* [Web3ClientVersion](README.md#web3clientversion)
* [Web3Sha3](README.md#web3sha3)

## Type aliases

###  Address

Ƭ **Address**: *string*

Defined in index.d.ts:69

___

###  AddressOrNull

Ƭ **AddressOrNull**: *[Address](README.md#address) | [Null](README.md#null)*

Defined in index.d.ts:186

___

###  Addresses

Ƭ **Addresses**: *[Address](README.md#address)[]*

Defined in index.d.ts:123

List of contract addresses from which to monitor events

___

###  AnyOfDataTransactionBlockNumberOrTagTransactionAddressBlockNumberBlockHashIsTransactionsIncludedBlockNumberOrTagIsTransactionsIncludedBlockHashBlockNumberOrTagAddressBlockNumberFilterIdFilterIdTransactionHashBlockHashIntegerBlockNumberOrTagIntegerFilterAddressPositionBlockNumberOrTagBlockHashIntegerBlockNumberOrTagIntegerTransactionHashAddressBlockNumberOrTagTransactionHashBlockHashIntegerBlockNumberIntegerBlockHashBlockNumberOrTagAddressStorageKeysBlockNumberOrTagFilterBytesDataWordDataWordNoncePowHashMixHashFilterIdClientVersionKeccakIsNetListeningNumConnectedPeersNetworkIdBlockNumberOrTagBytesChainIdAddressIntegerGasPriceResultIntegerOrNullBlockOrNullBlockOrNullIntegerOrNullIntegerOrNullBytesLogResultSetOfLogsBytesBytesBytesSetOfLogsDataWordTransactionOrNullTransactionOrNullTransactionOrNullNonceOrNullTransactionReceiptOrNullBlockOrNullBlockOrNullIntegerOrNullIntegerOrNullProofAccountOrNullGetWorkResultsIntegerBooleanVyG3AEThFilterIdIntegerFilterIdTransactionsIntegerKeccakBooleanVyG3AEThBooleanVyG3AEThIsSyncingResultBooleanVyG3AETh

Ƭ **AnyOfDataTransactionBlockNumberOrTagTransactionAddressBlockNumberBlockHashIsTransactionsIncludedBlockNumberOrTagIsTransactionsIncludedBlockHashBlockNumberOrTagAddressBlockNumberFilterIdFilterIdTransactionHashBlockHashIntegerBlockNumberOrTagIntegerFilterAddressPositionBlockNumberOrTagBlockHashIntegerBlockNumberOrTagIntegerTransactionHashAddressBlockNumberOrTagTransactionHashBlockHashIntegerBlockNumberIntegerBlockHashBlockNumberOrTagAddressStorageKeysBlockNumberOrTagFilterBytesDataWordDataWordNoncePowHashMixHashFilterIdClientVersionKeccakIsNetListeningNumConnectedPeersNetworkIdBlockNumberOrTagBytesChainIdAddressIntegerGasPriceResultIntegerOrNullBlockOrNullBlockOrNullIntegerOrNullIntegerOrNullBytesLogResultSetOfLogsBytesBytesBytesSetOfLogsDataWordTransactionOrNullTransactionOrNullTransactionOrNullNonceOrNullTransactionReceiptOrNullBlockOrNullBlockOrNullIntegerOrNullIntegerOrNullProofAccountOrNullGetWorkResultsIntegerBooleanVyG3AEThFilterIdIntegerFilterIdTransactionsIntegerKeccakBooleanVyG3AEThBooleanVyG3AEThIsSyncingResultBooleanVyG3AETh**: *[Data](README.md#data) | [Transaction](interfaces/transaction.md) | [BlockNumberOrTag](README.md#blocknumberortag) | [Address](README.md#address) | [BlockNumber](README.md#blocknumber) | [BlockHash](README.md#blockhash) | [IsTransactionsIncluded](README.md#istransactionsincluded) | [FilterId](README.md#filterid) | [TransactionHash](README.md#transactionhash) | [Integer](README.md#integer) | [Filter](interfaces/filter.md) | [Position](README.md#position) | [StorageKeys](README.md#storagekeys) | [Bytes](README.md#bytes) | [DataWord](README.md#dataword) | [Nonce](README.md#nonce) | [PowHash](README.md#powhash) | [MixHash](README.md#mixhash) | [ClientVersion](README.md#clientversion) | [Keccak](README.md#keccak) | [IsNetListening](README.md#isnetlistening) | [NumConnectedPeers](README.md#numconnectedpeers) | [NetworkId](README.md#networkid) | [ChainId](README.md#chainid) | [GasPriceResult](README.md#gaspriceresult) | [IntegerOrNull](README.md#integerornull) | [BlockOrNull](README.md#blockornull) | [LogResult](README.md#logresult) | [SetOfLogs](README.md#setoflogs) | [TransactionOrNull](README.md#transactionornull) | [NonceOrNull](README.md#nonceornull) | [TransactionReceiptOrNull](README.md#transactionreceiptornull) | [ProofAccountOrNull](README.md#proofaccountornull) | [GetWorkResults](README.md#getworkresults) | [BooleanVyG3AETh](README.md#booleanvyg3aeth) | [Transactions](README.md#transactions) | [IsSyncingResult](README.md#issyncingresult)*

Defined in index.d.ts:625

Generated! Represents an alias to any of the provided schemas

___

###  BlockDifficulty

Ƭ **BlockDifficulty**: *string*

Defined in index.d.ts:192

Integer of the difficulty for this block

___

###  BlockExtraData

Ƭ **BlockExtraData**: *string*

Defined in index.d.ts:204

The 'extra data' field of this block

___

###  BlockGasLimit

Ƭ **BlockGasLimit**: *string*

Defined in index.d.ts:216

The maximum gas allowed in this block

___

###  BlockGasUsed

Ƭ **BlockGasUsed**: *string*

Defined in index.d.ts:222

The total used gas by all transactions in this block

___

###  BlockHash

Ƭ **BlockHash**: *string*

Defined in index.d.ts:148

The hex representation of the Keccak 256 of the RLP encoded block

___

###  BlockHashOrNull

Ƭ **BlockHashOrNull**: *[Keccak](README.md#keccak) | [Null](README.md#null)*

Defined in index.d.ts:20

The block hash or null when its the pending block

___

###  BlockLogsBloom

Ƭ **BlockLogsBloom**: *string*

Defined in index.d.ts:167

The bloom filter for the logs of the block or null when its the pending block

___

###  BlockNumber

Ƭ **BlockNumber**: *string*

Defined in index.d.ts:26

The hex representation of the block's height

___

###  BlockNumberOrNull

Ƭ **BlockNumberOrNull**: *[BlockNumber](README.md#blocknumber) | [Null](README.md#null)*

Defined in index.d.ts:32

The block number or null when its the pending block

___

###  BlockNumberOrTag

Ƭ **BlockNumberOrTag**: *[BlockNumber](README.md#blocknumber) | [BlockNumberTag](README.md#blocknumbertag)*

Defined in index.d.ts:539

___

###  BlockNumberTag

Ƭ **BlockNumberTag**: *"earliest" | "latest" | "pending"*

Defined in index.d.ts:117

The optional block height description

___

###  BlockOrNull

Ƭ **BlockOrNull**: *[Block](interfaces/block.md) | [Null](README.md#null)*

Defined in index.d.ts:606

___

###  BlockReceiptsRoot

Ƭ **BlockReceiptsRoot**: *string*

Defined in index.d.ts:185

The root of the receipts trie of the block

___

###  BlockShaUncles

Ƭ **BlockShaUncles**: *string*

Defined in index.d.ts:161

Keccak hash of the uncles data in the block

___

###  BlockSize

Ƭ **BlockSize**: *string*

Defined in index.d.ts:210

Integer the size of this block in bytes

___

###  BlockStateRoot

Ƭ **BlockStateRoot**: *string*

Defined in index.d.ts:179

The root of the final state trie of the block

___

###  BlockTimeStamp

Ƭ **BlockTimeStamp**: *string*

Defined in index.d.ts:228

The unix timestamp for when the block was collated

___

###  BlockTotalDifficulty

Ƭ **BlockTotalDifficulty**: *[Integer](README.md#integer) | [Null](README.md#null)*

Defined in index.d.ts:198

Integer of the total difficulty of the chain until this block

___

###  BlockTransactionsRoot

Ƭ **BlockTransactionsRoot**: *string*

Defined in index.d.ts:173

The root of the transactions trie of the block.

___

###  BloomFilter

Ƭ **BloomFilter**: *string*

Defined in index.d.ts:362

A 2048 bit bloom filter from the logs of the transaction. Each log sets 3 bits though taking the low-order 11 bits of each of the first three pairs of bytes in a Keccak 256 hash of the log's byte series

___

###  BooleanVyG3AETh

Ƭ **BooleanVyG3AETh**: *boolean*

Defined in index.d.ts:537

___

###  Bytes

Ƭ **Bytes**: *string*

Defined in index.d.ts:576

Hex representation of a variable length byte array

___

###  ChainId

Ƭ **ChainId**: *string*

Defined in index.d.ts:598

___

###  ClientVersion

Ƭ **ClientVersion**: *string*

Defined in index.d.ts:589

___

###  Data

Ƭ **Data**: *string*

Defined in index.d.ts:538

___

###  DataWord

Ƭ **DataWord**: *string*

Defined in index.d.ts:582

Hex representation of a 256 bit unit of data

___

###  Difficulty

Ƭ **Difficulty**: *string*

Defined in index.d.ts:493

The boundary condition ('target'), 2^256 / difficulty.

___

###  EthBlockNumber

Ƭ **EthBlockNumber**: *function*

Defined in index.d.ts:631

#### Type declaration:

▸ (): *Promise‹[BlockNumberOrTag](README.md#blocknumberortag)›*

___

###  EthCall

Ƭ **EthCall**: *function*

Defined in index.d.ts:632

#### Type declaration:

▸ (`transaction`: [Transaction](interfaces/transaction.md), `blockNumber`: [BlockNumberOrTag](README.md#blocknumberortag)): *Promise‹[Bytes](README.md#bytes)›*

**Parameters:**

Name | Type |
------ | ------ |
`transaction` | [Transaction](interfaces/transaction.md) |
`blockNumber` | [BlockNumberOrTag](README.md#blocknumberortag) |

___

###  EthChainId

Ƭ **EthChainId**: *function*

Defined in index.d.ts:633

#### Type declaration:

▸ (): *Promise‹[ChainId](README.md#chainid)›*

___

###  EthCoinbase

Ƭ **EthCoinbase**: *function*

Defined in index.d.ts:634

#### Type declaration:

▸ (): *Promise‹[Address](README.md#address)›*

___

###  EthEstimateGas

Ƭ **EthEstimateGas**: *function*

Defined in index.d.ts:635

#### Type declaration:

▸ (`transaction`: [Transaction](interfaces/transaction.md)): *Promise‹[Integer](README.md#integer)›*

**Parameters:**

Name | Type |
------ | ------ |
`transaction` | [Transaction](interfaces/transaction.md) |

___

###  EthGasPrice

Ƭ **EthGasPrice**: *function*

Defined in index.d.ts:636

#### Type declaration:

▸ (): *Promise‹[GasPriceResult](README.md#gaspriceresult)›*

___

###  EthGetBalance

Ƭ **EthGetBalance**: *function*

Defined in index.d.ts:637

#### Type declaration:

▸ (`address`: [Address](README.md#address), `blockNumber`: [BlockNumber](README.md#blocknumber)): *Promise‹[IntegerOrNull](README.md#integerornull)›*

**Parameters:**

Name | Type |
------ | ------ |
`address` | [Address](README.md#address) |
`blockNumber` | [BlockNumber](README.md#blocknumber) |

___

###  EthGetBlockByHash

Ƭ **EthGetBlockByHash**: *function*

Defined in index.d.ts:638

#### Type declaration:

▸ (`blockHash`: [BlockHash](README.md#blockhash), `includeTransactions`: [IsTransactionsIncluded](README.md#istransactionsincluded)): *Promise‹[BlockOrNull](README.md#blockornull)›*

**Parameters:**

Name | Type |
------ | ------ |
`blockHash` | [BlockHash](README.md#blockhash) |
`includeTransactions` | [IsTransactionsIncluded](README.md#istransactionsincluded) |

___

###  EthGetBlockByNumber

Ƭ **EthGetBlockByNumber**: *function*

Defined in index.d.ts:639

#### Type declaration:

▸ (`blockNumber`: [BlockNumberOrTag](README.md#blocknumberortag), `includeTransactions`: [IsTransactionsIncluded](README.md#istransactionsincluded)): *Promise‹[BlockOrNull](README.md#blockornull)›*

**Parameters:**

Name | Type |
------ | ------ |
`blockNumber` | [BlockNumberOrTag](README.md#blocknumberortag) |
`includeTransactions` | [IsTransactionsIncluded](README.md#istransactionsincluded) |

___

###  EthGetBlockTransactionCountByHash

Ƭ **EthGetBlockTransactionCountByHash**: *function*

Defined in index.d.ts:640

#### Type declaration:

▸ (`blockHash`: [BlockHash](README.md#blockhash)): *Promise‹[IntegerOrNull](README.md#integerornull)›*

**Parameters:**

Name | Type |
------ | ------ |
`blockHash` | [BlockHash](README.md#blockhash) |

___

###  EthGetBlockTransactionCountByNumber

Ƭ **EthGetBlockTransactionCountByNumber**: *function*

Defined in index.d.ts:641

#### Type declaration:

▸ (`blockNumber`: [BlockNumberOrTag](README.md#blocknumberortag)): *Promise‹[IntegerOrNull](README.md#integerornull)›*

**Parameters:**

Name | Type |
------ | ------ |
`blockNumber` | [BlockNumberOrTag](README.md#blocknumberortag) |

___

###  EthGetCode

Ƭ **EthGetCode**: *function*

Defined in index.d.ts:642

#### Type declaration:

▸ (`address`: [Address](README.md#address), `blockNumber`: [BlockNumber](README.md#blocknumber)): *Promise‹[Bytes](README.md#bytes)›*

**Parameters:**

Name | Type |
------ | ------ |
`address` | [Address](README.md#address) |
`blockNumber` | [BlockNumber](README.md#blocknumber) |

___

###  EthGetFilterChanges

Ƭ **EthGetFilterChanges**: *function*

Defined in index.d.ts:643

#### Type declaration:

▸ (`filterId`: [FilterId](README.md#filterid)): *Promise‹[LogResult](README.md#logresult)›*

**Parameters:**

Name | Type |
------ | ------ |
`filterId` | [FilterId](README.md#filterid) |

___

###  EthGetFilterLogs

Ƭ **EthGetFilterLogs**: *function*

Defined in index.d.ts:644

#### Type declaration:

▸ (`filterId`: [FilterId](README.md#filterid)): *Promise‹[SetOfLogs](README.md#setoflogs)›*

**Parameters:**

Name | Type |
------ | ------ |
`filterId` | [FilterId](README.md#filterid) |

___

###  EthGetLogs

Ƭ **EthGetLogs**: *function*

Defined in index.d.ts:648

#### Type declaration:

▸ (`filter`: [Filter](interfaces/filter.md)): *Promise‹[SetOfLogs](README.md#setoflogs)›*

**Parameters:**

Name | Type |
------ | ------ |
`filter` | [Filter](interfaces/filter.md) |

___

###  EthGetProof

Ƭ **EthGetProof**: *function*

Defined in index.d.ts:659

#### Type declaration:

▸ (`address`: [Address](README.md#address), `storageKeys`: [StorageKeys](README.md#storagekeys), `blockNumber`: [BlockNumberOrTag](README.md#blocknumberortag)): *Promise‹[ProofAccountOrNull](README.md#proofaccountornull)›*

**Parameters:**

Name | Type |
------ | ------ |
`address` | [Address](README.md#address) |
`storageKeys` | [StorageKeys](README.md#storagekeys) |
`blockNumber` | [BlockNumberOrTag](README.md#blocknumberortag) |

___

###  EthGetRawTransactionByBlockHashAndIndex

Ƭ **EthGetRawTransactionByBlockHashAndIndex**: *function*

Defined in index.d.ts:646

#### Type declaration:

▸ (`blockHash`: [BlockHash](README.md#blockhash), `index`: [Integer](README.md#integer)): *Promise‹[Bytes](README.md#bytes)›*

**Parameters:**

Name | Type |
------ | ------ |
`blockHash` | [BlockHash](README.md#blockhash) |
`index` | [Integer](README.md#integer) |

___

###  EthGetRawTransactionByBlockNumberAndIndex

Ƭ **EthGetRawTransactionByBlockNumberAndIndex**: *function*

Defined in index.d.ts:647

#### Type declaration:

▸ (`blockNumber`: [BlockNumberOrTag](README.md#blocknumberortag), `index`: [Integer](README.md#integer)): *Promise‹[Bytes](README.md#bytes)›*

**Parameters:**

Name | Type |
------ | ------ |
`blockNumber` | [BlockNumberOrTag](README.md#blocknumberortag) |
`index` | [Integer](README.md#integer) |

___

###  EthGetRawTransactionByHash

Ƭ **EthGetRawTransactionByHash**: *function*

Defined in index.d.ts:645

#### Type declaration:

▸ (`transactionHash`: [TransactionHash](README.md#transactionhash)): *Promise‹[Bytes](README.md#bytes)›*

**Parameters:**

Name | Type |
------ | ------ |
`transactionHash` | [TransactionHash](README.md#transactionhash) |

___

###  EthGetStorageAt

Ƭ **EthGetStorageAt**: *function*

Defined in index.d.ts:649

#### Type declaration:

▸ (`address`: [Address](README.md#address), `key`: [Position](README.md#position), `blockNumber`: [BlockNumberOrTag](README.md#blocknumberortag)): *Promise‹[DataWord](README.md#dataword)›*

**Parameters:**

Name | Type |
------ | ------ |
`address` | [Address](README.md#address) |
`key` | [Position](README.md#position) |
`blockNumber` | [BlockNumberOrTag](README.md#blocknumberortag) |

___

###  EthGetTransactionByBlockHashAndIndex

Ƭ **EthGetTransactionByBlockHashAndIndex**: *function*

Defined in index.d.ts:650

#### Type declaration:

▸ (`blockHash`: [BlockHash](README.md#blockhash), `index`: [Integer](README.md#integer)): *Promise‹[TransactionOrNull](README.md#transactionornull)›*

**Parameters:**

Name | Type |
------ | ------ |
`blockHash` | [BlockHash](README.md#blockhash) |
`index` | [Integer](README.md#integer) |

___

###  EthGetTransactionByBlockNumberAndIndex

Ƭ **EthGetTransactionByBlockNumberAndIndex**: *function*

Defined in index.d.ts:651

#### Type declaration:

▸ (`blockNumber`: [BlockNumberOrTag](README.md#blocknumberortag), `index`: [Integer](README.md#integer)): *Promise‹[TransactionOrNull](README.md#transactionornull)›*

**Parameters:**

Name | Type |
------ | ------ |
`blockNumber` | [BlockNumberOrTag](README.md#blocknumberortag) |
`index` | [Integer](README.md#integer) |

___

###  EthGetTransactionByHash

Ƭ **EthGetTransactionByHash**: *function*

Defined in index.d.ts:652

#### Type declaration:

▸ (`transactionHash`: [TransactionHash](README.md#transactionhash)): *Promise‹[TransactionOrNull](README.md#transactionornull)›*

**Parameters:**

Name | Type |
------ | ------ |
`transactionHash` | [TransactionHash](README.md#transactionhash) |

___

###  EthGetTransactionCount

Ƭ **EthGetTransactionCount**: *function*

Defined in index.d.ts:653

#### Type declaration:

▸ (`address`: [Address](README.md#address), `blockNumber`: [BlockNumberOrTag](README.md#blocknumberortag)): *Promise‹[NonceOrNull](README.md#nonceornull)›*

**Parameters:**

Name | Type |
------ | ------ |
`address` | [Address](README.md#address) |
`blockNumber` | [BlockNumberOrTag](README.md#blocknumberortag) |

___

###  EthGetTransactionReceipt

Ƭ **EthGetTransactionReceipt**: *function*

Defined in index.d.ts:654

#### Type declaration:

▸ (`transactionHash`: [TransactionHash](README.md#transactionhash)): *Promise‹[TransactionReceiptOrNull](README.md#transactionreceiptornull)›*

**Parameters:**

Name | Type |
------ | ------ |
`transactionHash` | [TransactionHash](README.md#transactionhash) |

___

###  EthGetUncleByBlockHashAndIndex

Ƭ **EthGetUncleByBlockHashAndIndex**: *function*

Defined in index.d.ts:655

#### Type declaration:

▸ (`blockHash`: [BlockHash](README.md#blockhash), `index`: [Integer](README.md#integer)): *Promise‹[BlockOrNull](README.md#blockornull)›*

**Parameters:**

Name | Type |
------ | ------ |
`blockHash` | [BlockHash](README.md#blockhash) |
`index` | [Integer](README.md#integer) |

___

###  EthGetUncleByBlockNumberAndIndex

Ƭ **EthGetUncleByBlockNumberAndIndex**: *function*

Defined in index.d.ts:656

#### Type declaration:

▸ (`uncleBlockNumber`: [BlockNumber](README.md#blocknumber), `index`: [Integer](README.md#integer)): *Promise‹[BlockOrNull](README.md#blockornull)›*

**Parameters:**

Name | Type |
------ | ------ |
`uncleBlockNumber` | [BlockNumber](README.md#blocknumber) |
`index` | [Integer](README.md#integer) |

___

###  EthGetUncleCountByBlockHash

Ƭ **EthGetUncleCountByBlockHash**: *function*

Defined in index.d.ts:657

#### Type declaration:

▸ (`blockHash`: [BlockHash](README.md#blockhash)): *Promise‹[IntegerOrNull](README.md#integerornull)›*

**Parameters:**

Name | Type |
------ | ------ |
`blockHash` | [BlockHash](README.md#blockhash) |

___

###  EthGetUncleCountByBlockNumber

Ƭ **EthGetUncleCountByBlockNumber**: *function*

Defined in index.d.ts:658

#### Type declaration:

▸ (`blockNumber`: [BlockNumberOrTag](README.md#blocknumberortag)): *Promise‹[IntegerOrNull](README.md#integerornull)›*

**Parameters:**

Name | Type |
------ | ------ |
`blockNumber` | [BlockNumberOrTag](README.md#blocknumberortag) |

___

###  EthGetWork

Ƭ **EthGetWork**: *function*

Defined in index.d.ts:660

#### Type declaration:

▸ (): *Promise‹[GetWorkResults](README.md#getworkresults)›*

___

###  EthHashrate

Ƭ **EthHashrate**: *function*

Defined in index.d.ts:661

#### Type declaration:

▸ (): *Promise‹[Integer](README.md#integer)›*

___

###  EthMining

Ƭ **EthMining**: *function*

Defined in index.d.ts:662

#### Type declaration:

▸ (): *Promise‹[BooleanVyG3AETh](README.md#booleanvyg3aeth)›*

___

###  EthNewBlockFilter

Ƭ **EthNewBlockFilter**: *function*

Defined in index.d.ts:663

#### Type declaration:

▸ (): *Promise‹[FilterId](README.md#filterid)›*

___

###  EthNewFilter

Ƭ **EthNewFilter**: *function*

Defined in index.d.ts:664

#### Type declaration:

▸ (`filter`: [Filter](interfaces/filter.md)): *Promise‹[Integer](README.md#integer)›*

**Parameters:**

Name | Type |
------ | ------ |
`filter` | [Filter](interfaces/filter.md) |

___

###  EthNewPendingTransactionFilter

Ƭ **EthNewPendingTransactionFilter**: *function*

Defined in index.d.ts:665

#### Type declaration:

▸ (): *Promise‹[FilterId](README.md#filterid)›*

___

###  EthPendingTransactions

Ƭ **EthPendingTransactions**: *function*

Defined in index.d.ts:666

#### Type declaration:

▸ (): *Promise‹[Transactions](README.md#transactions)›*

___

###  EthProtocolVersion

Ƭ **EthProtocolVersion**: *function*

Defined in index.d.ts:667

#### Type declaration:

▸ (): *Promise‹[Integer](README.md#integer)›*

___

###  EthSendRawTransaction

Ƭ **EthSendRawTransaction**: *function*

Defined in index.d.ts:668

#### Type declaration:

▸ (`signedTransactionData`: [Bytes](README.md#bytes)): *Promise‹[Keccak](README.md#keccak)›*

**Parameters:**

Name | Type |
------ | ------ |
`signedTransactionData` | [Bytes](README.md#bytes) |

___

###  EthSubmitHashrate

Ƭ **EthSubmitHashrate**: *function*

Defined in index.d.ts:669

#### Type declaration:

▸ (`hashRate`: [DataWord](README.md#dataword), `id`: [DataWord](README.md#dataword)): *Promise‹[BooleanVyG3AETh](README.md#booleanvyg3aeth)›*

**Parameters:**

Name | Type |
------ | ------ |
`hashRate` | [DataWord](README.md#dataword) |
`id` | [DataWord](README.md#dataword) |

___

###  EthSubmitWork

Ƭ **EthSubmitWork**: *function*

Defined in index.d.ts:670

#### Type declaration:

▸ (`nonce`: [Nonce](README.md#nonce), `powHash`: [PowHash](README.md#powhash), `mixHash`: [MixHash](README.md#mixhash)): *Promise‹[BooleanVyG3AETh](README.md#booleanvyg3aeth)›*

**Parameters:**

Name | Type |
------ | ------ |
`nonce` | [Nonce](README.md#nonce) |
`powHash` | [PowHash](README.md#powhash) |
`mixHash` | [MixHash](README.md#mixhash) |

___

###  EthSyncing

Ƭ **EthSyncing**: *function*

Defined in index.d.ts:671

#### Type declaration:

▸ (): *Promise‹[IsSyncingResult](README.md#issyncingresult)›*

___

###  EthUninstallFilter

Ƭ **EthUninstallFilter**: *function*

Defined in index.d.ts:672

#### Type declaration:

▸ (`filterId`: [FilterId](README.md#filterid)): *Promise‹[BooleanVyG3AETh](README.md#booleanvyg3aeth)›*

**Parameters:**

Name | Type |
------ | ------ |
`filterId` | [FilterId](README.md#filterid) |

___

###  FilterId

Ƭ **FilterId**: *string*

Defined in index.d.ts:546

An identifier used to reference the filter.

___

###  From

Ƭ **From**: *string*

Defined in index.d.ts:38

The sender of the transaction

___

###  GasPriceResult

Ƭ **GasPriceResult**: *string*

Defined in index.d.ts:604

Integer of the current gas price

___

###  GetWorkResults

Ƭ **GetWorkResults**: *[[PowHash](README.md#powhash), [SeedHash](README.md#seedhash), [Difficulty](README.md#difficulty)]*

Defined in index.d.ts:612

___

###  Integer

Ƭ **Integer**: *string*

Defined in index.d.ts:81

Hex representation of the integer

___

###  IntegerOrNull

Ƭ **IntegerOrNull**: *[Integer](README.md#integer) | [Null](README.md#null)*

Defined in index.d.ts:605

___

###  IsNetListening

Ƭ **IsNetListening**: *boolean*

Defined in index.d.ts:590

___

###  IsSyncingResult

Ƭ **IsSyncingResult**: *[SyncingData](interfaces/syncingdata.md) | [BooleanVyG3AETh](README.md#booleanvyg3aeth)*

Defined in index.d.ts:619

___

###  IsTransactionsIncluded

Ƭ **IsTransactionsIncluded**: *boolean*

Defined in index.d.ts:540

___

###  Keccak

Ƭ **Keccak**: *string*

Defined in index.d.ts:8

Hex representation of a Keccak 256 hash

___

###  LogAddress

Ƭ **LogAddress**: *string*

Defined in index.d.ts:297

Sender of the transaction

___

###  LogData

Ƭ **LogData**: *string*

Defined in index.d.ts:303

The data/input string sent along with the transaction

___

###  LogIndex

Ƭ **LogIndex**: *string*

Defined in index.d.ts:309

The index of the event within its transaction, null when its pending

___

###  LogIsRemoved

Ƭ **LogIsRemoved**: *boolean*

Defined in index.d.ts:315

Whether or not the log was orphaned off the main chain

___

###  LogResult

Ƭ **LogResult**: *[Log](interfaces/log.md)[]*

Defined in index.d.ts:607

___

###  LogTopics

Ƭ **LogTopics**: *[Topic](README.md#topic)[]*

Defined in index.d.ts:136

Topics are order-dependent. Each topic can also be an array of DATA with 'or' options.

___

###  Logs

Ƭ **Logs**: *[Log](interfaces/log.md)[]*

Defined in index.d.ts:356

An array of all the logs triggered during the transaction

___

###  MixHash

Ƭ **MixHash**: *string*

Defined in index.d.ts:588

The mix digest.

___

###  NetListening

Ƭ **NetListening**: *function*

Defined in index.d.ts:628

#### Type declaration:

▸ (): *Promise‹[IsNetListening](README.md#isnetlistening)›*

___

###  NetPeerCount

Ƭ **NetPeerCount**: *function*

Defined in index.d.ts:629

#### Type declaration:

▸ (): *Promise‹[NumConnectedPeers](README.md#numconnectedpeers)›*

___

###  NetVersion

Ƭ **NetVersion**: *function*

Defined in index.d.ts:630

#### Type declaration:

▸ (): *Promise‹[NetworkId](README.md#networkid)›*

___

###  NetworkId

Ƭ **NetworkId**: *string*

Defined in index.d.ts:597

___

###  Nonce

Ƭ **Nonce**: *string*

Defined in index.d.ts:154

A number only to be used once

___

###  NonceOrNull

Ƭ **NonceOrNull**: *[Nonce](README.md#nonce) | [Null](README.md#null)*

Defined in index.d.ts:155

___

###  Null

Ƭ **Null**: *null*

Defined in index.d.ts:14

Null

___

###  NumConnectedPeers

Ƭ **NumConnectedPeers**: *string*

Defined in index.d.ts:596

Hex representation of number of connected peers

___

###  OneOrArrayOfAddresses

Ƭ **OneOrArrayOfAddresses**: *[Address](README.md#address) | [Addresses](README.md#addresses)*

Defined in index.d.ts:124

___

###  Position

Ƭ **Position**: *string*

Defined in index.d.ts:564

Hex representation of the storage slot where the variable exists

___

###  PowHash

Ƭ **PowHash**: *string*

Defined in index.d.ts:481

Current block header PoW hash.

___

###  ProofAccountAddress

Ƭ **ProofAccountAddress**: *string*

Defined in index.d.ts:401

The address of the account or contract of the request

___

###  ProofAccountBalance

Ƭ **ProofAccountBalance**: *string*

Defined in index.d.ts:419

The Ether balance of the account or contract of the request

___

###  ProofAccountCodeHash

Ƭ **ProofAccountCodeHash**: *string*

Defined in index.d.ts:425

The code hash of the contract of the request (keccak(NULL) if external account)

___

###  ProofAccountNonce

Ƭ **ProofAccountNonce**: *string*

Defined in index.d.ts:431

The transaction count of the account or contract of the request

___

###  ProofAccountOrNull

Ƭ **ProofAccountOrNull**: *[ProofAccount](interfaces/proofaccount.md) | [Null](README.md#null)*

Defined in index.d.ts:611

___

###  ProofAccountStorageHash

Ƭ **ProofAccountStorageHash**: *string*

Defined in index.d.ts:437

The storage hash of the contract of the request (keccak(rlp(NULL)) if external account)

___

###  ProofNode

Ƭ **ProofNode**: *string*

Defined in index.d.ts:407

An individual node used to prove a path down a merkle-patricia-tree

___

###  ProofNodes

Ƭ **ProofNodes**: *[ProofNode](README.md#proofnode)[]*

Defined in index.d.ts:413

The set of node values needed to traverse a patricia merkle tree (from root to leaf) to retrieve a value

___

###  ReceiptContractAddress

Ƭ **ReceiptContractAddress**: *[Address](README.md#address) | [Null](README.md#null)*

Defined in index.d.ts:338

The contract address created, if the transaction was a contract creation, otherwise null

___

###  ReceiptCumulativeGasUsed

Ƭ **ReceiptCumulativeGasUsed**: *string*

Defined in index.d.ts:344

The gas units used by the transaction

___

###  ReceiptGasUsed

Ƭ **ReceiptGasUsed**: *string*

Defined in index.d.ts:350

The total gas used by the transaction

___

###  ReceiptPostTransactionState

Ƭ **ReceiptPostTransactionState**: *string*

Defined in index.d.ts:368

The intermediate stateRoot directly after transaction execution.

___

###  ReceiptStatus

Ƭ **ReceiptStatus**: *boolean*

Defined in index.d.ts:374

Whether or not the transaction threw an error.

___

###  SeedHash

Ƭ **SeedHash**: *string*

Defined in index.d.ts:487

The seed hash used for the DAG.

___

###  SetOfLogs

Ƭ **SetOfLogs**: *[Log](interfaces/log.md)[]*

Defined in index.d.ts:608

___

###  StorageKeys

Ƭ **StorageKeys**: *any*

Defined in index.d.ts:570

A storage key is indexed from the solidity compiler by the order it is declared. For mappings it uses the keccak of the mapping key with its position (and recursively for X-dimensional mappings)

___

###  StorageProofKey

Ƭ **StorageProofKey**: *string*

Defined in index.d.ts:142

The key used to get the storage slot in its account tree.

___

###  StorageProofSet

Ƭ **StorageProofSet**: *[StorageProof](interfaces/storageproof.md)[]*

Defined in index.d.ts:460

Current block header PoW hash.

___

###  StorageProofValue

Ƭ **StorageProofValue**: *string*

Defined in index.d.ts:443

The value of the storage slot in its account tree

___

###  SyncingDataCurrentBlock

Ƭ **SyncingDataCurrentBlock**: *string*

Defined in index.d.ts:505

The current block, same as eth_blockNumber

___

###  SyncingDataHighestBlock

Ƭ **SyncingDataHighestBlock**: *string*

Defined in index.d.ts:511

The estimated highest block

___

###  SyncingDataKnownStates

Ƭ **SyncingDataKnownStates**: *string*

Defined in index.d.ts:517

The known states

___

###  SyncingDataPulledStates

Ƭ **SyncingDataPulledStates**: *string*

Defined in index.d.ts:523

The pulled states

___

###  SyncingDataStartingBlock

Ƭ **SyncingDataStartingBlock**: *string*

Defined in index.d.ts:499

Block at which the import started (will only be reset, after the sync reached his head)

___

###  To

Ƭ **To**: *[Address](README.md#address) | [Null](README.md#null)*

Defined in index.d.ts:75

Destination address of the transaction. Null if it was a contract create.

___

###  Topic

Ƭ **Topic**: *string*

Defined in index.d.ts:130

32 Bytes DATA of indexed log arguments. (In solidity: The first topic is the hash of the signature of the event (e.g. Deposit(address,bytes32,uint256))

___

###  TransactionGas

Ƭ **TransactionGas**: *string*

Defined in index.d.ts:44

The gas limit provided by the sender in Wei

___

###  TransactionGasPrice

Ƭ **TransactionGasPrice**: *string*

Defined in index.d.ts:50

The gas price willing to be paid by the sender in Wei

___

###  TransactionHash

Ƭ **TransactionHash**: *string*

Defined in index.d.ts:56

Keccak 256 Hash of the RLP encoding of a transaction

___

###  TransactionIndex

Ƭ **TransactionIndex**: *[Integer](README.md#integer) | [Null](README.md#null)*

Defined in index.d.ts:87

The index of the transaction. null when its pending

___

###  TransactionInput

Ƭ **TransactionInput**: *string*

Defined in index.d.ts:62

The data field sent with the transaction

___

###  TransactionNonce

Ƭ **TransactionNonce**: *string*

Defined in index.d.ts:68

The total number of prior transactions made by the sender

___

###  TransactionOrNull

Ƭ **TransactionOrNull**: *[Transaction](interfaces/transaction.md) | [Null](README.md#null)*

Defined in index.d.ts:609

___

###  TransactionOrTransactionHash

Ƭ **TransactionOrTransactionHash**: *[Transaction](interfaces/transaction.md) | [TransactionHash](README.md#transactionhash)*

Defined in index.d.ts:246

___

###  TransactionReceiptOrNull

Ƭ **TransactionReceiptOrNull**: *[Receipt](interfaces/receipt.md) | [Null](README.md#null)*

Defined in index.d.ts:610

___

###  TransactionSigR

Ƭ **TransactionSigR**: *string*

Defined in index.d.ts:105

ECDSA signature r

___

###  TransactionSigS

Ƭ **TransactionSigS**: *string*

Defined in index.d.ts:111

ECDSA signature s

___

###  TransactionSigV

Ƭ **TransactionSigV**: *string*

Defined in index.d.ts:99

ECDSA recovery id

___

###  TransactionValue

Ƭ **TransactionValue**: *string*

Defined in index.d.ts:93

Value of Ether being transferred in Wei

___

###  Transactions

Ƭ **Transactions**: *[Transaction](interfaces/transaction.md)[]*

Defined in index.d.ts:618

An array of transactions

___

###  TransactionsOrHashes

Ƭ **TransactionsOrHashes**: *[TransactionOrTransactionHash](README.md#transactionortransactionhash)[]*

Defined in index.d.ts:252

Array of transaction objects, or 32 Bytes transaction hashes depending on the last given parameter

___

###  UncleHash

Ƭ **UncleHash**: *string*

Defined in index.d.ts:258

Block hash of the RLP encoding of an uncle block

___

###  UncleHashes

Ƭ **UncleHashes**: *[UncleHash](README.md#unclehash)[]*

Defined in index.d.ts:264

Array of uncle hashes

___

###  Web3ClientVersion

Ƭ **Web3ClientVersion**: *function*

Defined in index.d.ts:626

#### Type declaration:

▸ (): *Promise‹[ClientVersion](README.md#clientversion)›*

___

###  Web3Sha3

Ƭ **Web3Sha3**: *function*

Defined in index.d.ts:627

#### Type declaration:

▸ (`data`: [Data](README.md#data)): *Promise‹[Keccak](README.md#keccak)›*

**Parameters:**

Name | Type |
------ | ------ |
`data` | [Data](README.md#data) |
