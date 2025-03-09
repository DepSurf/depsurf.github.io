# Function: <code>cgroup_destroy_locked</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int cgroup_destroy_locked(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_destroy_locked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579993504,
      "name": "cgroup_destroy_locked",
      "external": false,
      "loc": "kernel/cgroup.c:5242",
      "file": "kernel/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_rmdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579993504,
      "name": "cgroup_destroy_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int cgroup_destroy_locked(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_destroy_locked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580024896,
      "name": "cgroup_destroy_locked",
      "external": false,
      "loc": "kernel/cgroup.c:5444",
      "file": "kernel/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_rmdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580024896,
      "name": "cgroup_destroy_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int cgroup_destroy_locked(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_destroy_locked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580058800,
      "name": "cgroup_destroy_locked",
      "external": false,
      "loc": "kernel/cgroup.c:5463",
      "file": "kernel/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_rmdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580058800,
      "name": "cgroup_destroy_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int cgroup_destroy_locked(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_destroy_locked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580056096,
      "name": "cgroup_destroy_locked",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:4420",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580056096,
      "name": "cgroup_destroy_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
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
int cgroup_destroy_locked(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_destroy_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580106288,
      "name": "cgroup_destroy_locked",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:5058",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580106288,
      "name": "cgroup_destroy_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
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
int cgroup_destroy_locked(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_destroy_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580165424,
      "name": "cgroup_destroy_locked",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:5098",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580165424,
      "name": "cgroup_destroy_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 319
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
int cgroup_destroy_locked(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_destroy_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580213168,
      "name": "cgroup_destroy_locked",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:5192",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580213168,
      "name": "cgroup_destroy_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 319
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
int cgroup_destroy_locked(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_destroy_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580261712,
      "name": "cgroup_destroy_locked",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:5521",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580261712,
      "name": "cgroup_destroy_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 369
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
int cgroup_destroy_locked(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_destroy_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580309984,
      "name": "cgroup_destroy_locked",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:5536",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580309984,
      "name": "cgroup_destroy_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 369
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
int cgroup_destroy_locked(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_destroy_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580379936,
      "name": "cgroup_destroy_locked",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:5478",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580379936,
      "name": "cgroup_destroy_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 438
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
int cgroup_destroy_locked(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_destroy_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580366880,
      "name": "cgroup_destroy_locked",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:5470",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580366880,
      "name": "cgroup_destroy_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 446
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
int cgroup_destroy_locked(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_destroy_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580369904,
      "name": "cgroup_destroy_locked",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:5451",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580369904,
      "name": "cgroup_destroy_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 446
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
int cgroup_destroy_locked(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_destroy_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580529792,
      "name": "cgroup_destroy_locked",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:5641",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580529792,
      "name": "cgroup_destroy_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 476
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
int cgroup_destroy_locked(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_destroy_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580726928,
      "name": "cgroup_destroy_locked",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:5652",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580726928,
      "name": "cgroup_destroy_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 470
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
int cgroup_destroy_locked(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_destroy_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581002512,
      "name": "cgroup_destroy_locked",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:5868",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581002512,
      "name": "cgroup_destroy_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 469
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
int cgroup_destroy_locked(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_destroy_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581091104,
      "name": "cgroup_destroy_locked",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:5849",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581091104,
      "name": "cgroup_destroy_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 469
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
int cgroup_destroy_locked(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_destroy_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581188624,
      "name": "cgroup_destroy_locked",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:5882",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581188624,
      "name": "cgroup_destroy_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 465
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
int cgroup_destroy_locked(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_destroy_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491562096,
      "name": "cgroup_destroy_locked",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:5536",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491562096,
      "name": "cgroup_destroy_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 420
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
int cgroup_destroy_locked(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_destroy_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225526776,
      "name": "cgroup_destroy_locked",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:5536",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225526776,
      "name": "cgroup_destroy_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 396
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
int cgroup_destroy_locked(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_destroy_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284538560,
      "name": "cgroup_destroy_locked",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:5536",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284538560,
      "name": "cgroup_destroy_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 612
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
int cgroup_destroy_locked(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_destroy_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271975888,
      "name": "cgroup_destroy_locked",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:5536",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271975888,
      "name": "cgroup_destroy_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 468
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
int cgroup_destroy_locked(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_destroy_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580278784,
      "name": "cgroup_destroy_locked",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:5536",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580278784,
      "name": "cgroup_destroy_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 369
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
int cgroup_destroy_locked(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_destroy_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580226272,
      "name": "cgroup_destroy_locked",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:5536",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580226272,
      "name": "cgroup_destroy_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 357
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
int cgroup_destroy_locked(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_destroy_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580270032,
      "name": "cgroup_destroy_locked",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:5536",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580270032,
      "name": "cgroup_destroy_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 369
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
int cgroup_destroy_locked(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_destroy_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580323584,
      "name": "cgroup_destroy_locked",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:5536",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580323584,
      "name": "cgroup_destroy_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 362
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
