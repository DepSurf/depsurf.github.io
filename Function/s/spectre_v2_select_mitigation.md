# Function: <code>spectre_v2_select_mitigation</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "spectre_v2_select_mitigation",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602654120,
      "name": "spectre_v2_select_mitigation",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:221",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "not declared, inlined",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "spectre_v2_select_mitigation",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602824576,
      "name": "spectre_v2_select_mitigation",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:327",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "not declared, inlined",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "spectre_v2_select_mitigation",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604619753,
      "name": "spectre_v2_select_mitigation",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:482",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "not declared, inlined",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "spectre_v2_select_mitigation",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604716824,
      "name": "spectre_v2_select_mitigation",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:637",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "not declared, inlined",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "spectre_v2_select_mitigation",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604729485,
      "name": "spectre_v2_select_mitigation",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:759",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "not declared, inlined",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void spectre_v2_select_mitigation()
```

```json
{
  "name": "spectre_v2_select_mitigation",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609076382,
      "name": "spectre_v2_select_mitigation",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:866",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609076382,
      "name": "spectre_v2_select_mitigation",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 461
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
void spectre_v2_select_mitigation()
```

```json
{
  "name": "spectre_v2_select_mitigation",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612140100,
      "name": "spectre_v2_select_mitigation",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:860",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612140100,
      "name": "spectre_v2_select_mitigation",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 461
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
void spectre_v2_select_mitigation()
```

```json
{
  "name": "spectre_v2_select_mitigation",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614278862,
      "name": "spectre_v2_select_mitigation",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:860",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614278862,
      "name": "spectre_v2_select_mitigation",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 759
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
void spectre_v2_select_mitigation()
```

```json
{
  "name": "spectre_v2_select_mitigation",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615202311,
      "name": "spectre_v2_select_mitigation",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:963",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615202311,
      "name": "spectre_v2_select_mitigation",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 482
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
void spectre_v2_select_mitigation()
```

```json
{
  "name": "spectre_v2_select_mitigation",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071616974609,
      "name": "spectre_v2_select_mitigation",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:1389",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071616974609,
      "name": "spectre_v2_select_mitigation",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 905
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
void spectre_v2_select_mitigation()
```

```json
{
  "name": "spectre_v2_select_mitigation",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071627595216,
      "name": "spectre_v2_select_mitigation",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:1437",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627595216,
      "name": "spectre_v2_select_mitigation",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 996
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
void spectre_v2_select_mitigation()
```

```json
{
  "name": "spectre_v2_select_mitigation",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619349008,
      "name": "spectre_v2_select_mitigation",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:1544",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:cpu_select_mitigations"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619349008,
      "name": "spectre_v2_select_mitigation",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1056
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
void spectre_v2_select_mitigation()
```

```json
{
  "name": "spectre_v2_select_mitigation",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071621642880,
      "name": "spectre_v2_select_mitigation",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:1682",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:cpu_select_mitigations"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071621642880,
      "name": "spectre_v2_select_mitigation",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1097
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "spectre_v2_select_mitigation",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604655788,
      "name": "spectre_v2_select_mitigation",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:759",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "not declared, inlined",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "spectre_v2_select_mitigation",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604623542,
      "name": "spectre_v2_select_mitigation",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:759",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "not declared, inlined",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "spectre_v2_select_mitigation",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604733551,
      "name": "spectre_v2_select_mitigation",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:759",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "not declared, inlined",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "spectre_v2_select_mitigation",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604733597,
      "name": "spectre_v2_select_mitigation",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:759",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "not declared, inlined",
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
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void spectre_v2_select_mitigation()
```
</details>
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
