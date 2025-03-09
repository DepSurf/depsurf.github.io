# Function: <code>hctx_unlock</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hctx_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583634436,
      "name": "hctx_unlock",
      "external": false,
      "loc": "block/blk-mq.c:588",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_request_issue_directly",
        "block/blk-mq.c:blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_run_hw_queue",
        "block/blk-mq.c:__blk_mq_run_hw_queue"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hctx_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583737686,
      "name": "hctx_unlock",
      "external": false,
      "loc": "block/blk-mq.c:623",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_run_hw_queue",
        "block/blk-mq.c:__blk_mq_run_hw_queue"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hctx_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583928075,
      "name": "hctx_unlock",
      "external": false,
      "loc": "block/blk-mq.c:618",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_request_issue_directly",
        "block/blk-mq.c:blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_run_hw_queue",
        "block/blk-mq.c:__blk_mq_run_hw_queue"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hctx_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584031435,
      "name": "hctx_unlock",
      "external": false,
      "loc": "block/blk-mq.c:629",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_request_issue_directly",
        "block/blk-mq.c:blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_run_hw_queue",
        "block/blk-mq.c:__blk_mq_run_hw_queue"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hctx_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584426544,
      "name": "hctx_unlock",
      "external": false,
      "loc": "block/blk-mq.c:643",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_try_issue_list_directly",
        "block/blk-mq.c:blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_run_hw_queue",
        "block/blk-mq.c:__blk_mq_run_hw_queue"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void hctx_unlock(struct blk_mq_hw_ctx * hctx, int srcu_idx)
```

```json
{
  "name": "hctx_unlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584525248,
      "name": "hctx_unlock",
      "external": false,
      "loc": "block/blk-mq.c:710",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_try_issue_list_directly",
        "block/blk-mq.c:blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_run_hw_queue",
        "block/blk-mq.c:blk_mq_run_hw_queue",
        "block/blk-mq.c:__blk_mq_run_hw_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584525248,
      "name": "hctx_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
void hctx_unlock(struct blk_mq_hw_ctx * hctx, int srcu_idx)
```

```json
{
  "name": "hctx_unlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584557856,
      "name": "hctx_unlock",
      "external": false,
      "loc": "block/blk-mq.c:684",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_try_issue_list_directly",
        "block/blk-mq.c:blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_run_hw_queue",
        "block/blk-mq.c:blk_mq_run_hw_queue",
        "block/blk-mq.c:__blk_mq_run_hw_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584557856,
      "name": "hctx_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hctx_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584986196,
      "name": "hctx_unlock",
      "external": false,
      "loc": "block/blk-mq.c:691",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_try_issue_list_directly",
        "block/blk-mq.c:blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_run_hw_queue",
        "block/blk-mq.c:__blk_mq_run_hw_queue"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "hctx_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336495864588,
      "name": "hctx_unlock",
      "external": false,
      "loc": "block/blk-mq.c:629",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_request_issue_directly",
        "block/blk-mq.c:blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_run_hw_queue",
        "block/blk-mq.c:__blk_mq_run_hw_queue"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "hctx_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3229211640,
      "name": "hctx_unlock",
      "external": false,
      "loc": "block/blk-mq.c:629",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_request_issue_directly",
        "block/blk-mq.c:blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_run_hw_queue",
        "block/blk-mq.c:__blk_mq_run_hw_queue"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "hctx_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055290063316,
      "name": "hctx_unlock",
      "external": false,
      "loc": "block/blk-mq.c:629",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_request_issue_directly",
        "block/blk-mq.c:blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_run_hw_queue",
        "block/blk-mq.c:__blk_mq_run_hw_queue"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "hctx_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274990416,
      "name": "hctx_unlock",
      "external": false,
      "loc": "block/blk-mq.c:629",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_request_issue_directly",
        "block/blk-mq.c:blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_run_hw_queue",
        "block/blk-mq.c:__blk_mq_run_hw_queue"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hctx_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584000171,
      "name": "hctx_unlock",
      "external": false,
      "loc": "block/blk-mq.c:629",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_request_issue_directly",
        "block/blk-mq.c:blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_run_hw_queue",
        "block/blk-mq.c:__blk_mq_run_hw_queue"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hctx_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583935995,
      "name": "hctx_unlock",
      "external": false,
      "loc": "block/blk-mq.c:629",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_request_issue_directly",
        "block/blk-mq.c:blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_run_hw_queue",
        "block/blk-mq.c:__blk_mq_run_hw_queue"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hctx_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583983931,
      "name": "hctx_unlock",
      "external": false,
      "loc": "block/blk-mq.c:629",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_request_issue_directly",
        "block/blk-mq.c:blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_run_hw_queue",
        "block/blk-mq.c:__blk_mq_run_hw_queue"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void hctx_unlock(struct blk_mq_hw_ctx * hctx, int srcu_idx)
```

```json
{
  "name": "hctx_unlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584072112,
      "name": "hctx_unlock",
      "external": false,
      "loc": "block/blk-mq.c:629",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_request_issue_directly",
        "block/blk-mq.c:blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_run_hw_queue",
        "block/blk-mq.c:blk_mq_run_hw_queue",
        "block/blk-mq.c:__blk_mq_run_hw_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584072112,
      "name": "hctx_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void hctx_unlock(struct blk_mq_hw_ctx * hctx, int srcu_idx)
```
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
void hctx_unlock(struct blk_mq_hw_ctx * hctx, int srcu_idx)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ➕</summary>

```c
void hctx_unlock(struct blk_mq_hw_ctx * hctx, int srcu_idx)
```
</details>
</li>
</ul>
