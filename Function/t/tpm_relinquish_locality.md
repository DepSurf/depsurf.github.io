# Function: <code>tpm_relinquish_locality</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tpm_relinquish_locality",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm_relinquish_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm-interface.c:390",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-interface.c:tpm_transmit"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tpm_relinquish_locality",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585622512,
      "name": "tpm_relinquish_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm-interface.c:125",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-interface.c:tpm_transmit"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void tpm_relinquish_locality(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_relinquish_locality",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm_relinquish_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm-chip.c:50",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-chip.c:tpm_chip_stop",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585836128,
      "name": "tpm_relinquish_locality",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071585838851,
      "name": "tpm_relinquish_locality.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
void tpm_relinquish_locality(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_relinquish_locality",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm_relinquish_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm-chip.c:50",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-chip.c:tpm_chip_stop",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585978784,
      "name": "tpm_relinquish_locality",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071585981507,
      "name": "tpm_relinquish_locality.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void tpm_relinquish_locality(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_relinquish_locality",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm_relinquish_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm-chip.c:50",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-chip.c:tpm_chip_stop",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586719856,
      "name": "tpm_relinquish_locality",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071586722659,
      "name": "tpm_relinquish_locality.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void tpm_relinquish_locality(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_relinquish_locality",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm_relinquish_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm-chip.c:50",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-chip.c:tpm_chip_stop",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586815680,
      "name": "tpm_relinquish_locality",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071591469684,
      "name": "tpm_relinquish_locality.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void tpm_relinquish_locality(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_relinquish_locality",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm_relinquish_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm-chip.c:50",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-chip.c:tpm_chip_stop",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586695744,
      "name": "tpm_relinquish_locality",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071591410939,
      "name": "tpm_relinquish_locality.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void tpm_relinquish_locality(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_relinquish_locality",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm_relinquish_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm-chip.c:50",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-chip.c:tpm_chip_stop",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587245072,
      "name": "tpm_relinquish_locality",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071592462725,
      "name": "tpm_relinquish_locality.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void tpm_relinquish_locality(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_relinquish_locality",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm_relinquish_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm-chip.c:50",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-chip.c:tpm_chip_stop",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588553808,
      "name": "tpm_relinquish_locality",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071594332608,
      "name": "tpm_relinquish_locality.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
void tpm_relinquish_locality(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_relinquish_locality",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590005520,
      "name": "tpm_relinquish_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm-chip.c:50",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-chip.c:tpm_chip_stop",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590005520,
      "name": "tpm_relinquish_locality",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
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
void tpm_relinquish_locality(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_relinquish_locality",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590315056,
      "name": "tpm_relinquish_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm-chip.c:50",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-chip.c:tpm_chip_stop",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590315056,
      "name": "tpm_relinquish_locality",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
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
void tpm_relinquish_locality(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_relinquish_locality",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590656368,
      "name": "tpm_relinquish_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm-chip.c:55",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-chip.c:tpm_chip_stop",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590656368,
      "name": "tpm_relinquish_locality",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
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
void tpm_relinquish_locality(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_relinquish_locality",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498772680,
      "name": "tpm_relinquish_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm-chip.c:50",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-chip.c:tpm_chip_stop",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498772680,
      "name": "tpm_relinquish_locality",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
void tpm_relinquish_locality(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_relinquish_locality",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231388628,
      "name": "tpm_relinquish_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm-chip.c:50",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-chip.c:tpm_chip_stop",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231388628,
      "name": "tpm_relinquish_locality",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
void tpm_relinquish_locality(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_relinquish_locality",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291962048,
      "name": "tpm_relinquish_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm-chip.c:50",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-chip.c:tpm_chip_stop",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291962048,
      "name": "tpm_relinquish_locality",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
void tpm_relinquish_locality(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_relinquish_locality",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276268090,
      "name": "tpm_relinquish_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm-chip.c:50",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-chip.c:tpm_chip_stop",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276268090,
      "name": "tpm_relinquish_locality",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void tpm_relinquish_locality(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_relinquish_locality",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm_relinquish_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm-chip.c:50",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-chip.c:tpm_chip_stop",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585739760,
      "name": "tpm_relinquish_locality",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071585742483,
      "name": "tpm_relinquish_locality.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
void tpm_relinquish_locality(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_relinquish_locality",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm_relinquish_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm-chip.c:50",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-chip.c:tpm_chip_stop",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585598944,
      "name": "tpm_relinquish_locality",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071585601667,
      "name": "tpm_relinquish_locality.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void tpm_relinquish_locality(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_relinquish_locality",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm_relinquish_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm-chip.c:50",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-chip.c:tpm_chip_stop",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585928800,
      "name": "tpm_relinquish_locality",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071585931523,
      "name": "tpm_relinquish_locality.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
void tpm_relinquish_locality(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_relinquish_locality",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm_relinquish_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm-chip.c:50",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-chip.c:tpm_chip_stop",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586036784,
      "name": "tpm_relinquish_locality",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071586039507,
      "name": "tpm_relinquish_locality.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void tpm_relinquish_locality(struct tpm_chip * chip)
```
</details>
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
