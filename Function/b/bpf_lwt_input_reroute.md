# Function: <code>bpf_lwt_input_reroute</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_lwt_input_reroute",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588555734,
      "name": "bpf_lwt_input_reroute",
      "external": false,
      "loc": "net/core/lwt_bpf.c:86",
      "file": "net/core/lwt_bpf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_input"
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
  "name": "bpf_lwt_input_reroute",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588772650,
      "name": "bpf_lwt_input_reroute",
      "external": false,
      "loc": "net/core/lwt_bpf.c:86",
      "file": "net/core/lwt_bpf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_input"
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
  "name": "bpf_lwt_input_reroute",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589647034,
      "name": "bpf_lwt_input_reroute",
      "external": false,
      "loc": "net/core/lwt_bpf.c:86",
      "file": "net/core/lwt_bpf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_input"
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
  "name": "bpf_lwt_input_reroute",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589670778,
      "name": "bpf_lwt_input_reroute",
      "external": false,
      "loc": "net/core/lwt_bpf.c:86",
      "file": "net/core/lwt_bpf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_input"
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
  "name": "bpf_lwt_input_reroute",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589562250,
      "name": "bpf_lwt_input_reroute",
      "external": false,
      "loc": "net/core/lwt_bpf.c:86",
      "file": "net/core/lwt_bpf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_input"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int bpf_lwt_input_reroute(struct sk_buff * skb)
```

```json
{
  "name": "bpf_lwt_input_reroute",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590307216,
      "name": "bpf_lwt_input_reroute",
      "external": false,
      "loc": "net/core/lwt_bpf.c:86",
      "file": "net/core/lwt_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590307216,
      "name": "bpf_lwt_input_reroute",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 396
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
int bpf_lwt_input_reroute(struct sk_buff * skb)
```

```json
{
  "name": "bpf_lwt_input_reroute",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591892096,
      "name": "bpf_lwt_input_reroute",
      "external": false,
      "loc": "net/core/lwt_bpf.c:87",
      "file": "net/core/lwt_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591892096,
      "name": "bpf_lwt_input_reroute",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 479
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
int bpf_lwt_input_reroute(struct sk_buff * skb)
```

```json
{
  "name": "bpf_lwt_input_reroute",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593694528,
      "name": "bpf_lwt_input_reroute",
      "external": false,
      "loc": "net/core/lwt_bpf.c:87",
      "file": "net/core/lwt_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593694528,
      "name": "bpf_lwt_input_reroute",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 479
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
int bpf_lwt_input_reroute(struct sk_buff * skb)
```

```json
{
  "name": "bpf_lwt_input_reroute",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594175344,
      "name": "bpf_lwt_input_reroute",
      "external": false,
      "loc": "net/core/lwt_bpf.c:86",
      "file": "net/core/lwt_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594175344,
      "name": "bpf_lwt_input_reroute",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 475
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
int bpf_lwt_input_reroute(struct sk_buff * skb)
```

```json
{
  "name": "bpf_lwt_input_reroute",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594971872,
      "name": "bpf_lwt_input_reroute",
      "external": false,
      "loc": "net/core/lwt_bpf.c:86",
      "file": "net/core/lwt_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594971872,
      "name": "bpf_lwt_input_reroute",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 475
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
  "name": "bpf_lwt_input_reroute",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336502341892,
      "name": "bpf_lwt_input_reroute",
      "external": false,
      "loc": "net/core/lwt_bpf.c:86",
      "file": "net/core/lwt_bpf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_input"
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
  "name": "bpf_lwt_input_reroute",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235078976,
      "name": "bpf_lwt_input_reroute",
      "external": false,
      "loc": "net/core/lwt_bpf.c:86",
      "file": "net/core/lwt_bpf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_input"
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
  "name": "bpf_lwt_input_reroute",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055295860884,
      "name": "bpf_lwt_input_reroute",
      "external": false,
      "loc": "net/core/lwt_bpf.c:86",
      "file": "net/core/lwt_bpf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_input"
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
  "name": "bpf_lwt_input_reroute",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278560864,
      "name": "bpf_lwt_input_reroute",
      "external": false,
      "loc": "net/core/lwt_bpf.c:86",
      "file": "net/core/lwt_bpf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_input"
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
  "name": "bpf_lwt_input_reroute",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588379034,
      "name": "bpf_lwt_input_reroute",
      "external": false,
      "loc": "net/core/lwt_bpf.c:86",
      "file": "net/core/lwt_bpf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_input"
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
  "name": "bpf_lwt_input_reroute",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588091722,
      "name": "bpf_lwt_input_reroute",
      "external": false,
      "loc": "net/core/lwt_bpf.c:86",
      "file": "net/core/lwt_bpf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_input"
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
  "name": "bpf_lwt_input_reroute",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588711210,
      "name": "bpf_lwt_input_reroute",
      "external": false,
      "loc": "net/core/lwt_bpf.c:86",
      "file": "net/core/lwt_bpf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_input"
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
  "name": "bpf_lwt_input_reroute",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588851466,
      "name": "bpf_lwt_input_reroute",
      "external": false,
      "loc": "net/core/lwt_bpf.c:86",
      "file": "net/core/lwt_bpf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_input"
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
int bpf_lwt_input_reroute(struct sk_buff * skb)
```
</details>
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
