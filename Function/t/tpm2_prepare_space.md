# Function: <code>tpm2_prepare_space</code>

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
int tpm2_prepare_space(struct tpm_chip * chip, struct tpm_space * space, u32 cc, u8 * cmd)
```

```json
{
  "name": "tpm2_prepare_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584859152,
      "name": "tpm2_prepare_space",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-space.c:266",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_transmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584859152,
      "name": "tpm2_prepare_space",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 641
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
int tpm2_prepare_space(struct tpm_chip * chip, struct tpm_space * space, u32 cc, u8 * cmd)
```

```json
{
  "name": "tpm2_prepare_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585278128,
      "name": "tpm2_prepare_space",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-space.c:266",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_transmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585278128,
      "name": "tpm2_prepare_space",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 641
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
int tpm2_prepare_space(struct tpm_chip * chip, struct tpm_space * space, u32 cc, u8 * cmd)
```

```json
{
  "name": "tpm2_prepare_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585515184,
      "name": "tpm2_prepare_space",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-space.c:269",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_transmit",
        "drivers/char/tpm/tpm-interface.c:tpm_transmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585515184,
      "name": "tpm2_prepare_space",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 626
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
int tpm2_prepare_space(struct tpm_chip * chip, struct tpm_space * space, u32 cc, u8 * cmd)
```

```json
{
  "name": "tpm2_prepare_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585634848,
      "name": "tpm2_prepare_space",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-space.c:267",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_transmit",
        "drivers/char/tpm/tpm-interface.c:tpm_transmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585634848,
      "name": "tpm2_prepare_space",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 626
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
int tpm2_prepare_space(struct tpm_chip * chip, struct tpm_space * space, u8 * cmd, size_t cmdsiz)
```

```json
{
  "name": "tpm2_prepare_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm2_prepare_space",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-space.c:297",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585859864,
      "name": "tpm2_prepare_space.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071585857680,
      "name": "tpm2_prepare_space",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 814
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
int tpm2_prepare_space(struct tpm_chip * chip, struct tpm_space * space, u8 * cmd, size_t cmdsiz)
```

```json
{
  "name": "tpm2_prepare_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm2_prepare_space",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-space.c:297",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586002456,
      "name": "tpm2_prepare_space.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071586000272,
      "name": "tpm2_prepare_space",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 814
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
int tpm2_prepare_space(struct tpm_chip * chip, struct tpm_space * space, u8 * cmd, size_t cmdsiz)
```

```json
{
  "name": "tpm2_prepare_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586738976,
      "name": "tpm2_prepare_space",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-space.c:300",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586738976,
      "name": "tpm2_prepare_space",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 515
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
int tpm2_prepare_space(struct tpm_chip * chip, struct tpm_space * space, u8 * cmd, size_t cmdsiz)
```

```json
{
  "name": "tpm2_prepare_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586833456,
      "name": "tpm2_prepare_space",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-space.c:300",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586833456,
      "name": "tpm2_prepare_space",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 515
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
int tpm2_prepare_space(struct tpm_chip * chip, struct tpm_space * space, u8 * cmd, size_t cmdsiz)
```

```json
{
  "name": "tpm2_prepare_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm2_prepare_space",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-space.c:300",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591412456,
      "name": "tpm2_prepare_space.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071586712528,
      "name": "tpm2_prepare_space",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 752
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
int tpm2_prepare_space(struct tpm_chip * chip, struct tpm_space * space, u8 * cmd, size_t cmdsiz)
```

```json
{
  "name": "tpm2_prepare_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm2_prepare_space",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-space.c:300",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592464364,
      "name": "tpm2_prepare_space.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071587262592,
      "name": "tpm2_prepare_space",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1002
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
int tpm2_prepare_space(struct tpm_chip * chip, struct tpm_space * space, u8 * cmd, size_t cmdsiz)
```

```json
{
  "name": "tpm2_prepare_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm2_prepare_space",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-space.c:300",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594334314,
      "name": "tpm2_prepare_space.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071588572304,
      "name": "tpm2_prepare_space",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1012
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
int tpm2_prepare_space(struct tpm_chip * chip, struct tpm_space * space, u8 * cmd, size_t cmdsiz)
```

```json
{
  "name": "tpm2_prepare_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590027168,
      "name": "tpm2_prepare_space",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-space.c:300",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590027168,
      "name": "tpm2_prepare_space",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1064
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
int tpm2_prepare_space(struct tpm_chip * chip, struct tpm_space * space, u8 * cmd, size_t cmdsiz)
```

```json
{
  "name": "tpm2_prepare_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590336448,
      "name": "tpm2_prepare_space",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-space.c:300",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590336448,
      "name": "tpm2_prepare_space",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1061
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
int tpm2_prepare_space(struct tpm_chip * chip, struct tpm_space * space, u8 * cmd, size_t cmdsiz)
```

```json
{
  "name": "tpm2_prepare_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590677936,
      "name": "tpm2_prepare_space",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-space.c:300",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590677936,
      "name": "tpm2_prepare_space",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1061
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
int tpm2_prepare_space(struct tpm_chip * chip, struct tpm_space * space, u8 * cmd, size_t cmdsiz)
```

```json
{
  "name": "tpm2_prepare_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498797056,
      "name": "tpm2_prepare_space",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-space.c:297",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498797056,
      "name": "tpm2_prepare_space",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 836
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
int tpm2_prepare_space(struct tpm_chip * chip, struct tpm_space * space, u8 * cmd, size_t cmdsiz)
```

```json
{
  "name": "tpm2_prepare_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231411772,
      "name": "tpm2_prepare_space",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-space.c:297",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3231411772,
      "name": "tpm2_prepare_space",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 776
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
int tpm2_prepare_space(struct tpm_chip * chip, struct tpm_space * space, u8 * cmd, size_t cmdsiz)
```

```json
{
  "name": "tpm2_prepare_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291992496,
      "name": "tpm2_prepare_space",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-space.c:297",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291992496,
      "name": "tpm2_prepare_space",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1036
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
int tpm2_prepare_space(struct tpm_chip * chip, struct tpm_space * space, u8 * cmd, size_t cmdsiz)
```

```json
{
  "name": "tpm2_prepare_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276299354,
      "name": "tpm2_prepare_space",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-space.c:297",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276299354,
      "name": "tpm2_prepare_space",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 986
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
int tpm2_prepare_space(struct tpm_chip * chip, struct tpm_space * space, u8 * cmd, size_t cmdsiz)
```

```json
{
  "name": "tpm2_prepare_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm2_prepare_space",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-space.c:297",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585763432,
      "name": "tpm2_prepare_space.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071585761248,
      "name": "tpm2_prepare_space",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 814
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
int tpm2_prepare_space(struct tpm_chip * chip, struct tpm_space * space, u8 * cmd, size_t cmdsiz)
```

```json
{
  "name": "tpm2_prepare_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm2_prepare_space",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-space.c:297",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585622616,
      "name": "tpm2_prepare_space.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071585620432,
      "name": "tpm2_prepare_space",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 814
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
int tpm2_prepare_space(struct tpm_chip * chip, struct tpm_space * space, u8 * cmd, size_t cmdsiz)
```

```json
{
  "name": "tpm2_prepare_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm2_prepare_space",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-space.c:297",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585952472,
      "name": "tpm2_prepare_space.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071585950288,
      "name": "tpm2_prepare_space",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 814
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
int tpm2_prepare_space(struct tpm_chip * chip, struct tpm_space * space, u8 * cmd, size_t cmdsiz)
```

```json
{
  "name": "tpm2_prepare_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm2_prepare_space",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-space.c:297",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586060232,
      "name": "tpm2_prepare_space.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071586058048,
      "name": "tpm2_prepare_space",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 814
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
int tpm2_prepare_space(struct tpm_chip * chip, struct tpm_space * space, u32 cc, u8 * cmd)
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
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>size_t cmdsiz</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 cc</code>
</li>
<li>
<b>Param reordered. </b>
<code>chip, space, cc, cmd</code> ➡️ <code>chip, space, cmd, cmdsiz</code>
</li>
</ul>
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
