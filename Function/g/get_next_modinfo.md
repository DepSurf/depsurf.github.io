# Function: <code>get_next_modinfo</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
char * get_next_modinfo(const struct load_info * info, const char * tag, char * prev)
```

```json
{
  "name": "get_next_modinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580226016,
      "name": "get_next_modinfo",
      "external": false,
      "loc": "kernel/module.c:2541",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:resolve_symbol"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580226016,
      "name": "get_next_modinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
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
char * get_next_modinfo(const struct load_info * info, const char * tag, char * prev)
```

```json
{
  "name": "get_next_modinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580298224,
      "name": "get_next_modinfo",
      "external": false,
      "loc": "kernel/module.c:2535",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:setup_load_info",
        "kernel/module.c:resolve_symbol"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580298224,
      "name": "get_next_modinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 341
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
char * get_next_modinfo(const struct load_info * info, const char * tag, char * prev)
```

```json
{
  "name": "get_next_modinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580282688,
      "name": "get_next_modinfo",
      "external": false,
      "loc": "kernel/module.c:2622",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:setup_load_info",
        "kernel/module.c:resolve_symbol"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580282688,
      "name": "get_next_modinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 341
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
char * get_next_modinfo(const struct load_info * info, const char * tag, char * prev)
```

```json
{
  "name": "get_next_modinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580286816,
      "name": "get_next_modinfo",
      "external": false,
      "loc": "kernel/module.c:2546",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:resolve_symbol"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580286816,
      "name": "get_next_modinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 314
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
char * get_next_modinfo(const struct load_info * info, const char * tag, char * prev)
```

```json
{
  "name": "get_next_modinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580438800,
      "name": "get_next_modinfo",
      "external": false,
      "loc": "kernel/module.c:2548",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:resolve_symbol"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580438800,
      "name": "get_next_modinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 314
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
char * get_next_modinfo(const struct load_info * info, const char * tag, char * prev)
```

```json
{
  "name": "get_next_modinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580466416,
      "name": "get_next_modinfo",
      "external": false,
      "loc": "kernel/module/main.c:1543",
      "file": "kernel/module/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/main.c:load_module",
        "kernel/module/main.c:load_module",
        "kernel/module/main.c:check_modinfo",
        "kernel/module/main.c:check_modinfo",
        "kernel/module/main.c:check_modinfo",
        "kernel/module/main.c:check_modinfo",
        "kernel/module/main.c:check_modinfo",
        "kernel/module/main.c:check_modinfo",
        "kernel/module/main.c:resolve_symbol"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580466416,
      "name": "get_next_modinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 301
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
char * get_next_modinfo(const struct load_info * info, const char * tag, char * prev)
```

```json
{
  "name": "get_next_modinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580714000,
      "name": "get_next_modinfo",
      "external": false,
      "loc": "kernel/module/main.c:1541",
      "file": "kernel/module/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/main.c:load_module",
        "kernel/module/main.c:load_module",
        "kernel/module/main.c:check_modinfo",
        "kernel/module/main.c:check_modinfo",
        "kernel/module/main.c:check_modinfo",
        "kernel/module/main.c:check_modinfo",
        "kernel/module/main.c:check_modinfo",
        "kernel/module/main.c:check_modinfo",
        "kernel/module/main.c:check_modinfo",
        "kernel/module/main.c:resolve_symbol"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580714000,
      "name": "get_next_modinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 301
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
char * get_next_modinfo(const struct load_info * info, const char * tag, char * prev)
```

```json
{
  "name": "get_next_modinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580794240,
      "name": "get_next_modinfo",
      "external": false,
      "loc": "kernel/module/main.c:1031",
      "file": "kernel/module/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/main.c:load_module",
        "kernel/module/main.c:early_mod_check",
        "kernel/module/main.c:early_mod_check",
        "kernel/module/main.c:module_augment_kernel_taints",
        "kernel/module/main.c:module_augment_kernel_taints",
        "kernel/module/main.c:module_augment_kernel_taints",
        "kernel/module/main.c:module_augment_kernel_taints",
        "kernel/module/main.c:module_augment_kernel_taints",
        "kernel/module/main.c:elf_validity_cache_copy",
        "kernel/module/main.c:resolve_symbol"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580794240,
      "name": "get_next_modinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 301
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
char * get_next_modinfo(const struct load_info * info, const char * tag, char * prev)
```

```json
{
  "name": "get_next_modinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580883920,
      "name": "get_next_modinfo",
      "external": false,
      "loc": "kernel/module/main.c:1031",
      "file": "kernel/module/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/main.c:load_module",
        "kernel/module/main.c:early_mod_check",
        "kernel/module/main.c:early_mod_check",
        "kernel/module/main.c:module_augment_kernel_taints",
        "kernel/module/main.c:module_augment_kernel_taints",
        "kernel/module/main.c:module_augment_kernel_taints",
        "kernel/module/main.c:module_augment_kernel_taints",
        "kernel/module/main.c:module_augment_kernel_taints",
        "kernel/module/main.c:elf_validity_cache_copy",
        "kernel/module/main.c:resolve_symbol"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580883920,
      "name": "get_next_modinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 301
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
char * get_next_modinfo(const struct load_info * info, const char * tag, char * prev)
```

```json
{
  "name": "get_next_modinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491467008,
      "name": "get_next_modinfo",
      "external": false,
      "loc": "kernel/module.c:2541",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:resolve_symbol",
        "kernel/module.c:resolve_symbol"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491467008,
      "name": "get_next_modinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 404
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
char * get_next_modinfo(const struct load_info * info, const char * tag, char * prev)
```

```json
{
  "name": "get_next_modinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225450484,
      "name": "get_next_modinfo",
      "external": false,
      "loc": "kernel/module.c:2541",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:resolve_symbol",
        "kernel/module.c:resolve_symbol"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225450484,
      "name": "get_next_modinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 360
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
char * get_next_modinfo(const struct load_info * info, const char * tag, char * prev)
```

```json
{
  "name": "get_next_modinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284415888,
      "name": "get_next_modinfo",
      "external": false,
      "loc": "kernel/module.c:2541",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:resolve_symbol",
        "kernel/module.c:resolve_symbol"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284415888,
      "name": "get_next_modinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 608
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
char * get_next_modinfo(const struct load_info * info, const char * tag, char * prev)
```

```json
{
  "name": "get_next_modinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271918342,
      "name": "get_next_modinfo",
      "external": false,
      "loc": "kernel/module.c:2541",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:resolve_symbol",
        "kernel/module.c:resolve_symbol"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271918342,
      "name": "get_next_modinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
char * get_next_modinfo(const struct load_info * info, const char * tag, char * prev)
```

```json
{
  "name": "get_next_modinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580194816,
      "name": "get_next_modinfo",
      "external": false,
      "loc": "kernel/module.c:2541",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:resolve_symbol"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580194816,
      "name": "get_next_modinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
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
char * get_next_modinfo(const struct load_info * info, const char * tag, char * prev)
```

```json
{
  "name": "get_next_modinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580142256,
      "name": "get_next_modinfo",
      "external": false,
      "loc": "kernel/module.c:2541",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:resolve_symbol"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580142256,
      "name": "get_next_modinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
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
char * get_next_modinfo(const struct load_info * info, const char * tag, char * prev)
```

```json
{
  "name": "get_next_modinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580186288,
      "name": "get_next_modinfo",
      "external": false,
      "loc": "kernel/module.c:2541",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:resolve_symbol"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580186288,
      "name": "get_next_modinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
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
char * get_next_modinfo(const struct load_info * info, const char * tag, char * prev)
```

```json
{
  "name": "get_next_modinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580238528,
      "name": "get_next_modinfo",
      "external": false,
      "loc": "kernel/module.c:2541",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:resolve_symbol"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580238528,
      "name": "get_next_modinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
char * get_next_modinfo(const struct load_info * info, const char * tag, char * prev)
```
</details>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
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
