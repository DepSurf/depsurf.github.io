# Function: <code>percpu_counter_destroy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void percpu_counter_destroy(struct percpu_counter * fbc)
```

```json
{
  "name": "percpu_counter_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583112240,
      "name": "percpu_counter_destroy",
      "external": true,
      "loc": "lib/percpu_counter.c:139",
      "file": "lib/percpu_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_put_super",
        "mm/backing-dev.c:wb_init",
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_exit",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "block/blk-cgroup.c:blkg_free",
        "block/blk-cgroup.c:blkg_free",
        "block/blk-cgroup.c:blkg_free",
        "block/blk-cgroup.c:blkg_free",
        "block/blk-cgroup.c:blkg_free",
        "block/blk-cgroup.c:blkg_free",
        "block/blk-cgroup.c:blkg_free",
        "block/blk-cgroup.c:blkg_free",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-cgroup.c:blkg_alloc",
        "block/cfq-iosched.c:cfqg_stats_exit",
        "block/cfq-iosched.c:cfqg_stats_exit",
        "block/cfq-iosched.c:cfqg_stats_exit",
        "block/cfq-iosched.c:cfqg_stats_exit",
        "block/cfq-iosched.c:cfqg_stats_exit",
        "block/cfq-iosched.c:cfqg_stats_exit",
        "block/cfq-iosched.c:cfqg_stats_exit",
        "block/cfq-iosched.c:cfqg_stats_exit",
        "block/cfq-iosched.c:cfqg_stats_exit",
        "block/cfq-iosched.c:cfqg_stats_exit",
        "block/cfq-iosched.c:cfqg_stats_exit",
        "block/cfq-iosched.c:cfqg_stats_exit",
        "block/cfq-iosched.c:cfqg_stats_exit",
        "block/cfq-iosched.c:cfqg_stats_exit",
        "block/cfq-iosched.c:cfqg_stats_exit",
        "block/cfq-iosched.c:cfqg_stats_exit",
        "block/cfq-iosched.c:cfqg_stats_exit",
        "block/cfq-iosched.c:cfq_pd_alloc",
        "block/cfq-iosched.c:cfq_pd_alloc",
        "block/cfq-iosched.c:cfq_pd_alloc",
        "block/cfq-iosched.c:cfq_pd_alloc",
        "lib/flex_proportions.c:fprop_global_destroy",
        "lib/flex_proportions.c:fprop_local_destroy_percpu",
        "net/ipv4/ip_fragment.c:ipv4_frags_init_net",
        "net/ipv4/inet_fragment.c:inet_frags_exit_net",
        "net/ipv4/tcp_memcontrol.c:tcp_destroy_cgroup",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_exit",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_init",
        "net/ipv6/route.c:ip6_route_net_exit",
        "net/ipv6/route.c:ip6_route_net_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/reassembly.c:ipv6_frags_init_net",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_exit",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583112240,
      "name": "percpu_counter_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void percpu_counter_destroy(struct percpu_counter * fbc)
```

```json
{
  "name": "percpu_counter_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583406480,
      "name": "percpu_counter_destroy",
      "external": true,
      "loc": "lib/percpu_counter.c:139",
      "file": "lib/percpu_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_put_super",
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_init",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-cgroup.c:blkg_free",
        "block/blk-cgroup.c:blkg_free",
        "block/cfq-iosched.c:cfq_pd_alloc",
        "block/cfq-iosched.c:cfq_pd_alloc",
        "block/cfq-iosched.c:cfq_pd_alloc",
        "block/cfq-iosched.c:cfq_pd_alloc",
        "block/cfq-iosched.c:cfqg_stats_exit",
        "block/cfq-iosched.c:cfqg_stats_exit",
        "block/cfq-iosched.c:cfqg_stats_exit",
        "block/cfq-iosched.c:cfqg_stats_exit",
        "block/cfq-iosched.c:cfqg_stats_exit",
        "lib/flex_proportions.c:fprop_local_destroy_percpu",
        "lib/flex_proportions.c:fprop_global_destroy",
        "net/ipv4/ip_fragment.c:ipv4_frags_init_net",
        "net/ipv4/inet_fragment.c:inet_frags_exit_net",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_exit",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_init",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_net_exit",
        "net/ipv6/route.c:ip6_route_net_init",
        "net/ipv6/reassembly.c:ipv6_frags_init_net",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_exit",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583406480,
      "name": "percpu_counter_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void percpu_counter_destroy(struct percpu_counter * fbc)
```

```json
{
  "name": "percpu_counter_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583531856,
      "name": "percpu_counter_destroy",
      "external": true,
      "loc": "lib/percpu_counter.c:139",
      "file": "lib/percpu_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_put_super",
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_init",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-cgroup.c:blkg_free",
        "block/blk-cgroup.c:blkg_free",
        "block/cfq-iosched.c:cfq_pd_alloc",
        "block/cfq-iosched.c:cfq_pd_alloc",
        "block/cfq-iosched.c:cfq_pd_alloc",
        "block/cfq-iosched.c:cfq_pd_alloc",
        "block/cfq-iosched.c:cfqg_stats_exit",
        "block/cfq-iosched.c:cfqg_stats_exit",
        "block/cfq-iosched.c:cfqg_stats_exit",
        "block/cfq-iosched.c:cfqg_stats_exit",
        "block/cfq-iosched.c:cfqg_stats_exit",
        "lib/flex_proportions.c:fprop_local_destroy_percpu",
        "lib/flex_proportions.c:fprop_global_destroy",
        "net/ipv4/ip_fragment.c:ipv4_frags_init_net",
        "net/ipv4/inet_fragment.c:inet_frags_exit_net",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_exit",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_init",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_net_exit",
        "net/ipv6/route.c:ip6_route_net_init",
        "net/ipv6/reassembly.c:ipv6_frags_init_net",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_exit",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583531856,
      "name": "percpu_counter_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void percpu_counter_destroy(struct percpu_counter * fbc)
```

```json
{
  "name": "percpu_counter_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583569552,
      "name": "percpu_counter_destroy",
      "external": true,
      "loc": "lib/percpu_counter.c:146",
      "file": "lib/percpu_counter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_put_super",
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_init",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-cgroup.c:blkg_alloc",
        "block/cfq-iosched.c:cfq_pd_alloc",
        "block/cfq-iosched.c:cfq_pd_alloc",
        "block/cfq-iosched.c:cfq_pd_alloc",
        "block/cfq-iosched.c:cfq_pd_alloc",
        "block/cfq-iosched.c:cfqg_stats_exit",
        "block/cfq-iosched.c:cfqg_stats_exit",
        "block/cfq-iosched.c:cfqg_stats_exit",
        "block/cfq-iosched.c:cfqg_stats_exit",
        "block/cfq-iosched.c:cfqg_stats_exit",
        "block/cfq-iosched.c:cfqg_stats_exit",
        "block/cfq-iosched.c:cfqg_stats_exit",
        "block/cfq-iosched.c:cfqg_stats_exit",
        "block/cfq-iosched.c:cfqg_stats_exit",
        "block/cfq-iosched.c:cfqg_stats_exit",
        "block/cfq-iosched.c:cfqg_stats_exit",
        "block/cfq-iosched.c:cfqg_stats_exit",
        "block/cfq-iosched.c:cfqg_stats_exit",
        "block/cfq-iosched.c:cfqg_stats_exit",
        "block/cfq-iosched.c:cfqg_stats_exit",
        "block/cfq-iosched.c:cfqg_stats_exit",
        "block/cfq-iosched.c:cfqg_stats_exit",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_exit",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_init",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_net_exit",
        "net/ipv6/route.c:ip6_route_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_exit",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_init",
        "lib/flex_proportions.c:fprop_local_destroy_percpu",
        "lib/flex_proportions.c:fprop_global_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583569552,
      "name": "percpu_counter_destroy",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void percpu_counter_destroy(struct percpu_counter * fbc)
```

```json
{
  "name": "percpu_counter_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583814864,
      "name": "percpu_counter_destroy",
      "external": true,
      "loc": "lib/percpu_counter.c:147",
      "file": "lib/percpu_counter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_put_super",
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_init",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-cgroup.c:blkg_alloc",
        "block/cfq-iosched.c:cfq_pd_alloc",
        "block/cfq-iosched.c:cfq_pd_alloc",
        "block/cfq-iosched.c:cfq_pd_alloc",
        "block/cfq-iosched.c:cfq_pd_alloc",
        "block/cfq-iosched.c:cfqg_stats_exit",
        "block/cfq-iosched.c:cfqg_stats_exit",
        "block/cfq-iosched.c:cfqg_stats_exit",
        "block/cfq-iosched.c:cfqg_stats_exit",
        "block/cfq-iosched.c:cfqg_stats_exit",
        "block/cfq-iosched.c:cfqg_stats_exit",
        "block/cfq-iosched.c:cfqg_stats_exit",
        "block/cfq-iosched.c:cfqg_stats_exit",
        "block/cfq-iosched.c:cfqg_stats_exit",
        "block/cfq-iosched.c:cfqg_stats_exit",
        "block/cfq-iosched.c:cfqg_stats_exit",
        "block/cfq-iosched.c:cfqg_stats_exit",
        "block/cfq-iosched.c:cfqg_stats_exit",
        "block/cfq-iosched.c:cfqg_stats_exit",
        "block/cfq-iosched.c:cfqg_stats_exit",
        "block/cfq-iosched.c:cfqg_stats_exit",
        "block/cfq-iosched.c:cfqg_stats_exit",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_exit",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_init",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_net_exit",
        "net/ipv6/route.c:ip6_route_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_exit",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_init",
        "lib/flex_proportions.c:fprop_local_destroy_percpu",
        "lib/flex_proportions.c:fprop_global_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583814864,
      "name": "percpu_counter_destroy",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void percpu_counter_destroy(struct percpu_counter * fbc)
```

```json
{
  "name": "percpu_counter_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584021808,
      "name": "percpu_counter_destroy",
      "external": true,
      "loc": "lib/percpu_counter.c:147",
      "file": "lib/percpu_counter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_put_super",
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_init",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-cgroup.c:blkg_alloc",
        "block/cfq-iosched.c:cfq_pd_alloc",
        "block/cfq-iosched.c:cfq_pd_alloc",
        "block/cfq-iosched.c:cfq_pd_alloc",
        "block/cfq-iosched.c:cfq_pd_alloc",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_exit",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_init",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_net_exit",
        "net/ipv6/route.c:ip6_route_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_exit",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_init",
        "lib/flex_proportions.c:fprop_local_destroy_percpu",
        "lib/flex_proportions.c:fprop_global_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584021808,
      "name": "percpu_counter_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void percpu_counter_destroy(struct percpu_counter * fbc)
```

```json
{
  "name": "percpu_counter_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584103504,
      "name": "percpu_counter_destroy",
      "external": true,
      "loc": "lib/percpu_counter.c:146",
      "file": "lib/percpu_counter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_put_super",
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_init",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-cgroup.c:blkg_alloc",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_exit",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_init",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_net_exit",
        "net/ipv6/route.c:ip6_route_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_exit",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_init",
        "lib/flex_proportions.c:fprop_local_destroy_percpu",
        "lib/flex_proportions.c:fprop_global_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584103504,
      "name": "percpu_counter_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void percpu_counter_destroy(struct percpu_counter * fbc)
```

```json
{
  "name": "percpu_counter_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584292272,
      "name": "percpu_counter_destroy",
      "external": true,
      "loc": "lib/percpu_counter.c:146",
      "file": "lib/percpu_counter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_put_super",
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_init",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-cgroup.c:blkg_alloc",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_exit",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_init",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_net_exit",
        "net/ipv6/route.c:ip6_route_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_exit",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_init",
        "lib/flex_proportions.c:fprop_local_destroy_percpu",
        "lib/flex_proportions.c:fprop_global_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584292272,
      "name": "percpu_counter_destroy",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void percpu_counter_destroy(struct percpu_counter * fbc)
```

```json
{
  "name": "percpu_counter_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584427200,
      "name": "percpu_counter_destroy",
      "external": true,
      "loc": "lib/percpu_counter.c:146",
      "file": "lib/percpu_counter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_put_super",
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_init",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-cgroup.c:blkg_alloc",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_exit",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_init",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_net_exit",
        "net/ipv6/route.c:ip6_route_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_exit",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_init",
        "lib/flex_proportions.c:fprop_local_destroy_percpu",
        "lib/flex_proportions.c:fprop_global_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584427200,
      "name": "percpu_counter_destroy",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void percpu_counter_destroy(struct percpu_counter * fbc)
```

```json
{
  "name": "percpu_counter_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584989344,
      "name": "percpu_counter_destroy",
      "external": true,
      "loc": "lib/percpu_counter.c:146",
      "file": "lib/percpu_counter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_fill_super",
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_init",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "block/blk-cgroup-rwstat.c:blkg_rwstat_exit",
        "block/blk-cgroup-rwstat.c:blkg_rwstat_init",
        "lib/flex_proportions.c:fprop_local_destroy_percpu",
        "lib/flex_proportions.c:fprop_global_destroy",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_exit",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_init",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_net_exit",
        "net/ipv6/route.c:ip6_route_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_exit",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584989344,
      "name": "percpu_counter_destroy",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void percpu_counter_destroy(struct percpu_counter * fbc)
```

```json
{
  "name": "percpu_counter_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585111360,
      "name": "percpu_counter_destroy",
      "external": true,
      "loc": "lib/percpu_counter.c:165",
      "file": "lib/percpu_counter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_fill_super",
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_init",
        "fs/io_uring.c:__io_uring_free",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "block/blk-cgroup-rwstat.c:blkg_rwstat_exit",
        "block/blk-cgroup-rwstat.c:blkg_rwstat_init",
        "lib/flex_proportions.c:fprop_local_destroy_percpu",
        "lib/flex_proportions.c:fprop_global_destroy",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_exit",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_init",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_net_exit",
        "net/ipv6/route.c:ip6_route_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_exit",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585111360,
      "name": "percpu_counter_destroy",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void percpu_counter_destroy(struct percpu_counter * fbc)
```

```json
{
  "name": "percpu_counter_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584991520,
      "name": "percpu_counter_destroy",
      "external": true,
      "loc": "lib/percpu_counter.c:165",
      "file": "lib/percpu_counter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_fill_super",
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_init",
        "fs/io_uring.c:__io_uring_free",
        "fs/io_uring.c:io_uring_alloc_task_context",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "block/blk-cgroup-rwstat.c:blkg_rwstat_exit",
        "block/blk-cgroup-rwstat.c:blkg_rwstat_init",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_exit",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_init",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_net_exit",
        "net/ipv6/route.c:ip6_route_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_exit",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584991520,
      "name": "percpu_counter_destroy",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void percpu_counter_destroy(struct percpu_counter * fbc)
```

```json
{
  "name": "percpu_counter_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585432160,
      "name": "percpu_counter_destroy",
      "external": true,
      "loc": "lib/percpu_counter.c:165",
      "file": "lib/percpu_counter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/user.c:alloc_uid",
        "kernel/user.c:free_uid",
        "mm/shmem.c:shmem_fill_super",
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_init",
        "fs/io_uring.c:__io_uring_free",
        "fs/io_uring.c:io_uring_alloc_task_context",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:journal_init_common",
        "block/blk-cgroup-rwstat.c:blkg_rwstat_exit",
        "block/blk-cgroup-rwstat.c:blkg_rwstat_init",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_exit",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_init",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_net_exit",
        "net/ipv6/route.c:ip6_route_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_exit",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585432160,
      "name": "percpu_counter_destroy",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void percpu_counter_destroy(struct percpu_counter * fbc)
```

```json
{
  "name": "percpu_counter_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586572016,
      "name": "percpu_counter_destroy",
      "external": true,
      "loc": "lib/percpu_counter.c:165",
      "file": "lib/percpu_counter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/user.c:alloc_uid",
        "kernel/user.c:free_uid",
        "mm/shmem.c:shmem_fill_super",
        "mm/backing-dev.c:release_bdi",
        "mm/backing-dev.c:release_bdi",
        "mm/backing-dev.c:release_bdi",
        "mm/backing-dev.c:release_bdi",
        "mm/backing-dev.c:cgwb_create",
        "mm/backing-dev.c:cgwb_create",
        "mm/backing-dev.c:cgwb_create",
        "mm/backing-dev.c:cgwb_create",
        "mm/backing-dev.c:cgwb_release_workfn",
        "mm/backing-dev.c:cgwb_release_workfn",
        "mm/backing-dev.c:cgwb_release_workfn",
        "mm/backing-dev.c:cgwb_release_workfn",
        "mm/backing-dev.c:wb_init",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/super.c:__ext4_fill_super",
        "fs/ext4/super.c:__ext4_fill_super",
        "fs/ext4/super.c:__ext4_fill_super",
        "fs/ext4/super.c:__ext4_fill_super",
        "fs/ext4/super.c:__ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:journal_init_common",
        "block/blk-cgroup-rwstat.c:blkg_rwstat_exit",
        "block/blk-cgroup-rwstat.c:blkg_rwstat_init",
        "io_uring/io_uring.c:__io_uring_free",
        "io_uring/io_uring.c:io_uring_alloc_task_context",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_exit",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_init",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_net_exit",
        "net/ipv6/route.c:ip6_route_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_exit",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586572016,
      "name": "percpu_counter_destroy",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void percpu_counter_destroy(struct percpu_counter * fbc)
```

```json
{
  "name": "percpu_counter_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587806784,
      "name": "percpu_counter_destroy",
      "external": true,
      "loc": "lib/percpu_counter.c:182",
      "file": "lib/percpu_counter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_init",
        "kernel/fork.c:__mmdrop",
        "kernel/fork.c:__mmdrop",
        "kernel/fork.c:__mmdrop",
        "kernel/fork.c:__mmdrop",
        "kernel/user.c:alloc_uid",
        "kernel/user.c:free_uid",
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "mm/shmem.c:shmem_fill_super",
        "mm/backing-dev.c:release_bdi",
        "mm/backing-dev.c:release_bdi",
        "mm/backing-dev.c:release_bdi",
        "mm/backing-dev.c:release_bdi",
        "mm/backing-dev.c:cgwb_create",
        "mm/backing-dev.c:cgwb_create",
        "mm/backing-dev.c:cgwb_create",
        "mm/backing-dev.c:cgwb_create",
        "mm/backing-dev.c:cgwb_release_workfn",
        "mm/backing-dev.c:cgwb_release_workfn",
        "mm/backing-dev.c:cgwb_release_workfn",
        "mm/backing-dev.c:cgwb_release_workfn",
        "mm/backing-dev.c:wb_init",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/super.c:__ext4_fill_super",
        "fs/ext4/super.c:__ext4_fill_super",
        "fs/ext4/super.c:__ext4_fill_super",
        "fs/ext4/super.c:__ext4_fill_super",
        "fs/ext4/super.c:__ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:journal_init_common",
        "ipc/msg.c:msg_exit_ns",
        "ipc/msg.c:msg_exit_ns",
        "ipc/msg.c:msg_init_ns",
        "block/blk-cgroup-rwstat.c:blkg_rwstat_exit",
        "block/blk-cgroup-rwstat.c:blkg_rwstat_init",
        "io_uring/tctx.c:io_uring_alloc_task_context",
        "io_uring/tctx.c:__io_uring_free",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_exit",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_init",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_net_exit",
        "net/ipv6/route.c:ip6_route_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_exit",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587806784,
      "name": "percpu_counter_destroy",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void percpu_counter_destroy(struct percpu_counter * fbc)
```

```json
{
  "name": "percpu_counter_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588077920,
      "name": "percpu_counter_destroy",
      "external": true,
      "loc": "lib/percpu_counter.c:178",
      "file": "lib/percpu_counter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_init",
        "kernel/fork.c:__mmdrop",
        "kernel/fork.c:__mmdrop",
        "kernel/fork.c:__mmdrop",
        "kernel/fork.c:__mmdrop",
        "kernel/user.c:alloc_uid",
        "kernel/user.c:free_uid",
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "mm/shmem.c:shmem_fill_super",
        "mm/backing-dev.c:release_bdi",
        "mm/backing-dev.c:release_bdi",
        "mm/backing-dev.c:release_bdi",
        "mm/backing-dev.c:release_bdi",
        "mm/backing-dev.c:cgwb_create",
        "mm/backing-dev.c:cgwb_create",
        "mm/backing-dev.c:cgwb_create",
        "mm/backing-dev.c:cgwb_create",
        "mm/backing-dev.c:cgwb_release_workfn",
        "mm/backing-dev.c:cgwb_release_workfn",
        "mm/backing-dev.c:cgwb_release_workfn",
        "mm/backing-dev.c:cgwb_release_workfn",
        "mm/backing-dev.c:wb_init",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:journal_init_common",
        "ipc/msg.c:msg_exit_ns",
        "ipc/msg.c:msg_exit_ns",
        "ipc/msg.c:msg_init_ns",
        "block/blk-cgroup-rwstat.c:blkg_rwstat_exit",
        "block/blk-cgroup-rwstat.c:blkg_rwstat_init",
        "io_uring/tctx.c:io_uring_alloc_task_context",
        "io_uring/tctx.c:__io_uring_free",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_exit",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_init",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_net_exit",
        "net/ipv6/route.c:ip6_route_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_exit",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588077920,
      "name": "percpu_counter_destroy",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "percpu_counter_destroy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579971139,
      "name": "percpu_counter_destroy",
      "external": false,
      "loc": "include/linux/percpu_counter.h:50",
      "file": "kernel/user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/user.c:alloc_uid",
        "kernel/user.c:free_uid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582302436,
      "name": "percpu_counter_destroy",
      "external": false,
      "loc": "include/linux/percpu_counter.h:50",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582931332,
      "name": "percpu_counter_destroy",
      "external": false,
      "loc": "include/linux/percpu_counter.h:50",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_put_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582994312,
      "name": "percpu_counter_destroy",
      "external": false,
      "loc": "include/linux/percpu_counter.h:50",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584980005,
      "name": "percpu_counter_destroy",
      "external": false,
      "loc": "include/linux/percpu_counter.h:50",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585326581,
      "name": "percpu_counter_destroy",
      "external": false,
      "loc": "include/linux/percpu_counter.h:50",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_percpu_param_destroy",
        "fs/ext4/super.c:ext4_percpu_param_destroy",
        "fs/ext4/super.c:ext4_percpu_param_destroy",
        "fs/ext4/super.c:ext4_percpu_param_destroy",
        "fs/ext4/super.c:ext4_percpu_param_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585506979,
      "name": "percpu_counter_destroy",
      "external": false,
      "loc": "include/linux/percpu_counter.h:50",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:journal_init_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585876728,
      "name": "percpu_counter_destroy",
      "external": false,
      "loc": "include/linux/percpu_counter.h:50",
      "file": "ipc/msg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/msg.c:msg_exit_ns",
        "ipc/msg.c:msg_exit_ns",
        "ipc/msg.c:msg_init_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587129882,
      "name": "percpu_counter_destroy",
      "external": false,
      "loc": "include/linux/percpu_counter.h:50",
      "file": "block/blk-cgroup-rwstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup-rwstat.c:blkg_rwstat_exit",
        "block/blk-cgroup-rwstat.c:blkg_rwstat_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587369095,
      "name": "percpu_counter_destroy",
      "external": false,
      "loc": "include/linux/percpu_counter.h:50",
      "file": "io_uring/tctx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/tctx.c:io_uring_alloc_task_context",
        "io_uring/tctx.c:__io_uring_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595959461,
      "name": "percpu_counter_destroy",
      "external": false,
      "loc": "include/linux/percpu_counter.h:50",
      "file": "net/ipv4/xfrm4_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_policy.c:xfrm4_net_exit",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596309732,
      "name": "percpu_counter_destroy",
      "external": false,
      "loc": "include/linux/percpu_counter.h:50",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_net_exit",
        "net/ipv6/route.c:ip6_route_net_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596540933,
      "name": "percpu_counter_destroy",
      "external": false,
      "loc": "include/linux/percpu_counter.h:50",
      "file": "net/ipv6/xfrm6_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_policy.c:xfrm6_net_exit",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597164144,
      "name": "percpu_counter_destroy",
      "external": false,
      "loc": "include/linux/percpu_counter.h:50",
      "file": "lib/flex_proportions.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void percpu_counter_destroy(struct percpu_counter * fbc)
```

```json
{
  "name": "percpu_counter_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496311280,
      "name": "percpu_counter_destroy",
      "external": true,
      "loc": "lib/percpu_counter.c:146",
      "file": "lib/percpu_counter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_put_super",
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_init",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-cgroup.c:blkg_alloc",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_exit",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_init",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_net_exit",
        "net/ipv6/route.c:ip6_route_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_exit",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_init",
        "lib/flex_proportions.c:fprop_local_destroy_percpu",
        "lib/flex_proportions.c:fprop_global_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496311280,
      "name": "percpu_counter_destroy",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void percpu_counter_destroy(struct percpu_counter * fbc)
```

```json
{
  "name": "percpu_counter_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229648220,
      "name": "percpu_counter_destroy",
      "external": true,
      "loc": "lib/percpu_counter.c:146",
      "file": "lib/percpu_counter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_put_super",
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_init",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-cgroup.c:blkg_alloc",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_exit",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_init",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_net_exit",
        "net/ipv6/route.c:ip6_route_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_exit",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_init",
        "lib/flex_proportions.c:fprop_local_destroy_percpu",
        "lib/flex_proportions.c:fprop_global_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229648220,
      "name": "percpu_counter_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void percpu_counter_destroy(struct percpu_counter * fbc)
```

```json
{
  "name": "percpu_counter_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290623760,
      "name": "percpu_counter_destroy",
      "external": true,
      "loc": "lib/percpu_counter.c:146",
      "file": "lib/percpu_counter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_put_super",
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_init",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-cgroup.c:blkg_alloc",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_exit",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_exit",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_init",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_net_exit",
        "net/ipv6/route.c:ip6_route_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_exit",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_exit",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_init",
        "lib/flex_proportions.c:fprop_local_destroy_percpu",
        "lib/flex_proportions.c:fprop_global_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290623760,
      "name": "percpu_counter_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
void percpu_counter_destroy(struct percpu_counter * fbc)
```

```json
{
  "name": "percpu_counter_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275367044,
      "name": "percpu_counter_destroy",
      "external": true,
      "loc": "lib/percpu_counter.c:146",
      "file": "lib/percpu_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_put_super",
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_init",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-cgroup.c:blkg_alloc",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_exit",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_init",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_net_exit",
        "net/ipv6/route.c:ip6_route_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_exit",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_init",
        "lib/flex_proportions.c:fprop_local_destroy_percpu",
        "lib/flex_proportions.c:fprop_global_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275367044,
      "name": "percpu_counter_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void percpu_counter_destroy(struct percpu_counter * fbc)
```

```json
{
  "name": "percpu_counter_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584395936,
      "name": "percpu_counter_destroy",
      "external": true,
      "loc": "lib/percpu_counter.c:146",
      "file": "lib/percpu_counter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_put_super",
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_init",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-cgroup.c:blkg_alloc",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_exit",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_init",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_net_exit",
        "net/ipv6/route.c:ip6_route_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_exit",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_init",
        "lib/flex_proportions.c:fprop_local_destroy_percpu",
        "lib/flex_proportions.c:fprop_global_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584395936,
      "name": "percpu_counter_destroy",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void percpu_counter_destroy(struct percpu_counter * fbc)
```

```json
{
  "name": "percpu_counter_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584331136,
      "name": "percpu_counter_destroy",
      "external": true,
      "loc": "lib/percpu_counter.c:146",
      "file": "lib/percpu_counter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_put_super",
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_init",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-cgroup.c:blkg_alloc",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_exit",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_init",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_net_exit",
        "net/ipv6/route.c:ip6_route_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_exit",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_init",
        "lib/flex_proportions.c:fprop_local_destroy_percpu",
        "lib/flex_proportions.c:fprop_global_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584331136,
      "name": "percpu_counter_destroy",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void percpu_counter_destroy(struct percpu_counter * fbc)
```

```json
{
  "name": "percpu_counter_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584378848,
      "name": "percpu_counter_destroy",
      "external": true,
      "loc": "lib/percpu_counter.c:146",
      "file": "lib/percpu_counter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_put_super",
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_init",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-cgroup.c:blkg_alloc",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_exit",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_init",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_net_exit",
        "net/ipv6/route.c:ip6_route_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_exit",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_init",
        "lib/flex_proportions.c:fprop_local_destroy_percpu",
        "lib/flex_proportions.c:fprop_global_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584378848,
      "name": "percpu_counter_destroy",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void percpu_counter_destroy(struct percpu_counter * fbc)
```

```json
{
  "name": "percpu_counter_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584485072,
      "name": "percpu_counter_destroy",
      "external": true,
      "loc": "lib/percpu_counter.c:146",
      "file": "lib/percpu_counter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_put_super",
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_init",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/extents_status.c:ext4_es_register_shrinker",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-cgroup.c:blkg_alloc",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_exit",
        "net/ipv4/xfrm4_policy.c:xfrm4_net_init",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_net_exit",
        "net/ipv6/route.c:ip6_route_net_init",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_exit",
        "net/ipv6/xfrm6_policy.c:xfrm6_net_init",
        "lib/flex_proportions.c:fprop_local_destroy_percpu",
        "lib/flex_proportions.c:fprop_global_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584485072,
      "name": "percpu_counter_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void percpu_counter_destroy(struct percpu_counter * fbc)
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
