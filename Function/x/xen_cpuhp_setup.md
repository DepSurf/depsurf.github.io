# Function: <code>xen_cpuhp_setup</code>

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
int xen_cpuhp_setup()
```

```json
{
  "name": "xen_cpuhp_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579380086,
      "name": "xen_cpuhp_setup",
      "external": false,
      "loc": "arch/x86/xen/enlighten.c:1527",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_start_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579380086,
      "name": "xen_cpuhp_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
int xen_cpuhp_setup(int (*)(unsigned int) cpu_up_prepare_cb, int (*)(unsigned int) cpu_dead_cb)
```

```json
{
  "name": "xen_cpuhp_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578949728,
      "name": "xen_cpuhp_setup",
      "external": true,
      "loc": "arch/x86/xen/enlighten.c:90",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578949728,
      "name": "xen_cpuhp_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
int xen_cpuhp_setup(int (*)(unsigned int) cpu_up_prepare_cb, int (*)(unsigned int) cpu_dead_cb)
```

```json
{
  "name": "xen_cpuhp_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578952000,
      "name": "xen_cpuhp_setup",
      "external": true,
      "loc": "arch/x86/xen/enlighten.c:94",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578952000,
      "name": "xen_cpuhp_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
int xen_cpuhp_setup(int (*)(unsigned int) cpu_up_prepare_cb, int (*)(unsigned int) cpu_dead_cb)
```

```json
{
  "name": "xen_cpuhp_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578954528,
      "name": "xen_cpuhp_setup",
      "external": true,
      "loc": "arch/x86/xen/enlighten.c:102",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578954528,
      "name": "xen_cpuhp_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
int xen_cpuhp_setup(int (*)(unsigned int) cpu_up_prepare_cb, int (*)(unsigned int) cpu_dead_cb)
```

```json
{
  "name": "xen_cpuhp_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578956528,
      "name": "xen_cpuhp_setup",
      "external": true,
      "loc": "arch/x86/xen/enlighten.c:104",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578956528,
      "name": "xen_cpuhp_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
int xen_cpuhp_setup(int (*)(unsigned int) cpu_up_prepare_cb, int (*)(unsigned int) cpu_dead_cb)
```

```json
{
  "name": "xen_cpuhp_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578963472,
      "name": "xen_cpuhp_setup",
      "external": true,
      "loc": "arch/x86/xen/enlighten.c:104",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578963472,
      "name": "xen_cpuhp_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
int xen_cpuhp_setup(int (*)(unsigned int) cpu_up_prepare_cb, int (*)(unsigned int) cpu_dead_cb)
```

```json
{
  "name": "xen_cpuhp_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578965904,
      "name": "xen_cpuhp_setup",
      "external": true,
      "loc": "arch/x86/xen/enlighten.c:104",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578965904,
      "name": "xen_cpuhp_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
int xen_cpuhp_setup(int (*)(unsigned int) cpu_up_prepare_cb, int (*)(unsigned int) cpu_dead_cb)
```

```json
{
  "name": "xen_cpuhp_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578975232,
      "name": "xen_cpuhp_setup",
      "external": true,
      "loc": "arch/x86/xen/enlighten.c:104",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578975232,
      "name": "xen_cpuhp_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
int xen_cpuhp_setup(int (*)(unsigned int) cpu_up_prepare_cb, int (*)(unsigned int) cpu_dead_cb)
```

```json
{
  "name": "xen_cpuhp_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578977952,
      "name": "xen_cpuhp_setup",
      "external": true,
      "loc": "arch/x86/xen/enlighten.c:104",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578977952,
      "name": "xen_cpuhp_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
int xen_cpuhp_setup(int (*)(unsigned int) cpu_up_prepare_cb, int (*)(unsigned int) cpu_dead_cb)
```

```json
{
  "name": "xen_cpuhp_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578987072,
      "name": "xen_cpuhp_setup",
      "external": true,
      "loc": "arch/x86/xen/enlighten.c:104",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578987072,
      "name": "xen_cpuhp_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
int xen_cpuhp_setup(int (*)(unsigned int) cpu_up_prepare_cb, int (*)(unsigned int) cpu_dead_cb)
```

```json
{
  "name": "xen_cpuhp_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579003104,
      "name": "xen_cpuhp_setup",
      "external": true,
      "loc": "arch/x86/xen/enlighten.c:108",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579003104,
      "name": "xen_cpuhp_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
int xen_cpuhp_setup(int (*)(unsigned int) cpu_up_prepare_cb, int (*)(unsigned int) cpu_dead_cb)
```

```json
{
  "name": "xen_cpuhp_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579019904,
      "name": "xen_cpuhp_setup",
      "external": true,
      "loc": "arch/x86/xen/enlighten.c:78",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579019904,
      "name": "xen_cpuhp_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
int xen_cpuhp_setup(int (*)(unsigned int) cpu_up_prepare_cb, int (*)(unsigned int) cpu_dead_cb)
```

```json
{
  "name": "xen_cpuhp_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579047584,
      "name": "xen_cpuhp_setup",
      "external": true,
      "loc": "arch/x86/xen/enlighten.c:78",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579047584,
      "name": "xen_cpuhp_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
int xen_cpuhp_setup(int (*)(unsigned int) cpu_up_prepare_cb, int (*)(unsigned int) cpu_dead_cb)
```

```json
{
  "name": "xen_cpuhp_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579047584,
      "name": "xen_cpuhp_setup",
      "external": true,
      "loc": "arch/x86/xen/enlighten.c:78",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579047584,
      "name": "xen_cpuhp_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
int xen_cpuhp_setup(int (*)(unsigned int) cpu_up_prepare_cb, int (*)(unsigned int) cpu_dead_cb)
```

```json
{
  "name": "xen_cpuhp_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579072912,
      "name": "xen_cpuhp_setup",
      "external": true,
      "loc": "arch/x86/xen/enlighten.c:81",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579072912,
      "name": "xen_cpuhp_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
int xen_cpuhp_setup(int (*)(unsigned int) cpu_up_prepare_cb, int (*)(unsigned int) cpu_dead_cb)
```

```json
{
  "name": "xen_cpuhp_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578965904,
      "name": "xen_cpuhp_setup",
      "external": true,
      "loc": "arch/x86/xen/enlighten.c:104",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578965904,
      "name": "xen_cpuhp_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
int xen_cpuhp_setup(int (*)(unsigned int) cpu_up_prepare_cb, int (*)(unsigned int) cpu_dead_cb)
```

```json
{
  "name": "xen_cpuhp_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578965840,
      "name": "xen_cpuhp_setup",
      "external": true,
      "loc": "arch/x86/xen/enlighten.c:104",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578965840,
      "name": "xen_cpuhp_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
int xen_cpuhp_setup(int (*)(unsigned int) cpu_up_prepare_cb, int (*)(unsigned int) cpu_dead_cb)
```

```json
{
  "name": "xen_cpuhp_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578966432,
      "name": "xen_cpuhp_setup",
      "external": true,
      "loc": "arch/x86/xen/enlighten.c:104",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578966432,
      "name": "xen_cpuhp_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
int xen_cpuhp_setup()
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int (*)(unsigned int) cpu_up_prepare_cb</code>
</li>
<li>
<b>Param added. </b>
<code>int (*)(unsigned int) cpu_dead_cb</code>
</li>
</ul>
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
int xen_cpuhp_setup(int (*)(unsigned int) cpu_up_prepare_cb, int (*)(unsigned int) cpu_dead_cb)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int xen_cpuhp_setup(int (*)(unsigned int) cpu_up_prepare_cb, int (*)(unsigned int) cpu_dead_cb)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int xen_cpuhp_setup(int (*)(unsigned int) cpu_up_prepare_cb, int (*)(unsigned int) cpu_dead_cb)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int xen_cpuhp_setup(int (*)(unsigned int) cpu_up_prepare_cb, int (*)(unsigned int) cpu_dead_cb)
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
int xen_cpuhp_setup(int (*)(unsigned int) cpu_up_prepare_cb, int (*)(unsigned int) cpu_dead_cb)
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
