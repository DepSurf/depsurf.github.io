# Function: <code>xen_hvm_init_shared_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void xen_hvm_init_shared_info()
```

```json
{
  "name": "xen_hvm_init_shared_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587332272,
      "name": "xen_hvm_init_shared_info",
      "external": true,
      "loc": "arch/x86/xen/enlighten.c:1736",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_post_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587332272,
      "name": "xen_hvm_init_shared_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
void xen_hvm_init_shared_info()
```

```json
{
  "name": "xen_hvm_init_shared_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587830672,
      "name": "xen_hvm_init_shared_info",
      "external": true,
      "loc": "arch/x86/xen/enlighten.c:1756",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_post_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587830672,
      "name": "xen_hvm_init_shared_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
void xen_hvm_init_shared_info()
```

```json
{
  "name": "xen_hvm_init_shared_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588045984,
      "name": "xen_hvm_init_shared_info",
      "external": true,
      "loc": "arch/x86/xen/enlighten.c:1761",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_post_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588045984,
      "name": "xen_hvm_init_shared_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 282
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
void xen_hvm_init_shared_info()
```

```json
{
  "name": "xen_hvm_init_shared_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578958240,
      "name": "xen_hvm_init_shared_info",
      "external": true,
      "loc": "arch/x86/xen/enlighten_hvm.c:27",
      "file": "arch/x86/xen/enlighten_hvm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578958240,
      "name": "xen_hvm_init_shared_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void xen_hvm_init_shared_info()
```

```json
{
  "name": "xen_hvm_init_shared_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578961552,
      "name": "xen_hvm_init_shared_info",
      "external": true,
      "loc": "arch/x86/xen/enlighten_hvm.c:28",
      "file": "arch/x86/xen/enlighten_hvm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578961552,
      "name": "xen_hvm_init_shared_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void xen_hvm_init_shared_info()
```

```json
{
  "name": "xen_hvm_init_shared_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578964144,
      "name": "xen_hvm_init_shared_info",
      "external": true,
      "loc": "arch/x86/xen/enlighten_hvm.c:28",
      "file": "arch/x86/xen/enlighten_hvm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578964144,
      "name": "xen_hvm_init_shared_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void xen_hvm_init_shared_info()
```

```json
{
  "name": "xen_hvm_init_shared_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578961808,
      "name": "xen_hvm_init_shared_info",
      "external": true,
      "loc": "arch/x86/xen/enlighten_hvm.c:30",
      "file": "arch/x86/xen/enlighten_hvm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578961808,
      "name": "xen_hvm_init_shared_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void xen_hvm_init_shared_info()
```

```json
{
  "name": "xen_hvm_init_shared_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578968768,
      "name": "xen_hvm_init_shared_info",
      "external": true,
      "loc": "arch/x86/xen/enlighten_hvm.c:30",
      "file": "arch/x86/xen/enlighten_hvm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578968768,
      "name": "xen_hvm_init_shared_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void xen_hvm_init_shared_info()
```

```json
{
  "name": "xen_hvm_init_shared_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578971200,
      "name": "xen_hvm_init_shared_info",
      "external": true,
      "loc": "arch/x86/xen/enlighten_hvm.c:30",
      "file": "arch/x86/xen/enlighten_hvm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578971200,
      "name": "xen_hvm_init_shared_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void xen_hvm_init_shared_info()
```

```json
{
  "name": "xen_hvm_init_shared_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578980864,
      "name": "xen_hvm_init_shared_info",
      "external": true,
      "loc": "arch/x86/xen/enlighten_hvm.c:31",
      "file": "arch/x86/xen/enlighten_hvm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578980864,
      "name": "xen_hvm_init_shared_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void xen_hvm_init_shared_info()
```

```json
{
  "name": "xen_hvm_init_shared_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578983008,
      "name": "xen_hvm_init_shared_info",
      "external": true,
      "loc": "arch/x86/xen/enlighten_hvm.c:32",
      "file": "arch/x86/xen/enlighten_hvm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578983008,
      "name": "xen_hvm_init_shared_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void xen_hvm_init_shared_info()
```

```json
{
  "name": "xen_hvm_init_shared_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578992112,
      "name": "xen_hvm_init_shared_info",
      "external": true,
      "loc": "arch/x86/xen/enlighten_hvm.c:32",
      "file": "arch/x86/xen/enlighten_hvm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578992112,
      "name": "xen_hvm_init_shared_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void xen_hvm_init_shared_info()
```

```json
{
  "name": "xen_hvm_init_shared_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579009360,
      "name": "xen_hvm_init_shared_info",
      "external": true,
      "loc": "arch/x86/xen/enlighten_hvm.c:32",
      "file": "arch/x86/xen/enlighten_hvm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579009360,
      "name": "xen_hvm_init_shared_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void xen_hvm_init_shared_info()
```

```json
{
  "name": "xen_hvm_init_shared_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579027152,
      "name": "xen_hvm_init_shared_info",
      "external": true,
      "loc": "arch/x86/xen/enlighten_hvm.c:34",
      "file": "arch/x86/xen/enlighten_hvm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579027152,
      "name": "xen_hvm_init_shared_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
void xen_hvm_init_shared_info()
```

```json
{
  "name": "xen_hvm_init_shared_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071627519410,
      "name": "xen_hvm_init_shared_info",
      "external": true,
      "loc": "arch/x86/xen/enlighten_hvm.c:39",
      "file": "arch/x86/xen/enlighten_hvm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init"
      ],
      "caller_func": [
        "arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579056000,
      "name": "xen_hvm_init_shared_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
void xen_hvm_init_shared_info()
```

```json
{
  "name": "xen_hvm_init_shared_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071619264594,
      "name": "xen_hvm_init_shared_info",
      "external": true,
      "loc": "arch/x86/xen/enlighten_hvm.c:39",
      "file": "arch/x86/xen/enlighten_hvm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init"
      ],
      "caller_func": [
        "arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579055888,
      "name": "xen_hvm_init_shared_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
void xen_hvm_init_shared_info()
```

```json
{
  "name": "xen_hvm_init_shared_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071621557266,
      "name": "xen_hvm_init_shared_info",
      "external": true,
      "loc": "arch/x86/xen/enlighten_hvm.c:39",
      "file": "arch/x86/xen/enlighten_hvm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init"
      ],
      "caller_func": [
        "arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579081232,
      "name": "xen_hvm_init_shared_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void xen_hvm_init_shared_info()
```

```json
{
  "name": "xen_hvm_init_shared_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578971504,
      "name": "xen_hvm_init_shared_info",
      "external": true,
      "loc": "arch/x86/xen/enlighten_hvm.c:37",
      "file": "arch/x86/xen/enlighten_hvm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_map_shared_info",
        "arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578971504,
      "name": "xen_hvm_init_shared_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void xen_hvm_init_shared_info()
```

```json
{
  "name": "xen_hvm_init_shared_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578971136,
      "name": "xen_hvm_init_shared_info",
      "external": true,
      "loc": "arch/x86/xen/enlighten_hvm.c:30",
      "file": "arch/x86/xen/enlighten_hvm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578971136,
      "name": "xen_hvm_init_shared_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void xen_hvm_init_shared_info()
```

```json
{
  "name": "xen_hvm_init_shared_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578971728,
      "name": "xen_hvm_init_shared_info",
      "external": true,
      "loc": "arch/x86/xen/enlighten_hvm.c:30",
      "file": "arch/x86/xen/enlighten_hvm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578971728,
      "name": "xen_hvm_init_shared_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void xen_hvm_init_shared_info()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void xen_hvm_init_shared_info()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void xen_hvm_init_shared_info()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void xen_hvm_init_shared_info()
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
void xen_hvm_init_shared_info()
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
