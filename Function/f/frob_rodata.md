# Function: <code>frob_rodata</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void frob_rodata(const struct module_layout * layout, int (*)(long unsigned int, int) set_memory)
```

```json
{
  "name": "frob_rodata",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579917904,
      "name": "frob_rodata",
      "external": false,
      "loc": "kernel/module.c:1873",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:disable_ro_nx",
        "kernel/module.c:disable_ro_nx",
        "kernel/module.c:module_disable_ro",
        "kernel/module.c:module_disable_ro",
        "kernel/module.c:module_enable_ro",
        "kernel/module.c:module_enable_ro",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579917904,
      "name": "frob_rodata",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void frob_rodata(const struct module_layout * layout, int (*)(long unsigned int, int) set_memory)
```

```json
{
  "name": "frob_rodata",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579948848,
      "name": "frob_rodata",
      "external": false,
      "loc": "kernel/module.c:1878",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:disable_ro_nx",
        "kernel/module.c:disable_ro_nx",
        "kernel/module.c:module_enable_ro",
        "kernel/module.c:module_enable_ro",
        "kernel/module.c:module_disable_ro",
        "kernel/module.c:module_disable_ro"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579948848,
      "name": "frob_rodata",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void frob_rodata(const struct module_layout * layout, int (*)(long unsigned int, int) set_memory)
```

```json
{
  "name": "frob_rodata",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579979824,
      "name": "frob_rodata",
      "external": false,
      "loc": "kernel/module.c:1870",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:disable_ro_nx",
        "kernel/module.c:disable_ro_nx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579979824,
      "name": "frob_rodata",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
void frob_rodata(const struct module_layout * layout, int (*)(long unsigned int, int) set_memory)
```

```json
{
  "name": "frob_rodata",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579980464,
      "name": "frob_rodata",
      "external": false,
      "loc": "kernel/module.c:1897",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:disable_ro_nx",
        "kernel/module.c:disable_ro_nx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579980464,
      "name": "frob_rodata",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
void frob_rodata(const struct module_layout * layout, int (*)(long unsigned int, int) set_memory)
```

```json
{
  "name": "frob_rodata",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580026976,
      "name": "frob_rodata",
      "external": false,
      "loc": "kernel/module.c:1905",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:disable_ro_nx",
        "kernel/module.c:disable_ro_nx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580026976,
      "name": "frob_rodata",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
void frob_rodata(const struct module_layout * layout, int (*)(long unsigned int, int) set_memory)
```

```json
{
  "name": "frob_rodata",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580082832,
      "name": "frob_rodata",
      "external": false,
      "loc": "kernel/module.c:1904",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:disable_ro_nx",
        "kernel/module.c:disable_ro_nx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580082832,
      "name": "frob_rodata",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
void frob_rodata(const struct module_layout * layout, int (*)(long unsigned int, int) set_memory)
```

```json
{
  "name": "frob_rodata",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580130192,
      "name": "frob_rodata",
      "external": false,
      "loc": "kernel/module.c:1905",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:disable_ro_nx",
        "kernel/module.c:disable_ro_nx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580130192,
      "name": "frob_rodata",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
void frob_rodata(const struct module_layout * layout, int (*)(long unsigned int, int) set_memory)
```

```json
{
  "name": "frob_rodata",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580177008,
      "name": "frob_rodata",
      "external": false,
      "loc": "kernel/module.c:1913",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:module_disable_ro",
        "kernel/module.c:module_disable_ro"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580177008,
      "name": "frob_rodata",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
void frob_rodata(const struct module_layout * layout, int (*)(long unsigned int, int) set_memory)
```

```json
{
  "name": "frob_rodata",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580224896,
      "name": "frob_rodata",
      "external": false,
      "loc": "kernel/module.c:1970",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:module_disable_ro",
        "kernel/module.c:module_disable_ro"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580224896,
      "name": "frob_rodata",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
void frob_rodata(const struct module_layout * layout, int (*)(long unsigned int, int) set_memory)
```

```json
{
  "name": "frob_rodata",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580291776,
      "name": "frob_rodata",
      "external": false,
      "loc": "kernel/module.c:2008",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:complete_formation",
        "kernel/module.c:complete_formation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580291776,
      "name": "frob_rodata",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
void frob_rodata(const struct module_layout * layout, int (*)(long unsigned int, int) set_memory)
```

```json
{
  "name": "frob_rodata",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580275200,
      "name": "frob_rodata",
      "external": false,
      "loc": "kernel/module.c:2067",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:complete_formation",
        "kernel/module.c:complete_formation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580275200,
      "name": "frob_rodata",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
void frob_rodata(const struct module_layout * layout, int (*)(long unsigned int, int) set_memory)
```

```json
{
  "name": "frob_rodata",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580279536,
      "name": "frob_rodata",
      "external": false,
      "loc": "kernel/module.c:1977",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:complete_formation",
        "kernel/module.c:complete_formation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580279536,
      "name": "frob_rodata",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
void frob_rodata(const struct module_layout * layout, int (*)(long unsigned int, int) set_memory)
```

```json
{
  "name": "frob_rodata",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580431664,
      "name": "frob_rodata",
      "external": false,
      "loc": "kernel/module.c:1979",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:complete_formation",
        "kernel/module.c:complete_formation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580431664,
      "name": "frob_rodata",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
  "name": "frob_rodata",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580485443,
      "name": "frob_rodata",
      "external": false,
      "loc": "kernel/module/strict_rwx.c:42",
      "file": "kernel/module/strict_rwx.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module/strict_rwx.c:module_enable_nx",
        "kernel/module/strict_rwx.c:module_enable_nx",
        "kernel/module/strict_rwx.c:module_enable_ro",
        "kernel/module/strict_rwx.c:module_enable_ro"
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
  "name": "frob_rodata",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580736579,
      "name": "frob_rodata",
      "external": false,
      "loc": "kernel/module/strict_rwx.c:42",
      "file": "kernel/module/strict_rwx.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module/strict_rwx.c:module_enable_nx",
        "kernel/module/strict_rwx.c:module_enable_nx",
        "kernel/module/strict_rwx.c:module_enable_ro",
        "kernel/module/strict_rwx.c:module_enable_ro"
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
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void frob_rodata(const struct module_layout * layout, int (*)(long unsigned int, int) set_memory)
```

```json
{
  "name": "frob_rodata",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491465632,
      "name": "frob_rodata",
      "external": false,
      "loc": "kernel/module.c:1970",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:module_disable_ro",
        "kernel/module.c:module_disable_ro"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491465632,
      "name": "frob_rodata",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
void frob_rodata(const struct module_layout * layout, int (*)(long unsigned int, int) set_memory)
```

```json
{
  "name": "frob_rodata",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225449248,
      "name": "frob_rodata",
      "external": false,
      "loc": "kernel/module.c:1970",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:module_disable_ro",
        "kernel/module.c:module_disable_ro"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225449248,
      "name": "frob_rodata",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
void frob_rodata(const struct module_layout * layout, int (*)(long unsigned int, int) set_memory)
```

```json
{
  "name": "frob_rodata",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580193696,
      "name": "frob_rodata",
      "external": false,
      "loc": "kernel/module.c:1970",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:module_disable_ro",
        "kernel/module.c:module_disable_ro"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580193696,
      "name": "frob_rodata",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
void frob_rodata(const struct module_layout * layout, int (*)(long unsigned int, int) set_memory)
```

```json
{
  "name": "frob_rodata",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580141136,
      "name": "frob_rodata",
      "external": false,
      "loc": "kernel/module.c:1970",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:module_disable_ro",
        "kernel/module.c:module_disable_ro"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580141136,
      "name": "frob_rodata",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
void frob_rodata(const struct module_layout * layout, int (*)(long unsigned int, int) set_memory)
```

```json
{
  "name": "frob_rodata",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580185168,
      "name": "frob_rodata",
      "external": false,
      "loc": "kernel/module.c:1970",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:module_disable_ro",
        "kernel/module.c:module_disable_ro"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580185168,
      "name": "frob_rodata",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
void frob_rodata(const struct module_layout * layout, int (*)(long unsigned int, int) set_memory)
```

```json
{
  "name": "frob_rodata",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580237408,
      "name": "frob_rodata",
      "external": false,
      "loc": "kernel/module.c:1970",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:module_disable_ro",
        "kernel/module.c:module_disable_ro"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580237408,
      "name": "frob_rodata",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void frob_rodata(const struct module_layout * layout, int (*)(long unsigned int, int) set_memory)
```
</details>
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
void frob_rodata(const struct module_layout * layout, int (*)(long unsigned int, int) set_memory)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void frob_rodata(const struct module_layout * layout, int (*)(long unsigned int, int) set_memory)
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
