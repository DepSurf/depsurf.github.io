# Function: <code>chacha_block</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void chacha_block(u32 * state, u8 * stream, int nrounds)
```

```json
{
  "name": "chacha_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589359280,
      "name": "chacha_block",
      "external": true,
      "loc": "lib/chacha.c:79",
      "file": "lib/chacha.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:_extract_crng"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589359280,
      "name": "chacha_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void chacha_block(u32 * state, u8 * stream, int nrounds)
```

```json
{
  "name": "chacha_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589816352,
      "name": "chacha_block",
      "external": true,
      "loc": "lib/chacha.c:75",
      "file": "lib/chacha.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:_extract_crng"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589816352,
      "name": "chacha_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void chacha_block(u32 * state, u8 * stream, int nrounds)
```

```json
{
  "name": "chacha_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590042672,
      "name": "chacha_block",
      "external": true,
      "loc": "lib/chacha.c:75",
      "file": "lib/chacha.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:_extract_crng"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590042672,
      "name": "chacha_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void chacha_block(u32 * state, u8 * stream, int nrounds)
```

```json
{
  "name": "chacha_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503803560,
      "name": "chacha_block",
      "external": true,
      "loc": "lib/chacha.c:75",
      "file": "lib/chacha.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:_extract_crng"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503803560,
      "name": "chacha_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void chacha_block(u32 * state, u8 * stream, int nrounds)
```

```json
{
  "name": "chacha_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236426552,
      "name": "chacha_block",
      "external": true,
      "loc": "lib/chacha.c:75",
      "file": "lib/chacha.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3236426552,
      "name": "chacha_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void chacha_block(u32 * state, u8 * stream, int nrounds)
```

```json
{
  "name": "chacha_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297641936,
      "name": "chacha_block",
      "external": true,
      "loc": "lib/chacha.c:75",
      "file": "lib/chacha.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:_extract_crng"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297641936,
      "name": "chacha_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void chacha_block(u32 * state, u8 * stream, int nrounds)
```

```json
{
  "name": "chacha_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279700950,
      "name": "chacha_block",
      "external": true,
      "loc": "lib/chacha.c:75",
      "file": "lib/chacha.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279700950,
      "name": "chacha_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void chacha_block(u32 * state, u8 * stream, int nrounds)
```

```json
{
  "name": "chacha_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589644928,
      "name": "chacha_block",
      "external": true,
      "loc": "lib/chacha.c:75",
      "file": "lib/chacha.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:_extract_crng"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589644928,
      "name": "chacha_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void chacha_block(u32 * state, u8 * stream, int nrounds)
```

```json
{
  "name": "chacha_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589370800,
      "name": "chacha_block",
      "external": true,
      "loc": "lib/chacha.c:75",
      "file": "lib/chacha.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:_extract_crng"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589370800,
      "name": "chacha_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void chacha_block(u32 * state, u8 * stream, int nrounds)
```

```json
{
  "name": "chacha_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590088304,
      "name": "chacha_block",
      "external": true,
      "loc": "lib/chacha.c:75",
      "file": "lib/chacha.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:_extract_crng"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590088304,
      "name": "chacha_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void chacha_block(u32 * state, u8 * stream, int nrounds)
```

```json
{
  "name": "chacha_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590138560,
      "name": "chacha_block",
      "external": true,
      "loc": "lib/chacha.c:75",
      "file": "lib/chacha.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:_extract_crng"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590138560,
      "name": "chacha_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void chacha_block(u32 * state, u8 * stream, int nrounds)
```
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void chacha_block(u32 * state, u8 * stream, int nrounds)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
