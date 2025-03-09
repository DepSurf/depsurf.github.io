# Function: <code>tboot_sleep</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int tboot_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control)
```

```json
{
  "name": "tboot_sleep",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579099728,
      "name": "tboot_sleep",
      "external": false,
      "loc": "arch/x86/kernel/tboot.c:277",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579099728,
      "name": "tboot_sleep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 318
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
int tboot_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control)
```

```json
{
  "name": "tboot_sleep",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579099248,
      "name": "tboot_sleep",
      "external": false,
      "loc": "arch/x86/kernel/tboot.c:271",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579099248,
      "name": "tboot_sleep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 318
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
int tboot_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control)
```

```json
{
  "name": "tboot_sleep",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579097376,
      "name": "tboot_sleep",
      "external": false,
      "loc": "arch/x86/kernel/tboot.c:271",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579097376,
      "name": "tboot_sleep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 318
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
int tboot_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control)
```

```json
{
  "name": "tboot_sleep",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579089296,
      "name": "tboot_sleep",
      "external": false,
      "loc": "arch/x86/kernel/tboot.c:275",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579089296,
      "name": "tboot_sleep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
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
int tboot_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control)
```

```json
{
  "name": "tboot_sleep",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579100080,
      "name": "tboot_sleep",
      "external": false,
      "loc": "arch/x86/kernel/tboot.c:286",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579100080,
      "name": "tboot_sleep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int tboot_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control)
```

```json
{
  "name": "tboot_sleep",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "tboot_sleep",
      "external": false,
      "loc": "arch/x86/kernel/tboot.c:286",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579105600,
      "name": "tboot_sleep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 337
    },
    {
      "addr": 18446744071579106213,
      "name": "tboot_sleep.cold.19",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int tboot_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control)
```

```json
{
  "name": "tboot_sleep",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579111272,
      "name": "tboot_sleep",
      "external": false,
      "loc": "arch/x86/kernel/tboot.c:286",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579111232,
      "name": "tboot_sleep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 337
    },
    {
      "addr": 18446744071579111845,
      "name": "tboot_sleep.cold.19",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int tboot_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control)
```

```json
{
  "name": "tboot_sleep",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579121241,
      "name": "tboot_sleep",
      "external": false,
      "loc": "arch/x86/kernel/tboot.c:273",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579121200,
      "name": "tboot_sleep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
    },
    {
      "addr": 18446744071579121805,
      "name": "tboot_sleep.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int tboot_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control)
```

```json
{
  "name": "tboot_sleep",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579123113,
      "name": "tboot_sleep",
      "external": false,
      "loc": "arch/x86/kernel/tboot.c:273",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579123072,
      "name": "tboot_sleep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
    },
    {
      "addr": 18446744071579123677,
      "name": "tboot_sleep.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
int tboot_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control)
```

```json
{
  "name": "tboot_sleep",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579137882,
      "name": "tboot_sleep",
      "external": false,
      "loc": "arch/x86/kernel/tboot.c:275",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579137840,
      "name": "tboot_sleep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    },
    {
      "addr": 18446744071579139124,
      "name": "tboot_sleep.cold",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int tboot_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control)
```

```json
{
  "name": "tboot_sleep",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579135882,
      "name": "tboot_sleep",
      "external": false,
      "loc": "arch/x86/kernel/tboot.c:276",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579135840,
      "name": "tboot_sleep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    },
    {
      "addr": 18446744071591251627,
      "name": "tboot_sleep.cold",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int tboot_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control)
```

```json
{
  "name": "tboot_sleep",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579142399,
      "name": "tboot_sleep",
      "external": false,
      "loc": "arch/x86/kernel/tboot.c:284",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579142352,
      "name": "tboot_sleep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 315
    },
    {
      "addr": 18446744071591195230,
      "name": "tboot_sleep.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
int tboot_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control)
```

```json
{
  "name": "tboot_sleep",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579169425,
      "name": "tboot_sleep",
      "external": false,
      "loc": "arch/x86/kernel/tboot.c:284",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579169376,
      "name": "tboot_sleep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 379
    },
    {
      "addr": 18446744071592061014,
      "name": "tboot_sleep.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
int tboot_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control)
```

```json
{
  "name": "tboot_sleep",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tboot_sleep",
      "external": false,
      "loc": "arch/x86/kernel/tboot.c:283",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579215088,
      "name": "tboot_sleep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 391
    },
    {
      "addr": 18446744071593827544,
      "name": "tboot_sleep.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
int tboot_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control)
```

```json
{
  "name": "tboot_sleep",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579271856,
      "name": "tboot_sleep",
      "external": false,
      "loc": "arch/x86/kernel/tboot.c:282",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579271856,
      "name": "tboot_sleep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 404
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
int tboot_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control)
```

```json
{
  "name": "tboot_sleep",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579278288,
      "name": "tboot_sleep",
      "external": false,
      "loc": "arch/x86/kernel/tboot.c:282",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579278288,
      "name": "tboot_sleep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 404
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
int tboot_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control)
```

```json
{
  "name": "tboot_sleep",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579308192,
      "name": "tboot_sleep",
      "external": false,
      "loc": "arch/x86/kernel/tboot.c:282",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579308192,
      "name": "tboot_sleep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 404
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int tboot_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control)
```

```json
{
  "name": "tboot_sleep",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579123497,
      "name": "tboot_sleep",
      "external": false,
      "loc": "arch/x86/kernel/tboot.c:273",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579123456,
      "name": "tboot_sleep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
    },
    {
      "addr": 18446744071579124061,
      "name": "tboot_sleep.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
int tboot_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control)
```

```json
{
  "name": "tboot_sleep",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579055433,
      "name": "tboot_sleep",
      "external": false,
      "loc": "arch/x86/kernel/tboot.c:273",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579055392,
      "name": "tboot_sleep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
    },
    {
      "addr": 18446744071579055997,
      "name": "tboot_sleep.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
int tboot_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control)
```

```json
{
  "name": "tboot_sleep",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579123049,
      "name": "tboot_sleep",
      "external": false,
      "loc": "arch/x86/kernel/tboot.c:273",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579123008,
      "name": "tboot_sleep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
    },
    {
      "addr": 18446744071579123613,
      "name": "tboot_sleep.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
int tboot_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control)
```

```json
{
  "name": "tboot_sleep",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579128169,
      "name": "tboot_sleep",
      "external": false,
      "loc": "arch/x86/kernel/tboot.c:273",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579128128,
      "name": "tboot_sleep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
    },
    {
      "addr": 18446744071579128733,
      "name": "tboot_sleep.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int tboot_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int tboot_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int tboot_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int tboot_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control)
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
