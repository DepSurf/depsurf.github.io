# Function: <code>tpm_find_get_ops</code>

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
struct tpm_chip * tpm_find_get_ops(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_find_get_ops",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585618464,
      "name": "tpm_find_get_ops",
      "external": true,
      "loc": "drivers/char/tpm/tpm-chip.c:125",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_unseal_trusted",
        "drivers/char/tpm/tpm-interface.c:tpm_seal_trusted",
        "drivers/char/tpm/tpm-interface.c:tpm_get_random",
        "drivers/char/tpm/tpm-interface.c:tpm_send",
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_extend",
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_read",
        "drivers/char/tpm/tpm-interface.c:tpm_is_tpm2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585618464,
      "name": "tpm_find_get_ops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
struct tpm_chip * tpm_find_get_ops(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_find_get_ops",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585838768,
      "name": "tpm_find_get_ops",
      "external": true,
      "loc": "drivers/char/tpm/tpm-chip.c:235",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_unseal_trusted",
        "drivers/char/tpm/tpm-interface.c:tpm_seal_trusted",
        "drivers/char/tpm/tpm-interface.c:tpm_get_random",
        "drivers/char/tpm/tpm-interface.c:tpm_send",
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_extend",
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_read",
        "drivers/char/tpm/tpm-interface.c:tpm_is_tpm2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585838768,
      "name": "tpm_find_get_ops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
struct tpm_chip * tpm_find_get_ops(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_find_get_ops",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585981424,
      "name": "tpm_find_get_ops",
      "external": true,
      "loc": "drivers/char/tpm/tpm-chip.c:235",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_unseal_trusted",
        "drivers/char/tpm/tpm-interface.c:tpm_seal_trusted",
        "drivers/char/tpm/tpm-interface.c:tpm_get_random",
        "drivers/char/tpm/tpm-interface.c:tpm_send",
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_extend",
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_read",
        "drivers/char/tpm/tpm-interface.c:tpm_is_tpm2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585981424,
      "name": "tpm_find_get_ops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
struct tpm_chip * tpm_find_get_ops(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_find_get_ops",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586722576,
      "name": "tpm_find_get_ops",
      "external": true,
      "loc": "drivers/char/tpm/tpm-chip.c:235",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_get_random",
        "drivers/char/tpm/tpm-interface.c:tpm_send",
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_extend",
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_read",
        "drivers/char/tpm/tpm-interface.c:tpm_is_tpm2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586722576,
      "name": "tpm_find_get_ops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
struct tpm_chip * tpm_find_get_ops(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_find_get_ops",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586818400,
      "name": "tpm_find_get_ops",
      "external": true,
      "loc": "drivers/char/tpm/tpm-chip.c:235",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_get_random",
        "drivers/char/tpm/tpm-interface.c:tpm_send",
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_extend",
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_read",
        "drivers/char/tpm/tpm-interface.c:tpm_is_tpm2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586818400,
      "name": "tpm_find_get_ops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
struct tpm_chip * tpm_find_get_ops(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_find_get_ops",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586698416,
      "name": "tpm_find_get_ops",
      "external": true,
      "loc": "drivers/char/tpm/tpm-chip.c:235",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_get_random",
        "drivers/char/tpm/tpm-interface.c:tpm_send",
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_extend",
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_read",
        "drivers/char/tpm/tpm-interface.c:tpm_is_tpm2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586698416,
      "name": "tpm_find_get_ops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
struct tpm_chip * tpm_find_get_ops(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_find_get_ops",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587247760,
      "name": "tpm_find_get_ops",
      "external": true,
      "loc": "drivers/char/tpm/tpm-chip.c:235",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_get_random",
        "drivers/char/tpm/tpm-interface.c:tpm_send",
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_extend",
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_read",
        "drivers/char/tpm/tpm-interface.c:tpm_is_tpm2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587247760,
      "name": "tpm_find_get_ops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
struct tpm_chip * tpm_find_get_ops(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_find_get_ops",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588556544,
      "name": "tpm_find_get_ops",
      "external": true,
      "loc": "drivers/char/tpm/tpm-chip.c:235",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_get_random",
        "drivers/char/tpm/tpm-interface.c:tpm_send",
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_extend",
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_read",
        "drivers/char/tpm/tpm-interface.c:tpm_is_tpm2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588556544,
      "name": "tpm_find_get_ops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
struct tpm_chip * tpm_find_get_ops(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_find_get_ops",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590008960,
      "name": "tpm_find_get_ops",
      "external": true,
      "loc": "drivers/char/tpm/tpm-chip.c:235",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_get_random",
        "drivers/char/tpm/tpm-interface.c:tpm_send",
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_extend",
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_read",
        "drivers/char/tpm/tpm-interface.c:tpm_is_tpm2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590008960,
      "name": "tpm_find_get_ops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
struct tpm_chip * tpm_find_get_ops(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_find_get_ops",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590318080,
      "name": "tpm_find_get_ops",
      "external": true,
      "loc": "drivers/char/tpm/tpm-chip.c:235",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_get_random",
        "drivers/char/tpm/tpm-interface.c:tpm_send",
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_extend",
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_read",
        "drivers/char/tpm/tpm-interface.c:tpm_is_tpm2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590318080,
      "name": "tpm_find_get_ops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
struct tpm_chip * tpm_find_get_ops(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_find_get_ops",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590659552,
      "name": "tpm_find_get_ops",
      "external": true,
      "loc": "drivers/char/tpm/tpm-chip.c:240",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_get_random",
        "drivers/char/tpm/tpm-interface.c:tpm_send",
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_extend",
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_read",
        "drivers/char/tpm/tpm-interface.c:tpm_is_tpm2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590659552,
      "name": "tpm_find_get_ops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
struct tpm_chip * tpm_find_get_ops(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_find_get_ops",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498775640,
      "name": "tpm_find_get_ops",
      "external": true,
      "loc": "drivers/char/tpm/tpm-chip.c:235",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_unseal_trusted",
        "drivers/char/tpm/tpm-interface.c:tpm_seal_trusted",
        "drivers/char/tpm/tpm-interface.c:tpm_get_random",
        "drivers/char/tpm/tpm-interface.c:tpm_send",
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_extend",
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_read",
        "drivers/char/tpm/tpm-interface.c:tpm_is_tpm2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498775640,
      "name": "tpm_find_get_ops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
struct tpm_chip * tpm_find_get_ops(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_find_get_ops",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231391332,
      "name": "tpm_find_get_ops",
      "external": true,
      "loc": "drivers/char/tpm/tpm-chip.c:235",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_unseal_trusted",
        "drivers/char/tpm/tpm-interface.c:tpm_seal_trusted",
        "drivers/char/tpm/tpm-interface.c:tpm_get_random",
        "drivers/char/tpm/tpm-interface.c:tpm_send",
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_extend",
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_read",
        "drivers/char/tpm/tpm-interface.c:tpm_is_tpm2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231391332,
      "name": "tpm_find_get_ops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
struct tpm_chip * tpm_find_get_ops(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_find_get_ops",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291966256,
      "name": "tpm_find_get_ops",
      "external": true,
      "loc": "drivers/char/tpm/tpm-chip.c:235",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_unseal_trusted",
        "drivers/char/tpm/tpm-interface.c:tpm_seal_trusted",
        "drivers/char/tpm/tpm-interface.c:tpm_get_random",
        "drivers/char/tpm/tpm-interface.c:tpm_send",
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_extend",
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_read",
        "drivers/char/tpm/tpm-interface.c:tpm_is_tpm2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291966256,
      "name": "tpm_find_get_ops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
struct tpm_chip * tpm_find_get_ops(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_find_get_ops",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276270788,
      "name": "tpm_find_get_ops",
      "external": true,
      "loc": "drivers/char/tpm/tpm-chip.c:235",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_unseal_trusted",
        "drivers/char/tpm/tpm-interface.c:tpm_seal_trusted",
        "drivers/char/tpm/tpm-interface.c:tpm_get_random",
        "drivers/char/tpm/tpm-interface.c:tpm_send",
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_extend",
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_read",
        "drivers/char/tpm/tpm-interface.c:tpm_is_tpm2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276270788,
      "name": "tpm_find_get_ops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
struct tpm_chip * tpm_find_get_ops(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_find_get_ops",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585742400,
      "name": "tpm_find_get_ops",
      "external": true,
      "loc": "drivers/char/tpm/tpm-chip.c:235",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_unseal_trusted",
        "drivers/char/tpm/tpm-interface.c:tpm_seal_trusted",
        "drivers/char/tpm/tpm-interface.c:tpm_get_random",
        "drivers/char/tpm/tpm-interface.c:tpm_send",
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_extend",
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_read",
        "drivers/char/tpm/tpm-interface.c:tpm_is_tpm2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585742400,
      "name": "tpm_find_get_ops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
struct tpm_chip * tpm_find_get_ops(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_find_get_ops",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585601584,
      "name": "tpm_find_get_ops",
      "external": true,
      "loc": "drivers/char/tpm/tpm-chip.c:235",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_unseal_trusted",
        "drivers/char/tpm/tpm-interface.c:tpm_seal_trusted",
        "drivers/char/tpm/tpm-interface.c:tpm_get_random",
        "drivers/char/tpm/tpm-interface.c:tpm_send",
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_extend",
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_read",
        "drivers/char/tpm/tpm-interface.c:tpm_is_tpm2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585601584,
      "name": "tpm_find_get_ops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
struct tpm_chip * tpm_find_get_ops(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_find_get_ops",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585931440,
      "name": "tpm_find_get_ops",
      "external": true,
      "loc": "drivers/char/tpm/tpm-chip.c:235",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_unseal_trusted",
        "drivers/char/tpm/tpm-interface.c:tpm_seal_trusted",
        "drivers/char/tpm/tpm-interface.c:tpm_get_random",
        "drivers/char/tpm/tpm-interface.c:tpm_send",
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_extend",
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_read",
        "drivers/char/tpm/tpm-interface.c:tpm_is_tpm2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585931440,
      "name": "tpm_find_get_ops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
struct tpm_chip * tpm_find_get_ops(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_find_get_ops",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586039424,
      "name": "tpm_find_get_ops",
      "external": true,
      "loc": "drivers/char/tpm/tpm-chip.c:235",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_unseal_trusted",
        "drivers/char/tpm/tpm-interface.c:tpm_seal_trusted",
        "drivers/char/tpm/tpm-interface.c:tpm_get_random",
        "drivers/char/tpm/tpm-interface.c:tpm_send",
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_extend",
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_read",
        "drivers/char/tpm/tpm-interface.c:tpm_is_tpm2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586039424,
      "name": "tpm_find_get_ops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
struct tpm_chip * tpm_find_get_ops(struct tpm_chip * chip)
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
