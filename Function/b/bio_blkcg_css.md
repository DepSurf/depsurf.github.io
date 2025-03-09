# Function: <code>bio_blkcg_css</code>

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
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct cgroup_subsys_state * bio_blkcg_css(struct bio * bio)
```

```json
{
  "name": "bio_blkcg_css",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585808078,
      "name": "bio_blkcg_css",
      "external": true,
      "loc": "block/blk-cgroup.c:183",
      "file": "block/blk-cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:bio_clone_blkg_association",
        "block/blk-cgroup.c:bio_associate_blkg"
      ],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_add_trace_bio_remap",
        "kernel/trace/blktrace.c:blk_add_trace_split",
        "kernel/trace/blktrace.c:blk_add_trace_getrq",
        "kernel/trace/blktrace.c:blk_add_trace_bio_queue",
        "kernel/trace/blktrace.c:blk_add_trace_bio_frontmerge",
        "kernel/trace/blktrace.c:blk_add_trace_bio_backmerge",
        "kernel/trace/blktrace.c:blk_add_trace_bio_bounce",
        "kernel/trace/blktrace.c:blk_add_trace_rq_complete",
        "kernel/trace/blktrace.c:blk_add_trace_rq_requeue",
        "kernel/trace/blktrace.c:blk_add_trace_rq_merge",
        "kernel/trace/blktrace.c:blk_add_trace_rq_issue",
        "kernel/trace/blktrace.c:blk_add_trace_rq_insert",
        "drivers/block/loop.c:loop_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585796352,
      "name": "bio_blkcg_css",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
struct cgroup_subsys_state * bio_blkcg_css(struct bio * bio)
```

```json
{
  "name": "bio_blkcg_css",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586589726,
      "name": "bio_blkcg_css",
      "external": true,
      "loc": "block/blk-cgroup.c:215",
      "file": "block/blk-cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:bio_clone_blkg_association",
        "block/blk-cgroup.c:bio_associate_blkg"
      ],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_add_trace_bio_remap",
        "kernel/trace/blktrace.c:blk_add_trace_split",
        "kernel/trace/blktrace.c:blk_add_trace_getrq",
        "kernel/trace/blktrace.c:blk_add_trace_bio_queue",
        "kernel/trace/blktrace.c:blk_add_trace_bio_frontmerge",
        "kernel/trace/blktrace.c:blk_add_trace_bio_backmerge",
        "kernel/trace/blktrace.c:blk_add_trace_bio_complete",
        "kernel/trace/blktrace.c:blk_add_trace_bio_bounce",
        "kernel/trace/blktrace.c:blk_add_trace_rq_complete",
        "kernel/trace/blktrace.c:blk_add_trace_rq_requeue",
        "kernel/trace/blktrace.c:blk_add_trace_rq_merge",
        "kernel/trace/blktrace.c:blk_add_trace_rq_issue",
        "kernel/trace/blktrace.c:blk_add_trace_rq_insert",
        "drivers/block/loop.c:loop_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586577680,
      "name": "bio_blkcg_css",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
struct cgroup_subsys_state * bio_blkcg_css(struct bio * bio)
```

```json
{
  "name": "bio_blkcg_css",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586846958,
      "name": "bio_blkcg_css",
      "external": true,
      "loc": "block/blk-cgroup.c:278",
      "file": "block/blk-cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:bio_clone_blkg_association",
        "block/blk-cgroup.c:bio_associate_blkg"
      ],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_add_trace_bio_remap",
        "kernel/trace/blktrace.c:blk_add_trace_split",
        "kernel/trace/blktrace.c:blk_add_trace_getrq",
        "kernel/trace/blktrace.c:blk_add_trace_bio_queue",
        "kernel/trace/blktrace.c:blk_add_trace_bio_frontmerge",
        "kernel/trace/blktrace.c:blk_add_trace_bio_backmerge",
        "kernel/trace/blktrace.c:blk_add_trace_bio_complete",
        "kernel/trace/blktrace.c:blk_add_trace_bio_bounce",
        "kernel/trace/blktrace.c:blk_add_trace_rq_complete",
        "kernel/trace/blktrace.c:blk_add_trace_rq_requeue",
        "kernel/trace/blktrace.c:blk_add_trace_rq_merge",
        "kernel/trace/blktrace.c:blk_add_trace_rq_issue",
        "kernel/trace/blktrace.c:blk_add_trace_rq_insert",
        "drivers/block/loop.c:loop_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586835440,
      "name": "bio_blkcg_css",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct cgroup_subsys_state * bio_blkcg_css(struct bio * bio)
```

```json
{
  "name": "bio_blkcg_css",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587124270,
      "name": "bio_blkcg_css",
      "external": true,
      "loc": "block/blk-cgroup.c:278",
      "file": "block/blk-cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:bio_clone_blkg_association"
      ],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_add_trace_bio_remap",
        "kernel/trace/blktrace.c:blk_add_trace_split",
        "kernel/trace/blktrace.c:blk_add_trace_getrq",
        "kernel/trace/blktrace.c:blk_add_trace_bio_queue",
        "kernel/trace/blktrace.c:blk_add_trace_bio_frontmerge",
        "kernel/trace/blktrace.c:blk_add_trace_bio_backmerge",
        "kernel/trace/blktrace.c:blk_add_trace_bio_complete",
        "kernel/trace/blktrace.c:blk_add_trace_bio_bounce",
        "kernel/trace/blktrace.c:blk_add_trace_rq_complete",
        "kernel/trace/blktrace.c:blk_add_trace_rq_requeue",
        "kernel/trace/blktrace.c:blk_add_trace_rq_merge",
        "kernel/trace/blktrace.c:blk_add_trace_rq_issue",
        "kernel/trace/blktrace.c:blk_add_trace_rq_insert",
        "drivers/block/loop.c:loop_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587112656,
      "name": "bio_blkcg_css",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
struct cgroup_subsys_state * bio_blkcg_css(struct bio * bio)
```
</details>
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
