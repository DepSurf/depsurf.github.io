# Function: <code>cgroup_bpf_inherit</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void cgroup_bpf_inherit(struct cgroup * cgrp, struct cgroup * parent)
```

```json
{
  "name": "cgroup_bpf_inherit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580514416,
      "name": "cgroup_bpf_inherit",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:45",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580514416,
      "name": "cgroup_bpf_inherit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void cgroup_bpf_inherit(struct cgroup * cgrp, struct cgroup * parent)
```

```json
{
  "name": "cgroup_bpf_inherit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580546096,
      "name": "cgroup_bpf_inherit",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:45",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580546096,
      "name": "cgroup_bpf_inherit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int cgroup_bpf_inherit(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_bpf_inherit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580624816,
      "name": "cgroup_bpf_inherit",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:150",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_setup_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580624816,
      "name": "cgroup_bpf_inherit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
int cgroup_bpf_inherit(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_bpf_inherit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580753456,
      "name": "cgroup_bpf_inherit",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:149",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_setup_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580753456,
      "name": "cgroup_bpf_inherit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
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
int cgroup_bpf_inherit(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_bpf_inherit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580818368,
      "name": "cgroup_bpf_inherit",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:160",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_setup_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580818368,
      "name": "cgroup_bpf_inherit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
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
int cgroup_bpf_inherit(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_bpf_inherit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580912864,
      "name": "cgroup_bpf_inherit",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:195",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:cgroup_setup_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580912864,
      "name": "cgroup_bpf_inherit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
int cgroup_bpf_inherit(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_bpf_inherit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580966160,
      "name": "cgroup_bpf_inherit",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:198",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:cgroup_setup_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580966160,
      "name": "cgroup_bpf_inherit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 446
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
int cgroup_bpf_inherit(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_bpf_inherit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581127824,
      "name": "cgroup_bpf_inherit",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:272",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:cgroup_setup_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581127824,
      "name": "cgroup_bpf_inherit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 453
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
int cgroup_bpf_inherit(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_bpf_inherit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581161888,
      "name": "cgroup_bpf_inherit",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:287",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:cgroup_setup_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581161888,
      "name": "cgroup_bpf_inherit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 501
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
int cgroup_bpf_inherit(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_bpf_inherit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581178864,
      "name": "cgroup_bpf_inherit",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:287",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:cgroup_setup_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581178864,
      "name": "cgroup_bpf_inherit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 500
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
int cgroup_bpf_inherit(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_bpf_inherit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581418336,
      "name": "cgroup_bpf_inherit",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:287",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:cgroup_setup_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581418336,
      "name": "cgroup_bpf_inherit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 704
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
int cgroup_bpf_inherit(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_bpf_inherit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581747728,
      "name": "cgroup_bpf_inherit",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:326",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:cgroup_setup_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581747728,
      "name": "cgroup_bpf_inherit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 709
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
int cgroup_bpf_inherit(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_bpf_inherit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582162672,
      "name": "cgroup_bpf_inherit",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:461",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:cgroup_setup_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582162672,
      "name": "cgroup_bpf_inherit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 715
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
int cgroup_bpf_inherit(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_bpf_inherit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582359600,
      "name": "cgroup_bpf_inherit",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:461",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:cgroup_setup_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582359600,
      "name": "cgroup_bpf_inherit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 715
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
int cgroup_bpf_inherit(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_bpf_inherit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582526432,
      "name": "cgroup_bpf_inherit",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:461",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:cgroup_setup_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582526432,
      "name": "cgroup_bpf_inherit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 721
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
int cgroup_bpf_inherit(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_bpf_inherit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492314544,
      "name": "cgroup_bpf_inherit",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:198",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:cgroup_setup_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492314544,
      "name": "cgroup_bpf_inherit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 536
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
int cgroup_bpf_inherit(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_bpf_inherit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226200044,
      "name": "cgroup_bpf_inherit",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:198",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:cgroup_setup_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226200044,
      "name": "cgroup_bpf_inherit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 540
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
int cgroup_bpf_inherit(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_bpf_inherit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285554064,
      "name": "cgroup_bpf_inherit",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:198",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_setup_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285554064,
      "name": "cgroup_bpf_inherit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 656
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
int cgroup_bpf_inherit(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_bpf_inherit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272441624,
      "name": "cgroup_bpf_inherit",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:198",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:cgroup_setup_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272441624,
      "name": "cgroup_bpf_inherit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 416
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
int cgroup_bpf_inherit(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_bpf_inherit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580934960,
      "name": "cgroup_bpf_inherit",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:198",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:cgroup_setup_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580934960,
      "name": "cgroup_bpf_inherit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 446
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
int cgroup_bpf_inherit(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_bpf_inherit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580881024,
      "name": "cgroup_bpf_inherit",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:198",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:cgroup_setup_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580881024,
      "name": "cgroup_bpf_inherit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 446
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
int cgroup_bpf_inherit(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_bpf_inherit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580926208,
      "name": "cgroup_bpf_inherit",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:198",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:cgroup_setup_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580926208,
      "name": "cgroup_bpf_inherit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 446
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
int cgroup_bpf_inherit(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_bpf_inherit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580986656,
      "name": "cgroup_bpf_inherit",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:198",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:cgroup_setup_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580986656,
      "name": "cgroup_bpf_inherit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 514
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
void cgroup_bpf_inherit(struct cgroup * cgrp, struct cgroup * parent)
```
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct cgroup * parent</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
