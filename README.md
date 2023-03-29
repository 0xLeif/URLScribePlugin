# URLScribePlugin

A Scribe Plugin to send logs to a remote URL.

## Usage

```swift
URLScribePlugin(
    url: URL,
    headerFields: [String : String],
    outputFormatter: (Scribe.PluginPayload) async throws -> Data,
    responseHandler: (DataResponse) async throws -> Void
)
```
