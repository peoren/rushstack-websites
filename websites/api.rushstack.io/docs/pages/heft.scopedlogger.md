---
hide_title: true
custom_edit_url: null
pagination_prev: null
pagination_next: null
---
<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@rushstack/heft](./heft.md) &gt; [ScopedLogger](./heft.scopedlogger.md)

## ScopedLogger class

**Signature:**

```typescript
export declare class ScopedLogger implements IScopedLogger 
```
**Implements:** [IScopedLogger](./heft.iscopedlogger.md)

## Remarks

The constructor for this class is marked as internal. Third-party code should not call the constructor directly or create subclasses that extend the `ScopedLogger` class.

## Properties

|  Property | Modifiers | Type | Description |
|  --- | --- | --- | --- |
|  [errors](./heft.scopedlogger.errors.md) | <code>readonly</code> | ReadonlyArray&lt;Error&gt; |  |
|  [loggerName](./heft.scopedlogger.loggername.md) | <code>readonly</code> | string |  |
|  [terminal](./heft.scopedlogger.terminal.md) | <code>readonly</code> | [ITerminal](./node-core-library.iterminal.md) |  |
|  [terminalProvider](./heft.scopedlogger.terminalprovider.md) | <code>readonly</code> | [ITerminalProvider](./node-core-library.iterminalprovider.md) |  |
|  [warnings](./heft.scopedlogger.warnings.md) | <code>readonly</code> | ReadonlyArray&lt;Error&gt; |  |

## Methods

|  Method | Modifiers | Description |
|  --- | --- | --- |
|  [emitError(error)](./heft.scopedlogger.emiterror.md) |  | Call this function to emit an error to the heft runtime. |
|  [emitWarning(warning)](./heft.scopedlogger.emitwarning.md) |  | Call this function to emit an warning to the heft runtime. |

