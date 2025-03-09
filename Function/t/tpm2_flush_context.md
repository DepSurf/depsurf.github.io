# Function: <code>tpm2_flush_context</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tpm2_flush_context",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584247976,
      "name": "tpm2_flush_context",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-cmd.c:593",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tpm2_flush_context",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584587699,
      "name": "tpm2_flush_context",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-cmd.c:593",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted"
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
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void tpm2_flush_context(struct tpm_chip * chip, u32 handle)
```

```json
{
  "name": "tpm2_flush_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm2_flush_context",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-cmd.c:362",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-space.c:tpm2_commit_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_commit_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_flush_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_flush_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_del_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585856041,
      "name": "tpm2_flush_context.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071585851360,
      "name": "tpm2_flush_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
void tpm2_flush_context(struct tpm_chip * chip, u32 handle)
```

```json
{
  "name": "tpm2_flush_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm2_flush_context",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-cmd.c:362",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-space.c:tpm2_commit_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_commit_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_flush_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_flush_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_del_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585998633,
      "name": "tpm2_flush_context.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071585993936,
      "name": "tpm2_flush_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
void tpm2_flush_context(struct tpm_chip * chip, u32 handle)
```

```json
{
  "name": "tpm2_flush_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm2_flush_context",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-cmd.c:348",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-space.c:tpm2_save_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_flush_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_flush_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_del_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586736505,
      "name": "tpm2_flush_context.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071586731664,
      "name": "tpm2_flush_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
void tpm2_flush_context(struct tpm_chip * chip, u32 handle)
```

```json
{
  "name": "tpm2_flush_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm2_flush_context",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-cmd.c:348",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-space.c:tpm2_save_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_flush_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_flush_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_del_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591470722,
      "name": "tpm2_flush_context.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071586826384,
      "name": "tpm2_flush_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
void tpm2_flush_context(struct tpm_chip * chip, u32 handle)
```

```json
{
  "name": "tpm2_flush_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm2_flush_context",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-cmd.c:348",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-space.c:tpm2_commit_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_commit_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_flush_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_flush_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_del_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591411989,
      "name": "tpm2_flush_context.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071586706272,
      "name": "tpm2_flush_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
void tpm2_flush_context(struct tpm_chip * chip, u32 handle)
```

```json
{
  "name": "tpm2_flush_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm2_flush_context",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-cmd.c:348",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-space.c:tpm2_commit_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_commit_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_flush_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_flush_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_del_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592463934,
      "name": "tpm2_flush_context.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071587256048,
      "name": "tpm2_flush_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
void tpm2_flush_context(struct tpm_chip * chip, u32 handle)
```

```json
{
  "name": "tpm2_flush_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm2_flush_context",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-cmd.c:348",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-space.c:tpm2_commit_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_commit_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_flush_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_flush_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_del_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594333841,
      "name": "tpm2_flush_context.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071588565296,
      "name": "tpm2_flush_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
void tpm2_flush_context(struct tpm_chip * chip, u32 handle)
```

```json
{
  "name": "tpm2_flush_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590019344,
      "name": "tpm2_flush_context",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-cmd.c:348",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-space.c:tpm2_commit_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_commit_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_flush_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_flush_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_del_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590019344,
      "name": "tpm2_flush_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
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
void tpm2_flush_context(struct tpm_chip * chip, u32 handle)
```

```json
{
  "name": "tpm2_flush_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590328640,
      "name": "tpm2_flush_context",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-cmd.c:348",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-space.c:tpm2_commit_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_commit_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_flush_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_flush_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_del_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590328640,
      "name": "tpm2_flush_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
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
void tpm2_flush_context(struct tpm_chip * chip, u32 handle)
```

```json
{
  "name": "tpm2_flush_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590670080,
      "name": "tpm2_flush_context",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-cmd.c:348",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-space.c:tpm2_commit_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_commit_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_flush_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_flush_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_del_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590670080,
      "name": "tpm2_flush_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
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
void tpm2_flush_context(struct tpm_chip * chip, u32 handle)
```

```json
{
  "name": "tpm2_flush_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498789872,
      "name": "tpm2_flush_context",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-cmd.c:362",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-space.c:tpm2_commit_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_commit_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_flush_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_flush_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_del_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498789872,
      "name": "tpm2_flush_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
void tpm2_flush_context(struct tpm_chip * chip, u32 handle)
```

```json
{
  "name": "tpm2_flush_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231404428,
      "name": "tpm2_flush_context",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-cmd.c:362",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-space.c:tpm2_commit_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_commit_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_flush_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_flush_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_del_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231404428,
      "name": "tpm2_flush_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
void tpm2_flush_context(struct tpm_chip * chip, u32 handle)
```

```json
{
  "name": "tpm2_flush_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291983616,
      "name": "tpm2_flush_context",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-cmd.c:362",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-space.c:tpm2_commit_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_commit_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_flush_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_flush_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_del_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291983616,
      "name": "tpm2_flush_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 408
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
void tpm2_flush_context(struct tpm_chip * chip, u32 handle)
```

```json
{
  "name": "tpm2_flush_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276288258,
      "name": "tpm2_flush_context",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-cmd.c:362",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-space.c:tpm2_commit_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_commit_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_flush_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_flush_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_del_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276288258,
      "name": "tpm2_flush_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 458
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
void tpm2_flush_context(struct tpm_chip * chip, u32 handle)
```

```json
{
  "name": "tpm2_flush_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm2_flush_context",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-cmd.c:362",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-space.c:tpm2_commit_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_commit_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_flush_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_flush_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_del_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585759609,
      "name": "tpm2_flush_context.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071585754912,
      "name": "tpm2_flush_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
void tpm2_flush_context(struct tpm_chip * chip, u32 handle)
```

```json
{
  "name": "tpm2_flush_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm2_flush_context",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-cmd.c:362",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-space.c:tpm2_commit_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_commit_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_flush_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_flush_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_del_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585618793,
      "name": "tpm2_flush_context.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071585614096,
      "name": "tpm2_flush_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
void tpm2_flush_context(struct tpm_chip * chip, u32 handle)
```

```json
{
  "name": "tpm2_flush_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm2_flush_context",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-cmd.c:362",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-space.c:tpm2_commit_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_commit_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_flush_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_flush_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_del_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585948649,
      "name": "tpm2_flush_context.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071585943952,
      "name": "tpm2_flush_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
void tpm2_flush_context(struct tpm_chip * chip, u32 handle)
```

```json
{
  "name": "tpm2_flush_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm2_flush_context",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-cmd.c:362",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-space.c:tpm2_commit_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_commit_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_flush_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_flush_space",
        "drivers/char/tpm/tpm2-space.c:tpm2_del_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586056409,
      "name": "tpm2_flush_context.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071586051792,
      "name": "tpm2_flush_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
void tpm2_flush_context(struct tpm_chip * chip, u32 handle)
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
