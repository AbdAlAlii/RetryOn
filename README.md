# RetryOn

RetryOn simplifies retrying streams after failure for subscribers.

## Usage

### Import

Ensure you import RetryOn into the relevant files:

```swift
import RetryOn
```

### Implementation

Integrate the operator within your publisher chain declaration:

```swift
let _ = publisher.retryOn(ErrorName, retries: 1, chainedPublisher: useThisPublisherBeforeRetrying)
```

## Installation

### Swift Package Manager

Add RetryOn to your dependencies:

```swift
.package(url: "https://github.com/AbdAlAlii/RetryOn")
```

## License

RetryOn is licensed under the MIT License. See the [LICENSE](./LICENSE) file for more information.