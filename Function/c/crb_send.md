# Function: <code>crb_send</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int crb_send(struct tpm_chip * chip, u8 * buf, size_t len)
```

```json
{
  "name": "crb_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585531184,
      "name": "crb_send",
      "external": false,
      "loc": "drivers/char/tpm/tpm_crb.c:352",
      "file": "drivers/char/tpm/tpm_crb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585531184,
      "name": "crb_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
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
int crb_send(struct tpm_chip * chip, u8 * buf, size_t len)
```

```json
{
  "name": "crb_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585653264,
      "name": "crb_send",
      "external": false,
      "loc": "drivers/char/tpm/tpm_crb.c:362",
      "file": "drivers/char/tpm/tpm_crb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585653264,
      "name": "crb_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
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
int crb_send(struct tpm_chip * chip, u8 * buf, size_t len)
```

```json
{
  "name": "crb_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "crb_send",
      "external": false,
      "loc": "drivers/char/tpm/tpm_crb.c:358",
      "file": "drivers/char/tpm/tpm_crb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585877776,
      "name": "crb_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
    },
    {
      "addr": 18446744071585879903,
      "name": "crb_send.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
int crb_send(struct tpm_chip * chip, u8 * buf, size_t len)
```

```json
{
  "name": "crb_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "crb_send",
      "external": false,
      "loc": "drivers/char/tpm/tpm_crb.c:358",
      "file": "drivers/char/tpm/tpm_crb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586020336,
      "name": "crb_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
    },
    {
      "addr": 18446744071586022463,
      "name": "crb_send.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
int crb_send(struct tpm_chip * chip, u8 * buf, size_t len)
```

```json
{
  "name": "crb_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "crb_send",
      "external": false,
      "loc": "drivers/char/tpm/tpm_crb.c:358",
      "file": "drivers/char/tpm/tpm_crb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586759184,
      "name": "crb_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
    },
    {
      "addr": 18446744071586761544,
      "name": "crb_send.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
int crb_send(struct tpm_chip * chip, u8 * buf, size_t len)
```

```json
{
  "name": "crb_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "crb_send",
      "external": false,
      "loc": "drivers/char/tpm/tpm_crb.c:358",
      "file": "drivers/char/tpm/tpm_crb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586850720,
      "name": "crb_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
    },
    {
      "addr": 18446744071591473420,
      "name": "crb_send.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
int crb_send(struct tpm_chip * chip, u8 * buf, size_t len)
```

```json
{
  "name": "crb_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "crb_send",
      "external": false,
      "loc": "drivers/char/tpm/tpm_crb.c:358",
      "file": "drivers/char/tpm/tpm_crb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586731168,
      "name": "crb_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
    },
    {
      "addr": 18446744071591414667,
      "name": "crb_send.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
int crb_send(struct tpm_chip * chip, u8 * buf, size_t len)
```

```json
{
  "name": "crb_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "crb_send",
      "external": false,
      "loc": "drivers/char/tpm/tpm_crb.c:358",
      "file": "drivers/char/tpm/tpm_crb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587282912,
      "name": "crb_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
    },
    {
      "addr": 18446744071592466753,
      "name": "crb_send.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
int crb_send(struct tpm_chip * chip, u8 * buf, size_t len)
```

```json
{
  "name": "crb_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "crb_send",
      "external": false,
      "loc": "drivers/char/tpm/tpm_crb.c:358",
      "file": "drivers/char/tpm/tpm_crb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588595232,
      "name": "crb_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
    },
    {
      "addr": 18446744071594336862,
      "name": "crb_send.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
int crb_send(struct tpm_chip * chip, u8 * buf, size_t len)
```

```json
{
  "name": "crb_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590053952,
      "name": "crb_send",
      "external": false,
      "loc": "drivers/char/tpm/tpm_crb.c:358",
      "file": "drivers/char/tpm/tpm_crb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590053952,
      "name": "crb_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
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
int crb_send(struct tpm_chip * chip, u8 * buf, size_t len)
```

```json
{
  "name": "crb_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590364960,
      "name": "crb_send",
      "external": false,
      "loc": "drivers/char/tpm/tpm_crb.c:397",
      "file": "drivers/char/tpm/tpm_crb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590364960,
      "name": "crb_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 382
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
int crb_send(struct tpm_chip * chip, u8 * buf, size_t len)
```

```json
{
  "name": "crb_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590706480,
      "name": "crb_send",
      "external": false,
      "loc": "drivers/char/tpm/tpm_crb.c:397",
      "file": "drivers/char/tpm/tpm_crb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590706480,
      "name": "crb_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 382
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
int crb_send(struct tpm_chip * chip, u8 * buf, size_t len)
```

```json
{
  "name": "crb_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498818616,
      "name": "crb_send",
      "external": false,
      "loc": "drivers/char/tpm/tpm_crb.c:358",
      "file": "drivers/char/tpm/tpm_crb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498818616,
      "name": "crb_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 408
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int crb_send(struct tpm_chip * chip, u8 * buf, size_t len)
```

```json
{
  "name": "crb_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "crb_send",
      "external": false,
      "loc": "drivers/char/tpm/tpm_crb.c:358",
      "file": "drivers/char/tpm/tpm_crb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585781312,
      "name": "crb_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
    },
    {
      "addr": 18446744071585783439,
      "name": "crb_send.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
int crb_send(struct tpm_chip * chip, u8 * buf, size_t len)
```

```json
{
  "name": "crb_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "crb_send",
      "external": false,
      "loc": "drivers/char/tpm/tpm_crb.c:358",
      "file": "drivers/char/tpm/tpm_crb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585640496,
      "name": "crb_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
    },
    {
      "addr": 18446744071585642623,
      "name": "crb_send.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
int crb_send(struct tpm_chip * chip, u8 * buf, size_t len)
```

```json
{
  "name": "crb_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "crb_send",
      "external": false,
      "loc": "drivers/char/tpm/tpm_crb.c:358",
      "file": "drivers/char/tpm/tpm_crb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585970352,
      "name": "crb_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
    },
    {
      "addr": 18446744071585972479,
      "name": "crb_send.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
int crb_send(struct tpm_chip * chip, u8 * buf, size_t len)
```

```json
{
  "name": "crb_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "crb_send",
      "external": false,
      "loc": "drivers/char/tpm/tpm_crb.c:358",
      "file": "drivers/char/tpm/tpm_crb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586078080,
      "name": "crb_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
    },
    {
      "addr": 18446744071586080207,
      "name": "crb_send.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int crb_send(struct tpm_chip * chip, u8 * buf, size_t len)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int crb_send(struct tpm_chip * chip, u8 * buf, size_t len)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int crb_send(struct tpm_chip * chip, u8 * buf, size_t len)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int crb_send(struct tpm_chip * chip, u8 * buf, size_t len)
```
</details>
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
