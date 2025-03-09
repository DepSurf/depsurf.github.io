# Function: <code>spectre_v2_user_select_mitigation</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "spectre_v2_user_select_mitigation",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604620331,
      "name": "spectre_v2_user_select_mitigation",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "spectre_v2_user_select_mitigation",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604717405,
      "name": "spectre_v2_user_select_mitigation",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:481",
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
  "name": "spectre_v2_user_select_mitigation",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604730062,
      "name": "spectre_v2_user_select_mitigation",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:603",
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
void spectre_v2_user_select_mitigation(enum spectre_v2_mitigation_cmd v2_cmd)
```

```json
{
  "name": "spectre_v2_user_select_mitigation",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609075789,
      "name": "spectre_v2_user_select_mitigation",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:706",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_select_mitigation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609075789,
      "name": "spectre_v2_user_select_mitigation",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 593
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
void spectre_v2_user_select_mitigation(enum spectre_v2_mitigation_cmd v2_cmd)
```

```json
{
  "name": "spectre_v2_user_select_mitigation",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612139500,
      "name": "spectre_v2_user_select_mitigation",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:704",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_select_mitigation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612139500,
      "name": "spectre_v2_user_select_mitigation",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 600
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
void spectre_v2_user_select_mitigation(enum spectre_v2_mitigation_cmd v2_cmd)
```

```json
{
  "name": "spectre_v2_user_select_mitigation",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614278241,
      "name": "spectre_v2_user_select_mitigation",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:704",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_select_mitigation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614278241,
      "name": "spectre_v2_user_select_mitigation",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 621
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
void spectre_v2_user_select_mitigation(enum spectre_v2_mitigation_cmd v2_cmd)
```

```json
{
  "name": "spectre_v2_user_select_mitigation",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615201540,
      "name": "spectre_v2_user_select_mitigation",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:778",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_select_mitigation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615201540,
      "name": "spectre_v2_user_select_mitigation",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 771
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
void spectre_v2_user_select_mitigation()
```

```json
{
  "name": "spectre_v2_user_select_mitigation",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071616972324,
      "name": "spectre_v2_user_select_mitigation",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:1107",
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
      "addr": 18446744071616972324,
      "name": "spectre_v2_user_select_mitigation",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 801
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
void spectre_v2_user_select_mitigation()
```

```json
{
  "name": "spectre_v2_user_select_mitigation",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071627593344,
      "name": "spectre_v2_user_select_mitigation",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:1148",
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
      "addr": 18446744071627593344,
      "name": "spectre_v2_user_select_mitigation",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 967
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
void spectre_v2_user_select_mitigation()
```

```json
{
  "name": "spectre_v2_user_select_mitigation",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619347184,
      "name": "spectre_v2_user_select_mitigation",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:1253",
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
      "addr": 18446744071619347184,
      "name": "spectre_v2_user_select_mitigation",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 959
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
void spectre_v2_user_select_mitigation()
```

```json
{
  "name": "spectre_v2_user_select_mitigation",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071621640512,
      "name": "spectre_v2_user_select_mitigation",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:1318",
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
      "addr": 18446744071621640512,
      "name": "spectre_v2_user_select_mitigation",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 959
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
  "name": "spectre_v2_user_select_mitigation",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604656365,
      "name": "spectre_v2_user_select_mitigation",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:603",
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
  "name": "spectre_v2_user_select_mitigation",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604624126,
      "name": "spectre_v2_user_select_mitigation",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:603",
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
  "name": "spectre_v2_user_select_mitigation",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604734128,
      "name": "spectre_v2_user_select_mitigation",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:603",
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
  "name": "spectre_v2_user_select_mitigation",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604734174,
      "name": "spectre_v2_user_select_mitigation",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:603",
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
void spectre_v2_user_select_mitigation(enum spectre_v2_mitigation_cmd v2_cmd)
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>enum spectre_v2_mitigation_cmd v2_cmd</code>
</li>
</ul>
</details>
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
