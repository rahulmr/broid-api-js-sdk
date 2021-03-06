[@broid/api-sdk](../README.md) > ["core/helpers/Http"](../modules/_core_helpers_http_.md) > [Http](../classes/_core_helpers_http_.http.md)



# Class: Http

## Index

### Constructors

* [constructor](_core_helpers_http_.http.md#constructor)


### Methods

* [_autoParse](_core_helpers_http_.http.md#_autoparse)
* [_generateHeaders](_core_helpers_http_.http.md#_generateheaders)
* [makeRequest](_core_helpers_http_.http.md#makerequest)



---
## Constructors
<a id="constructor"></a>


### ⊕ **new Http**(credentials: *`any`*, hostUrl?: *`string`*, apiVersion?: *`string`*, logger: *`Logger`*): [Http](_core_helpers_http_.http.md)



*Defined in [core/helpers/Http.ts:9](https://github.com/broidHQ/broid-api-js-sdk/blob/0f18411/src/core/helpers/Http.ts#L9)*



**Parameters:**

| Param | Type | Default value | Description |
| ------ | ------ | ------ | ------ |
| credentials | `any`  | - |   - |
| hostUrl | `string`  | &quot;https://api-dev.broid.ai&quot; |   - |
| apiVersion | `string`  | &quot;1&quot; |   - |
| logger | `Logger`  | - |   - |





**Returns:** [Http](_core_helpers_http_.http.md)

---



## Methods
<a id="_autoparse"></a>

### «Private» _autoParse

► **_autoParse**(body: *`any`*, response: *`any`*): `any`




*Defined in [core/helpers/Http.ts:16](https://github.com/broidHQ/broid-api-js-sdk/blob/0f18411/src/core/helpers/Http.ts#L16)*



**Parameters:**

| Param | Type | Description |
| ------ | ------ | ------ |
| body | `any`   |  - |
| response | `any`   |  - |





**Returns:** `any`





___

<a id="_generateheaders"></a>

### «Private» _generateHeaders

► **_generateHeaders**(): `Object`




*Defined in [core/helpers/Http.ts:26](https://github.com/broidHQ/broid-api-js-sdk/blob/0f18411/src/core/helpers/Http.ts#L26)*





**Returns:** `Object`





___

<a id="makerequest"></a>

###  makeRequest

► **makeRequest**(method: *`string`*, url: *`string`*, body_: *`ObjectConstructor`⎮`null`*): `request.RequestPromise`




*Defined in [core/helpers/Http.ts:37](https://github.com/broidHQ/broid-api-js-sdk/blob/0f18411/src/core/helpers/Http.ts#L37)*



**Parameters:**

| Param | Type | Description |
| ------ | ------ | ------ |
| method | `string`   |  - |
| url | `string`   |  - |
| body_ | `ObjectConstructor`⎮`null`   |  - |





**Returns:** `request.RequestPromise`





___


