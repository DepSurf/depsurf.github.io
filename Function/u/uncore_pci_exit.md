# Function: <code>uncore_pci_exit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uncore_pci_exit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594967640,
      "name": "uncore_pci_exit",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.c:1021",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "uncore_pci_exit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596568331,
      "name": "uncore_pci_exit",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.c:1046",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:intel_uncore_exit",
        "arch/x86/events/intel/uncore.c:intel_uncore_init"
      ],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:intel_uncore_exit",
        "arch/x86/events/intel/uncore.c:intel_uncore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579362171,
      "name": "uncore_pci_exit.part.23",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uncore_pci_exit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071597510142,
      "name": "uncore_pci_exit",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.c:1032",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:intel_uncore_exit",
        "arch/x86/events/intel/uncore.c:intel_uncore_init"
      ],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:intel_uncore_exit",
        "arch/x86/events/intel/uncore.c:intel_uncore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579379995,
      "name": "uncore_pci_exit.part.23",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uncore_pci_exit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071598513926,
      "name": "uncore_pci_exit",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.c:1032",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:intel_uncore_exit",
        "arch/x86/events/intel/uncore.c:intel_uncore_init"
      ],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:intel_uncore_exit",
        "arch/x86/events/intel/uncore.c:intel_uncore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578929869,
      "name": "uncore_pci_exit.part.23",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uncore_pci_exit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604883590,
      "name": "uncore_pci_exit",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.c:1040",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:intel_uncore_exit",
        "arch/x86/events/intel/uncore.c:intel_uncore_init"
      ],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:intel_uncore_exit",
        "arch/x86/events/intel/uncore.c:intel_uncore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578932013,
      "name": "uncore_pci_exit.part.23",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void uncore_pci_exit()
```

```json
{
  "name": "uncore_pci_exit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578935069,
      "name": "uncore_pci_exit",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.c:1101",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:intel_uncore_exit",
        "arch/x86/events/intel/uncore.c:intel_uncore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578935069,
      "name": "uncore_pci_exit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void uncore_pci_exit()
```

```json
{
  "name": "uncore_pci_exit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578936989,
      "name": "uncore_pci_exit",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.c:1102",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:intel_uncore_exit",
        "arch/x86/events/intel/uncore.c:intel_uncore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578936989,
      "name": "uncore_pci_exit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
  "name": "uncore_pci_exit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071607170928,
      "name": "uncore_pci_exit",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.c:1114",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:intel_uncore_exit",
        "arch/x86/events/intel/uncore.c:intel_uncore_init"
      ],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:intel_uncore_exit",
        "arch/x86/events/intel/uncore.c:intel_uncore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578942670,
      "name": "uncore_pci_exit.part.0",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uncore_pci_exit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071607232096,
      "name": "uncore_pci_exit",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.c:1146",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:intel_uncore_exit",
        "arch/x86/events/intel/uncore.c:intel_uncore_init"
      ],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:intel_uncore_exit",
        "arch/x86/events/intel/uncore.c:intel_uncore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578945118,
      "name": "uncore_pci_exit.part.0",
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
  "name": "uncore_pci_exit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071611498747,
      "name": "uncore_pci_exit",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.c:1146",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:intel_uncore_exit",
        "arch/x86/events/intel/uncore.c:intel_uncore_init"
      ],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:intel_uncore_exit",
        "arch/x86/events/intel/uncore.c:intel_uncore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578951624,
      "name": "uncore_pci_exit.part.0",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uncore_pci_exit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071614613147,
      "name": "uncore_pci_exit",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.c:1304",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:intel_uncore_exit",
        "arch/x86/events/intel/uncore.c:intel_uncore_init"
      ],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:intel_uncore_exit",
        "arch/x86/events/intel/uncore.c:intel_uncore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591240760,
      "name": "uncore_pci_exit.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uncore_pci_exit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071616923283,
      "name": "uncore_pci_exit",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.c:1412",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:intel_uncore_exit",
        "arch/x86/events/intel/uncore.c:intel_uncore_init"
      ],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:intel_uncore_exit",
        "arch/x86/events/intel/uncore.c:intel_uncore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591184194,
      "name": "uncore_pci_exit.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void uncore_pci_exit()
```

```json
{
  "name": "uncore_pci_exit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592044430,
      "name": "uncore_pci_exit",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.c:1419",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:intel_uncore_exit",
        "arch/x86/events/intel/uncore.c:intel_uncore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592044430,
      "name": "uncore_pci_exit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void uncore_pci_exit()
```

```json
{
  "name": "uncore_pci_exit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593810995,
      "name": "uncore_pci_exit",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.c:1419",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:intel_uncore_exit",
        "arch/x86/events/intel/uncore.c:intel_uncore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593810995,
      "name": "uncore_pci_exit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uncore_pci_exit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071631991836,
      "name": "uncore_pci_exit",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.c:1419",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:intel_uncore_exit",
        "arch/x86/events/intel/uncore.c:intel_uncore_init"
      ],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:intel_uncore_exit",
        "arch/x86/events/intel/uncore.c:intel_uncore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578991456,
      "name": "uncore_pci_exit.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uncore_pci_exit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071623876236,
      "name": "uncore_pci_exit",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.c:1440",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:intel_uncore_exit",
        "arch/x86/events/intel/uncore.c:intel_uncore_init"
      ],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:intel_uncore_exit",
        "arch/x86/events/intel/uncore.c:intel_uncore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578990720,
      "name": "uncore_pci_exit.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uncore_pci_exit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071626349484,
      "name": "uncore_pci_exit",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.c:1440",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:intel_uncore_exit",
        "arch/x86/events/intel/uncore.c:intel_uncore_init"
      ],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:intel_uncore_exit",
        "arch/x86/events/intel/uncore.c:intel_uncore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579015600,
      "name": "uncore_pci_exit.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
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
  "name": "uncore_pci_exit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071607101568,
      "name": "uncore_pci_exit",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.c:1146",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:intel_uncore_exit",
        "arch/x86/events/intel/uncore.c:intel_uncore_init"
      ],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:intel_uncore_exit",
        "arch/x86/events/intel/uncore.c:intel_uncore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578945118,
      "name": "uncore_pci_exit.part.0",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uncore_pci_exit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071606906024,
      "name": "uncore_pci_exit",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.c:1146",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:intel_uncore_exit",
        "arch/x86/events/intel/uncore.c:intel_uncore_init"
      ],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:intel_uncore_exit",
        "arch/x86/events/intel/uncore.c:intel_uncore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578942094,
      "name": "uncore_pci_exit.part.0",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uncore_pci_exit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071607212360,
      "name": "uncore_pci_exit",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.c:1146",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:intel_uncore_exit",
        "arch/x86/events/intel/uncore.c:intel_uncore_init"
      ],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:intel_uncore_exit",
        "arch/x86/events/intel/uncore.c:intel_uncore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578945054,
      "name": "uncore_pci_exit.part.0",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uncore_pci_exit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071607166104,
      "name": "uncore_pci_exit",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.c:1146",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:intel_uncore_exit",
        "arch/x86/events/intel/uncore.c:intel_uncore_init"
      ],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:intel_uncore_exit",
        "arch/x86/events/intel/uncore.c:intel_uncore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578945630,
      "name": "uncore_pci_exit.part.0",
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
<details>
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void uncore_pci_exit()
```
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
void uncore_pci_exit()
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
void uncore_pci_exit()
```
</details>
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void uncore_pci_exit()
```
</details>
</li>
</ul>
