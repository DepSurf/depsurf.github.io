# Function: <code>blk_stat_init</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_stat_init(struct blk_rq_stat * stat)
```

```json
{
  "name": "blk_stat_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583198500,
      "name": "blk_stat_init",
      "external": true,
      "loc": "block/blk-stat.c:180",
      "file": "block/blk-stat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-stat.c:blk_stat_clear",
        "block/blk-stat.c:blk_stat_clear",
        "block/blk-stat.c:blk_stat_clear",
        "block/blk-stat.c:blk_stat_clear",
        "block/blk-stat.c:blk_queue_stat_get",
        "block/blk-stat.c:blk_queue_stat_get"
      ],
      "caller_func": [
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-mq-sysfs.c:blk_mq_hw_sysfs_stat_show",
        "block/blk-mq-sysfs.c:blk_mq_hw_sysfs_stat_show",
        "block/blk-mq-sysfs.c:blk_mq_hw_sysfs_stat_store",
        "block/blk-mq-sysfs.c:blk_mq_hw_sysfs_stat_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583198016,
      "name": "blk_stat_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blk_stat_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583253274,
      "name": "blk_stat_init",
      "external": false,
      "loc": "block/blk-stat.c:22",
      "file": "block/blk-stat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-stat.c:blk_stat_add_callback",
        "block/blk-stat.c:blk_stat_timer_fn",
        "block/blk-stat.c:blk_stat_timer_fn"
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
  "name": "blk_stat_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583432624,
      "name": "blk_stat_init",
      "external": false,
      "loc": "block/blk-stat.c:20",
      "file": "block/blk-stat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-stat.c:blk_stat_add_callback",
        "block/blk-stat.c:blk_stat_timer_fn",
        "block/blk-stat.c:blk_stat_timer_fn"
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
  "name": "blk_stat_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583643854,
      "name": "blk_stat_init",
      "external": false,
      "loc": "block/blk-stat.c:20",
      "file": "block/blk-stat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-stat.c:blk_stat_add_callback",
        "block/blk-stat.c:blk_stat_timer_fn",
        "block/blk-stat.c:blk_stat_timer_fn"
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
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
void blk_stat_init(struct blk_rq_stat * stat)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
void blk_stat_init(struct blk_rq_stat * stat)
```
</details>
</li>
</ul>
