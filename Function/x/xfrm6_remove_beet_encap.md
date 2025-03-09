# Function: <code>xfrm6_remove_beet_encap</code>

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
  "name": "xfrm6_remove_beet_encap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589284606,
      "name": "xfrm6_remove_beet_encap",
      "external": false,
      "loc": "net/xfrm/xfrm_input.c:293",
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
  "name": "xfrm6_remove_beet_encap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589509038,
      "name": "xfrm6_remove_beet_encap",
      "external": false,
      "loc": "net/xfrm/xfrm_input.c:293",
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
int xfrm6_remove_beet_encap(struct xfrm_state * x, struct sk_buff * skb)
```

```json
{
  "name": "xfrm6_remove_beet_encap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590499856,
      "name": "xfrm6_remove_beet_encap",
      "external": false,
      "loc": "net/xfrm/xfrm_input.c:294",
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
      "addr": 18446744071590499856,
      "name": "xfrm6_remove_beet_encap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 379
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
int xfrm6_remove_beet_encap(struct xfrm_state * x, struct sk_buff * skb)
```

```json
{
  "name": "xfrm6_remove_beet_encap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590559280,
      "name": "xfrm6_remove_beet_encap",
      "external": false,
      "loc": "net/xfrm/xfrm_input.c:296",
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
      "addr": 18446744071590559280,
      "name": "xfrm6_remove_beet_encap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 389
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
int xfrm6_remove_beet_encap(struct xfrm_state * x, struct sk_buff * skb)
```

```json
{
  "name": "xfrm6_remove_beet_encap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590484640,
      "name": "xfrm6_remove_beet_encap",
      "external": false,
      "loc": "net/xfrm/xfrm_input.c:296",
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
      "addr": 18446744071590484640,
      "name": "xfrm6_remove_beet_encap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 378
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
int xfrm6_remove_beet_encap(struct xfrm_state * x, struct sk_buff * skb)
```

```json
{
  "name": "xfrm6_remove_beet_encap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591288176,
      "name": "xfrm6_remove_beet_encap",
      "external": false,
      "loc": "net/xfrm/xfrm_input.c:296",
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
      "addr": 18446744071591288176,
      "name": "xfrm6_remove_beet_encap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 381
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
int xfrm6_remove_beet_encap(struct xfrm_state * x, struct sk_buff * skb)
```

```json
{
  "name": "xfrm6_remove_beet_encap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592955648,
      "name": "xfrm6_remove_beet_encap",
      "external": false,
      "loc": "net/xfrm/xfrm_input.c:296",
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
      "addr": 18446744071592955648,
      "name": "xfrm6_remove_beet_encap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 403
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xfrm6_remove_beet_encap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594844495,
      "name": "xfrm6_remove_beet_encap",
      "external": false,
      "loc": "net/xfrm/xfrm_input.c:297",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_prepare_input"
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
  "name": "xfrm6_remove_beet_encap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595235627,
      "name": "xfrm6_remove_beet_encap",
      "external": false,
      "loc": "net/xfrm/xfrm_input.c:299",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_prepare_input"
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
  "name": "xfrm6_remove_beet_encap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596076107,
      "name": "xfrm6_remove_beet_encap",
      "external": false,
      "loc": "net/xfrm/xfrm_input.c:299",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_prepare_input"
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
  "name": "xfrm6_remove_beet_encap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336503173692,
      "name": "xfrm6_remove_beet_encap",
      "external": false,
      "loc": "net/xfrm/xfrm_input.c:293",
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
  "name": "xfrm6_remove_beet_encap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235849740,
      "name": "xfrm6_remove_beet_encap",
      "external": false,
      "loc": "net/xfrm/xfrm_input.c:293",
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
  "name": "xfrm6_remove_beet_encap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055296900368,
      "name": "xfrm6_remove_beet_encap",
      "external": false,
      "loc": "net/xfrm/xfrm_input.c:293",
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
  "name": "xfrm6_remove_beet_encap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936279215734,
      "name": "xfrm6_remove_beet_encap",
      "external": false,
      "loc": "net/xfrm/xfrm_input.c:293",
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
  "name": "xfrm6_remove_beet_encap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589113406,
      "name": "xfrm6_remove_beet_encap",
      "external": false,
      "loc": "net/xfrm/xfrm_input.c:293",
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
  "name": "xfrm6_remove_beet_encap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588838446,
      "name": "xfrm6_remove_beet_encap",
      "external": false,
      "loc": "net/xfrm/xfrm_input.c:293",
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
  "name": "xfrm6_remove_beet_encap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589550270,
      "name": "xfrm6_remove_beet_encap",
      "external": false,
      "loc": "net/xfrm/xfrm_input.c:293",
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
  "name": "xfrm6_remove_beet_encap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589597737,
      "name": "xfrm6_remove_beet_encap",
      "external": false,
      "loc": "net/xfrm/xfrm_input.c:293",
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
int xfrm6_remove_beet_encap(struct xfrm_state * x, struct sk_buff * skb)
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
int xfrm6_remove_beet_encap(struct xfrm_state * x, struct sk_buff * skb)
```
</details>
</li>
</ul>
