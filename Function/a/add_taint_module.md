# Function: <code>add_taint_module</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "add_taint_module",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579927876,
      "name": "add_taint_module",
      "external": false,
      "loc": "kernel/module.c:327",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module"
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
  "name": "add_taint_module",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579959183,
      "name": "add_taint_module",
      "external": false,
      "loc": "kernel/module.c:329",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void add_taint_module(struct module * mod, unsigned int flag, enum lockdep_ok lockdep_ok)
```

```json
{
  "name": "add_taint_module",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579990087,
      "name": "add_taint_module",
      "external": false,
      "loc": "kernel/module.c:332",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate"
      ],
      "caller_func": [
        "kernel/module.c:layout_and_allocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579977808,
      "name": "add_taint_module",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
void add_taint_module(struct module * mod, unsigned int flag, enum lockdep_ok lockdep_ok)
```

```json
{
  "name": "add_taint_module",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579995654,
      "name": "add_taint_module",
      "external": false,
      "loc": "kernel/module.c:336",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate"
      ],
      "caller_func": [
        "kernel/module.c:layout_and_allocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579981760,
      "name": "add_taint_module",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
void add_taint_module(struct module * mod, unsigned int flag, enum lockdep_ok lockdep_ok)
```

```json
{
  "name": "add_taint_module",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580042162,
      "name": "add_taint_module",
      "external": false,
      "loc": "kernel/module.c:346",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate"
      ],
      "caller_func": [
        "kernel/module.c:layout_and_allocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580028272,
      "name": "add_taint_module",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
void add_taint_module(struct module * mod, unsigned int flag, enum lockdep_ok lockdep_ok)
```

```json
{
  "name": "add_taint_module",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580100832,
      "name": "add_taint_module",
      "external": false,
      "loc": "kernel/module.c:345",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate"
      ],
      "caller_func": [
        "kernel/module.c:layout_and_allocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580083872,
      "name": "add_taint_module",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
void add_taint_module(struct module * mod, unsigned int flag, enum lockdep_ok lockdep_ok)
```

```json
{
  "name": "add_taint_module",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580148239,
      "name": "add_taint_module",
      "external": false,
      "loc": "kernel/module.c:327",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate"
      ],
      "caller_func": [
        "kernel/module.c:layout_and_allocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580131456,
      "name": "add_taint_module",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
  "name": "add_taint_module",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580196090,
      "name": "add_taint_module",
      "external": false,
      "loc": "kernel/module.c:323",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate"
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
  "name": "add_taint_module",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580244332,
      "name": "add_taint_module",
      "external": false,
      "loc": "kernel/module.c:325",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo"
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
  "name": "add_taint_module",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580314459,
      "name": "add_taint_module",
      "external": false,
      "loc": "kernel/module.c:328",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module",
        "kernel/module.c:check_module_license_and_versions",
        "kernel/module.c:check_module_license_and_versions",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:set_license"
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
  "name": "add_taint_module",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580300015,
      "name": "add_taint_module",
      "external": false,
      "loc": "kernel/module.c:330",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module",
        "kernel/module.c:check_module_license_and_versions",
        "kernel/module.c:check_module_license_and_versions",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:set_license"
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
  "name": "add_taint_module",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580303116,
      "name": "add_taint_module",
      "external": false,
      "loc": "kernel/module.c:328",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo"
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
  "name": "add_taint_module",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580456448,
      "name": "add_taint_module",
      "external": false,
      "loc": "kernel/module.c:329",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void add_taint_module(struct module * mod, unsigned int flag, enum lockdep_ok lockdep_ok)
```

```json
{
  "name": "add_taint_module",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580480429,
      "name": "add_taint_module",
      "external": false,
      "loc": "kernel/module/main.c:158",
      "file": "kernel/module/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module/main.c:load_module",
        "kernel/module/main.c:load_module",
        "kernel/module/main.c:load_module",
        "kernel/module/main.c:check_modinfo",
        "kernel/module/main.c:check_modinfo",
        "kernel/module/main.c:check_modinfo"
      ],
      "caller_func": [
        "kernel/module/main.c:check_modinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580464944,
      "name": "add_taint_module",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
  "name": "add_taint_module",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580730047,
      "name": "add_taint_module",
      "external": false,
      "loc": "kernel/module/main.c:156",
      "file": "kernel/module/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module/main.c:load_module",
        "kernel/module/main.c:load_module",
        "kernel/module/main.c:load_module",
        "kernel/module/main.c:check_modinfo",
        "kernel/module/main.c:check_modinfo",
        "kernel/module/main.c:check_modinfo",
        "kernel/module/main.c:check_modinfo",
        "kernel/module/main.c:check_modinfo"
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
  "name": "add_taint_module",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580794696,
      "name": "add_taint_module",
      "external": false,
      "loc": "kernel/module/main.c:163",
      "file": "kernel/module/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module/main.c:module_augment_kernel_taints",
        "kernel/module/main.c:module_augment_kernel_taints",
        "kernel/module/main.c:module_augment_kernel_taints",
        "kernel/module/main.c:module_augment_kernel_taints",
        "kernel/module/main.c:module_augment_kernel_taints",
        "kernel/module/main.c:module_augment_kernel_taints",
        "kernel/module/main.c:module_augment_kernel_taints",
        "kernel/module/main.c:module_augment_kernel_taints"
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
  "name": "add_taint_module",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580884376,
      "name": "add_taint_module",
      "external": false,
      "loc": "kernel/module/main.c:163",
      "file": "kernel/module/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module/main.c:module_augment_kernel_taints",
        "kernel/module/main.c:module_augment_kernel_taints",
        "kernel/module/main.c:module_augment_kernel_taints",
        "kernel/module/main.c:module_augment_kernel_taints",
        "kernel/module/main.c:module_augment_kernel_taints",
        "kernel/module/main.c:module_augment_kernel_taints",
        "kernel/module/main.c:module_augment_kernel_taints",
        "kernel/module/main.c:module_augment_kernel_taints"
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "add_taint_module",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491486544,
      "name": "add_taint_module",
      "external": false,
      "loc": "kernel/module.c:325",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "add_taint_module",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225469032,
      "name": "add_taint_module",
      "external": false,
      "loc": "kernel/module.c:325",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "add_taint_module",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284441428,
      "name": "add_taint_module",
      "external": false,
      "loc": "kernel/module.c:325",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "add_taint_module",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271930798,
      "name": "add_taint_module",
      "external": false,
      "loc": "kernel/module.c:325",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "add_taint_module",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580213132,
      "name": "add_taint_module",
      "external": false,
      "loc": "kernel/module.c:325",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo"
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
  "name": "add_taint_module",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580160572,
      "name": "add_taint_module",
      "external": false,
      "loc": "kernel/module.c:325",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo"
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
  "name": "add_taint_module",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580204604,
      "name": "add_taint_module",
      "external": false,
      "loc": "kernel/module.c:325",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo"
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
  "name": "add_taint_module",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580257063,
      "name": "add_taint_module",
      "external": false,
      "loc": "kernel/module.c:325",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo"
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
<details>
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
void add_taint_module(struct module * mod, unsigned int flag, enum lockdep_ok lockdep_ok)
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
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
void add_taint_module(struct module * mod, unsigned int flag, enum lockdep_ok lockdep_ok)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void add_taint_module(struct module * mod, unsigned int flag, enum lockdep_ok lockdep_ok)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void add_taint_module(struct module * mod, unsigned int flag, enum lockdep_ok lockdep_ok)
```
</details>
</li>
</ul>
