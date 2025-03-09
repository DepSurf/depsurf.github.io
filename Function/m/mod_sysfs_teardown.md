# Function: <code>mod_sysfs_teardown</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mod_sysfs_teardown",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579923930,
      "name": "mod_sysfs_teardown",
      "external": false,
      "loc": "kernel/module.c:1841",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void mod_sysfs_teardown(struct module * mod)
```

```json
{
  "name": "mod_sysfs_teardown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579951520,
      "name": "mod_sysfs_teardown",
      "external": false,
      "loc": "kernel/module.c:1845",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:free_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579951520,
      "name": "mod_sysfs_teardown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void mod_sysfs_teardown(struct module * mod)
```

```json
{
  "name": "mod_sysfs_teardown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579982720,
      "name": "mod_sysfs_teardown",
      "external": false,
      "loc": "kernel/module.c:1837",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:free_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579982720,
      "name": "mod_sysfs_teardown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
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
void mod_sysfs_teardown(struct module * mod)
```

```json
{
  "name": "mod_sysfs_teardown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579986656,
      "name": "mod_sysfs_teardown",
      "external": false,
      "loc": "kernel/module.c:1864",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:free_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579986656,
      "name": "mod_sysfs_teardown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
void mod_sysfs_teardown(struct module * mod)
```

```json
{
  "name": "mod_sysfs_teardown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580033248,
      "name": "mod_sysfs_teardown",
      "external": false,
      "loc": "kernel/module.c:1872",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:free_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580033248,
      "name": "mod_sysfs_teardown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
void mod_sysfs_teardown(struct module * mod)
```

```json
{
  "name": "mod_sysfs_teardown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580089328,
      "name": "mod_sysfs_teardown",
      "external": false,
      "loc": "kernel/module.c:1871",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:free_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580089328,
      "name": "mod_sysfs_teardown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
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
void mod_sysfs_teardown(struct module * mod)
```

```json
{
  "name": "mod_sysfs_teardown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580136608,
      "name": "mod_sysfs_teardown",
      "external": false,
      "loc": "kernel/module.c:1872",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:free_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580136608,
      "name": "mod_sysfs_teardown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
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
void mod_sysfs_teardown(struct module * mod)
```

```json
{
  "name": "mod_sysfs_teardown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580183264,
      "name": "mod_sysfs_teardown",
      "external": false,
      "loc": "kernel/module.c:1879",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:free_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580183264,
      "name": "mod_sysfs_teardown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
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
void mod_sysfs_teardown(struct module * mod)
```

```json
{
  "name": "mod_sysfs_teardown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580231360,
      "name": "mod_sysfs_teardown",
      "external": false,
      "loc": "kernel/module.c:1936",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:free_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580231360,
      "name": "mod_sysfs_teardown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
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
void mod_sysfs_teardown(struct module * mod)
```

```json
{
  "name": "mod_sysfs_teardown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580303088,
      "name": "mod_sysfs_teardown",
      "external": false,
      "loc": "kernel/module.c:1958",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:free_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580303088,
      "name": "mod_sysfs_teardown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 434
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
void mod_sysfs_teardown(struct module * mod)
```

```json
{
  "name": "mod_sysfs_teardown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580284672,
      "name": "mod_sysfs_teardown",
      "external": false,
      "loc": "kernel/module.c:2017",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:free_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580284672,
      "name": "mod_sysfs_teardown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 434
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
void mod_sysfs_teardown(struct module * mod)
```

```json
{
  "name": "mod_sysfs_teardown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580290528,
      "name": "mod_sysfs_teardown",
      "external": false,
      "loc": "kernel/module.c:1927",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:free_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580290528,
      "name": "mod_sysfs_teardown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 427
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
void mod_sysfs_teardown(struct module * mod)
```

```json
{
  "name": "mod_sysfs_teardown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580442544,
      "name": "mod_sysfs_teardown",
      "external": false,
      "loc": "kernel/module.c:1929",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:free_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580442544,
      "name": "mod_sysfs_teardown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 427
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
void mod_sysfs_teardown(struct module * mod)
```

```json
{
  "name": "mod_sysfs_teardown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580494576,
      "name": "mod_sysfs_teardown",
      "external": true,
      "loc": "kernel/module/sysfs.c:423",
      "file": "kernel/module/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/main.c:load_module",
        "kernel/module/main.c:free_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580494576,
      "name": "mod_sysfs_teardown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 441
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
void mod_sysfs_teardown(struct module * mod)
```

```json
{
  "name": "mod_sysfs_teardown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580746400,
      "name": "mod_sysfs_teardown",
      "external": true,
      "loc": "kernel/module/sysfs.c:423",
      "file": "kernel/module/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/main.c:load_module",
        "kernel/module/main.c:free_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580746400,
      "name": "mod_sysfs_teardown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 441
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
void mod_sysfs_teardown(struct module * mod)
```

```json
{
  "name": "mod_sysfs_teardown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580828832,
      "name": "mod_sysfs_teardown",
      "external": true,
      "loc": "kernel/module/sysfs.c:423",
      "file": "kernel/module/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/main.c:load_module",
        "kernel/module/main.c:free_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580828832,
      "name": "mod_sysfs_teardown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 441
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
void mod_sysfs_teardown(struct module * mod)
```

```json
{
  "name": "mod_sysfs_teardown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580918256,
      "name": "mod_sysfs_teardown",
      "external": true,
      "loc": "kernel/module/sysfs.c:423",
      "file": "kernel/module/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/main.c:load_module",
        "kernel/module/main.c:free_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580918256,
      "name": "mod_sysfs_teardown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 445
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "mod_sysfs_teardown",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491479336,
      "name": "mod_sysfs_teardown",
      "external": false,
      "loc": "kernel/module.c:1936",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "mod_sysfs_teardown",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225461552,
      "name": "mod_sysfs_teardown",
      "external": false,
      "loc": "kernel/module.c:1936",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void mod_sysfs_teardown(struct module * mod)
```

```json
{
  "name": "mod_sysfs_teardown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284424256,
      "name": "mod_sysfs_teardown",
      "external": false,
      "loc": "kernel/module.c:1936",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:free_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284424256,
      "name": "mod_sysfs_teardown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "mod_sysfs_teardown",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271925460,
      "name": "mod_sysfs_teardown",
      "external": false,
      "loc": "kernel/module.c:1936",
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
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void mod_sysfs_teardown(struct module * mod)
```

```json
{
  "name": "mod_sysfs_teardown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580200160,
      "name": "mod_sysfs_teardown",
      "external": false,
      "loc": "kernel/module.c:1936",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:free_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580200160,
      "name": "mod_sysfs_teardown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
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
void mod_sysfs_teardown(struct module * mod)
```

```json
{
  "name": "mod_sysfs_teardown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580147600,
      "name": "mod_sysfs_teardown",
      "external": false,
      "loc": "kernel/module.c:1936",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:free_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580147600,
      "name": "mod_sysfs_teardown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
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
void mod_sysfs_teardown(struct module * mod)
```

```json
{
  "name": "mod_sysfs_teardown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580191632,
      "name": "mod_sysfs_teardown",
      "external": false,
      "loc": "kernel/module.c:1936",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:free_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580191632,
      "name": "mod_sysfs_teardown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
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
void mod_sysfs_teardown(struct module * mod)
```

```json
{
  "name": "mod_sysfs_teardown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580243984,
      "name": "mod_sysfs_teardown",
      "external": false,
      "loc": "kernel/module.c:1936",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:free_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580243984,
      "name": "mod_sysfs_teardown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void mod_sysfs_teardown(struct module * mod)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void mod_sysfs_teardown(struct module * mod)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void mod_sysfs_teardown(struct module * mod)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void mod_sysfs_teardown(struct module * mod)
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
