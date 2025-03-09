# Function: <code>part_round_stats</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void part_round_stats(int cpu, struct hd_struct * part)
```

```json
{
  "name": "part_round_stats",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582733472,
      "name": "part_round_stats",
      "external": true,
      "loc": "block/blk-core.c:1440",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:generic_start_io_acct",
        "block/bio.c:generic_end_io_acct",
        "block/blk-core.c:blk_account_io_start",
        "block/blk-merge.c:attempt_merge",
        "block/genhd.c:diskstats_show",
        "block/partition-generic.c:part_stat_show",
        "drivers/nvdimm/core.c:__nd_iostat_start",
        "drivers/nvdimm/core.c:nd_iostat_end",
        "drivers/md/dm.c:__split_and_process_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582733472,
      "name": "part_round_stats",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void part_round_stats(int cpu, struct hd_struct * part)
```

```json
{
  "name": "part_round_stats",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583015712,
      "name": "part_round_stats",
      "external": true,
      "loc": "block/blk-core.c:1399",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:generic_end_io_acct",
        "block/bio.c:generic_start_io_acct",
        "block/blk-core.c:blk_account_io_start",
        "block/genhd.c:diskstats_show",
        "block/partition-generic.c:part_stat_show",
        "drivers/nvdimm/core.c:nd_iostat_end",
        "drivers/nvdimm/core.c:__nd_iostat_start",
        "drivers/md/dm.c:__split_and_process_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583015712,
      "name": "part_round_stats",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void part_round_stats(int cpu, struct hd_struct * part)
```

```json
{
  "name": "part_round_stats",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583120544,
      "name": "part_round_stats",
      "external": true,
      "loc": "block/blk-core.c:1401",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:generic_end_io_acct",
        "block/bio.c:generic_start_io_acct",
        "block/blk-core.c:blk_account_io_start",
        "block/genhd.c:diskstats_show",
        "block/partition-generic.c:part_stat_show",
        "drivers/md/dm.c:__split_and_process_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583120544,
      "name": "part_round_stats",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void part_round_stats(int cpu, struct hd_struct * part)
```

```json
{
  "name": "part_round_stats",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583176576,
      "name": "part_round_stats",
      "external": true,
      "loc": "block/blk-core.c:1505",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:generic_end_io_acct",
        "block/bio.c:generic_start_io_acct",
        "block/blk-core.c:blk_account_io_start",
        "block/blk-merge.c:attempt_merge",
        "block/genhd.c:diskstats_show",
        "block/partition-generic.c:part_stat_show",
        "drivers/md/dm.c:__split_and_process_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583176576,
      "name": "part_round_stats",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void part_round_stats(struct request_queue * q, int cpu, struct hd_struct * part)
```

```json
{
  "name": "part_round_stats",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583353296,
      "name": "part_round_stats",
      "external": true,
      "loc": "block/blk-core.c:1606",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:generic_end_io_acct",
        "block/bio.c:generic_start_io_acct",
        "block/blk-core.c:blk_account_io_start",
        "block/blk-merge.c:attempt_merge",
        "block/genhd.c:diskstats_show",
        "block/partition-generic.c:part_stat_show",
        "drivers/md/dm.c:__split_and_process_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583353296,
      "name": "part_round_stats",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 368
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
void part_round_stats(struct request_queue * q, int cpu, struct hd_struct * part)
```

```json
{
  "name": "part_round_stats",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583562976,
      "name": "part_round_stats",
      "external": true,
      "loc": "block/blk-core.c:1702",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:generic_end_io_acct",
        "block/bio.c:generic_start_io_acct",
        "block/blk-core.c:blk_account_io_start",
        "block/genhd.c:diskstats_show",
        "block/partition-generic.c:part_stat_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583562976,
      "name": "part_round_stats",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 371
    }
  ]
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct request_queue * q</code>
</li>
<li>
<b>Param reordered. </b>
<code>cpu, part</code> ➡️ <code>q, cpu, part</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
void part_round_stats(struct request_queue * q, int cpu, struct hd_struct * part)
```
</details>
</li>
</ul>
