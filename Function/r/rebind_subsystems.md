# Function: <code>rebind_subsystems</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int rebind_subsystems(struct cgroup_root * dst_root, long unsigned int ss_mask)
```

```json
{
  "name": "rebind_subsystems",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579975328,
      "name": "rebind_subsystems",
      "external": false,
      "loc": "kernel/cgroup.c:1489",
      "file": "kernel/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_remount",
        "kernel/cgroup.c:cgroup_remount",
        "kernel/cgroup.c:css_free_work_fn",
        "kernel/cgroup.c:cgroup_setup_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579975328,
      "name": "rebind_subsystems",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1284
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int rebind_subsystems(struct cgroup_root * dst_root, u16 ss_mask)
```

```json
{
  "name": "rebind_subsystems",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580019824,
      "name": "rebind_subsystems",
      "external": false,
      "loc": "kernel/cgroup.c:1557",
      "file": "kernel/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:css_free_work_fn",
        "kernel/cgroup.c:cgroup_setup_root",
        "kernel/cgroup.c:cgroup_remount",
        "kernel/cgroup.c:cgroup_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580019824,
      "name": "rebind_subsystems",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 899
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
int rebind_subsystems(struct cgroup_root * dst_root, u16 ss_mask)
```

```json
{
  "name": "rebind_subsystems",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580053504,
      "name": "rebind_subsystems",
      "external": false,
      "loc": "kernel/cgroup.c:1562",
      "file": "kernel/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:css_free_work_fn",
        "kernel/cgroup.c:cgroup_setup_root",
        "kernel/cgroup.c:cgroup_remount",
        "kernel/cgroup.c:cgroup_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580053504,
      "name": "rebind_subsystems",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 899
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
int rebind_subsystems(struct cgroup_root * dst_root, u16 ss_mask)
```

```json
{
  "name": "rebind_subsystems",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580050752,
      "name": "rebind_subsystems",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1453",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_free_work_fn",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/cgroup/cgroup-v1.c:cgroup1_remount",
        "kernel/cgroup/cgroup-v1.c:cgroup1_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580050752,
      "name": "rebind_subsystems",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1017
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
int rebind_subsystems(struct cgroup_root * dst_root, u16 ss_mask)
```

```json
{
  "name": "rebind_subsystems",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580100784,
      "name": "rebind_subsystems",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1624",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_free_work_fn",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/cgroup/cgroup-v1.c:cgroup1_remount",
        "kernel/cgroup/cgroup-v1.c:cgroup1_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580100784,
      "name": "rebind_subsystems",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 908
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int rebind_subsystems(struct cgroup_root * dst_root, u16 ss_mask)
```

```json
{
  "name": "rebind_subsystems",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rebind_subsystems",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1640",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/cgroup/cgroup-v1.c:cgroup1_remount",
        "kernel/cgroup/cgroup-v1.c:cgroup1_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580170942,
      "name": "rebind_subsystems.cold.48",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071580159872,
      "name": "rebind_subsystems",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 870
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
int rebind_subsystems(struct cgroup_root * dst_root, u16 ss_mask)
```

```json
{
  "name": "rebind_subsystems",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rebind_subsystems",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1678",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/cgroup/cgroup-v1.c:cgroup1_remount",
        "kernel/cgroup/cgroup-v1.c:cgroup1_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580218830,
      "name": "rebind_subsystems.cold.52",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071580207664,
      "name": "rebind_subsystems",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 870
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
int rebind_subsystems(struct cgroup_root * dst_root, u16 ss_mask)
```

```json
{
  "name": "rebind_subsystems",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rebind_subsystems",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1719",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580267741,
      "name": "rebind_subsystems.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071580255808,
      "name": "rebind_subsystems",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 853
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
int rebind_subsystems(struct cgroup_root * dst_root, u16 ss_mask)
```

```json
{
  "name": "rebind_subsystems",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rebind_subsystems",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1719",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580315948,
      "name": "rebind_subsystems.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071580304048,
      "name": "rebind_subsystems",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 842
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int rebind_subsystems(struct cgroup_root * dst_root, u16 ss_mask)
```

```json
{
  "name": "rebind_subsystems",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rebind_subsystems",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1709",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/cgroup/cgroup.c:cgroup_destroy_root",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580387416,
      "name": "rebind_subsystems.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071580373744,
      "name": "rebind_subsystems",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 835
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int rebind_subsystems(struct cgroup_root * dst_root, u16 ss_mask)
```

```json
{
  "name": "rebind_subsystems",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rebind_subsystems",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1706",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/cgroup/cgroup.c:cgroup_destroy_root",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591315241,
      "name": "rebind_subsystems.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071580360608,
      "name": "rebind_subsystems",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 837
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
int rebind_subsystems(struct cgroup_root * dst_root, u16 ss_mask)
```

```json
{
  "name": "rebind_subsystems",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rebind_subsystems",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1707",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/cgroup/cgroup.c:cgroup_destroy_root",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591257427,
      "name": "rebind_subsystems.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580363376,
      "name": "rebind_subsystems",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 955
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
int rebind_subsystems(struct cgroup_root * dst_root, u16 ss_mask)
```

```json
{
  "name": "rebind_subsystems",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rebind_subsystems",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1738",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/cgroup/cgroup.c:cgroup_destroy_root",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592161152,
      "name": "rebind_subsystems.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
    },
    {
      "addr": 18446744071580522048,
      "name": "rebind_subsystems",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1636
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
int rebind_subsystems(struct cgroup_root * dst_root, u16 ss_mask)
```

```json
{
  "name": "rebind_subsystems",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rebind_subsystems",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1741",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/cgroup/cgroup.c:cgroup_destroy_root",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593934181,
      "name": "rebind_subsystems.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
    },
    {
      "addr": 18446744071580719104,
      "name": "rebind_subsystems",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1616
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int rebind_subsystems(struct cgroup_root * dst_root, u16 ss_mask)
```

```json
{
  "name": "rebind_subsystems",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rebind_subsystems",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1787",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/cgroup/cgroup.c:cgroup_destroy_root",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595999759,
      "name": "rebind_subsystems.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    },
    {
      "addr": 18446744071580993856,
      "name": "rebind_subsystems",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1686
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int rebind_subsystems(struct cgroup_root * dst_root, u16 ss_mask)
```

```json
{
  "name": "rebind_subsystems",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rebind_subsystems",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1781",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/cgroup/cgroup.c:cgroup_destroy_root",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596517893,
      "name": "rebind_subsystems.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 18446744071581081424,
      "name": "rebind_subsystems",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2682
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int rebind_subsystems(struct cgroup_root * dst_root, u16 ss_mask)
```

```json
{
  "name": "rebind_subsystems",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rebind_subsystems",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1778",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/cgroup/cgroup.c:cgroup_destroy_root",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597418115,
      "name": "rebind_subsystems.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 18446744071581178944,
      "name": "rebind_subsystems",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2682
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
int rebind_subsystems(struct cgroup_root * dst_root, u16 ss_mask)
```

```json
{
  "name": "rebind_subsystems",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491555720,
      "name": "rebind_subsystems",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1719",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491555720,
      "name": "rebind_subsystems",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 916
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
int rebind_subsystems(struct cgroup_root * dst_root, u16 ss_mask)
```

```json
{
  "name": "rebind_subsystems",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225519720,
      "name": "rebind_subsystems",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1719",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225519720,
      "name": "rebind_subsystems",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1208
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
int rebind_subsystems(struct cgroup_root * dst_root, u16 ss_mask)
```

```json
{
  "name": "rebind_subsystems",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284528320,
      "name": "rebind_subsystems",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1719",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284528320,
      "name": "rebind_subsystems",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1220
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
int rebind_subsystems(struct cgroup_root * dst_root, u16 ss_mask)
```

```json
{
  "name": "rebind_subsystems",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271969782,
      "name": "rebind_subsystems",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1719",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271969782,
      "name": "rebind_subsystems",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 926
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
int rebind_subsystems(struct cgroup_root * dst_root, u16 ss_mask)
```

```json
{
  "name": "rebind_subsystems",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rebind_subsystems",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1719",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580284748,
      "name": "rebind_subsystems.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071580272848,
      "name": "rebind_subsystems",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 842
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
int rebind_subsystems(struct cgroup_root * dst_root, u16 ss_mask)
```

```json
{
  "name": "rebind_subsystems",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rebind_subsystems",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1719",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580232156,
      "name": "rebind_subsystems.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071580220352,
      "name": "rebind_subsystems",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 836
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
int rebind_subsystems(struct cgroup_root * dst_root, u16 ss_mask)
```

```json
{
  "name": "rebind_subsystems",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rebind_subsystems",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1719",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580275996,
      "name": "rebind_subsystems.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071580264096,
      "name": "rebind_subsystems",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 842
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
int rebind_subsystems(struct cgroup_root * dst_root, u16 ss_mask)
```

```json
{
  "name": "rebind_subsystems",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rebind_subsystems",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1719",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580329808,
      "name": "rebind_subsystems.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071580317440,
      "name": "rebind_subsystems",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 833
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>long unsigned int ss_mask</code> ➡️ <code>u16 ss_mask</code>
</li>
</ul>
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
