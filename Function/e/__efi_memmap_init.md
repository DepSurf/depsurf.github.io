# Function: <code>__efi_memmap_init</code>

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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __efi_memmap_init(struct efi_memory_map_data * data, bool late)
```

```json
{
  "name": "__efi_memmap_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595762734,
      "name": "__efi_memmap_init",
      "external": false,
      "loc": "drivers/firmware/efi/memmap.c:68",
      "file": "drivers/firmware/efi/memmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/memmap.c:efi_memmap_install",
        "drivers/firmware/efi/memmap.c:efi_memmap_init_late",
        "drivers/firmware/efi/memmap.c:efi_memmap_init_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595762734,
      "name": "__efi_memmap_init",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 174
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __efi_memmap_init(struct efi_memory_map_data * data, bool late)
```

```json
{
  "name": "__efi_memmap_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596691799,
      "name": "__efi_memmap_init",
      "external": false,
      "loc": "drivers/firmware/efi/memmap.c:68",
      "file": "drivers/firmware/efi/memmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/memmap.c:efi_memmap_install",
        "drivers/firmware/efi/memmap.c:efi_memmap_init_late",
        "drivers/firmware/efi/memmap.c:efi_memmap_init_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596691799,
      "name": "__efi_memmap_init",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 180
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __efi_memmap_init(struct efi_memory_map_data * data, bool late)
```

```json
{
  "name": "__efi_memmap_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071603021856,
      "name": "__efi_memmap_init",
      "external": false,
      "loc": "drivers/firmware/efi/memmap.c:69",
      "file": "drivers/firmware/efi/memmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/memmap.c:efi_memmap_install",
        "drivers/firmware/efi/memmap.c:efi_memmap_init_late",
        "drivers/firmware/efi/memmap.c:efi_memmap_init_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071603021856,
      "name": "__efi_memmap_init",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 180
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
int __efi_memmap_init(struct efi_memory_map_data * data, bool late)
```

```json
{
  "name": "__efi_memmap_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071603194591,
      "name": "__efi_memmap_init",
      "external": false,
      "loc": "drivers/firmware/efi/memmap.c:69",
      "file": "drivers/firmware/efi/memmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/memmap.c:efi_memmap_install",
        "drivers/firmware/efi/memmap.c:efi_memmap_init_late",
        "drivers/firmware/efi/memmap.c:efi_memmap_init_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071603194591,
      "name": "__efi_memmap_init",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 180
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
int __efi_memmap_init(struct efi_memory_map_data * data, bool late)
```

```json
{
  "name": "__efi_memmap_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605004939,
      "name": "__efi_memmap_init",
      "external": false,
      "loc": "drivers/firmware/efi/memmap.c:69",
      "file": "drivers/firmware/efi/memmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/memmap.c:efi_memmap_install",
        "drivers/firmware/efi/memmap.c:efi_memmap_init_late",
        "drivers/firmware/efi/memmap.c:efi_memmap_init_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605004939,
      "name": "__efi_memmap_init",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 180
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
int __efi_memmap_init(struct efi_memory_map_data * data, bool late)
```

```json
{
  "name": "__efi_memmap_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605117816,
      "name": "__efi_memmap_init",
      "external": false,
      "loc": "drivers/firmware/efi/memmap.c:69",
      "file": "drivers/firmware/efi/memmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/memmap.c:efi_memmap_install",
        "drivers/firmware/efi/memmap.c:efi_memmap_init_late",
        "drivers/firmware/efi/memmap.c:efi_memmap_init_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605117816,
      "name": "__efi_memmap_init",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 184
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
int __efi_memmap_init(struct efi_memory_map_data * data, bool late)
```

```json
{
  "name": "__efi_memmap_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605157265,
      "name": "__efi_memmap_init",
      "external": false,
      "loc": "drivers/firmware/efi/memmap.c:69",
      "file": "drivers/firmware/efi/memmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/memmap.c:efi_memmap_install",
        "drivers/firmware/efi/memmap.c:efi_memmap_init_late",
        "drivers/firmware/efi/memmap.c:efi_memmap_init_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605157265,
      "name": "__efi_memmap_init",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 184
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
int __efi_memmap_init(struct efi_memory_map_data * data)
```

```json
{
  "name": "__efi_memmap_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609427216,
      "name": "__efi_memmap_init",
      "external": false,
      "loc": "drivers/firmware/efi/memmap.c:105",
      "file": "drivers/firmware/efi/memmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/memmap.c:efi_memmap_install",
        "drivers/firmware/efi/memmap.c:efi_memmap_init_late",
        "drivers/firmware/efi/memmap.c:efi_memmap_init_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609427216,
      "name": "__efi_memmap_init",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 226
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
int __efi_memmap_init(struct efi_memory_map_data * data)
```

```json
{
  "name": "__efi_memmap_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612501034,
      "name": "__efi_memmap_init",
      "external": false,
      "loc": "drivers/firmware/efi/memmap.c:105",
      "file": "drivers/firmware/efi/memmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/memmap.c:efi_memmap_install",
        "drivers/firmware/efi/memmap.c:efi_memmap_init_late",
        "drivers/firmware/efi/memmap.c:efi_memmap_init_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612501034,
      "name": "__efi_memmap_init",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 226
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
int __efi_memmap_init(struct efi_memory_map_data * data)
```

```json
{
  "name": "__efi_memmap_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614643234,
      "name": "__efi_memmap_init",
      "external": false,
      "loc": "drivers/firmware/efi/memmap.c:105",
      "file": "drivers/firmware/efi/memmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/memmap.c:efi_memmap_install",
        "drivers/firmware/efi/memmap.c:efi_memmap_init_late",
        "drivers/firmware/efi/memmap.c:efi_memmap_init_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614643234,
      "name": "__efi_memmap_init",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 226
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
int __efi_memmap_init(struct efi_memory_map_data * data)
```

```json
{
  "name": "__efi_memmap_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615601192,
      "name": "__efi_memmap_init",
      "external": false,
      "loc": "drivers/firmware/efi/memmap.c:105",
      "file": "drivers/firmware/efi/memmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/memmap.c:efi_memmap_install",
        "drivers/firmware/efi/memmap.c:efi_memmap_init_late",
        "drivers/firmware/efi/memmap.c:efi_memmap_init_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615601192,
      "name": "__efi_memmap_init",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 226
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
int __efi_memmap_init(struct efi_memory_map_data * data)
```

```json
{
  "name": "__efi_memmap_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617410979,
      "name": "__efi_memmap_init",
      "external": false,
      "loc": "drivers/firmware/efi/memmap.c:105",
      "file": "drivers/firmware/efi/memmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/memmap.c:efi_memmap_install",
        "drivers/firmware/efi/memmap.c:efi_memmap_init_late",
        "drivers/firmware/efi/memmap.c:efi_memmap_init_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617410979,
      "name": "__efi_memmap_init",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 249
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
int __efi_memmap_init(struct efi_memory_map_data * data)
```

```json
{
  "name": "__efi_memmap_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071628163072,
      "name": "__efi_memmap_init",
      "external": true,
      "loc": "drivers/firmware/efi/memmap.c:37",
      "file": "drivers/firmware/efi/memmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/efi/memmap.c:efi_memmap_install",
        "drivers/firmware/efi/memmap.c:efi_memmap_init_late",
        "drivers/firmware/efi/memmap.c:efi_memmap_init_early",
        "drivers/firmware/efi/memmap.c:efi_memmap_init_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071628163072,
      "name": "__efi_memmap_init",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 232
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
int __efi_memmap_init(struct efi_memory_map_data * data)
```

```json
{
  "name": "__efi_memmap_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619930432,
      "name": "__efi_memmap_init",
      "external": true,
      "loc": "drivers/firmware/efi/memmap.c:37",
      "file": "drivers/firmware/efi/memmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/efi/memmap.c:efi_memmap_install",
        "drivers/firmware/efi/memmap.c:efi_memmap_init_late",
        "drivers/firmware/efi/memmap.c:efi_memmap_init_early",
        "drivers/firmware/efi/memmap.c:efi_memmap_init_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619930432,
      "name": "__efi_memmap_init",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 232
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
int __efi_memmap_init(struct efi_memory_map_data * data)
```

```json
{
  "name": "__efi_memmap_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071622241600,
      "name": "__efi_memmap_init",
      "external": true,
      "loc": "drivers/firmware/efi/memmap.c:37",
      "file": "drivers/firmware/efi/memmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/efi/memmap.c:efi_memmap_install",
        "drivers/firmware/efi/memmap.c:efi_memmap_init_late",
        "drivers/firmware/efi/memmap.c:efi_memmap_init_early",
        "drivers/firmware/efi/memmap.c:efi_memmap_init_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071622241600,
      "name": "__efi_memmap_init",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 232
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int __efi_memmap_init(struct efi_memory_map_data * data, bool late)
```

```json
{
  "name": "__efi_memmap_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336511284820,
      "name": "__efi_memmap_init",
      "external": false,
      "loc": "drivers/firmware/efi/memmap.c:69",
      "file": "drivers/firmware/efi/memmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/memmap.c:efi_memmap_install",
        "drivers/firmware/efi/memmap.c:efi_memmap_init_late",
        "drivers/firmware/efi/memmap.c:efi_memmap_init_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336511284820,
      "name": "__efi_memmap_init",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 236
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int __efi_memmap_init(struct efi_memory_map_data * data, bool late)
```

```json
{
  "name": "__efi_memmap_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3243936260,
      "name": "__efi_memmap_init",
      "external": false,
      "loc": "drivers/firmware/efi/memmap.c:69",
      "file": "drivers/firmware/efi/memmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/memmap.c:efi_memmap_install",
        "drivers/firmware/efi/memmap.c:efi_memmap_init_late",
        "drivers/firmware/efi/memmap.c:efi_memmap_init_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3243936260,
      "name": "__efi_memmap_init",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 220
    }
  ]
}
```
</details>
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
int __efi_memmap_init(struct efi_memory_map_data * data, bool late)
```

```json
{
  "name": "__efi_memmap_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605047703,
      "name": "__efi_memmap_init",
      "external": false,
      "loc": "drivers/firmware/efi/memmap.c:69",
      "file": "drivers/firmware/efi/memmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/memmap.c:efi_memmap_install",
        "drivers/firmware/efi/memmap.c:efi_memmap_init_late",
        "drivers/firmware/efi/memmap.c:efi_memmap_init_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605047703,
      "name": "__efi_memmap_init",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 184
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
int __efi_memmap_init(struct efi_memory_map_data * data, bool late)
```

```json
{
  "name": "__efi_memmap_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605013043,
      "name": "__efi_memmap_init",
      "external": false,
      "loc": "drivers/firmware/efi/memmap.c:69",
      "file": "drivers/firmware/efi/memmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/memmap.c:efi_memmap_install",
        "drivers/firmware/efi/memmap.c:efi_memmap_init_late",
        "drivers/firmware/efi/memmap.c:efi_memmap_init_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605013043,
      "name": "__efi_memmap_init",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 184
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
int __efi_memmap_init(struct efi_memory_map_data * data, bool late)
```

```json
{
  "name": "__efi_memmap_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605134278,
      "name": "__efi_memmap_init",
      "external": false,
      "loc": "drivers/firmware/efi/memmap.c:69",
      "file": "drivers/firmware/efi/memmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/memmap.c:efi_memmap_install",
        "drivers/firmware/efi/memmap.c:efi_memmap_init_late",
        "drivers/firmware/efi/memmap.c:efi_memmap_init_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605134278,
      "name": "__efi_memmap_init",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 184
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
int __efi_memmap_init(struct efi_memory_map_data * data, bool late)
```

```json
{
  "name": "__efi_memmap_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605161459,
      "name": "__efi_memmap_init",
      "external": false,
      "loc": "drivers/firmware/efi/memmap.c:69",
      "file": "drivers/firmware/efi/memmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/memmap.c:efi_memmap_install",
        "drivers/firmware/efi/memmap.c:efi_memmap_init_late",
        "drivers/firmware/efi/memmap.c:efi_memmap_init_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605161459,
      "name": "__efi_memmap_init",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 184
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
int __efi_memmap_init(struct efi_memory_map_data * data, bool late)
```
</details>
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
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool late</code>
</li>
</ul>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int __efi_memmap_init(struct efi_memory_map_data * data, bool late)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int __efi_memmap_init(struct efi_memory_map_data * data, bool late)
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
