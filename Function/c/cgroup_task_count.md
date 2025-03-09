# Function: <code>cgroup_task_count</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cgroup_task_count",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579994931,
      "name": "cgroup_task_count",
      "external": false,
      "loc": "kernel/cgroup.c:3736",
      "file": "kernel/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup.c:pidlist_array_load"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cgroup_task_count",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580026802,
      "name": "cgroup_task_count",
      "external": false,
      "loc": "kernel/cgroup.c:3925",
      "file": "kernel/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup.c:cgroup_pidlist_start"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cgroup_task_count",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580060831,
      "name": "cgroup_task_count",
      "external": false,
      "loc": "kernel/cgroup.c:3936",
      "file": "kernel/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup.c:cgroup_pidlist_start"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int cgroup_task_count(const struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_task_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580065952,
      "name": "cgroup_task_count",
      "external": true,
      "loc": "kernel/cgroup/cgroup-v1.c:338",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580065952,
      "name": "cgroup_task_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int cgroup_task_count(const struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_task_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580118688,
      "name": "cgroup_task_count",
      "external": true,
      "loc": "kernel/cgroup/cgroup-v1.c:343",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580118688,
      "name": "cgroup_task_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
int cgroup_task_count(const struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_task_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580178048,
      "name": "cgroup_task_count",
      "external": true,
      "loc": "kernel/cgroup/cgroup-v1.c:343",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580178048,
      "name": "cgroup_task_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
int cgroup_task_count(const struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_task_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580226112,
      "name": "cgroup_task_count",
      "external": true,
      "loc": "kernel/cgroup/cgroup-v1.c:346",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580226112,
      "name": "cgroup_task_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
int cgroup_task_count(const struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_task_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580242144,
      "name": "cgroup_task_count",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:619",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580242144,
      "name": "cgroup_task_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
int cgroup_task_count(const struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_task_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580290320,
      "name": "cgroup_task_count",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:619",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580290320,
      "name": "cgroup_task_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
int cgroup_task_count(const struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_task_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580361568,
      "name": "cgroup_task_count",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:612",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580361568,
      "name": "cgroup_task_count",
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
int cgroup_task_count(const struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_task_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580348416,
      "name": "cgroup_task_count",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:609",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580348416,
      "name": "cgroup_task_count",
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
int cgroup_task_count(const struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_task_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580351536,
      "name": "cgroup_task_count",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:609",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580351536,
      "name": "cgroup_task_count",
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
int cgroup_task_count(const struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_task_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580508144,
      "name": "cgroup_task_count",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:640",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580508144,
      "name": "cgroup_task_count",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int cgroup_task_count(const struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_task_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580704496,
      "name": "cgroup_task_count",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:641",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580704496,
      "name": "cgroup_task_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
int cgroup_task_count(const struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_task_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580977552,
      "name": "cgroup_task_count",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:646",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580977552,
      "name": "cgroup_task_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
int cgroup_task_count(const struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_task_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581065392,
      "name": "cgroup_task_count",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:645",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581065392,
      "name": "cgroup_task_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
int cgroup_task_count(const struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_task_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581162768,
      "name": "cgroup_task_count",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:625",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581162768,
      "name": "cgroup_task_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
int cgroup_task_count(const struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_task_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491540392,
      "name": "cgroup_task_count",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:619",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491540392,
      "name": "cgroup_task_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
int cgroup_task_count(const struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_task_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225505496,
      "name": "cgroup_task_count",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:619",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225505496,
      "name": "cgroup_task_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int cgroup_task_count(const struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_task_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284509424,
      "name": "cgroup_task_count",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:619",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284509424,
      "name": "cgroup_task_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
int cgroup_task_count(const struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_task_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271956360,
      "name": "cgroup_task_count",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:619",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271956360,
      "name": "cgroup_task_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
int cgroup_task_count(const struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_task_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580259120,
      "name": "cgroup_task_count",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:619",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580259120,
      "name": "cgroup_task_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
int cgroup_task_count(const struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_task_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580206656,
      "name": "cgroup_task_count",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:619",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580206656,
      "name": "cgroup_task_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
int cgroup_task_count(const struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_task_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580250368,
      "name": "cgroup_task_count",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:619",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580250368,
      "name": "cgroup_task_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
int cgroup_task_count(const struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_task_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580303648,
      "name": "cgroup_task_count",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:619",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580303648,
      "name": "cgroup_task_count",
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int cgroup_task_count(const struct cgroup * cgrp)
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
