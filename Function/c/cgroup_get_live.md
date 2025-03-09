# Function: <code>cgroup_get_live</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void cgroup_get_live(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_get_live",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580036608,
      "name": "cgroup_get_live",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:444",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_get_from_path",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:init_and_link_css",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580036608,
      "name": "cgroup_get_live",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
void cgroup_get_live(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_get_live",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580084880,
      "name": "cgroup_get_live",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:552",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_get_from_path",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:init_and_link_css",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580084880,
      "name": "cgroup_get_live",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
void cgroup_get_live(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_get_live",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580143792,
      "name": "cgroup_get_live",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:555",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_get_from_path",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:init_and_link_css",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580143792,
      "name": "cgroup_get_live",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
void cgroup_get_live(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_get_live",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580190400,
      "name": "cgroup_get_live",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:589",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_get_from_path",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:init_and_link_css",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580190400,
      "name": "cgroup_get_live",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
void cgroup_get_live(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_get_live",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580237552,
      "name": "cgroup_get_live",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:591",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_get_from_path",
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:init_and_link_css",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580237552,
      "name": "cgroup_get_live",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
void cgroup_get_live(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_get_live",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580285760,
      "name": "cgroup_get_live",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:591",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_get_from_path",
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:init_and_link_css",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580285760,
      "name": "cgroup_get_live",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cgroup_get_live(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_get_live",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580365295,
      "name": "cgroup_get_live",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:584",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_get_tree"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_get_from_path",
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:init_and_link_css",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:link_css_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580351424,
      "name": "cgroup_get_live",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
void cgroup_get_live(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_get_live",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580338368,
      "name": "cgroup_get_live",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:581",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_get_from_path",
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:init_and_link_css",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_get_tree",
        "kernel/cgroup/cgroup.c:link_css_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580338368,
      "name": "cgroup_get_live",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
void cgroup_get_live(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_get_live",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580341536,
      "name": "cgroup_get_live",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:581",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_get_from_path",
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:init_and_link_css",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_get_tree",
        "kernel/cgroup/cgroup.c:cgroup_setup_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580341536,
      "name": "cgroup_get_live",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cgroup_get_live(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_get_live",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580525110,
      "name": "cgroup_get_live",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:612",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_get_tree",
        "kernel/cgroup/cgroup.c:cgroup_setup_root"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_get_from_path",
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:init_and_link_css"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580496048,
      "name": "cgroup_get_live",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cgroup_get_live(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_get_live",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580721941,
      "name": "cgroup_get_live",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:613",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_get_tree"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:init_and_link_css",
        "kernel/cgroup/cgroup.c:link_css_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580694000,
      "name": "cgroup_get_live",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cgroup_get_live(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_get_live",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580996804,
      "name": "cgroup_get_live",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:618",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_get_tree"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:init_and_link_css",
        "kernel/cgroup/cgroup.c:link_css_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580964592,
      "name": "cgroup_get_live",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cgroup_get_live(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_get_live",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581085364,
      "name": "cgroup_get_live",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:617",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_get_tree"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:init_and_link_css",
        "kernel/cgroup/cgroup.c:link_css_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581053280,
      "name": "cgroup_get_live",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cgroup_get_live(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_get_live",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581182884,
      "name": "cgroup_get_live",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:597",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_get_tree"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:init_and_link_css",
        "kernel/cgroup/cgroup.c:link_css_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581151120,
      "name": "cgroup_get_live",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
void cgroup_get_live(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_get_live",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491534976,
      "name": "cgroup_get_live",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:591",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_get_from_path",
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:init_and_link_css",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491534976,
      "name": "cgroup_get_live",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
void cgroup_get_live(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_get_live",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225502764,
      "name": "cgroup_get_live",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:591",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_get_from_path",
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:init_and_link_css",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225502764,
      "name": "cgroup_get_live",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void cgroup_get_live(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_get_live",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284502512,
      "name": "cgroup_get_live",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:591",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_get_from_path",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:init_and_link_css",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_get_tree",
        "kernel/cgroup/cgroup.c:link_css_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284502512,
      "name": "cgroup_get_live",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
void cgroup_get_live(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_get_live",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271951908,
      "name": "cgroup_get_live",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:591",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_get_from_path",
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:init_and_link_css",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271951908,
      "name": "cgroup_get_live",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
void cgroup_get_live(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_get_live",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580254560,
      "name": "cgroup_get_live",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:591",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_get_from_path",
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:init_and_link_css",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580254560,
      "name": "cgroup_get_live",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
void cgroup_get_live(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_get_live",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580202112,
      "name": "cgroup_get_live",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:591",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_get_from_path",
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:init_and_link_css",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580202112,
      "name": "cgroup_get_live",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
void cgroup_get_live(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_get_live",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580245808,
      "name": "cgroup_get_live",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:591",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_get_from_path",
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:init_and_link_css",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580245808,
      "name": "cgroup_get_live",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
void cgroup_get_live(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_get_live",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580301216,
      "name": "cgroup_get_live",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:591",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_get_from_path",
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:init_and_link_css",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580301216,
      "name": "cgroup_get_live",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
void cgroup_get_live(struct cgroup * cgrp)
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
