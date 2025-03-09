# Function: <code>cpu_mitigations_auto_nosmt</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpu_mitigations_auto_nosmt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604718345,
      "name": "cpu_mitigations_auto_nosmt",
      "external": false,
      "loc": "include/linux/cpu.h:233",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
bool cpu_mitigations_auto_nosmt()
```

```json
{
  "name": "cpu_mitigations_auto_nosmt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579507504,
      "name": "cpu_mitigations_auto_nosmt",
      "external": true,
      "loc": "kernel/cpu.c:2419",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:mds_select_mitigation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579507504,
      "name": "cpu_mitigations_auto_nosmt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
bool cpu_mitigations_auto_nosmt()
```

```json
{
  "name": "cpu_mitigations_auto_nosmt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579535760,
      "name": "cpu_mitigations_auto_nosmt",
      "external": true,
      "loc": "kernel/cpu.c:2550",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:taa_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:mds_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579535760,
      "name": "cpu_mitigations_auto_nosmt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
bool cpu_mitigations_auto_nosmt()
```

```json
{
  "name": "cpu_mitigations_auto_nosmt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579517920,
      "name": "cpu_mitigations_auto_nosmt",
      "external": true,
      "loc": "kernel/cpu.c:2561",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:taa_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:mds_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579517920,
      "name": "cpu_mitigations_auto_nosmt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
bool cpu_mitigations_auto_nosmt()
```

```json
{
  "name": "cpu_mitigations_auto_nosmt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579521168,
      "name": "cpu_mitigations_auto_nosmt",
      "external": true,
      "loc": "kernel/cpu.c:2681",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:mds_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579521168,
      "name": "cpu_mitigations_auto_nosmt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
bool cpu_mitigations_auto_nosmt()
```

```json
{
  "name": "cpu_mitigations_auto_nosmt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579592880,
      "name": "cpu_mitigations_auto_nosmt",
      "external": true,
      "loc": "kernel/cpu.c:2708",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:mds_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579592880,
      "name": "cpu_mitigations_auto_nosmt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
bool cpu_mitigations_auto_nosmt()
```

```json
{
  "name": "cpu_mitigations_auto_nosmt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579684400,
      "name": "cpu_mitigations_auto_nosmt",
      "external": true,
      "loc": "kernel/cpu.c:2730",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:mmio_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:taa_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:mds_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:retbleed_select_mitigation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579684400,
      "name": "cpu_mitigations_auto_nosmt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
bool cpu_mitigations_auto_nosmt()
```

```json
{
  "name": "cpu_mitigations_auto_nosmt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579807280,
      "name": "cpu_mitigations_auto_nosmt",
      "external": true,
      "loc": "kernel/cpu.c:2757",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:mmio_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:taa_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:mds_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:retbleed_select_mitigation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579807280,
      "name": "cpu_mitigations_auto_nosmt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
bool cpu_mitigations_auto_nosmt()
```

```json
{
  "name": "cpu_mitigations_auto_nosmt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579855472,
      "name": "cpu_mitigations_auto_nosmt",
      "external": true,
      "loc": "kernel/cpu.c:3154",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:mmio_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:taa_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:mds_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:retbleed_select_mitigation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579855472,
      "name": "cpu_mitigations_auto_nosmt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
bool cpu_mitigations_auto_nosmt()
```

```json
{
  "name": "cpu_mitigations_auto_nosmt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579893280,
      "name": "cpu_mitigations_auto_nosmt",
      "external": true,
      "loc": "kernel/cpu.c:3236",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:mmio_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:taa_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:mds_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:retbleed_select_mitigation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579893280,
      "name": "cpu_mitigations_auto_nosmt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
bool cpu_mitigations_auto_nosmt()
```

```json
{
  "name": "cpu_mitigations_auto_nosmt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490642704,
      "name": "cpu_mitigations_auto_nosmt",
      "external": true,
      "loc": "kernel/cpu.c:2419",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490642704,
      "name": "cpu_mitigations_auto_nosmt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
bool cpu_mitigations_auto_nosmt()
```

```json
{
  "name": "cpu_mitigations_auto_nosmt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224718856,
      "name": "cpu_mitigations_auto_nosmt",
      "external": true,
      "loc": "kernel/cpu.c:2419",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3224718856,
      "name": "cpu_mitigations_auto_nosmt",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
bool cpu_mitigations_auto_nosmt()
```

```json
{
  "name": "cpu_mitigations_auto_nosmt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283461184,
      "name": "cpu_mitigations_auto_nosmt",
      "external": true,
      "loc": "kernel/cpu.c:2419",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283461184,
      "name": "cpu_mitigations_auto_nosmt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
bool cpu_mitigations_auto_nosmt()
```

```json
{
  "name": "cpu_mitigations_auto_nosmt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271394976,
      "name": "cpu_mitigations_auto_nosmt",
      "external": true,
      "loc": "kernel/cpu.c:2419",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271394976,
      "name": "cpu_mitigations_auto_nosmt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
bool cpu_mitigations_auto_nosmt()
```

```json
{
  "name": "cpu_mitigations_auto_nosmt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579481168,
      "name": "cpu_mitigations_auto_nosmt",
      "external": true,
      "loc": "kernel/cpu.c:2419",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:mds_select_mitigation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579481168,
      "name": "cpu_mitigations_auto_nosmt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
bool cpu_mitigations_auto_nosmt()
```

```json
{
  "name": "cpu_mitigations_auto_nosmt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579410048,
      "name": "cpu_mitigations_auto_nosmt",
      "external": true,
      "loc": "kernel/cpu.c:2419",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:mds_select_mitigation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579410048,
      "name": "cpu_mitigations_auto_nosmt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
bool cpu_mitigations_auto_nosmt()
```

```json
{
  "name": "cpu_mitigations_auto_nosmt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579481088,
      "name": "cpu_mitigations_auto_nosmt",
      "external": true,
      "loc": "kernel/cpu.c:2419",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:mds_select_mitigation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579481088,
      "name": "cpu_mitigations_auto_nosmt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
bool cpu_mitigations_auto_nosmt()
```

```json
{
  "name": "cpu_mitigations_auto_nosmt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579512944,
      "name": "cpu_mitigations_auto_nosmt",
      "external": true,
      "loc": "kernel/cpu.c:2419",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:mds_select_mitigation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579512944,
      "name": "cpu_mitigations_auto_nosmt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
bool cpu_mitigations_auto_nosmt()
```
</details>
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
