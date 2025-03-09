# Function: <code>fixup_owner</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int fixup_owner(u32 * uaddr, struct futex_q * q, int locked)
```

```json
{
  "name": "fixup_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579896016,
      "name": "fixup_owner",
      "external": false,
      "loc": "kernel/futex.c:2097",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_lock_pi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579896016,
      "name": "fixup_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
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
int fixup_owner(u32 * uaddr, struct futex_q * q, int locked)
```

```json
{
  "name": "fixup_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579923632,
      "name": "fixup_owner",
      "external": false,
      "loc": "kernel/futex.c:2221",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_lock_pi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579923632,
      "name": "fixup_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
int fixup_owner(u32 * uaddr, struct futex_q * q, int locked)
```

```json
{
  "name": "fixup_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579954288,
      "name": "fixup_owner",
      "external": false,
      "loc": "kernel/futex.c:2230",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_lock_pi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579954288,
      "name": "fixup_owner",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int fixup_owner(u32 * uaddr, struct futex_q * q, int locked)
```

```json
{
  "name": "fixup_owner",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579964016,
      "name": "fixup_owner",
      "external": false,
      "loc": "kernel/futex.c:2341",
      "file": "kernel/futex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_lock_pi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579964016,
      "name": "fixup_owner",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int fixup_owner(u32 * uaddr, struct futex_q * q, int locked)
```

```json
{
  "name": "fixup_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580006080,
      "name": "fixup_owner",
      "external": false,
      "loc": "kernel/futex.c:2469",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_lock_pi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580006080,
      "name": "fixup_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int fixup_owner(u32 * uaddr, struct futex_q * q, int locked)
```

```json
{
  "name": "fixup_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fixup_owner",
      "external": false,
      "loc": "kernel/futex.c:2451",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_lock_pi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580060768,
      "name": "fixup_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
    },
    {
      "addr": 18446744071580072632,
      "name": "fixup_owner.cold.29",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int fixup_owner(u32 * uaddr, struct futex_q * q, int locked)
```

```json
{
  "name": "fixup_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fixup_owner",
      "external": false,
      "loc": "kernel/futex.c:2519",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_lock_pi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580110176,
      "name": "fixup_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
    },
    {
      "addr": 18446744071580121490,
      "name": "fixup_owner.cold.28",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
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
int fixup_owner(u32 * uaddr, struct futex_q * q, int locked)
```

```json
{
  "name": "fixup_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fixup_owner",
      "external": false,
      "loc": "kernel/futex.c:2550",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_lock_pi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580156224,
      "name": "fixup_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    },
    {
      "addr": 18446744071580166636,
      "name": "fixup_owner.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
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
int fixup_owner(u32 * uaddr, struct futex_q * q, int locked)
```

```json
{
  "name": "fixup_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fixup_owner",
      "external": false,
      "loc": "kernel/futex.c:2642",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_lock_pi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580204336,
      "name": "fixup_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    },
    {
      "addr": 18446744071580214852,
      "name": "fixup_owner.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
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
int fixup_owner(u32 * uaddr, struct futex_q * q, int locked)
```

```json
{
  "name": "fixup_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fixup_owner",
      "external": false,
      "loc": "kernel/futex.c:2555",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_lock_pi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580273200,
      "name": "fixup_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    },
    {
      "addr": 18446744071580282593,
      "name": "fixup_owner.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int fixup_owner(u32 * uaddr, struct futex_q * q, int locked)
```

```json
{
  "name": "fixup_owner",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580258272,
      "name": "fixup_owner",
      "external": false,
      "loc": "kernel/futex.c:2536",
      "file": "kernel/futex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_lock_pi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580258272,
      "name": "fixup_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int fixup_owner(u32 * uaddr, struct futex_q * q, int locked)
```

```json
{
  "name": "fixup_owner",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580263792,
      "name": "fixup_owner",
      "external": false,
      "loc": "kernel/futex.c:2535",
      "file": "kernel/futex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_lock_pi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580263792,
      "name": "fixup_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int fixup_owner(u32 * uaddr, struct futex_q * q, int locked)
```

```json
{
  "name": "fixup_owner",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580413824,
      "name": "fixup_owner",
      "external": false,
      "loc": "kernel/futex.c:2783",
      "file": "kernel/futex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_lock_pi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580413824,
      "name": "fixup_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
    }
  ]
}
```
</details>
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
int fixup_owner(u32 * uaddr, struct futex_q * q, int locked)
```

```json
{
  "name": "fixup_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491440928,
      "name": "fixup_owner",
      "external": false,
      "loc": "kernel/futex.c:2642",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_lock_pi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491440928,
      "name": "fixup_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
int fixup_owner(u32 * uaddr, struct futex_q * q, int locked)
```

```json
{
  "name": "fixup_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225422672,
      "name": "fixup_owner",
      "external": false,
      "loc": "kernel/futex.c:2642",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_lock_pi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225422672,
      "name": "fixup_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
int fixup_owner(u32 * uaddr, struct futex_q * q, int locked)
```

```json
{
  "name": "fixup_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284391904,
      "name": "fixup_owner",
      "external": false,
      "loc": "kernel/futex.c:2642",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_lock_pi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284391904,
      "name": "fixup_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
int fixup_owner(u32 * uaddr, struct futex_q * q, int locked)
```

```json
{
  "name": "fixup_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271900150,
      "name": "fixup_owner",
      "external": false,
      "loc": "kernel/futex.c:2642",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_lock_pi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271900150,
      "name": "fixup_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int fixup_owner(u32 * uaddr, struct futex_q * q, int locked)
```

```json
{
  "name": "fixup_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fixup_owner",
      "external": false,
      "loc": "kernel/futex.c:2642",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_lock_pi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580173136,
      "name": "fixup_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    },
    {
      "addr": 18446744071580183652,
      "name": "fixup_owner.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
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
int fixup_owner(u32 * uaddr, struct futex_q * q, int locked)
```

```json
{
  "name": "fixup_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fixup_owner",
      "external": false,
      "loc": "kernel/futex.c:2642",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_lock_pi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580119920,
      "name": "fixup_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    },
    {
      "addr": 18446744071580131172,
      "name": "fixup_owner.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
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
int fixup_owner(u32 * uaddr, struct futex_q * q, int locked)
```

```json
{
  "name": "fixup_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fixup_owner",
      "external": false,
      "loc": "kernel/futex.c:2642",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_lock_pi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580164608,
      "name": "fixup_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    },
    {
      "addr": 18446744071580175124,
      "name": "fixup_owner.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
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
int fixup_owner(u32 * uaddr, struct futex_q * q, int locked)
```

```json
{
  "name": "fixup_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fixup_owner",
      "external": false,
      "loc": "kernel/futex.c:2642",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_lock_pi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580211536,
      "name": "fixup_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    },
    {
      "addr": 18446744071580227196,
      "name": "fixup_owner.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
int fixup_owner(u32 * uaddr, struct futex_q * q, int locked)
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
