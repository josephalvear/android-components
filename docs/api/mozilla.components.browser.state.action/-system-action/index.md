[android-components](../../index.md) / [mozilla.components.browser.state.action](../index.md) / [SystemAction](./index.md)

# SystemAction

`sealed class SystemAction : `[`BrowserAction`](../-browser-action.md) [(source)](https://github.com/mozilla-mobile/android-components/blob/master/components/browser/state/src/main/java/mozilla/components/browser/state/action/BrowserAction.kt#L43)

[BrowserAction](../-browser-action.md) implementations to react to system events.

### Types

| Name | Summary |
|---|---|
| [LowMemoryAction](-low-memory-action/index.md) | `data class LowMemoryAction : `[`SystemAction`](./index.md)<br>Optimizes the [BrowserState](../../mozilla.components.browser.state.state/-browser-state/index.md) by removing unneeded and optional resources if the system is in a low memory condition. |

### Extension Functions

| Name | Summary |
|---|---|
| [loadResourceAsString](../../mozilla.components.support.test.file/kotlin.-any/load-resource-as-string.md) | `fun `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`.loadResourceAsString(path: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>Loads a file from the resources folder and returns its content as a string object. |

### Inheritors

| Name | Summary |
|---|---|
| [LowMemoryAction](-low-memory-action/index.md) | `data class LowMemoryAction : `[`SystemAction`](./index.md)<br>Optimizes the [BrowserState](../../mozilla.components.browser.state.state/-browser-state/index.md) by removing unneeded and optional resources if the system is in a low memory condition. |
