# Function: <code>mmc_blk_part_switch_post</code>

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
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int mmc_blk_part_switch_post(struct mmc_card * card, unsigned int part_type)
```

```json
{
  "name": "mmc_blk_part_switch_post",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501427696,
      "name": "mmc_blk_part_switch_post",
      "external": false,
      "loc": "drivers/mmc/core/block.c:853",
      "file": "drivers/mmc/core/block.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/block.c:mmc_blk_remove",
        "drivers/mmc/core/block.c:mmc_blk_remove",
        "drivers/mmc/core/block.c:mmc_blk_mq_issue_rq",
        "drivers/mmc/core/block.c:mmc_blk_mq_issue_rq",
        "drivers/mmc/core/block.c:mmc_blk_mq_issue_rq",
        "drivers/mmc/core/block.c:__mmc_blk_ioctl_cmd",
        "drivers/mmc/core/block.c:__mmc_blk_ioctl_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501427696,
      "name": "mmc_blk_part_switch_post",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
int mmc_blk_part_switch_post(struct mmc_card * card, unsigned int part_type)
```

```json
{
  "name": "mmc_blk_part_switch_post",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233916648,
      "name": "mmc_blk_part_switch_post",
      "external": false,
      "loc": "drivers/mmc/core/block.c:853",
      "file": "drivers/mmc/core/block.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/block.c:mmc_blk_remove",
        "drivers/mmc/core/block.c:mmc_blk_remove",
        "drivers/mmc/core/block.c:mmc_blk_mq_issue_rq",
        "drivers/mmc/core/block.c:mmc_blk_mq_issue_rq",
        "drivers/mmc/core/block.c:mmc_blk_mq_issue_rq",
        "drivers/mmc/core/block.c:mmc_blk_reset",
        "drivers/mmc/core/block.c:mmc_blk_reset",
        "drivers/mmc/core/block.c:__mmc_blk_ioctl_cmd",
        "drivers/mmc/core/block.c:__mmc_blk_ioctl_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233916648,
      "name": "mmc_blk_part_switch_post",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int mmc_blk_part_switch_post(struct mmc_card * card, unsigned int part_type)
```

```json
{
  "name": "mmc_blk_part_switch_post",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278031748,
      "name": "mmc_blk_part_switch_post",
      "external": false,
      "loc": "drivers/mmc/core/block.c:853",
      "file": "drivers/mmc/core/block.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/block.c:mmc_blk_remove",
        "drivers/mmc/core/block.c:mmc_blk_remove",
        "drivers/mmc/core/block.c:mmc_blk_mq_issue_rq",
        "drivers/mmc/core/block.c:mmc_blk_mq_issue_rq",
        "drivers/mmc/core/block.c:mmc_blk_mq_issue_rq",
        "drivers/mmc/core/block.c:mmc_blk_reset",
        "drivers/mmc/core/block.c:mmc_blk_reset",
        "drivers/mmc/core/block.c:__mmc_blk_ioctl_cmd",
        "drivers/mmc/core/block.c:__mmc_blk_ioctl_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278031748,
      "name": "mmc_blk_part_switch_post",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
int mmc_blk_part_switch_post(struct mmc_card * card, unsigned int part_type)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int mmc_blk_part_switch_post(struct mmc_card * card, unsigned int part_type)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int mmc_blk_part_switch_post(struct mmc_card * card, unsigned int part_type)
```
</details>
</li>
</ul>
