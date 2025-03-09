# Function: <code>e820__range_remove</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
u64 e820__range_remove(u64 start, u64 size, enum e820_type old_type, bool check_type)
```

```json
{
  "name": "e820__range_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596324833,
      "name": "e820__range_remove",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:491",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596324833,
      "name": "e820__range_remove",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 335
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
u64 e820__range_remove(u64 start, u64 size, enum e820_type old_type, bool check_type)
```

```json
{
  "name": "e820__range_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071602642871,
      "name": "e820__range_remove",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:511",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602642871,
      "name": "e820__range_remove",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 335
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
u64 e820__range_remove(u64 start, u64 size, enum e820_type old_type, bool check_type)
```

```json
{
  "name": "e820__range_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071602812547,
      "name": "e820__range_remove",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:513",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602812547,
      "name": "e820__range_remove",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 331
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
u64 e820__range_remove(u64 start, u64 size, enum e820_type old_type, bool check_type)
```

```json
{
  "name": "e820__range_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604607594,
      "name": "e820__range_remove",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:512",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604607594,
      "name": "e820__range_remove",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 331
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
u64 e820__range_remove(u64 start, u64 size, enum e820_type old_type, bool check_type)
```

```json
{
  "name": "e820__range_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604703175,
      "name": "e820__range_remove",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:526",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604703175,
      "name": "e820__range_remove",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 318
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
u64 e820__range_remove(u64 start, u64 size, enum e820_type old_type, bool check_type)
```

```json
{
  "name": "e820__range_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604715563,
      "name": "e820__range_remove",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:526",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604715563,
      "name": "e820__range_remove",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 318
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
u64 e820__range_remove(u64 start, u64 size, enum e820_type old_type, bool check_type)
```

```json
{
  "name": "e820__range_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609062203,
      "name": "e820__range_remove",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:527",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:parse_memopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609062203,
      "name": "e820__range_remove",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 318
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
u64 e820__range_remove(u64 start, u64 size, enum e820_type old_type, bool check_type)
```

```json
{
  "name": "e820__range_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612125579,
      "name": "e820__range_remove",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:541",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:parse_memopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612125579,
      "name": "e820__range_remove",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 318
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
u64 e820__range_remove(u64 start, u64 size, enum e820_type old_type, bool check_type)
```

```json
{
  "name": "e820__range_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614265500,
      "name": "e820__range_remove",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:541",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:parse_memopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614265500,
      "name": "e820__range_remove",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 321
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
u64 e820__range_remove(u64 start, u64 size, enum e820_type old_type, bool check_type)
```

```json
{
  "name": "e820__range_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615187587,
      "name": "e820__range_remove",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:541",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:parse_memopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615187587,
      "name": "e820__range_remove",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 321
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
u64 e820__range_remove(u64 start, u64 size, enum e820_type old_type, bool check_type)
```

```json
{
  "name": "e820__range_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071616954482,
      "name": "e820__range_remove",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:541",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:parse_memopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071616954482,
      "name": "e820__range_remove",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 356
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
u64 e820__range_remove(u64 start, u64 size, enum e820_type old_type, bool check_type)
```

```json
{
  "name": "e820__range_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071627567312,
      "name": "e820__range_remove",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:541",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:parse_memopt",
        "arch/x86/platform/efi/efi.c:efi_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627567312,
      "name": "e820__range_remove",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 515
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
u64 e820__range_remove(u64 start, u64 size, enum e820_type old_type, bool check_type)
```

```json
{
  "name": "e820__range_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619318064,
      "name": "e820__range_remove",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:541",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:parse_memopt",
        "arch/x86/platform/efi/efi.c:efi_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619318064,
      "name": "e820__range_remove",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 871
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
u64 e820__range_remove(u64 start, u64 size, enum e820_type old_type, bool check_type)
```

```json
{
  "name": "e820__range_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071621611184,
      "name": "e820__range_remove",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:541",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:parse_memopt",
        "arch/x86/platform/efi/efi.c:efi_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071621611184,
      "name": "e820__range_remove",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 871
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
u64 e820__range_remove(u64 start, u64 size, enum e820_type old_type, bool check_type)
```

```json
{
  "name": "e820__range_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604641853,
      "name": "e820__range_remove",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:526",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604641853,
      "name": "e820__range_remove",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 318
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
u64 e820__range_remove(u64 start, u64 size, enum e820_type old_type, bool check_type)
```

```json
{
  "name": "e820__range_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604609787,
      "name": "e820__range_remove",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:526",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604609787,
      "name": "e820__range_remove",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 318
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
u64 e820__range_remove(u64 start, u64 size, enum e820_type old_type, bool check_type)
```

```json
{
  "name": "e820__range_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604719645,
      "name": "e820__range_remove",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:526",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604719645,
      "name": "e820__range_remove",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 318
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
u64 e820__range_remove(u64 start, u64 size, enum e820_type old_type, bool check_type)
```

```json
{
  "name": "e820__range_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604719675,
      "name": "e820__range_remove",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:526",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604719675,
      "name": "e820__range_remove",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 318
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
u64 e820__range_remove(u64 start, u64 size, enum e820_type old_type, bool check_type)
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
u64 e820__range_remove(u64 start, u64 size, enum e820_type old_type, bool check_type)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
u64 e820__range_remove(u64 start, u64 size, enum e820_type old_type, bool check_type)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
u64 e820__range_remove(u64 start, u64 size, enum e820_type old_type, bool check_type)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
u64 e820__range_remove(u64 start, u64 size, enum e820_type old_type, bool check_type)
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
