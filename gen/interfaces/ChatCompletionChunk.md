[Scrypted Documentation](../globals.md) / ChatCompletionChunk

# Interface: ChatCompletionChunk

Represents a streamed chunk of a chat completion response returned by the model,
based on the provided input.
[Learn more](https://platform.openai.com/docs/guides/streaming-responses).

## Properties

### id

> **id**: `string`

A unique identifier for the chat completion. Each chunk has the same ID.

***

### choices

> **choices**: [`Choice`](../namespaces/ChatCompletionChunk/interfaces/Choice.md)[]

A list of chat completion choices. Can contain more than one elements if `n` is
greater than 1. Can also be empty for the last chunk if you set
`stream_options: {"include_usage": true}`.

***

### created

> **created**: `number`

The Unix timestamp (in seconds) of when the chat completion was created. Each
chunk has the same timestamp.

***

### model

> **model**: `string`

The model to generate the completion.

***

### object

> **object**: `"chat.completion.chunk"`

The object type, which is always `chat.completion.chunk`.

***

### service\_tier?

> `optional` **service\_tier**: `null` \| `"flex"` \| `"auto"` \| `"default"`

Specifies the latency tier to use for processing the request. This parameter is
relevant for customers subscribed to the scale tier service:

- If set to 'auto', and the Project is Scale tier enabled, the system will
  utilize scale tier credits until they are exhausted.
- If set to 'auto', and the Project is not Scale tier enabled, the request will
  be processed using the default service tier with a lower uptime SLA and no
  latency guarantee.
- If set to 'default', the request will be processed using the default service
  tier with a lower uptime SLA and no latency guarantee.
- If set to 'flex', the request will be processed with the Flex Processing
  service tier.
  [Learn more](https://platform.openai.com/docs/guides/flex-processing).
- When not set, the default behavior is 'auto'.

When this parameter is set, the response body will include the `service_tier`
utilized.

***

### system\_fingerprint?

> `optional` **system\_fingerprint**: `string`

This fingerprint represents the backend configuration that the model runs with.
Can be used in conjunction with the `seed` request parameter to understand when
backend changes have been made that might impact determinism.

***

### usage?

> `optional` **usage**: `null` \| `CompletionUsage`

An optional field that will only be present when you set
`stream_options: {"include_usage": true}` in your request. When present, it
contains a null value **except for the last chunk** which contains the token
usage statistics for the entire request.

**NOTE:** If the stream is interrupted or cancelled, you may not receive the
final usage chunk which contains the total token usage for the request.
