# Function: <code>module_remove_modinfo_attrs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "module_remove_modinfo_attrs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579924016,
      "name": "module_remove_modinfo_attrs",
      "external": false,
      "loc": "kernel/module.c:1704",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:free_module"
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
  "name": "module_remove_modinfo_attrs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579951622,
      "name": "module_remove_modinfo_attrs",
      "external": false,
      "loc": "kernel/module.c:1708",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:mod_sysfs_teardown"
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
  "name": "module_remove_modinfo_attrs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579982822,
      "name": "module_remove_modinfo_attrs",
      "external": false,
      "loc": "kernel/module.c:1700",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:mod_sysfs_teardown"
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
void module_remove_modinfo_attrs(struct module * mod)
```

```json
{
  "name": "module_remove_modinfo_attrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579981296,
      "name": "module_remove_modinfo_attrs",
      "external": false,
      "loc": "kernel/module.c:1722",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:mod_sysfs_teardown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579981296,
      "name": "module_remove_modinfo_attrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
void module_remove_modinfo_attrs(struct module * mod)
```

```json
{
  "name": "module_remove_modinfo_attrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580027808,
      "name": "module_remove_modinfo_attrs",
      "external": false,
      "loc": "kernel/module.c:1730",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:mod_sysfs_teardown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580027808,
      "name": "module_remove_modinfo_attrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
void module_remove_modinfo_attrs(struct module * mod)
```

```json
{
  "name": "module_remove_modinfo_attrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580083408,
      "name": "module_remove_modinfo_attrs",
      "external": false,
      "loc": "kernel/module.c:1729",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:mod_sysfs_teardown",
        "kernel/module.c:mod_sysfs_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580083408,
      "name": "module_remove_modinfo_attrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
void module_remove_modinfo_attrs(struct module * mod)
```

```json
{
  "name": "module_remove_modinfo_attrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580130768,
      "name": "module_remove_modinfo_attrs",
      "external": false,
      "loc": "kernel/module.c:1730",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:mod_sysfs_teardown",
        "kernel/module.c:mod_sysfs_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580130768,
      "name": "module_remove_modinfo_attrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
void module_remove_modinfo_attrs(struct module * mod, int end)
```

```json
{
  "name": "module_remove_modinfo_attrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580177632,
      "name": "module_remove_modinfo_attrs",
      "external": false,
      "loc": "kernel/module.c:1735",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:mod_sysfs_teardown",
        "kernel/module.c:mod_sysfs_setup",
        "kernel/module.c:mod_sysfs_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580177632,
      "name": "module_remove_modinfo_attrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
void module_remove_modinfo_attrs(struct module * mod, int end)
```

```json
{
  "name": "module_remove_modinfo_attrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580225520,
      "name": "module_remove_modinfo_attrs",
      "external": false,
      "loc": "kernel/module.c:1792",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:mod_sysfs_teardown",
        "kernel/module.c:mod_sysfs_setup",
        "kernel/module.c:mod_sysfs_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580225520,
      "name": "module_remove_modinfo_attrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
void module_remove_modinfo_attrs(struct module * mod, int end)
```

```json
{
  "name": "module_remove_modinfo_attrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580292432,
      "name": "module_remove_modinfo_attrs",
      "external": false,
      "loc": "kernel/module.c:1814",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:mod_sysfs_teardown",
        "kernel/module.c:mod_sysfs_setup",
        "kernel/module.c:module_add_modinfo_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580292432,
      "name": "module_remove_modinfo_attrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
void module_remove_modinfo_attrs(struct module * mod, int end)
```

```json
{
  "name": "module_remove_modinfo_attrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580275552,
      "name": "module_remove_modinfo_attrs",
      "external": false,
      "loc": "kernel/module.c:1875",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:mod_sysfs_teardown",
        "kernel/module.c:mod_sysfs_setup",
        "kernel/module.c:module_add_modinfo_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580275552,
      "name": "module_remove_modinfo_attrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
void module_remove_modinfo_attrs(struct module * mod, int end)
```

```json
{
  "name": "module_remove_modinfo_attrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580279888,
      "name": "module_remove_modinfo_attrs",
      "external": false,
      "loc": "kernel/module.c:1785",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:mod_sysfs_teardown",
        "kernel/module.c:mod_sysfs_setup",
        "kernel/module.c:mod_sysfs_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580279888,
      "name": "module_remove_modinfo_attrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
void module_remove_modinfo_attrs(struct module * mod, int end)
```

```json
{
  "name": "module_remove_modinfo_attrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580432016,
      "name": "module_remove_modinfo_attrs",
      "external": false,
      "loc": "kernel/module.c:1787",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:mod_sysfs_teardown",
        "kernel/module.c:mod_sysfs_setup",
        "kernel/module.c:mod_sysfs_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580432016,
      "name": "module_remove_modinfo_attrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
void module_remove_modinfo_attrs(struct module * mod, int end)
```

```json
{
  "name": "module_remove_modinfo_attrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580492096,
      "name": "module_remove_modinfo_attrs",
      "external": false,
      "loc": "kernel/module/sysfs.c:275",
      "file": "kernel/module/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/sysfs.c:mod_sysfs_teardown",
        "kernel/module/sysfs.c:mod_sysfs_setup",
        "kernel/module/sysfs.c:module_add_modinfo_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580492096,
      "name": "module_remove_modinfo_attrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
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
void module_remove_modinfo_attrs(struct module * mod, int end)
```

```json
{
  "name": "module_remove_modinfo_attrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580743760,
      "name": "module_remove_modinfo_attrs",
      "external": false,
      "loc": "kernel/module/sysfs.c:275",
      "file": "kernel/module/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/sysfs.c:mod_sysfs_teardown",
        "kernel/module/sysfs.c:mod_sysfs_setup",
        "kernel/module/sysfs.c:module_add_modinfo_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580743760,
      "name": "module_remove_modinfo_attrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
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
void module_remove_modinfo_attrs(struct module * mod, int end)
```

```json
{
  "name": "module_remove_modinfo_attrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580826096,
      "name": "module_remove_modinfo_attrs",
      "external": false,
      "loc": "kernel/module/sysfs.c:275",
      "file": "kernel/module/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/sysfs.c:mod_sysfs_teardown",
        "kernel/module/sysfs.c:mod_sysfs_setup",
        "kernel/module/sysfs.c:module_add_modinfo_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580826096,
      "name": "module_remove_modinfo_attrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
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
void module_remove_modinfo_attrs(struct module * mod, int end)
```

```json
{
  "name": "module_remove_modinfo_attrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580915536,
      "name": "module_remove_modinfo_attrs",
      "external": false,
      "loc": "kernel/module/sysfs.c:275",
      "file": "kernel/module/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/sysfs.c:mod_sysfs_teardown",
        "kernel/module/sysfs.c:mod_sysfs_setup",
        "kernel/module/sysfs.c:module_add_modinfo_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580915536,
      "name": "module_remove_modinfo_attrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
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
void module_remove_modinfo_attrs(struct module * mod, int end)
```

```json
{
  "name": "module_remove_modinfo_attrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491466392,
      "name": "module_remove_modinfo_attrs",
      "external": false,
      "loc": "kernel/module.c:1792",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:free_module",
        "kernel/module.c:mod_sysfs_setup",
        "kernel/module.c:mod_sysfs_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491466392,
      "name": "module_remove_modinfo_attrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
void module_remove_modinfo_attrs(struct module * mod, int end)
```

```json
{
  "name": "module_remove_modinfo_attrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225449940,
      "name": "module_remove_modinfo_attrs",
      "external": false,
      "loc": "kernel/module.c:1792",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:free_module",
        "kernel/module.c:mod_sysfs_setup",
        "kernel/module.c:mod_sysfs_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225449940,
      "name": "module_remove_modinfo_attrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
void module_remove_modinfo_attrs(struct module * mod, int end)
```

```json
{
  "name": "module_remove_modinfo_attrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284415024,
      "name": "module_remove_modinfo_attrs",
      "external": false,
      "loc": "kernel/module.c:1792",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:mod_sysfs_teardown",
        "kernel/module.c:mod_sysfs_setup",
        "kernel/module.c:mod_sysfs_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284415024,
      "name": "module_remove_modinfo_attrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
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
void module_remove_modinfo_attrs(struct module * mod, int end)
```

```json
{
  "name": "module_remove_modinfo_attrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271917816,
      "name": "module_remove_modinfo_attrs",
      "external": false,
      "loc": "kernel/module.c:1792",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:free_module",
        "kernel/module.c:mod_sysfs_setup",
        "kernel/module.c:mod_sysfs_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271917816,
      "name": "module_remove_modinfo_attrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
void module_remove_modinfo_attrs(struct module * mod, int end)
```

```json
{
  "name": "module_remove_modinfo_attrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580194320,
      "name": "module_remove_modinfo_attrs",
      "external": false,
      "loc": "kernel/module.c:1792",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:mod_sysfs_teardown",
        "kernel/module.c:mod_sysfs_setup",
        "kernel/module.c:mod_sysfs_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580194320,
      "name": "module_remove_modinfo_attrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
void module_remove_modinfo_attrs(struct module * mod, int end)
```

```json
{
  "name": "module_remove_modinfo_attrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580141760,
      "name": "module_remove_modinfo_attrs",
      "external": false,
      "loc": "kernel/module.c:1792",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:mod_sysfs_teardown",
        "kernel/module.c:mod_sysfs_setup",
        "kernel/module.c:mod_sysfs_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580141760,
      "name": "module_remove_modinfo_attrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
void module_remove_modinfo_attrs(struct module * mod, int end)
```

```json
{
  "name": "module_remove_modinfo_attrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580185792,
      "name": "module_remove_modinfo_attrs",
      "external": false,
      "loc": "kernel/module.c:1792",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:mod_sysfs_teardown",
        "kernel/module.c:mod_sysfs_setup",
        "kernel/module.c:mod_sysfs_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580185792,
      "name": "module_remove_modinfo_attrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
void module_remove_modinfo_attrs(struct module * mod, int end)
```

```json
{
  "name": "module_remove_modinfo_attrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580238032,
      "name": "module_remove_modinfo_attrs",
      "external": false,
      "loc": "kernel/module.c:1792",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:mod_sysfs_teardown",
        "kernel/module.c:mod_sysfs_setup",
        "kernel/module.c:mod_sysfs_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580238032,
      "name": "module_remove_modinfo_attrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
void module_remove_modinfo_attrs(struct module * mod)
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
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int end</code>
</li>
</ul>
</details>
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
