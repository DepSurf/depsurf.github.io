# Function: <code>xen_hvm_post_suspend</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xen_hvm_post_suspend",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578993049,
      "name": "xen_hvm_post_suspend",
      "external": false,
      "loc": "arch/x86/xen/suspend.c:33",
      "file": "arch/x86/xen/suspend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend.c:xen_arch_post_suspend"
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
  "name": "xen_hvm_post_suspend",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578989657,
      "name": "xen_hvm_post_suspend",
      "external": false,
      "loc": "arch/x86/xen/suspend.c:33",
      "file": "arch/x86/xen/suspend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend.c:xen_arch_post_suspend"
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
  "name": "xen_hvm_post_suspend",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578991529,
      "name": "xen_hvm_post_suspend",
      "external": false,
      "loc": "arch/x86/xen/suspend.c:33",
      "file": "arch/x86/xen/suspend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend.c:xen_arch_post_suspend"
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
void xen_hvm_post_suspend(int suspend_cancelled)
```

```json
{
  "name": "xen_hvm_post_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578958784,
      "name": "xen_hvm_post_suspend",
      "external": true,
      "loc": "arch/x86/xen/suspend_hvm.c:9",
      "file": "arch/x86/xen/suspend_hvm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_post_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578958784,
      "name": "xen_hvm_post_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void xen_hvm_post_suspend(int suspend_cancelled)
```

```json
{
  "name": "xen_hvm_post_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578962096,
      "name": "xen_hvm_post_suspend",
      "external": true,
      "loc": "arch/x86/xen/suspend_hvm.c:10",
      "file": "arch/x86/xen/suspend_hvm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_post_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578962096,
      "name": "xen_hvm_post_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void xen_hvm_post_suspend(int suspend_cancelled)
```

```json
{
  "name": "xen_hvm_post_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578964688,
      "name": "xen_hvm_post_suspend",
      "external": true,
      "loc": "arch/x86/xen/suspend_hvm.c:10",
      "file": "arch/x86/xen/suspend_hvm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_post_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578964688,
      "name": "xen_hvm_post_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void xen_hvm_post_suspend(int suspend_cancelled)
```

```json
{
  "name": "xen_hvm_post_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578962352,
      "name": "xen_hvm_post_suspend",
      "external": true,
      "loc": "arch/x86/xen/suspend_hvm.c:10",
      "file": "arch/x86/xen/suspend_hvm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_post_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578962352,
      "name": "xen_hvm_post_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void xen_hvm_post_suspend(int suspend_cancelled)
```

```json
{
  "name": "xen_hvm_post_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578969296,
      "name": "xen_hvm_post_suspend",
      "external": true,
      "loc": "arch/x86/xen/suspend_hvm.c:10",
      "file": "arch/x86/xen/suspend_hvm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_post_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578969296,
      "name": "xen_hvm_post_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void xen_hvm_post_suspend(int suspend_cancelled)
```

```json
{
  "name": "xen_hvm_post_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578971728,
      "name": "xen_hvm_post_suspend",
      "external": true,
      "loc": "arch/x86/xen/suspend_hvm.c:10",
      "file": "arch/x86/xen/suspend_hvm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_post_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578971728,
      "name": "xen_hvm_post_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void xen_hvm_post_suspend(int suspend_cancelled)
```

```json
{
  "name": "xen_hvm_post_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578981376,
      "name": "xen_hvm_post_suspend",
      "external": true,
      "loc": "arch/x86/xen/suspend_hvm.c:11",
      "file": "arch/x86/xen/suspend_hvm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_post_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578981376,
      "name": "xen_hvm_post_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void xen_hvm_post_suspend(int suspend_cancelled)
```

```json
{
  "name": "xen_hvm_post_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578983360,
      "name": "xen_hvm_post_suspend",
      "external": true,
      "loc": "arch/x86/xen/suspend_hvm.c:11",
      "file": "arch/x86/xen/suspend_hvm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_post_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578983360,
      "name": "xen_hvm_post_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void xen_hvm_post_suspend(int suspend_cancelled)
```

```json
{
  "name": "xen_hvm_post_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578992464,
      "name": "xen_hvm_post_suspend",
      "external": true,
      "loc": "arch/x86/xen/suspend_hvm.c:11",
      "file": "arch/x86/xen/suspend_hvm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_post_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578992464,
      "name": "xen_hvm_post_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void xen_hvm_post_suspend(int suspend_cancelled)
```

```json
{
  "name": "xen_hvm_post_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579009712,
      "name": "xen_hvm_post_suspend",
      "external": true,
      "loc": "arch/x86/xen/suspend_hvm.c:11",
      "file": "arch/x86/xen/suspend_hvm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_post_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579009712,
      "name": "xen_hvm_post_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void xen_hvm_post_suspend(int suspend_cancelled)
```

```json
{
  "name": "xen_hvm_post_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579027600,
      "name": "xen_hvm_post_suspend",
      "external": true,
      "loc": "arch/x86/xen/suspend_hvm.c:11",
      "file": "arch/x86/xen/suspend_hvm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_post_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579027600,
      "name": "xen_hvm_post_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void xen_hvm_post_suspend(int suspend_cancelled)
```

```json
{
  "name": "xen_hvm_post_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_hvm_post_suspend",
      "external": true,
      "loc": "arch/x86/xen/suspend_hvm.c:12",
      "file": "arch/x86/xen/suspend_hvm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_post_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595956410,
      "name": "xen_hvm_post_suspend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071579056496,
      "name": "xen_hvm_post_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void xen_hvm_post_suspend(int suspend_cancelled)
```

```json
{
  "name": "xen_hvm_post_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_hvm_post_suspend",
      "external": true,
      "loc": "arch/x86/xen/suspend_hvm.c:12",
      "file": "arch/x86/xen/suspend_hvm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_post_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596473766,
      "name": "xen_hvm_post_suspend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071579056384,
      "name": "xen_hvm_post_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void xen_hvm_post_suspend(int suspend_cancelled)
```

```json
{
  "name": "xen_hvm_post_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_hvm_post_suspend",
      "external": true,
      "loc": "arch/x86/xen/suspend_hvm.c:12",
      "file": "arch/x86/xen/suspend_hvm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_post_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597369108,
      "name": "xen_hvm_post_suspend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071579081728,
      "name": "xen_hvm_post_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
void xen_hvm_post_suspend(int suspend_cancelled)
```

```json
{
  "name": "xen_hvm_post_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578972080,
      "name": "xen_hvm_post_suspend",
      "external": true,
      "loc": "arch/x86/xen/suspend_hvm.c:10",
      "file": "arch/x86/xen/suspend_hvm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_post_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578972080,
      "name": "xen_hvm_post_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void xen_hvm_post_suspend(int suspend_cancelled)
```

```json
{
  "name": "xen_hvm_post_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578971664,
      "name": "xen_hvm_post_suspend",
      "external": true,
      "loc": "arch/x86/xen/suspend_hvm.c:10",
      "file": "arch/x86/xen/suspend_hvm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_post_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578971664,
      "name": "xen_hvm_post_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void xen_hvm_post_suspend(int suspend_cancelled)
```

```json
{
  "name": "xen_hvm_post_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578972256,
      "name": "xen_hvm_post_suspend",
      "external": true,
      "loc": "arch/x86/xen/suspend_hvm.c:10",
      "file": "arch/x86/xen/suspend_hvm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_post_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578972256,
      "name": "xen_hvm_post_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void xen_hvm_post_suspend(int suspend_cancelled)
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
void xen_hvm_post_suspend(int suspend_cancelled)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void xen_hvm_post_suspend(int suspend_cancelled)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void xen_hvm_post_suspend(int suspend_cancelled)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void xen_hvm_post_suspend(int suspend_cancelled)
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
void xen_hvm_post_suspend(int suspend_cancelled)
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
