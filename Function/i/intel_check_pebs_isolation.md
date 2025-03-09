# Function: <code>intel_check_pebs_isolation</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void intel_check_pebs_isolation()
```

```json
{
  "name": "intel_check_pebs_isolation",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604656267,
      "name": "intel_check_pebs_isolation",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:4000",
      "file": "arch/x86/events/intel/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pebs_isolation_quirk"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578895056,
      "name": "intel_check_pebs_isolation",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
void intel_check_pebs_isolation()
```

```json
{
  "name": "intel_check_pebs_isolation",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604668666,
      "name": "intel_check_pebs_isolation",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:4018",
      "file": "arch/x86/events/intel/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pebs_isolation_quirk"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578896128,
      "name": "intel_check_pebs_isolation",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
void intel_check_pebs_isolation()
```

```json
{
  "name": "intel_check_pebs_isolation",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578900560,
      "name": "intel_check_pebs_isolation",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:4056",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pebs_isolation_quirk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578900560,
      "name": "intel_check_pebs_isolation",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
void intel_check_pebs_isolation()
```

```json
{
  "name": "intel_check_pebs_isolation",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578896688,
      "name": "intel_check_pebs_isolation",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:4423",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pebs_isolation_quirk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578896688,
      "name": "intel_check_pebs_isolation",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
void intel_check_pebs_isolation()
```

```json
{
  "name": "intel_check_pebs_isolation",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578899296,
      "name": "intel_check_pebs_isolation",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:4710",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pebs_isolation_quirk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578899296,
      "name": "intel_check_pebs_isolation",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
void intel_check_pebs_isolation()
```

```json
{
  "name": "intel_check_pebs_isolation",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578900480,
      "name": "intel_check_pebs_isolation",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:4730",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pebs_isolation_quirk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578900480,
      "name": "intel_check_pebs_isolation",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
void intel_check_pebs_isolation()
```

```json
{
  "name": "intel_check_pebs_isolation",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578905504,
      "name": "intel_check_pebs_isolation",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:4800",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pebs_isolation_quirk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578905504,
      "name": "intel_check_pebs_isolation",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
void intel_check_pebs_isolation()
```

```json
{
  "name": "intel_check_pebs_isolation",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071627497781,
      "name": "intel_check_pebs_isolation",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:4926",
      "file": "arch/x86/events/intel/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pebs_isolation_quirk"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578919600,
      "name": "intel_check_pebs_isolation",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
void intel_check_pebs_isolation()
```

```json
{
  "name": "intel_check_pebs_isolation",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071619241893,
      "name": "intel_check_pebs_isolation",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:5057",
      "file": "arch/x86/events/intel/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pebs_isolation_quirk"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578916784,
      "name": "intel_check_pebs_isolation",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
void intel_check_pebs_isolation()
```

```json
{
  "name": "intel_check_pebs_isolation",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071621532085,
      "name": "intel_check_pebs_isolation",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:5221",
      "file": "arch/x86/events/intel/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pebs_isolation_quirk"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578939216,
      "name": "intel_check_pebs_isolation",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
void intel_check_pebs_isolation()
```

```json
{
  "name": "intel_check_pebs_isolation",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604594938,
      "name": "intel_check_pebs_isolation",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:4018",
      "file": "arch/x86/events/intel/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pebs_isolation_quirk"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578896128,
      "name": "intel_check_pebs_isolation",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void intel_check_pebs_isolation()
```

```json
{
  "name": "intel_check_pebs_isolation",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604586592,
      "name": "intel_check_pebs_isolation",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:4018",
      "file": "arch/x86/events/intel/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pebs_isolation_quirk"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578889984,
      "name": "intel_check_pebs_isolation",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void intel_check_pebs_isolation()
```

```json
{
  "name": "intel_check_pebs_isolation",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604672762,
      "name": "intel_check_pebs_isolation",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:4018",
      "file": "arch/x86/events/intel/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pebs_isolation_quirk"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578896064,
      "name": "intel_check_pebs_isolation",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
void intel_check_pebs_isolation()
```

```json
{
  "name": "intel_check_pebs_isolation",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604672782,
      "name": "intel_check_pebs_isolation",
      "external": false,
      "loc": "arch/x86/events/intel/core.c:4018",
      "file": "arch/x86/events/intel/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pebs_isolation_quirk"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578896624,
      "name": "intel_check_pebs_isolation",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
void intel_check_pebs_isolation()
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
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void intel_check_pebs_isolation()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void intel_check_pebs_isolation()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void intel_check_pebs_isolation()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void intel_check_pebs_isolation()
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
