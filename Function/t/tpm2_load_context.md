# Function: <code>tpm2_load_context</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int tpm2_load_context(struct tpm_chip * chip, u8 * buf, unsigned int * offset, u32 * handle)
```

```json
{
  "name": "tpm2_load_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584858464,
      "name": "tpm2_load_context",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-space.c:70",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm2-space.c:tpm2_prepare_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_prepare_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584858464,
      "name": "tpm2_load_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 447
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
int tpm2_load_context(struct tpm_chip * chip, u8 * buf, unsigned int * offset, u32 * handle)
```

```json
{
  "name": "tpm2_load_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585277504,
      "name": "tpm2_load_context",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-space.c:70",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm2-space.c:tpm2_prepare_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_prepare_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585277504,
      "name": "tpm2_load_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 383
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
int tpm2_load_context(struct tpm_chip * chip, u8 * buf, unsigned int * offset, u32 * handle)
```

```json
{
  "name": "tpm2_load_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585514512,
      "name": "tpm2_load_context",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-space.c:71",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm2-space.c:tpm2_prepare_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_prepare_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585514512,
      "name": "tpm2_load_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 420
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
int tpm2_load_context(struct tpm_chip * chip, u8 * buf, unsigned int * offset, u32 * handle)
```

```json
{
  "name": "tpm2_load_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585634176,
      "name": "tpm2_load_context",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-space.c:70",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm2-space.c:tpm2_prepare_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_prepare_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585634176,
      "name": "tpm2_load_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 420
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int tpm2_load_context(struct tpm_chip * chip, u8 * buf, unsigned int * offset, u32 * handle)
```

```json
{
  "name": "tpm2_load_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm2_load_context",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-space.c:68",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm2-space.c:tpm2_prepare_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_prepare_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585856912,
      "name": "tpm2_load_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 396
    },
    {
      "addr": 18446744071585859772,
      "name": "tpm2_load_context.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
int tpm2_load_context(struct tpm_chip * chip, u8 * buf, unsigned int * offset, u32 * handle)
```

```json
{
  "name": "tpm2_load_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm2_load_context",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-space.c:68",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm2-space.c:tpm2_prepare_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_prepare_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585999504,
      "name": "tpm2_load_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 396
    },
    {
      "addr": 18446744071586002364,
      "name": "tpm2_load_context.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
int tpm2_load_context(struct tpm_chip * chip, u8 * buf, unsigned int * offset, u32 * handle)
```

```json
{
  "name": "tpm2_load_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm2_load_context",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-space.c:71",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm2-space.c:tpm2_load_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_load_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586737328,
      "name": "tpm2_load_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 358
    },
    {
      "addr": 18446744071586740004,
      "name": "tpm2_load_context.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
int tpm2_load_context(struct tpm_chip * chip, u8 * buf, unsigned int * offset, u32 * handle)
```

```json
{
  "name": "tpm2_load_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm2_load_context",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-space.c:71",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm2-space.c:tpm2_load_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_load_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586831808,
      "name": "tpm2_load_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 358
    },
    {
      "addr": 18446744071591470955,
      "name": "tpm2_load_context.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
int tpm2_load_context(struct tpm_chip * chip, u8 * buf, unsigned int * offset, u32 * handle)
```

```json
{
  "name": "tpm2_load_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm2_load_context",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-space.c:71",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm2-space.c:tpm2_prepare_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_prepare_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586711424,
      "name": "tpm2_load_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 358
    },
    {
      "addr": 18446744071591412227,
      "name": "tpm2_load_context.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
int tpm2_load_context(struct tpm_chip * chip, u8 * buf, unsigned int * offset, u32 * handle)
```

```json
{
  "name": "tpm2_load_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm2_load_context",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-space.c:71",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm2-space.c:tpm2_prepare_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_prepare_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587261328,
      "name": "tpm2_load_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 358
    },
    {
      "addr": 18446744071592464135,
      "name": "tpm2_load_context.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
int tpm2_load_context(struct tpm_chip * chip, u8 * buf, unsigned int * offset, u32 * handle)
```

```json
{
  "name": "tpm2_load_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm2_load_context",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-space.c:71",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm2-space.c:tpm2_prepare_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_prepare_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588570992,
      "name": "tpm2_load_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 386
    },
    {
      "addr": 18446744071594334153,
      "name": "tpm2_load_context.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
int tpm2_load_context(struct tpm_chip * chip, u8 * buf, unsigned int * offset, u32 * handle)
```

```json
{
  "name": "tpm2_load_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590025632,
      "name": "tpm2_load_context",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-space.c:71",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm2-space.c:tpm2_prepare_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_prepare_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590025632,
      "name": "tpm2_load_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 458
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
int tpm2_load_context(struct tpm_chip * chip, u8 * buf, unsigned int * offset, u32 * handle)
```

```json
{
  "name": "tpm2_load_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590335408,
      "name": "tpm2_load_context",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-space.c:71",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm2-space.c:tpm2_prepare_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_prepare_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590335408,
      "name": "tpm2_load_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 454
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
int tpm2_load_context(struct tpm_chip * chip, u8 * buf, unsigned int * offset, u32 * handle)
```

```json
{
  "name": "tpm2_load_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590676896,
      "name": "tpm2_load_context",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-space.c:71",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm2-space.c:tpm2_prepare_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_prepare_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590676896,
      "name": "tpm2_load_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 454
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
int tpm2_load_context(struct tpm_chip * chip, u8 * buf, unsigned int * offset, u32 * handle)
```

```json
{
  "name": "tpm2_load_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498796088,
      "name": "tpm2_load_context",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-space.c:68",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm2-space.c:tpm2_prepare_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_prepare_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498796088,
      "name": "tpm2_load_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 548
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
int tpm2_load_context(struct tpm_chip * chip, u8 * buf, unsigned int * offset, u32 * handle)
```

```json
{
  "name": "tpm2_load_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231410784,
      "name": "tpm2_load_context",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-space.c:68",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm2-space.c:tpm2_prepare_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_prepare_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231410784,
      "name": "tpm2_load_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 596
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
int tpm2_load_context(struct tpm_chip * chip, u8 * buf, unsigned int * offset, u32 * handle)
```

```json
{
  "name": "tpm2_load_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291991280,
      "name": "tpm2_load_context",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-space.c:68",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm2-space.c:tpm2_prepare_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_prepare_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291991280,
      "name": "tpm2_load_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 640
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
int tpm2_load_context(struct tpm_chip * chip, u8 * buf, unsigned int * offset, u32 * handle)
```

```json
{
  "name": "tpm2_load_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276298316,
      "name": "tpm2_load_context",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-space.c:68",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm2-space.c:tpm2_prepare_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_prepare_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276298316,
      "name": "tpm2_load_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 642
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
int tpm2_load_context(struct tpm_chip * chip, u8 * buf, unsigned int * offset, u32 * handle)
```

```json
{
  "name": "tpm2_load_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm2_load_context",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-space.c:68",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm2-space.c:tpm2_prepare_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_prepare_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585760480,
      "name": "tpm2_load_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 396
    },
    {
      "addr": 18446744071585763340,
      "name": "tpm2_load_context.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
int tpm2_load_context(struct tpm_chip * chip, u8 * buf, unsigned int * offset, u32 * handle)
```

```json
{
  "name": "tpm2_load_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm2_load_context",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-space.c:68",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm2-space.c:tpm2_prepare_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_prepare_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585619664,
      "name": "tpm2_load_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 396
    },
    {
      "addr": 18446744071585622524,
      "name": "tpm2_load_context.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
int tpm2_load_context(struct tpm_chip * chip, u8 * buf, unsigned int * offset, u32 * handle)
```

```json
{
  "name": "tpm2_load_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm2_load_context",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-space.c:68",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm2-space.c:tpm2_prepare_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_prepare_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585949520,
      "name": "tpm2_load_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 396
    },
    {
      "addr": 18446744071585952380,
      "name": "tpm2_load_context.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
int tpm2_load_context(struct tpm_chip * chip, u8 * buf, unsigned int * offset, u32 * handle)
```

```json
{
  "name": "tpm2_load_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm2_load_context",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-space.c:68",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm2-space.c:tpm2_prepare_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_prepare_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586057280,
      "name": "tpm2_load_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 393
    },
    {
      "addr": 18446744071586060140,
      "name": "tpm2_load_context.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int tpm2_load_context(struct tpm_chip * chip, u8 * buf, unsigned int * offset, u32 * handle)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
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
