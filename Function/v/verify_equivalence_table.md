# Function: <code>verify_equivalence_table</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool verify_equivalence_table(const u8 * buf, size_t buf_size, bool early)
```

```json
{
  "name": "verify_equivalence_table",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579192496,
      "name": "verify_equivalence_table",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:118",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:scan_containers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579192496,
      "name": "verify_equivalence_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool verify_equivalence_table(const u8 * buf, size_t buf_size, bool early)
```

```json
{
  "name": "verify_equivalence_table",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579205360,
      "name": "verify_equivalence_table",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:116",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:scan_containers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579205360,
      "name": "verify_equivalence_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
bool verify_equivalence_table(const u8 * buf, size_t buf_size, bool early)
```

```json
{
  "name": "verify_equivalence_table",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579207616,
      "name": "verify_equivalence_table",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:116",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:scan_containers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579207616,
      "name": "verify_equivalence_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
  "name": "verify_equivalence_table",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579229445,
      "name": "verify_equivalence_table",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:116",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:install_equiv_cpu_table",
        "arch/x86/kernel/cpu/microcode/amd.c:parse_container"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:install_equiv_cpu_table",
        "arch/x86/kernel/cpu/microcode/amd.c:parse_container"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579228240,
      "name": "verify_equivalence_table.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
  "name": "verify_equivalence_table",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579223174,
      "name": "verify_equivalence_table",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:116",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:install_equiv_cpu_table",
        "arch/x86/kernel/cpu/microcode/amd.c:parse_container"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:install_equiv_cpu_table",
        "arch/x86/kernel/cpu/microcode/amd.c:parse_container"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579221744,
      "name": "verify_equivalence_table.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
  "name": "verify_equivalence_table",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579224454,
      "name": "verify_equivalence_table",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:116",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:scan_containers"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:scan_containers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579224256,
      "name": "verify_equivalence_table.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "verify_equivalence_table",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579263014,
      "name": "verify_equivalence_table",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:116",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:scan_containers"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:scan_containers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579262816,
      "name": "verify_equivalence_table.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
bool verify_equivalence_table(const u8 * buf, size_t buf_size, bool early)
```

```json
{
  "name": "verify_equivalence_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579313824,
      "name": "verify_equivalence_table",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:116",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:scan_containers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579313824,
      "name": "verify_equivalence_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
bool verify_equivalence_table(const u8 * buf, size_t buf_size, bool early)
```

```json
{
  "name": "verify_equivalence_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579379328,
      "name": "verify_equivalence_table",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:118",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:install_equiv_cpu_table",
        "arch/x86/kernel/cpu/microcode/amd.c:scan_containers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579379328,
      "name": "verify_equivalence_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
bool verify_equivalence_table(const u8 * buf, size_t buf_size, bool early)
```

```json
{
  "name": "verify_equivalence_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579390256,
      "name": "verify_equivalence_table",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:116",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:install_equiv_cpu_table",
        "arch/x86/kernel/cpu/microcode/amd.c:scan_containers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579390256,
      "name": "verify_equivalence_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
bool verify_equivalence_table(const u8 * buf, size_t buf_size)
```

```json
{
  "name": "verify_equivalence_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579419600,
      "name": "verify_equivalence_table",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:156",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:install_equiv_cpu_table",
        "arch/x86/kernel/cpu/microcode/amd.c:scan_containers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579419600,
      "name": "verify_equivalence_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
bool verify_equivalence_table(const u8 * buf, size_t buf_size, bool early)
```

```json
{
  "name": "verify_equivalence_table",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579206464,
      "name": "verify_equivalence_table",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:116",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:scan_containers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579206464,
      "name": "verify_equivalence_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
bool verify_equivalence_table(const u8 * buf, size_t buf_size, bool early)
```

```json
{
  "name": "verify_equivalence_table",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579141312,
      "name": "verify_equivalence_table",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:116",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:scan_containers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579141312,
      "name": "verify_equivalence_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
bool verify_equivalence_table(const u8 * buf, size_t buf_size, bool early)
```

```json
{
  "name": "verify_equivalence_table",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579207536,
      "name": "verify_equivalence_table",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:116",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:scan_containers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579207536,
      "name": "verify_equivalence_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
bool verify_equivalence_table(const u8 * buf, size_t buf_size, bool early)
```

```json
{
  "name": "verify_equivalence_table",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579212816,
      "name": "verify_equivalence_table",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:116",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:scan_containers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579212816,
      "name": "verify_equivalence_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
bool verify_equivalence_table(const u8 * buf, size_t buf_size, bool early)
```
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
bool verify_equivalence_table(const u8 * buf, size_t buf_size, bool early)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
bool verify_equivalence_table(const u8 * buf, size_t buf_size, bool early)
```
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool early</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
bool verify_equivalence_table(const u8 * buf, size_t buf_size, bool early)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
bool verify_equivalence_table(const u8 * buf, size_t buf_size, bool early)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
bool verify_equivalence_table(const u8 * buf, size_t buf_size, bool early)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
bool verify_equivalence_table(const u8 * buf, size_t buf_size, bool early)
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
