# Function: <code>param_set_bool</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int param_set_bool(const char * val, const struct kernel_param * kp)
```

```json
{
  "name": "param_set_bool",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579496416,
      "name": "param_set_bool",
      "external": true,
      "loc": "kernel/params.c:343",
      "file": "kernel/params.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/params.c:param_set_invbool",
        "kernel/params.c:param_set_bint"
      ],
      "caller_func": [
        "security/apparmor/lsm.c:param_set_aabool",
        "security/apparmor/lsm.c:param_set_aalockpolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579496416,
      "name": "param_set_bool",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int param_set_bool(const char * val, const struct kernel_param * kp)
```

```json
{
  "name": "param_set_bool",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579510749,
      "name": "param_set_bool",
      "external": true,
      "loc": "kernel/params.c:343",
      "file": "kernel/params.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/params.c:param_set_bint",
        "kernel/params.c:param_set_invbool",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/params.c:param_set_bool_enable_only"
      ],
      "caller_func": [
        "security/apparmor/lsm.c:param_set_aabool",
        "security/apparmor/lsm.c:param_set_aalockpolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579510432,
      "name": "param_set_bool",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int param_set_bool(const char * val, const struct kernel_param * kp)
```

```json
{
  "name": "param_set_bool",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579531421,
      "name": "param_set_bool",
      "external": true,
      "loc": "kernel/params.c:343",
      "file": "kernel/params.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/params.c:param_set_bint",
        "kernel/params.c:param_set_invbool",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/params.c:param_set_bool_enable_only"
      ],
      "caller_func": [
        "mm/zswap.c:zswap_enabled_param_set",
        "security/apparmor/lsm.c:param_set_aabool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579531104,
      "name": "param_set_bool",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
int param_set_bool(const char * val, const struct kernel_param * kp)
```

```json
{
  "name": "param_set_bool",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579519213,
      "name": "param_set_bool",
      "external": true,
      "loc": "kernel/params.c:291",
      "file": "kernel/params.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/params.c:param_set_bint",
        "kernel/params.c:param_set_invbool",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/params.c:param_set_bool_enable_only"
      ],
      "caller_func": [
        "mm/zswap.c:zswap_enabled_param_set",
        "security/apparmor/lsm.c:param_set_aabool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579518896,
      "name": "param_set_bool",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int param_set_bool(const char * val, const struct kernel_param * kp)
```

```json
{
  "name": "param_set_bool",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579545405,
      "name": "param_set_bool",
      "external": true,
      "loc": "kernel/params.c:299",
      "file": "kernel/params.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/params.c:param_set_bint",
        "kernel/params.c:param_set_invbool",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/params.c:param_set_bool_enable_only"
      ],
      "caller_func": [
        "mm/zswap.c:zswap_enabled_param_set",
        "security/apparmor/lsm.c:param_set_aabool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579545088,
      "name": "param_set_bool",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int param_set_bool(const char * val, const struct kernel_param * kp)
```

```json
{
  "name": "param_set_bool",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579572740,
      "name": "param_set_bool",
      "external": true,
      "loc": "kernel/params.c:299",
      "file": "kernel/params.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/params.c:param_set_bint",
        "kernel/params.c:param_set_invbool",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/params.c:param_set_bool_enable_only"
      ],
      "caller_func": [
        "mm/zswap.c:zswap_enabled_param_set",
        "security/apparmor/lsm.c:param_set_aabool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579572400,
      "name": "param_set_bool",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int param_set_bool(const char * val, const struct kernel_param * kp)
```

```json
{
  "name": "param_set_bool",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579609924,
      "name": "param_set_bool",
      "external": true,
      "loc": "kernel/params.c:299",
      "file": "kernel/params.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/params.c:param_set_bint",
        "kernel/params.c:param_set_invbool",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/params.c:param_set_bool_enable_only"
      ],
      "caller_func": [
        "mm/zswap.c:zswap_enabled_param_set",
        "security/apparmor/lsm.c:param_set_aaintbool",
        "security/apparmor/lsm.c:param_set_aabool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579609584,
      "name": "param_set_bool",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int param_set_bool(const char * val, const struct kernel_param * kp)
```

```json
{
  "name": "param_set_bool",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579634276,
      "name": "param_set_bool",
      "external": true,
      "loc": "kernel/params.c:287",
      "file": "kernel/params.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/params.c:param_set_bint",
        "kernel/params.c:param_set_invbool",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/params.c:param_set_bool_enable_only"
      ],
      "caller_func": [
        "mm/shuffle.c:shuffle_store",
        "mm/zswap.c:zswap_enabled_param_set",
        "security/apparmor/lsm.c:param_set_aaintbool",
        "security/apparmor/lsm.c:param_set_aabool",
        "security/apparmor/lsm.c:param_set_aalockpolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579633936,
      "name": "param_set_bool",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int param_set_bool(const char * val, const struct kernel_param * kp)
```

```json
{
  "name": "param_set_bool",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579659876,
      "name": "param_set_bool",
      "external": true,
      "loc": "kernel/params.c:288",
      "file": "kernel/params.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/params.c:param_set_bint",
        "kernel/params.c:param_set_invbool",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/params.c:param_set_bool_enable_only"
      ],
      "caller_func": [
        "mm/shuffle.c:shuffle_store",
        "mm/zswap.c:zswap_enabled_param_set",
        "security/apparmor/lsm.c:param_set_aaintbool",
        "security/apparmor/lsm.c:param_set_aabool",
        "security/apparmor/lsm.c:param_set_aalockpolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579659536,
      "name": "param_set_bool",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int param_set_bool(const char * val, const struct kernel_param * kp)
```

```json
{
  "name": "param_set_bool",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579692644,
      "name": "param_set_bool",
      "external": true,
      "loc": "kernel/params.c:288",
      "file": "kernel/params.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/params.c:param_set_bint",
        "kernel/params.c:param_set_invbool",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/params.c:param_set_bool_enable_only"
      ],
      "caller_func": [
        "mm/shuffle.c:shuffle_store",
        "mm/zswap.c:zswap_enabled_param_set",
        "security/apparmor/lsm.c:param_set_aaintbool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579692304,
      "name": "param_set_bool",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
int param_set_bool(const char * val, const struct kernel_param * kp)
```

```json
{
  "name": "param_set_bool",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579670932,
      "name": "param_set_bool",
      "external": true,
      "loc": "kernel/params.c:289",
      "file": "kernel/params.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/params.c:param_set_bint",
        "kernel/params.c:param_set_invbool",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/params.c:param_set_bool_enable_only"
      ],
      "caller_func": [
        "mm/shuffle.c:shuffle_store",
        "mm/zswap.c:zswap_enabled_param_set",
        "security/apparmor/lsm.c:param_set_aaintbool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579670592,
      "name": "param_set_bool",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
int param_set_bool(const char * val, const struct kernel_param * kp)
```

```json
{
  "name": "param_set_bool",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579677860,
      "name": "param_set_bool",
      "external": true,
      "loc": "kernel/params.c:289",
      "file": "kernel/params.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/params.c:param_set_bint",
        "kernel/params.c:param_set_invbool",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/params.c:param_set_bool_enable_only"
      ],
      "caller_func": [
        "mm/shuffle.c:shuffle_store",
        "mm/zswap.c:zswap_enabled_param_set",
        "security/apparmor/lsm.c:param_set_aaintbool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579677520,
      "name": "param_set_bool",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
int param_set_bool(const char * val, const struct kernel_param * kp)
```

```json
{
  "name": "param_set_bool",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579756630,
      "name": "param_set_bool",
      "external": true,
      "loc": "kernel/params.c:307",
      "file": "kernel/params.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/params.c:param_set_bint",
        "kernel/params.c:param_set_invbool",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/params.c:param_set_bool_enable_only"
      ],
      "caller_func": [
        "mm/shuffle.c:shuffle_store",
        "mm/zswap.c:zswap_enabled_param_set",
        "security/apparmor/lsm.c:param_set_aaintbool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579755696,
      "name": "param_set_bool",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int param_set_bool(const char * val, const struct kernel_param * kp)
```

```json
{
  "name": "param_set_bool",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579863236,
      "name": "param_set_bool",
      "external": true,
      "loc": "kernel/params.c:307",
      "file": "kernel/params.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/params.c:param_set_bint",
        "kernel/params.c:param_set_invbool",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/params.c:param_set_bool_enable_only"
      ],
      "caller_func": [
        "mm/shuffle.c:shuffle_store",
        "mm/memory_hotplug.c:memmap_on_memory_set",
        "mm/zswap.c:zswap_enabled_param_set",
        "security/apparmor/lsm.c:param_set_aaintbool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579861888,
      "name": "param_set_bool",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
int param_set_bool(const char * val, const struct kernel_param * kp)
```

```json
{
  "name": "param_set_bool",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580005284,
      "name": "param_set_bool",
      "external": true,
      "loc": "kernel/params.c:307",
      "file": "kernel/params.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/params.c:param_set_bint",
        "kernel/params.c:param_set_invbool",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/params.c:param_set_bool_enable_only"
      ],
      "caller_func": [
        "mm/shuffle.c:shuffle_param_set",
        "mm/zswap.c:zswap_enabled_param_set",
        "security/apparmor/lsm.c:param_set_aaintbool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580003792,
      "name": "param_set_bool",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
int param_set_bool(const char * val, const struct kernel_param * kp)
```

```json
{
  "name": "param_set_bool",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580059124,
      "name": "param_set_bool",
      "external": true,
      "loc": "kernel/params.c:308",
      "file": "kernel/params.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/params.c:param_set_bint",
        "kernel/params.c:param_set_invbool",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/params.c:param_set_bool_enable_only"
      ],
      "caller_func": [
        "mm/shuffle.c:shuffle_param_set",
        "security/apparmor/lsm.c:param_set_aaintbool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580057664,
      "name": "param_set_bool",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
int param_set_bool(const char * val, const struct kernel_param * kp)
```

```json
{
  "name": "param_set_bool",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580101652,
      "name": "param_set_bool",
      "external": true,
      "loc": "kernel/params.c:310",
      "file": "kernel/params.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/params.c:param_set_bint",
        "kernel/params.c:param_set_invbool",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/params.c:param_set_bool_enable_only"
      ],
      "caller_func": [
        "mm/shuffle.c:shuffle_param_set",
        "security/apparmor/lsm.c:param_set_aaintbool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580100192,
      "name": "param_set_bool",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
int param_set_bool(const char * val, const struct kernel_param * kp)
```

```json
{
  "name": "param_set_bool",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490835296,
      "name": "param_set_bool",
      "external": true,
      "loc": "kernel/params.c:288",
      "file": "kernel/params.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/params.c:param_set_bint",
        "kernel/params.c:param_set_invbool",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/params.c:param_set_bool_enable_only"
      ],
      "caller_func": [
        "mm/shuffle.c:shuffle_store",
        "mm/zswap.c:zswap_enabled_param_set",
        "security/apparmor/lsm.c:param_set_aaintbool",
        "security/apparmor/lsm.c:param_set_aabool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490834880,
      "name": "param_set_bool",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
int param_set_bool(const char * val, const struct kernel_param * kp)
```

```json
{
  "name": "param_set_bool",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224865372,
      "name": "param_set_bool",
      "external": true,
      "loc": "kernel/params.c:288",
      "file": "kernel/params.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/params.c:param_set_bint",
        "kernel/params.c:param_set_invbool",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/params.c:param_set_bool_enable_only"
      ],
      "caller_func": [
        "mm/shuffle.c:shuffle_store",
        "mm/zswap.c:zswap_enabled_param_set",
        "security/apparmor/lsm.c:param_set_aaintbool",
        "security/apparmor/lsm.c:param_set_aabool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224864964,
      "name": "param_set_bool",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
int param_set_bool(const char * val, const struct kernel_param * kp)
```

```json
{
  "name": "param_set_bool",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283670724,
      "name": "param_set_bool",
      "external": true,
      "loc": "kernel/params.c:288",
      "file": "kernel/params.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/params.c:param_set_bint",
        "kernel/params.c:param_set_invbool",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/params.c:param_set_bool_enable_only"
      ],
      "caller_func": [
        "mm/shuffle.c:shuffle_store",
        "mm/zswap.c:zswap_enabled_param_set",
        "security/apparmor/lsm.c:param_set_aaintbool",
        "security/apparmor/lsm.c:param_set_aabool",
        "security/apparmor/lsm.c:param_set_aalockpolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283670144,
      "name": "param_set_bool",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int param_set_bool(const char * val, const struct kernel_param * kp)
```

```json
{
  "name": "param_set_bool",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271505684,
      "name": "param_set_bool",
      "external": true,
      "loc": "kernel/params.c:288",
      "file": "kernel/params.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/params.c:param_set_bint",
        "kernel/params.c:param_set_invbool",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/params.c:param_set_bool_enable_only"
      ],
      "caller_func": [
        "mm/shuffle.c:shuffle_store",
        "mm/zswap.c:zswap_enabled_param_set",
        "security/apparmor/lsm.c:param_set_aaintbool",
        "security/apparmor/lsm.c:param_set_aabool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271505392,
      "name": "param_set_bool",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int param_set_bool(const char * val, const struct kernel_param * kp)
```

```json
{
  "name": "param_set_bool",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579636196,
      "name": "param_set_bool",
      "external": true,
      "loc": "kernel/params.c:288",
      "file": "kernel/params.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/params.c:param_set_bint",
        "kernel/params.c:param_set_invbool",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/params.c:param_set_bool_enable_only"
      ],
      "caller_func": [
        "mm/shuffle.c:shuffle_store",
        "mm/zswap.c:zswap_enabled_param_set",
        "security/apparmor/lsm.c:param_set_aaintbool",
        "security/apparmor/lsm.c:param_set_aabool",
        "security/apparmor/lsm.c:param_set_aalockpolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579635856,
      "name": "param_set_bool",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int param_set_bool(const char * val, const struct kernel_param * kp)
```

```json
{
  "name": "param_set_bool",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579564500,
      "name": "param_set_bool",
      "external": true,
      "loc": "kernel/params.c:288",
      "file": "kernel/params.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/params.c:param_set_bint",
        "kernel/params.c:param_set_invbool",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/params.c:param_set_bool_enable_only"
      ],
      "caller_func": [
        "mm/shuffle.c:shuffle_store",
        "mm/zswap.c:zswap_enabled_param_set",
        "security/apparmor/lsm.c:param_set_aaintbool",
        "security/apparmor/lsm.c:param_set_aabool",
        "security/apparmor/lsm.c:param_set_aalockpolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579564160,
      "name": "param_set_bool",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int param_set_bool(const char * val, const struct kernel_param * kp)
```

```json
{
  "name": "param_set_bool",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579633460,
      "name": "param_set_bool",
      "external": true,
      "loc": "kernel/params.c:288",
      "file": "kernel/params.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/params.c:param_set_bint",
        "kernel/params.c:param_set_invbool",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/params.c:param_set_bool_enable_only"
      ],
      "caller_func": [
        "mm/shuffle.c:shuffle_store",
        "mm/zswap.c:zswap_enabled_param_set",
        "security/apparmor/lsm.c:param_set_aaintbool",
        "security/apparmor/lsm.c:param_set_aabool",
        "security/apparmor/lsm.c:param_set_aalockpolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579633120,
      "name": "param_set_bool",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int param_set_bool(const char * val, const struct kernel_param * kp)
```

```json
{
  "name": "param_set_bool",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579667460,
      "name": "param_set_bool",
      "external": true,
      "loc": "kernel/params.c:288",
      "file": "kernel/params.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/params.c:param_set_bint",
        "kernel/params.c:param_set_invbool",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/params.c:param_set_bool_enable_only"
      ],
      "caller_func": [
        "mm/shuffle.c:shuffle_store",
        "mm/zswap.c:zswap_enabled_param_set",
        "security/apparmor/lsm.c:param_set_aaintbool",
        "security/apparmor/lsm.c:param_set_aabool",
        "security/apparmor/lsm.c:param_set_aalockpolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579667120,
      "name": "param_set_bool",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
