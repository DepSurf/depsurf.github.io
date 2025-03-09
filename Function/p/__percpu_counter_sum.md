# Function: <code>__percpu_counter_sum</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
s64 __percpu_counter_sum(struct percpu_counter * fbc)
```

```json
{
  "name": "__percpu_counter_sum",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583111872,
      "name": "__percpu_counter_sum",
      "external": true,
      "loc": "lib/percpu_counter.c:98",
      "file": "lib/percpu_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_statfs",
        "fs/file_table.c:get_empty_filp",
        "fs/quota/dquot.c:do_proc_dqstats",
        "fs/ext4/balloc.c:ext4_has_free_clusters",
        "fs/ext4/balloc.c:ext4_has_free_clusters",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/super.c:ext4_statfs",
        "fs/ext4/super.c:ext4_statfs",
        "fs/ext4/super.c:ext4_statfs",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/sysfs.c:ext4_attr_show",
        "block/blk-cgroup.c:blkg_prfill_stat",
        "block/blk-cgroup.c:blkg_rwstat_read",
        "block/blk-cgroup.c:blkg_stat_recursive_sum",
        "block/blk-cgroup.c:blkg_rwstat_recursive_sum",
        "block/cfq-iosched.c:blkg_rwstat_read",
        "block/cfq-iosched.c:cfq_pd_offline",
        "lib/flex_proportions.c:fprop_new_period",
        "net/ipv4/route.c:rt_cpu_seq_show",
        "net/ipv4/ip_fragment.c:ip_frag_mem",
        "net/ipv4/tcp.c:tcp_check_oom",
        "net/ipv4/inet_fragment.c:inet_frags_exit_net",
        "net/ipv4/proc.c:sockstat_seq_show",
        "net/ipv4/proc.c:sockstat_seq_show",
        "net/ipv4/xfrm4_policy.c:xfrm4_garbage_collect",
        "net/ipv6/route.c:ip6_dst_gc",
        "net/ipv6/route.c:rt6_stats_seq_show",
        "net/ipv6/proc.c:sockstat6_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583111872,
      "name": "__percpu_counter_sum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
s64 __percpu_counter_sum(struct percpu_counter * fbc)
```

```json
{
  "name": "__percpu_counter_sum",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583406128,
      "name": "__percpu_counter_sum",
      "external": true,
      "loc": "lib/percpu_counter.c:98",
      "file": "lib/percpu_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_statfs",
        "fs/file_table.c:get_empty_filp",
        "fs/quota/dquot.c:do_proc_dqstats",
        "fs/ext4/balloc.c:ext4_has_free_clusters",
        "fs/ext4/balloc.c:ext4_has_free_clusters",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/super.c:ext4_statfs",
        "fs/ext4/super.c:ext4_statfs",
        "fs/ext4/super.c:ext4_statfs",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/sysfs.c:ext4_attr_show",
        "block/blk-cgroup.c:blkg_rwstat_recursive_sum",
        "block/blk-cgroup.c:blkg_stat_recursive_sum",
        "block/blk-cgroup.c:blkg_prfill_stat",
        "block/blk-cgroup.c:blkg_rwstat_read",
        "block/cfq-iosched.c:cfq_pd_offline",
        "block/cfq-iosched.c:blkg_rwstat_read",
        "lib/flex_proportions.c:fprop_new_period",
        "net/ipv4/route.c:rt_cpu_seq_show",
        "net/ipv4/ip_fragment.c:ip_frag_mem",
        "net/ipv4/tcp.c:tcp_check_oom",
        "net/ipv4/inet_fragment.c:inet_frags_exit_net",
        "net/ipv4/proc.c:sockstat_seq_show",
        "net/ipv4/proc.c:sockstat_seq_show",
        "net/ipv4/xfrm4_policy.c:xfrm4_garbage_collect",
        "net/ipv6/route.c:rt6_stats_seq_show",
        "net/ipv6/route.c:ip6_dst_gc",
        "net/ipv6/proc.c:sockstat6_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583406128,
      "name": "__percpu_counter_sum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
s64 __percpu_counter_sum(struct percpu_counter * fbc)
```

```json
{
  "name": "__percpu_counter_sum",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583531504,
      "name": "__percpu_counter_sum",
      "external": true,
      "loc": "lib/percpu_counter.c:98",
      "file": "lib/percpu_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_statfs",
        "fs/file_table.c:get_empty_filp",
        "fs/quota/dquot.c:do_proc_dqstats",
        "fs/ext4/balloc.c:ext4_has_free_clusters",
        "fs/ext4/balloc.c:ext4_has_free_clusters",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/super.c:ext4_statfs",
        "fs/ext4/super.c:ext4_statfs",
        "fs/ext4/super.c:ext4_statfs",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/sysfs.c:ext4_attr_show",
        "block/blk-cgroup.c:blkg_rwstat_recursive_sum",
        "block/blk-cgroup.c:blkg_stat_recursive_sum",
        "block/blk-cgroup.c:blkg_prfill_stat",
        "block/blk-cgroup.c:blkg_rwstat_read",
        "block/cfq-iosched.c:cfq_pd_offline",
        "block/cfq-iosched.c:blkg_rwstat_read",
        "lib/flex_proportions.c:fprop_new_period",
        "net/ipv4/route.c:rt_cpu_seq_show",
        "net/ipv4/ip_fragment.c:ip_frag_mem",
        "net/ipv4/tcp.c:tcp_check_oom",
        "net/ipv4/inet_fragment.c:inet_frags_exit_net",
        "net/ipv4/proc.c:sockstat_seq_show",
        "net/ipv4/proc.c:sockstat_seq_show",
        "net/ipv4/xfrm4_policy.c:xfrm4_garbage_collect",
        "net/ipv6/route.c:rt6_stats_seq_show",
        "net/ipv6/route.c:ip6_dst_gc",
        "net/ipv6/proc.c:sockstat6_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583531504,
      "name": "__percpu_counter_sum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
s64 __percpu_counter_sum(struct percpu_counter * fbc)
```

```json
{
  "name": "__percpu_counter_sum",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583569200,
      "name": "__percpu_counter_sum",
      "external": true,
      "loc": "lib/percpu_counter.c:105",
      "file": "lib/percpu_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_statfs",
        "fs/file_table.c:get_empty_filp",
        "fs/quota/dquot.c:do_proc_dqstats",
        "fs/ext4/balloc.c:ext4_has_free_clusters",
        "fs/ext4/balloc.c:ext4_has_free_clusters",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/super.c:ext4_statfs",
        "fs/ext4/super.c:ext4_statfs",
        "fs/ext4/super.c:ext4_statfs",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/sysfs.c:ext4_attr_show",
        "block/blk-cgroup.c:blkg_rwstat_recursive_sum",
        "block/blk-cgroup.c:blkg_stat_recursive_sum",
        "block/blk-cgroup.c:blkg_prfill_stat",
        "block/blk-cgroup.c:blkg_rwstat_read",
        "block/cfq-iosched.c:cfq_pd_offline",
        "block/cfq-iosched.c:blkg_rwstat_read",
        "net/ipv4/route.c:rt_cpu_seq_show",
        "net/ipv4/tcp.c:tcp_check_oom",
        "net/ipv4/proc.c:sockstat_seq_show",
        "net/ipv4/proc.c:sockstat_seq_show",
        "net/ipv4/xfrm4_policy.c:xfrm4_garbage_collect",
        "net/ipv6/route.c:rt6_stats_seq_show",
        "net/ipv6/route.c:ip6_dst_gc",
        "lib/flex_proportions.c:fprop_new_period"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583569200,
      "name": "__percpu_counter_sum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
s64 __percpu_counter_sum(struct percpu_counter * fbc)
```

```json
{
  "name": "__percpu_counter_sum",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583814528,
      "name": "__percpu_counter_sum",
      "external": true,
      "loc": "lib/percpu_counter.c:106",
      "file": "lib/percpu_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/shmem.c:shmem_statfs",
        "fs/file_table.c:get_empty_filp",
        "fs/quota/dquot.c:do_proc_dqstats",
        "fs/ext4/balloc.c:ext4_has_free_clusters",
        "fs/ext4/balloc.c:ext4_has_free_clusters",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/super.c:ext4_statfs",
        "fs/ext4/super.c:ext4_statfs",
        "fs/ext4/super.c:ext4_statfs",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/sysfs.c:ext4_attr_show",
        "block/blk-cgroup.c:blkg_rwstat_recursive_sum",
        "block/blk-cgroup.c:blkg_stat_recursive_sum",
        "block/blk-cgroup.c:blkg_prfill_stat",
        "block/blk-cgroup.c:blkg_rwstat_read",
        "block/cfq-iosched.c:cfq_pd_offline",
        "block/cfq-iosched.c:blkg_rwstat_read",
        "net/ipv4/route.c:rt_cpu_seq_show",
        "net/ipv4/tcp.c:tcp_check_oom",
        "net/ipv4/proc.c:sockstat_seq_show",
        "net/ipv4/proc.c:sockstat_seq_show",
        "net/ipv6/route.c:rt6_stats_seq_show",
        "net/ipv6/route.c:ip6_dst_gc",
        "lib/flex_proportions.c:fprop_new_period"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583814528,
      "name": "__percpu_counter_sum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
s64 __percpu_counter_sum(struct percpu_counter * fbc)
```

```json
{
  "name": "__percpu_counter_sum",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584021472,
      "name": "__percpu_counter_sum",
      "external": true,
      "loc": "lib/percpu_counter.c:106",
      "file": "lib/percpu_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/shmem.c:shmem_statfs",
        "fs/file_table.c:get_empty_filp",
        "fs/quota/dquot.c:do_proc_dqstats",
        "fs/ext4/balloc.c:ext4_has_free_clusters",
        "fs/ext4/balloc.c:ext4_has_free_clusters",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/super.c:ext4_statfs",
        "fs/ext4/super.c:ext4_statfs",
        "fs/ext4/super.c:ext4_statfs",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/sysfs.c:ext4_attr_show",
        "block/blk-cgroup.c:blkg_rwstat_recursive_sum",
        "block/blk-cgroup.c:blkg_stat_recursive_sum",
        "block/blk-cgroup.c:blkg_prfill_stat",
        "block/blk-cgroup.c:blkg_destroy",
        "block/blk-cgroup.c:blkg_destroy",
        "block/blk-cgroup.c:blkg_rwstat_read",
        "block/cfq-iosched.c:cfq_pd_offline",
        "block/cfq-iosched.c:cfq_pd_offline",
        "block/cfq-iosched.c:cfq_pd_offline",
        "block/cfq-iosched.c:cfq_pd_offline",
        "block/cfq-iosched.c:blkg_rwstat_read",
        "net/ipv4/route.c:rt_cpu_seq_show",
        "net/ipv4/tcp.c:tcp_check_oom",
        "net/ipv4/proc.c:sockstat_seq_show",
        "net/ipv4/proc.c:sockstat_seq_show",
        "net/ipv6/route.c:rt6_stats_seq_show",
        "net/ipv6/route.c:ip6_dst_gc",
        "lib/flex_proportions.c:fprop_new_period"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584021472,
      "name": "__percpu_counter_sum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
s64 __percpu_counter_sum(struct percpu_counter * fbc)
```

```json
{
  "name": "__percpu_counter_sum",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584103168,
      "name": "__percpu_counter_sum",
      "external": true,
      "loc": "lib/percpu_counter.c:105",
      "file": "lib/percpu_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/shmem.c:shmem_statfs",
        "fs/quota/dquot.c:do_proc_dqstats",
        "fs/ext4/balloc.c:ext4_has_free_clusters",
        "fs/ext4/balloc.c:ext4_has_free_clusters",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/super.c:ext4_statfs",
        "fs/ext4/super.c:ext4_statfs",
        "fs/ext4/super.c:ext4_statfs",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/sysfs.c:ext4_attr_show",
        "block/blk-cgroup.c:blkg_rwstat_recursive_sum",
        "block/blk-cgroup.c:blkg_stat_recursive_sum",
        "block/blk-cgroup.c:blkg_prfill_stat",
        "block/blk-cgroup.c:blkg_destroy",
        "block/blk-cgroup.c:blkg_destroy",
        "block/blk-cgroup.c:blkg_rwstat_read",
        "net/ipv4/route.c:rt_cpu_seq_show",
        "net/ipv4/tcp.c:tcp_check_oom",
        "net/ipv4/proc.c:sockstat_seq_show",
        "net/ipv4/proc.c:sockstat_seq_show",
        "net/ipv6/route.c:rt6_stats_seq_show",
        "net/ipv6/route.c:ip6_dst_gc",
        "lib/flex_proportions.c:fprop_new_period"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584103168,
      "name": "__percpu_counter_sum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
s64 __percpu_counter_sum(struct percpu_counter * fbc)
```

```json
{
  "name": "__percpu_counter_sum",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584291920,
      "name": "__percpu_counter_sum",
      "external": true,
      "loc": "lib/percpu_counter.c:105",
      "file": "lib/percpu_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/shmem.c:shmem_statfs",
        "fs/quota/dquot.c:do_proc_dqstats",
        "fs/ext4/balloc.c:ext4_has_free_clusters",
        "fs/ext4/balloc.c:ext4_has_free_clusters",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/super.c:ext4_statfs",
        "fs/ext4/super.c:ext4_statfs",
        "fs/ext4/super.c:ext4_statfs",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/sysfs.c:ext4_attr_show",
        "block/blk-cgroup.c:blkg_rwstat_recursive_sum",
        "block/blk-cgroup.c:blkg_prfill_rwstat_field",
        "block/blk-cgroup.c:blkg_prfill_rwstat",
        "block/blk-cgroup.c:blkg_destroy",
        "block/blk-cgroup.c:blkg_destroy",
        "net/ipv4/route.c:rt_cpu_seq_show",
        "net/ipv4/tcp.c:tcp_check_oom",
        "net/ipv4/proc.c:sockstat_seq_show",
        "net/ipv4/proc.c:sockstat_seq_show",
        "net/ipv6/route.c:rt6_stats_seq_show",
        "net/ipv6/route.c:ip6_dst_gc",
        "lib/flex_proportions.c:fprop_new_period"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584291920,
      "name": "__percpu_counter_sum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
s64 __percpu_counter_sum(struct percpu_counter * fbc)
```

```json
{
  "name": "__percpu_counter_sum",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584426752,
      "name": "__percpu_counter_sum",
      "external": true,
      "loc": "lib/percpu_counter.c:105",
      "file": "lib/percpu_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/shmem.c:shmem_statfs",
        "fs/quota/dquot.c:do_proc_dqstats",
        "fs/ext4/balloc.c:ext4_has_free_clusters",
        "fs/ext4/balloc.c:ext4_has_free_clusters",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/super.c:ext4_statfs",
        "fs/ext4/super.c:ext4_statfs",
        "fs/ext4/super.c:ext4_statfs",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/sysfs.c:ext4_attr_show",
        "block/blk-cgroup.c:blkg_rwstat_recursive_sum",
        "block/blk-cgroup.c:blkg_prfill_rwstat_field",
        "block/blk-cgroup.c:blkg_prfill_rwstat",
        "block/blk-cgroup.c:blkg_destroy",
        "block/blk-cgroup.c:blkg_destroy",
        "net/ipv4/route.c:rt_cpu_seq_show",
        "net/ipv4/tcp.c:tcp_check_oom",
        "net/ipv4/proc.c:sockstat_seq_show",
        "net/ipv4/proc.c:sockstat_seq_show",
        "net/ipv6/route.c:rt6_stats_seq_show",
        "net/ipv6/route.c:ip6_dst_gc",
        "lib/flex_proportions.c:fprop_new_period"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584426752,
      "name": "__percpu_counter_sum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
s64 __percpu_counter_sum(struct percpu_counter * fbc)
```

```json
{
  "name": "__percpu_counter_sum",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584988896,
      "name": "__percpu_counter_sum",
      "external": true,
      "loc": "lib/percpu_counter.c:105",
      "file": "lib/percpu_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/shmem.c:shmem_statfs",
        "fs/file_table.c:alloc_empty_file",
        "fs/quota/dquot.c:do_proc_dqstats",
        "fs/ext4/balloc.c:ext4_has_free_clusters",
        "fs/ext4/balloc.c:ext4_has_free_clusters",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/inode.c:ext4_print_free_blocks",
        "fs/ext4/inode.c:ext4_print_free_blocks",
        "fs/ext4/super.c:ext4_statfs",
        "fs/ext4/super.c:ext4_statfs",
        "fs/ext4/super.c:ext4_statfs",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/sysfs.c:ext4_attr_show",
        "block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum",
        "block/blk-cgroup-rwstat.c:blkg_prfill_rwstat",
        "lib/flex_proportions.c:fprop_new_period",
        "net/ipv4/route.c:rt_cpu_seq_show",
        "net/ipv4/tcp.c:tcp_check_oom",
        "net/ipv4/proc.c:sockstat_seq_show",
        "net/ipv4/proc.c:sockstat_seq_show",
        "net/ipv6/route.c:rt6_stats_seq_show",
        "net/ipv6/route.c:ip6_dst_gc",
        "net/ipv6/route.c:ip6_dst_gc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584988896,
      "name": "__percpu_counter_sum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
s64 __percpu_counter_sum(struct percpu_counter * fbc)
```

```json
{
  "name": "__percpu_counter_sum",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585110848,
      "name": "__percpu_counter_sum",
      "external": true,
      "loc": "lib/percpu_counter.c:124",
      "file": "lib/percpu_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/shmem.c:shmem_statfs",
        "mm/util.c:vm_memory_committed",
        "fs/file_table.c:alloc_empty_file",
        "fs/io_uring.c:tctx_inflight",
        "fs/io_uring.c:tctx_inflight",
        "fs/quota/dquot.c:do_proc_dqstats",
        "fs/ext4/balloc.c:ext4_has_free_clusters",
        "fs/ext4/balloc.c:ext4_has_free_clusters",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/inode.c:ext4_print_free_blocks",
        "fs/ext4/inode.c:ext4_print_free_blocks",
        "fs/ext4/super.c:ext4_statfs",
        "fs/ext4/super.c:ext4_statfs",
        "fs/ext4/super.c:ext4_statfs",
        "fs/ext4/super.c:ext4_update_super",
        "fs/ext4/super.c:ext4_update_super",
        "fs/ext4/sysfs.c:ext4_attr_show",
        "fs/ext4/sysfs.c:ext4_attr_show",
        "block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum",
        "block/blk-cgroup-rwstat.c:blkg_prfill_rwstat",
        "lib/flex_proportions.c:fprop_new_period",
        "net/ipv4/route.c:rt_cpu_seq_show",
        "net/ipv4/tcp.c:tcp_check_oom",
        "net/ipv4/proc.c:sockstat_seq_show",
        "net/ipv4/proc.c:sockstat_seq_show",
        "net/ipv6/route.c:rt6_stats_seq_show",
        "net/ipv6/route.c:ip6_dst_gc",
        "net/ipv6/route.c:ip6_dst_gc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585110848,
      "name": "__percpu_counter_sum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
s64 __percpu_counter_sum(struct percpu_counter * fbc)
```

```json
{
  "name": "__percpu_counter_sum",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584991024,
      "name": "__percpu_counter_sum",
      "external": true,
      "loc": "lib/percpu_counter.c:124",
      "file": "lib/percpu_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/shmem.c:shmem_statfs",
        "mm/util.c:vm_memory_committed",
        "fs/file_table.c:alloc_empty_file",
        "fs/io_uring.c:__io_uring_cancel",
        "fs/io_uring.c:__io_uring_cancel",
        "fs/io_uring.c:io_uring_cancel_sqpoll",
        "fs/io_uring.c:io_uring_cancel_sqpoll",
        "fs/quota/dquot.c:do_proc_dqstats",
        "fs/ext4/balloc.c:ext4_has_free_clusters",
        "fs/ext4/balloc.c:ext4_has_free_clusters",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/super.c:ext4_statfs",
        "fs/ext4/super.c:ext4_statfs",
        "fs/ext4/super.c:ext4_statfs",
        "fs/ext4/super.c:ext4_update_super",
        "fs/ext4/super.c:ext4_update_super",
        "fs/ext4/sysfs.c:ext4_attr_show",
        "fs/ext4/sysfs.c:ext4_attr_show",
        "block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum",
        "block/blk-cgroup-rwstat.c:blkg_prfill_rwstat",
        "lib/flex_proportions.c:fprop_new_period",
        "net/ipv4/route.c:rt_cpu_seq_show",
        "net/ipv4/tcp.c:tcp_check_oom",
        "net/ipv4/proc.c:sockstat_seq_show",
        "net/ipv4/proc.c:sockstat_seq_show",
        "net/ipv6/route.c:rt6_stats_seq_show",
        "net/ipv6/route.c:ip6_dst_gc",
        "net/ipv6/route.c:ip6_dst_gc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584991024,
      "name": "__percpu_counter_sum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
s64 __percpu_counter_sum(struct percpu_counter * fbc)
```

```json
{
  "name": "__percpu_counter_sum",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585431616,
      "name": "__percpu_counter_sum",
      "external": true,
      "loc": "lib/percpu_counter.c:124",
      "file": "lib/percpu_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:wb_over_bg_thresh",
        "mm/page-writeback.c:wb_over_bg_thresh",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/shmem.c:shmem_statfs",
        "mm/util.c:vm_memory_committed",
        "fs/file_table.c:alloc_empty_file",
        "fs/io_uring.c:io_uring_cancel_generic",
        "fs/io_uring.c:io_uring_cancel_generic",
        "fs/quota/dquot.c:do_proc_dqstats",
        "fs/ext4/balloc.c:ext4_has_free_clusters",
        "fs/ext4/balloc.c:ext4_has_free_clusters",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/super.c:ext4_statfs",
        "fs/ext4/super.c:ext4_statfs",
        "fs/ext4/super.c:ext4_statfs",
        "fs/ext4/super.c:ext4_update_super",
        "fs/ext4/super.c:ext4_update_super",
        "fs/ext4/sysfs.c:ext4_attr_show",
        "fs/ext4/sysfs.c:ext4_attr_show",
        "block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum",
        "block/blk-cgroup-rwstat.c:blkg_prfill_rwstat",
        "lib/flex_proportions.c:fprop_new_period",
        "net/ipv4/route.c:rt_cpu_seq_show",
        "net/ipv4/proc.c:sockstat_seq_show",
        "net/ipv6/route.c:rt6_stats_seq_show",
        "net/ipv6/route.c:ip6_dst_gc",
        "net/ipv6/route.c:ip6_dst_gc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585431616,
      "name": "__percpu_counter_sum",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
s64 __percpu_counter_sum(struct percpu_counter * fbc)
```

```json
{
  "name": "__percpu_counter_sum",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586571360,
      "name": "__percpu_counter_sum",
      "external": true,
      "loc": "lib/percpu_counter.c:124",
      "file": "lib/percpu_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:wb_over_bg_thresh",
        "mm/page-writeback.c:wb_over_bg_thresh",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/shmem.c:shmem_statfs",
        "mm/util.c:vm_memory_committed",
        "fs/file_table.c:alloc_empty_file",
        "fs/quota/dquot.c:do_proc_dqstats",
        "fs/ext4/balloc.c:ext4_has_free_clusters",
        "fs/ext4/balloc.c:ext4_has_free_clusters",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/super.c:ext4_statfs",
        "fs/ext4/super.c:ext4_statfs",
        "fs/ext4/super.c:ext4_statfs",
        "fs/ext4/super.c:ext4_update_super",
        "fs/ext4/super.c:ext4_update_super",
        "fs/ext4/sysfs.c:ext4_attr_show",
        "fs/ext4/sysfs.c:ext4_attr_show",
        "block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum",
        "block/blk-cgroup-rwstat.c:blkg_prfill_rwstat",
        "io_uring/io_uring.c:io_uring_cancel_generic",
        "io_uring/io_uring.c:io_uring_cancel_generic",
        "lib/percpu_counter.c:__percpu_counter_compare",
        "lib/flex_proportions.c:fprop_new_period",
        "net/ipv4/route.c:rt_cpu_seq_show",
        "net/ipv4/proc.c:sockstat_seq_show",
        "net/ipv6/route.c:rt6_stats_seq_show",
        "net/ipv6/route.c:ip6_dst_gc",
        "net/ipv6/route.c:ip6_dst_gc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586571360,
      "name": "__percpu_counter_sum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
s64 __percpu_counter_sum(struct percpu_counter * fbc)
```

```json
{
  "name": "__percpu_counter_sum",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587806507,
      "name": "__percpu_counter_sum",
      "external": true,
      "loc": "lib/percpu_counter.c:141",
      "file": "lib/percpu_counter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/percpu_counter.c:__percpu_counter_compare"
      ],
      "caller_func": [
        "kernel/fork.c:__mmdrop",
        "mm/page-writeback.c:wb_over_bg_thresh",
        "mm/page-writeback.c:wb_over_bg_thresh",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/shmem.c:shmem_statfs",
        "mm/util.c:vm_memory_committed",
        "mm/slab_common.c:perf_trace_rss_stat",
        "mm/slab_common.c:trace_event_raw_event_rss_stat",
        "fs/file_table.c:alloc_empty_file",
        "fs/quota/dquot.c:do_proc_dqstats",
        "fs/ext4/balloc.c:ext4_has_free_clusters",
        "fs/ext4/balloc.c:ext4_has_free_clusters",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/super.c:ext4_statfs",
        "fs/ext4/super.c:ext4_statfs",
        "fs/ext4/super.c:ext4_statfs",
        "fs/ext4/super.c:ext4_update_super",
        "fs/ext4/super.c:ext4_update_super",
        "fs/ext4/sysfs.c:ext4_attr_show",
        "fs/ext4/sysfs.c:ext4_attr_show",
        "block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum",
        "block/blk-cgroup-rwstat.c:blkg_prfill_rwstat",
        "io_uring/io_uring.c:io_uring_cancel_generic",
        "io_uring/io_uring.c:io_uring_cancel_generic",
        "net/ipv4/route.c:rt_cpu_seq_show",
        "net/ipv4/proc.c:sockstat_seq_show",
        "net/ipv6/route.c:rt6_stats_seq_show",
        "net/ipv6/route.c:ip6_dst_gc",
        "net/ipv6/route.c:ip6_dst_gc",
        "lib/flex_proportions.c:fprop_new_period"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587806384,
      "name": "__percpu_counter_sum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
s64 __percpu_counter_sum(struct percpu_counter * fbc)
```

```json
{
  "name": "__percpu_counter_sum",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588078064,
      "name": "__percpu_counter_sum",
      "external": true,
      "loc": "lib/percpu_counter.c:137",
      "file": "lib/percpu_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:__mmdrop",
        "kernel/bpf/hashtab.c:htab_map_mem_usage",
        "mm/page-writeback.c:wb_over_bg_thresh",
        "mm/page-writeback.c:wb_over_bg_thresh",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/shmem.c:shmem_statfs",
        "mm/util.c:vm_memory_committed",
        "mm/slab_common.c:perf_trace_rss_stat",
        "mm/slab_common.c:trace_event_raw_event_rss_stat",
        "fs/file_table.c:alloc_empty_file",
        "fs/quota/dquot.c:do_proc_dqstats",
        "fs/ext4/balloc.c:ext4_has_free_clusters",
        "fs/ext4/balloc.c:ext4_has_free_clusters",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/super.c:ext4_statfs",
        "fs/ext4/super.c:ext4_statfs",
        "fs/ext4/super.c:ext4_statfs",
        "fs/ext4/super.c:ext4_update_super",
        "fs/ext4/super.c:ext4_update_super",
        "fs/ext4/sysfs.c:ext4_attr_show",
        "fs/ext4/sysfs.c:ext4_attr_show",
        "block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum",
        "block/blk-cgroup-rwstat.c:blkg_prfill_rwstat",
        "io_uring/io_uring.c:io_uring_cancel_generic",
        "io_uring/io_uring.c:io_uring_cancel_generic",
        "lib/percpu_counter.c:__percpu_counter_compare",
        "net/ipv4/route.c:rt_cpu_seq_show",
        "net/ipv4/proc.c:sockstat_seq_show",
        "net/ipv6/route.c:rt6_stats_seq_show",
        "net/ipv6/route.c:ip6_dst_gc",
        "lib/flex_proportions.c:fprop_new_period"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588078064,
      "name": "__percpu_counter_sum",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
s64 __percpu_counter_sum(struct percpu_counter * fbc)
```

```json
{
  "name": "__percpu_counter_sum",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588412960,
      "name": "__percpu_counter_sum",
      "external": true,
      "loc": "lib/percpu_counter.c:137",
      "file": "lib/percpu_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:__mmdrop",
        "kernel/bpf/hashtab.c:htab_map_mem_usage",
        "mm/page-writeback.c:wb_over_bg_thresh",
        "mm/page-writeback.c:wb_over_bg_thresh",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/shmem.c:shmem_statfs",
        "mm/util.c:vm_memory_committed",
        "mm/slab_common.c:perf_trace_rss_stat",
        "mm/slab_common.c:trace_event_raw_event_rss_stat",
        "fs/file_table.c:alloc_empty_file",
        "fs/quota/dquot.c:do_proc_dqstats",
        "fs/ext4/balloc.c:ext4_has_free_clusters",
        "fs/ext4/balloc.c:ext4_has_free_clusters",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/super.c:ext4_statfs",
        "fs/ext4/super.c:ext4_statfs",
        "fs/ext4/super.c:ext4_statfs",
        "fs/ext4/super.c:ext4_update_super",
        "fs/ext4/super.c:ext4_update_super",
        "fs/ext4/sysfs.c:ext4_attr_show",
        "fs/ext4/sysfs.c:ext4_attr_show",
        "block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum",
        "block/blk-cgroup-rwstat.c:blkg_prfill_rwstat",
        "io_uring/io_uring.c:io_uring_cancel_generic",
        "io_uring/io_uring.c:io_uring_cancel_generic",
        "lib/percpu_counter.c:__percpu_counter_compare",
        "net/ipv4/route.c:rt_cpu_seq_show",
        "net/ipv4/proc.c:sockstat_seq_show",
        "net/ipv6/route.c:rt6_stats_seq_show",
        "net/ipv6/route.c:ip6_dst_gc",
        "lib/flex_proportions.c:fprop_new_period"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588412960,
      "name": "__percpu_counter_sum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
s64 __percpu_counter_sum(struct percpu_counter * fbc)
```

```json
{
  "name": "__percpu_counter_sum",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496311720,
      "name": "__percpu_counter_sum",
      "external": true,
      "loc": "lib/percpu_counter.c:105",
      "file": "lib/percpu_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/shmem.c:shmem_statfs",
        "fs/quota/dquot.c:do_proc_dqstats",
        "fs/ext4/balloc.c:ext4_has_free_clusters",
        "fs/ext4/balloc.c:ext4_has_free_clusters",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/super.c:ext4_statfs",
        "fs/ext4/super.c:ext4_statfs",
        "fs/ext4/super.c:ext4_statfs",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/sysfs.c:ext4_attr_show",
        "block/blk-cgroup.c:blkg_rwstat_recursive_sum",
        "block/blk-cgroup.c:blkg_prfill_rwstat_field",
        "block/blk-cgroup.c:blkg_prfill_rwstat",
        "block/blk-cgroup.c:blkg_destroy",
        "block/blk-cgroup.c:blkg_destroy",
        "net/ipv4/route.c:rt_cpu_seq_show",
        "net/ipv4/tcp.c:tcp_check_oom",
        "net/ipv4/proc.c:sockstat_seq_show",
        "net/ipv4/proc.c:sockstat_seq_show",
        "net/ipv6/route.c:rt6_stats_seq_show",
        "net/ipv6/route.c:ip6_dst_gc",
        "lib/flex_proportions.c:fprop_new_period",
        "lib/flex_proportions.c:fprop_new_period"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496311720,
      "name": "__percpu_counter_sum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
s64 __percpu_counter_sum(struct percpu_counter * fbc)
```

```json
{
  "name": "__percpu_counter_sum",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229647800,
      "name": "__percpu_counter_sum",
      "external": true,
      "loc": "lib/percpu_counter.c:105",
      "file": "lib/percpu_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/shmem.c:shmem_statfs",
        "fs/quota/dquot.c:do_proc_dqstats",
        "fs/ext4/balloc.c:ext4_has_free_clusters",
        "fs/ext4/balloc.c:ext4_has_free_clusters",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/super.c:ext4_statfs",
        "fs/ext4/super.c:ext4_statfs",
        "fs/ext4/super.c:ext4_statfs",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/sysfs.c:ext4_attr_show",
        "block/blk-cgroup.c:blkg_rwstat_recursive_sum",
        "block/blk-cgroup.c:blkg_prfill_rwstat_field",
        "block/blk-cgroup.c:blkg_prfill_rwstat",
        "block/blk-cgroup.c:blkg_destroy",
        "block/blk-cgroup.c:blkg_destroy",
        "net/ipv4/route.c:rt_cpu_seq_show",
        "net/ipv4/tcp.c:tcp_check_oom",
        "net/ipv4/proc.c:sockstat_seq_show",
        "net/ipv4/proc.c:sockstat_seq_show",
        "net/ipv6/route.c:rt6_stats_seq_show",
        "net/ipv6/route.c:ip6_dst_gc",
        "lib/flex_proportions.c:fprop_reflect_period_percpu",
        "lib/flex_proportions.c:fprop_new_period"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229647800,
      "name": "__percpu_counter_sum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
s64 __percpu_counter_sum(struct percpu_counter * fbc)
```

```json
{
  "name": "__percpu_counter_sum",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290622896,
      "name": "__percpu_counter_sum",
      "external": true,
      "loc": "lib/percpu_counter.c:105",
      "file": "lib/percpu_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/shmem.c:shmem_statfs",
        "fs/quota/dquot.c:do_proc_dqstats",
        "fs/ext4/balloc.c:ext4_has_free_clusters",
        "fs/ext4/balloc.c:ext4_has_free_clusters",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/super.c:ext4_statfs",
        "fs/ext4/super.c:ext4_statfs",
        "fs/ext4/super.c:ext4_statfs",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/sysfs.c:ext4_attr_show",
        "block/blk-cgroup.c:blkg_rwstat_recursive_sum",
        "block/blk-cgroup.c:blkg_prfill_rwstat_field",
        "block/blk-cgroup.c:blkg_prfill_rwstat",
        "block/blk-cgroup.c:blkg_destroy",
        "block/blk-cgroup.c:blkg_destroy",
        "net/ipv4/route.c:rt_cpu_seq_show",
        "net/ipv4/tcp.c:tcp_check_oom",
        "net/ipv4/proc.c:sockstat_seq_show",
        "net/ipv4/proc.c:sockstat_seq_show",
        "net/ipv6/route.c:rt6_stats_seq_show",
        "net/ipv6/route.c:ip6_dst_gc",
        "lib/flex_proportions.c:fprop_reflect_period_percpu",
        "lib/flex_proportions.c:fprop_new_period"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290622896,
      "name": "__percpu_counter_sum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
s64 __percpu_counter_sum(struct percpu_counter * fbc)
```

```json
{
  "name": "__percpu_counter_sum",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275366854,
      "name": "__percpu_counter_sum",
      "external": true,
      "loc": "lib/percpu_counter.c:105",
      "file": "lib/percpu_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/shmem.c:shmem_statfs",
        "fs/quota/dquot.c:do_proc_dqstats",
        "fs/ext4/balloc.c:ext4_has_free_clusters",
        "fs/ext4/balloc.c:ext4_has_free_clusters",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/super.c:ext4_statfs",
        "fs/ext4/super.c:ext4_statfs",
        "fs/ext4/super.c:ext4_statfs",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/sysfs.c:ext4_attr_show",
        "block/blk-cgroup.c:blkg_rwstat_recursive_sum",
        "block/blk-cgroup.c:blkg_prfill_rwstat_field",
        "block/blk-cgroup.c:blkg_prfill_rwstat",
        "block/blk-cgroup.c:blkg_destroy",
        "block/blk-cgroup.c:blkg_destroy",
        "net/ipv4/route.c:rt_cpu_seq_show",
        "net/ipv4/tcp.c:tcp_check_oom",
        "net/ipv4/proc.c:sockstat_seq_show",
        "net/ipv4/proc.c:sockstat_seq_show",
        "net/ipv6/route.c:rt6_stats_seq_show",
        "net/ipv6/route.c:ip6_dst_gc",
        "lib/flex_proportions.c:fprop_reflect_period_percpu",
        "lib/flex_proportions.c:fprop_new_period"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275366854,
      "name": "__percpu_counter_sum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
s64 __percpu_counter_sum(struct percpu_counter * fbc)
```

```json
{
  "name": "__percpu_counter_sum",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584395488,
      "name": "__percpu_counter_sum",
      "external": true,
      "loc": "lib/percpu_counter.c:105",
      "file": "lib/percpu_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/shmem.c:shmem_statfs",
        "fs/quota/dquot.c:do_proc_dqstats",
        "fs/ext4/balloc.c:ext4_has_free_clusters",
        "fs/ext4/balloc.c:ext4_has_free_clusters",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/super.c:ext4_statfs",
        "fs/ext4/super.c:ext4_statfs",
        "fs/ext4/super.c:ext4_statfs",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/sysfs.c:ext4_attr_show",
        "block/blk-cgroup.c:blkg_rwstat_recursive_sum",
        "block/blk-cgroup.c:blkg_prfill_rwstat_field",
        "block/blk-cgroup.c:blkg_prfill_rwstat",
        "block/blk-cgroup.c:blkg_destroy",
        "block/blk-cgroup.c:blkg_destroy",
        "net/ipv4/route.c:rt_cpu_seq_show",
        "net/ipv4/tcp.c:tcp_check_oom",
        "net/ipv4/proc.c:sockstat_seq_show",
        "net/ipv4/proc.c:sockstat_seq_show",
        "net/ipv6/route.c:rt6_stats_seq_show",
        "net/ipv6/route.c:ip6_dst_gc",
        "lib/flex_proportions.c:fprop_new_period"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584395488,
      "name": "__percpu_counter_sum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
s64 __percpu_counter_sum(struct percpu_counter * fbc)
```

```json
{
  "name": "__percpu_counter_sum",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584330688,
      "name": "__percpu_counter_sum",
      "external": true,
      "loc": "lib/percpu_counter.c:105",
      "file": "lib/percpu_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/shmem.c:shmem_statfs",
        "fs/quota/dquot.c:do_proc_dqstats",
        "fs/ext4/balloc.c:ext4_has_free_clusters",
        "fs/ext4/balloc.c:ext4_has_free_clusters",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/super.c:ext4_statfs",
        "fs/ext4/super.c:ext4_statfs",
        "fs/ext4/super.c:ext4_statfs",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/sysfs.c:ext4_attr_show",
        "block/blk-cgroup.c:blkg_rwstat_recursive_sum",
        "block/blk-cgroup.c:blkg_prfill_rwstat_field",
        "block/blk-cgroup.c:blkg_prfill_rwstat",
        "block/blk-cgroup.c:blkg_destroy",
        "block/blk-cgroup.c:blkg_destroy",
        "net/ipv4/route.c:rt_cpu_seq_show",
        "net/ipv4/tcp.c:tcp_check_oom",
        "net/ipv4/proc.c:sockstat_seq_show",
        "net/ipv4/proc.c:sockstat_seq_show",
        "net/ipv6/route.c:rt6_stats_seq_show",
        "net/ipv6/route.c:ip6_dst_gc",
        "lib/flex_proportions.c:fprop_new_period"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584330688,
      "name": "__percpu_counter_sum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
s64 __percpu_counter_sum(struct percpu_counter * fbc)
```

```json
{
  "name": "__percpu_counter_sum",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584378400,
      "name": "__percpu_counter_sum",
      "external": true,
      "loc": "lib/percpu_counter.c:105",
      "file": "lib/percpu_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/shmem.c:shmem_statfs",
        "fs/quota/dquot.c:do_proc_dqstats",
        "fs/ext4/balloc.c:ext4_has_free_clusters",
        "fs/ext4/balloc.c:ext4_has_free_clusters",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/super.c:ext4_statfs",
        "fs/ext4/super.c:ext4_statfs",
        "fs/ext4/super.c:ext4_statfs",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/sysfs.c:ext4_attr_show",
        "block/blk-cgroup.c:blkg_rwstat_recursive_sum",
        "block/blk-cgroup.c:blkg_prfill_rwstat_field",
        "block/blk-cgroup.c:blkg_prfill_rwstat",
        "block/blk-cgroup.c:blkg_destroy",
        "block/blk-cgroup.c:blkg_destroy",
        "net/ipv4/route.c:rt_cpu_seq_show",
        "net/ipv4/tcp.c:tcp_check_oom",
        "net/ipv4/proc.c:sockstat_seq_show",
        "net/ipv4/proc.c:sockstat_seq_show",
        "net/ipv6/route.c:rt6_stats_seq_show",
        "net/ipv6/route.c:ip6_dst_gc",
        "lib/flex_proportions.c:fprop_new_period"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584378400,
      "name": "__percpu_counter_sum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
s64 __percpu_counter_sum(struct percpu_counter * fbc)
```

```json
{
  "name": "__percpu_counter_sum",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584484608,
      "name": "__percpu_counter_sum",
      "external": true,
      "loc": "lib/percpu_counter.c:105",
      "file": "lib/percpu_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/shmem.c:shmem_statfs",
        "fs/quota/dquot.c:do_proc_dqstats",
        "fs/ext4/balloc.c:ext4_has_free_clusters",
        "fs/ext4/balloc.c:ext4_has_free_clusters",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/super.c:ext4_statfs",
        "fs/ext4/super.c:ext4_statfs",
        "fs/ext4/super.c:ext4_statfs",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/sysfs.c:ext4_attr_show",
        "block/blk-cgroup.c:blkg_rwstat_recursive_sum",
        "block/blk-cgroup.c:blkg_prfill_rwstat_field",
        "block/blk-cgroup.c:blkg_prfill_rwstat",
        "block/blk-cgroup.c:blkg_destroy",
        "block/blk-cgroup.c:blkg_destroy",
        "net/ipv4/route.c:rt_cpu_seq_show",
        "net/ipv4/tcp.c:tcp_check_oom",
        "net/ipv4/proc.c:sockstat_seq_show",
        "net/ipv4/proc.c:sockstat_seq_show",
        "net/ipv6/route.c:rt6_stats_seq_show",
        "net/ipv6/route.c:ip6_dst_gc",
        "lib/flex_proportions.c:fprop_new_period"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584484608,
      "name": "__percpu_counter_sum",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
