# Function: <code>__kmalloc_track_caller</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void * __kmalloc_track_caller(size_t size, gfp_t gfpflags, long unsigned int caller)
```

```json
{
  "name": "__kmalloc_track_caller",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580871232,
      "name": "__kmalloc_track_caller",
      "external": true,
      "loc": "mm/slub.c:4023",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/util.c:kstrdup",
        "mm/util.c:kmemdup",
        "mm/util.c:kstrndup",
        "mm/util.c:memdup_user",
        "mm/slab_common.c:__krealloc",
        "mm/slab_common.c:krealloc",
        "mm/slab_common.c:krealloc",
        "lib/kasprintf.c:kvasprintf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580871232,
      "name": "__kmalloc_track_caller",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 577
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
void * __kmalloc_track_caller(size_t size, gfp_t gfpflags, long unsigned int caller)
```

```json
{
  "name": "__kmalloc_track_caller",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580999088,
      "name": "__kmalloc_track_caller",
      "external": true,
      "loc": "mm/slub.c:4250",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/util.c:memdup_user_nul",
        "mm/util.c:memdup_user",
        "mm/util.c:kmemdup",
        "mm/util.c:kstrndup",
        "mm/util.c:kstrdup",
        "mm/slab_common.c:krealloc",
        "mm/slab_common.c:krealloc",
        "mm/slab_common.c:__krealloc",
        "lib/kasprintf.c:kvasprintf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580999088,
      "name": "__kmalloc_track_caller",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 501
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
void * __kmalloc_track_caller(size_t size, gfp_t gfpflags, long unsigned int caller)
```

```json
{
  "name": "__kmalloc_track_caller",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581072880,
      "name": "__kmalloc_track_caller",
      "external": true,
      "loc": "mm/slub.c:4219",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/util.c:memdup_user_nul",
        "mm/util.c:memdup_user",
        "mm/util.c:kmemdup",
        "mm/util.c:kstrndup",
        "mm/util.c:kstrdup",
        "mm/slab_common.c:krealloc",
        "mm/slab_common.c:krealloc",
        "mm/slab_common.c:__krealloc",
        "lib/kasprintf.c:kvasprintf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581072880,
      "name": "__kmalloc_track_caller",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 501
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
void * __kmalloc_track_caller(size_t size, gfp_t gfpflags, long unsigned int caller)
```

```json
{
  "name": "__kmalloc_track_caller",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581121376,
      "name": "__kmalloc_track_caller",
      "external": true,
      "loc": "mm/slub.c:4261",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/util.c:memdup_user_nul",
        "mm/util.c:memdup_user",
        "mm/util.c:kmemdup_nul",
        "mm/util.c:kstrndup",
        "mm/util.c:kstrdup",
        "mm/util.c:kmemdup",
        "mm/slab_common.c:krealloc",
        "mm/slab_common.c:krealloc",
        "mm/slab_common.c:__krealloc",
        "lib/kasprintf.c:kvasprintf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581121376,
      "name": "__kmalloc_track_caller",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 491
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
void * __kmalloc_track_caller(size_t size, gfp_t gfpflags, long unsigned int caller)
```

```json
{
  "name": "__kmalloc_track_caller",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581233776,
      "name": "__kmalloc_track_caller",
      "external": true,
      "loc": "mm/slub.c:4277",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/util.c:memdup_user_nul",
        "mm/util.c:memdup_user",
        "mm/util.c:kmemdup_nul",
        "mm/util.c:kstrndup",
        "mm/util.c:kstrdup",
        "mm/util.c:kmemdup",
        "mm/slab_common.c:krealloc",
        "mm/slab_common.c:krealloc",
        "mm/slab_common.c:__krealloc",
        "lib/kasprintf.c:kvasprintf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581233776,
      "name": "__kmalloc_track_caller",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 525
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
void * __kmalloc_track_caller(size_t size, gfp_t gfpflags, long unsigned int caller)
```

```json
{
  "name": "__kmalloc_track_caller",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581376928,
      "name": "__kmalloc_track_caller",
      "external": true,
      "loc": "mm/slub.c:4279",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/util.c:memdup_user_nul",
        "mm/util.c:memdup_user",
        "mm/util.c:kmemdup_nul",
        "mm/util.c:kstrndup",
        "mm/util.c:kstrdup",
        "mm/util.c:kmemdup",
        "mm/slab_common.c:krealloc",
        "mm/slab_common.c:krealloc",
        "mm/slab_common.c:__krealloc",
        "lib/kasprintf.c:kvasprintf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581376928,
      "name": "__kmalloc_track_caller",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 552
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
void * __kmalloc_track_caller(size_t size, gfp_t gfpflags, long unsigned int caller)
```

```json
{
  "name": "__kmalloc_track_caller",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581461088,
      "name": "__kmalloc_track_caller",
      "external": true,
      "loc": "mm/slub.c:4331",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/util.c:memdup_user_nul",
        "mm/util.c:memdup_user",
        "mm/util.c:kmemdup_nul",
        "mm/util.c:kstrndup",
        "mm/util.c:kstrdup",
        "mm/util.c:kmemdup",
        "mm/slab_common.c:krealloc",
        "mm/slab_common.c:krealloc",
        "mm/slab_common.c:__krealloc",
        "lib/kasprintf.c:kvasprintf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581461088,
      "name": "__kmalloc_track_caller",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 521
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
void * __kmalloc_track_caller(size_t size, gfp_t gfpflags, long unsigned int caller)
```

```json
{
  "name": "__kmalloc_track_caller",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581575232,
      "name": "__kmalloc_track_caller",
      "external": true,
      "loc": "mm/slub.c:4322",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "mm/util.c:memdup_user_nul",
        "mm/util.c:memdup_user",
        "mm/util.c:kmemdup_nul",
        "mm/util.c:kstrndup",
        "mm/util.c:kstrdup",
        "mm/util.c:kmemdup",
        "mm/slab_common.c:krealloc",
        "mm/slab_common.c:krealloc",
        "mm/slab_common.c:__krealloc",
        "lib/kasprintf.c:kvasprintf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581575232,
      "name": "__kmalloc_track_caller",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 614
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
void * __kmalloc_track_caller(size_t size, gfp_t gfpflags, long unsigned int caller)
```

```json
{
  "name": "__kmalloc_track_caller",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581640448,
      "name": "__kmalloc_track_caller",
      "external": true,
      "loc": "mm/slub.c:4340",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "mm/util.c:memdup_user_nul",
        "mm/util.c:memdup_user",
        "mm/util.c:kmemdup_nul",
        "mm/util.c:kstrndup",
        "mm/util.c:kstrdup",
        "mm/util.c:kmemdup",
        "mm/slab_common.c:krealloc",
        "mm/slab_common.c:krealloc",
        "mm/slab_common.c:__krealloc",
        "lib/kasprintf.c:kvasprintf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581640448,
      "name": "__kmalloc_track_caller",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 614
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
void * __kmalloc_track_caller(size_t size, gfp_t gfpflags, long unsigned int caller)
```

```json
{
  "name": "__kmalloc_track_caller",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581845888,
      "name": "__kmalloc_track_caller",
      "external": true,
      "loc": "mm/slub.c:4417",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "mm/util.c:memdup_user_nul",
        "mm/util.c:memdup_user",
        "mm/util.c:kmemdup_nul",
        "mm/util.c:kstrndup",
        "mm/util.c:kstrdup",
        "mm/util.c:kmemdup",
        "mm/slab_common.c:krealloc",
        "lib/kasprintf.c:kvasprintf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581845888,
      "name": "__kmalloc_track_caller",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 641
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
void * __kmalloc_track_caller(size_t size, gfp_t gfpflags, long unsigned int caller)
```

```json
{
  "name": "__kmalloc_track_caller",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581896848,
      "name": "__kmalloc_track_caller",
      "external": true,
      "loc": "mm/slub.c:4466",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "mm/util.c:memdup_user_nul",
        "mm/util.c:memdup_user",
        "mm/util.c:kmemdup_nul",
        "mm/util.c:kstrndup",
        "mm/util.c:kstrdup",
        "mm/util.c:kmemdup",
        "mm/slab_common.c:krealloc",
        "lib/kasprintf.c:kvasprintf",
        "net/xfrm/xfrm_state.c:xfrm_user_policy",
        "net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581896848,
      "name": "__kmalloc_track_caller",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 576
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
void * __kmalloc_track_caller(size_t size, gfp_t gfpflags, long unsigned int caller)
```

```json
{
  "name": "__kmalloc_track_caller",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581923456,
      "name": "__kmalloc_track_caller",
      "external": true,
      "loc": "mm/slub.c:4547",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "mm/util.c:memdup_user_nul",
        "mm/util.c:memdup_user",
        "mm/util.c:kmemdup_nul",
        "mm/util.c:kstrndup",
        "mm/util.c:kstrdup",
        "mm/util.c:kmemdup",
        "mm/slab_common.c:krealloc",
        "lib/kasprintf.c:kvasprintf",
        "net/xfrm/xfrm_state.c:xfrm_user_policy",
        "net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581923456,
      "name": "__kmalloc_track_caller",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 608
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
void * __kmalloc_track_caller(size_t size, gfp_t gfpflags, long unsigned int caller)
```

```json
{
  "name": "__kmalloc_track_caller",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582222416,
      "name": "__kmalloc_track_caller",
      "external": true,
      "loc": "mm/slub.c:4903",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:copy_array",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "mm/util.c:memdup_user_nul",
        "mm/util.c:memdup_user",
        "mm/util.c:kmemdup_nul",
        "mm/util.c:kstrndup",
        "mm/util.c:kstrdup",
        "mm/util.c:kmemdup",
        "mm/slab_common.c:krealloc",
        "lib/kasprintf.c:kvasprintf",
        "net/xfrm/xfrm_state.c:xfrm_user_policy",
        "net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582222416,
      "name": "__kmalloc_track_caller",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 820
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
void * __kmalloc_track_caller(size_t size, gfp_t gfpflags, long unsigned int caller)
```

```json
{
  "name": "__kmalloc_track_caller",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582693744,
      "name": "__kmalloc_track_caller",
      "external": true,
      "loc": "mm/slub.c:4935",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:copy_array",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "mm/util.c:memdup_user_nul",
        "mm/util.c:memdup_user",
        "mm/util.c:kmemdup_nul",
        "mm/util.c:kstrndup",
        "mm/util.c:kstrdup",
        "mm/util.c:kmemdup",
        "mm/slab_common.c:krealloc",
        "lib/kasprintf.c:kvasprintf",
        "net/xfrm/xfrm_state.c:xfrm_user_policy",
        "net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582693744,
      "name": "__kmalloc_track_caller",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 886
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void * __kmalloc_track_caller(size_t size, gfp_t gfpflags, long unsigned int caller)
```

```json
{
  "name": "__kmalloc_track_caller",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493090216,
      "name": "__kmalloc_track_caller",
      "external": true,
      "loc": "mm/slub.c:4340",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "mm/util.c:memdup_user_nul",
        "mm/util.c:memdup_user",
        "mm/util.c:kmemdup_nul",
        "mm/util.c:kstrndup",
        "mm/util.c:kstrdup",
        "mm/util.c:kmemdup",
        "mm/slab_common.c:krealloc",
        "mm/slab_common.c:krealloc",
        "mm/slab_common.c:__krealloc",
        "lib/kasprintf.c:kvasprintf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493090216,
      "name": "__kmalloc_track_caller",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 744
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
void * __kmalloc_track_caller(size_t size, gfp_t gfpflags, long unsigned int caller)
```

```json
{
  "name": "__kmalloc_track_caller",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226796372,
      "name": "__kmalloc_track_caller",
      "external": true,
      "loc": "mm/slub.c:4340",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "mm/util.c:memdup_user_nul",
        "mm/util.c:memdup_user",
        "mm/util.c:kmemdup_nul",
        "mm/util.c:kstrndup",
        "mm/util.c:kstrdup",
        "mm/util.c:kmemdup",
        "mm/slab_common.c:krealloc",
        "mm/slab_common.c:krealloc",
        "mm/slab_common.c:__krealloc",
        "lib/kasprintf.c:kvasprintf",
        "drivers/base/devres.c:devm_kmalloc",
        "drivers/base/devres.c:devres_alloc_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226796372,
      "name": "__kmalloc_track_caller",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 912
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
void * __kmalloc_track_caller(size_t size, gfp_t gfpflags, long unsigned int caller)
```

```json
{
  "name": "__kmalloc_track_caller",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286538384,
      "name": "__kmalloc_track_caller",
      "external": true,
      "loc": "mm/slub.c:4340",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "mm/util.c:memdup_user_nul",
        "mm/util.c:memdup_user",
        "mm/util.c:kmemdup_nul",
        "mm/util.c:kstrndup",
        "mm/util.c:kstrdup",
        "mm/util.c:kmemdup",
        "mm/slab_common.c:krealloc",
        "mm/slab_common.c:__krealloc",
        "lib/kasprintf.c:kvasprintf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286538384,
      "name": "__kmalloc_track_caller",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1048
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
void * __kmalloc_track_caller(size_t size, gfp_t gfpflags, long unsigned int caller)
```

```json
{
  "name": "__kmalloc_track_caller",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272946836,
      "name": "__kmalloc_track_caller",
      "external": true,
      "loc": "mm/slub.c:4340",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "mm/util.c:memdup_user_nul",
        "mm/util.c:memdup_user",
        "mm/util.c:kmemdup_nul",
        "mm/util.c:kmemdup",
        "mm/util.c:kstrndup",
        "mm/util.c:kstrdup",
        "mm/slab_common.c:krealloc",
        "mm/slab_common.c:__krealloc",
        "lib/kasprintf.c:kvasprintf",
        "drivers/base/devres.c:devm_kmalloc",
        "drivers/base/devres.c:devres_alloc_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272946836,
      "name": "__kmalloc_track_caller",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 694
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
void * __kmalloc_track_caller(size_t size, gfp_t gfpflags, long unsigned int caller)
```

```json
{
  "name": "__kmalloc_track_caller",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581609184,
      "name": "__kmalloc_track_caller",
      "external": true,
      "loc": "mm/slub.c:4340",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "mm/util.c:memdup_user_nul",
        "mm/util.c:memdup_user",
        "mm/util.c:kmemdup_nul",
        "mm/util.c:kstrndup",
        "mm/util.c:kstrdup",
        "mm/util.c:kmemdup",
        "mm/slab_common.c:krealloc",
        "mm/slab_common.c:krealloc",
        "mm/slab_common.c:__krealloc",
        "lib/kasprintf.c:kvasprintf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581609184,
      "name": "__kmalloc_track_caller",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 614
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
void * __kmalloc_track_caller(size_t size, gfp_t gfpflags, long unsigned int caller)
```

```json
{
  "name": "__kmalloc_track_caller",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581550512,
      "name": "__kmalloc_track_caller",
      "external": true,
      "loc": "mm/slub.c:4340",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "mm/util.c:memdup_user_nul",
        "mm/util.c:memdup_user",
        "mm/util.c:kmemdup_nul",
        "mm/util.c:kstrndup",
        "mm/util.c:kstrdup",
        "mm/util.c:kmemdup",
        "mm/slab_common.c:krealloc",
        "mm/slab_common.c:krealloc",
        "mm/slab_common.c:__krealloc",
        "lib/kasprintf.c:kvasprintf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581550512,
      "name": "__kmalloc_track_caller",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 619
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
void * __kmalloc_track_caller(size_t size, gfp_t gfpflags, long unsigned int caller)
```

```json
{
  "name": "__kmalloc_track_caller",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581600496,
      "name": "__kmalloc_track_caller",
      "external": true,
      "loc": "mm/slub.c:4340",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "mm/util.c:memdup_user_nul",
        "mm/util.c:memdup_user",
        "mm/util.c:kmemdup_nul",
        "mm/util.c:kstrndup",
        "mm/util.c:kstrdup",
        "mm/util.c:kmemdup",
        "mm/slab_common.c:krealloc",
        "mm/slab_common.c:krealloc",
        "mm/slab_common.c:__krealloc",
        "lib/kasprintf.c:kvasprintf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581600496,
      "name": "__kmalloc_track_caller",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 614
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
void * __kmalloc_track_caller(size_t size, gfp_t gfpflags, long unsigned int caller)
```

```json
{
  "name": "__kmalloc_track_caller",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581666352,
      "name": "__kmalloc_track_caller",
      "external": true,
      "loc": "mm/slub.c:4340",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "mm/util.c:memdup_user_nul",
        "mm/util.c:memdup_user",
        "mm/util.c:kmemdup_nul",
        "mm/util.c:kstrndup",
        "mm/util.c:kstrdup",
        "mm/util.c:kmemdup",
        "mm/slab_common.c:krealloc",
        "mm/slab_common.c:krealloc",
        "mm/slab_common.c:__krealloc",
        "lib/kasprintf.c:kvasprintf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581666352,
      "name": "__kmalloc_track_caller",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 658
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void * __kmalloc_track_caller(size_t size, gfp_t gfpflags, long unsigned int caller)
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
