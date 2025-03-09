# Function: <code>amd_df_indirect_read</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int amd_df_indirect_read(u16 node, u8 func, u16 reg, u8 instance_id, u32 * lo)
```

```json
{
  "name": "amd_df_indirect_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579262976,
      "name": "amd_df_indirect_read",
      "external": true,
      "loc": "arch/x86/kernel/amd_nb.c:147",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:umc_normaddr_to_sysaddr",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:umc_normaddr_to_sysaddr",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:umc_normaddr_to_sysaddr",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:umc_normaddr_to_sysaddr",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:umc_normaddr_to_sysaddr",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:umc_normaddr_to_sysaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579262976,
      "name": "amd_df_indirect_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int amd_df_indirect_read(u16 node, u8 func, u16 reg, u8 instance_id, u32 * lo)
```

```json
{
  "name": "amd_df_indirect_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579259760,
      "name": "amd_df_indirect_read",
      "external": true,
      "loc": "arch/x86/kernel/amd_nb.c:147",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:umc_normaddr_to_sysaddr",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:umc_normaddr_to_sysaddr",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:umc_normaddr_to_sysaddr",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:umc_normaddr_to_sysaddr",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:umc_normaddr_to_sysaddr",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:umc_normaddr_to_sysaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579259760,
      "name": "amd_df_indirect_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
int amd_df_indirect_read(u16 node, u8 func, u16 reg, u8 instance_id, u32 * lo)
```

```json
{
  "name": "amd_df_indirect_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579276560,
      "name": "amd_df_indirect_read",
      "external": true,
      "loc": "arch/x86/kernel/amd_nb.c:151",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:umc_normaddr_to_sysaddr",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:umc_normaddr_to_sysaddr",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:umc_normaddr_to_sysaddr",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:umc_normaddr_to_sysaddr",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:umc_normaddr_to_sysaddr",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:umc_normaddr_to_sysaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579276560,
      "name": "amd_df_indirect_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
int amd_df_indirect_read(u16 node, u8 func, u16 reg, u8 instance_id, u32 * lo)
```

```json
{
  "name": "amd_df_indirect_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "amd_df_indirect_read",
      "external": true,
      "loc": "arch/x86/kernel/amd_nb.c:157",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:umc_normaddr_to_sysaddr",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:umc_normaddr_to_sysaddr",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:umc_normaddr_to_sysaddr",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:umc_normaddr_to_sysaddr",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:umc_normaddr_to_sysaddr",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:umc_normaddr_to_sysaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579289829,
      "name": "amd_df_indirect_read.cold.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071579287872,
      "name": "amd_df_indirect_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
int amd_df_indirect_read(u16 node, u8 func, u16 reg, u8 instance_id, u32 * lo)
```

```json
{
  "name": "amd_df_indirect_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "amd_df_indirect_read",
      "external": true,
      "loc": "arch/x86/kernel/amd_nb.c:177",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr",
        "arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr",
        "arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr",
        "arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr",
        "arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr",
        "arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579314037,
      "name": "amd_df_indirect_read.cold.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071579311824,
      "name": "amd_df_indirect_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
int amd_df_indirect_read(u16 node, u8 func, u16 reg, u8 instance_id, u32 * lo)
```

```json
{
  "name": "amd_df_indirect_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "amd_df_indirect_read",
      "external": true,
      "loc": "arch/x86/kernel/amd_nb.c:178",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr",
        "arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr",
        "arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr",
        "arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr",
        "arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr",
        "arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579329152,
      "name": "amd_df_indirect_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071579326992,
      "name": "amd_df_indirect_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
int amd_df_indirect_read(u16 node, u8 func, u16 reg, u8 instance_id, u32 * lo)
```

```json
{
  "name": "amd_df_indirect_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "amd_df_indirect_read",
      "external": true,
      "loc": "arch/x86/kernel/amd_nb.c:184",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr",
        "arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr",
        "arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr",
        "arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr",
        "arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr",
        "arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579333200,
      "name": "amd_df_indirect_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071579331040,
      "name": "amd_df_indirect_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
int amd_df_indirect_read(u16 node, u8 func, u16 reg, u8 instance_id, u32 * lo)
```

```json
{
  "name": "amd_df_indirect_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "amd_df_indirect_read",
      "external": true,
      "loc": "arch/x86/kernel/amd_nb.c:187",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr",
        "arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr",
        "arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr",
        "arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr",
        "arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr",
        "arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579362688,
      "name": "amd_df_indirect_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071579360384,
      "name": "amd_df_indirect_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
int amd_df_indirect_read(u16 node, u8 func, u16 reg, u8 instance_id, u32 * lo)
```

```json
{
  "name": "amd_df_indirect_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "amd_df_indirect_read",
      "external": true,
      "loc": "arch/x86/kernel/amd_nb.c:187",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr",
        "arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr",
        "arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr",
        "arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr",
        "arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr",
        "arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591264201,
      "name": "amd_df_indirect_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071579359584,
      "name": "amd_df_indirect_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
int amd_df_indirect_read(u16 node, u8 func, u16 reg, u8 instance_id, u32 * lo)
```

```json
{
  "name": "amd_df_indirect_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "amd_df_indirect_read",
      "external": true,
      "loc": "arch/x86/kernel/amd_nb.c:187",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr",
        "arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr",
        "arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr",
        "arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr",
        "arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr",
        "arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591206523,
      "name": "amd_df_indirect_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071579363984,
      "name": "amd_df_indirect_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
int amd_df_indirect_read(u16 node, u8 func, u16 reg, u8 instance_id, u32 * lo)
```

```json
{
  "name": "amd_df_indirect_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "amd_df_indirect_read",
      "external": true,
      "loc": "arch/x86/kernel/amd_nb.c:200",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr",
        "arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr",
        "arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr",
        "arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr",
        "arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr",
        "arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592079281,
      "name": "amd_df_indirect_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071579424544,
      "name": "amd_df_indirect_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
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
int amd_df_indirect_read(u16 node, u8 func, u16 reg, u8 instance_id, u32 * lo)
```

```json
{
  "name": "amd_df_indirect_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "amd_df_indirect_read",
      "external": true,
      "loc": "arch/x86/kernel/amd_nb.c:184",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr",
        "arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr",
        "arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr",
        "arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr",
        "arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr",
        "arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579329104,
      "name": "amd_df_indirect_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071579326944,
      "name": "amd_df_indirect_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
int amd_df_indirect_read(u16 node, u8 func, u16 reg, u8 instance_id, u32 * lo)
```

```json
{
  "name": "amd_df_indirect_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "amd_df_indirect_read",
      "external": true,
      "loc": "arch/x86/kernel/amd_nb.c:184",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr",
        "arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr",
        "arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr",
        "arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr",
        "arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr",
        "arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579263520,
      "name": "amd_df_indirect_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071579261392,
      "name": "amd_df_indirect_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
int amd_df_indirect_read(u16 node, u8 func, u16 reg, u8 instance_id, u32 * lo)
```

```json
{
  "name": "amd_df_indirect_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "amd_df_indirect_read",
      "external": true,
      "loc": "arch/x86/kernel/amd_nb.c:184",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr",
        "arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr",
        "arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr",
        "arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr",
        "arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr",
        "arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579329024,
      "name": "amd_df_indirect_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071579326864,
      "name": "amd_df_indirect_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
int amd_df_indirect_read(u16 node, u8 func, u16 reg, u8 instance_id, u32 * lo)
```

```json
{
  "name": "amd_df_indirect_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "amd_df_indirect_read",
      "external": true,
      "loc": "arch/x86/kernel/amd_nb.c:184",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr",
        "arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr",
        "arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr",
        "arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr",
        "arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr",
        "arch/x86/kernel/cpu/mce/amd.c:umc_normaddr_to_sysaddr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579337312,
      "name": "amd_df_indirect_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071579335152,
      "name": "amd_df_indirect_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
int amd_df_indirect_read(u16 node, u8 func, u16 reg, u8 instance_id, u32 * lo)
```
</details>
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
int amd_df_indirect_read(u16 node, u8 func, u16 reg, u8 instance_id, u32 * lo)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int amd_df_indirect_read(u16 node, u8 func, u16 reg, u8 instance_id, u32 * lo)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int amd_df_indirect_read(u16 node, u8 func, u16 reg, u8 instance_id, u32 * lo)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int amd_df_indirect_read(u16 node, u8 func, u16 reg, u8 instance_id, u32 * lo)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int amd_df_indirect_read(u16 node, u8 func, u16 reg, u8 instance_id, u32 * lo)
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
