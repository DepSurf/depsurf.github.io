# Function: <code>percpu_counter_destroy_many</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void percpu_counter_destroy_many(struct percpu_counter * fbc, u32 nr_counters)
```

```json
{
  "name": "percpu_counter_destroy_many",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588412464,
      "name": "percpu_counter_destroy_many",
      "external": true,
      "loc": "lib/percpu_counter.c:193",
      "file": "lib/percpu_counter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:__mmdrop",
        "kernel/user.c:alloc_uid",
        "kernel/user.c:free_uid",
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/hashtab.c:htab_map_alloc",
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
        "fs/ext4/super.c:ext4_percpu_param_destroy",
        "fs/ext4/super.c:ext4_percpu_param_destroy",
        "fs/ext4/super.c:ext4_percpu_param_destroy",
        "fs/ext4/super.c:ext4_percpu_param_destroy",
        "fs/ext4/super.c:ext4_percpu_param_destroy",
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
      "addr": 18446744071588412464,
      "name": "percpu_counter_destroy_many",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
void percpu_counter_destroy_many(struct percpu_counter * fbc, u32 nr_counters)
```
</details>
</li>
</ul>
