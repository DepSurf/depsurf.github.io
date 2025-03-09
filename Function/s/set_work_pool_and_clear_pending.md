# Function: <code>set_work_pool_and_clear_pending</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_work_pool_and_clear_pending",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579470288,
      "name": "set_work_pool_and_clear_pending",
      "external": false,
      "loc": "kernel/workqueue.c:641",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:cancel_delayed_work",
        "kernel/workqueue.c:process_one_work"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_work_pool_and_clear_pending",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579484046,
      "name": "set_work_pool_and_clear_pending",
      "external": false,
      "loc": "kernel/workqueue.c:632",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:cancel_delayed_work",
        "kernel/workqueue.c:process_one_work"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_work_pool_and_clear_pending",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579504594,
      "name": "set_work_pool_and_clear_pending",
      "external": false,
      "loc": "kernel/workqueue.c:634",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:__cancel_work",
        "kernel/workqueue.c:process_one_work"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_work_pool_and_clear_pending",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579493691,
      "name": "set_work_pool_and_clear_pending",
      "external": false,
      "loc": "kernel/workqueue.c:634",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:__cancel_work",
        "kernel/workqueue.c:process_one_work"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void set_work_pool_and_clear_pending(struct work_struct * work, int pool_id)
```

```json
{
  "name": "set_work_pool_and_clear_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579513392,
      "name": "set_work_pool_and_clear_pending",
      "external": false,
      "loc": "kernel/workqueue.c:636",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:__cancel_work",
        "kernel/workqueue.c:process_one_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579513392,
      "name": "set_work_pool_and_clear_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_work_pool_and_clear_pending",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579551187,
      "name": "set_work_pool_and_clear_pending",
      "external": false,
      "loc": "kernel/workqueue.c:634",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:cancel_delayed_work",
        "kernel/workqueue.c:process_one_work"
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
  "name": "set_work_pool_and_clear_pending",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579587763,
      "name": "set_work_pool_and_clear_pending",
      "external": false,
      "loc": "kernel/workqueue.c:634",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:cancel_delayed_work",
        "kernel/workqueue.c:process_one_work"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void set_work_pool_and_clear_pending(struct work_struct * work, int pool_id)
```

```json
{
  "name": "set_work_pool_and_clear_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579601216,
      "name": "set_work_pool_and_clear_pending",
      "external": false,
      "loc": "kernel/workqueue.c:637",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:cancel_delayed_work",
        "kernel/workqueue.c:process_one_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579601216,
      "name": "set_work_pool_and_clear_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_work_pool_and_clear_pending",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579637043,
      "name": "set_work_pool_and_clear_pending",
      "external": false,
      "loc": "kernel/workqueue.c:638",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:cancel_delayed_work",
        "kernel/workqueue.c:process_one_work"
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
  "name": "set_work_pool_and_clear_pending",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579675027,
      "name": "set_work_pool_and_clear_pending",
      "external": false,
      "loc": "kernel/workqueue.c:633",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:cancel_delayed_work",
        "kernel/workqueue.c:process_one_work"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_work_pool_and_clear_pending",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579654851,
      "name": "set_work_pool_and_clear_pending",
      "external": false,
      "loc": "kernel/workqueue.c:633",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:cancel_delayed_work",
        "kernel/workqueue.c:process_one_work"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_work_pool_and_clear_pending",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579661298,
      "name": "set_work_pool_and_clear_pending",
      "external": false,
      "loc": "kernel/workqueue.c:634",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:cancel_delayed_work",
        "kernel/workqueue.c:process_one_work"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_work_pool_and_clear_pending",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579738386,
      "name": "set_work_pool_and_clear_pending",
      "external": false,
      "loc": "kernel/workqueue.c:651",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:cancel_delayed_work",
        "kernel/workqueue.c:process_one_work"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_work_pool_and_clear_pending",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579834506,
      "name": "set_work_pool_and_clear_pending",
      "external": false,
      "loc": "kernel/workqueue.c:653",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:cancel_delayed_work",
        "kernel/workqueue.c:process_one_work"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_work_pool_and_clear_pending",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579977808,
      "name": "set_work_pool_and_clear_pending",
      "external": false,
      "loc": "kernel/workqueue.c:653",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:__cancel_work",
        "kernel/workqueue.c:process_one_work"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_work_pool_and_clear_pending",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580026848,
      "name": "set_work_pool_and_clear_pending",
      "external": false,
      "loc": "kernel/workqueue.c:695",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:__cancel_work",
        "kernel/workqueue.c:process_one_work"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_work_pool_and_clear_pending",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580062064,
      "name": "set_work_pool_and_clear_pending",
      "external": false,
      "loc": "kernel/workqueue.c:692",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:__cancel_work",
        "kernel/workqueue.c:process_one_work"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void set_work_pool_and_clear_pending(struct work_struct * work, int pool_id)
```

```json
{
  "name": "set_work_pool_and_clear_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490793128,
      "name": "set_work_pool_and_clear_pending",
      "external": false,
      "loc": "kernel/workqueue.c:638",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:cancel_delayed_work",
        "kernel/workqueue.c:process_one_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490793128,
      "name": "set_work_pool_and_clear_pending",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "set_work_pool_and_clear_pending",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224840248,
      "name": "set_work_pool_and_clear_pending",
      "external": false,
      "loc": "kernel/workqueue.c:638",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:cancel_delayed_work",
        "kernel/workqueue.c:process_one_work"
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
  "name": "set_work_pool_and_clear_pending",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283632264,
      "name": "set_work_pool_and_clear_pending",
      "external": false,
      "loc": "kernel/workqueue.c:638",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:cancel_delayed_work",
        "kernel/workqueue.c:process_one_work"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void set_work_pool_and_clear_pending(struct work_struct * work, int pool_id)
```

```json
{
  "name": "set_work_pool_and_clear_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271474056,
      "name": "set_work_pool_and_clear_pending",
      "external": false,
      "loc": "kernel/workqueue.c:638",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:cancel_delayed_work",
        "kernel/workqueue.c:process_one_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271474056,
      "name": "set_work_pool_and_clear_pending",
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_work_pool_and_clear_pending",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579613347,
      "name": "set_work_pool_and_clear_pending",
      "external": false,
      "loc": "kernel/workqueue.c:638",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:cancel_delayed_work",
        "kernel/workqueue.c:process_one_work"
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
  "name": "set_work_pool_and_clear_pending",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579542337,
      "name": "set_work_pool_and_clear_pending",
      "external": false,
      "loc": "kernel/workqueue.c:638",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:cancel_delayed_work",
        "kernel/workqueue.c:process_one_work"
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
  "name": "set_work_pool_and_clear_pending",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579610627,
      "name": "set_work_pool_and_clear_pending",
      "external": false,
      "loc": "kernel/workqueue.c:638",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:cancel_delayed_work",
        "kernel/workqueue.c:process_one_work"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_work_pool_and_clear_pending",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579648707,
      "name": "set_work_pool_and_clear_pending",
      "external": false,
      "loc": "kernel/workqueue.c:638",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:cancel_delayed_work",
        "kernel/workqueue.c:process_one_work"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void set_work_pool_and_clear_pending(struct work_struct * work, int pool_id)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
void set_work_pool_and_clear_pending(struct work_struct * work, int pool_id)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void set_work_pool_and_clear_pending(struct work_struct * work, int pool_id)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➖</summary>

```c
void set_work_pool_and_clear_pending(struct work_struct * work, int pool_id)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
void set_work_pool_and_clear_pending(struct work_struct * work, int pool_id)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
void set_work_pool_and_clear_pending(struct work_struct * work, int pool_id)
```
</details>
</li>
</ul>
