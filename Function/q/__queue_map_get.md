# Function: <code>__queue_map_get</code>

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
int __queue_map_get(struct bpf_map * map, void * value, bool delete)
```

```json
{
  "name": "__queue_map_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580780832,
      "name": "__queue_map_get",
      "external": false,
      "loc": "kernel/bpf/queue_stack_maps.c:115",
      "file": "kernel/bpf/queue_stack_maps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/queue_stack_maps.c:queue_map_pop_elem",
        "kernel/bpf/queue_stack_maps.c:queue_map_peek_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580780832,
      "name": "__queue_map_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
int __queue_map_get(struct bpf_map * map, void * value, bool delete)
```

```json
{
  "name": "__queue_map_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580865600,
      "name": "__queue_map_get",
      "external": false,
      "loc": "kernel/bpf/queue_stack_maps.c:114",
      "file": "kernel/bpf/queue_stack_maps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/queue_stack_maps.c:queue_map_pop_elem",
        "kernel/bpf/queue_stack_maps.c:queue_map_peek_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580865600,
      "name": "__queue_map_get",
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
int __queue_map_get(struct bpf_map * map, void * value, bool delete)
```

```json
{
  "name": "__queue_map_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580916560,
      "name": "__queue_map_get",
      "external": false,
      "loc": "kernel/bpf/queue_stack_maps.c:114",
      "file": "kernel/bpf/queue_stack_maps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/queue_stack_maps.c:queue_map_pop_elem",
        "kernel/bpf/queue_stack_maps.c:queue_map_peek_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580916560,
      "name": "__queue_map_get",
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
int __queue_map_get(struct bpf_map * map, void * value, bool delete)
```

```json
{
  "name": "__queue_map_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581063616,
      "name": "__queue_map_get",
      "external": false,
      "loc": "kernel/bpf/queue_stack_maps.c:114",
      "file": "kernel/bpf/queue_stack_maps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/queue_stack_maps.c:queue_map_pop_elem",
        "kernel/bpf/queue_stack_maps.c:queue_map_peek_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581063616,
      "name": "__queue_map_get",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int __queue_map_get(struct bpf_map * map, void * value, bool delete)
```

```json
{
  "name": "__queue_map_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581075440,
      "name": "__queue_map_get",
      "external": false,
      "loc": "kernel/bpf/queue_stack_maps.c:99",
      "file": "kernel/bpf/queue_stack_maps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/queue_stack_maps.c:queue_map_pop_elem",
        "kernel/bpf/queue_stack_maps.c:queue_map_peek_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581075440,
      "name": "__queue_map_get",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int __queue_map_get(struct bpf_map * map, void * value, bool delete)
```

```json
{
  "name": "__queue_map_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581090432,
      "name": "__queue_map_get",
      "external": false,
      "loc": "kernel/bpf/queue_stack_maps.c:99",
      "file": "kernel/bpf/queue_stack_maps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/queue_stack_maps.c:queue_map_pop_elem",
        "kernel/bpf/queue_stack_maps.c:queue_map_peek_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581090432,
      "name": "__queue_map_get",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int __queue_map_get(struct bpf_map * map, void * value, bool delete)
```

```json
{
  "name": "__queue_map_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581319616,
      "name": "__queue_map_get",
      "external": false,
      "loc": "kernel/bpf/queue_stack_maps.c:99",
      "file": "kernel/bpf/queue_stack_maps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/queue_stack_maps.c:queue_map_pop_elem",
        "kernel/bpf/queue_stack_maps.c:queue_map_peek_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581319616,
      "name": "__queue_map_get",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int __queue_map_get(struct bpf_map * map, void * value, bool delete)
```

```json
{
  "name": "__queue_map_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581621856,
      "name": "__queue_map_get",
      "external": false,
      "loc": "kernel/bpf/queue_stack_maps.c:100",
      "file": "kernel/bpf/queue_stack_maps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/queue_stack_maps.c:queue_map_pop_elem",
        "kernel/bpf/queue_stack_maps.c:queue_map_peek_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581621856,
      "name": "__queue_map_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
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
int __queue_map_get(struct bpf_map * map, void * value, bool delete)
```

```json
{
  "name": "__queue_map_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582007456,
      "name": "__queue_map_get",
      "external": false,
      "loc": "kernel/bpf/queue_stack_maps.c:98",
      "file": "kernel/bpf/queue_stack_maps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/queue_stack_maps.c:queue_map_pop_elem",
        "kernel/bpf/queue_stack_maps.c:queue_map_peek_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582007456,
      "name": "__queue_map_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
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
long int __queue_map_get(struct bpf_map * map, void * value, bool delete)
```

```json
{
  "name": "__queue_map_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582198320,
      "name": "__queue_map_get",
      "external": false,
      "loc": "kernel/bpf/queue_stack_maps.c:94",
      "file": "kernel/bpf/queue_stack_maps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/queue_stack_maps.c:queue_map_pop_elem",
        "kernel/bpf/queue_stack_maps.c:queue_map_peek_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582198320,
      "name": "__queue_map_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
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
long int __queue_map_get(struct bpf_map * map, void * value, bool delete)
```

```json
{
  "name": "__queue_map_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582347264,
      "name": "__queue_map_get",
      "external": false,
      "loc": "kernel/bpf/queue_stack_maps.c:94",
      "file": "kernel/bpf/queue_stack_maps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/queue_stack_maps.c:queue_map_pop_elem",
        "kernel/bpf/queue_stack_maps.c:queue_map_peek_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582347264,
      "name": "__queue_map_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
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
int __queue_map_get(struct bpf_map * map, void * value, bool delete)
```

```json
{
  "name": "__queue_map_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492251984,
      "name": "__queue_map_get",
      "external": false,
      "loc": "kernel/bpf/queue_stack_maps.c:114",
      "file": "kernel/bpf/queue_stack_maps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/queue_stack_maps.c:queue_map_pop_elem",
        "kernel/bpf/queue_stack_maps.c:queue_map_peek_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492251984,
      "name": "__queue_map_get",
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
int __queue_map_get(struct bpf_map * map, void * value, bool delete)
```

```json
{
  "name": "__queue_map_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226143032,
      "name": "__queue_map_get",
      "external": false,
      "loc": "kernel/bpf/queue_stack_maps.c:114",
      "file": "kernel/bpf/queue_stack_maps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/queue_stack_maps.c:queue_map_pop_elem",
        "kernel/bpf/queue_stack_maps.c:queue_map_peek_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226143032,
      "name": "__queue_map_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
int __queue_map_get(struct bpf_map * map, void * value, bool delete)
```

```json
{
  "name": "__queue_map_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285479376,
      "name": "__queue_map_get",
      "external": false,
      "loc": "kernel/bpf/queue_stack_maps.c:114",
      "file": "kernel/bpf/queue_stack_maps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/queue_stack_maps.c:queue_map_pop_elem",
        "kernel/bpf/queue_stack_maps.c:queue_map_peek_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285479376,
      "name": "__queue_map_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "__queue_map_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272392716,
      "name": "__queue_map_get",
      "external": false,
      "loc": "kernel/bpf/queue_stack_maps.c:114",
      "file": "kernel/bpf/queue_stack_maps.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/queue_stack_maps.c:queue_map_pop_elem",
        "kernel/bpf/queue_stack_maps.c:queue_map_peek_elem"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int __queue_map_get(struct bpf_map * map, void * value, bool delete)
```

```json
{
  "name": "__queue_map_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580885360,
      "name": "__queue_map_get",
      "external": false,
      "loc": "kernel/bpf/queue_stack_maps.c:114",
      "file": "kernel/bpf/queue_stack_maps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/queue_stack_maps.c:queue_map_pop_elem",
        "kernel/bpf/queue_stack_maps.c:queue_map_peek_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580885360,
      "name": "__queue_map_get",
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
int __queue_map_get(struct bpf_map * map, void * value, bool delete)
```

```json
{
  "name": "__queue_map_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580831424,
      "name": "__queue_map_get",
      "external": false,
      "loc": "kernel/bpf/queue_stack_maps.c:114",
      "file": "kernel/bpf/queue_stack_maps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/queue_stack_maps.c:queue_map_pop_elem",
        "kernel/bpf/queue_stack_maps.c:queue_map_peek_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580831424,
      "name": "__queue_map_get",
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
int __queue_map_get(struct bpf_map * map, void * value, bool delete)
```

```json
{
  "name": "__queue_map_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580876608,
      "name": "__queue_map_get",
      "external": false,
      "loc": "kernel/bpf/queue_stack_maps.c:114",
      "file": "kernel/bpf/queue_stack_maps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/queue_stack_maps.c:queue_map_pop_elem",
        "kernel/bpf/queue_stack_maps.c:queue_map_peek_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580876608,
      "name": "__queue_map_get",
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
int __queue_map_get(struct bpf_map * map, void * value, bool delete)
```

```json
{
  "name": "__queue_map_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580935248,
      "name": "__queue_map_get",
      "external": false,
      "loc": "kernel/bpf/queue_stack_maps.c:114",
      "file": "kernel/bpf/queue_stack_maps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/queue_stack_maps.c:queue_map_pop_elem",
        "kernel/bpf/queue_stack_maps.c:queue_map_peek_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580935248,
      "name": "__queue_map_get",
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
int __queue_map_get(struct bpf_map * map, void * value, bool delete)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int __queue_map_get(struct bpf_map * map, void * value, bool delete)
```
</details>
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
