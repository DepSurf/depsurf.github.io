# Function: <code>tpm2_commit_space</code>

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
int tpm2_commit_space(struct tpm_chip * chip, struct tpm_space * space, u32 cc, u8 * buf, size_t * bufsiz)
```

```json
{
  "name": "tpm2_commit_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584859808,
      "name": "tpm2_commit_space",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-space.c:491",
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
      "addr": 18446744071584859808,
      "name": "tpm2_commit_space",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1140
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
int tpm2_commit_space(struct tpm_chip * chip, struct tpm_space * space, u32 cc, u8 * buf, size_t * bufsiz)
```

```json
{
  "name": "tpm2_commit_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585278784,
      "name": "tpm2_commit_space",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-space.c:491",
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
      "addr": 18446744071585278784,
      "name": "tpm2_commit_space",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1140
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
int tpm2_commit_space(struct tpm_chip * chip, struct tpm_space * space, u32 cc, u8 * buf, size_t * bufsiz)
```

```json
{
  "name": "tpm2_commit_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585515824,
      "name": "tpm2_commit_space",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-space.c:496",
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
      "addr": 18446744071585515824,
      "name": "tpm2_commit_space",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1129
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
int tpm2_commit_space(struct tpm_chip * chip, struct tpm_space * space, u32 cc, u8 * buf, size_t * bufsiz)
```

```json
{
  "name": "tpm2_commit_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585635488,
      "name": "tpm2_commit_space",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-space.c:492",
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
      "addr": 18446744071585635488,
      "name": "tpm2_commit_space",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1129
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
int tpm2_commit_space(struct tpm_chip * chip, struct tpm_space * space, void * buf, size_t * bufsiz)
```

```json
{
  "name": "tpm2_commit_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm2_commit_space",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-space.c:527",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585859922,
      "name": "tpm2_commit_space.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071585858496,
      "name": "tpm2_commit_space",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1140
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
int tpm2_commit_space(struct tpm_chip * chip, struct tpm_space * space, void * buf, size_t * bufsiz)
```

```json
{
  "name": "tpm2_commit_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm2_commit_space",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-space.c:527",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586002514,
      "name": "tpm2_commit_space.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071586001088,
      "name": "tpm2_commit_space",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1140
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
int tpm2_commit_space(struct tpm_chip * chip, struct tpm_space * space, void * buf, size_t * bufsiz)
```

```json
{
  "name": "tpm2_commit_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586739504,
      "name": "tpm2_commit_space",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-space.c:531",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586739504,
      "name": "tpm2_commit_space",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 468
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
int tpm2_commit_space(struct tpm_chip * chip, struct tpm_space * space, void * buf, size_t * bufsiz)
```

```json
{
  "name": "tpm2_commit_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586833984,
      "name": "tpm2_commit_space",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-space.c:531",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586833984,
      "name": "tpm2_commit_space",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 468
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
int tpm2_commit_space(struct tpm_chip * chip, struct tpm_space * space, void * buf, size_t * bufsiz)
```

```json
{
  "name": "tpm2_commit_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm2_commit_space",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-space.c:531",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591412514,
      "name": "tpm2_commit_space.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071586713280,
      "name": "tpm2_commit_space",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1087
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
int tpm2_commit_space(struct tpm_chip * chip, struct tpm_space * space, void * buf, size_t * bufsiz)
```

```json
{
  "name": "tpm2_commit_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm2_commit_space",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-space.c:534",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592464422,
      "name": "tpm2_commit_space.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071587263600,
      "name": "tpm2_commit_space",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1437
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
int tpm2_commit_space(struct tpm_chip * chip, struct tpm_space * space, void * buf, size_t * bufsiz)
```

```json
{
  "name": "tpm2_commit_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm2_commit_space",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-space.c:534",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594334372,
      "name": "tpm2_commit_space.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071588573328,
      "name": "tpm2_commit_space",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1478
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
int tpm2_commit_space(struct tpm_chip * chip, struct tpm_space * space, void * buf, size_t * bufsiz)
```

```json
{
  "name": "tpm2_commit_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590028256,
      "name": "tpm2_commit_space",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-space.c:534",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590028256,
      "name": "tpm2_commit_space",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1489
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
int tpm2_commit_space(struct tpm_chip * chip, struct tpm_space * space, void * buf, size_t * bufsiz)
```

```json
{
  "name": "tpm2_commit_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590337536,
      "name": "tpm2_commit_space",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-space.c:534",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590337536,
      "name": "tpm2_commit_space",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1489
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
int tpm2_commit_space(struct tpm_chip * chip, struct tpm_space * space, void * buf, size_t * bufsiz)
```

```json
{
  "name": "tpm2_commit_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590679024,
      "name": "tpm2_commit_space",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-space.c:534",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590679024,
      "name": "tpm2_commit_space",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1489
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
int tpm2_commit_space(struct tpm_chip * chip, struct tpm_space * space, void * buf, size_t * bufsiz)
```

```json
{
  "name": "tpm2_commit_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498797896,
      "name": "tpm2_commit_space",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-space.c:527",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498797896,
      "name": "tpm2_commit_space",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1084
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
int tpm2_commit_space(struct tpm_chip * chip, struct tpm_space * space, void * buf, size_t * bufsiz)
```

```json
{
  "name": "tpm2_commit_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231412548,
      "name": "tpm2_commit_space",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-space.c:527",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3231412548,
      "name": "tpm2_commit_space",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1076
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
int tpm2_commit_space(struct tpm_chip * chip, struct tpm_space * space, void * buf, size_t * bufsiz)
```

```json
{
  "name": "tpm2_commit_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291993536,
      "name": "tpm2_commit_space",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-space.c:527",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291993536,
      "name": "tpm2_commit_space",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1460
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
int tpm2_commit_space(struct tpm_chip * chip, struct tpm_space * space, void * buf, size_t * bufsiz)
```

```json
{
  "name": "tpm2_commit_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276300340,
      "name": "tpm2_commit_space",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-space.c:527",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276300340,
      "name": "tpm2_commit_space",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1648
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
int tpm2_commit_space(struct tpm_chip * chip, struct tpm_space * space, void * buf, size_t * bufsiz)
```

```json
{
  "name": "tpm2_commit_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm2_commit_space",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-space.c:527",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585763490,
      "name": "tpm2_commit_space.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071585762064,
      "name": "tpm2_commit_space",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1140
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
int tpm2_commit_space(struct tpm_chip * chip, struct tpm_space * space, void * buf, size_t * bufsiz)
```

```json
{
  "name": "tpm2_commit_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm2_commit_space",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-space.c:527",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585622674,
      "name": "tpm2_commit_space.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071585621248,
      "name": "tpm2_commit_space",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1140
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
int tpm2_commit_space(struct tpm_chip * chip, struct tpm_space * space, void * buf, size_t * bufsiz)
```

```json
{
  "name": "tpm2_commit_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm2_commit_space",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-space.c:527",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585952530,
      "name": "tpm2_commit_space.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071585951104,
      "name": "tpm2_commit_space",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1140
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
int tpm2_commit_space(struct tpm_chip * chip, struct tpm_space * space, void * buf, size_t * bufsiz)
```

```json
{
  "name": "tpm2_commit_space",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm2_commit_space",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-space.c:527",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586060290,
      "name": "tpm2_commit_space.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071586058864,
      "name": "tpm2_commit_space",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1140
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
int tpm2_commit_space(struct tpm_chip * chip, struct tpm_space * space, u32 cc, u8 * buf, size_t * bufsiz)
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
<b>Param removed. </b>
<code>u32 cc</code>
</li>
<li>
<b>Param reordered. </b>
<code>chip, space, cc, buf, bufsiz</code> ➡️ <code>chip, space, buf, bufsiz</code>
</li>
<li>
<b>Param type changed. </b>
<code>u8 * buf</code> ➡️ <code>void * buf</code>
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
