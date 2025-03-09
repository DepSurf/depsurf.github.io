# Function: <code>cgroup_lock_and_drain_offline</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void cgroup_lock_and_drain_offline(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_lock_and_drain_offline",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580013824,
      "name": "cgroup_lock_and_drain_offline",
      "external": false,
      "loc": "kernel/cgroup.c:3125",
      "file": "kernel/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:css_free_work_fn",
        "kernel/cgroup.c:cgroup_mount",
        "kernel/cgroup.c:cgroup_remount",
        "kernel/cgroup.c:cgroup_kn_lock_live"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580013824,
      "name": "cgroup_lock_and_drain_offline",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 370
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
void cgroup_lock_and_drain_offline(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_lock_and_drain_offline",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580047408,
      "name": "cgroup_lock_and_drain_offline",
      "external": false,
      "loc": "kernel/cgroup.c:3134",
      "file": "kernel/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:css_free_work_fn",
        "kernel/cgroup.c:cgroup_mount",
        "kernel/cgroup.c:cgroup_remount",
        "kernel/cgroup.c:cgroup_kn_lock_live"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580047408,
      "name": "cgroup_lock_and_drain_offline",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 370
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
void cgroup_lock_and_drain_offline(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_lock_and_drain_offline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580052544,
      "name": "cgroup_lock_and_drain_offline",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2649",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_free_work_fn",
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live",
        "kernel/cgroup/cgroup-v1.c:cgroup1_mount",
        "kernel/cgroup/cgroup-v1.c:cgroup1_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580052544,
      "name": "cgroup_lock_and_drain_offline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 348
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
void cgroup_lock_and_drain_offline(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_lock_and_drain_offline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580102480,
      "name": "cgroup_lock_and_drain_offline",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2784",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_free_work_fn",
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live",
        "kernel/cgroup/cgroup-v1.c:cgroup1_mount",
        "kernel/cgroup/cgroup-v1.c:cgroup1_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580102480,
      "name": "cgroup_lock_and_drain_offline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 354
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
void cgroup_lock_and_drain_offline(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_lock_and_drain_offline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580161520,
      "name": "cgroup_lock_and_drain_offline",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2802",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live",
        "kernel/cgroup/cgroup-v1.c:cgroup1_mount",
        "kernel/cgroup/cgroup-v1.c:cgroup1_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580161520,
      "name": "cgroup_lock_and_drain_offline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 359
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
void cgroup_lock_and_drain_offline(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_lock_and_drain_offline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580209312,
      "name": "cgroup_lock_and_drain_offline",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2843",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live",
        "kernel/cgroup/cgroup-v1.c:cgroup1_mount",
        "kernel/cgroup/cgroup-v1.c:cgroup1_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580209312,
      "name": "cgroup_lock_and_drain_offline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 359
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
void cgroup_lock_and_drain_offline(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_lock_and_drain_offline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580257424,
      "name": "cgroup_lock_and_drain_offline",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2983",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live",
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580257424,
      "name": "cgroup_lock_and_drain_offline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 350
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
void cgroup_lock_and_drain_offline(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_lock_and_drain_offline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580305648,
      "name": "cgroup_lock_and_drain_offline",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2984",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live",
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580305648,
      "name": "cgroup_lock_and_drain_offline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 350
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
void cgroup_lock_and_drain_offline(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_lock_and_drain_offline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580375424,
      "name": "cgroup_lock_and_drain_offline",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2925",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live",
        "kernel/cgroup/cgroup.c:cgroup_destroy_root",
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580375424,
      "name": "cgroup_lock_and_drain_offline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 365
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
void cgroup_lock_and_drain_offline(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_lock_and_drain_offline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580362256,
      "name": "cgroup_lock_and_drain_offline",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2921",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live",
        "kernel/cgroup/cgroup.c:cgroup_destroy_root",
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580362256,
      "name": "cgroup_lock_and_drain_offline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 373
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
void cgroup_lock_and_drain_offline(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_lock_and_drain_offline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580365312,
      "name": "cgroup_lock_and_drain_offline",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2934",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live",
        "kernel/cgroup/cgroup.c:cgroup_destroy_root",
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580365312,
      "name": "cgroup_lock_and_drain_offline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 375
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
void cgroup_lock_and_drain_offline(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_lock_and_drain_offline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580524832,
      "name": "cgroup_lock_and_drain_offline",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2989",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live",
        "kernel/cgroup/cgroup.c:cgroup_destroy_root",
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580524832,
      "name": "cgroup_lock_and_drain_offline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 504
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
void cgroup_lock_and_drain_offline(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_lock_and_drain_offline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580721648,
      "name": "cgroup_lock_and_drain_offline",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:3000",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live",
        "kernel/cgroup/cgroup.c:cgroup_destroy_root",
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580721648,
      "name": "cgroup_lock_and_drain_offline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 529
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
void cgroup_lock_and_drain_offline(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_lock_and_drain_offline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580996512,
      "name": "cgroup_lock_and_drain_offline",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:3105",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live",
        "kernel/cgroup/cgroup.c:cgroup_destroy_root",
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580996512,
      "name": "cgroup_lock_and_drain_offline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 528
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
void cgroup_lock_and_drain_offline(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_lock_and_drain_offline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581085072,
      "name": "cgroup_lock_and_drain_offline",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:3074",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live",
        "kernel/cgroup/cgroup.c:cgroup_destroy_root",
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581085072,
      "name": "cgroup_lock_and_drain_offline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 528
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
void cgroup_lock_and_drain_offline(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_lock_and_drain_offline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581182592,
      "name": "cgroup_lock_and_drain_offline",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:3083",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live",
        "kernel/cgroup/cgroup.c:cgroup_destroy_root",
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581182592,
      "name": "cgroup_lock_and_drain_offline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 528
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
void cgroup_lock_and_drain_offline(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_lock_and_drain_offline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491557424,
      "name": "cgroup_lock_and_drain_offline",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2984",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live",
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491557424,
      "name": "cgroup_lock_and_drain_offline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
void cgroup_lock_and_drain_offline(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_lock_and_drain_offline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225521796,
      "name": "cgroup_lock_and_drain_offline",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2984",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live",
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225521796,
      "name": "cgroup_lock_and_drain_offline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 452
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
void cgroup_lock_and_drain_offline(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_lock_and_drain_offline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284530592,
      "name": "cgroup_lock_and_drain_offline",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2984",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live",
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284530592,
      "name": "cgroup_lock_and_drain_offline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 560
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
void cgroup_lock_and_drain_offline(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_lock_and_drain_offline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271971454,
      "name": "cgroup_lock_and_drain_offline",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2984",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live",
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271971454,
      "name": "cgroup_lock_and_drain_offline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
void cgroup_lock_and_drain_offline(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_lock_and_drain_offline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580274448,
      "name": "cgroup_lock_and_drain_offline",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2984",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live",
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580274448,
      "name": "cgroup_lock_and_drain_offline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 350
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
void cgroup_lock_and_drain_offline(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_lock_and_drain_offline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580221952,
      "name": "cgroup_lock_and_drain_offline",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2984",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live",
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580221952,
      "name": "cgroup_lock_and_drain_offline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 350
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
void cgroup_lock_and_drain_offline(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_lock_and_drain_offline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580265696,
      "name": "cgroup_lock_and_drain_offline",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2984",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live",
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580265696,
      "name": "cgroup_lock_and_drain_offline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 350
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
void cgroup_lock_and_drain_offline(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_lock_and_drain_offline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580319040,
      "name": "cgroup_lock_and_drain_offline",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2984",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live",
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580319040,
      "name": "cgroup_lock_and_drain_offline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 375
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
void cgroup_lock_and_drain_offline(struct cgroup * cgrp)
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
