[@tauri-apps/api](../index.md) / [http](../modules/http.md) / Client

# Class: Client

[http](../modules/http.md).Client

## Properties

### id

• **id**: `number`

#### Defined in

[http.ts:162](https://github.com/tauri-apps/tauri/blob/e32a6f7/tooling/api/src/http.ts#L162)

## Methods

### delete

▸ **delete**<`T`\>(`url`, `options?`): `Promise`<[`Response`](http.Response.md)<`T`\>\>

Makes a DELETE request.

#### Type parameters

| Name |
| :------ |
| `T` |

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `url` | `string` | The request URL. |
| `options?` | [`RequestOptions`](../modules/http.md#requestoptions) | The request options. |

#### Returns

`Promise`<[`Response`](http.Response.md)<`T`\>\>

A promise resolving to the response.

#### Defined in

[http.ts:306](https://github.com/tauri-apps/tauri/blob/e32a6f7/tooling/api/src/http.ts#L306)

___

### drop

▸ **drop**(): `Promise`<`void`\>

Drops the client instance.

#### Returns

`Promise`<`void`\>

#### Defined in

[http.ts:173](https://github.com/tauri-apps/tauri/blob/e32a6f7/tooling/api/src/http.ts#L173)

___

### get

▸ **get**<`T`\>(`url`, `options?`): `Promise`<[`Response`](http.Response.md)<`T`\>\>

Makes a GET request.

#### Type parameters

| Name |
| :------ |
| `T` |

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `url` | `string` | The request URL. |
| `options?` | [`RequestOptions`](../modules/http.md#requestoptions) | The request options. |

#### Returns

`Promise`<[`Response`](http.Response.md)<`T`\>\>

A promise resolving to the response.

#### Defined in

[http.ts:234](https://github.com/tauri-apps/tauri/blob/e32a6f7/tooling/api/src/http.ts#L234)

___

### patch

▸ **patch**<`T`\>(`url`, `options?`): `Promise`<[`Response`](http.Response.md)<`T`\>\>

Makes a PATCH request.

#### Type parameters

| Name |
| :------ |
| `T` |

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `url` | `string` | The request URL. |
| `options?` | [`RequestOptions`](../modules/http.md#requestoptions) | The request options. |

#### Returns

`Promise`<[`Response`](http.Response.md)<`T`\>\>

A promise resolving to the response.

#### Defined in

[http.ts:291](https://github.com/tauri-apps/tauri/blob/e32a6f7/tooling/api/src/http.ts#L291)

___

### post

▸ **post**<`T`\>(`url`, `body?`, `options?`): `Promise`<[`Response`](http.Response.md)<`T`\>\>

Makes a POST request.

#### Type parameters

| Name |
| :------ |
| `T` |

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `url` | `string` | The request URL. |
| `body?` | [`Body`](http.Body.md) | The body of the request. |
| `options?` | [`RequestOptions`](../modules/http.md#requestoptions) | The request options. |

#### Returns

`Promise`<[`Response`](http.Response.md)<`T`\>\>

A promise resolving to the response.

#### Defined in

[http.ts:250](https://github.com/tauri-apps/tauri/blob/e32a6f7/tooling/api/src/http.ts#L250)

___

### put

▸ **put**<`T`\>(`url`, `body?`, `options?`): `Promise`<[`Response`](http.Response.md)<`T`\>\>

Makes a PUT request.

#### Type parameters

| Name |
| :------ |
| `T` |

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `url` | `string` | The request URL. |
| `body?` | [`Body`](http.Body.md) | The body of the request. |
| `options?` | [`RequestOptions`](../modules/http.md#requestoptions) | Request options. |

#### Returns

`Promise`<[`Response`](http.Response.md)<`T`\>\>

A promise resolving to the response.

#### Defined in

[http.ts:271](https://github.com/tauri-apps/tauri/blob/e32a6f7/tooling/api/src/http.ts#L271)

___

### request

▸ **request**<`T`\>(`options`): `Promise`<[`Response`](http.Response.md)<`T`\>\>

Makes an HTTP request.

#### Type parameters

| Name |
| :------ |
| `T` |

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `options` | [`HttpOptions`](../interfaces/http.HttpOptions.md) | The request options. |

#### Returns

`Promise`<[`Response`](http.Response.md)<`T`\>\>

A promise resolving to the response.

#### Defined in

[http.ts:189](https://github.com/tauri-apps/tauri/blob/e32a6f7/tooling/api/src/http.ts#L189)
