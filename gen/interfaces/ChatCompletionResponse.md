[Scrypted Documentation](../globals.md) / ChatCompletionResponse

# Interface: ChatCompletionResponse

Represents a chat completion response returned by model, based on the provided
input.

## Properties

### id

> **id**: `string`

A unique identifier for the chat completion.

***

### choices

> **choices**: [`Choice`](../namespaces/ChatCompletionResponse/interfaces/Choice.md)[]

A list of chat completion choices. Can be more than one if `n` is greater
than 1.

***

### created

> **created**: `number`

The Unix timestamp (in seconds) of when the chat completion was created.

***

### model

> **model**: `string`

The model used for the chat completion.

***

### object

> **object**: `"chat.completion"`

The object type, which is always `chat.completion`.

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

> `optional` **usage**: `CompletionUsage`

Usage statistics for the completion request.
