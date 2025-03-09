# Function: <code>frob_writable_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void frob_writable_data(const struct module_layout * layout, int (*)(long unsigned int, int) set_memory)
```

```json
{
  "name": "frob_writable_data",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579917984,
      "name": "frob_writable_data",
      "external": false,
      "loc": "kernel/module.c:1883",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:disable_ro_nx",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579917984,
      "name": "frob_writable_data",
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
void frob_writable_data(const struct module_layout * layout, int (*)(long unsigned int, int) set_memory)
```

```json
{
  "name": "frob_writable_data",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579949008,
      "name": "frob_writable_data",
      "external": false,
      "loc": "kernel/module.c:1898",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:disable_ro_nx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579949008,
      "name": "frob_writable_data",
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
void frob_writable_data(const struct module_layout * layout, int (*)(long unsigned int, int) set_memory)
```

```json
{
  "name": "frob_writable_data",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579979984,
      "name": "frob_writable_data",
      "external": false,
      "loc": "kernel/module.c:1890",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:disable_ro_nx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579979984,
      "name": "frob_writable_data",
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
void frob_writable_data(const struct module_layout * layout, int (*)(long unsigned int, int) set_memory)
```

```json
{
  "name": "frob_writable_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579980624,
      "name": "frob_writable_data",
      "external": false,
      "loc": "kernel/module.c:1917",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:disable_ro_nx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579980624,
      "name": "frob_writable_data",
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
void frob_writable_data(const struct module_layout * layout, int (*)(long unsigned int, int) set_memory)
```

```json
{
  "name": "frob_writable_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580027136,
      "name": "frob_writable_data",
      "external": false,
      "loc": "kernel/module.c:1925",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:disable_ro_nx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580027136,
      "name": "frob_writable_data",
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
void frob_writable_data(const struct module_layout * layout, int (*)(long unsigned int, int) set_memory)
```

```json
{
  "name": "frob_writable_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580082992,
      "name": "frob_writable_data",
      "external": false,
      "loc": "kernel/module.c:1924",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:disable_ro_nx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580082992,
      "name": "frob_writable_data",
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
void frob_writable_data(const struct module_layout * layout, int (*)(long unsigned int, int) set_memory)
```

```json
{
  "name": "frob_writable_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580130352,
      "name": "frob_writable_data",
      "external": false,
      "loc": "kernel/module.c:1925",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:disable_ro_nx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580130352,
      "name": "frob_writable_data",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "frob_writable_data",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580182304,
      "name": "frob_writable_data",
      "external": false,
      "loc": "kernel/module.c:1933",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580182304,
      "name": "frob_writable_data.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
  "name": "frob_writable_data",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580230400,
      "name": "frob_writable_data",
      "external": false,
      "loc": "kernel/module.c:1990",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580230400,
      "name": "frob_writable_data.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
  "name": "frob_writable_data",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580294640,
      "name": "frob_writable_data",
      "external": false,
      "loc": "kernel/module.c:2028",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:complete_formation",
        "kernel/module.c:complete_formation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580294640,
      "name": "frob_writable_data.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
  "name": "frob_writable_data",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580278544,
      "name": "frob_writable_data",
      "external": false,
      "loc": "kernel/module.c:2087",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:complete_formation",
        "kernel/module.c:complete_formation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580278544,
      "name": "frob_writable_data.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
  "name": "frob_writable_data",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580282688,
      "name": "frob_writable_data",
      "external": false,
      "loc": "kernel/module.c:1997",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:complete_formation",
        "kernel/module.c:complete_formation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580282688,
      "name": "frob_writable_data.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
  "name": "frob_writable_data",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580435088,
      "name": "frob_writable_data",
      "external": false,
      "loc": "kernel/module.c:1999",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:complete_formation",
        "kernel/module.c:complete_formation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580435088,
      "name": "frob_writable_data.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
  "name": "frob_writable_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580485501,
      "name": "frob_writable_data",
      "external": false,
      "loc": "kernel/module/strict_rwx.c:56",
      "file": "kernel/module/strict_rwx.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module/strict_rwx.c:module_enable_nx",
        "kernel/module/strict_rwx.c:module_enable_nx"
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
  "name": "frob_writable_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580736637,
      "name": "frob_writable_data",
      "external": false,
      "loc": "kernel/module/strict_rwx.c:56",
      "file": "kernel/module/strict_rwx.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module/strict_rwx.c:module_enable_nx",
        "kernel/module/strict_rwx.c:module_enable_nx"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "frob_writable_data",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491470784,
      "name": "frob_writable_data",
      "external": false,
      "loc": "kernel/module.c:1990",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491470784,
      "name": "frob_writable_data.constprop.0",
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
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "frob_writable_data",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225454180,
      "name": "frob_writable_data",
      "external": false,
      "loc": "kernel/module.c:1990",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225454180,
      "name": "frob_writable_data.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "frob_writable_data",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580199200,
      "name": "frob_writable_data",
      "external": false,
      "loc": "kernel/module.c:1990",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580199200,
      "name": "frob_writable_data.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
  "name": "frob_writable_data",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580146640,
      "name": "frob_writable_data",
      "external": false,
      "loc": "kernel/module.c:1990",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580146640,
      "name": "frob_writable_data.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
  "name": "frob_writable_data",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580190672,
      "name": "frob_writable_data",
      "external": false,
      "loc": "kernel/module.c:1990",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580190672,
      "name": "frob_writable_data.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
  "name": "frob_writable_data",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580243008,
      "name": "frob_writable_data",
      "external": false,
      "loc": "kernel/module.c:1990",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580243008,
      "name": "frob_writable_data.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
void frob_writable_data(const struct module_layout * layout, int (*)(long unsigned int, int) set_memory)
```
</details>
</li>
</ul>
