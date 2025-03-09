# Function: <code>cgroup_attach_task</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int cgroup_attach_task(struct cgroup * dst_cgrp, struct task_struct * leader, bool threadgroup)
```

```json
{
  "name": "cgroup_attach_task",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579987296,
      "name": "cgroup_attach_task",
      "external": false,
      "loc": "kernel/cgroup.c:2749",
      "file": "kernel/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_attach_task_all",
        "kernel/cgroup.c:__cgroup_procs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579987296,
      "name": "cgroup_attach_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
int cgroup_attach_task(struct cgroup * dst_cgrp, struct task_struct * leader, bool threadgroup)
```

```json
{
  "name": "cgroup_attach_task",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580016784,
      "name": "cgroup_attach_task",
      "external": false,
      "loc": "kernel/cgroup.c:2804",
      "file": "kernel/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_attach_task_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580016784,
      "name": "cgroup_attach_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
int cgroup_attach_task(struct cgroup * dst_cgrp, struct task_struct * leader, bool threadgroup)
```

```json
{
  "name": "cgroup_attach_task",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580050368,
      "name": "cgroup_attach_task",
      "external": false,
      "loc": "kernel/cgroup.c:2809",
      "file": "kernel/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_attach_task_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580050368,
      "name": "cgroup_attach_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 382
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
int cgroup_attach_task(struct cgroup * dst_cgrp, struct task_struct * leader, bool threadgroup)
```

```json
{
  "name": "cgroup_attach_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580046272,
      "name": "cgroup_attach_task",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2383",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:__cgroup_procs_write",
        "kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580046272,
      "name": "cgroup_attach_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 493
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
int cgroup_attach_task(struct cgroup * dst_cgrp, struct task_struct * leader, bool threadgroup)
```

```json
{
  "name": "cgroup_attach_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580096144,
      "name": "cgroup_attach_task",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2592",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580096144,
      "name": "cgroup_attach_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 475
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
int cgroup_attach_task(struct cgroup * dst_cgrp, struct task_struct * leader, bool threadgroup)
```

```json
{
  "name": "cgroup_attach_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580155360,
      "name": "cgroup_attach_task",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2610",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580155360,
      "name": "cgroup_attach_task",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int cgroup_attach_task(struct cgroup * dst_cgrp, struct task_struct * leader, bool threadgroup)
```

```json
{
  "name": "cgroup_attach_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580203008,
      "name": "cgroup_attach_task",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2651",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580203008,
      "name": "cgroup_attach_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 514
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
int cgroup_attach_task(struct cgroup * dst_cgrp, struct task_struct * leader, bool threadgroup)
```

```json
{
  "name": "cgroup_attach_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580250336,
      "name": "cgroup_attach_task",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2791",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580250336,
      "name": "cgroup_attach_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 523
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
int cgroup_attach_task(struct cgroup * dst_cgrp, struct task_struct * leader, bool threadgroup)
```

```json
{
  "name": "cgroup_attach_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580298576,
      "name": "cgroup_attach_task",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2792",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580298576,
      "name": "cgroup_attach_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 523
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
int cgroup_attach_task(struct cgroup * dst_cgrp, struct task_struct * leader, bool threadgroup)
```

```json
{
  "name": "cgroup_attach_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580369760,
      "name": "cgroup_attach_task",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2718",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580369760,
      "name": "cgroup_attach_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 510
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
int cgroup_attach_task(struct cgroup * dst_cgrp, struct task_struct * leader, bool threadgroup)
```

```json
{
  "name": "cgroup_attach_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580356672,
      "name": "cgroup_attach_task",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2714",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580356672,
      "name": "cgroup_attach_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 492
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
int cgroup_attach_task(struct cgroup * dst_cgrp, struct task_struct * leader, bool threadgroup)
```

```json
{
  "name": "cgroup_attach_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580359872,
      "name": "cgroup_attach_task",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2727",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:__cgroup_procs_write",
        "kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580359872,
      "name": "cgroup_attach_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 474
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
int cgroup_attach_task(struct cgroup * dst_cgrp, struct task_struct * leader, bool threadgroup)
```

```json
{
  "name": "cgroup_attach_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580518272,
      "name": "cgroup_attach_task",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2782",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:__cgroup_procs_write",
        "kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580518272,
      "name": "cgroup_attach_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 459
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
int cgroup_attach_task(struct cgroup * dst_cgrp, struct task_struct * leader, bool threadgroup)
```

```json
{
  "name": "cgroup_attach_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580715120,
      "name": "cgroup_attach_task",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2792",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:__cgroup_procs_write",
        "kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580715120,
      "name": "cgroup_attach_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 503
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
int cgroup_attach_task(struct cgroup * dst_cgrp, struct task_struct * leader, bool threadgroup)
```

```json
{
  "name": "cgroup_attach_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580989552,
      "name": "cgroup_attach_task",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2888",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:__cgroup_procs_write",
        "kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580989552,
      "name": "cgroup_attach_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 503
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
int cgroup_attach_task(struct cgroup * dst_cgrp, struct task_struct * leader, bool threadgroup)
```

```json
{
  "name": "cgroup_attach_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581077104,
      "name": "cgroup_attach_task",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2857",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:__cgroup_procs_write",
        "kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581077104,
      "name": "cgroup_attach_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 503
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
int cgroup_attach_task(struct cgroup * dst_cgrp, struct task_struct * leader, bool threadgroup)
```

```json
{
  "name": "cgroup_attach_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581174544,
      "name": "cgroup_attach_task",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2866",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:__cgroup_procs_write",
        "kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581174544,
      "name": "cgroup_attach_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 564
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
int cgroup_attach_task(struct cgroup * dst_cgrp, struct task_struct * leader, bool threadgroup)
```

```json
{
  "name": "cgroup_attach_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491549504,
      "name": "cgroup_attach_task",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2792",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491549504,
      "name": "cgroup_attach_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 644
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
int cgroup_attach_task(struct cgroup * dst_cgrp, struct task_struct * leader, bool threadgroup)
```

```json
{
  "name": "cgroup_attach_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225513860,
      "name": "cgroup_attach_task",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2792",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225513860,
      "name": "cgroup_attach_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 592
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
int cgroup_attach_task(struct cgroup * dst_cgrp, struct task_struct * leader, bool threadgroup)
```

```json
{
  "name": "cgroup_attach_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284521104,
      "name": "cgroup_attach_task",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2792",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284521104,
      "name": "cgroup_attach_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 752
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
int cgroup_attach_task(struct cgroup * dst_cgrp, struct task_struct * leader, bool threadgroup)
```

```json
{
  "name": "cgroup_attach_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271964326,
      "name": "cgroup_attach_task",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2792",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271964326,
      "name": "cgroup_attach_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 540
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
int cgroup_attach_task(struct cgroup * dst_cgrp, struct task_struct * leader, bool threadgroup)
```

```json
{
  "name": "cgroup_attach_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580267376,
      "name": "cgroup_attach_task",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2792",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580267376,
      "name": "cgroup_attach_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 523
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
int cgroup_attach_task(struct cgroup * dst_cgrp, struct task_struct * leader, bool threadgroup)
```

```json
{
  "name": "cgroup_attach_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580214880,
      "name": "cgroup_attach_task",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2792",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580214880,
      "name": "cgroup_attach_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 517
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
int cgroup_attach_task(struct cgroup * dst_cgrp, struct task_struct * leader, bool threadgroup)
```

```json
{
  "name": "cgroup_attach_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580258624,
      "name": "cgroup_attach_task",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2792",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580258624,
      "name": "cgroup_attach_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 523
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
int cgroup_attach_task(struct cgroup * dst_cgrp, struct task_struct * leader, bool threadgroup)
```

```json
{
  "name": "cgroup_attach_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580311968,
      "name": "cgroup_attach_task",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2792",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580311968,
      "name": "cgroup_attach_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 545
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
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
