[@tauri-apps/api](../index.md) / [http](../modules/http.md) / Response

# Class: Response<T\>

[http](../modules/http.md).Response

Response object.

## Type parameters

| Name |
| :------ |
| `T` |

## Properties

### data

• **data**: `T`

The response data.

#### Defined in

[http.ts:148](https://github.com/tauri-apps/tauri/blob/e32a6f7/tooling/api/src/http.ts#L148)

___

### headers

• **headers**: `Record`<`string`, `string`\>

The response headers.

#### Defined in

[http.ts:144](https://github.com/tauri-apps/tauri/blob/e32a6f7/tooling/api/src/http.ts#L144)

___

### ok

• **ok**: `boolean`

A boolean indicating whether the response was successful (status in the range 200–299) or not.

#### Defined in

[http.ts:142](https://github.com/tauri-apps/tauri/blob/e32a6f7/tooling/api/src/http.ts#L142)

___

### rawHeaders

• **rawHeaders**: `Record`<`string`, `string`[]\>

The response raw headers.

#### Defined in

[http.ts:146](https://github.com/tauri-apps/tauri/blob/e32a6f7/tooling/api/src/http.ts#L146)

___

### status

• **status**: `number`

The response status code.

#### Defined in

[http.ts:140](https://github.com/tauri-apps/tauri/blob/e32a6f7/tooling/api/src/http.ts#L140)

___

### url

• **url**: `string`

The request URL.

#### Defined in

[http.ts:138](https://github.com/tauri-apps/tauri/blob/e32a6f7/tooling/api/src/http.ts#L138)
