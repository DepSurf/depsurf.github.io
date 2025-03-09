# Function: <code>uncore_type_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uncore_type_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594966931,
      "name": "uncore_type_init",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.c:785",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_types_init"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int uncore_type_init(struct intel_uncore_type * type, bool setid)
```

```json
{
  "name": "uncore_type_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595129941,
      "name": "uncore_type_init",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.c:819",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:intel_uncore_init",
        "arch/x86/events/intel/uncore.c:intel_uncore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595129941,
      "name": "uncore_type_init",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 351
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
int uncore_type_init(struct intel_uncore_type * type, bool setid)
```

```json
{
  "name": "uncore_type_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595372751,
      "name": "uncore_type_init",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.c:805",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:intel_uncore_init",
        "arch/x86/events/intel/uncore.c:intel_uncore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595372751,
      "name": "uncore_type_init",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 351
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
int uncore_type_init(struct intel_uncore_type * type, bool setid)
```

```json
{
  "name": "uncore_type_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596290908,
      "name": "uncore_type_init",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.c:805",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:intel_uncore_init",
        "arch/x86/events/intel/uncore.c:intel_uncore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596290908,
      "name": "uncore_type_init",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 350
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
int uncore_type_init(struct intel_uncore_type * type, bool setid)
```

```json
{
  "name": "uncore_type_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071602607686,
      "name": "uncore_type_init",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.c:805",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:intel_uncore_init",
        "arch/x86/events/intel/uncore.c:intel_uncore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602607686,
      "name": "uncore_type_init",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 398
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
int uncore_type_init(struct intel_uncore_type * type, bool setid)
```

```json
{
  "name": "uncore_type_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071602776011,
      "name": "uncore_type_init",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.c:865",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:intel_uncore_init",
        "arch/x86/events/intel/uncore.c:intel_uncore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602776011,
      "name": "uncore_type_init",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 433
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
int uncore_type_init(struct intel_uncore_type * type, bool setid)
```

```json
{
  "name": "uncore_type_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604570843,
      "name": "uncore_type_init",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.c:866",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:intel_uncore_init",
        "arch/x86/events/intel/uncore.c:intel_uncore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604570843,
      "name": "uncore_type_init",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 445
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uncore_type_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604665542,
      "name": "uncore_type_init",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.c:876",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_types_init"
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
  "name": "uncore_type_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604678040,
      "name": "uncore_type_init",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.c:908",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_types_init"
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
int uncore_type_init(struct intel_uncore_type * type, bool setid)
```

```json
{
  "name": "uncore_type_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609028115,
      "name": "uncore_type_init",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.c:908",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_types_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609028115,
      "name": "uncore_type_init",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 458
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
int uncore_type_init(struct intel_uncore_type * type, bool setid)
```

```json
{
  "name": "uncore_type_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612091437,
      "name": "uncore_type_init",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.c:918",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_types_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612091437,
      "name": "uncore_type_init",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 494
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
int uncore_type_init(struct intel_uncore_type * type, bool setid)
```

```json
{
  "name": "uncore_type_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614230942,
      "name": "uncore_type_init",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.c:958",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_types_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614230942,
      "name": "uncore_type_init",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 503
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
int uncore_type_init(struct intel_uncore_type * type, bool setid)
```

```json
{
  "name": "uncore_type_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615149548,
      "name": "uncore_type_init",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.c:965",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_types_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615149548,
      "name": "uncore_type_init",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 537
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
int uncore_type_init(struct intel_uncore_type * type, bool setid)
```

```json
{
  "name": "uncore_type_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071616914416,
      "name": "uncore_type_init",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.c:965",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_types_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071616914416,
      "name": "uncore_type_init",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 534
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
int uncore_type_init(struct intel_uncore_type * type, bool setid)
```

```json
{
  "name": "uncore_type_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071627512256,
      "name": "uncore_type_init",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.c:965",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:intel_uncore_init",
        "arch/x86/events/intel/uncore.c:intel_uncore_init",
        "arch/x86/events/intel/uncore.c:uncore_pci_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627512256,
      "name": "uncore_type_init",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 601
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
int uncore_type_init(struct intel_uncore_type * type, bool setid)
```

```json
{
  "name": "uncore_type_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619257168,
      "name": "uncore_type_init",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.c:986",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:intel_uncore_init",
        "arch/x86/events/intel/uncore.c:intel_uncore_init",
        "arch/x86/events/intel/uncore.c:uncore_pci_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619257168,
      "name": "uncore_type_init",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 602
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
int uncore_type_init(struct intel_uncore_type * type, bool setid)
```

```json
{
  "name": "uncore_type_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071621549840,
      "name": "uncore_type_init",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.c:986",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:intel_uncore_init",
        "arch/x86/events/intel/uncore.c:intel_uncore_init",
        "arch/x86/events/intel/uncore.c:uncore_pci_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071621549840,
      "name": "uncore_type_init",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 602
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
  "name": "uncore_type_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604604312,
      "name": "uncore_type_init",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.c:908",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_types_init"
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
  "name": "uncore_type_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604595837,
      "name": "uncore_type_init",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.c:908",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_types_init"
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
  "name": "uncore_type_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604682136,
      "name": "uncore_type_init",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.c:908",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_types_init"
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
  "name": "uncore_type_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604682156,
      "name": "uncore_type_init",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.c:908",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_types_init"
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int uncore_type_init(struct intel_uncore_type * type, bool setid)
```
</details>
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
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
int uncore_type_init(struct intel_uncore_type * type, bool setid)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int uncore_type_init(struct intel_uncore_type * type, bool setid)
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
