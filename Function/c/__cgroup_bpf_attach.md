# Function: <code>__cgroup_bpf_attach</code>

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
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int __cgroup_bpf_attach(struct cgroup * cgrp, struct bpf_prog * prog, enum bpf_attach_type type, u32 flags)
```

```json
{
  "name": "__cgroup_bpf_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580625040,
      "name": "__cgroup_bpf_attach",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:187",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_bpf_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580625040,
      "name": "__cgroup_bpf_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 901
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
int __cgroup_bpf_attach(struct cgroup * cgrp, struct bpf_prog * prog, enum bpf_attach_type type, u32 flags)
```

```json
{
  "name": "__cgroup_bpf_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580753712,
      "name": "__cgroup_bpf_attach",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:186",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_bpf_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580753712,
      "name": "__cgroup_bpf_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 917
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
int __cgroup_bpf_attach(struct cgroup * cgrp, struct bpf_prog * prog, enum bpf_attach_type type, u32 flags)
```

```json
{
  "name": "__cgroup_bpf_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580818624,
      "name": "__cgroup_bpf_attach",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:236",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_bpf_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580818624,
      "name": "__cgroup_bpf_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1130
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
int __cgroup_bpf_attach(struct cgroup * cgrp, struct bpf_prog * prog, enum bpf_attach_type type, u32 flags)
```

```json
{
  "name": "__cgroup_bpf_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580913168,
      "name": "__cgroup_bpf_attach",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:291",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_bpf_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580913168,
      "name": "__cgroup_bpf_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1158
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
int __cgroup_bpf_attach(struct cgroup * cgrp, struct bpf_prog * prog, enum bpf_attach_type type, u32 flags)
```

```json
{
  "name": "__cgroup_bpf_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580966608,
      "name": "__cgroup_bpf_attach",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:301",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_bpf_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580966608,
      "name": "__cgroup_bpf_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1176
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
int __cgroup_bpf_attach(struct cgroup * cgrp, struct bpf_prog * prog, struct bpf_prog * replace_prog, struct bpf_cgroup_link * link, enum bpf_attach_type type, u32 flags)
```

```json
{
  "name": "__cgroup_bpf_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581128288,
      "name": "__cgroup_bpf_attach",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:416",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_bpf_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581128288,
      "name": "__cgroup_bpf_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1519
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
int __cgroup_bpf_attach(struct cgroup * cgrp, struct bpf_prog * prog, struct bpf_prog * replace_prog, struct bpf_cgroup_link * link, enum bpf_attach_type type, u32 flags)
```

```json
{
  "name": "__cgroup_bpf_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581162400,
      "name": "__cgroup_bpf_attach",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:433",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_bpf_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581162400,
      "name": "__cgroup_bpf_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1392
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
int __cgroup_bpf_attach(struct cgroup * cgrp, struct bpf_prog * prog, struct bpf_prog * replace_prog, struct bpf_cgroup_link * link, enum bpf_attach_type type, u32 flags)
```

```json
{
  "name": "__cgroup_bpf_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581179376,
      "name": "__cgroup_bpf_attach",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:433",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_bpf_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581179376,
      "name": "__cgroup_bpf_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1381
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
int __cgroup_bpf_attach(struct cgroup * cgrp, struct bpf_prog * prog, struct bpf_prog * replace_prog, struct bpf_cgroup_link * link, enum bpf_attach_type type, u32 flags)
```

```json
{
  "name": "__cgroup_bpf_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581419040,
      "name": "__cgroup_bpf_attach",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:433",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_bpf_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581419040,
      "name": "__cgroup_bpf_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1924
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
int __cgroup_bpf_attach(struct cgroup * cgrp, struct bpf_prog * prog, struct bpf_prog * replace_prog, struct bpf_cgroup_link * link, enum bpf_attach_type type, u32 flags)
```

```json
{
  "name": "__cgroup_bpf_attach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581745712,
      "name": "__cgroup_bpf_attach",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:472",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:cgroup_bpf_link_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581745712,
      "name": "__cgroup_bpf_attach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1919
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
int __cgroup_bpf_attach(struct cgroup * cgrp, struct bpf_prog * prog, struct bpf_prog * replace_prog, struct bpf_cgroup_link * link, enum bpf_attach_type type, u32 flags)
```

```json
{
  "name": "__cgroup_bpf_attach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582157440,
      "name": "__cgroup_bpf_attach",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:607",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:cgroup_bpf_link_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582157440,
      "name": "__cgroup_bpf_attach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1958
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
int __cgroup_bpf_attach(struct cgroup * cgrp, struct bpf_prog * prog, struct bpf_prog * replace_prog, struct bpf_cgroup_link * link, enum bpf_attach_type type, u32 flags)
```

```json
{
  "name": "__cgroup_bpf_attach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582354912,
      "name": "__cgroup_bpf_attach",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:607",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:cgroup_bpf_link_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582354912,
      "name": "__cgroup_bpf_attach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2018
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
int __cgroup_bpf_attach(struct cgroup * cgrp, struct bpf_prog * prog, struct bpf_prog * replace_prog, struct bpf_cgroup_link * link, enum bpf_attach_type type, u32 flags)
```

```json
{
  "name": "__cgroup_bpf_attach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582521696,
      "name": "__cgroup_bpf_attach",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:607",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:cgroup_bpf_link_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582521696,
      "name": "__cgroup_bpf_attach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2065
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
int __cgroup_bpf_attach(struct cgroup * cgrp, struct bpf_prog * prog, enum bpf_attach_type type, u32 flags)
```

```json
{
  "name": "__cgroup_bpf_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492315080,
      "name": "__cgroup_bpf_attach",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:301",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_bpf_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492315080,
      "name": "__cgroup_bpf_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1068
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
int __cgroup_bpf_attach(struct cgroup * cgrp, struct bpf_prog * prog, enum bpf_attach_type type, u32 flags)
```

```json
{
  "name": "__cgroup_bpf_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226200584,
      "name": "__cgroup_bpf_attach",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:301",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_bpf_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226200584,
      "name": "__cgroup_bpf_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1312
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
int __cgroup_bpf_attach(struct cgroup * cgrp, struct bpf_prog * prog, enum bpf_attach_type type, u32 flags)
```

```json
{
  "name": "__cgroup_bpf_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285554720,
      "name": "__cgroup_bpf_attach",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:301",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_bpf_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285554720,
      "name": "__cgroup_bpf_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1432
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
int __cgroup_bpf_attach(struct cgroup * cgrp, struct bpf_prog * prog, enum bpf_attach_type type, u32 flags)
```

```json
{
  "name": "__cgroup_bpf_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272442040,
      "name": "__cgroup_bpf_attach",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:301",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_bpf_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272442040,
      "name": "__cgroup_bpf_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 968
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
int __cgroup_bpf_attach(struct cgroup * cgrp, struct bpf_prog * prog, enum bpf_attach_type type, u32 flags)
```

```json
{
  "name": "__cgroup_bpf_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580935408,
      "name": "__cgroup_bpf_attach",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:301",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_bpf_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580935408,
      "name": "__cgroup_bpf_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1176
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
int __cgroup_bpf_attach(struct cgroup * cgrp, struct bpf_prog * prog, enum bpf_attach_type type, u32 flags)
```

```json
{
  "name": "__cgroup_bpf_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580881472,
      "name": "__cgroup_bpf_attach",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:301",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_bpf_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580881472,
      "name": "__cgroup_bpf_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1176
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
int __cgroup_bpf_attach(struct cgroup * cgrp, struct bpf_prog * prog, enum bpf_attach_type type, u32 flags)
```

```json
{
  "name": "__cgroup_bpf_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580926656,
      "name": "__cgroup_bpf_attach",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:301",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_bpf_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580926656,
      "name": "__cgroup_bpf_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1176
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
int __cgroup_bpf_attach(struct cgroup * cgrp, struct bpf_prog * prog, enum bpf_attach_type type, u32 flags)
```

```json
{
  "name": "__cgroup_bpf_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580987184,
      "name": "__cgroup_bpf_attach",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:301",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_bpf_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580987184,
      "name": "__cgroup_bpf_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1176
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
int __cgroup_bpf_attach(struct cgroup * cgrp, struct bpf_prog * prog, enum bpf_attach_type type, u32 flags)
```
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct bpf_prog * replace_prog</code>
</li>
<li>
<b>Param added. </b>
<code>struct bpf_cgroup_link * link</code>
</li>
<li>
<b>Param reordered. </b>
<code>cgrp, prog, type, flags</code> ➡️ <code>cgrp, prog, replace_prog, link, type, flags</code>
</li>
</ul>
</details>
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
