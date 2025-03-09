# Function: <code>add_e820_entry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "add_e820_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579226636,
      "name": "add_e820_entry",
      "external": false,
      "loc": "arch/x86/kernel/crash.c:514",
      "file": "arch/x86/kernel/crash.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:memmap_entry_callback",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "add_e820_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579228319,
      "name": "add_e820_entry",
      "external": false,
      "loc": "arch/x86/kernel/crash.c:490",
      "file": "arch/x86/kernel/crash.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:memmap_entry_callback"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "add_e820_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579240735,
      "name": "add_e820_entry",
      "external": false,
      "loc": "arch/x86/kernel/crash.c:506",
      "file": "arch/x86/kernel/crash.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:memmap_entry_callback"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int add_e820_entry(struct boot_params * params, struct e820_entry * entry)
```

```json
{
  "name": "add_e820_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579235280,
      "name": "add_e820_entry",
      "external": false,
      "loc": "arch/x86/kernel/crash.c:507",
      "file": "arch/x86/kernel/crash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:memmap_entry_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579235280,
      "name": "add_e820_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
int add_e820_entry(struct boot_params * params, struct e820_entry * entry)
```

```json
{
  "name": "add_e820_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579251680,
      "name": "add_e820_entry",
      "external": false,
      "loc": "arch/x86/kernel/crash.c:507",
      "file": "arch/x86/kernel/crash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:memmap_entry_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579251680,
      "name": "add_e820_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
int add_e820_entry(struct boot_params * params, struct e820_entry * entry)
```

```json
{
  "name": "add_e820_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579263568,
      "name": "add_e820_entry",
      "external": false,
      "loc": "arch/x86/kernel/crash.c:298",
      "file": "arch/x86/kernel/crash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:memmap_entry_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579263568,
      "name": "add_e820_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
int add_e820_entry(struct boot_params * params, struct e820_entry * entry)
```

```json
{
  "name": "add_e820_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579288144,
      "name": "add_e820_entry",
      "external": false,
      "loc": "arch/x86/kernel/crash.c:299",
      "file": "arch/x86/kernel/crash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:memmap_entry_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579288144,
      "name": "add_e820_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int add_e820_entry(struct boot_params * params, struct e820_entry * entry)
```

```json
{
  "name": "add_e820_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579304528,
      "name": "add_e820_entry",
      "external": false,
      "loc": "arch/x86/kernel/crash.c:293",
      "file": "arch/x86/kernel/crash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:memmap_entry_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579304528,
      "name": "add_e820_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
int add_e820_entry(struct boot_params * params, struct e820_entry * entry)
```

```json
{
  "name": "add_e820_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579308624,
      "name": "add_e820_entry",
      "external": false,
      "loc": "arch/x86/kernel/crash.c:291",
      "file": "arch/x86/kernel/crash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:memmap_entry_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579308624,
      "name": "add_e820_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
  "name": "add_e820_entry",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579337673,
      "name": "add_e820_entry",
      "external": false,
      "loc": "arch/x86/kernel/crash.c:288",
      "file": "arch/x86/kernel/crash.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:memmap_entry_callback"
      ],
      "caller_func": [
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579337600,
      "name": "add_e820_entry.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
  "name": "add_e820_entry",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579337673,
      "name": "add_e820_entry",
      "external": false,
      "loc": "arch/x86/kernel/crash.c:288",
      "file": "arch/x86/kernel/crash.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:memmap_entry_callback"
      ],
      "caller_func": [
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579337600,
      "name": "add_e820_entry.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
  "name": "add_e820_entry",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579341417,
      "name": "add_e820_entry",
      "external": false,
      "loc": "arch/x86/kernel/crash.c:288",
      "file": "arch/x86/kernel/crash.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:memmap_entry_callback"
      ],
      "caller_func": [
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579341344,
      "name": "add_e820_entry.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
  "name": "add_e820_entry",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579398821,
      "name": "add_e820_entry",
      "external": false,
      "loc": "arch/x86/kernel/crash.c:275",
      "file": "arch/x86/kernel/crash.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:memmap_entry_callback"
      ],
      "caller_func": [
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579398688,
      "name": "add_e820_entry.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "add_e820_entry",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579464889,
      "name": "add_e820_entry",
      "external": false,
      "loc": "arch/x86/kernel/crash.c:275",
      "file": "arch/x86/kernel/crash.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:memmap_entry_callback"
      ],
      "caller_func": [
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579464336,
      "name": "add_e820_entry.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
  "name": "add_e820_entry",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579555984,
      "name": "add_e820_entry",
      "external": false,
      "loc": "arch/x86/kernel/crash.c:260",
      "file": "arch/x86/kernel/crash.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:memmap_entry_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579555984,
      "name": "add_e820_entry.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
  "name": "add_e820_entry",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579568272,
      "name": "add_e820_entry",
      "external": false,
      "loc": "arch/x86/kernel/crash.c:260",
      "file": "arch/x86/kernel/crash.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:memmap_entry_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579568272,
      "name": "add_e820_entry.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
  "name": "add_e820_entry",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579597392,
      "name": "add_e820_entry",
      "external": false,
      "loc": "arch/x86/kernel/crash.c:233",
      "file": "arch/x86/kernel/crash.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:memmap_entry_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579597392,
      "name": "add_e820_entry.isra.0",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int add_e820_entry(struct boot_params * params, struct e820_entry * entry)
```

```json
{
  "name": "add_e820_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579304528,
      "name": "add_e820_entry",
      "external": false,
      "loc": "arch/x86/kernel/crash.c:291",
      "file": "arch/x86/kernel/crash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:memmap_entry_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579304528,
      "name": "add_e820_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
int add_e820_entry(struct boot_params * params, struct e820_entry * entry)
```

```json
{
  "name": "add_e820_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579238992,
      "name": "add_e820_entry",
      "external": false,
      "loc": "arch/x86/kernel/crash.c:291",
      "file": "arch/x86/kernel/crash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:memmap_entry_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579238992,
      "name": "add_e820_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
int add_e820_entry(struct boot_params * params, struct e820_entry * entry)
```

```json
{
  "name": "add_e820_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579304528,
      "name": "add_e820_entry",
      "external": false,
      "loc": "arch/x86/kernel/crash.c:291",
      "file": "arch/x86/kernel/crash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:memmap_entry_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579304528,
      "name": "add_e820_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
int add_e820_entry(struct boot_params * params, struct e820_entry * entry)
```

```json
{
  "name": "add_e820_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579312720,
      "name": "add_e820_entry",
      "external": false,
      "loc": "arch/x86/kernel/crash.c:291",
      "file": "arch/x86/kernel/crash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:memmap_entry_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579312720,
      "name": "add_e820_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int add_e820_entry(struct boot_params * params, struct e820_entry * entry)
```
</details>
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
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int add_e820_entry(struct boot_params * params, struct e820_entry * entry)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int add_e820_entry(struct boot_params * params, struct e820_entry * entry)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int add_e820_entry(struct boot_params * params, struct e820_entry * entry)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int add_e820_entry(struct boot_params * params, struct e820_entry * entry)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int add_e820_entry(struct boot_params * params, struct e820_entry * entry)
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
