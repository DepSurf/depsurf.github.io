# Function: <code>tpm_tis_send_main</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tpm_tis_send_main",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584254896,
      "name": "tpm_tis_send_main",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis.c:380",
      "file": "drivers/char/tpm/tpm_tis.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_send",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_send"
      ],
      "caller_func": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_send",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584254896,
      "name": "tpm_tis_send_main.part.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int tpm_tis_send_main(struct tpm_chip * chip, u8 * buf, size_t len)
```

```json
{
  "name": "tpm_tis_send_main",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584596480,
      "name": "tpm_tis_send_main",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:335",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584596480,
      "name": "tpm_tis_send_main",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
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
int tpm_tis_send_main(struct tpm_chip * chip, u8 * buf, size_t len)
```

```json
{
  "name": "tpm_tis_send_main",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584777904,
      "name": "tpm_tis_send_main",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:357",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584777904,
      "name": "tpm_tis_send_main",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
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
int tpm_tis_send_main(struct tpm_chip * chip, u8 * buf, size_t len)
```

```json
{
  "name": "tpm_tis_send_main",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584865120,
      "name": "tpm_tis_send_main",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:346",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584865120,
      "name": "tpm_tis_send_main",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 257
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
int tpm_tis_send_main(struct tpm_chip * chip, const u8 * buf, size_t len)
```

```json
{
  "name": "tpm_tis_send_main",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585284592,
      "name": "tpm_tis_send_main",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:349",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585284592,
      "name": "tpm_tis_send_main",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 269
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
int tpm_tis_send_main(struct tpm_chip * chip, const u8 * buf, size_t len)
```

```json
{
  "name": "tpm_tis_send_main",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585523712,
      "name": "tpm_tis_send_main",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:457",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585523712,
      "name": "tpm_tis_send_main",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 270
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int tpm_tis_send_main(struct tpm_chip * chip, const u8 * buf, size_t len)
```

```json
{
  "name": "tpm_tis_send_main",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585647808,
      "name": "tpm_tis_send_main",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:457",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585647808,
      "name": "tpm_tis_send_main",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
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
int tpm_tis_send_main(struct tpm_chip * chip, const u8 * buf, size_t len)
```

```json
{
  "name": "tpm_tis_send_main",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585872320,
      "name": "tpm_tis_send_main",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:453",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585872320,
      "name": "tpm_tis_send_main",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
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
int tpm_tis_send_main(struct tpm_chip * chip, const u8 * buf, size_t len)
```

```json
{
  "name": "tpm_tis_send_main",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586014880,
      "name": "tpm_tis_send_main",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:453",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586014880,
      "name": "tpm_tis_send_main",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int tpm_tis_send_main(struct tpm_chip * chip, const u8 * buf, size_t len)
```

```json
{
  "name": "tpm_tis_send_main",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586754736,
      "name": "tpm_tis_send_main",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:456",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586754736,
      "name": "tpm_tis_send_main",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int tpm_tis_send_main(struct tpm_chip * chip, const u8 * buf, size_t len)
```

```json
{
  "name": "tpm_tis_send_main",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586847424,
      "name": "tpm_tis_send_main",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:423",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586847424,
      "name": "tpm_tis_send_main",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int tpm_tis_send_main(struct tpm_chip * chip, const u8 * buf, size_t len)
```

```json
{
  "name": "tpm_tis_send_main",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586727872,
      "name": "tpm_tis_send_main",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:434",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586727872,
      "name": "tpm_tis_send_main",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int tpm_tis_send_main(struct tpm_chip * chip, const u8 * buf, size_t len)
```

```json
{
  "name": "tpm_tis_send_main",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587279376,
      "name": "tpm_tis_send_main",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:435",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587279376,
      "name": "tpm_tis_send_main",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int tpm_tis_send_main(struct tpm_chip * chip, const u8 * buf, size_t len)
```

```json
{
  "name": "tpm_tis_send_main",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588591120,
      "name": "tpm_tis_send_main",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:435",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588591120,
      "name": "tpm_tis_send_main",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 261
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int tpm_tis_send_main(struct tpm_chip * chip, const u8 * buf, size_t len)
```

```json
{
  "name": "tpm_tis_send_main",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590048048,
      "name": "tpm_tis_send_main",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:443",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590048048,
      "name": "tpm_tis_send_main",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 329
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int tpm_tis_send_main(struct tpm_chip * chip, const u8 * buf, size_t len)
```

```json
{
  "name": "tpm_tis_send_main",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590356784,
      "name": "tpm_tis_send_main",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:509",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590356784,
      "name": "tpm_tis_send_main",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 341
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int tpm_tis_send_main(struct tpm_chip * chip, const u8 * buf, size_t len)
```

```json
{
  "name": "tpm_tis_send_main",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590698448,
      "name": "tpm_tis_send_main",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:536",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590698448,
      "name": "tpm_tis_send_main",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 323
    }
  ]
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int tpm_tis_send_main(struct tpm_chip * chip, const u8 * buf, size_t len)
```

```json
{
  "name": "tpm_tis_send_main",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498815368,
      "name": "tpm_tis_send_main",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:453",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498815368,
      "name": "tpm_tis_send_main",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
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
int tpm_tis_send_main(struct tpm_chip * chip, const u8 * buf, size_t len)
```

```json
{
  "name": "tpm_tis_send_main",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231424600,
      "name": "tpm_tis_send_main",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:453",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231424600,
      "name": "tpm_tis_send_main",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
int tpm_tis_send_main(struct tpm_chip * chip, const u8 * buf, size_t len)
```

```json
{
  "name": "tpm_tis_send_main",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292009728,
      "name": "tpm_tis_send_main",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:453",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292009728,
      "name": "tpm_tis_send_main",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
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
int tpm_tis_send_main(struct tpm_chip * chip, const u8 * buf, size_t len)
```

```json
{
  "name": "tpm_tis_send_main",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276311348,
      "name": "tpm_tis_send_main",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:453",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276311348,
      "name": "tpm_tis_send_main",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
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
int tpm_tis_send_main(struct tpm_chip * chip, const u8 * buf, size_t len)
```

```json
{
  "name": "tpm_tis_send_main",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585775856,
      "name": "tpm_tis_send_main",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:453",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585775856,
      "name": "tpm_tis_send_main",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
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
int tpm_tis_send_main(struct tpm_chip * chip, const u8 * buf, size_t len)
```

```json
{
  "name": "tpm_tis_send_main",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585635040,
      "name": "tpm_tis_send_main",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:453",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585635040,
      "name": "tpm_tis_send_main",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
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
int tpm_tis_send_main(struct tpm_chip * chip, const u8 * buf, size_t len)
```

```json
{
  "name": "tpm_tis_send_main",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585964896,
      "name": "tpm_tis_send_main",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:453",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585964896,
      "name": "tpm_tis_send_main",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
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
int tpm_tis_send_main(struct tpm_chip * chip, const u8 * buf, size_t len)
```

```json
{
  "name": "tpm_tis_send_main",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586072624,
      "name": "tpm_tis_send_main",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:453",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586072624,
      "name": "tpm_tis_send_main",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int tpm_tis_send_main(struct tpm_chip * chip, u8 * buf, size_t len)
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
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>u8 * buf</code> ➡️ <code>const u8 * buf</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
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
