# Function: <code>css_populate_dir</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int css_populate_dir(struct cgroup_subsys_state * css, struct cgroup * cgrp_override)
```

```json
{
  "name": "css_populate_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579975024,
      "name": "css_populate_dir",
      "external": false,
      "loc": "kernel/cgroup.c:1456",
      "file": "kernel/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:rebind_subsystems",
        "kernel/cgroup.c:create_css",
        "kernel/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup.c:cgroup_setup_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579975024,
      "name": "css_populate_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
int css_populate_dir(struct cgroup_subsys_state * css)
```

```json
{
  "name": "css_populate_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580008416,
      "name": "css_populate_dir",
      "external": false,
      "loc": "kernel/cgroup.c:1519",
      "file": "kernel/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup.c:cgroup_setup_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580008416,
      "name": "css_populate_dir",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int css_populate_dir(struct cgroup_subsys_state * css)
```

```json
{
  "name": "css_populate_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580042016,
      "name": "css_populate_dir",
      "external": false,
      "loc": "kernel/cgroup.c:1524",
      "file": "kernel/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup.c:cgroup_setup_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580042016,
      "name": "css_populate_dir",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int css_populate_dir(struct cgroup_subsys_state * css)
```

```json
{
  "name": "css_populate_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580039376,
      "name": "css_populate_dir",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1415",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_setup_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580039376,
      "name": "css_populate_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
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
int css_populate_dir(struct cgroup_subsys_state * css)
```

```json
{
  "name": "css_populate_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580088176,
      "name": "css_populate_dir",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1586",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_setup_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580088176,
      "name": "css_populate_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
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
int css_populate_dir(struct cgroup_subsys_state * css)
```

```json
{
  "name": "css_populate_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580146784,
      "name": "css_populate_dir",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1600",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_setup_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580146784,
      "name": "css_populate_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 320
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
int css_populate_dir(struct cgroup_subsys_state * css)
```

```json
{
  "name": "css_populate_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580194384,
      "name": "css_populate_dir",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1638",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_setup_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580194384,
      "name": "css_populate_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 320
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
int css_populate_dir(struct cgroup_subsys_state * css)
```

```json
{
  "name": "css_populate_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580240496,
      "name": "css_populate_dir",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1679",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_setup_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580240496,
      "name": "css_populate_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 315
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
int css_populate_dir(struct cgroup_subsys_state * css)
```

```json
{
  "name": "css_populate_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580288672,
      "name": "css_populate_dir",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1679",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_setup_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580288672,
      "name": "css_populate_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 315
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
int css_populate_dir(struct cgroup_subsys_state * css)
```

```json
{
  "name": "css_populate_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580359632,
      "name": "css_populate_dir",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1669",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_setup_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580359632,
      "name": "css_populate_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 315
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
int css_populate_dir(struct cgroup_subsys_state * css)
```

```json
{
  "name": "css_populate_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580346432,
      "name": "css_populate_dir",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1666",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_setup_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580346432,
      "name": "css_populate_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 315
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
int css_populate_dir(struct cgroup_subsys_state * css)
```

```json
{
  "name": "css_populate_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580350064,
      "name": "css_populate_dir",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1667",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_setup_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580350064,
      "name": "css_populate_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 315
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
int css_populate_dir(struct cgroup_subsys_state * css)
```

```json
{
  "name": "css_populate_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580506240,
      "name": "css_populate_dir",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1698",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_setup_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580506240,
      "name": "css_populate_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 315
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
int css_populate_dir(struct cgroup_subsys_state * css)
```

```json
{
  "name": "css_populate_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580688560,
      "name": "css_populate_dir",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1701",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_setup_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580688560,
      "name": "css_populate_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
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
int css_populate_dir(struct cgroup_subsys_state * css)
```

```json
{
  "name": "css_populate_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580976576,
      "name": "css_populate_dir",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1739",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_setup_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580976576,
      "name": "css_populate_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 363
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
int css_populate_dir(struct cgroup_subsys_state * css)
```

```json
{
  "name": "css_populate_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581064544,
      "name": "css_populate_dir",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1733",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_setup_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581064544,
      "name": "css_populate_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
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
int css_populate_dir(struct cgroup_subsys_state * css)
```

```json
{
  "name": "css_populate_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581161936,
      "name": "css_populate_dir",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1728",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_setup_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581161936,
      "name": "css_populate_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 359
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
int css_populate_dir(struct cgroup_subsys_state * css)
```

```json
{
  "name": "css_populate_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491536992,
      "name": "css_populate_dir",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1679",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_setup_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491536992,
      "name": "css_populate_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
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
int css_populate_dir(struct cgroup_subsys_state * css)
```

```json
{
  "name": "css_populate_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225495780,
      "name": "css_populate_dir",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1679",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_setup_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225495780,
      "name": "css_populate_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
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
int css_populate_dir(struct cgroup_subsys_state * css)
```

```json
{
  "name": "css_populate_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284505776,
      "name": "css_populate_dir",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1679",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_setup_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284505776,
      "name": "css_populate_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 540
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
int css_populate_dir(struct cgroup_subsys_state * css)
```

```json
{
  "name": "css_populate_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271954186,
      "name": "css_populate_dir",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1679",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_setup_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271954186,
      "name": "css_populate_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
int css_populate_dir(struct cgroup_subsys_state * css)
```

```json
{
  "name": "css_populate_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580257472,
      "name": "css_populate_dir",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1679",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_setup_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580257472,
      "name": "css_populate_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 315
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
int css_populate_dir(struct cgroup_subsys_state * css)
```

```json
{
  "name": "css_populate_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580204720,
      "name": "css_populate_dir",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1679",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_setup_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580204720,
      "name": "css_populate_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 315
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
int css_populate_dir(struct cgroup_subsys_state * css)
```

```json
{
  "name": "css_populate_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580248720,
      "name": "css_populate_dir",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1679",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_setup_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580248720,
      "name": "css_populate_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 315
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
int css_populate_dir(struct cgroup_subsys_state * css)
```

```json
{
  "name": "css_populate_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580294656,
      "name": "css_populate_dir",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1679",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_enable",
        "kernel/cgroup/cgroup.c:cgroup_setup_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580294656,
      "name": "css_populate_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 315
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
<b>Param removed. </b>
<code>struct cgroup * cgrp_override</code>
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
