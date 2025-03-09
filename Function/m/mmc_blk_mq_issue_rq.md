# Function: <code>mmc_blk_mq_issue_rq</code>

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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
enum mmc_issued mmc_blk_mq_issue_rq(struct mmc_queue * mq, struct request * req)
```

```json
{
  "name": "mmc_blk_mq_issue_rq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501440832,
      "name": "mmc_blk_mq_issue_rq",
      "external": true,
      "loc": "drivers/mmc/core/block.c:2178",
      "file": "drivers/mmc/core/block.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/queue.c:mmc_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501440832,
      "name": "mmc_blk_mq_issue_rq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1912
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
enum mmc_issued mmc_blk_mq_issue_rq(struct mmc_queue * mq, struct request * req)
```

```json
{
  "name": "mmc_blk_mq_issue_rq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233926584,
      "name": "mmc_blk_mq_issue_rq",
      "external": true,
      "loc": "drivers/mmc/core/block.c:2178",
      "file": "drivers/mmc/core/block.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/queue.c:mmc_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233926584,
      "name": "mmc_blk_mq_issue_rq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2264
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
enum mmc_issued mmc_blk_mq_issue_rq(struct mmc_queue * mq, struct request * req)
```

```json
{
  "name": "mmc_blk_mq_issue_rq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278040104,
      "name": "mmc_blk_mq_issue_rq",
      "external": true,
      "loc": "drivers/mmc/core/block.c:2178",
      "file": "drivers/mmc/core/block.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/queue.c:mmc_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278040104,
      "name": "mmc_blk_mq_issue_rq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1506
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
enum mmc_issued mmc_blk_mq_issue_rq(struct mmc_queue * mq, struct request * req)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
enum mmc_issued mmc_blk_mq_issue_rq(struct mmc_queue * mq, struct request * req)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
enum mmc_issued mmc_blk_mq_issue_rq(struct mmc_queue * mq, struct request * req)
```
</details>
</li>
</ul>
