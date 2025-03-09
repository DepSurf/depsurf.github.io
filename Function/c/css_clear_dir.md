# Function: <code>css_clear_dir</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void css_clear_dir(struct cgroup_subsys_state * css, struct cgroup * cgrp_override)
```

```json
{
  "name": "css_clear_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579974912,
      "name": "css_clear_dir",
      "external": false,
      "loc": "kernel/cgroup.c:1439",
      "file": "kernel/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:rebind_subsystems",
        "kernel/cgroup.c:rebind_subsystems",
        "kernel/cgroup.c:kill_css",
        "kernel/cgroup.c:create_css",
        "kernel/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup.c:cgroup_subtree_control_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579974912,
      "name": "css_clear_dir",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void css_clear_dir(struct cgroup_subsys_state * css)
```

```json
{
  "name": "css_clear_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580008208,
      "name": "css_clear_dir",
      "external": false,
      "loc": "kernel/cgroup.c:1499",
      "file": "kernel/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:kill_css",
        "kernel/cgroup.c:cgroup_apply_control_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580008208,
      "name": "css_clear_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
void css_clear_dir(struct cgroup_subsys_state * css)
```

```json
{
  "name": "css_clear_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580041808,
      "name": "css_clear_dir",
      "external": false,
      "loc": "kernel/cgroup.c:1504",
      "file": "kernel/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:kill_css",
        "kernel/cgroup.c:cgroup_apply_control_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580041808,
      "name": "css_clear_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
void css_clear_dir(struct cgroup_subsys_state * css)
```

```json
{
  "name": "css_clear_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580039168,
      "name": "css_clear_dir",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1395",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:kill_css",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580039168,
      "name": "css_clear_dir",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void css_clear_dir(struct cgroup_subsys_state * css)
```

```json
{
  "name": "css_clear_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580087968,
      "name": "css_clear_dir",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1566",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:kill_css",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580087968,
      "name": "css_clear_dir",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void css_clear_dir(struct cgroup_subsys_state * css)
```

```json
{
  "name": "css_clear_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580146528,
      "name": "css_clear_dir",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1571",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:kill_css",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580146528,
      "name": "css_clear_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
void css_clear_dir(struct cgroup_subsys_state * css)
```

```json
{
  "name": "css_clear_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580194128,
      "name": "css_clear_dir",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1609",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:kill_css",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580194128,
      "name": "css_clear_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
void css_clear_dir(struct cgroup_subsys_state * css)
```

```json
{
  "name": "css_clear_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580240240,
      "name": "css_clear_dir",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1650",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:kill_css",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580240240,
      "name": "css_clear_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
void css_clear_dir(struct cgroup_subsys_state * css)
```

```json
{
  "name": "css_clear_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580288416,
      "name": "css_clear_dir",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1650",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:kill_css",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580288416,
      "name": "css_clear_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
void css_clear_dir(struct cgroup_subsys_state * css)
```

```json
{
  "name": "css_clear_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580359472,
      "name": "css_clear_dir",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1640",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580359472,
      "name": "css_clear_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
void css_clear_dir(struct cgroup_subsys_state * css)
```

```json
{
  "name": "css_clear_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580346272,
      "name": "css_clear_dir",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1637",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580346272,
      "name": "css_clear_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
void css_clear_dir(struct cgroup_subsys_state * css)
```

```json
{
  "name": "css_clear_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580349904,
      "name": "css_clear_dir",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1638",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580349904,
      "name": "css_clear_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
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
void css_clear_dir(struct cgroup_subsys_state * css)
```

```json
{
  "name": "css_clear_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580506080,
      "name": "css_clear_dir",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1669",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580506080,
      "name": "css_clear_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
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
void css_clear_dir(struct cgroup_subsys_state * css)
```

```json
{
  "name": "css_clear_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580688368,
      "name": "css_clear_dir",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1672",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580688368,
      "name": "css_clear_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
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
void css_clear_dir(struct cgroup_subsys_state * css)
```

```json
{
  "name": "css_clear_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580976320,
      "name": "css_clear_dir",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1706",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580976320,
      "name": "css_clear_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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
void css_clear_dir(struct cgroup_subsys_state * css)
```

```json
{
  "name": "css_clear_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581064288,
      "name": "css_clear_dir",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1700",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581064288,
      "name": "css_clear_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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
void css_clear_dir(struct cgroup_subsys_state * css)
```

```json
{
  "name": "css_clear_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581161680,
      "name": "css_clear_dir",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1695",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581161680,
      "name": "css_clear_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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
void css_clear_dir(struct cgroup_subsys_state * css)
```

```json
{
  "name": "css_clear_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491536672,
      "name": "css_clear_dir",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1650",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:kill_css",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491536672,
      "name": "css_clear_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
void css_clear_dir(struct cgroup_subsys_state * css)
```

```json
{
  "name": "css_clear_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225495608,
      "name": "css_clear_dir",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1650",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:kill_css",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225495608,
      "name": "css_clear_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
void css_clear_dir(struct cgroup_subsys_state * css)
```

```json
{
  "name": "css_clear_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284505264,
      "name": "css_clear_dir",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1650",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:kill_css",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284505264,
      "name": "css_clear_dir",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void css_clear_dir(struct cgroup_subsys_state * css)
```

```json
{
  "name": "css_clear_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271953870,
      "name": "css_clear_dir",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1650",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:kill_css",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271953870,
      "name": "css_clear_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
void css_clear_dir(struct cgroup_subsys_state * css)
```

```json
{
  "name": "css_clear_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580257216,
      "name": "css_clear_dir",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1650",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:kill_css",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580257216,
      "name": "css_clear_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
void css_clear_dir(struct cgroup_subsys_state * css)
```

```json
{
  "name": "css_clear_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580204464,
      "name": "css_clear_dir",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1650",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:kill_css",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580204464,
      "name": "css_clear_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
void css_clear_dir(struct cgroup_subsys_state * css)
```

```json
{
  "name": "css_clear_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580248464,
      "name": "css_clear_dir",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1650",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:kill_css",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580248464,
      "name": "css_clear_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
void css_clear_dir(struct cgroup_subsys_state * css)
```

```json
{
  "name": "css_clear_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580294496,
      "name": "css_clear_dir",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1650",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:kill_css",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580294496,
      "name": "css_clear_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
