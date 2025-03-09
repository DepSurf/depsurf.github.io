# Function: <code>__blk_run_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __blk_run_queue(struct request_queue * q)
```

```json
{
  "name": "__blk_run_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582733344,
      "name": "__blk_run_queue",
      "external": true,
      "loc": "block/blk-core.c:337",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:__elv_add_request",
        "block/blk-core.c:blk_run_queue",
        "block/blk-core.c:blk_start_queue",
        "block/blk-core.c:queue_unplugged",
        "block/blk-core.c:__blk_drain_queue",
        "block/blk-core.c:blk_delay_work",
        "block/blk-core.c:blk_post_runtime_resume",
        "block/blk-core.c:blk_queue_bio",
        "block/blk-exec.c:blk_execute_rq_nowait",
        "block/cfq-iosched.c:cfq_kick_queue",
        "block/cfq-iosched.c:cfq_insert_request",
        "block/cfq-iosched.c:cfq_insert_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582733344,
      "name": "__blk_run_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void __blk_run_queue(struct request_queue * q)
```

```json
{
  "name": "__blk_run_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583015584,
      "name": "__blk_run_queue",
      "external": true,
      "loc": "block/blk-core.c:337",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:__elv_add_request",
        "block/blk-core.c:blk_post_runtime_resume",
        "block/blk-core.c:queue_unplugged",
        "block/blk-core.c:blk_queue_bio",
        "block/blk-core.c:__blk_drain_queue",
        "block/blk-core.c:blk_run_queue",
        "block/blk-core.c:blk_start_queue",
        "block/blk-core.c:blk_delay_work",
        "block/blk-exec.c:blk_execute_rq_nowait",
        "block/cfq-iosched.c:cfq_kick_queue",
        "block/cfq-iosched.c:cfq_insert_request",
        "block/cfq-iosched.c:cfq_insert_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583015584,
      "name": "__blk_run_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void __blk_run_queue(struct request_queue * q)
```

```json
{
  "name": "__blk_run_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583120416,
      "name": "__blk_run_queue",
      "external": true,
      "loc": "block/blk-core.c:338",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:__elv_add_request",
        "block/blk-core.c:blk_post_runtime_resume",
        "block/blk-core.c:queue_unplugged",
        "block/blk-core.c:blk_queue_bio",
        "block/blk-core.c:__blk_drain_queue",
        "block/blk-core.c:blk_run_queue",
        "block/blk-core.c:blk_start_queue",
        "block/blk-core.c:blk_delay_work",
        "block/blk-exec.c:blk_execute_rq_nowait",
        "block/cfq-iosched.c:cfq_kick_queue",
        "block/cfq-iosched.c:cfq_insert_request",
        "block/cfq-iosched.c:cfq_insert_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583120416,
      "name": "__blk_run_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void __blk_run_queue(struct request_queue * q)
```

```json
{
  "name": "__blk_run_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583179664,
      "name": "__blk_run_queue",
      "external": true,
      "loc": "block/blk-core.c:388",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:__elv_add_request",
        "block/blk-core.c:queue_unplugged",
        "block/blk-core.c:blk_queue_bio",
        "block/blk-core.c:__blk_drain_queue",
        "block/blk-core.c:blk_run_queue",
        "block/blk-core.c:blk_start_queue",
        "block/blk-core.c:blk_delay_work",
        "block/blk-exec.c:blk_execute_rq_nowait",
        "block/cfq-iosched.c:cfq_kick_queue",
        "block/cfq-iosched.c:cfq_insert_request",
        "block/cfq-iosched.c:cfq_insert_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583179664,
      "name": "__blk_run_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void __blk_run_queue(struct request_queue * q)
```

```json
{
  "name": "__blk_run_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583356016,
      "name": "__blk_run_queue",
      "external": true,
      "loc": "block/blk-core.c:421",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:__elv_add_request",
        "block/blk-core.c:queue_unplugged",
        "block/blk-core.c:blk_queue_bio",
        "block/blk-core.c:__blk_drain_queue",
        "block/blk-core.c:blk_run_queue",
        "block/blk-core.c:blk_start_queue",
        "block/blk-core.c:blk_delay_work",
        "block/blk-exec.c:blk_execute_rq_nowait",
        "block/cfq-iosched.c:cfq_kick_queue",
        "block/cfq-iosched.c:cfq_insert_request",
        "block/cfq-iosched.c:cfq_insert_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583356016,
      "name": "__blk_run_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
void __blk_run_queue(struct request_queue * q)
```

```json
{
  "name": "__blk_run_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583565600,
      "name": "__blk_run_queue",
      "external": true,
      "loc": "block/blk-core.c:482",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:__elv_add_request",
        "block/blk-core.c:queue_unplugged",
        "block/blk-core.c:blk_queue_bio",
        "block/blk-core.c:blk_run_queue",
        "block/blk-core.c:blk_start_queue",
        "block/blk-core.c:blk_delay_work",
        "block/blk-exec.c:blk_execute_rq_nowait",
        "block/cfq-iosched.c:cfq_kick_queue",
        "block/cfq-iosched.c:cfq_insert_request",
        "block/cfq-iosched.c:cfq_insert_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583565600,
      "name": "__blk_run_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
void __blk_run_queue(struct request_queue * q)
```
</details>
</li>
</ul>
