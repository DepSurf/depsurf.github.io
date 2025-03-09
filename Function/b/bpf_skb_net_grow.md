# Function: <code>bpf_skb_net_grow</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_skb_net_grow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587149189,
      "name": "bpf_skb_net_grow",
      "external": false,
      "loc": "net/core/filter.c:2169",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_adjust_room"
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
  "name": "bpf_skb_net_grow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587656789,
      "name": "bpf_skb_net_grow",
      "external": false,
      "loc": "net/core/filter.c:2234",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_adjust_room"
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
  "name": "bpf_skb_net_grow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587980367,
      "name": "bpf_skb_net_grow",
      "external": false,
      "loc": "net/core/filter.c:2763",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_adjust_room"
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
  "name": "bpf_skb_net_grow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588132076,
      "name": "bpf_skb_net_grow",
      "external": false,
      "loc": "net/core/filter.c:2953",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_adjust_room"
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
  "name": "bpf_skb_net_grow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588446223,
      "name": "bpf_skb_net_grow",
      "external": false,
      "loc": "net/core/filter.c:3009",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_adjust_room"
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
  "name": "bpf_skb_net_grow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588652607,
      "name": "bpf_skb_net_grow",
      "external": false,
      "loc": "net/core/filter.c:3011",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_adjust_room"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int bpf_skb_net_grow(struct sk_buff * skb, u32 off, u32 len_diff, u64 flags)
```

```json
{
  "name": "bpf_skb_net_grow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589511584,
      "name": "bpf_skb_net_grow",
      "external": false,
      "loc": "net/core/filter.c:3049",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_skb_adjust_room"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589511584,
      "name": "bpf_skb_net_grow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 806
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
int bpf_skb_net_grow(struct sk_buff * skb, u32 off, u32 len_diff, u64 flags)
```

```json
{
  "name": "bpf_skb_net_grow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589517088,
      "name": "bpf_skb_net_grow",
      "external": false,
      "loc": "net/core/filter.c:3418",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_skb_adjust_room"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589517088,
      "name": "bpf_skb_net_grow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 806
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
int bpf_skb_net_grow(struct sk_buff * skb, u32 off, u32 len_diff, u64 flags)
```

```json
{
  "name": "bpf_skb_net_grow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589416848,
      "name": "bpf_skb_net_grow",
      "external": false,
      "loc": "net/core/filter.c:3412",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_skb_adjust_room"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589416848,
      "name": "bpf_skb_net_grow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 885
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
int bpf_skb_net_grow(struct sk_buff * skb, u32 off, u32 len_diff, u64 flags)
```

```json
{
  "name": "bpf_skb_net_grow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590143296,
      "name": "bpf_skb_net_grow",
      "external": false,
      "loc": "net/core/filter.c:3381",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_skb_adjust_room"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590143296,
      "name": "bpf_skb_net_grow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 883
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
int bpf_skb_net_grow(struct sk_buff * skb, u32 off, u32 len_diff, u64 flags)
```

```json
{
  "name": "bpf_skb_net_grow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591697872,
      "name": "bpf_skb_net_grow",
      "external": false,
      "loc": "net/core/filter.c:3382",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_skb_adjust_room"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591697872,
      "name": "bpf_skb_net_grow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 892
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
int bpf_skb_net_grow(struct sk_buff * skb, u32 off, u32 len_diff, u64 flags)
```

```json
{
  "name": "bpf_skb_net_grow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593497296,
      "name": "bpf_skb_net_grow",
      "external": false,
      "loc": "net/core/filter.c:3392",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_skb_adjust_room"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593497296,
      "name": "bpf_skb_net_grow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 978
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
int bpf_skb_net_grow(struct sk_buff * skb, u32 off, u32 len_diff, u64 flags)
```

```json
{
  "name": "bpf_skb_net_grow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593962464,
      "name": "bpf_skb_net_grow",
      "external": false,
      "loc": "net/core/filter.c:3412",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_skb_adjust_room"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593962464,
      "name": "bpf_skb_net_grow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 976
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
int bpf_skb_net_grow(struct sk_buff * skb, u32 off, u32 len_diff, u64 flags)
```

```json
{
  "name": "bpf_skb_net_grow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594744688,
      "name": "bpf_skb_net_grow",
      "external": false,
      "loc": "net/core/filter.c:3446",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_skb_adjust_room"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594744688,
      "name": "bpf_skb_net_grow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 976
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_skb_net_grow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336502197624,
      "name": "bpf_skb_net_grow",
      "external": false,
      "loc": "net/core/filter.c:3011",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_adjust_room"
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
  "name": "bpf_skb_net_grow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3234950392,
      "name": "bpf_skb_net_grow",
      "external": false,
      "loc": "net/core/filter.c:3011",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_adjust_room"
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
  "name": "bpf_skb_net_grow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055295693344,
      "name": "bpf_skb_net_grow",
      "external": false,
      "loc": "net/core/filter.c:3011",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_adjust_room"
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
  "name": "bpf_skb_net_grow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278456074,
      "name": "bpf_skb_net_grow",
      "external": false,
      "loc": "net/core/filter.c:3011",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_adjust_room"
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
  "name": "bpf_skb_net_grow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588259343,
      "name": "bpf_skb_net_grow",
      "external": false,
      "loc": "net/core/filter.c:3011",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_adjust_room"
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
  "name": "bpf_skb_net_grow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587972159,
      "name": "bpf_skb_net_grow",
      "external": false,
      "loc": "net/core/filter.c:3011",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_adjust_room"
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
  "name": "bpf_skb_net_grow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588591167,
      "name": "bpf_skb_net_grow",
      "external": false,
      "loc": "net/core/filter.c:3011",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_adjust_room"
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
  "name": "bpf_skb_net_grow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588728655,
      "name": "bpf_skb_net_grow",
      "external": false,
      "loc": "net/core/filter.c:3011",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_adjust_room"
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int bpf_skb_net_grow(struct sk_buff * skb, u32 off, u32 len_diff, u64 flags)
```
</details>
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
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
