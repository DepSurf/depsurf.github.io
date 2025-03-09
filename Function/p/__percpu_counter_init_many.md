# Function: <code>__percpu_counter_init_many</code>

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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int __percpu_counter_init_many(struct percpu_counter * fbc, s64 amount, gfp_t gfp, u32 nr_counters, struct lock_class_key * key)
```

```json
{
  "name": "__percpu_counter_init_many",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588412192,
      "name": "__percpu_counter_init_many",
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
      "addr": 18446744071588412192,
      "name": "__percpu_counter_init_many",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
int __percpu_counter_init_many(struct percpu_counter * fbc, s64 amount, gfp_t gfp, u32 nr_counters, struct lock_class_key * key)
```
</details>
</li>
</ul>
