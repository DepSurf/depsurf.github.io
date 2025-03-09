# Function: <code>xfrm4_remove_beet_encap</code>

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
  "name": "xfrm4_remove_beet_encap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589284965,
      "name": "xfrm4_remove_beet_encap",
      "external": false,
      "loc": "net/xfrm/xfrm_input.c:171",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "xfrm4_remove_beet_encap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589509397,
      "name": "xfrm4_remove_beet_encap",
      "external": false,
      "loc": "net/xfrm/xfrm_input.c:171",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
int xfrm4_remove_beet_encap(struct xfrm_state * x, struct sk_buff * skb)
```

```json
{
  "name": "xfrm4_remove_beet_encap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590501072,
      "name": "xfrm4_remove_beet_encap",
      "external": false,
      "loc": "net/xfrm/xfrm_input.c:172",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_prepare_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590501072,
      "name": "xfrm4_remove_beet_encap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 485
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
int xfrm4_remove_beet_encap(struct xfrm_state * x, struct sk_buff * skb)
```

```json
{
  "name": "xfrm4_remove_beet_encap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590560672,
      "name": "xfrm4_remove_beet_encap",
      "external": false,
      "loc": "net/xfrm/xfrm_input.c:174",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_prepare_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590560672,
      "name": "xfrm4_remove_beet_encap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 485
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
int xfrm4_remove_beet_encap(struct xfrm_state * x, struct sk_buff * skb)
```

```json
{
  "name": "xfrm4_remove_beet_encap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590486016,
      "name": "xfrm4_remove_beet_encap",
      "external": false,
      "loc": "net/xfrm/xfrm_input.c:174",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_prepare_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590486016,
      "name": "xfrm4_remove_beet_encap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 485
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
int xfrm4_remove_beet_encap(struct xfrm_state * x, struct sk_buff * skb)
```

```json
{
  "name": "xfrm4_remove_beet_encap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591290400,
      "name": "xfrm4_remove_beet_encap",
      "external": false,
      "loc": "net/xfrm/xfrm_input.c:174",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_prepare_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591290400,
      "name": "xfrm4_remove_beet_encap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 485
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
int xfrm4_remove_beet_encap(struct xfrm_state * x, struct sk_buff * skb)
```

```json
{
  "name": "xfrm4_remove_beet_encap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592957024,
      "name": "xfrm4_remove_beet_encap",
      "external": false,
      "loc": "net/xfrm/xfrm_input.c:174",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_prepare_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592957024,
      "name": "xfrm4_remove_beet_encap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 497
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
int xfrm4_remove_beet_encap(struct xfrm_state * x, struct sk_buff * skb)
```

```json
{
  "name": "xfrm4_remove_beet_encap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594842736,
      "name": "xfrm4_remove_beet_encap",
      "external": false,
      "loc": "net/xfrm/xfrm_input.c:176",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_prepare_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594842736,
      "name": "xfrm4_remove_beet_encap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 497
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
int xfrm4_remove_beet_encap(struct xfrm_state * x, struct sk_buff * skb)
```

```json
{
  "name": "xfrm4_remove_beet_encap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595234048,
      "name": "xfrm4_remove_beet_encap",
      "external": false,
      "loc": "net/xfrm/xfrm_input.c:177",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_prepare_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595234048,
      "name": "xfrm4_remove_beet_encap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 509
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
int xfrm4_remove_beet_encap(struct xfrm_state * x, struct sk_buff * skb)
```

```json
{
  "name": "xfrm4_remove_beet_encap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596074528,
      "name": "xfrm4_remove_beet_encap",
      "external": false,
      "loc": "net/xfrm/xfrm_input.c:177",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_prepare_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596074528,
      "name": "xfrm4_remove_beet_encap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 509
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
  "name": "xfrm4_remove_beet_encap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336503174040,
      "name": "xfrm4_remove_beet_encap",
      "external": false,
      "loc": "net/xfrm/xfrm_input.c:171",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "xfrm4_remove_beet_encap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235849432,
      "name": "xfrm4_remove_beet_encap",
      "external": false,
      "loc": "net/xfrm/xfrm_input.c:171",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_inner_mode_input"
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
  "name": "xfrm4_remove_beet_encap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055296900932,
      "name": "xfrm4_remove_beet_encap",
      "external": false,
      "loc": "net/xfrm/xfrm_input.c:171",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "xfrm4_remove_beet_encap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936279216098,
      "name": "xfrm4_remove_beet_encap",
      "external": false,
      "loc": "net/xfrm/xfrm_input.c:171",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "xfrm4_remove_beet_encap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589113765,
      "name": "xfrm4_remove_beet_encap",
      "external": false,
      "loc": "net/xfrm/xfrm_input.c:171",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "xfrm4_remove_beet_encap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588838805,
      "name": "xfrm4_remove_beet_encap",
      "external": false,
      "loc": "net/xfrm/xfrm_input.c:171",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "xfrm4_remove_beet_encap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589550629,
      "name": "xfrm4_remove_beet_encap",
      "external": false,
      "loc": "net/xfrm/xfrm_input.c:171",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "xfrm4_remove_beet_encap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589598101,
      "name": "xfrm4_remove_beet_encap",
      "external": false,
      "loc": "net/xfrm/xfrm_input.c:171",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
int xfrm4_remove_beet_encap(struct xfrm_state * x, struct sk_buff * skb)
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
