# Function: <code>find_kallsyms_symbol</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
const char * find_kallsyms_symbol(struct module * mod, long unsigned int addr, long unsigned int * size, long unsigned int * offset)
```

```json
{
  "name": "find_kallsyms_symbol",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580131888,
      "name": "find_kallsyms_symbol",
      "external": false,
      "loc": "kernel/module.c:3958",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:lookup_module_symbol_attrs",
        "kernel/module.c:lookup_module_symbol_name",
        "kernel/module.c:module_address_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580131888,
      "name": "find_kallsyms_symbol",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 390
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
const char * find_kallsyms_symbol(struct module * mod, long unsigned int addr, long unsigned int * size, long unsigned int * offset)
```

```json
{
  "name": "find_kallsyms_symbol",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580178752,
      "name": "find_kallsyms_symbol",
      "external": false,
      "loc": "kernel/module.c:3986",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:lookup_module_symbol_attrs",
        "kernel/module.c:lookup_module_symbol_name",
        "kernel/module.c:module_address_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580178752,
      "name": "find_kallsyms_symbol",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 420
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
const char * find_kallsyms_symbol(struct module * mod, long unsigned int addr, long unsigned int * size, long unsigned int * offset)
```

```json
{
  "name": "find_kallsyms_symbol",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580226752,
      "name": "find_kallsyms_symbol",
      "external": false,
      "loc": "kernel/module.c:4053",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:lookup_module_symbol_attrs",
        "kernel/module.c:lookup_module_symbol_name",
        "kernel/module.c:module_address_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580226752,
      "name": "find_kallsyms_symbol",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 420
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
const char * find_kallsyms_symbol(struct module * mod, long unsigned int addr, long unsigned int * size, long unsigned int * offset)
```

```json
{
  "name": "find_kallsyms_symbol",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580293856,
      "name": "find_kallsyms_symbol",
      "external": false,
      "loc": "kernel/module.c:4060",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:lookup_module_symbol_attrs",
        "kernel/module.c:lookup_module_symbol_name",
        "kernel/module.c:module_address_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580293856,
      "name": "find_kallsyms_symbol",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 397
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
const char * find_kallsyms_symbol(struct module * mod, long unsigned int addr, long unsigned int * size, long unsigned int * offset)
```

```json
{
  "name": "find_kallsyms_symbol",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580277744,
      "name": "find_kallsyms_symbol",
      "external": false,
      "loc": "kernel/module.c:4285",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:lookup_module_symbol_attrs",
        "kernel/module.c:lookup_module_symbol_name",
        "kernel/module.c:module_address_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580277744,
      "name": "find_kallsyms_symbol",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 397
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
const char * find_kallsyms_symbol(struct module * mod, long unsigned int addr, long unsigned int * size, long unsigned int * offset)
```

```json
{
  "name": "find_kallsyms_symbol",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580282032,
      "name": "find_kallsyms_symbol",
      "external": false,
      "loc": "kernel/module.c:4189",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:lookup_module_symbol_attrs",
        "kernel/module.c:lookup_module_symbol_name",
        "kernel/module.c:module_address_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580282032,
      "name": "find_kallsyms_symbol",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 396
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
const char * find_kallsyms_symbol(struct module * mod, long unsigned int addr, long unsigned int * size, long unsigned int * offset)
```

```json
{
  "name": "find_kallsyms_symbol",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580433792,
      "name": "find_kallsyms_symbol",
      "external": false,
      "loc": "kernel/module.c:4202",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:lookup_module_symbol_attrs",
        "kernel/module.c:lookup_module_symbol_name",
        "kernel/module.c:module_address_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580433792,
      "name": "find_kallsyms_symbol",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 396
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
const char * find_kallsyms_symbol(struct module * mod, long unsigned int addr, long unsigned int * size, long unsigned int * offset)
```

```json
{
  "name": "find_kallsyms_symbol",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580487424,
      "name": "find_kallsyms_symbol",
      "external": false,
      "loc": "kernel/module/kallsyms.c:262",
      "file": "kernel/module/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/kallsyms.c:lookup_module_symbol_attrs",
        "kernel/module/kallsyms.c:lookup_module_symbol_name",
        "kernel/module/kallsyms.c:module_address_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580487424,
      "name": "find_kallsyms_symbol",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 482
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
const char * find_kallsyms_symbol(struct module * mod, long unsigned int addr, long unsigned int * size, long unsigned int * offset)
```

```json
{
  "name": "find_kallsyms_symbol",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580738832,
      "name": "find_kallsyms_symbol",
      "external": false,
      "loc": "kernel/module/kallsyms.c:262",
      "file": "kernel/module/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/kallsyms.c:lookup_module_symbol_attrs",
        "kernel/module/kallsyms.c:lookup_module_symbol_name",
        "kernel/module/kallsyms.c:module_address_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580738832,
      "name": "find_kallsyms_symbol",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 482
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
const char * find_kallsyms_symbol(struct module * mod, long unsigned int addr, long unsigned int * size, long unsigned int * offset)
```

```json
{
  "name": "find_kallsyms_symbol",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580821152,
      "name": "find_kallsyms_symbol",
      "external": false,
      "loc": "kernel/module/kallsyms.c:256",
      "file": "kernel/module/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/kallsyms.c:lookup_module_symbol_name",
        "kernel/module/kallsyms.c:module_address_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580821152,
      "name": "find_kallsyms_symbol",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 578
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
const char * find_kallsyms_symbol(struct module * mod, long unsigned int addr, long unsigned int * size, long unsigned int * offset)
```

```json
{
  "name": "find_kallsyms_symbol",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580910640,
      "name": "find_kallsyms_symbol",
      "external": false,
      "loc": "kernel/module/kallsyms.c:256",
      "file": "kernel/module/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/kallsyms.c:lookup_module_symbol_name",
        "kernel/module/kallsyms.c:module_address_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580910640,
      "name": "find_kallsyms_symbol",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 531
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
const char * find_kallsyms_symbol(struct module * mod, long unsigned int addr, long unsigned int * size, long unsigned int * offset)
```

```json
{
  "name": "find_kallsyms_symbol",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491467976,
      "name": "find_kallsyms_symbol",
      "external": false,
      "loc": "kernel/module.c:4053",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:lookup_module_symbol_attrs",
        "kernel/module.c:lookup_module_symbol_name",
        "kernel/module.c:module_address_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491467976,
      "name": "find_kallsyms_symbol",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 480
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
const char * find_kallsyms_symbol(struct module * mod, long unsigned int addr, long unsigned int * size, long unsigned int * offset)
```

```json
{
  "name": "find_kallsyms_symbol",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225451252,
      "name": "find_kallsyms_symbol",
      "external": false,
      "loc": "kernel/module.c:4053",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:lookup_module_symbol_attrs",
        "kernel/module.c:lookup_module_symbol_name",
        "kernel/module.c:module_address_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225451252,
      "name": "find_kallsyms_symbol",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 444
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
const char * find_kallsyms_symbol(struct module * mod, long unsigned int addr, long unsigned int * size, long unsigned int * offset)
```

```json
{
  "name": "find_kallsyms_symbol",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284417152,
      "name": "find_kallsyms_symbol",
      "external": false,
      "loc": "kernel/module.c:4053",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:lookup_module_symbol_attrs",
        "kernel/module.c:lookup_module_symbol_name",
        "kernel/module.c:module_address_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284417152,
      "name": "find_kallsyms_symbol",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 680
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
const char * find_kallsyms_symbol(struct module * mod, long unsigned int addr, long unsigned int * size, long unsigned int * offset)
```

```json
{
  "name": "find_kallsyms_symbol",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271919214,
      "name": "find_kallsyms_symbol",
      "external": false,
      "loc": "kernel/module.c:4053",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:lookup_module_symbol_attrs",
        "kernel/module.c:lookup_module_symbol_name",
        "kernel/module.c:module_address_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271919214,
      "name": "find_kallsyms_symbol",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 384
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
const char * find_kallsyms_symbol(struct module * mod, long unsigned int addr, long unsigned int * size, long unsigned int * offset)
```

```json
{
  "name": "find_kallsyms_symbol",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580195552,
      "name": "find_kallsyms_symbol",
      "external": false,
      "loc": "kernel/module.c:4053",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:lookup_module_symbol_attrs",
        "kernel/module.c:lookup_module_symbol_name",
        "kernel/module.c:module_address_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580195552,
      "name": "find_kallsyms_symbol",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 420
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
const char * find_kallsyms_symbol(struct module * mod, long unsigned int addr, long unsigned int * size, long unsigned int * offset)
```

```json
{
  "name": "find_kallsyms_symbol",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580142992,
      "name": "find_kallsyms_symbol",
      "external": false,
      "loc": "kernel/module.c:4053",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:lookup_module_symbol_attrs",
        "kernel/module.c:lookup_module_symbol_name",
        "kernel/module.c:module_address_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580142992,
      "name": "find_kallsyms_symbol",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 420
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
const char * find_kallsyms_symbol(struct module * mod, long unsigned int addr, long unsigned int * size, long unsigned int * offset)
```

```json
{
  "name": "find_kallsyms_symbol",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580187024,
      "name": "find_kallsyms_symbol",
      "external": false,
      "loc": "kernel/module.c:4053",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:lookup_module_symbol_attrs",
        "kernel/module.c:lookup_module_symbol_name",
        "kernel/module.c:module_address_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580187024,
      "name": "find_kallsyms_symbol",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 420
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
const char * find_kallsyms_symbol(struct module * mod, long unsigned int addr, long unsigned int * size, long unsigned int * offset)
```

```json
{
  "name": "find_kallsyms_symbol",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580239264,
      "name": "find_kallsyms_symbol",
      "external": false,
      "loc": "kernel/module.c:4053",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:lookup_module_symbol_attrs",
        "kernel/module.c:lookup_module_symbol_name",
        "kernel/module.c:module_address_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580239264,
      "name": "find_kallsyms_symbol",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 420
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
const char * find_kallsyms_symbol(struct module * mod, long unsigned int addr, long unsigned int * size, long unsigned int * offset)
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
