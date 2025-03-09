# Function: <code>compute_effective_progs</code>

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
int compute_effective_progs(struct cgroup * cgrp, enum bpf_attach_type type, struct bpf_prog_array * * array)
```

```json
{
  "name": "compute_effective_progs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580623664,
      "name": "compute_effective_progs",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:94",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580623664,
      "name": "compute_effective_progs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 266
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
int compute_effective_progs(struct cgroup * cgrp, enum bpf_attach_type type, struct bpf_prog_array * * array)
```

```json
{
  "name": "compute_effective_progs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580752064,
      "name": "compute_effective_progs",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:94",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580752064,
      "name": "compute_effective_progs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 242
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
int compute_effective_progs(struct cgroup * cgrp, enum bpf_attach_type type, struct bpf_prog_array * * array)
```

```json
{
  "name": "compute_effective_progs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580816544,
      "name": "compute_effective_progs",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:99",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580816544,
      "name": "compute_effective_progs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
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
int compute_effective_progs(struct cgroup * cgrp, enum bpf_attach_type type, struct bpf_prog_array * * array)
```

```json
{
  "name": "compute_effective_progs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580905952,
      "name": "compute_effective_progs",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:135",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580905952,
      "name": "compute_effective_progs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 299
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
int compute_effective_progs(struct cgroup * cgrp, enum bpf_attach_type type, struct bpf_prog_array * * array)
```

```json
{
  "name": "compute_effective_progs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580959136,
      "name": "compute_effective_progs",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:138",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580959136,
      "name": "compute_effective_progs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
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
int compute_effective_progs(struct cgroup * cgrp, enum bpf_attach_type type, struct bpf_prog_array * * array)
```

```json
{
  "name": "compute_effective_progs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581127088,
      "name": "compute_effective_progs",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:212",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581127088,
      "name": "compute_effective_progs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 313
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
int compute_effective_progs(struct cgroup * cgrp, enum bpf_attach_type type, struct bpf_prog_array * * array)
```

```json
{
  "name": "compute_effective_progs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581160528,
      "name": "compute_effective_progs",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:227",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581160528,
      "name": "compute_effective_progs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 321
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
int compute_effective_progs(struct cgroup * cgrp, enum bpf_attach_type type, struct bpf_prog_array * * array)
```

```json
{
  "name": "compute_effective_progs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581174736,
      "name": "compute_effective_progs",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:227",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581174736,
      "name": "compute_effective_progs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 321
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
int compute_effective_progs(struct cgroup * cgrp, enum cgroup_bpf_attach_type atype, struct bpf_prog_array * * array)
```

```json
{
  "name": "compute_effective_progs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581415152,
      "name": "compute_effective_progs",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:227",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581415152,
      "name": "compute_effective_progs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 672
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
int compute_effective_progs(struct cgroup * cgrp, enum cgroup_bpf_attach_type atype, struct bpf_prog_array * * array)
```

```json
{
  "name": "compute_effective_progs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581741104,
      "name": "compute_effective_progs",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:266",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581741104,
      "name": "compute_effective_progs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 696
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
int compute_effective_progs(struct cgroup * cgrp, enum cgroup_bpf_attach_type atype, struct bpf_prog_array * * array)
```

```json
{
  "name": "compute_effective_progs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582152704,
      "name": "compute_effective_progs",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:401",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582152704,
      "name": "compute_effective_progs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 489
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
int compute_effective_progs(struct cgroup * cgrp, enum cgroup_bpf_attach_type atype, struct bpf_prog_array * * array)
```

```json
{
  "name": "compute_effective_progs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582350144,
      "name": "compute_effective_progs",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:401",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582350144,
      "name": "compute_effective_progs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 524
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
int compute_effective_progs(struct cgroup * cgrp, enum cgroup_bpf_attach_type atype, struct bpf_prog_array * * array)
```

```json
{
  "name": "compute_effective_progs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582516928,
      "name": "compute_effective_progs",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:401",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582516928,
      "name": "compute_effective_progs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 523
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
int compute_effective_progs(struct cgroup * cgrp, enum bpf_attach_type type, struct bpf_prog_array * * array)
```

```json
{
  "name": "compute_effective_progs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492304760,
      "name": "compute_effective_progs",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:138",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492304760,
      "name": "compute_effective_progs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
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
int compute_effective_progs(struct cgroup * cgrp, enum bpf_attach_type type, struct bpf_prog_array * * array)
```

```json
{
  "name": "compute_effective_progs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226189936,
      "name": "compute_effective_progs",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:138",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226189936,
      "name": "compute_effective_progs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
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
int compute_effective_progs(struct cgroup * cgrp, enum bpf_attach_type type, struct bpf_prog_array * * array)
```

```json
{
  "name": "compute_effective_progs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285542464,
      "name": "compute_effective_progs",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:138",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285542464,
      "name": "compute_effective_progs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 456
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
int compute_effective_progs(struct cgroup * cgrp, enum bpf_attach_type type, struct bpf_prog_array * * array)
```

```json
{
  "name": "compute_effective_progs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272434042,
      "name": "compute_effective_progs",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:138",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272434042,
      "name": "compute_effective_progs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
int compute_effective_progs(struct cgroup * cgrp, enum bpf_attach_type type, struct bpf_prog_array * * array)
```

```json
{
  "name": "compute_effective_progs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580927936,
      "name": "compute_effective_progs",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:138",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580927936,
      "name": "compute_effective_progs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
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
int compute_effective_progs(struct cgroup * cgrp, enum bpf_attach_type type, struct bpf_prog_array * * array)
```

```json
{
  "name": "compute_effective_progs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580874000,
      "name": "compute_effective_progs",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:138",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580874000,
      "name": "compute_effective_progs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
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
int compute_effective_progs(struct cgroup * cgrp, enum bpf_attach_type type, struct bpf_prog_array * * array)
```

```json
{
  "name": "compute_effective_progs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580919184,
      "name": "compute_effective_progs",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:138",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580919184,
      "name": "compute_effective_progs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
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
int compute_effective_progs(struct cgroup * cgrp, enum bpf_attach_type type, struct bpf_prog_array * * array)
```

```json
{
  "name": "compute_effective_progs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580979280,
      "name": "compute_effective_progs",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:138",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:update_effective_progs",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580979280,
      "name": "compute_effective_progs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
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
int compute_effective_progs(struct cgroup * cgrp, enum bpf_attach_type type, struct bpf_prog_array * * array)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum cgroup_bpf_attach_type atype</code>
</li>
<li>
<b>Param removed. </b>
<code>enum bpf_attach_type type</code>
</li>
</ul>
</details>
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
