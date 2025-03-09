# Function: <code>__xen_send_IPI_mask</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __xen_send_IPI_mask(const struct cpumask * mask, int vector)
```

```json
{
  "name": "__xen_send_IPI_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579020736,
      "name": "__xen_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/xen/smp.c:591",
      "file": "arch/x86/xen/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_smp_send_call_function_single_ipi",
        "arch/x86/xen/smp.c:xen_send_IPI_mask",
        "arch/x86/xen/smp.c:xen_send_IPI_mask",
        "arch/x86/xen/smp.c:xen_send_IPI_mask",
        "arch/x86/xen/smp.c:xen_send_IPI_mask",
        "arch/x86/xen/smp.c:xen_send_IPI_all",
        "arch/x86/xen/smp.c:xen_send_IPI_all",
        "arch/x86/xen/smp.c:xen_send_IPI_all",
        "arch/x86/xen/smp.c:xen_send_IPI_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579020736,
      "name": "__xen_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
void __xen_send_IPI_mask(const struct cpumask * mask, int vector)
```

```json
{
  "name": "__xen_send_IPI_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579017440,
      "name": "__xen_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/xen/smp.c:601",
      "file": "arch/x86/xen/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_send_IPI_all",
        "arch/x86/xen/smp.c:xen_send_IPI_all",
        "arch/x86/xen/smp.c:xen_send_IPI_all",
        "arch/x86/xen/smp.c:xen_send_IPI_all",
        "arch/x86/xen/smp.c:xen_send_IPI_mask",
        "arch/x86/xen/smp.c:xen_send_IPI_mask",
        "arch/x86/xen/smp.c:xen_send_IPI_mask",
        "arch/x86/xen/smp.c:xen_send_IPI_mask",
        "arch/x86/xen/smp.c:xen_smp_send_call_function_single_ipi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579017440,
      "name": "__xen_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
void __xen_send_IPI_mask(const struct cpumask * mask, int vector)
```

```json
{
  "name": "__xen_send_IPI_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579019312,
      "name": "__xen_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/xen/smp.c:595",
      "file": "arch/x86/xen/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_send_IPI_all",
        "arch/x86/xen/smp.c:xen_send_IPI_all",
        "arch/x86/xen/smp.c:xen_send_IPI_all",
        "arch/x86/xen/smp.c:xen_send_IPI_all",
        "arch/x86/xen/smp.c:xen_send_IPI_mask",
        "arch/x86/xen/smp.c:xen_send_IPI_mask",
        "arch/x86/xen/smp.c:xen_send_IPI_mask",
        "arch/x86/xen/smp.c:xen_send_IPI_mask",
        "arch/x86/xen/smp.c:xen_smp_send_call_function_single_ipi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579019312,
      "name": "__xen_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
void __xen_send_IPI_mask(const struct cpumask * mask, int vector)
```

```json
{
  "name": "__xen_send_IPI_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579011744,
      "name": "__xen_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/xen/smp.c:153",
      "file": "arch/x86/xen/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_send_IPI_all",
        "arch/x86/xen/smp.c:xen_send_IPI_mask",
        "arch/x86/xen/smp.c:xen_smp_send_call_function_single_ipi",
        "arch/x86/xen/smp.c:xen_smp_send_call_function_ipi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579011744,
      "name": "__xen_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
void __xen_send_IPI_mask(const struct cpumask * mask, int vector)
```

```json
{
  "name": "__xen_send_IPI_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579012272,
      "name": "__xen_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/xen/smp.c:156",
      "file": "arch/x86/xen/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_send_IPI_all",
        "arch/x86/xen/smp.c:xen_send_IPI_mask",
        "arch/x86/xen/smp.c:xen_smp_send_call_function_single_ipi",
        "arch/x86/xen/smp.c:xen_smp_send_call_function_ipi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579012272,
      "name": "__xen_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
void __xen_send_IPI_mask(const struct cpumask * mask, int vector)
```

```json
{
  "name": "__xen_send_IPI_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579014912,
      "name": "__xen_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/xen/smp.c:156",
      "file": "arch/x86/xen/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_send_IPI_all",
        "arch/x86/xen/smp.c:xen_send_IPI_mask",
        "arch/x86/xen/smp.c:xen_smp_send_call_function_single_ipi",
        "arch/x86/xen/smp.c:xen_smp_send_call_function_ipi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579014912,
      "name": "__xen_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
void __xen_send_IPI_mask(const struct cpumask * mask, int vector)
```

```json
{
  "name": "__xen_send_IPI_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579016416,
      "name": "__xen_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/xen/smp.c:156",
      "file": "arch/x86/xen/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_send_IPI_all",
        "arch/x86/xen/smp.c:xen_send_IPI_mask",
        "arch/x86/xen/smp.c:xen_smp_send_call_function_single_ipi",
        "arch/x86/xen/smp.c:xen_smp_send_call_function_ipi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579016416,
      "name": "__xen_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
void __xen_send_IPI_mask(const struct cpumask * mask, int vector)
```

```json
{
  "name": "__xen_send_IPI_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579024032,
      "name": "__xen_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/xen/smp.c:156",
      "file": "arch/x86/xen/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_send_IPI_all",
        "arch/x86/xen/smp.c:xen_send_IPI_mask",
        "arch/x86/xen/smp.c:xen_smp_send_call_function_single_ipi",
        "arch/x86/xen/smp.c:xen_smp_send_call_function_ipi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579024032,
      "name": "__xen_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
void __xen_send_IPI_mask(const struct cpumask * mask, int vector)
```

```json
{
  "name": "__xen_send_IPI_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579026336,
      "name": "__xen_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/xen/smp.c:156",
      "file": "arch/x86/xen/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_send_IPI_all",
        "arch/x86/xen/smp.c:xen_send_IPI_mask",
        "arch/x86/xen/smp.c:xen_smp_send_call_function_single_ipi",
        "arch/x86/xen/smp.c:xen_smp_send_call_function_ipi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579026336,
      "name": "__xen_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__xen_send_IPI_mask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579035851,
      "name": "__xen_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/xen/smp.c:156",
      "file": "arch/x86/xen/smp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp.c:xen_send_IPI_all",
        "arch/x86/xen/smp.c:xen_send_IPI_mask",
        "arch/x86/xen/smp.c:xen_smp_send_call_function_single_ipi",
        "arch/x86/xen/smp.c:xen_smp_send_call_function_ipi"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__xen_send_IPI_mask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579039531,
      "name": "__xen_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/xen/smp.c:159",
      "file": "arch/x86/xen/smp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp.c:xen_send_IPI_all",
        "arch/x86/xen/smp.c:xen_send_IPI_mask",
        "arch/x86/xen/smp.c:xen_smp_send_call_function_single_ipi",
        "arch/x86/xen/smp.c:xen_smp_send_call_function_ipi"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__xen_send_IPI_mask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579042379,
      "name": "__xen_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/xen/smp.c:159",
      "file": "arch/x86/xen/smp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp.c:xen_send_IPI_all",
        "arch/x86/xen/smp.c:xen_send_IPI_mask",
        "arch/x86/xen/smp.c:xen_smp_send_call_function_single_ipi",
        "arch/x86/xen/smp.c:xen_smp_send_call_function_ipi"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__xen_send_IPI_mask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579062411,
      "name": "__xen_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/xen/smp.c:159",
      "file": "arch/x86/xen/smp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp.c:xen_send_IPI_all",
        "arch/x86/xen/smp.c:xen_send_IPI_mask",
        "arch/x86/xen/smp.c:xen_smp_send_call_function_single_ipi",
        "arch/x86/xen/smp.c:xen_smp_send_call_function_ipi"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__xen_send_IPI_mask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579086320,
      "name": "__xen_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/xen/smp.c:135",
      "file": "arch/x86/xen/smp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp.c:xen_send_IPI_all",
        "arch/x86/xen/smp.c:xen_send_IPI_mask",
        "arch/x86/xen/smp.c:xen_smp_send_call_function_single_ipi",
        "arch/x86/xen/smp.c:xen_smp_send_call_function_ipi"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void __xen_send_IPI_mask(const struct cpumask * mask, int vector)
```

```json
{
  "name": "__xen_send_IPI_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579118192,
      "name": "__xen_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/xen/smp.c:135",
      "file": "arch/x86/xen/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_send_IPI_all",
        "arch/x86/xen/smp.c:xen_send_IPI_mask",
        "arch/x86/xen/smp.c:xen_smp_send_call_function_single_ipi",
        "arch/x86/xen/smp.c:xen_smp_send_call_function_ipi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579118192,
      "name": "__xen_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
void __xen_send_IPI_mask(const struct cpumask * mask, int vector)
```

```json
{
  "name": "__xen_send_IPI_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579118704,
      "name": "__xen_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/xen/smp.c:135",
      "file": "arch/x86/xen/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_send_IPI_all",
        "arch/x86/xen/smp.c:xen_send_IPI_all",
        "arch/x86/xen/smp.c:xen_send_IPI_mask",
        "arch/x86/xen/smp.c:xen_send_IPI_mask",
        "arch/x86/xen/smp.c:xen_smp_send_call_function_single_ipi",
        "arch/x86/xen/smp.c:xen_smp_send_call_function_ipi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579118704,
      "name": "__xen_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
void __xen_send_IPI_mask(const struct cpumask * mask, int vector)
```

```json
{
  "name": "__xen_send_IPI_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579144512,
      "name": "__xen_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/xen/smp.c:147",
      "file": "arch/x86/xen/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_send_IPI_all",
        "arch/x86/xen/smp.c:xen_send_IPI_all",
        "arch/x86/xen/smp.c:xen_send_IPI_mask",
        "arch/x86/xen/smp.c:xen_send_IPI_mask",
        "arch/x86/xen/smp.c:xen_smp_send_call_function_single_ipi",
        "arch/x86/xen/smp.c:xen_smp_send_call_function_ipi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579144512,
      "name": "__xen_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
void __xen_send_IPI_mask(const struct cpumask * mask, int vector)
```

```json
{
  "name": "__xen_send_IPI_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579026688,
      "name": "__xen_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/xen/smp.c:156",
      "file": "arch/x86/xen/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_send_IPI_all",
        "arch/x86/xen/smp.c:xen_send_IPI_mask",
        "arch/x86/xen/smp.c:xen_smp_send_call_function_single_ipi",
        "arch/x86/xen/smp.c:xen_smp_send_call_function_ipi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579026688,
      "name": "__xen_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
void __xen_send_IPI_mask(const struct cpumask * mask, int vector)
```

```json
{
  "name": "__xen_send_IPI_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579026272,
      "name": "__xen_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/xen/smp.c:156",
      "file": "arch/x86/xen/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_send_IPI_all",
        "arch/x86/xen/smp.c:xen_send_IPI_mask",
        "arch/x86/xen/smp.c:xen_smp_send_call_function_single_ipi",
        "arch/x86/xen/smp.c:xen_smp_send_call_function_ipi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579026272,
      "name": "__xen_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
void __xen_send_IPI_mask(const struct cpumask * mask, int vector)
```

```json
{
  "name": "__xen_send_IPI_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579029840,
      "name": "__xen_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/xen/smp.c:156",
      "file": "arch/x86/xen/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_send_IPI_all",
        "arch/x86/xen/smp.c:xen_send_IPI_mask",
        "arch/x86/xen/smp.c:xen_smp_send_call_function_single_ipi",
        "arch/x86/xen/smp.c:xen_smp_send_call_function_ipi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579029840,
      "name": "__xen_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void __xen_send_IPI_mask(const struct cpumask * mask, int vector)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
void __xen_send_IPI_mask(const struct cpumask * mask, int vector)
```
</details>
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
void __xen_send_IPI_mask(const struct cpumask * mask, int vector)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void __xen_send_IPI_mask(const struct cpumask * mask, int vector)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void __xen_send_IPI_mask(const struct cpumask * mask, int vector)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void __xen_send_IPI_mask(const struct cpumask * mask, int vector)
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
void __xen_send_IPI_mask(const struct cpumask * mask, int vector)
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
