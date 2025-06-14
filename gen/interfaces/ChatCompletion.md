[Scrypted Documentation](../globals.md) / ChatCompletion

# Interface: ChatCompletion

## Methods

### getChatCompletion()

> **getChatCompletion**(`body`): `Promise`\<[`ChatCompletionResponse`](ChatCompletionResponse.md)\>

#### Parameters

• **body**: [`ChatCompletionCreateParamsNonStreaming`](ChatCompletionCreateParamsNonStreaming.md)

#### Returns

`Promise`\<[`ChatCompletionResponse`](ChatCompletionResponse.md)\>

***

### streamChatCompletion()

> **streamChatCompletion**(`params`): `Promise`\<`AsyncGenerator`\<[`ChatCompletionResponse`](ChatCompletionResponse.md) \| [`ChatCompletionChunk`](ChatCompletionChunk.md), `any`, `any`\>\>

#### Parameters

• **params**: `ChatCompletionStreamParams`

#### Returns

`Promise`\<`AsyncGenerator`\<[`ChatCompletionResponse`](ChatCompletionResponse.md) \| [`ChatCompletionChunk`](ChatCompletionChunk.md), `any`, `any`\>\>
