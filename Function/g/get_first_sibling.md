# Function: <code>get_first_sibling</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_first_sibling",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582811647,
      "name": "get_first_sibling",
      "external": false,
      "loc": "block/blk-mq-cpumap.c:23",
      "file": "block/blk-mq-cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-cpumap.c:blk_mq_update_queue_map",
        "block/blk-mq-cpumap.c:blk_mq_update_queue_map"
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
  "name": "get_first_sibling",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579799131,
      "name": "get_first_sibling",
      "external": false,
      "loc": "kernel/irq/affinity.c:7",
      "file": "kernel/irq/affinity.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:irq_create_affinity_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583090783,
      "name": "get_first_sibling",
      "external": false,
      "loc": "block/blk-mq-cpumap.c:23",
      "file": "block/blk-mq-cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-cpumap.c:blk_mq_update_queue_map",
        "block/blk-mq-cpumap.c:blk_mq_update_queue_map"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int get_first_sibling(unsigned int cpu)
```

```json
{
  "name": "get_first_sibling",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583202112,
      "name": "get_first_sibling",
      "external": false,
      "loc": "block/blk-mq-cpumap.c:23",
      "file": "block/blk-mq-cpumap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-cpumap.c:blk_mq_map_queues",
        "block/blk-mq-cpumap.c:blk_mq_map_queues"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583202112,
      "name": "get_first_sibling",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
  "name": "get_first_sibling",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583256641,
      "name": "get_first_sibling",
      "external": false,
      "loc": "block/blk-mq-cpumap.c:27",
      "file": "block/blk-mq-cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-cpumap.c:blk_mq_map_queues"
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
  "name": "get_first_sibling",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583435857,
      "name": "get_first_sibling",
      "external": false,
      "loc": "block/blk-mq-cpumap.c:27",
      "file": "block/blk-mq-cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-cpumap.c:blk_mq_map_queues"
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
  "name": "get_first_sibling",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583647092,
      "name": "get_first_sibling",
      "external": false,
      "loc": "block/blk-mq-cpumap.c:22",
      "file": "block/blk-mq-cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-cpumap.c:blk_mq_map_queues"
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
  "name": "get_first_sibling",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583753892,
      "name": "get_first_sibling",
      "external": false,
      "loc": "block/blk-mq-cpumap.c:23",
      "file": "block/blk-mq-cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-cpumap.c:blk_mq_map_queues"
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
  "name": "get_first_sibling",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583942994,
      "name": "get_first_sibling",
      "external": false,
      "loc": "block/blk-mq-cpumap.c:24",
      "file": "block/blk-mq-cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-cpumap.c:blk_mq_map_queues"
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
  "name": "get_first_sibling",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584046574,
      "name": "get_first_sibling",
      "external": false,
      "loc": "block/blk-mq-cpumap.c:24",
      "file": "block/blk-mq-cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-cpumap.c:blk_mq_map_queues"
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
  "name": "get_first_sibling",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584442382,
      "name": "get_first_sibling",
      "external": false,
      "loc": "block/blk-mq-cpumap.c:24",
      "file": "block/blk-mq-cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-cpumap.c:blk_mq_map_queues"
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
  "name": "get_first_sibling",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584559198,
      "name": "get_first_sibling",
      "external": false,
      "loc": "block/blk-mq-cpumap.c:24",
      "file": "block/blk-mq-cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-cpumap.c:blk_mq_map_queues"
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
  "name": "get_first_sibling",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584592019,
      "name": "get_first_sibling",
      "external": false,
      "loc": "block/blk-mq-cpumap.c:24",
      "file": "block/blk-mq-cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-cpumap.c:blk_mq_map_queues"
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
  "name": "get_first_sibling",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585006492,
      "name": "get_first_sibling",
      "external": false,
      "loc": "block/blk-mq-cpumap.c:24",
      "file": "block/blk-mq-cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-cpumap.c:blk_mq_map_queues"
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
  "name": "get_first_sibling",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585721802,
      "name": "get_first_sibling",
      "external": false,
      "loc": "block/blk-mq-cpumap.c:24",
      "file": "block/blk-mq-cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-cpumap.c:blk_mq_map_queues"
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
  "name": "get_first_sibling",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586502776,
      "name": "get_first_sibling",
      "external": false,
      "loc": "block/blk-mq-cpumap.c:24",
      "file": "block/blk-mq-cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-cpumap.c:blk_mq_map_queues"
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
  "name": "get_first_sibling",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336495882628,
      "name": "get_first_sibling",
      "external": false,
      "loc": "block/blk-mq-cpumap.c:24",
      "file": "block/blk-mq-cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-cpumap.c:blk_mq_map_queues"
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
  "name": "get_first_sibling",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3229227648,
      "name": "get_first_sibling",
      "external": false,
      "loc": "block/blk-mq-cpumap.c:24",
      "file": "block/blk-mq-cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-cpumap.c:blk_mq_map_queues"
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
  "name": "get_first_sibling",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055290086016,
      "name": "get_first_sibling",
      "external": false,
      "loc": "block/blk-mq-cpumap.c:24",
      "file": "block/blk-mq-cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-cpumap.c:blk_mq_map_queues"
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
  "name": "get_first_sibling",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936275004524,
      "name": "get_first_sibling",
      "external": false,
      "loc": "block/blk-mq-cpumap.c:24",
      "file": "block/blk-mq-cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-cpumap.c:blk_mq_map_queues"
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
  "name": "get_first_sibling",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584015310,
      "name": "get_first_sibling",
      "external": false,
      "loc": "block/blk-mq-cpumap.c:24",
      "file": "block/blk-mq-cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-cpumap.c:blk_mq_map_queues"
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
  "name": "get_first_sibling",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583951134,
      "name": "get_first_sibling",
      "external": false,
      "loc": "block/blk-mq-cpumap.c:24",
      "file": "block/blk-mq-cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-cpumap.c:blk_mq_map_queues"
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
  "name": "get_first_sibling",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583999070,
      "name": "get_first_sibling",
      "external": false,
      "loc": "block/blk-mq-cpumap.c:24",
      "file": "block/blk-mq-cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-cpumap.c:blk_mq_map_queues"
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
  "name": "get_first_sibling",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584101422,
      "name": "get_first_sibling",
      "external": false,
      "loc": "block/blk-mq-cpumap.c:24",
      "file": "block/blk-mq-cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-cpumap.c:blk_mq_map_queues"
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
int get_first_sibling(unsigned int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
int get_first_sibling(unsigned int cpu)
```
</details>
</li>
</ul>
