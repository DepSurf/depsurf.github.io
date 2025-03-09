# Function: <code>locate_module_kobject</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct module_kobject * locate_module_kobject(const char * name)
```

```json
{
  "name": "locate_module_kobject",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595083998,
      "name": "locate_module_kobject",
      "external": false,
      "loc": "kernel/params.c:798",
      "file": "kernel/params.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595083998,
      "name": "locate_module_kobject",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 193
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
struct module_kobject * locate_module_kobject(const char * name)
```

```json
{
  "name": "locate_module_kobject",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595251354,
      "name": "locate_module_kobject",
      "external": false,
      "loc": "kernel/params.c:798",
      "file": "kernel/params.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595251354,
      "name": "locate_module_kobject",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 193
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
struct module_kobject * locate_module_kobject(const char * name)
```

```json
{
  "name": "locate_module_kobject",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595495839,
      "name": "locate_module_kobject",
      "external": false,
      "loc": "kernel/params.c:798",
      "file": "kernel/params.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595495839,
      "name": "locate_module_kobject",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 193
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
struct module_kobject * locate_module_kobject(const char * name)
```

```json
{
  "name": "locate_module_kobject",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596416953,
      "name": "locate_module_kobject",
      "external": false,
      "loc": "kernel/params.c:746",
      "file": "kernel/params.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596416953,
      "name": "locate_module_kobject",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 201
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
struct module_kobject * locate_module_kobject(const char * name)
```

```json
{
  "name": "locate_module_kobject",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071602741509,
      "name": "locate_module_kobject",
      "external": false,
      "loc": "kernel/params.c:759",
      "file": "kernel/params.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602741509,
      "name": "locate_module_kobject",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 201
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
struct module_kobject * locate_module_kobject(const char * name)
```

```json
{
  "name": "locate_module_kobject",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071602914129,
      "name": "locate_module_kobject",
      "external": false,
      "loc": "kernel/params.c:759",
      "file": "kernel/params.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_sysfs_init",
        "kernel/params.c:param_sysfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602914129,
      "name": "locate_module_kobject",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 201
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
struct module_kobject * locate_module_kobject(const char * name)
```

```json
{
  "name": "locate_module_kobject",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604711737,
      "name": "locate_module_kobject",
      "external": false,
      "loc": "kernel/params.c:759",
      "file": "kernel/params.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_sysfs_init",
        "kernel/params.c:param_sysfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604711737,
      "name": "locate_module_kobject",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 206
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
struct module_kobject * locate_module_kobject(const char * name)
```

```json
{
  "name": "locate_module_kobject",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604812057,
      "name": "locate_module_kobject",
      "external": false,
      "loc": "kernel/params.c:747",
      "file": "kernel/params.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_sysfs_init",
        "kernel/params.c:param_sysfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604812057,
      "name": "locate_module_kobject",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 209
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
struct module_kobject * locate_module_kobject(const char * name)
```

```json
{
  "name": "locate_module_kobject",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604846316,
      "name": "locate_module_kobject",
      "external": false,
      "loc": "kernel/params.c:742",
      "file": "kernel/params.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_sysfs_init",
        "kernel/params.c:param_sysfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604846316,
      "name": "locate_module_kobject",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 209
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
struct module_kobject * locate_module_kobject(const char * name)
```

```json
{
  "name": "locate_module_kobject",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609179797,
      "name": "locate_module_kobject",
      "external": false,
      "loc": "kernel/params.c:742",
      "file": "kernel/params.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_sysfs_init",
        "kernel/params.c:kernel_add_sysfs_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609179797,
      "name": "locate_module_kobject",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 209
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
struct module_kobject * locate_module_kobject(const char * name)
```

```json
{
  "name": "locate_module_kobject",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612245231,
      "name": "locate_module_kobject",
      "external": false,
      "loc": "kernel/params.c:743",
      "file": "kernel/params.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_sysfs_init",
        "kernel/params.c:kernel_add_sysfs_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612245231,
      "name": "locate_module_kobject",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 209
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
struct module_kobject * locate_module_kobject(const char * name)
```

```json
{
  "name": "locate_module_kobject",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614385804,
      "name": "locate_module_kobject",
      "external": false,
      "loc": "kernel/params.c:743",
      "file": "kernel/params.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_sysfs_init",
        "kernel/params.c:param_sysfs_builtin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614385804,
      "name": "locate_module_kobject",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 209
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
struct module_kobject * locate_module_kobject(const char * name)
```

```json
{
  "name": "locate_module_kobject",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615319308,
      "name": "locate_module_kobject",
      "external": false,
      "loc": "kernel/params.c:761",
      "file": "kernel/params.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_sysfs_init",
        "kernel/params.c:param_sysfs_builtin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615319308,
      "name": "locate_module_kobject",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 209
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
struct module_kobject * locate_module_kobject(const char * name)
```

```json
{
  "name": "locate_module_kobject",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617101422,
      "name": "locate_module_kobject",
      "external": false,
      "loc": "kernel/params.c:761",
      "file": "kernel/params.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_sysfs_init",
        "kernel/params.c:param_sysfs_builtin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617101422,
      "name": "locate_module_kobject",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 219
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
struct module_kobject * locate_module_kobject(const char * name)
```

```json
{
  "name": "locate_module_kobject",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071627763920,
      "name": "locate_module_kobject",
      "external": false,
      "loc": "kernel/params.c:761",
      "file": "kernel/params.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_sysfs_builtin_init",
        "kernel/params.c:param_sysfs_builtin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627763920,
      "name": "locate_module_kobject",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 225
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
struct module_kobject * locate_module_kobject(const char * name)
```

```json
{
  "name": "locate_module_kobject",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619525168,
      "name": "locate_module_kobject",
      "external": false,
      "loc": "kernel/params.c:762",
      "file": "kernel/params.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_sysfs_builtin_init",
        "kernel/params.c:param_sysfs_builtin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619525168,
      "name": "locate_module_kobject",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 225
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
struct module_kobject * locate_module_kobject(const char * name)
```

```json
{
  "name": "locate_module_kobject",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071621824000,
      "name": "locate_module_kobject",
      "external": false,
      "loc": "kernel/params.c:766",
      "file": "kernel/params.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_sysfs_builtin_init",
        "kernel/params.c:param_sysfs_builtin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071621824000,
      "name": "locate_module_kobject",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 272
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
struct module_kobject * locate_module_kobject(const char * name)
```

```json
{
  "name": "locate_module_kobject",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336510879548,
      "name": "locate_module_kobject",
      "external": false,
      "loc": "kernel/params.c:742",
      "file": "kernel/params.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_sysfs_init",
        "kernel/params.c:param_sysfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336510879548,
      "name": "locate_module_kobject",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 224
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
struct module_kobject * locate_module_kobject(const char * name)
```

```json
{
  "name": "locate_module_kobject",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3243365892,
      "name": "locate_module_kobject",
      "external": false,
      "loc": "kernel/params.c:742",
      "file": "kernel/params.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_sysfs_init",
        "kernel/params.c:param_sysfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3243365892,
      "name": "locate_module_kobject",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 224
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
struct module_kobject * locate_module_kobject(const char * name)
```

```json
{
  "name": "locate_module_kobject",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055302510684,
      "name": "locate_module_kobject",
      "external": false,
      "loc": "kernel/params.c:742",
      "file": "kernel/params.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_sysfs_init",
        "kernel/params.c:param_sysfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055302510684,
      "name": "locate_module_kobject",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 308
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
struct module_kobject * locate_module_kobject(const char * name)
```

```json
{
  "name": "locate_module_kobject",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936270620856,
      "name": "locate_module_kobject",
      "external": false,
      "loc": "kernel/params.c:742",
      "file": "kernel/params.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_sysfs_init",
        "kernel/params.c:param_sysfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936270620856,
      "name": "locate_module_kobject",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 214
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
struct module_kobject * locate_module_kobject(const char * name)
```

```json
{
  "name": "locate_module_kobject",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604751583,
      "name": "locate_module_kobject",
      "external": false,
      "loc": "kernel/params.c:742",
      "file": "kernel/params.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_sysfs_init",
        "kernel/params.c:param_sysfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604751583,
      "name": "locate_module_kobject",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 209
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
struct module_kobject * locate_module_kobject(const char * name)
```

```json
{
  "name": "locate_module_kobject",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604719200,
      "name": "locate_module_kobject",
      "external": false,
      "loc": "kernel/params.c:742",
      "file": "kernel/params.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_sysfs_init",
        "kernel/params.c:param_sysfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604719200,
      "name": "locate_module_kobject",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 209
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
struct module_kobject * locate_module_kobject(const char * name)
```

```json
{
  "name": "locate_module_kobject",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604829150,
      "name": "locate_module_kobject",
      "external": false,
      "loc": "kernel/params.c:742",
      "file": "kernel/params.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_sysfs_init",
        "kernel/params.c:param_sysfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604829150,
      "name": "locate_module_kobject",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 209
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
struct module_kobject * locate_module_kobject(const char * name)
```

```json
{
  "name": "locate_module_kobject",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604850485,
      "name": "locate_module_kobject",
      "external": false,
      "loc": "kernel/params.c:742",
      "file": "kernel/params.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_sysfs_init",
        "kernel/params.c:param_sysfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604850485,
      "name": "locate_module_kobject",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 209
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
