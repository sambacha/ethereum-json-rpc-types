[@etclabscore/ethereum-json-rpc - v1.3.13](../README.md) › [EthereumJSONRPC](ethereumjsonrpc.md)

# Class: EthereumJSONRPC

## Hierarchy

* **EthereumJSONRPC**

## Index

### Constructors

* [constructor](ethereumjsonrpc.md#constructor)

### Properties

* [eth_blockNumber](ethereumjsonrpc.md#eth_blocknumber)
* [eth_call](ethereumjsonrpc.md#eth_call)
* [eth_chainId](ethereumjsonrpc.md#eth_chainid)
* [eth_coinbase](ethereumjsonrpc.md#eth_coinbase)
* [eth_estimateGas](ethereumjsonrpc.md#eth_estimategas)
* [eth_gasPrice](ethereumjsonrpc.md#eth_gasprice)
* [eth_getBalance](ethereumjsonrpc.md#eth_getbalance)
* [eth_getBlockByHash](ethereumjsonrpc.md#eth_getblockbyhash)
* [eth_getBlockByNumber](ethereumjsonrpc.md#eth_getblockbynumber)
* [eth_getBlockTransactionCountByHash](ethereumjsonrpc.md#eth_getblocktransactioncountbyhash)
* [eth_getBlockTransactionCountByNumber](ethereumjsonrpc.md#eth_getblocktransactioncountbynumber)
* [eth_getCode](ethereumjsonrpc.md#eth_getcode)
* [eth_getFilterChanges](ethereumjsonrpc.md#eth_getfilterchanges)
* [eth_getFilterLogs](ethereumjsonrpc.md#eth_getfilterlogs)
* [eth_getLogs](ethereumjsonrpc.md#eth_getlogs)
* [eth_getProof](ethereumjsonrpc.md#eth_getproof)
* [eth_getRawTransactionByBlockHashAndIndex](ethereumjsonrpc.md#eth_getrawtransactionbyblockhashandindex)
* [eth_getRawTransactionByBlockNumberAndIndex](ethereumjsonrpc.md#eth_getrawtransactionbyblocknumberandindex)
* [eth_getRawTransactionByHash](ethereumjsonrpc.md#eth_getrawtransactionbyhash)
* [eth_getStorageAt](ethereumjsonrpc.md#eth_getstorageat)
* [eth_getTransactionByBlockHashAndIndex](ethereumjsonrpc.md#eth_gettransactionbyblockhashandindex)
* [eth_getTransactionByBlockNumberAndIndex](ethereumjsonrpc.md#eth_gettransactionbyblocknumberandindex)
* [eth_getTransactionByHash](ethereumjsonrpc.md#eth_gettransactionbyhash)
* [eth_getTransactionCount](ethereumjsonrpc.md#eth_gettransactioncount)
* [eth_getTransactionReceipt](ethereumjsonrpc.md#eth_gettransactionreceipt)
* [eth_getUncleByBlockHashAndIndex](ethereumjsonrpc.md#eth_getunclebyblockhashandindex)
* [eth_getUncleByBlockNumberAndIndex](ethereumjsonrpc.md#eth_getunclebyblocknumberandindex)
* [eth_getUncleCountByBlockHash](ethereumjsonrpc.md#eth_getunclecountbyblockhash)
* [eth_getUncleCountByBlockNumber](ethereumjsonrpc.md#eth_getunclecountbyblocknumber)
* [eth_getWork](ethereumjsonrpc.md#eth_getwork)
* [eth_hashrate](ethereumjsonrpc.md#eth_hashrate)
* [eth_mining](ethereumjsonrpc.md#eth_mining)
* [eth_newBlockFilter](ethereumjsonrpc.md#eth_newblockfilter)
* [eth_newFilter](ethereumjsonrpc.md#eth_newfilter)
* [eth_newPendingTransactionFilter](ethereumjsonrpc.md#eth_newpendingtransactionfilter)
* [eth_pendingTransactions](ethereumjsonrpc.md#eth_pendingtransactions)
* [eth_protocolVersion](ethereumjsonrpc.md#eth_protocolversion)
* [eth_sendRawTransaction](ethereumjsonrpc.md#eth_sendrawtransaction)
* [eth_submitHashrate](ethereumjsonrpc.md#eth_submithashrate)
* [eth_submitWork](ethereumjsonrpc.md#eth_submitwork)
* [eth_syncing](ethereumjsonrpc.md#eth_syncing)
* [eth_uninstallFilter](ethereumjsonrpc.md#eth_uninstallfilter)
* [net_listening](ethereumjsonrpc.md#net_listening)
* [net_peerCount](ethereumjsonrpc.md#net_peercount)
* [net_version](ethereumjsonrpc.md#net_version)
* [rpc](ethereumjsonrpc.md#rpc)
* [transport](ethereumjsonrpc.md#transport)
* [web3_clientVersion](ethereumjsonrpc.md#web3_clientversion)
* [web3_sha3](ethereumjsonrpc.md#web3_sha3)
* [openrpcDocument](ethereumjsonrpc.md#static-openrpcdocument)

### Methods

* [onError](ethereumjsonrpc.md#onerror)
* [onNotification](ethereumjsonrpc.md#onnotification)
* [setDefaultTimeout](ethereumjsonrpc.md#setdefaulttimeout)
* [startBatch](ethereumjsonrpc.md#startbatch)
* [stopBatch](ethereumjsonrpc.md#stopbatch)

## Constructors

###  constructor

\+ **new EthereumJSONRPC**(`options`: [Options](../interfaces/options.md)): *[EthereumJSONRPC](ethereumjsonrpc.md)*

Defined in index.d.ts:687

**Parameters:**

Name | Type |
------ | ------ |
`options` | [Options](../interfaces/options.md) |

**Returns:** *[EthereumJSONRPC](ethereumjsonrpc.md)*

## Properties

###  eth_blockNumber

• **eth_blockNumber**: *[EthBlockNumber](../README.md#ethblocknumber)*

Defined in index.d.ts:761

Returns the number of most recent block.

___

###  eth_call

• **eth_call**: *[EthCall](../README.md#ethcall)*

Defined in index.d.ts:765

Executes a new message call (locally) immediately without creating a transaction on the block chain.

___

###  eth_chainId

• **eth_chainId**: *[EthChainId](../README.md#ethchainid)*

Defined in index.d.ts:769

Returns the currently configured chain id

___

###  eth_coinbase

• **eth_coinbase**: *[EthCoinbase](../README.md#ethcoinbase)*

Defined in index.d.ts:773

Returns the client coinbase address.

___

###  eth_estimateGas

• **eth_estimateGas**: *[EthEstimateGas](../README.md#ethestimategas)*

Defined in index.d.ts:777

Generates and returns an estimate of how much gas is necessary to allow the transaction to complete. The transaction will not be added to the blockchain. Note that the estimate may be significantly more than the amount of gas actually used by the transaction, for a variety of reasons including EVM mechanics and node performance.

___

###  eth_gasPrice

• **eth_gasPrice**: *[EthGasPrice](../README.md#ethgasprice)*

Defined in index.d.ts:781

Returns the current price per gas in wei

___

###  eth_getBalance

• **eth_getBalance**: *[EthGetBalance](../README.md#ethgetbalance)*

Defined in index.d.ts:785

Returns Ether balance of a given or account or contract

___

###  eth_getBlockByHash

• **eth_getBlockByHash**: *[EthGetBlockByHash](../README.md#ethgetblockbyhash)*

Defined in index.d.ts:789

Gets a block for a given hash

___

###  eth_getBlockByNumber

• **eth_getBlockByNumber**: *[EthGetBlockByNumber](../README.md#ethgetblockbynumber)*

Defined in index.d.ts:793

Gets a block for a given number

___

###  eth_getBlockTransactionCountByHash

• **eth_getBlockTransactionCountByHash**: *[EthGetBlockTransactionCountByHash](../README.md#ethgetblocktransactioncountbyhash)*

Defined in index.d.ts:797

Returns the number of transactions in a block from a block matching the given block hash.

___

###  eth_getBlockTransactionCountByNumber

• **eth_getBlockTransactionCountByNumber**: *[EthGetBlockTransactionCountByNumber](../README.md#ethgetblocktransactioncountbynumber)*

Defined in index.d.ts:801

Returns the number of transactions in a block from a block matching the given block number.

___

###  eth_getCode

• **eth_getCode**: *[EthGetCode](../README.md#ethgetcode)*

Defined in index.d.ts:805

Returns code at a given contract address

___

###  eth_getFilterChanges

• **eth_getFilterChanges**: *[EthGetFilterChanges](../README.md#ethgetfilterchanges)*

Defined in index.d.ts:809

Polling method for a filter, which returns an array of logs which occurred since last poll.

___

###  eth_getFilterLogs

• **eth_getFilterLogs**: *[EthGetFilterLogs](../README.md#ethgetfilterlogs)*

Defined in index.d.ts:813

Returns an array of all logs matching filter with given id.

___

###  eth_getLogs

• **eth_getLogs**: *[EthGetLogs](../README.md#ethgetlogs)*

Defined in index.d.ts:829

Returns an array of all logs matching a given filter object.

___

###  eth_getProof

• **eth_getProof**: *[EthGetProof](../README.md#ethgetproof)*

Defined in index.d.ts:873

Returns the account- and storage-values of the specified account including the Merkle-proof.

___

###  eth_getRawTransactionByBlockHashAndIndex

• **eth_getRawTransactionByBlockHashAndIndex**: *[EthGetRawTransactionByBlockHashAndIndex](../README.md#ethgetrawtransactionbyblockhashandindex)*

Defined in index.d.ts:821

Returns raw transaction data of a transaction with the block hash and index of which it was mined.

___

###  eth_getRawTransactionByBlockNumberAndIndex

• **eth_getRawTransactionByBlockNumberAndIndex**: *[EthGetRawTransactionByBlockNumberAndIndex](../README.md#ethgetrawtransactionbyblocknumberandindex)*

Defined in index.d.ts:825

Returns raw transaction data of a transaction with the block number and index of which it was mined.

___

###  eth_getRawTransactionByHash

• **eth_getRawTransactionByHash**: *[EthGetRawTransactionByHash](../README.md#ethgetrawtransactionbyhash)*

Defined in index.d.ts:817

Returns raw transaction data of a transaction with the given hash.

___

###  eth_getStorageAt

• **eth_getStorageAt**: *[EthGetStorageAt](../README.md#ethgetstorageat)*

Defined in index.d.ts:833

Gets a storage value from a contract address, a position, and an optional blockNumber

___

###  eth_getTransactionByBlockHashAndIndex

• **eth_getTransactionByBlockHashAndIndex**: *[EthGetTransactionByBlockHashAndIndex](../README.md#ethgettransactionbyblockhashandindex)*

Defined in index.d.ts:837

Returns the information about a transaction requested by the block hash and index of which it was mined.

___

###  eth_getTransactionByBlockNumberAndIndex

• **eth_getTransactionByBlockNumberAndIndex**: *[EthGetTransactionByBlockNumberAndIndex](../README.md#ethgettransactionbyblocknumberandindex)*

Defined in index.d.ts:841

Returns the information about a transaction requested by the block number and index of which it was mined.

___

###  eth_getTransactionByHash

• **eth_getTransactionByHash**: *[EthGetTransactionByHash](../README.md#ethgettransactionbyhash)*

Defined in index.d.ts:845

Returns the information about a transaction requested by transaction hash.

___

###  eth_getTransactionCount

• **eth_getTransactionCount**: *[EthGetTransactionCount](../README.md#ethgettransactioncount)*

Defined in index.d.ts:849

Returns the number of transactions sent from an address

___

###  eth_getTransactionReceipt

• **eth_getTransactionReceipt**: *[EthGetTransactionReceipt](../README.md#ethgettransactionreceipt)*

Defined in index.d.ts:853

Returns the receipt information of a transaction by its hash.

___

###  eth_getUncleByBlockHashAndIndex

• **eth_getUncleByBlockHashAndIndex**: *[EthGetUncleByBlockHashAndIndex](../README.md#ethgetunclebyblockhashandindex)*

Defined in index.d.ts:857

Returns information about a uncle of a block by hash and uncle index position.

___

###  eth_getUncleByBlockNumberAndIndex

• **eth_getUncleByBlockNumberAndIndex**: *[EthGetUncleByBlockNumberAndIndex](../README.md#ethgetunclebyblocknumberandindex)*

Defined in index.d.ts:861

Returns information about a uncle of a block by hash and uncle index position.

___

###  eth_getUncleCountByBlockHash

• **eth_getUncleCountByBlockHash**: *[EthGetUncleCountByBlockHash](../README.md#ethgetunclecountbyblockhash)*

Defined in index.d.ts:865

Returns the number of uncles in a block from a block matching the given block hash.

___

###  eth_getUncleCountByBlockNumber

• **eth_getUncleCountByBlockNumber**: *[EthGetUncleCountByBlockNumber](../README.md#ethgetunclecountbyblocknumber)*

Defined in index.d.ts:869

Returns the number of uncles in a block from a block matching the given block number.

___

###  eth_getWork

• **eth_getWork**: *[EthGetWork](../README.md#ethgetwork)*

Defined in index.d.ts:877

Returns the hash of the current block, the seedHash, and the boundary condition to be met ('target').

___

###  eth_hashrate

• **eth_hashrate**: *[EthHashrate](../README.md#ethhashrate)*

Defined in index.d.ts:881

Returns the number of hashes per second that the node is mining with.

___

###  eth_mining

• **eth_mining**: *[EthMining](../README.md#ethmining)*

Defined in index.d.ts:885

Returns true if client is actively mining new blocks.

___

###  eth_newBlockFilter

• **eth_newBlockFilter**: *[EthNewBlockFilter](../README.md#ethnewblockfilter)*

Defined in index.d.ts:889

Creates a filter in the node, to notify when a new block arrives. To check if the state has changed, call eth_getFilterChanges.

___

###  eth_newFilter

• **eth_newFilter**: *[EthNewFilter](../README.md#ethnewfilter)*

Defined in index.d.ts:893

Creates a filter object, based on filter options, to notify when the state changes (logs). To check if the state has changed, call eth_getFilterChanges.

___

###  eth_newPendingTransactionFilter

• **eth_newPendingTransactionFilter**: *[EthNewPendingTransactionFilter](../README.md#ethnewpendingtransactionfilter)*

Defined in index.d.ts:897

Creates a filter in the node, to notify when new pending transactions arrive. To check if the state has changed, call eth_getFilterChanges.

___

###  eth_pendingTransactions

• **eth_pendingTransactions**: *[EthPendingTransactions](../README.md#ethpendingtransactions)*

Defined in index.d.ts:901

Returns the transactions that are pending in the transaction pool and have a from address that is one of the accounts this node manages.

___

###  eth_protocolVersion

• **eth_protocolVersion**: *[EthProtocolVersion](../README.md#ethprotocolversion)*

Defined in index.d.ts:905

Returns the current ethereum protocol version.

___

###  eth_sendRawTransaction

• **eth_sendRawTransaction**: *[EthSendRawTransaction](../README.md#ethsendrawtransaction)*

Defined in index.d.ts:909

Creates new message call transaction or a contract creation for signed transactions.

___

###  eth_submitHashrate

• **eth_submitHashrate**: *[EthSubmitHashrate](../README.md#ethsubmithashrate)*

Defined in index.d.ts:913

Used for submitting mining hashrate.

___

###  eth_submitWork

• **eth_submitWork**: *[EthSubmitWork](../README.md#ethsubmitwork)*

Defined in index.d.ts:917

Used for submitting a proof-of-work solution.

___

###  eth_syncing

• **eth_syncing**: *[EthSyncing](../README.md#ethsyncing)*

Defined in index.d.ts:921

Returns an object with data about the sync status or false.

___

###  eth_uninstallFilter

• **eth_uninstallFilter**: *[EthUninstallFilter](../README.md#ethuninstallfilter)*

Defined in index.d.ts:925

Uninstalls a filter with given id. Should always be called when watch is no longer needed. Additionally Filters timeout when they aren't requested with eth_getFilterChanges for a period of time.

___

###  net_listening

• **net_listening**: *[NetListening](../README.md#netlistening)*

Defined in index.d.ts:749

returns listening status

___

###  net_peerCount

• **net_peerCount**: *[NetPeerCount](../README.md#netpeercount)*

Defined in index.d.ts:753

number of peers

___

###  net_version

• **net_version**: *[NetVersion](../README.md#netversion)*

Defined in index.d.ts:757

Network identifier associated with network

___

###  rpc

• **rpc**: *Client*

Defined in index.d.ts:683

___

###  transport

• **transport**: *HTTPTransport | WebSocketTransport | PostMessageWindowTransport | PostMessageIframeTransport*

Defined in index.d.ts:685

___

###  web3_clientVersion

• **web3_clientVersion**: *[Web3ClientVersion](../README.md#web3clientversion)*

Defined in index.d.ts:741

current client version

___

###  web3_sha3

• **web3_sha3**: *[Web3Sha3](../README.md#web3sha3)*

Defined in index.d.ts:745

Hashes data

___

### `Static` openrpcDocument

▪ **openrpcDocument**: *OpenRPC*

Defined in index.d.ts:684

## Methods

###  onError

▸ **onError**(`callback`: function): *void*

Defined in index.d.ts:700

Adds an optional JSONRPCError handler to handle receiving errors that cannot be resolved to a specific request

**`example`** 
myClient.onError((err: JSONRPCError)=>console.log(err.message));

**Parameters:**

▪ **callback**: *function*

▸ (`data`: JSONRPCError): *void*

**Parameters:**

Name | Type |
------ | ------ |
`data` | JSONRPCError |

**Returns:** *void*

___

###  onNotification

▸ **onNotification**(`callback`: function): *void*

Defined in index.d.ts:694

Adds a JSONRPC notification handler to handle receiving notifications.

**`example`** 
myClient.onNotification((data)=>console.log(data));

**Parameters:**

▪ **callback**: *function*

▸ (`data`: any): *void*

**Parameters:**

Name | Type |
------ | ------ |
`data` | any |

**Returns:** *void*

___

###  setDefaultTimeout

▸ **setDefaultTimeout**(`ms?`: number): *void*

Defined in index.d.ts:709

Sets a default timeout in ms for all requests excluding notifications.

**`example`** 
// 20s timeout
myClient.setDefaultTimeout(20000);
// Removes timeout from request
myClient.setDefaultTimeout(undefined);

**Parameters:**

Name | Type |
------ | ------ |
`ms?` | number |

**Returns:** *void*

___

###  startBatch

▸ **startBatch**(): *void*

Defined in index.d.ts:723

Initiates [EthereumJSONRPC.startBatch](ethereumjsonrpc.md#startbatch) in order to build a batch call.

Subsequent calls to [[EthereumJSONRPC.request]] will be added to the batch.
Once [EthereumJSONRPC.stopBatch](ethereumjsonrpc.md#stopbatch) is called, the promises for the [[EthereumJSONRPC.request]]
will then be resolved.  If there is already a batch in progress this method is a noop.

**`example`** 
myClient.startBatch();
myClient.foo().then(() => console.log("foobar"))
myClient.bar().then(() => console.log("foobarbaz"))
myClient.stopBatch();

**Returns:** *void*

___

###  stopBatch

▸ **stopBatch**(): *void*

Defined in index.d.ts:736

Initiates [[Client.stopBatch]] in order to finalize and send the batch to the underlying transport.

stopBatch will send the [EthereumJSONRPC](ethereumjsonrpc.md) calls made since the last [EthereumJSONRPC.startBatch](ethereumjsonrpc.md#startbatch) call. For
that reason, [EthereumJSONRPC.startBatch](ethereumjsonrpc.md#startbatch) MUST be called before [EthereumJSONRPC.stopBatch](ethereumjsonrpc.md#stopbatch).

**`example`** 
myClient.startBatch();
myClient.foo().then(() => console.log("foobar"))
myClient.bar().then(() => console.log("foobarbaz"))
myClient.stopBatch();

**Returns:** *void*
