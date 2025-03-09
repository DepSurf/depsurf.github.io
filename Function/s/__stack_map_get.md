# Function: <code>__stack_map_get</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int __stack_map_get(struct bpf_map * map, void * value, bool delete)
```

```json
{
  "name": "__stack_map_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580781312,
      "name": "__stack_map_get",
      "external": false,
      "loc": "kernel/bpf/queue_stack_maps.c:144",
      "file": "kernel/bpf/queue_stack_maps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/queue_stack_maps.c:stack_map_pop_elem",
        "kernel/bpf/queue_stack_maps.c:stack_map_peek_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580781312,
      "name": "__stack_map_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int __stack_map_get(struct bpf_map * map, void * value, bool delete)
```

```json
{
  "name": "__stack_map_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580866112,
      "name": "__stack_map_get",
      "external": false,
      "loc": "kernel/bpf/queue_stack_maps.c:143",
      "file": "kernel/bpf/queue_stack_maps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/queue_stack_maps.c:stack_map_pop_elem",
        "kernel/bpf/queue_stack_maps.c:stack_map_peek_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580866112,
      "name": "__stack_map_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int __stack_map_get(struct bpf_map * map, void * value, bool delete)
```

```json
{
  "name": "__stack_map_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580917072,
      "name": "__stack_map_get",
      "external": false,
      "loc": "kernel/bpf/queue_stack_maps.c:143",
      "file": "kernel/bpf/queue_stack_maps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/queue_stack_maps.c:stack_map_pop_elem",
        "kernel/bpf/queue_stack_maps.c:stack_map_peek_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580917072,
      "name": "__stack_map_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int __stack_map_get(struct bpf_map * map, void * value, bool delete)
```

```json
{
  "name": "__stack_map_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581064112,
      "name": "__stack_map_get",
      "external": false,
      "loc": "kernel/bpf/queue_stack_maps.c:143",
      "file": "kernel/bpf/queue_stack_maps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/queue_stack_maps.c:stack_map_pop_elem",
        "kernel/bpf/queue_stack_maps.c:stack_map_peek_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581064112,
      "name": "__stack_map_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int __stack_map_get(struct bpf_map * map, void * value, bool delete)
```

```json
{
  "name": "__stack_map_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581075936,
      "name": "__stack_map_get",
      "external": false,
      "loc": "kernel/bpf/queue_stack_maps.c:128",
      "file": "kernel/bpf/queue_stack_maps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/queue_stack_maps.c:stack_map_pop_elem",
        "kernel/bpf/queue_stack_maps.c:stack_map_peek_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581075936,
      "name": "__stack_map_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
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
int __stack_map_get(struct bpf_map * map, void * value, bool delete)
```

```json
{
  "name": "__stack_map_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581090928,
      "name": "__stack_map_get",
      "external": false,
      "loc": "kernel/bpf/queue_stack_maps.c:128",
      "file": "kernel/bpf/queue_stack_maps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/queue_stack_maps.c:stack_map_pop_elem",
        "kernel/bpf/queue_stack_maps.c:stack_map_peek_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581090928,
      "name": "__stack_map_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int __stack_map_get(struct bpf_map * map, void * value, bool delete)
```

```json
{
  "name": "__stack_map_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581320112,
      "name": "__stack_map_get",
      "external": false,
      "loc": "kernel/bpf/queue_stack_maps.c:128",
      "file": "kernel/bpf/queue_stack_maps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/queue_stack_maps.c:stack_map_pop_elem",
        "kernel/bpf/queue_stack_maps.c:stack_map_peek_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581320112,
      "name": "__stack_map_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int __stack_map_get(struct bpf_map * map, void * value, bool delete)
```

```json
{
  "name": "__stack_map_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581622368,
      "name": "__stack_map_get",
      "external": false,
      "loc": "kernel/bpf/queue_stack_maps.c:129",
      "file": "kernel/bpf/queue_stack_maps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/queue_stack_maps.c:stack_map_pop_elem",
        "kernel/bpf/queue_stack_maps.c:stack_map_peek_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581622368,
      "name": "__stack_map_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int __stack_map_get(struct bpf_map * map, void * value, bool delete)
```

```json
{
  "name": "__stack_map_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582008032,
      "name": "__stack_map_get",
      "external": false,
      "loc": "kernel/bpf/queue_stack_maps.c:127",
      "file": "kernel/bpf/queue_stack_maps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/queue_stack_maps.c:stack_map_pop_elem",
        "kernel/bpf/queue_stack_maps.c:stack_map_peek_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582008032,
      "name": "__stack_map_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
long int __stack_map_get(struct bpf_map * map, void * value, bool delete)
```

```json
{
  "name": "__stack_map_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582198896,
      "name": "__stack_map_get",
      "external": false,
      "loc": "kernel/bpf/queue_stack_maps.c:123",
      "file": "kernel/bpf/queue_stack_maps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/queue_stack_maps.c:stack_map_pop_elem",
        "kernel/bpf/queue_stack_maps.c:stack_map_peek_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582198896,
      "name": "__stack_map_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
long int __stack_map_get(struct bpf_map * map, void * value, bool delete)
```

```json
{
  "name": "__stack_map_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582348032,
      "name": "__stack_map_get",
      "external": false,
      "loc": "kernel/bpf/queue_stack_maps.c:128",
      "file": "kernel/bpf/queue_stack_maps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/queue_stack_maps.c:stack_map_pop_elem",
        "kernel/bpf/queue_stack_maps.c:stack_map_peek_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582348032,
      "name": "__stack_map_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
    }
  ]
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
int __stack_map_get(struct bpf_map * map, void * value, bool delete)
```

```json
{
  "name": "__stack_map_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492251600,
      "name": "__stack_map_get",
      "external": false,
      "loc": "kernel/bpf/queue_stack_maps.c:143",
      "file": "kernel/bpf/queue_stack_maps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/queue_stack_maps.c:stack_map_pop_elem",
        "kernel/bpf/queue_stack_maps.c:stack_map_peek_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492251600,
      "name": "__stack_map_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
int __stack_map_get(struct bpf_map * map, void * value, bool delete)
```

```json
{
  "name": "__stack_map_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226143500,
      "name": "__stack_map_get",
      "external": false,
      "loc": "kernel/bpf/queue_stack_maps.c:143",
      "file": "kernel/bpf/queue_stack_maps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/queue_stack_maps.c:stack_map_pop_elem",
        "kernel/bpf/queue_stack_maps.c:stack_map_peek_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226143500,
      "name": "__stack_map_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int __stack_map_get(struct bpf_map * map, void * value, bool delete)
```

```json
{
  "name": "__stack_map_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285480064,
      "name": "__stack_map_get",
      "external": false,
      "loc": "kernel/bpf/queue_stack_maps.c:143",
      "file": "kernel/bpf/queue_stack_maps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/queue_stack_maps.c:stack_map_pop_elem",
        "kernel/bpf/queue_stack_maps.c:stack_map_peek_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285480064,
      "name": "__stack_map_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 328
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int __stack_map_get(struct bpf_map * map, void * value, bool delete)
```

```json
{
  "name": "__stack_map_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272393080,
      "name": "__stack_map_get",
      "external": false,
      "loc": "kernel/bpf/queue_stack_maps.c:143",
      "file": "kernel/bpf/queue_stack_maps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/queue_stack_maps.c:stack_map_pop_elem",
        "kernel/bpf/queue_stack_maps.c:stack_map_peek_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272393080,
      "name": "__stack_map_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int __stack_map_get(struct bpf_map * map, void * value, bool delete)
```

```json
{
  "name": "__stack_map_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580885872,
      "name": "__stack_map_get",
      "external": false,
      "loc": "kernel/bpf/queue_stack_maps.c:143",
      "file": "kernel/bpf/queue_stack_maps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/queue_stack_maps.c:stack_map_pop_elem",
        "kernel/bpf/queue_stack_maps.c:stack_map_peek_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580885872,
      "name": "__stack_map_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int __stack_map_get(struct bpf_map * map, void * value, bool delete)
```

```json
{
  "name": "__stack_map_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580831936,
      "name": "__stack_map_get",
      "external": false,
      "loc": "kernel/bpf/queue_stack_maps.c:143",
      "file": "kernel/bpf/queue_stack_maps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/queue_stack_maps.c:stack_map_pop_elem",
        "kernel/bpf/queue_stack_maps.c:stack_map_peek_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580831936,
      "name": "__stack_map_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int __stack_map_get(struct bpf_map * map, void * value, bool delete)
```

```json
{
  "name": "__stack_map_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580877120,
      "name": "__stack_map_get",
      "external": false,
      "loc": "kernel/bpf/queue_stack_maps.c:143",
      "file": "kernel/bpf/queue_stack_maps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/queue_stack_maps.c:stack_map_pop_elem",
        "kernel/bpf/queue_stack_maps.c:stack_map_peek_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580877120,
      "name": "__stack_map_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int __stack_map_get(struct bpf_map * map, void * value, bool delete)
```

```json
{
  "name": "__stack_map_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580935760,
      "name": "__stack_map_get",
      "external": false,
      "loc": "kernel/bpf/queue_stack_maps.c:143",
      "file": "kernel/bpf/queue_stack_maps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/queue_stack_maps.c:stack_map_pop_elem",
        "kernel/bpf/queue_stack_maps.c:stack_map_peek_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580935760,
      "name": "__stack_map_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int __stack_map_get(struct bpf_map * map, void * value, bool delete)
```
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>long int</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
