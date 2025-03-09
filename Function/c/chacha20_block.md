# Function: <code>chacha20_block</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void chacha20_block(u32 * state, void * stream)
```

```json
{
  "name": "chacha20_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587826704,
      "name": "chacha20_block",
      "external": true,
      "loc": "lib/chacha20.c:24",
      "file": "lib/chacha20.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:_extract_crng"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587826704,
      "name": "chacha20_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 673
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void chacha20_block(u32 * state, void * stream)
```

```json
{
  "name": "chacha20_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588041264,
      "name": "chacha20_block",
      "external": true,
      "loc": "lib/chacha20.c:24",
      "file": "lib/chacha20.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:_extract_crng"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588041264,
      "name": "chacha20_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 673
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void chacha20_block(u32 * state, void * stream)
```

```json
{
  "name": "chacha20_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588197728,
      "name": "chacha20_block",
      "external": true,
      "loc": "lib/chacha20.c:24",
      "file": "lib/chacha20.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:_extract_crng"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588197728,
      "name": "chacha20_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 668
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void chacha20_block(u32 * state, void * stream)
```

```json
{
  "name": "chacha20_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588746528,
      "name": "chacha20_block",
      "external": true,
      "loc": "lib/chacha20.c:24",
      "file": "lib/chacha20.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:_extract_crng"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588746528,
      "name": "chacha20_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 668
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void chacha20_block(u32 * state, u32 * stream)
```

```json
{
  "name": "chacha20_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589124336,
      "name": "chacha20_block",
      "external": true,
      "loc": "lib/chacha20.c:19",
      "file": "lib/chacha20.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:_extract_crng"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589124336,
      "name": "chacha20_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 668
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "chacha20_block",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585555762,
      "name": "chacha20_block",
      "external": false,
      "loc": "include/crypto/chacha.h:38",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:_extract_crng"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "chacha20_block",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585771330,
      "name": "chacha20_block",
      "external": false,
      "loc": "include/crypto/chacha.h:38",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:_extract_crng"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "chacha20_block",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585913970,
      "name": "chacha20_block",
      "external": false,
      "loc": "include/crypto/chacha.h:38",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:_extract_crng"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "chacha20_block",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586653426,
      "name": "chacha20_block",
      "external": false,
      "loc": "include/crypto/chacha.h:38",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:_extract_crng"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "chacha20_block",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586764130,
      "name": "chacha20_block",
      "external": false,
      "loc": "include/crypto/chacha.h:34",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:_extract_crng"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "chacha20_block",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586645266,
      "name": "chacha20_block",
      "external": false,
      "loc": "include/crypto/chacha.h:34",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:_extract_crng"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "chacha20_block",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587192517,
      "name": "chacha20_block",
      "external": false,
      "loc": "include/crypto/chacha.h:34",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:_extract_crng"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "chacha20_block",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588500673,
      "name": "chacha20_block",
      "external": false,
      "loc": "include/crypto/chacha.h:34",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:get_random_bytes_user",
        "drivers/char/random.c:_get_random_bytes",
        "drivers/char/random.c:_get_random_bytes",
        "drivers/char/random.c:crng_fast_key_erasure"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "chacha20_block",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589936545,
      "name": "chacha20_block",
      "external": false,
      "loc": "include/crypto/chacha.h:34",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:get_random_bytes_user",
        "drivers/char/random.c:_get_random_bytes",
        "drivers/char/random.c:_get_random_bytes",
        "drivers/char/random.c:crng_fast_key_erasure"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "chacha20_block",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590244225,
      "name": "chacha20_block",
      "external": false,
      "loc": "include/crypto/chacha.h:34",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:get_random_bytes_user",
        "drivers/char/random.c:_get_random_bytes",
        "drivers/char/random.c:_get_random_bytes",
        "drivers/char/random.c:crng_fast_key_erasure"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "chacha20_block",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590585249,
      "name": "chacha20_block",
      "external": false,
      "loc": "include/crypto/chacha.h:34",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:get_random_bytes_user",
        "drivers/char/random.c:_get_random_bytes",
        "drivers/char/random.c:_get_random_bytes",
        "drivers/char/random.c:crng_fast_key_erasure"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "chacha20_block",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336498739880,
      "name": "chacha20_block",
      "external": false,
      "loc": "include/crypto/chacha.h:38",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:_extract_crng"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "chacha20_block",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3231359776,
      "name": "chacha20_block",
      "external": false,
      "loc": "include/crypto/chacha.h:38",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "chacha20_block",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055291895032,
      "name": "chacha20_block",
      "external": false,
      "loc": "include/crypto/chacha.h:38",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:_extract_crng"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "chacha20_block",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936276242674,
      "name": "chacha20_block",
      "external": false,
      "loc": "include/crypto/chacha.h:38",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "chacha20_block",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585674978,
      "name": "chacha20_block",
      "external": false,
      "loc": "include/crypto/chacha.h:38",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:_extract_crng"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "chacha20_block",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585534818,
      "name": "chacha20_block",
      "external": false,
      "loc": "include/crypto/chacha.h:38",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:_extract_crng"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "chacha20_block",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585864370,
      "name": "chacha20_block",
      "external": false,
      "loc": "include/crypto/chacha.h:38",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:_extract_crng"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "chacha20_block",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585972050,
      "name": "chacha20_block",
      "external": false,
      "loc": "include/crypto/chacha.h:38",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:_extract_crng"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void chacha20_block(u32 * state, void * stream)
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>void * stream</code> ➡️ <code>u32 * stream</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
void chacha20_block(u32 * state, u32 * stream)
```
</details>
</li>
</ul>
