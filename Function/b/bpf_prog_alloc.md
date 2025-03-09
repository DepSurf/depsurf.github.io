# Function: <code>bpf_prog_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct bpf_prog * bpf_prog_alloc(unsigned int size, gfp_t gfp_extra_flags)
```

```json
{
  "name": "bpf_prog_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580357088,
      "name": "bpf_prog_alloc",
      "external": true,
      "loc": "kernel/bpf/core.c:73",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "net/core/filter.c:bpf_prog_create",
        "net/core/filter.c:bpf_prog_create_from_user",
        "net/core/filter.c:sk_attach_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580357088,
      "name": "bpf_prog_alloc",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct bpf_prog * bpf_prog_alloc(unsigned int size, gfp_t gfp_extra_flags)
```

```json
{
  "name": "bpf_prog_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580411888,
      "name": "bpf_prog_alloc",
      "external": true,
      "loc": "kernel/bpf/core.c:74",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "net/core/filter.c:__get_filter",
        "net/core/filter.c:bpf_prog_create_from_user",
        "net/core/filter.c:bpf_prog_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580411888,
      "name": "bpf_prog_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
struct bpf_prog * bpf_prog_alloc(unsigned int size, gfp_t gfp_extra_flags)
```

```json
{
  "name": "bpf_prog_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580460032,
      "name": "bpf_prog_alloc",
      "external": true,
      "loc": "kernel/bpf/core.c:74",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "net/core/filter.c:__get_filter",
        "net/core/filter.c:bpf_prog_create_from_user",
        "net/core/filter.c:bpf_prog_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580460032,
      "name": "bpf_prog_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
struct bpf_prog * bpf_prog_alloc(unsigned int size, gfp_t gfp_extra_flags)
```

```json
{
  "name": "bpf_prog_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580474912,
      "name": "bpf_prog_alloc",
      "external": true,
      "loc": "kernel/bpf/core.c:77",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "net/core/filter.c:__get_filter",
        "net/core/filter.c:bpf_prog_create_from_user",
        "net/core/filter.c:bpf_prog_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580474912,
      "name": "bpf_prog_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
struct bpf_prog * bpf_prog_alloc(unsigned int size, gfp_t gfp_extra_flags)
```

```json
{
  "name": "bpf_prog_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580533296,
      "name": "bpf_prog_alloc",
      "external": true,
      "loc": "kernel/bpf/core.c:77",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "net/core/filter.c:__get_filter",
        "net/core/filter.c:bpf_prog_create_from_user",
        "net/core/filter.c:bpf_prog_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580533296,
      "name": "bpf_prog_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
struct bpf_prog * bpf_prog_alloc(unsigned int size, gfp_t gfp_extra_flags)
```

```json
{
  "name": "bpf_prog_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580619536,
      "name": "bpf_prog_alloc",
      "external": true,
      "loc": "kernel/bpf/core.c:78",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/verifier.c:bpf_check",
        "net/core/filter.c:__get_filter",
        "net/core/filter.c:bpf_prog_create_from_user",
        "net/core/filter.c:bpf_prog_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580619536,
      "name": "bpf_prog_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
struct bpf_prog * bpf_prog_alloc(unsigned int size, gfp_t gfp_extra_flags)
```

```json
{
  "name": "bpf_prog_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580678544,
      "name": "bpf_prog_alloc",
      "external": true,
      "loc": "kernel/bpf/core.c:81",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/verifier.c:bpf_check",
        "net/core/filter.c:__get_filter",
        "net/core/filter.c:bpf_prog_create_from_user",
        "net/core/filter.c:bpf_prog_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580678544,
      "name": "bpf_prog_alloc",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct bpf_prog * bpf_prog_alloc(unsigned int size, gfp_t gfp_extra_flags)
```

```json
{
  "name": "bpf_prog_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580747696,
      "name": "bpf_prog_alloc",
      "external": true,
      "loc": "kernel/bpf/core.c:104",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "net/core/filter.c:__get_filter",
        "net/core/filter.c:bpf_prog_create_from_user",
        "net/core/filter.c:bpf_prog_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580747696,
      "name": "bpf_prog_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
struct bpf_prog * bpf_prog_alloc(unsigned int size, gfp_t gfp_extra_flags)
```

```json
{
  "name": "bpf_prog_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580798272,
      "name": "bpf_prog_alloc",
      "external": true,
      "loc": "kernel/bpf/core.c:104",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "net/core/filter.c:__get_filter",
        "net/core/filter.c:bpf_prog_create_from_user",
        "net/core/filter.c:bpf_prog_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580798272,
      "name": "bpf_prog_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
struct bpf_prog * bpf_prog_alloc(unsigned int size, gfp_t gfp_extra_flags)
```

```json
{
  "name": "bpf_prog_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580915536,
      "name": "bpf_prog_alloc",
      "external": true,
      "loc": "kernel/bpf/core.c:105",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "net/core/filter.c:__get_filter",
        "net/core/filter.c:bpf_prog_create_from_user",
        "net/core/filter.c:bpf_prog_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580915536,
      "name": "bpf_prog_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
struct bpf_prog * bpf_prog_alloc(unsigned int size, gfp_t gfp_extra_flags)
```

```json
{
  "name": "bpf_prog_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580911568,
      "name": "bpf_prog_alloc",
      "external": true,
      "loc": "kernel/bpf/core.c:107",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "net/core/filter.c:__get_filter",
        "net/core/filter.c:bpf_prog_create_from_user",
        "net/core/filter.c:bpf_prog_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580911568,
      "name": "bpf_prog_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
struct bpf_prog * bpf_prog_alloc(unsigned int size, gfp_t gfp_extra_flags)
```

```json
{
  "name": "bpf_prog_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580915216,
      "name": "bpf_prog_alloc",
      "external": true,
      "loc": "kernel/bpf/core.c:115",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "net/core/filter.c:__get_filter",
        "net/core/filter.c:bpf_prog_create_from_user",
        "net/core/filter.c:bpf_prog_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580915216,
      "name": "bpf_prog_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
struct bpf_prog * bpf_prog_alloc(unsigned int size, gfp_t gfp_extra_flags)
```

```json
{
  "name": "bpf_prog_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581117600,
      "name": "bpf_prog_alloc",
      "external": true,
      "loc": "kernel/bpf/core.c:115",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "net/core/filter.c:__get_filter",
        "net/core/filter.c:bpf_prog_create_from_user",
        "net/core/filter.c:bpf_prog_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581117600,
      "name": "bpf_prog_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
struct bpf_prog * bpf_prog_alloc(unsigned int size, gfp_t gfp_extra_flags)
```

```json
{
  "name": "bpf_prog_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581386256,
      "name": "bpf_prog_alloc",
      "external": true,
      "loc": "kernel/bpf/core.c:120",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "net/core/filter.c:__get_filter",
        "net/core/filter.c:bpf_prog_create_from_user",
        "net/core/filter.c:bpf_prog_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581386256,
      "name": "bpf_prog_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
struct bpf_prog * bpf_prog_alloc(unsigned int size, gfp_t gfp_extra_flags)
```

```json
{
  "name": "bpf_prog_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581734576,
      "name": "bpf_prog_alloc",
      "external": true,
      "loc": "kernel/bpf/core.c:128",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/trampoline.c:bpf_trampoline_link_cgroup_shim",
        "net/core/filter.c:__get_filter",
        "net/core/filter.c:bpf_prog_create_from_user",
        "net/core/filter.c:bpf_prog_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581734576,
      "name": "bpf_prog_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
struct bpf_prog * bpf_prog_alloc(unsigned int size, gfp_t gfp_extra_flags)
```

```json
{
  "name": "bpf_prog_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581893856,
      "name": "bpf_prog_alloc",
      "external": true,
      "loc": "kernel/bpf/core.c:129",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/trampoline.c:bpf_trampoline_link_cgroup_shim",
        "net/core/filter.c:__get_filter",
        "net/core/filter.c:bpf_prog_create_from_user",
        "net/core/filter.c:bpf_prog_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581893856,
      "name": "bpf_prog_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
struct bpf_prog * bpf_prog_alloc(unsigned int size, gfp_t gfp_extra_flags)
```

```json
{
  "name": "bpf_prog_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582017616,
      "name": "bpf_prog_alloc",
      "external": true,
      "loc": "kernel/bpf/core.c:133",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/trampoline.c:bpf_trampoline_link_cgroup_shim",
        "net/core/filter.c:__get_filter",
        "net/core/filter.c:bpf_prog_create_from_user",
        "net/core/filter.c:bpf_prog_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582017616,
      "name": "bpf_prog_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
struct bpf_prog * bpf_prog_alloc(unsigned int size, gfp_t gfp_extra_flags)
```

```json
{
  "name": "bpf_prog_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492111736,
      "name": "bpf_prog_alloc",
      "external": true,
      "loc": "kernel/bpf/core.c:104",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "net/core/filter.c:__get_filter",
        "net/core/filter.c:bpf_prog_create_from_user",
        "net/core/filter.c:bpf_prog_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492111736,
      "name": "bpf_prog_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
struct bpf_prog * bpf_prog_alloc(unsigned int size, gfp_t gfp_extra_flags)
```

```json
{
  "name": "bpf_prog_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226013528,
      "name": "bpf_prog_alloc",
      "external": true,
      "loc": "kernel/bpf/core.c:104",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "net/core/filter.c:__get_filter",
        "net/core/filter.c:bpf_prog_create_from_user",
        "net/core/filter.c:bpf_prog_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226013528,
      "name": "bpf_prog_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
struct bpf_prog * bpf_prog_alloc(unsigned int size, gfp_t gfp_extra_flags)
```

```json
{
  "name": "bpf_prog_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285317968,
      "name": "bpf_prog_alloc",
      "external": true,
      "loc": "kernel/bpf/core.c:104",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "net/core/filter.c:__get_filter",
        "net/core/filter.c:bpf_prog_create_from_user",
        "net/core/filter.c:bpf_prog_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285317968,
      "name": "bpf_prog_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
struct bpf_prog * bpf_prog_alloc(unsigned int size, gfp_t gfp_extra_flags)
```

```json
{
  "name": "bpf_prog_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272285002,
      "name": "bpf_prog_alloc",
      "external": true,
      "loc": "kernel/bpf/core.c:104",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "net/core/filter.c:__get_filter",
        "net/core/filter.c:bpf_prog_create_from_user",
        "net/core/filter.c:bpf_prog_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272285002,
      "name": "bpf_prog_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
struct bpf_prog * bpf_prog_alloc(unsigned int size, gfp_t gfp_extra_flags)
```

```json
{
  "name": "bpf_prog_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580767072,
      "name": "bpf_prog_alloc",
      "external": true,
      "loc": "kernel/bpf/core.c:104",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "net/core/filter.c:__get_filter",
        "net/core/filter.c:bpf_prog_create_from_user",
        "net/core/filter.c:bpf_prog_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580767072,
      "name": "bpf_prog_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
struct bpf_prog * bpf_prog_alloc(unsigned int size, gfp_t gfp_extra_flags)
```

```json
{
  "name": "bpf_prog_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580713248,
      "name": "bpf_prog_alloc",
      "external": true,
      "loc": "kernel/bpf/core.c:104",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "net/core/filter.c:__get_filter",
        "net/core/filter.c:bpf_prog_create_from_user",
        "net/core/filter.c:bpf_prog_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580713248,
      "name": "bpf_prog_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
struct bpf_prog * bpf_prog_alloc(unsigned int size, gfp_t gfp_extra_flags)
```

```json
{
  "name": "bpf_prog_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580758320,
      "name": "bpf_prog_alloc",
      "external": true,
      "loc": "kernel/bpf/core.c:104",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "net/core/filter.c:__get_filter",
        "net/core/filter.c:bpf_prog_create_from_user",
        "net/core/filter.c:bpf_prog_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580758320,
      "name": "bpf_prog_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
struct bpf_prog * bpf_prog_alloc(unsigned int size, gfp_t gfp_extra_flags)
```

```json
{
  "name": "bpf_prog_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580816416,
      "name": "bpf_prog_alloc",
      "external": true,
      "loc": "kernel/bpf/core.c:104",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "net/core/filter.c:__get_filter",
        "net/core/filter.c:bpf_prog_create_from_user",
        "net/core/filter.c:bpf_prog_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580816416,
      "name": "bpf_prog_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
