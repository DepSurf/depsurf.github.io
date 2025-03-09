# Function: <code>cpu_smt_disable</code>

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
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void cpu_smt_disable(bool force)
```

```json
{
  "name": "cpu_smt_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071602909335,
      "name": "cpu_smt_disable",
      "external": true,
      "loc": "kernel/cpu.c:352",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "kernel/cpu.c:smt_cmdline_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602909335,
      "name": "cpu_smt_disable",
      "section": ".init.text",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void cpu_smt_disable(bool force)
```

```json
{
  "name": "cpu_smt_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604706967,
      "name": "cpu_smt_disable",
      "external": true,
      "loc": "kernel/cpu.c:380",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "kernel/cpu.c:smt_cmdline_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604706967,
      "name": "cpu_smt_disable",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void cpu_smt_disable(bool force)
```

```json
{
  "name": "cpu_smt_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604807298,
      "name": "cpu_smt_disable",
      "external": true,
      "loc": "kernel/cpu.c:390",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "kernel/cpu.c:smt_cmdline_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604807298,
      "name": "cpu_smt_disable",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void cpu_smt_disable(bool force)
```

```json
{
  "name": "cpu_smt_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604841601,
      "name": "cpu_smt_disable",
      "external": true,
      "loc": "kernel/cpu.c:393",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:mds_select_mitigation",
        "kernel/cpu.c:smt_cmdline_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604841601,
      "name": "cpu_smt_disable",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void cpu_smt_disable(bool force)
```

```json
{
  "name": "cpu_smt_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609176222,
      "name": "cpu_smt_disable",
      "external": true,
      "loc": "kernel/cpu.c:394",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:taa_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:mds_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation",
        "kernel/cpu.c:smt_cmdline_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609176222,
      "name": "cpu_smt_disable",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void cpu_smt_disable(bool force)
```

```json
{
  "name": "cpu_smt_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612241656,
      "name": "cpu_smt_disable",
      "external": true,
      "loc": "kernel/cpu.c:394",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:taa_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:mds_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation",
        "kernel/cpu.c:smt_cmdline_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612241656,
      "name": "cpu_smt_disable",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void cpu_smt_disable(bool force)
```

```json
{
  "name": "cpu_smt_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614382156,
      "name": "cpu_smt_disable",
      "external": true,
      "loc": "kernel/cpu.c:406",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:mds_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation",
        "kernel/cpu.c:smt_cmdline_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614382156,
      "name": "cpu_smt_disable",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void cpu_smt_disable(bool force)
```

```json
{
  "name": "cpu_smt_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615314985,
      "name": "cpu_smt_disable",
      "external": true,
      "loc": "kernel/cpu.c:417",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:mds_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation",
        "kernel/cpu.c:smt_cmdline_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615314985,
      "name": "cpu_smt_disable",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void cpu_smt_disable(bool force)
```

```json
{
  "name": "cpu_smt_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617096759,
      "name": "cpu_smt_disable",
      "external": true,
      "loc": "kernel/cpu.c:418",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:mmio_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:taa_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:mds_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:retbleed_select_mitigation",
        "kernel/cpu.c:smt_cmdline_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617096759,
      "name": "cpu_smt_disable",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void cpu_smt_disable(bool force)
```

```json
{
  "name": "cpu_smt_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071627756888,
      "name": "cpu_smt_disable",
      "external": true,
      "loc": "kernel/cpu.c:418",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:smt_cmdline_disable"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:mmio_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:taa_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:mds_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:retbleed_select_mitigation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627757424,
      "name": "cpu_smt_disable",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void cpu_smt_disable(bool force)
```

```json
{
  "name": "cpu_smt_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071619516712,
      "name": "cpu_smt_disable",
      "external": true,
      "loc": "kernel/cpu.c:597",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:smt_cmdline_disable"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:mmio_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:taa_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:mds_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:retbleed_select_mitigation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619517920,
      "name": "cpu_smt_disable",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void cpu_smt_disable(bool force)
```

```json
{
  "name": "cpu_smt_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071621813624,
      "name": "cpu_smt_disable",
      "external": true,
      "loc": "kernel/cpu.c:600",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:smt_cmdline_disable"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:mmio_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:taa_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:mds_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:retbleed_select_mitigation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071621814864,
      "name": "cpu_smt_disable",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 99
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
void cpu_smt_disable(bool force)
```

```json
{
  "name": "cpu_smt_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604746868,
      "name": "cpu_smt_disable",
      "external": true,
      "loc": "kernel/cpu.c:393",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:mds_select_mitigation",
        "kernel/cpu.c:smt_cmdline_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604746868,
      "name": "cpu_smt_disable",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void cpu_smt_disable(bool force)
```

```json
{
  "name": "cpu_smt_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604714485,
      "name": "cpu_smt_disable",
      "external": true,
      "loc": "kernel/cpu.c:393",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:mds_select_mitigation",
        "kernel/cpu.c:smt_cmdline_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604714485,
      "name": "cpu_smt_disable",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void cpu_smt_disable(bool force)
```

```json
{
  "name": "cpu_smt_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604824435,
      "name": "cpu_smt_disable",
      "external": true,
      "loc": "kernel/cpu.c:393",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:mds_select_mitigation",
        "kernel/cpu.c:smt_cmdline_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604824435,
      "name": "cpu_smt_disable",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void cpu_smt_disable(bool force)
```

```json
{
  "name": "cpu_smt_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604845758,
      "name": "cpu_smt_disable",
      "external": true,
      "loc": "kernel/cpu.c:393",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:mds_select_mitigation",
        "kernel/cpu.c:smt_cmdline_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604845758,
      "name": "cpu_smt_disable",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 77
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void cpu_smt_disable(bool force)
```
</details>
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
void cpu_smt_disable(bool force)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void cpu_smt_disable(bool force)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void cpu_smt_disable(bool force)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void cpu_smt_disable(bool force)
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
