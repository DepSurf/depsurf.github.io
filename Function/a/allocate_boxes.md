# Function: <code>allocate_boxes</code>

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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "allocate_boxes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578932779,
      "name": "allocate_boxes",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.c:1117",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online"
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
  "name": "allocate_boxes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578925855,
      "name": "allocate_boxes",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.c:1117",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online"
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
  "name": "allocate_boxes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578928211,
      "name": "allocate_boxes",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.c:1125",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online"
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
  "name": "allocate_boxes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578931171,
      "name": "allocate_boxes",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.c:1186",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online"
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
  "name": "allocate_boxes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578932707,
      "name": "allocate_boxes",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.c:1187",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online"
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
int allocate_boxes(struct intel_uncore_type * * types, unsigned int die, unsigned int cpu)
```

```json
{
  "name": "allocate_boxes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578935216,
      "name": "allocate_boxes",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.c:1208",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online",
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online",
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578935216,
      "name": "allocate_boxes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 521
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
int allocate_boxes(struct intel_uncore_type * * types, unsigned int die, unsigned int cpu)
```

```json
{
  "name": "allocate_boxes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578937696,
      "name": "allocate_boxes",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.c:1240",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online",
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online",
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578937696,
      "name": "allocate_boxes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 521
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
int allocate_boxes(struct intel_uncore_type * * types, unsigned int die, unsigned int cpu)
```

```json
{
  "name": "allocate_boxes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578943728,
      "name": "allocate_boxes",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.c:1240",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online",
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online",
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578943728,
      "name": "allocate_boxes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 524
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
int allocate_boxes(struct intel_uncore_type * * types, unsigned int die, unsigned int cpu)
```

```json
{
  "name": "allocate_boxes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578945472,
      "name": "allocate_boxes",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.c:1400",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online",
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online",
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578945472,
      "name": "allocate_boxes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 527
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
int allocate_boxes(struct intel_uncore_type * * types, unsigned int die, unsigned int cpu)
```

```json
{
  "name": "allocate_boxes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578950368,
      "name": "allocate_boxes",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.c:1511",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online",
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online",
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578950368,
      "name": "allocate_boxes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 526
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
int allocate_boxes(struct intel_uncore_type * * types, unsigned int die, unsigned int cpu)
```

```json
{
  "name": "allocate_boxes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578960432,
      "name": "allocate_boxes",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.c:1518",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online",
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online",
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578960432,
      "name": "allocate_boxes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 565
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
int allocate_boxes(struct intel_uncore_type * * types, unsigned int die, unsigned int cpu)
```

```json
{
  "name": "allocate_boxes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578970624,
      "name": "allocate_boxes",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.c:1518",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online",
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online",
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578970624,
      "name": "allocate_boxes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 577
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
int allocate_boxes(struct intel_uncore_type * * types, unsigned int die, unsigned int cpu)
```

```json
{
  "name": "allocate_boxes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578988432,
      "name": "allocate_boxes",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.c:1518",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online",
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online",
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578988432,
      "name": "allocate_boxes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 577
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
int allocate_boxes(struct intel_uncore_type * * types, unsigned int die, unsigned int cpu)
```

```json
{
  "name": "allocate_boxes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578987664,
      "name": "allocate_boxes",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.c:1539",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online",
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online",
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578987664,
      "name": "allocate_boxes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 577
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
int allocate_boxes(struct intel_uncore_type * * types, unsigned int die, unsigned int cpu)
```

```json
{
  "name": "allocate_boxes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579012544,
      "name": "allocate_boxes",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.c:1539",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online",
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online",
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579012544,
      "name": "allocate_boxes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 577
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
int allocate_boxes(struct intel_uncore_type * * types, unsigned int die, unsigned int cpu)
```

```json
{
  "name": "allocate_boxes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578937696,
      "name": "allocate_boxes",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.c:1240",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online",
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online",
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578937696,
      "name": "allocate_boxes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 521
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
int allocate_boxes(struct intel_uncore_type * * types, unsigned int die, unsigned int cpu)
```

```json
{
  "name": "allocate_boxes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578934672,
      "name": "allocate_boxes",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.c:1240",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online",
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online",
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578934672,
      "name": "allocate_boxes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 521
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
int allocate_boxes(struct intel_uncore_type * * types, unsigned int die, unsigned int cpu)
```

```json
{
  "name": "allocate_boxes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578937632,
      "name": "allocate_boxes",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.c:1240",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online",
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online",
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578937632,
      "name": "allocate_boxes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 521
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
int allocate_boxes(struct intel_uncore_type * * types, unsigned int die, unsigned int cpu)
```

```json
{
  "name": "allocate_boxes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578938208,
      "name": "allocate_boxes",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.c:1240",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online",
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online",
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578938208,
      "name": "allocate_boxes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 521
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
int allocate_boxes(struct intel_uncore_type * * types, unsigned int die, unsigned int cpu)
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
int allocate_boxes(struct intel_uncore_type * * types, unsigned int die, unsigned int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int allocate_boxes(struct intel_uncore_type * * types, unsigned int die, unsigned int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int allocate_boxes(struct intel_uncore_type * * types, unsigned int die, unsigned int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int allocate_boxes(struct intel_uncore_type * * types, unsigned int die, unsigned int cpu)
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
