# Function: <code>cgroup_freeze</code>

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
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void cgroup_freeze(struct cgroup * cgrp, bool freeze)
```

```json
{
  "name": "cgroup_freeze",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580279872,
      "name": "cgroup_freeze",
      "external": true,
      "loc": "kernel/cgroup/freezer.c:251",
      "file": "kernel/cgroup/freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_freeze_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580279872,
      "name": "cgroup_freeze",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void cgroup_freeze(struct cgroup * cgrp, bool freeze)
```

```json
{
  "name": "cgroup_freeze",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580328032,
      "name": "cgroup_freeze",
      "external": true,
      "loc": "kernel/cgroup/freezer.c:260",
      "file": "kernel/cgroup/freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_freeze_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580328032,
      "name": "cgroup_freeze",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void cgroup_freeze(struct cgroup * cgrp, bool freeze)
```

```json
{
  "name": "cgroup_freeze",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580400560,
      "name": "cgroup_freeze",
      "external": true,
      "loc": "kernel/cgroup/freezer.c:260",
      "file": "kernel/cgroup/freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_freeze_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580400560,
      "name": "cgroup_freeze",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void cgroup_freeze(struct cgroup * cgrp, bool freeze)
```

```json
{
  "name": "cgroup_freeze",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580387840,
      "name": "cgroup_freeze",
      "external": true,
      "loc": "kernel/cgroup/freezer.c:260",
      "file": "kernel/cgroup/freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_freeze_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580387840,
      "name": "cgroup_freeze",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 334
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
void cgroup_freeze(struct cgroup * cgrp, bool freeze)
```

```json
{
  "name": "cgroup_freeze",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580390768,
      "name": "cgroup_freeze",
      "external": true,
      "loc": "kernel/cgroup/freezer.c:260",
      "file": "kernel/cgroup/freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_freeze_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580390768,
      "name": "cgroup_freeze",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 334
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void cgroup_freeze(struct cgroup * cgrp, bool freeze)
```

```json
{
  "name": "cgroup_freeze",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cgroup_freeze",
      "external": true,
      "loc": "kernel/cgroup/freezer.c:260",
      "file": "kernel/cgroup/freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_freeze_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592161774,
      "name": "cgroup_freeze.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580552832,
      "name": "cgroup_freeze",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 344
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
void cgroup_freeze(struct cgroup * cgrp, bool freeze)
```

```json
{
  "name": "cgroup_freeze",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cgroup_freeze",
      "external": true,
      "loc": "kernel/cgroup/freezer.c:260",
      "file": "kernel/cgroup/freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_freeze_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593934835,
      "name": "cgroup_freeze.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580751520,
      "name": "cgroup_freeze",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 395
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
void cgroup_freeze(struct cgroup * cgrp, bool freeze)
```

```json
{
  "name": "cgroup_freeze",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cgroup_freeze",
      "external": true,
      "loc": "kernel/cgroup/freezer.c:260",
      "file": "kernel/cgroup/freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_freeze_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596000277,
      "name": "cgroup_freeze.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071581028992,
      "name": "cgroup_freeze",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 408
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
void cgroup_freeze(struct cgroup * cgrp, bool freeze)
```

```json
{
  "name": "cgroup_freeze",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cgroup_freeze",
      "external": true,
      "loc": "kernel/cgroup/freezer.c:260",
      "file": "kernel/cgroup/freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_freeze_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596518440,
      "name": "cgroup_freeze.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071581117360,
      "name": "cgroup_freeze",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 408
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
void cgroup_freeze(struct cgroup * cgrp, bool freeze)
```

```json
{
  "name": "cgroup_freeze",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cgroup_freeze",
      "external": true,
      "loc": "kernel/cgroup/freezer.c:260",
      "file": "kernel/cgroup/freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_freeze_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597418683,
      "name": "cgroup_freeze.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071581215600,
      "name": "cgroup_freeze",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 408
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
void cgroup_freeze(struct cgroup * cgrp, bool freeze)
```

```json
{
  "name": "cgroup_freeze",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491588136,
      "name": "cgroup_freeze",
      "external": true,
      "loc": "kernel/cgroup/freezer.c:260",
      "file": "kernel/cgroup/freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_freeze_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491588136,
      "name": "cgroup_freeze",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 488
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
void cgroup_freeze(struct cgroup * cgrp, bool freeze)
```

```json
{
  "name": "cgroup_freeze",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225548256,
      "name": "cgroup_freeze",
      "external": true,
      "loc": "kernel/cgroup/freezer.c:260",
      "file": "kernel/cgroup/freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_freeze_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225548256,
      "name": "cgroup_freeze",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1204
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
void cgroup_freeze(struct cgroup * cgrp, bool freeze)
```

```json
{
  "name": "cgroup_freeze",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284570048,
      "name": "cgroup_freeze",
      "external": true,
      "loc": "kernel/cgroup/freezer.c:260",
      "file": "kernel/cgroup/freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_freeze_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284570048,
      "name": "cgroup_freeze",
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
void cgroup_freeze(struct cgroup * cgrp, bool freeze)
```

```json
{
  "name": "cgroup_freeze",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271995668,
      "name": "cgroup_freeze",
      "external": true,
      "loc": "kernel/cgroup/freezer.c:260",
      "file": "kernel/cgroup/freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_freeze_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271995668,
      "name": "cgroup_freeze",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 362
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
void cgroup_freeze(struct cgroup * cgrp, bool freeze)
```

```json
{
  "name": "cgroup_freeze",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580296832,
      "name": "cgroup_freeze",
      "external": true,
      "loc": "kernel/cgroup/freezer.c:260",
      "file": "kernel/cgroup/freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_freeze_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580296832,
      "name": "cgroup_freeze",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void cgroup_freeze(struct cgroup * cgrp, bool freeze)
```

```json
{
  "name": "cgroup_freeze",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580244176,
      "name": "cgroup_freeze",
      "external": true,
      "loc": "kernel/cgroup/freezer.c:260",
      "file": "kernel/cgroup/freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_freeze_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580244176,
      "name": "cgroup_freeze",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void cgroup_freeze(struct cgroup * cgrp, bool freeze)
```

```json
{
  "name": "cgroup_freeze",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580288080,
      "name": "cgroup_freeze",
      "external": true,
      "loc": "kernel/cgroup/freezer.c:260",
      "file": "kernel/cgroup/freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_freeze_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580288080,
      "name": "cgroup_freeze",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void cgroup_freeze(struct cgroup * cgrp, bool freeze)
```

```json
{
  "name": "cgroup_freeze",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580342192,
      "name": "cgroup_freeze",
      "external": true,
      "loc": "kernel/cgroup/freezer.c:260",
      "file": "kernel/cgroup/freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_freeze_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580342192,
      "name": "cgroup_freeze",
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void cgroup_freeze(struct cgroup * cgrp, bool freeze)
```
</details>
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
