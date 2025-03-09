# Function: <code>__cgroup_bpf_detach</code>

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
int __cgroup_bpf_detach(struct cgroup * cgrp, struct bpf_prog * prog, enum bpf_attach_type type, u32 unused_flags)
```

```json
{
  "name": "__cgroup_bpf_detach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580625952,
      "name": "__cgroup_bpf_detach",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:296",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_bpf_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580625952,
      "name": "__cgroup_bpf_detach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 524
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
int __cgroup_bpf_detach(struct cgroup * cgrp, struct bpf_prog * prog, enum bpf_attach_type type, u32 unused_flags)
```

```json
{
  "name": "__cgroup_bpf_detach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580754640,
      "name": "__cgroup_bpf_detach",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:295",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_bpf_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580754640,
      "name": "__cgroup_bpf_detach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 526
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
int __cgroup_bpf_detach(struct cgroup * cgrp, struct bpf_prog * prog, enum bpf_attach_type type, u32 unused_flags)
```

```json
{
  "name": "__cgroup_bpf_detach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580819760,
      "name": "__cgroup_bpf_detach",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:365",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_bpf_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580819760,
      "name": "__cgroup_bpf_detach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 317
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
int __cgroup_bpf_detach(struct cgroup * cgrp, struct bpf_prog * prog, enum bpf_attach_type type)
```

```json
{
  "name": "__cgroup_bpf_detach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580914336,
      "name": "__cgroup_bpf_detach",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:420",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_bpf_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580914336,
      "name": "__cgroup_bpf_detach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
int __cgroup_bpf_detach(struct cgroup * cgrp, struct bpf_prog * prog, enum bpf_attach_type type)
```

```json
{
  "name": "__cgroup_bpf_detach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580967792,
      "name": "__cgroup_bpf_detach",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:430",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_bpf_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580967792,
      "name": "__cgroup_bpf_detach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
int __cgroup_bpf_detach(struct cgroup * cgrp, struct bpf_prog * prog, struct bpf_cgroup_link * link, enum bpf_attach_type type)
```

```json
{
  "name": "__cgroup_bpf_detach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581129808,
      "name": "__cgroup_bpf_detach",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:654",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_bpf_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581129808,
      "name": "__cgroup_bpf_detach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 454
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
int __cgroup_bpf_detach(struct cgroup * cgrp, struct bpf_prog * prog, struct bpf_cgroup_link * link, enum bpf_attach_type type)
```

```json
{
  "name": "__cgroup_bpf_detach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581163792,
      "name": "__cgroup_bpf_detach",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:667",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_bpf_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581163792,
      "name": "__cgroup_bpf_detach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 431
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
int __cgroup_bpf_detach(struct cgroup * cgrp, struct bpf_prog * prog, struct bpf_cgroup_link * link, enum bpf_attach_type type)
```

```json
{
  "name": "__cgroup_bpf_detach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581180768,
      "name": "__cgroup_bpf_detach",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:667",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_bpf_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581180768,
      "name": "__cgroup_bpf_detach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 442
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
int __cgroup_bpf_detach(struct cgroup * cgrp, struct bpf_prog * prog, struct bpf_cgroup_link * link, enum bpf_attach_type type)
```

```json
{
  "name": "__cgroup_bpf_detach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581420976,
      "name": "__cgroup_bpf_detach",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:681",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_bpf_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581420976,
      "name": "__cgroup_bpf_detach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 686
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
int __cgroup_bpf_detach(struct cgroup * cgrp, struct bpf_prog * prog, struct bpf_cgroup_link * link, enum bpf_attach_type type)
```

```json
{
  "name": "__cgroup_bpf_detach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__cgroup_bpf_detach",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:788",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:bpf_cgroup_link_release",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581742208,
      "name": "__cgroup_bpf_detach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1265
    },
    {
      "addr": 18446744071593962383,
      "name": "__cgroup_bpf_detach.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
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
int __cgroup_bpf_detach(struct cgroup * cgrp, struct bpf_prog * prog, struct bpf_cgroup_link * link, enum bpf_attach_type type)
```

```json
{
  "name": "__cgroup_bpf_detach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__cgroup_bpf_detach",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:949",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:bpf_cgroup_link_release",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582153632,
      "name": "__cgroup_bpf_detach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1161
    },
    {
      "addr": 18446744071596022849,
      "name": "__cgroup_bpf_detach.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
int __cgroup_bpf_detach(struct cgroup * cgrp, struct bpf_prog * prog, struct bpf_cgroup_link * link, enum bpf_attach_type type)
```

```json
{
  "name": "__cgroup_bpf_detach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__cgroup_bpf_detach",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:949",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:bpf_cgroup_link_release",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582351104,
      "name": "__cgroup_bpf_detach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1177
    },
    {
      "addr": 18446744071596544889,
      "name": "__cgroup_bpf_detach.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
int __cgroup_bpf_detach(struct cgroup * cgrp, struct bpf_prog * prog, struct bpf_cgroup_link * link, enum bpf_attach_type type)
```

```json
{
  "name": "__cgroup_bpf_detach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__cgroup_bpf_detach",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:950",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:bpf_cgroup_link_release",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582517888,
      "name": "__cgroup_bpf_detach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1176
    },
    {
      "addr": 18446744071597448584,
      "name": "__cgroup_bpf_detach.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
int __cgroup_bpf_detach(struct cgroup * cgrp, struct bpf_prog * prog, enum bpf_attach_type type)
```

```json
{
  "name": "__cgroup_bpf_detach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492316152,
      "name": "__cgroup_bpf_detach",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:430",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_bpf_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492316152,
      "name": "__cgroup_bpf_detach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
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
int __cgroup_bpf_detach(struct cgroup * cgrp, struct bpf_prog * prog, enum bpf_attach_type type)
```

```json
{
  "name": "__cgroup_bpf_detach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226201896,
      "name": "__cgroup_bpf_detach",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:430",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_bpf_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226201896,
      "name": "__cgroup_bpf_detach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 400
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
int __cgroup_bpf_detach(struct cgroup * cgrp, struct bpf_prog * prog, enum bpf_attach_type type)
```

```json
{
  "name": "__cgroup_bpf_detach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285556160,
      "name": "__cgroup_bpf_detach",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:430",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_bpf_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285556160,
      "name": "__cgroup_bpf_detach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 544
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
int __cgroup_bpf_detach(struct cgroup * cgrp, struct bpf_prog * prog, enum bpf_attach_type type)
```

```json
{
  "name": "__cgroup_bpf_detach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272443008,
      "name": "__cgroup_bpf_detach",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:430",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_bpf_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272443008,
      "name": "__cgroup_bpf_detach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 326
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
int __cgroup_bpf_detach(struct cgroup * cgrp, struct bpf_prog * prog, enum bpf_attach_type type)
```

```json
{
  "name": "__cgroup_bpf_detach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580936592,
      "name": "__cgroup_bpf_detach",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:430",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_bpf_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580936592,
      "name": "__cgroup_bpf_detach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
int __cgroup_bpf_detach(struct cgroup * cgrp, struct bpf_prog * prog, enum bpf_attach_type type)
```

```json
{
  "name": "__cgroup_bpf_detach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580882656,
      "name": "__cgroup_bpf_detach",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:430",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_bpf_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580882656,
      "name": "__cgroup_bpf_detach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
int __cgroup_bpf_detach(struct cgroup * cgrp, struct bpf_prog * prog, enum bpf_attach_type type)
```

```json
{
  "name": "__cgroup_bpf_detach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580927840,
      "name": "__cgroup_bpf_detach",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:430",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_bpf_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580927840,
      "name": "__cgroup_bpf_detach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
int __cgroup_bpf_detach(struct cgroup * cgrp, struct bpf_prog * prog, enum bpf_attach_type type)
```

```json
{
  "name": "__cgroup_bpf_detach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580988368,
      "name": "__cgroup_bpf_detach",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:430",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_bpf_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580988368,
      "name": "__cgroup_bpf_detach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
int __cgroup_bpf_detach(struct cgroup * cgrp, struct bpf_prog * prog, enum bpf_attach_type type, u32 unused_flags)
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
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>u32 unused_flags</code>
</li>
</ul>
</details>
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
<code>struct bpf_cgroup_link * link</code>
</li>
<li>
<b>Param reordered. </b>
<code>cgrp, prog, type</code> ➡️ <code>cgrp, prog, link, type</code>
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
