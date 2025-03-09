# Function: <code>__percpu_counter_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __percpu_counter_init(struct percpu_counter * fbc, s64 amount, gfp_t gfp, struct lock_class_key * key)
```

```json
{
  "name": "__percpu_counter_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583112112,
      "name": "__percpu_counter_init",
      "external": true,
      "loc": "lib/percpu_counter.c:115",
      "file": "lib/percpu_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_fill_super",
        "mm/backing-dev.c:wb_init",
        "mm/mmap.c:mmap_init",
        "fs/file_table.c:files_init",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-cgroup.c:blkg_alloc",
        "block/cfq-iosched.c:cfq_pd_alloc",
        "block/cfq-iosched.c:cfq_pd_alloc",
        "block/cfq-iosched.c:cfq_pd_alloc",
        "block/cfq-iosched.c:cfq_pd_alloc",
        "block/cfq-iosched.c:cfq_pd_alloc",
        "lib/flex_proportions.c:fprop_global_init",
        "lib/flex_proportions.c:fprop_local_init_percpu",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/ip_fragment.c:ipv4_frags_init_net",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/tcp_memcontrol.c:tcp_init_cgroup",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_init",
        "net/ipv6/route.c:ip6_route_net_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/reassembly.c:ipv6_frags_init_net",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583112112,
      "name": "__percpu_counter_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int __percpu_counter_init(struct percpu_counter * fbc, s64 amount, gfp_t gfp, struct lock_class_key * key)
```

```json
{
  "name": "__percpu_counter_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583406352,
      "name": "__percpu_counter_init",
      "external": true,
      "loc": "lib/percpu_counter.c:115",
      "file": "lib/percpu_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_fill_super",
        "mm/backing-dev.c:wb_init",
        "mm/mmap.c:mmap_init",
        "fs/file_table.c:files_init",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-cgroup.c:blkg_alloc",
        "block/cfq-iosched.c:cfq_pd_alloc",
        "block/cfq-iosched.c:cfq_pd_alloc",
        "block/cfq-iosched.c:cfq_pd_alloc",
        "block/cfq-iosched.c:cfq_pd_alloc",
        "block/cfq-iosched.c:cfq_pd_alloc",
        "lib/flex_proportions.c:fprop_local_init_percpu",
        "lib/flex_proportions.c:fprop_global_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/ip_fragment.c:ipv4_frags_init_net",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_net_init",
        "net/ipv6/reassembly.c:ipv6_frags_init_net",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583406352,
      "name": "__percpu_counter_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int __percpu_counter_init(struct percpu_counter * fbc, s64 amount, gfp_t gfp, struct lock_class_key * key)
```

```json
{
  "name": "__percpu_counter_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583531728,
      "name": "__percpu_counter_init",
      "external": true,
      "loc": "lib/percpu_counter.c:115",
      "file": "lib/percpu_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_fill_super",
        "mm/backing-dev.c:wb_init",
        "mm/mmap.c:mmap_init",
        "fs/file_table.c:files_init",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-cgroup.c:blkg_alloc",
        "block/cfq-iosched.c:cfq_pd_alloc",
        "block/cfq-iosched.c:cfq_pd_alloc",
        "block/cfq-iosched.c:cfq_pd_alloc",
        "block/cfq-iosched.c:cfq_pd_alloc",
        "block/cfq-iosched.c:cfq_pd_alloc",
        "lib/flex_proportions.c:fprop_local_init_percpu",
        "lib/flex_proportions.c:fprop_global_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/ip_fragment.c:ipv4_frags_init_net",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_net_init",
        "net/ipv6/reassembly.c:ipv6_frags_init_net",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583531728,
      "name": "__percpu_counter_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int __percpu_counter_init(struct percpu_counter * fbc, s64 amount, gfp_t gfp, struct lock_class_key * key)
```

```json
{
  "name": "__percpu_counter_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583569424,
      "name": "__percpu_counter_init",
      "external": true,
      "loc": "lib/percpu_counter.c:122",
      "file": "lib/percpu_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_fill_super",
        "mm/backing-dev.c:wb_init",
        "mm/mmap.c:mmap_init",
        "fs/file_table.c:files_init",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-cgroup.c:blkg_alloc",
        "block/cfq-iosched.c:cfq_pd_alloc",
        "block/cfq-iosched.c:cfq_pd_alloc",
        "block/cfq-iosched.c:cfq_pd_alloc",
        "block/cfq-iosched.c:cfq_pd_alloc",
        "block/cfq-iosched.c:cfq_pd_alloc",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_init",
        "lib/flex_proportions.c:fprop_local_init_percpu",
        "lib/flex_proportions.c:fprop_global_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583569424,
      "name": "__percpu_counter_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int __percpu_counter_init(struct percpu_counter * fbc, s64 amount, gfp_t gfp, struct lock_class_key * key)
```

```json
{
  "name": "__percpu_counter_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583814736,
      "name": "__percpu_counter_init",
      "external": true,
      "loc": "lib/percpu_counter.c:123",
      "file": "lib/percpu_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_fill_super",
        "mm/backing-dev.c:wb_init",
        "mm/mmap.c:mmap_init",
        "fs/file_table.c:files_init",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-cgroup.c:blkg_alloc",
        "block/cfq-iosched.c:cfq_pd_alloc",
        "block/cfq-iosched.c:cfq_pd_alloc",
        "block/cfq-iosched.c:cfq_pd_alloc",
        "block/cfq-iosched.c:cfq_pd_alloc",
        "block/cfq-iosched.c:cfq_pd_alloc",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_init",
        "lib/flex_proportions.c:fprop_local_init_percpu",
        "lib/flex_proportions.c:fprop_global_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583814736,
      "name": "__percpu_counter_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int __percpu_counter_init(struct percpu_counter * fbc, s64 amount, gfp_t gfp, struct lock_class_key * key)
```

```json
{
  "name": "__percpu_counter_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584021680,
      "name": "__percpu_counter_init",
      "external": true,
      "loc": "lib/percpu_counter.c:123",
      "file": "lib/percpu_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_fill_super",
        "mm/backing-dev.c:wb_init",
        "mm/mmap.c:mmap_init",
        "fs/file_table.c:files_init",
        "fs/quota/dquot.c:dquot_init",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-cgroup.c:blkg_alloc",
        "block/cfq-iosched.c:cfq_pd_alloc",
        "block/cfq-iosched.c:cfq_pd_alloc",
        "block/cfq-iosched.c:cfq_pd_alloc",
        "block/cfq-iosched.c:cfq_pd_alloc",
        "block/cfq-iosched.c:cfq_pd_alloc",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_init",
        "lib/flex_proportions.c:fprop_local_init_percpu",
        "lib/flex_proportions.c:fprop_global_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584021680,
      "name": "__percpu_counter_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int __percpu_counter_init(struct percpu_counter * fbc, s64 amount, gfp_t gfp, struct lock_class_key * key)
```

```json
{
  "name": "__percpu_counter_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584103376,
      "name": "__percpu_counter_init",
      "external": true,
      "loc": "lib/percpu_counter.c:122",
      "file": "lib/percpu_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_fill_super",
        "mm/backing-dev.c:wb_init",
        "mm/mmap.c:mmap_init",
        "fs/file_table.c:files_init",
        "fs/quota/dquot.c:dquot_init",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-cgroup.c:blkg_alloc",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_init",
        "lib/flex_proportions.c:fprop_local_init_percpu",
        "lib/flex_proportions.c:fprop_global_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584103376,
      "name": "__percpu_counter_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int __percpu_counter_init(struct percpu_counter * fbc, s64 amount, gfp_t gfp, struct lock_class_key * key)
```

```json
{
  "name": "__percpu_counter_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584292144,
      "name": "__percpu_counter_init",
      "external": true,
      "loc": "lib/percpu_counter.c:122",
      "file": "lib/percpu_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_fill_super",
        "mm/backing-dev.c:wb_init",
        "mm/mmap.c:mmap_init",
        "fs/file_table.c:files_init",
        "fs/quota/dquot.c:dquot_init",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-cgroup.c:blkg_alloc",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_init",
        "lib/flex_proportions.c:fprop_local_init_percpu",
        "lib/flex_proportions.c:fprop_global_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584292144,
      "name": "__percpu_counter_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int __percpu_counter_init(struct percpu_counter * fbc, s64 amount, gfp_t gfp, struct lock_class_key * key)
```

```json
{
  "name": "__percpu_counter_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584426976,
      "name": "__percpu_counter_init",
      "external": true,
      "loc": "lib/percpu_counter.c:122",
      "file": "lib/percpu_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_fill_super",
        "mm/backing-dev.c:wb_init",
        "mm/mmap.c:mmap_init",
        "fs/file_table.c:files_init",
        "fs/quota/dquot.c:dquot_init",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-cgroup.c:blkg_alloc",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_init",
        "lib/flex_proportions.c:fprop_local_init_percpu",
        "lib/flex_proportions.c:fprop_global_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584426976,
      "name": "__percpu_counter_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int __percpu_counter_init(struct percpu_counter * fbc, s64 amount, gfp_t gfp, struct lock_class_key * key)
```

```json
{
  "name": "__percpu_counter_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584989120,
      "name": "__percpu_counter_init",
      "external": true,
      "loc": "lib/percpu_counter.c:122",
      "file": "lib/percpu_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_fill_super",
        "mm/backing-dev.c:wb_init",
        "mm/mmap.c:mmap_init",
        "fs/file_table.c:files_init",
        "fs/quota/dquot.c:dquot_init",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "block/blk-cgroup-rwstat.c:blkg_rwstat_init",
        "lib/flex_proportions.c:fprop_local_init_percpu",
        "lib/flex_proportions.c:fprop_global_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_init",
        "net/mptcp/protocol.c:mptcp_proto_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584989120,
      "name": "__percpu_counter_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int __percpu_counter_init(struct percpu_counter * fbc, s64 amount, gfp_t gfp, struct lock_class_key * key)
```

```json
{
  "name": "__percpu_counter_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585111136,
      "name": "__percpu_counter_init",
      "external": true,
      "loc": "lib/percpu_counter.c:141",
      "file": "lib/percpu_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_fill_super",
        "mm/backing-dev.c:wb_init",
        "mm/mmap.c:mmap_init",
        "fs/file_table.c:files_init",
        "fs/io_uring.c:io_uring_alloc_task_context",
        "fs/quota/dquot.c:dquot_init",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "block/blk-cgroup-rwstat.c:blkg_rwstat_init",
        "lib/flex_proportions.c:fprop_local_init_percpu",
        "lib/flex_proportions.c:fprop_global_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_init",
        "net/mptcp/protocol.c:mptcp_proto_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585111136,
      "name": "__percpu_counter_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int __percpu_counter_init(struct percpu_counter * fbc, s64 amount, gfp_t gfp, struct lock_class_key * key)
```

```json
{
  "name": "__percpu_counter_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584991296,
      "name": "__percpu_counter_init",
      "external": true,
      "loc": "lib/percpu_counter.c:141",
      "file": "lib/percpu_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_fill_super",
        "mm/backing-dev.c:wb_init",
        "mm/mmap.c:mmap_init",
        "fs/file_table.c:files_init",
        "fs/io_uring.c:io_uring_alloc_task_context",
        "fs/quota/dquot.c:dquot_init",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "block/blk-cgroup-rwstat.c:blkg_rwstat_init",
        "lib/flex_proportions.c:fprop_local_init_percpu",
        "lib/flex_proportions.c:fprop_global_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_init",
        "net/mptcp/protocol.c:mptcp_proto_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584991296,
      "name": "__percpu_counter_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int __percpu_counter_init(struct percpu_counter * fbc, s64 amount, gfp_t gfp, struct lock_class_key * key)
```

```json
{
  "name": "__percpu_counter_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585431936,
      "name": "__percpu_counter_init",
      "external": true,
      "loc": "lib/percpu_counter.c:141",
      "file": "lib/percpu_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user.c:uid_cache_init",
        "kernel/user.c:alloc_uid",
        "mm/shmem.c:shmem_fill_super",
        "mm/backing-dev.c:wb_init",
        "mm/mmap.c:mmap_init",
        "fs/file_table.c:files_init",
        "fs/io_uring.c:io_uring_alloc_task_context",
        "fs/quota/dquot.c:dquot_init",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/jbd2/journal.c:journal_init_common",
        "block/blk-cgroup-rwstat.c:blkg_rwstat_init",
        "lib/flex_proportions.c:fprop_local_init_percpu",
        "lib/flex_proportions.c:fprop_global_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_init",
        "net/mptcp/protocol.c:mptcp_proto_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585431936,
      "name": "__percpu_counter_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int __percpu_counter_init(struct percpu_counter * fbc, s64 amount, gfp_t gfp, struct lock_class_key * key)
```

```json
{
  "name": "__percpu_counter_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586571872,
      "name": "__percpu_counter_init",
      "external": true,
      "loc": "lib/percpu_counter.c:141",
      "file": "lib/percpu_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user.c:uid_cache_init",
        "kernel/user.c:alloc_uid",
        "mm/shmem.c:shmem_fill_super",
        "mm/backing-dev.c:wb_init",
        "mm/mmap.c:mmap_init",
        "fs/file_table.c:files_init",
        "fs/quota/dquot.c:dquot_init",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/super.c:__ext4_fill_super",
        "fs/ext4/super.c:__ext4_fill_super",
        "fs/ext4/super.c:__ext4_fill_super",
        "fs/ext4/super.c:__ext4_fill_super",
        "fs/ext4/super.c:__ext4_fill_super",
        "fs/jbd2/journal.c:journal_init_common",
        "block/blk-cgroup-rwstat.c:blkg_rwstat_init",
        "io_uring/io_uring.c:io_uring_alloc_task_context",
        "lib/flex_proportions.c:fprop_local_init_percpu",
        "lib/flex_proportions.c:fprop_global_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_init",
        "net/mptcp/protocol.c:mptcp_proto_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586571872,
      "name": "__percpu_counter_init",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int __percpu_counter_init(struct percpu_counter * fbc, s64 amount, gfp_t gfp, struct lock_class_key * key)
```

```json
{
  "name": "__percpu_counter_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587806624,
      "name": "__percpu_counter_init",
      "external": true,
      "loc": "lib/percpu_counter.c:158",
      "file": "lib/percpu_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_init",
        "kernel/user.c:uid_cache_init",
        "kernel/user.c:alloc_uid",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "mm/shmem.c:shmem_fill_super",
        "mm/backing-dev.c:wb_init",
        "mm/mmap.c:mmap_init",
        "fs/file_table.c:files_init",
        "fs/quota/dquot.c:dquot_init",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/super.c:__ext4_fill_super",
        "fs/ext4/super.c:__ext4_fill_super",
        "fs/ext4/super.c:__ext4_fill_super",
        "fs/ext4/super.c:__ext4_fill_super",
        "fs/ext4/super.c:__ext4_fill_super",
        "fs/jbd2/journal.c:journal_init_common",
        "ipc/msg.c:msg_init_ns",
        "ipc/msg.c:msg_init_ns",
        "block/blk-cgroup-rwstat.c:blkg_rwstat_init",
        "io_uring/tctx.c:io_uring_alloc_task_context",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_init",
        "net/mptcp/protocol.c:mptcp_proto_init",
        "lib/flex_proportions.c:fprop_local_init_percpu",
        "lib/flex_proportions.c:fprop_global_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587806624,
      "name": "__percpu_counter_init",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int __percpu_counter_init(struct percpu_counter * fbc, s64 amount, gfp_t gfp, struct lock_class_key * key)
```

```json
{
  "name": "__percpu_counter_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588077760,
      "name": "__percpu_counter_init",
      "external": true,
      "loc": "lib/percpu_counter.c:154",
      "file": "lib/percpu_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_init",
        "kernel/user.c:uid_cache_init",
        "kernel/user.c:alloc_uid",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "mm/shmem.c:shmem_fill_super",
        "mm/backing-dev.c:wb_init",
        "mm/mmap.c:mmap_init",
        "fs/file_table.c:files_init",
        "fs/quota/dquot.c:dquot_init",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/super.c:ext4_percpu_param_init",
        "fs/ext4/super.c:ext4_percpu_param_init",
        "fs/ext4/super.c:ext4_percpu_param_init",
        "fs/ext4/super.c:ext4_percpu_param_init",
        "fs/ext4/super.c:ext4_percpu_param_init",
        "fs/jbd2/journal.c:journal_init_common",
        "ipc/msg.c:msg_init_ns",
        "ipc/msg.c:msg_init_ns",
        "block/blk-cgroup-rwstat.c:blkg_rwstat_init",
        "io_uring/tctx.c:io_uring_alloc_task_context",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_init",
        "net/mptcp/protocol.c:mptcp_proto_init",
        "lib/flex_proportions.c:fprop_local_init_percpu",
        "lib/flex_proportions.c:fprop_global_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588077760,
      "name": "__percpu_counter_init",
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
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int __percpu_counter_init(struct percpu_counter * fbc, s64 amount, gfp_t gfp, struct lock_class_key * key)
```

```json
{
  "name": "__percpu_counter_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496312056,
      "name": "__percpu_counter_init",
      "external": true,
      "loc": "lib/percpu_counter.c:122",
      "file": "lib/percpu_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_fill_super",
        "mm/backing-dev.c:wb_init",
        "mm/mmap.c:mmap_init",
        "fs/file_table.c:files_init",
        "fs/quota/dquot.c:dquot_init",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-cgroup.c:blkg_alloc",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_init",
        "lib/flex_proportions.c:fprop_local_init_percpu",
        "lib/flex_proportions.c:fprop_global_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496312056,
      "name": "__percpu_counter_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
int __percpu_counter_init(struct percpu_counter * fbc, s64 amount, gfp_t gfp, struct lock_class_key * key)
```

```json
{
  "name": "__percpu_counter_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229647924,
      "name": "__percpu_counter_init",
      "external": true,
      "loc": "lib/percpu_counter.c:122",
      "file": "lib/percpu_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_fill_super",
        "mm/backing-dev.c:wb_init",
        "mm/mmap.c:mmap_init",
        "fs/file_table.c:files_init",
        "fs/quota/dquot.c:dquot_init",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-cgroup.c:blkg_alloc",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_init",
        "lib/flex_proportions.c:fprop_local_init_percpu",
        "lib/flex_proportions.c:fprop_global_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229647924,
      "name": "__percpu_counter_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
int __percpu_counter_init(struct percpu_counter * fbc, s64 amount, gfp_t gfp, struct lock_class_key * key)
```

```json
{
  "name": "__percpu_counter_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290623360,
      "name": "__percpu_counter_init",
      "external": true,
      "loc": "lib/percpu_counter.c:122",
      "file": "lib/percpu_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_fill_super",
        "mm/backing-dev.c:wb_init",
        "mm/mmap.c:mmap_init",
        "fs/file_table.c:files_init",
        "fs/quota/dquot.c:dquot_init",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-cgroup.c:blkg_alloc",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_init",
        "lib/flex_proportions.c:fprop_local_init_percpu",
        "lib/flex_proportions.c:fprop_global_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290623360,
      "name": "__percpu_counter_init",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int __percpu_counter_init(struct percpu_counter * fbc, s64 amount, gfp_t gfp, struct lock_class_key * key)
```

```json
{
  "name": "__percpu_counter_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275366994,
      "name": "__percpu_counter_init",
      "external": true,
      "loc": "lib/percpu_counter.c:122",
      "file": "lib/percpu_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_fill_super",
        "mm/backing-dev.c:wb_init",
        "mm/mmap.c:mmap_init",
        "fs/file_table.c:files_init",
        "fs/quota/dquot.c:dquot_init",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-cgroup.c:blkg_alloc",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_init",
        "lib/flex_proportions.c:fprop_local_init_percpu",
        "lib/flex_proportions.c:fprop_global_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275366994,
      "name": "__percpu_counter_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
int __percpu_counter_init(struct percpu_counter * fbc, s64 amount, gfp_t gfp, struct lock_class_key * key)
```

```json
{
  "name": "__percpu_counter_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584395712,
      "name": "__percpu_counter_init",
      "external": true,
      "loc": "lib/percpu_counter.c:122",
      "file": "lib/percpu_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_fill_super",
        "mm/backing-dev.c:wb_init",
        "mm/mmap.c:mmap_init",
        "fs/file_table.c:files_init",
        "fs/quota/dquot.c:dquot_init",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-cgroup.c:blkg_alloc",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_init",
        "lib/flex_proportions.c:fprop_local_init_percpu",
        "lib/flex_proportions.c:fprop_global_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584395712,
      "name": "__percpu_counter_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int __percpu_counter_init(struct percpu_counter * fbc, s64 amount, gfp_t gfp, struct lock_class_key * key)
```

```json
{
  "name": "__percpu_counter_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584330912,
      "name": "__percpu_counter_init",
      "external": true,
      "loc": "lib/percpu_counter.c:122",
      "file": "lib/percpu_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_fill_super",
        "mm/backing-dev.c:wb_init",
        "mm/mmap.c:mmap_init",
        "fs/file_table.c:files_init",
        "fs/quota/dquot.c:dquot_init",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-cgroup.c:blkg_alloc",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_init",
        "lib/flex_proportions.c:fprop_local_init_percpu",
        "lib/flex_proportions.c:fprop_global_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584330912,
      "name": "__percpu_counter_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int __percpu_counter_init(struct percpu_counter * fbc, s64 amount, gfp_t gfp, struct lock_class_key * key)
```

```json
{
  "name": "__percpu_counter_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584378624,
      "name": "__percpu_counter_init",
      "external": true,
      "loc": "lib/percpu_counter.c:122",
      "file": "lib/percpu_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_fill_super",
        "mm/backing-dev.c:wb_init",
        "mm/mmap.c:mmap_init",
        "fs/file_table.c:files_init",
        "fs/quota/dquot.c:dquot_init",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-cgroup.c:blkg_alloc",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_init",
        "lib/flex_proportions.c:fprop_local_init_percpu",
        "lib/flex_proportions.c:fprop_global_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584378624,
      "name": "__percpu_counter_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int __percpu_counter_init(struct percpu_counter * fbc, s64 amount, gfp_t gfp, struct lock_class_key * key)
```

```json
{
  "name": "__percpu_counter_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584484848,
      "name": "__percpu_counter_init",
      "external": true,
      "loc": "lib/percpu_counter.c:122",
      "file": "lib/percpu_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_fill_super",
        "mm/backing-dev.c:wb_init",
        "mm/mmap.c:mmap_init",
        "fs/file_table.c:files_init",
        "fs/quota/dquot.c:dquot_init",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-cgroup.c:blkg_alloc",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_init",
        "lib/flex_proportions.c:fprop_local_init_percpu",
        "lib/flex_proportions.c:fprop_global_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584484848,
      "name": "__percpu_counter_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
int __percpu_counter_init(struct percpu_counter * fbc, s64 amount, gfp_t gfp, struct lock_class_key * key)
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
