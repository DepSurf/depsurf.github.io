# Function: <code>add_rmid_to_limbo</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "add_rmid_to_limbo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579125155,
      "name": "add_rmid_to_limbo",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel_rdt_monitor.c:176",
      "file": "arch/x86/kernel/cpu/intel_rdt_monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_monitor.c:free_rmid"
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
  "name": "add_rmid_to_limbo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579139443,
      "name": "add_rmid_to_limbo",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel_rdt_monitor.c:176",
      "file": "arch/x86/kernel/cpu/intel_rdt_monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_monitor.c:free_rmid"
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
  "name": "add_rmid_to_limbo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579149392,
      "name": "add_rmid_to_limbo",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel_rdt_monitor.c:176",
      "file": "arch/x86/kernel/cpu/intel_rdt_monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_monitor.c:free_rmid"
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
  "name": "add_rmid_to_limbo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579215824,
      "name": "add_rmid_to_limbo",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:173",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid"
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
  "name": "add_rmid_to_limbo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579228864,
      "name": "add_rmid_to_limbo",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:165",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid"
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
  "name": "add_rmid_to_limbo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579231088,
      "name": "add_rmid_to_limbo",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:165",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid"
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
void add_rmid_to_limbo(struct rmid_entry * entry)
```

```json
{
  "name": "add_rmid_to_limbo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579253872,
      "name": "add_rmid_to_limbo",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:165",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579253872,
      "name": "add_rmid_to_limbo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
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
void add_rmid_to_limbo(struct rmid_entry * entry)
```

```json
{
  "name": "add_rmid_to_limbo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579246752,
      "name": "add_rmid_to_limbo",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:228",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579246752,
      "name": "add_rmid_to_limbo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
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
void add_rmid_to_limbo(struct rmid_entry * entry)
```

```json
{
  "name": "add_rmid_to_limbo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579249408,
      "name": "add_rmid_to_limbo",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:228",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579249408,
      "name": "add_rmid_to_limbo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 231
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
void add_rmid_to_limbo(struct rmid_entry * entry)
```

```json
{
  "name": "add_rmid_to_limbo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579290000,
      "name": "add_rmid_to_limbo",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:228",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579290000,
      "name": "add_rmid_to_limbo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 231
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
void add_rmid_to_limbo(struct rmid_entry * entry)
```

```json
{
  "name": "add_rmid_to_limbo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579344368,
      "name": "add_rmid_to_limbo",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:228",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579344368,
      "name": "add_rmid_to_limbo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
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
void add_rmid_to_limbo(struct rmid_entry * entry)
```

```json
{
  "name": "add_rmid_to_limbo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579414144,
      "name": "add_rmid_to_limbo",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:317",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579414144,
      "name": "add_rmid_to_limbo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 342
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
void add_rmid_to_limbo(struct rmid_entry * entry)
```

```json
{
  "name": "add_rmid_to_limbo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579426592,
      "name": "add_rmid_to_limbo",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:334",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579426592,
      "name": "add_rmid_to_limbo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 342
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
void add_rmid_to_limbo(struct rmid_entry * entry)
```

```json
{
  "name": "add_rmid_to_limbo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579456176,
      "name": "add_rmid_to_limbo",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:334",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579456176,
      "name": "add_rmid_to_limbo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 342
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
  "name": "add_rmid_to_limbo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579229936,
      "name": "add_rmid_to_limbo",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:165",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid"
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
  "name": "add_rmid_to_limbo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579165112,
      "name": "add_rmid_to_limbo",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:165",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid"
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
  "name": "add_rmid_to_limbo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579231008,
      "name": "add_rmid_to_limbo",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:165",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid"
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
  "name": "add_rmid_to_limbo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579236416,
      "name": "add_rmid_to_limbo",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/monitor.c:165",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid"
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
void add_rmid_to_limbo(struct rmid_entry * entry)
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
