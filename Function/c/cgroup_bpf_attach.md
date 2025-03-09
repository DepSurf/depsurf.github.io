# Function: <code>cgroup_bpf_attach</code>

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
int cgroup_bpf_attach(struct cgroup * cgrp, struct bpf_prog * prog, enum bpf_attach_type type, u32 flags)
```

```json
{
  "name": "cgroup_bpf_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580111360,
      "name": "cgroup_bpf_attach",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:5845",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:SyS_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580111360,
      "name": "cgroup_bpf_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
int cgroup_bpf_attach(struct cgroup * cgrp, struct bpf_prog * prog, enum bpf_attach_type type, u32 flags)
```

```json
{
  "name": "cgroup_bpf_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580170528,
      "name": "cgroup_bpf_attach",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:5883",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580170528,
      "name": "cgroup_bpf_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
int cgroup_bpf_attach(struct cgroup * cgrp, struct bpf_prog * prog, enum bpf_attach_type type, u32 flags)
```

```json
{
  "name": "cgroup_bpf_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580218416,
      "name": "cgroup_bpf_attach",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:5986",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580218416,
      "name": "cgroup_bpf_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
int cgroup_bpf_attach(struct cgroup * cgrp, struct bpf_prog * prog, enum bpf_attach_type type, u32 flags)
```

```json
{
  "name": "cgroup_bpf_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580267248,
      "name": "cgroup_bpf_attach",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:6410",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580267248,
      "name": "cgroup_bpf_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
int cgroup_bpf_attach(struct cgroup * cgrp, struct bpf_prog * prog, enum bpf_attach_type type, u32 flags)
```

```json
{
  "name": "cgroup_bpf_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580315568,
      "name": "cgroup_bpf_attach",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:6429",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580315568,
      "name": "cgroup_bpf_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
int cgroup_bpf_attach(struct cgroup * cgrp, struct bpf_prog * prog, struct bpf_prog * replace_prog, struct bpf_cgroup_link * link, enum bpf_attach_type type, u32 flags)
```

```json
{
  "name": "cgroup_bpf_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580387024,
      "name": "cgroup_bpf_attach",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:6496",
      "file": "kernel/cgroup/cgroup.c",
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
      "addr": 18446744071580387024,
      "name": "cgroup_bpf_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int cgroup_bpf_attach(struct cgroup * cgrp, struct bpf_prog * prog, struct bpf_prog * replace_prog, struct bpf_cgroup_link * link, enum bpf_attach_type type, u32 flags)
```

```json
{
  "name": "cgroup_bpf_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580374160,
      "name": "cgroup_bpf_attach",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:6488",
      "file": "kernel/cgroup/cgroup.c",
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
      "addr": 18446744071580374160,
      "name": "cgroup_bpf_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int cgroup_bpf_attach(struct cgroup * cgrp, struct bpf_prog * prog, struct bpf_prog * replace_prog, struct bpf_cgroup_link * link, enum bpf_attach_type type, u32 flags)
```

```json
{
  "name": "cgroup_bpf_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580377088,
      "name": "cgroup_bpf_attach",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:6466",
      "file": "kernel/cgroup/cgroup.c",
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
      "addr": 18446744071580377088,
      "name": "cgroup_bpf_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int cgroup_bpf_attach(struct cgroup * cgrp, struct bpf_prog * prog, struct bpf_prog * replace_prog, struct bpf_cgroup_link * link, enum bpf_attach_type type, u32 flags)
```

```json
{
  "name": "cgroup_bpf_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580538304,
      "name": "cgroup_bpf_attach",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:6689",
      "file": "kernel/cgroup/cgroup.c",
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
      "addr": 18446744071580538304,
      "name": "cgroup_bpf_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cgroup_bpf_attach",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581749407,
      "name": "cgroup_bpf_attach",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:565",
      "file": "kernel/bpf/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_link_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cgroup_bpf_attach",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582164399,
      "name": "cgroup_bpf_attach",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:724",
      "file": "kernel/bpf/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_link_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cgroup_bpf_attach",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582361327,
      "name": "cgroup_bpf_attach",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:724",
      "file": "kernel/bpf/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_link_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cgroup_bpf_attach",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582528221,
      "name": "cgroup_bpf_attach",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:724",
      "file": "kernel/bpf/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_link_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int cgroup_bpf_attach(struct cgroup * cgrp, struct bpf_prog * prog, enum bpf_attach_type type, u32 flags)
```

```json
{
  "name": "cgroup_bpf_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491568800,
      "name": "cgroup_bpf_attach",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:6429",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491568800,
      "name": "cgroup_bpf_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
int cgroup_bpf_attach(struct cgroup * cgrp, struct bpf_prog * prog, enum bpf_attach_type type, u32 flags)
```

```json
{
  "name": "cgroup_bpf_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225533792,
      "name": "cgroup_bpf_attach",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:6429",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225533792,
      "name": "cgroup_bpf_attach",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int cgroup_bpf_attach(struct cgroup * cgrp, struct bpf_prog * prog, enum bpf_attach_type type, u32 flags)
```

```json
{
  "name": "cgroup_bpf_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284548640,
      "name": "cgroup_bpf_attach",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:6429",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284548640,
      "name": "cgroup_bpf_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
int cgroup_bpf_attach(struct cgroup * cgrp, struct bpf_prog * prog, enum bpf_attach_type type, u32 flags)
```

```json
{
  "name": "cgroup_bpf_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271982222,
      "name": "cgroup_bpf_attach",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:6429",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271982222,
      "name": "cgroup_bpf_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int cgroup_bpf_attach(struct cgroup * cgrp, struct bpf_prog * prog, enum bpf_attach_type type, u32 flags)
```

```json
{
  "name": "cgroup_bpf_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580284368,
      "name": "cgroup_bpf_attach",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:6429",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580284368,
      "name": "cgroup_bpf_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
int cgroup_bpf_attach(struct cgroup * cgrp, struct bpf_prog * prog, enum bpf_attach_type type, u32 flags)
```

```json
{
  "name": "cgroup_bpf_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580231776,
      "name": "cgroup_bpf_attach",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:6429",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580231776,
      "name": "cgroup_bpf_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
int cgroup_bpf_attach(struct cgroup * cgrp, struct bpf_prog * prog, enum bpf_attach_type type, u32 flags)
```

```json
{
  "name": "cgroup_bpf_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580275616,
      "name": "cgroup_bpf_attach",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:6429",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580275616,
      "name": "cgroup_bpf_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
int cgroup_bpf_attach(struct cgroup * cgrp, struct bpf_prog * prog, enum bpf_attach_type type, u32 flags)
```

```json
{
  "name": "cgroup_bpf_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580329424,
      "name": "cgroup_bpf_attach",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:6429",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580329424,
      "name": "cgroup_bpf_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
int cgroup_bpf_attach(struct cgroup * cgrp, struct bpf_prog * prog, enum bpf_attach_type type, u32 flags)
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
int cgroup_bpf_attach(struct cgroup * cgrp, struct bpf_prog * prog, struct bpf_prog * replace_prog, struct bpf_cgroup_link * link, enum bpf_attach_type type, u32 flags)
```
</details>
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
