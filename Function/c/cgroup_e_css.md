# Function: <code>cgroup_e_css</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct cgroup_subsys_state * cgroup_e_css(struct cgroup * cgrp, struct cgroup_subsys * ss)
```

```json
{
  "name": "cgroup_e_css",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579966928,
      "name": "cgroup_e_css",
      "external": false,
      "loc": "kernel/cgroup.c:384",
      "file": "kernel/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:find_css_set",
        "kernel/cgroup.c:cgroup_taskset_migrate",
        "kernel/cgroup.c:cgroup_taskset_migrate",
        "kernel/cgroup.c:cgroup_taskset_migrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579966928,
      "name": "cgroup_e_css",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cgroup_e_css",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580009432,
      "name": "cgroup_e_css",
      "external": false,
      "loc": "kernel/cgroup.c:427",
      "file": "kernel/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup.c:find_css_set"
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
  "name": "cgroup_e_css",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580043016,
      "name": "cgroup_e_css",
      "external": false,
      "loc": "kernel/cgroup.c:430",
      "file": "kernel/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup.c:find_css_set"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cgroup_e_css",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580039826,
      "name": "cgroup_e_css",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:385",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:find_css_set"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cgroup_e_css",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580090083,
      "name": "cgroup_e_css",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:498",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:find_css_set"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cgroup_e_css",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580149224,
      "name": "cgroup_e_css",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:501",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:find_css_set"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct cgroup_subsys_state * cgroup_e_css(struct cgroup * cgrp, struct cgroup_subsys * ss)
```

```json
{
  "name": "cgroup_e_css",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580195312,
      "name": "cgroup_e_css",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:540",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_associate_blkg_from_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580195312,
      "name": "cgroup_e_css",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
struct cgroup_subsys_state * cgroup_e_css(struct cgroup * cgrp, struct cgroup_subsys * ss)
```

```json
{
  "name": "cgroup_e_css",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580241808,
      "name": "cgroup_e_css",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:542",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_associate_blkg_from_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580241808,
      "name": "cgroup_e_css",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
struct cgroup_subsys_state * cgroup_e_css(struct cgroup * cgrp, struct cgroup_subsys * ss)
```

```json
{
  "name": "cgroup_e_css",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580289984,
      "name": "cgroup_e_css",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:542",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_associate_blkg_from_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580289984,
      "name": "cgroup_e_css",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
struct cgroup_subsys_state * cgroup_e_css(struct cgroup * cgrp, struct cgroup_subsys * ss)
```

```json
{
  "name": "cgroup_e_css",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580361248,
      "name": "cgroup_e_css",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:535",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_associate_blkg_from_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580361248,
      "name": "cgroup_e_css",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
struct cgroup_subsys_state * cgroup_e_css(struct cgroup * cgrp, struct cgroup_subsys * ss)
```

```json
{
  "name": "cgroup_e_css",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580348016,
      "name": "cgroup_e_css",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:532",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:__swap_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580348016,
      "name": "cgroup_e_css",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
struct cgroup_subsys_state * cgroup_e_css(struct cgroup * cgrp, struct cgroup_subsys * ss)
```

```json
{
  "name": "cgroup_e_css",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580351136,
      "name": "cgroup_e_css",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:532",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:__swap_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580351136,
      "name": "cgroup_e_css",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
struct cgroup_subsys_state * cgroup_e_css(struct cgroup * cgrp, struct cgroup_subsys * ss)
```

```json
{
  "name": "cgroup_e_css",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580507920,
      "name": "cgroup_e_css",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:556",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:__swap_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580507920,
      "name": "cgroup_e_css",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
struct cgroup_subsys_state * cgroup_e_css(struct cgroup * cgrp, struct cgroup_subsys * ss)
```

```json
{
  "name": "cgroup_e_css",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580704240,
      "name": "cgroup_e_css",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:557",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:__swap_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580704240,
      "name": "cgroup_e_css",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
struct cgroup_subsys_state * cgroup_e_css(struct cgroup * cgrp, struct cgroup_subsys * ss)
```

```json
{
  "name": "cgroup_e_css",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580977264,
      "name": "cgroup_e_css",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:562",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:__swap_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580977264,
      "name": "cgroup_e_css",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
struct cgroup_subsys_state * cgroup_e_css(struct cgroup * cgrp, struct cgroup_subsys * ss)
```

```json
{
  "name": "cgroup_e_css",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581065088,
      "name": "cgroup_e_css",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:561",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:bio_associate_blkg_from_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581065088,
      "name": "cgroup_e_css",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
struct cgroup_subsys_state * cgroup_e_css(struct cgroup * cgrp, struct cgroup_subsys * ss)
```

```json
{
  "name": "cgroup_e_css",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581162464,
      "name": "cgroup_e_css",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:541",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581162464,
      "name": "cgroup_e_css",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
struct cgroup_subsys_state * cgroup_e_css(struct cgroup * cgrp, struct cgroup_subsys * ss)
```

```json
{
  "name": "cgroup_e_css",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491539896,
      "name": "cgroup_e_css",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:542",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_associate_blkg_from_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491539896,
      "name": "cgroup_e_css",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct cgroup_subsys_state * cgroup_e_css(struct cgroup * cgrp, struct cgroup_subsys * ss)
```

```json
{
  "name": "cgroup_e_css",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225505040,
      "name": "cgroup_e_css",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:542",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_associate_blkg_from_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225505040,
      "name": "cgroup_e_css",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
struct cgroup_subsys_state * cgroup_e_css(struct cgroup * cgrp, struct cgroup_subsys * ss)
```

```json
{
  "name": "cgroup_e_css",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284508784,
      "name": "cgroup_e_css",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:542",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_associate_blkg_from_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284508784,
      "name": "cgroup_e_css",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
struct cgroup_subsys_state * cgroup_e_css(struct cgroup * cgrp, struct cgroup_subsys * ss)
```

```json
{
  "name": "cgroup_e_css",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271955992,
      "name": "cgroup_e_css",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:542",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_associate_blkg_from_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271955992,
      "name": "cgroup_e_css",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct cgroup_subsys_state * cgroup_e_css(struct cgroup * cgrp, struct cgroup_subsys * ss)
```

```json
{
  "name": "cgroup_e_css",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580258784,
      "name": "cgroup_e_css",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:542",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_associate_blkg_from_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580258784,
      "name": "cgroup_e_css",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
struct cgroup_subsys_state * cgroup_e_css(struct cgroup * cgrp, struct cgroup_subsys * ss)
```

```json
{
  "name": "cgroup_e_css",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580206320,
      "name": "cgroup_e_css",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:542",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_associate_blkg_from_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580206320,
      "name": "cgroup_e_css",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
struct cgroup_subsys_state * cgroup_e_css(struct cgroup * cgrp, struct cgroup_subsys * ss)
```

```json
{
  "name": "cgroup_e_css",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580250032,
      "name": "cgroup_e_css",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:542",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_associate_blkg_from_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580250032,
      "name": "cgroup_e_css",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
struct cgroup_subsys_state * cgroup_e_css(struct cgroup * cgrp, struct cgroup_subsys * ss)
```

```json
{
  "name": "cgroup_e_css",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580303216,
      "name": "cgroup_e_css",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:542",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_associate_blkg_from_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580303216,
      "name": "cgroup_e_css",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
<summary>Removed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➖</summary>

```c
struct cgroup_subsys_state * cgroup_e_css(struct cgroup * cgrp, struct cgroup_subsys * ss)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
struct cgroup_subsys_state * cgroup_e_css(struct cgroup * cgrp, struct cgroup_subsys * ss)
```
</details>
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
