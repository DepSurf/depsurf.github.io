# Function: <code>rb_reserve_next_event</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct ring_buffer_event * rb_reserve_next_event(struct ring_buffer * buffer, struct ring_buffer_per_cpu * cpu_buffer, long unsigned int length)
```

```json
{
  "name": "rb_reserve_next_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580186720,
      "name": "rb_reserve_next_event",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:2742",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve",
        "kernel/trace/ring_buffer.c:ring_buffer_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580186720,
      "name": "rb_reserve_next_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1113
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
struct ring_buffer_event * rb_reserve_next_event(struct ring_buffer * buffer, struct ring_buffer_per_cpu * cpu_buffer, long unsigned int length)
```

```json
{
  "name": "rb_reserve_next_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580228352,
      "name": "rb_reserve_next_event",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:2737",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580228352,
      "name": "rb_reserve_next_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1137
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
  "name": "rb_reserve_next_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580264853,
      "name": "rb_reserve_next_event",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:2706",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve"
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
  "name": "rb_reserve_next_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580277203,
      "name": "rb_reserve_next_event",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:2708",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve"
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
  "name": "rb_reserve_next_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580331011,
      "name": "rb_reserve_next_event",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:2700",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve"
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
  "name": "rb_reserve_next_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580391800,
      "name": "rb_reserve_next_event",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:2830",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve"
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
  "name": "rb_reserve_next_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580455576,
      "name": "rb_reserve_next_event",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:2893",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve"
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
  "name": "rb_reserve_next_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580510342,
      "name": "rb_reserve_next_event",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:2870",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve"
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
  "name": "rb_reserve_next_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580557910,
      "name": "rb_reserve_next_event",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:2871",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve"
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
  "name": "rb_reserve_next_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580650426,
      "name": "rb_reserve_next_event",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:2940",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve"
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
  "name": "rb_reserve_next_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580640758,
      "name": "rb_reserve_next_event",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:3501",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve"
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
  "name": "rb_reserve_next_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580637462,
      "name": "rb_reserve_next_event",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:3588",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve"
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
  "name": "rb_reserve_next_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580809599,
      "name": "rb_reserve_next_event",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:3588",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve"
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
  "name": "rb_reserve_next_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581035724,
      "name": "rb_reserve_next_event",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:3626",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve"
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
  "name": "rb_reserve_next_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581343292,
      "name": "rb_reserve_next_event",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:3705",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve"
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
  "name": "rb_reserve_next_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581437612,
      "name": "rb_reserve_next_event",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:3708",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve"
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
  "name": "rb_reserve_next_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581547166,
      "name": "rb_reserve_next_event",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:3604",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "rb_reserve_next_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491845264,
      "name": "rb_reserve_next_event",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:2871",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve"
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
  "name": "rb_reserve_next_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225792812,
      "name": "rb_reserve_next_event",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:2871",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve"
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
  "name": "rb_reserve_next_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284915724,
      "name": "rb_reserve_next_event",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:2871",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve"
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
  "name": "rb_reserve_next_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272146796,
      "name": "rb_reserve_next_event",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:2871",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve"
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
  "name": "rb_reserve_next_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580526710,
      "name": "rb_reserve_next_event",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:2871",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve"
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
  "name": "rb_reserve_next_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580473590,
      "name": "rb_reserve_next_event",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:2871",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve"
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
  "name": "rb_reserve_next_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580517958,
      "name": "rb_reserve_next_event",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:2871",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve"
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
  "name": "rb_reserve_next_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580574365,
      "name": "rb_reserve_next_event",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:2871",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve"
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
struct ring_buffer_event * rb_reserve_next_event(struct ring_buffer * buffer, struct ring_buffer_per_cpu * cpu_buffer, long unsigned int length)
```
</details>
</li>
</ul>
