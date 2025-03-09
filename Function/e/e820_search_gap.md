# Function: <code>e820_search_gap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int e820_search_gap(long unsigned int * gapstart, long unsigned int * gapsize, long unsigned int start_addr, long long unsigned int end_addr)
```

```json
{
  "name": "e820_search_gap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594999664,
      "name": "e820_search_gap",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:583",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820_setup_gap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594999664,
      "name": "e820_search_gap",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int e820_search_gap(long unsigned int * gapstart, long unsigned int * gapsize, long unsigned int start_addr, long long unsigned int end_addr)
```

```json
{
  "name": "e820_search_gap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595163173,
      "name": "e820_search_gap",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:583",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820_setup_gap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595163173,
      "name": "e820_search_gap",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 134
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
int e820_search_gap(long unsigned int * gapstart, long unsigned int * gapsize, long unsigned int start_addr, long long unsigned int end_addr)
```

```json
{
  "name": "e820_search_gap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595405815,
      "name": "e820_search_gap",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:585",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820_setup_gap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595405815,
      "name": "e820_search_gap",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 121
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
  "name": "e820_search_gap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596325339,
      "name": "e820_search_gap",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:571",
      "file": "arch/x86/kernel/e820.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/e820.c:e820__setup_pci_gap"
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
  "name": "e820_search_gap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602643377,
      "name": "e820_search_gap",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:591",
      "file": "arch/x86/kernel/e820.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/e820.c:e820__setup_pci_gap"
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
  "name": "e820_search_gap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602813049,
      "name": "e820_search_gap",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:593",
      "file": "arch/x86/kernel/e820.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/e820.c:e820__setup_pci_gap"
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
  "name": "e820_search_gap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604608096,
      "name": "e820_search_gap",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:592",
      "file": "arch/x86/kernel/e820.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/e820.c:e820__setup_pci_gap"
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
  "name": "e820_search_gap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604703678,
      "name": "e820_search_gap",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:606",
      "file": "arch/x86/kernel/e820.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/e820.c:e820__setup_pci_gap"
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
  "name": "e820_search_gap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604716066,
      "name": "e820_search_gap",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:606",
      "file": "arch/x86/kernel/e820.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/e820.c:e820__setup_pci_gap"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "e820_search_gap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071609063248,
      "name": "e820_search_gap",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:607",
      "file": "arch/x86/kernel/e820.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/e820.c:e820__setup_pci_gap"
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
  "name": "e820_search_gap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071612126624,
      "name": "e820_search_gap",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:621",
      "file": "arch/x86/kernel/e820.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/e820.c:e820__setup_pci_gap"
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
  "name": "e820_search_gap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071614266548,
      "name": "e820_search_gap",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:621",
      "file": "arch/x86/kernel/e820.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/e820.c:e820__setup_pci_gap"
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
  "name": "e820_search_gap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071615188635,
      "name": "e820_search_gap",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:621",
      "file": "arch/x86/kernel/e820.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/e820.c:e820__setup_pci_gap"
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
  "name": "e820_search_gap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071616955643,
      "name": "e820_search_gap",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:621",
      "file": "arch/x86/kernel/e820.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/e820.c:e820__setup_pci_gap"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "e820_search_gap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627569125,
      "name": "e820_search_gap",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:621",
      "file": "arch/x86/kernel/e820.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/e820.c:e820__setup_pci_gap"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "e820_search_gap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619320805,
      "name": "e820_search_gap",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:621",
      "file": "arch/x86/kernel/e820.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/e820.c:e820__setup_pci_gap"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "e820_search_gap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621613925,
      "name": "e820_search_gap",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:621",
      "file": "arch/x86/kernel/e820.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/e820.c:e820__setup_pci_gap"
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
  "name": "e820_search_gap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604642356,
      "name": "e820_search_gap",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:606",
      "file": "arch/x86/kernel/e820.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/e820.c:e820__setup_pci_gap"
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
  "name": "e820_search_gap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604610290,
      "name": "e820_search_gap",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:606",
      "file": "arch/x86/kernel/e820.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/e820.c:e820__setup_pci_gap"
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
  "name": "e820_search_gap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604720148,
      "name": "e820_search_gap",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:606",
      "file": "arch/x86/kernel/e820.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/e820.c:e820__setup_pci_gap"
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
  "name": "e820_search_gap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604720178,
      "name": "e820_search_gap",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:606",
      "file": "arch/x86/kernel/e820.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/e820.c:e820__setup_pci_gap"
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
int e820_search_gap(long unsigned int * gapstart, long unsigned int * gapsize, long unsigned int start_addr, long long unsigned int end_addr)
```
</details>
</li>
</ul>
