# Function: <code>mod_sysfs_setup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mod_sysfs_setup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579931947,
      "name": "mod_sysfs_setup",
      "external": false,
      "loc": "kernel/module.c:1761",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
  "name": "mod_sysfs_setup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579963725,
      "name": "mod_sysfs_setup",
      "external": false,
      "loc": "kernel/module.c:1765",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mod_sysfs_setup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579992676,
      "name": "mod_sysfs_setup",
      "external": false,
      "loc": "kernel/module.c:1757",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mod_sysfs_setup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580000055,
      "name": "mod_sysfs_setup",
      "external": false,
      "loc": "kernel/module.c:1779",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mod_sysfs_setup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580046571,
      "name": "mod_sysfs_setup",
      "external": false,
      "loc": "kernel/module.c:1787",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int mod_sysfs_setup(struct module * mod, const struct load_info * info, struct kernel_param * kparam, unsigned int num_params)
```

```json
{
  "name": "mod_sysfs_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mod_sysfs_setup",
      "external": false,
      "loc": "kernel/module.c:1786",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580091904,
      "name": "mod_sysfs_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1537
    },
    {
      "addr": 18446744071580108333,
      "name": "mod_sysfs_setup.cold.72",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int mod_sysfs_setup(struct module * mod, const struct load_info * info, struct kernel_param * kparam, unsigned int num_params)
```

```json
{
  "name": "mod_sysfs_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mod_sysfs_setup",
      "external": false,
      "loc": "kernel/module.c:1787",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580139184,
      "name": "mod_sysfs_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1551
    },
    {
      "addr": 18446744071580155407,
      "name": "mod_sysfs_setup.cold.75",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int mod_sysfs_setup(struct module * mod, const struct load_info * info, struct kernel_param * kparam, unsigned int num_params)
```

```json
{
  "name": "mod_sysfs_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mod_sysfs_setup",
      "external": false,
      "loc": "kernel/module.c:1794",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580185840,
      "name": "mod_sysfs_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1568
    },
    {
      "addr": 18446744071580201334,
      "name": "mod_sysfs_setup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int mod_sysfs_setup(struct module * mod, const struct load_info * info, struct kernel_param * kparam, unsigned int num_params)
```

```json
{
  "name": "mod_sysfs_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mod_sysfs_setup",
      "external": false,
      "loc": "kernel/module.c:1851",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580234512,
      "name": "mod_sysfs_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1596
    },
    {
      "addr": 18446744071580249785,
      "name": "mod_sysfs_setup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
int mod_sysfs_setup(struct module * mod, const struct load_info * info, struct kernel_param * kparam, unsigned int num_params)
```

```json
{
  "name": "mod_sysfs_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580306768,
      "name": "mod_sysfs_setup",
      "external": false,
      "loc": "kernel/module.c:1873",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580306768,
      "name": "mod_sysfs_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 547
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
int mod_sysfs_setup(struct module * mod, const struct load_info * info, struct kernel_param * kparam, unsigned int num_params)
```

```json
{
  "name": "mod_sysfs_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580292096,
      "name": "mod_sysfs_setup",
      "external": false,
      "loc": "kernel/module.c:1933",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580292096,
      "name": "mod_sysfs_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 537
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int mod_sysfs_setup(struct module * mod, const struct load_info * info, struct kernel_param * kparam, unsigned int num_params)
```

```json
{
  "name": "mod_sysfs_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mod_sysfs_setup",
      "external": false,
      "loc": "kernel/module.c:1843",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580293232,
      "name": "mod_sysfs_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 936
    },
    {
      "addr": 18446744071591256057,
      "name": "mod_sysfs_setup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int mod_sysfs_setup(struct module * mod, const struct load_info * info, struct kernel_param * kparam, unsigned int num_params)
```

```json
{
  "name": "mod_sysfs_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mod_sysfs_setup",
      "external": false,
      "loc": "kernel/module.c:1845",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580445248,
      "name": "mod_sysfs_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 967
    },
    {
      "addr": 18446744071592159012,
      "name": "mod_sysfs_setup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int mod_sysfs_setup(struct module * mod, const struct load_info * info, struct kernel_param * kparam, unsigned int num_params)
```

```json
{
  "name": "mod_sysfs_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mod_sysfs_setup",
      "external": true,
      "loc": "kernel/module/sysfs.c:370",
      "file": "kernel/module/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/main.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593925735,
      "name": "mod_sysfs_setup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071580493840,
      "name": "mod_sysfs_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 723
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
int mod_sysfs_setup(struct module * mod, const struct load_info * info, struct kernel_param * kparam, unsigned int num_params)
```

```json
{
  "name": "mod_sysfs_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580745664,
      "name": "mod_sysfs_setup",
      "external": true,
      "loc": "kernel/module/sysfs.c:370",
      "file": "kernel/module/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/main.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580745664,
      "name": "mod_sysfs_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 707
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
int mod_sysfs_setup(struct module * mod, const struct load_info * info, struct kernel_param * kparam, unsigned int num_params)
```

```json
{
  "name": "mod_sysfs_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580828096,
      "name": "mod_sysfs_setup",
      "external": true,
      "loc": "kernel/module/sysfs.c:370",
      "file": "kernel/module/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/main.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580828096,
      "name": "mod_sysfs_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 708
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
int mod_sysfs_setup(struct module * mod, const struct load_info * info, struct kernel_param * kparam, unsigned int num_params)
```

```json
{
  "name": "mod_sysfs_setup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580917520,
      "name": "mod_sysfs_setup",
      "external": true,
      "loc": "kernel/module/sysfs.c:370",
      "file": "kernel/module/sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/main.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580917520,
      "name": "mod_sysfs_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 708
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
int mod_sysfs_setup(struct module * mod, const struct load_info * info, struct kernel_param * kparam, unsigned int num_params)
```

```json
{
  "name": "mod_sysfs_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491473944,
      "name": "mod_sysfs_setup",
      "external": false,
      "loc": "kernel/module.c:1851",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491473944,
      "name": "mod_sysfs_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1484
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
int mod_sysfs_setup(struct module * mod, const struct load_info * info, struct kernel_param * kparam, unsigned int num_params)
```

```json
{
  "name": "mod_sysfs_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225458748,
      "name": "mod_sysfs_setup",
      "external": false,
      "loc": "kernel/module.c:1851",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225458748,
      "name": "mod_sysfs_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1708
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
int mod_sysfs_setup(struct module * mod, const struct load_info * info, struct kernel_param * kparam, unsigned int num_params)
```

```json
{
  "name": "mod_sysfs_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284427840,
      "name": "mod_sysfs_setup",
      "external": false,
      "loc": "kernel/module.c:1851",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284427840,
      "name": "mod_sysfs_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1960
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
int mod_sysfs_setup(struct module * mod, const struct load_info * info, struct kernel_param * kparam, unsigned int num_params)
```

```json
{
  "name": "mod_sysfs_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271923562,
      "name": "mod_sysfs_setup",
      "external": false,
      "loc": "kernel/module.c:1851",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271923562,
      "name": "mod_sysfs_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1322
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int mod_sysfs_setup(struct module * mod, const struct load_info * info, struct kernel_param * kparam, unsigned int num_params)
```

```json
{
  "name": "mod_sysfs_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mod_sysfs_setup",
      "external": false,
      "loc": "kernel/module.c:1851",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580203312,
      "name": "mod_sysfs_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1596
    },
    {
      "addr": 18446744071580218585,
      "name": "mod_sysfs_setup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int mod_sysfs_setup(struct module * mod, const struct load_info * info, struct kernel_param * kparam, unsigned int num_params)
```

```json
{
  "name": "mod_sysfs_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mod_sysfs_setup",
      "external": false,
      "loc": "kernel/module.c:1851",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580150752,
      "name": "mod_sysfs_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1596
    },
    {
      "addr": 18446744071580166025,
      "name": "mod_sysfs_setup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int mod_sysfs_setup(struct module * mod, const struct load_info * info, struct kernel_param * kparam, unsigned int num_params)
```

```json
{
  "name": "mod_sysfs_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mod_sysfs_setup",
      "external": false,
      "loc": "kernel/module.c:1851",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580194784,
      "name": "mod_sysfs_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1596
    },
    {
      "addr": 18446744071580210057,
      "name": "mod_sysfs_setup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int mod_sysfs_setup(struct module * mod, const struct load_info * info, struct kernel_param * kparam, unsigned int num_params)
```

```json
{
  "name": "mod_sysfs_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mod_sysfs_setup",
      "external": false,
      "loc": "kernel/module.c:1851",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580247200,
      "name": "mod_sysfs_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1596
    },
    {
      "addr": 18446744071580262736,
      "name": "mod_sysfs_setup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int mod_sysfs_setup(struct module * mod, const struct load_info * info, struct kernel_param * kparam, unsigned int num_params)
```
</details>
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
