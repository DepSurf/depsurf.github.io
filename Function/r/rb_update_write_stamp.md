# Function: <code>rb_update_write_stamp</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void rb_update_write_stamp(struct ring_buffer_per_cpu * cpu_buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "rb_update_write_stamp",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580184144,
      "name": "rb_update_write_stamp",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:2510",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_discard_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580184144,
      "name": "rb_update_write_stamp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void rb_update_write_stamp(struct ring_buffer_per_cpu * cpu_buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "rb_update_write_stamp",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580219024,
      "name": "rb_update_write_stamp",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:2504",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_discard_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580219024,
      "name": "rb_update_write_stamp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rb_update_write_stamp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580270690,
      "name": "rb_update_write_stamp",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:2473",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_discard_commit",
        "kernel/trace/ring_buffer.c:rb_commit"
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
  "name": "rb_update_write_stamp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580283178,
      "name": "rb_update_write_stamp",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:2475",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_discard_commit",
        "kernel/trace/ring_buffer.c:rb_commit"
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
  "name": "rb_update_write_stamp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580336623,
      "name": "rb_update_write_stamp",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:2471",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_discard_commit",
        "kernel/trace/ring_buffer.c:rb_commit"
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
  "name": "rb_update_write_stamp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580398852,
      "name": "rb_update_write_stamp",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:2549",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_discard_commit",
        "kernel/trace/ring_buffer.c:rb_commit"
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
  "name": "rb_update_write_stamp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580451336,
      "name": "rb_update_write_stamp",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:2597",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_discard_commit",
        "kernel/trace/ring_buffer.c:rb_commit"
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
  "name": "rb_update_write_stamp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580505698,
      "name": "rb_update_write_stamp",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:2574",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_discard_commit",
        "kernel/trace/ring_buffer.c:rb_commit"
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
  "name": "rb_update_write_stamp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580552543,
      "name": "rb_update_write_stamp",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:2575",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_discard_commit",
        "kernel/trace/ring_buffer.c:rb_commit"
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
  "name": "rb_update_write_stamp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580641470,
      "name": "rb_update_write_stamp",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:2644",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_discard_commit",
        "kernel/trace/ring_buffer.c:rb_commit"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "rb_update_write_stamp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491838556,
      "name": "rb_update_write_stamp",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:2575",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_discard_commit",
        "kernel/trace/ring_buffer.c:rb_commit"
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
  "name": "rb_update_write_stamp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225785864,
      "name": "rb_update_write_stamp",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:2575",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_discard_commit",
        "kernel/trace/ring_buffer.c:rb_commit"
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
  "name": "rb_update_write_stamp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284907752,
      "name": "rb_update_write_stamp",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:2575",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_discard_commit",
        "kernel/trace/ring_buffer.c:rb_commit"
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
  "name": "rb_update_write_stamp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272143630,
      "name": "rb_update_write_stamp",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:2575",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_discard_commit",
        "kernel/trace/ring_buffer.c:rb_commit"
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
  "name": "rb_update_write_stamp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580521343,
      "name": "rb_update_write_stamp",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:2575",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_discard_commit",
        "kernel/trace/ring_buffer.c:rb_commit"
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
  "name": "rb_update_write_stamp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580469775,
      "name": "rb_update_write_stamp",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:2575",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_discard_commit",
        "kernel/trace/ring_buffer.c:rb_commit"
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
  "name": "rb_update_write_stamp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580512591,
      "name": "rb_update_write_stamp",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:2575",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_discard_commit",
        "kernel/trace/ring_buffer.c:rb_commit"
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
  "name": "rb_update_write_stamp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580568927,
      "name": "rb_update_write_stamp",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:2575",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_discard_commit",
        "kernel/trace/ring_buffer.c:rb_commit"
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➖</summary>

```c
void rb_update_write_stamp(struct ring_buffer_per_cpu * cpu_buffer, struct ring_buffer_event * event)
```
</details>
</li>
</ul>
