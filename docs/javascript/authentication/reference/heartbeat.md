# Heartbeat

## Members

| Name     | Type                                                  | Description |
| -------- | ----------------------------------------------------- | ----------- |
| client   | [Client](/javascript/authentication/reference/client) | TODO        |
| context  | `string`                                              | TODO        |
| interval | `number`                                              | TODO        |
| logger   | [Logger](https://github.com/pinojs/pino)              | Pino logger |
| name     | `string`                                              | TODO        |

## Methods

### `init`

#### Description

TODO

#### Example

```ts
init(): Promise<void>
```

---

### `on`

#### Description

Creates event subscription

#### Example

```ts
on(event: string, listener: Function): void
```

---

### `off`

#### Description

Removes event subscription. Same as [removeListener](/javascript/authentication/reference/heartbeat#removelistener)

#### Example

```ts
off(event: string, listener: Function): void
```

---

### `once`

#### Description

Creates event subscription that only triggers once

#### Example

```ts
once(event: string, listener: Function): void
```

---

### `removeListener`

#### Description

Removes event subscription. Same as [off](/javascript/authentication/reference/heartbeat#off)

#### Example

```ts
removeListener(event: string, listener: Function): void
```

---