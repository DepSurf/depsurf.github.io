# Function: <code>lock_kernel_down</code>

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
void lock_kernel_down()
```

```json
{
  "name": "lock_kernel_down",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583026048,
      "name": "lock_kernel_down",
      "external": true,
      "loc": "security/lock_down.c:20",
      "file": "security/lock_down.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583026048,
      "name": "lock_kernel_down",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lock_kernel_down",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602889626,
      "name": "lock_kernel_down",
      "external": false,
      "loc": "security/lock_down.c:27",
      "file": "security/lock_down.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/lock_down.c:lockdown_param",
        "security/lock_down.c:init_lockdown"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lock_kernel_down",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071603063084,
      "name": "lock_kernel_down",
      "external": false,
      "loc": "security/lock_down.c:31",
      "file": "security/lock_down.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/lock_down.c:lockdown_param",
        "security/lock_down.c:init_lockdown"
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
  "name": "lock_kernel_down",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604865425,
      "name": "lock_kernel_down",
      "external": false,
      "loc": "security/lock_down.c:31",
      "file": "security/lock_down.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/lock_down.c:lockdown_param",
        "security/lock_down.c:init_lockdown"
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
  "name": "lock_kernel_down",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604971309,
      "name": "lock_kernel_down",
      "external": false,
      "loc": "security/lock_down.c:31",
      "file": "security/lock_down.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/lock_down.c:lockdown_param",
        "security/lock_down.c:init_lockdown"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int lock_kernel_down(const char * where, enum lockdown_reason level)
```

```json
{
  "name": "lock_kernel_down",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583774727,
      "name": "lock_kernel_down",
      "external": false,
      "loc": "security/lockdown/lockdown.c:53",
      "file": "security/lockdown/lockdown.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/lockdown/lockdown.c:lockdown_write",
        "security/lockdown/lockdown.c:lockdown_param",
        "security/lockdown/lockdown.c:lockdown_param"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583774592,
      "name": "lock_kernel_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071583775193,
      "name": "lock_kernel_down.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int lock_kernel_down(const char * where, enum lockdown_reason level)
```

```json
{
  "name": "lock_kernel_down",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584165175,
      "name": "lock_kernel_down",
      "external": false,
      "loc": "security/lockdown/lockdown.c:26",
      "file": "security/lockdown/lockdown.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/lockdown/lockdown.c:lockdown_write"
      ],
      "caller_func": [
        "security/lockdown/lockdown.c:lockdown_param",
        "security/lockdown/lockdown.c:lockdown_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584165024,
      "name": "lock_kernel_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071584165641,
      "name": "lock_kernel_down.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int lock_kernel_down(const char * where, enum lockdown_reason level)
```

```json
{
  "name": "lock_kernel_down",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584284423,
      "name": "lock_kernel_down",
      "external": false,
      "loc": "security/lockdown/lockdown.c:26",
      "file": "security/lockdown/lockdown.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/lockdown/lockdown.c:lockdown_write"
      ],
      "caller_func": [
        "security/lockdown/lockdown.c:lockdown_param",
        "security/lockdown/lockdown.c:lockdown_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584284272,
      "name": "lock_kernel_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071591369041,
      "name": "lock_kernel_down.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int lock_kernel_down(const char * where, enum lockdown_reason level)
```

```json
{
  "name": "lock_kernel_down",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584309511,
      "name": "lock_kernel_down",
      "external": false,
      "loc": "security/lockdown/lockdown.c:26",
      "file": "security/lockdown/lockdown.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/lockdown/lockdown.c:lockdown_write"
      ],
      "caller_func": [
        "security/lockdown/lockdown.c:lockdown_param",
        "security/lockdown/lockdown.c:lockdown_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584309360,
      "name": "lock_kernel_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071591311726,
      "name": "lock_kernel_down.cold",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int lock_kernel_down(const char * where, enum lockdown_reason level)
```

```json
{
  "name": "lock_kernel_down",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584696108,
      "name": "lock_kernel_down",
      "external": false,
      "loc": "security/lockdown/lockdown.c:26",
      "file": "security/lockdown/lockdown.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/lockdown/lockdown.c:lockdown_write"
      ],
      "caller_func": [
        "security/lockdown/lockdown.c:lockdown_param",
        "security/lockdown/lockdown.c:lockdown_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584695952,
      "name": "lock_kernel_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071592307365,
      "name": "lock_kernel_down.cold",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int lock_kernel_down(const char * where, enum lockdown_reason level)
```

```json
{
  "name": "lock_kernel_down",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585359876,
      "name": "lock_kernel_down",
      "external": false,
      "loc": "security/lockdown/lockdown.c:26",
      "file": "security/lockdown/lockdown.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/lockdown/lockdown.c:lockdown_write"
      ],
      "caller_func": [
        "security/lockdown/lockdown.c:lockdown_param",
        "security/lockdown/lockdown.c:lockdown_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585359712,
      "name": "lock_kernel_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071594088929,
      "name": "lock_kernel_down.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int lock_kernel_down(const char * where, enum lockdown_reason level)
```

```json
{
  "name": "lock_kernel_down",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586109748,
      "name": "lock_kernel_down",
      "external": false,
      "loc": "security/lockdown/lockdown.c:27",
      "file": "security/lockdown/lockdown.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/lockdown/lockdown.c:lockdown_write",
        "security/lockdown/lockdown.c:lockdown_param",
        "security/lockdown/lockdown.c:lockdown_param"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586109536,
      "name": "lock_kernel_down",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int lock_kernel_down(const char * where, enum lockdown_reason level)
```

```json
{
  "name": "lock_kernel_down",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586348356,
      "name": "lock_kernel_down",
      "external": false,
      "loc": "security/lockdown/lockdown.c:27",
      "file": "security/lockdown/lockdown.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/lockdown/lockdown.c:lockdown_write",
        "security/lockdown/lockdown.c:lockdown_param",
        "security/lockdown/lockdown.c:lockdown_param"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586348144,
      "name": "lock_kernel_down",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int lock_kernel_down(const char * where, enum lockdown_reason level)
```

```json
{
  "name": "lock_kernel_down",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586615412,
      "name": "lock_kernel_down",
      "external": false,
      "loc": "security/lockdown/lockdown.c:27",
      "file": "security/lockdown/lockdown.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/lockdown/lockdown.c:lockdown_write",
        "security/lockdown/lockdown.c:lockdown_param",
        "security/lockdown/lockdown.c:lockdown_param"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586615200,
      "name": "lock_kernel_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int lock_kernel_down(const char * where, enum lockdown_reason level)
```

```json
{
  "name": "lock_kernel_down",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495576344,
      "name": "lock_kernel_down",
      "external": false,
      "loc": "security/lockdown/lockdown.c:53",
      "file": "security/lockdown/lockdown.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/lockdown/lockdown.c:lockdown_write",
        "security/lockdown/lockdown.c:lockdown_param",
        "security/lockdown/lockdown.c:lockdown_param"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495576128,
      "name": "lock_kernel_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int lock_kernel_down(const char * where, enum lockdown_reason level)
```

```json
{
  "name": "lock_kernel_down",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228938468,
      "name": "lock_kernel_down",
      "external": false,
      "loc": "security/lockdown/lockdown.c:53",
      "file": "security/lockdown/lockdown.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/lockdown/lockdown.c:lockdown_write",
        "security/lockdown/lockdown.c:lockdown_param",
        "security/lockdown/lockdown.c:lockdown_param"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3228938248,
      "name": "lock_kernel_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int lock_kernel_down(const char * where, enum lockdown_reason level)
```

```json
{
  "name": "lock_kernel_down",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055289672876,
      "name": "lock_kernel_down",
      "external": false,
      "loc": "security/lockdown/lockdown.c:53",
      "file": "security/lockdown/lockdown.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/lockdown/lockdown.c:lockdown_write",
        "security/lockdown/lockdown.c:lockdown_param",
        "security/lockdown/lockdown.c:lockdown_param"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289672224,
      "name": "lock_kernel_down",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int lock_kernel_down(const char * where, enum lockdown_reason level)
```

```json
{
  "name": "lock_kernel_down",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274743454,
      "name": "lock_kernel_down",
      "external": false,
      "loc": "security/lockdown/lockdown.c:53",
      "file": "security/lockdown/lockdown.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/lockdown/lockdown.c:lockdown_write",
        "security/lockdown/lockdown.c:lockdown_param",
        "security/lockdown/lockdown.c:lockdown_param"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274743272,
      "name": "lock_kernel_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int lock_kernel_down(const char * where, enum lockdown_reason level)
```

```json
{
  "name": "lock_kernel_down",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583743463,
      "name": "lock_kernel_down",
      "external": false,
      "loc": "security/lockdown/lockdown.c:53",
      "file": "security/lockdown/lockdown.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/lockdown/lockdown.c:lockdown_write",
        "security/lockdown/lockdown.c:lockdown_param",
        "security/lockdown/lockdown.c:lockdown_param"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583743328,
      "name": "lock_kernel_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071583743929,
      "name": "lock_kernel_down.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int lock_kernel_down(const char * where, enum lockdown_reason level)
```

```json
{
  "name": "lock_kernel_down",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583680519,
      "name": "lock_kernel_down",
      "external": false,
      "loc": "security/lockdown/lockdown.c:53",
      "file": "security/lockdown/lockdown.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/lockdown/lockdown.c:lockdown_write",
        "security/lockdown/lockdown.c:lockdown_param",
        "security/lockdown/lockdown.c:lockdown_param"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583680384,
      "name": "lock_kernel_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071583680985,
      "name": "lock_kernel_down.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int lock_kernel_down(const char * where, enum lockdown_reason level)
```

```json
{
  "name": "lock_kernel_down",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583727239,
      "name": "lock_kernel_down",
      "external": false,
      "loc": "security/lockdown/lockdown.c:53",
      "file": "security/lockdown/lockdown.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/lockdown/lockdown.c:lockdown_write",
        "security/lockdown/lockdown.c:lockdown_param",
        "security/lockdown/lockdown.c:lockdown_param"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583727104,
      "name": "lock_kernel_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071583727705,
      "name": "lock_kernel_down.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int lock_kernel_down(const char * where, enum lockdown_reason level)
```

```json
{
  "name": "lock_kernel_down",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583827991,
      "name": "lock_kernel_down",
      "external": false,
      "loc": "security/lockdown/lockdown.c:53",
      "file": "security/lockdown/lockdown.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/lockdown/lockdown.c:lockdown_write",
        "security/lockdown/lockdown.c:lockdown_param",
        "security/lockdown/lockdown.c:lockdown_param"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583827856,
      "name": "lock_kernel_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071583828457,
      "name": "lock_kernel_down.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
void lock_kernel_down()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➖</summary>

```c
void lock_kernel_down()
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
int lock_kernel_down(const char * where, enum lockdown_reason level)
```
</details>
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
