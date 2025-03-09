# Function: <code>xen_pv_pre_suspend</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xen_pv_pre_suspend",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578992314,
      "name": "xen_pv_pre_suspend",
      "external": false,
      "loc": "arch/x86/xen/suspend.c:17",
      "file": "arch/x86/xen/suspend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend.c:xen_arch_pre_suspend"
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
  "name": "xen_pv_pre_suspend",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578988890,
      "name": "xen_pv_pre_suspend",
      "external": false,
      "loc": "arch/x86/xen/suspend.c:17",
      "file": "arch/x86/xen/suspend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend.c:xen_arch_pre_suspend"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xen_pv_pre_suspend",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578990762,
      "name": "xen_pv_pre_suspend",
      "external": false,
      "loc": "arch/x86/xen/suspend.c:17",
      "file": "arch/x86/xen/suspend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend.c:xen_arch_pre_suspend"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void xen_pv_pre_suspend()
```

```json
{
  "name": "xen_pv_pre_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578963376,
      "name": "xen_pv_pre_suspend",
      "external": true,
      "loc": "arch/x86/xen/suspend_pv.c:10",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_pre_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578963376,
      "name": "xen_pv_pre_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 667
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
void xen_pv_pre_suspend()
```

```json
{
  "name": "xen_pv_pre_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578966624,
      "name": "xen_pv_pre_suspend",
      "external": true,
      "loc": "arch/x86/xen/suspend_pv.c:11",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_pre_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578966624,
      "name": "xen_pv_pre_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 690
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
void xen_pv_pre_suspend()
```

```json
{
  "name": "xen_pv_pre_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578969280,
      "name": "xen_pv_pre_suspend",
      "external": true,
      "loc": "arch/x86/xen/suspend_pv.c:11",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_pre_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578969280,
      "name": "xen_pv_pre_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 661
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
void xen_pv_pre_suspend()
```

```json
{
  "name": "xen_pv_pre_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578967376,
      "name": "xen_pv_pre_suspend",
      "external": true,
      "loc": "arch/x86/xen/suspend_pv.c:11",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_pre_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578967376,
      "name": "xen_pv_pre_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 632
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void xen_pv_pre_suspend()
```

```json
{
  "name": "xen_pv_pre_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578974448,
      "name": "xen_pv_pre_suspend",
      "external": true,
      "loc": "arch/x86/xen/suspend_pv.c:11",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_pre_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578974448,
      "name": "xen_pv_pre_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 622
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void xen_pv_pre_suspend()
```

```json
{
  "name": "xen_pv_pre_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578976848,
      "name": "xen_pv_pre_suspend",
      "external": true,
      "loc": "arch/x86/xen/suspend_pv.c:11",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_pre_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578976848,
      "name": "xen_pv_pre_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 622
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
void xen_pv_pre_suspend()
```

```json
{
  "name": "xen_pv_pre_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578986656,
      "name": "xen_pv_pre_suspend",
      "external": true,
      "loc": "arch/x86/xen/suspend_pv.c:11",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_pre_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578986656,
      "name": "xen_pv_pre_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 625
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
void xen_pv_pre_suspend()
```

```json
{
  "name": "xen_pv_pre_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578988144,
      "name": "xen_pv_pre_suspend",
      "external": true,
      "loc": "arch/x86/xen/suspend_pv.c:11",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_pre_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578988144,
      "name": "xen_pv_pre_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 625
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void xen_pv_pre_suspend()
```

```json
{
  "name": "xen_pv_pre_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578997136,
      "name": "xen_pv_pre_suspend",
      "external": true,
      "loc": "arch/x86/xen/suspend_pv.c:11",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_pre_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578997136,
      "name": "xen_pv_pre_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 622
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
void xen_pv_pre_suspend()
```

```json
{
  "name": "xen_pv_pre_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579014816,
      "name": "xen_pv_pre_suspend",
      "external": true,
      "loc": "arch/x86/xen/suspend_pv.c:11",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_pre_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579014816,
      "name": "xen_pv_pre_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 622
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
void xen_pv_pre_suspend()
```

```json
{
  "name": "xen_pv_pre_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579033920,
      "name": "xen_pv_pre_suspend",
      "external": true,
      "loc": "arch/x86/xen/suspend_pv.c:11",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_pre_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579033920,
      "name": "xen_pv_pre_suspend",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void xen_pv_pre_suspend()
```

```json
{
  "name": "xen_pv_pre_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579063632,
      "name": "xen_pv_pre_suspend",
      "external": true,
      "loc": "arch/x86/xen/suspend_pv.c:11",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_pre_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579063632,
      "name": "xen_pv_pre_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
void xen_pv_pre_suspend()
```

```json
{
  "name": "xen_pv_pre_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579063504,
      "name": "xen_pv_pre_suspend",
      "external": true,
      "loc": "arch/x86/xen/suspend_pv.c:11",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_pre_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579063504,
      "name": "xen_pv_pre_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
void xen_pv_pre_suspend()
```

```json
{
  "name": "xen_pv_pre_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579088592,
      "name": "xen_pv_pre_suspend",
      "external": true,
      "loc": "arch/x86/xen/suspend_pv.c:11",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_pre_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579088592,
      "name": "xen_pv_pre_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void xen_pv_pre_suspend()
```

```json
{
  "name": "xen_pv_pre_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578977200,
      "name": "xen_pv_pre_suspend",
      "external": true,
      "loc": "arch/x86/xen/suspend_pv.c:11",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_pre_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578977200,
      "name": "xen_pv_pre_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 622
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void xen_pv_pre_suspend()
```

```json
{
  "name": "xen_pv_pre_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578976784,
      "name": "xen_pv_pre_suspend",
      "external": true,
      "loc": "arch/x86/xen/suspend_pv.c:11",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_pre_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578976784,
      "name": "xen_pv_pre_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 622
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void xen_pv_pre_suspend()
```

```json
{
  "name": "xen_pv_pre_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578977376,
      "name": "xen_pv_pre_suspend",
      "external": true,
      "loc": "arch/x86/xen/suspend_pv.c:11",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_pre_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578977376,
      "name": "xen_pv_pre_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 622
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
void xen_pv_pre_suspend()
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
void xen_pv_pre_suspend()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void xen_pv_pre_suspend()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void xen_pv_pre_suspend()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void xen_pv_pre_suspend()
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
void xen_pv_pre_suspend()
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
