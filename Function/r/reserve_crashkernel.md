# Function: <code>reserve_crashkernel</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "reserve_crashkernel",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594993460,
      "name": "reserve_crashkernel",
      "external": false,
      "loc": "arch/x86/kernel/setup.c:553",
      "file": "arch/x86/kernel/setup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/setup.c:setup_arch"
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
  "name": "reserve_crashkernel",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595156869,
      "name": "reserve_crashkernel",
      "external": false,
      "loc": "arch/x86/kernel/setup.c:556",
      "file": "arch/x86/kernel/setup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/setup.c:setup_arch"
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
  "name": "reserve_crashkernel",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595399453,
      "name": "reserve_crashkernel",
      "external": false,
      "loc": "arch/x86/kernel/setup.c:556",
      "file": "arch/x86/kernel/setup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/setup.c:setup_arch"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "reserve_crashkernel",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596318817,
      "name": "reserve_crashkernel",
      "external": false,
      "loc": "arch/x86/kernel/setup.c:537",
      "file": "arch/x86/kernel/setup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/setup.c:setup_arch"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "reserve_crashkernel",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602637621,
      "name": "reserve_crashkernel",
      "external": false,
      "loc": "arch/x86/kernel/setup.c:522",
      "file": "arch/x86/kernel/setup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/setup.c:setup_arch"
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
  "name": "reserve_crashkernel",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602807258,
      "name": "reserve_crashkernel",
      "external": false,
      "loc": "arch/x86/kernel/setup.c:520",
      "file": "arch/x86/kernel/setup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/setup.c:setup_arch"
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
  "name": "reserve_crashkernel",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604602303,
      "name": "reserve_crashkernel",
      "external": false,
      "loc": "arch/x86/kernel/setup.c:520",
      "file": "arch/x86/kernel/setup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/setup.c:setup_arch"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void reserve_crashkernel()
```

```json
{
  "name": "reserve_crashkernel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604695403,
      "name": "reserve_crashkernel",
      "external": false,
      "loc": "arch/x86/kernel/setup.c:530",
      "file": "arch/x86/kernel/setup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604695403,
      "name": "reserve_crashkernel",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 729
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
void reserve_crashkernel()
```

```json
{
  "name": "reserve_crashkernel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604707747,
      "name": "reserve_crashkernel",
      "external": false,
      "loc": "arch/x86/kernel/setup.c:530",
      "file": "arch/x86/kernel/setup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604707747,
      "name": "reserve_crashkernel",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 729
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
void reserve_crashkernel()
```

```json
{
  "name": "reserve_crashkernel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609054827,
      "name": "reserve_crashkernel",
      "external": false,
      "loc": "arch/x86/kernel/setup.c:482",
      "file": "arch/x86/kernel/setup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609054827,
      "name": "reserve_crashkernel",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 466
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
void reserve_crashkernel()
```

```json
{
  "name": "reserve_crashkernel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612118208,
      "name": "reserve_crashkernel",
      "external": false,
      "loc": "arch/x86/kernel/setup.c:465",
      "file": "arch/x86/kernel/setup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612118208,
      "name": "reserve_crashkernel",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 425
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
void reserve_crashkernel()
```

```json
{
  "name": "reserve_crashkernel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614257794,
      "name": "reserve_crashkernel",
      "external": false,
      "loc": "arch/x86/kernel/setup.c:465",
      "file": "arch/x86/kernel/setup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614257794,
      "name": "reserve_crashkernel",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 658
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
void reserve_crashkernel()
```

```json
{
  "name": "reserve_crashkernel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615179250,
      "name": "reserve_crashkernel",
      "external": false,
      "loc": "arch/x86/kernel/setup.c:487",
      "file": "arch/x86/kernel/setup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615179250,
      "name": "reserve_crashkernel",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 658
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
void reserve_crashkernel()
```

```json
{
  "name": "reserve_crashkernel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071616945249,
      "name": "reserve_crashkernel",
      "external": false,
      "loc": "arch/x86/kernel/setup.c:481",
      "file": "arch/x86/kernel/setup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071616945249,
      "name": "reserve_crashkernel",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 708
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
void reserve_crashkernel()
```

```json
{
  "name": "reserve_crashkernel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071627554256,
      "name": "reserve_crashkernel",
      "external": false,
      "loc": "arch/x86/kernel/setup.c:556",
      "file": "arch/x86/kernel/setup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627554256,
      "name": "reserve_crashkernel",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 752
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
void reserve_crashkernel()
```

```json
{
  "name": "reserve_crashkernel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619303584,
      "name": "reserve_crashkernel",
      "external": false,
      "loc": "arch/x86/kernel/setup.c:550",
      "file": "arch/x86/kernel/setup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619303584,
      "name": "reserve_crashkernel",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 752
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "reserve_crashkernel",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336510829956,
      "name": "reserve_crashkernel",
      "external": false,
      "loc": "arch/arm64/mm/init.c:69",
      "file": "arch/arm64/mm/init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/arm64/mm/init.c:arm64_memblock_init"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "reserve_crashkernel",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3243265624,
      "name": "reserve_crashkernel",
      "external": false,
      "loc": "arch/arm/kernel/setup.c:988",
      "file": "arch/arm/kernel/setup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/arm/kernel/setup.c:setup_arch"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void reserve_crashkernel()
```

```json
{
  "name": "reserve_crashkernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055302425792,
      "name": "reserve_crashkernel",
      "external": true,
      "loc": "arch/powerpc/kernel/machine_kexec.c:115",
      "file": "arch/powerpc/kernel/machine_kexec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/prom.c:early_init_devtree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055302425792,
      "name": "reserve_crashkernel",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 608
    }
  ]
}
```
</details>
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
void reserve_crashkernel()
```

```json
{
  "name": "reserve_crashkernel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604634035,
      "name": "reserve_crashkernel",
      "external": false,
      "loc": "arch/x86/kernel/setup.c:530",
      "file": "arch/x86/kernel/setup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604634035,
      "name": "reserve_crashkernel",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 729
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void reserve_crashkernel()
```

```json
{
  "name": "reserve_crashkernel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604602077,
      "name": "reserve_crashkernel",
      "external": false,
      "loc": "arch/x86/kernel/setup.c:530",
      "file": "arch/x86/kernel/setup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604602077,
      "name": "reserve_crashkernel",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 703
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void reserve_crashkernel()
```

```json
{
  "name": "reserve_crashkernel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604711843,
      "name": "reserve_crashkernel",
      "external": false,
      "loc": "arch/x86/kernel/setup.c:530",
      "file": "arch/x86/kernel/setup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604711843,
      "name": "reserve_crashkernel",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 729
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
void reserve_crashkernel()
```

```json
{
  "name": "reserve_crashkernel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604711859,
      "name": "reserve_crashkernel",
      "external": false,
      "loc": "arch/x86/kernel/setup.c:530",
      "file": "arch/x86/kernel/setup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604711859,
      "name": "reserve_crashkernel",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 729
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
void reserve_crashkernel()
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
void reserve_crashkernel()
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
void reserve_crashkernel()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void reserve_crashkernel()
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void reserve_crashkernel()
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
