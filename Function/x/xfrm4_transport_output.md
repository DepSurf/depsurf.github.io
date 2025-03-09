# Function: <code>xfrm4_transport_output</code>

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
  "name": "xfrm4_transport_output",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589290878,
      "name": "xfrm4_transport_output",
      "external": false,
      "loc": "net/xfrm/xfrm_output.c:58",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_outer_mode_output"
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
  "name": "xfrm4_transport_output",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589515262,
      "name": "xfrm4_transport_output",
      "external": false,
      "loc": "net/xfrm/xfrm_output.c:58",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_outer_mode_output"
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
int xfrm4_transport_output(struct xfrm_state * x, struct sk_buff * skb)
```

```json
{
  "name": "xfrm4_transport_output",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590507600,
      "name": "xfrm4_transport_output",
      "external": false,
      "loc": "net/xfrm/xfrm_output.c:64",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_output.c:xfrm_outer_mode_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590507600,
      "name": "xfrm4_transport_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
int xfrm4_transport_output(struct xfrm_state * x, struct sk_buff * skb)
```

```json
{
  "name": "xfrm4_transport_output",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590567200,
      "name": "xfrm4_transport_output",
      "external": false,
      "loc": "net/xfrm/xfrm_output.c:64",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_output.c:xfrm_outer_mode_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590567200,
      "name": "xfrm4_transport_output",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xfrm4_transport_output",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590494762,
      "name": "xfrm4_transport_output",
      "external": false,
      "loc": "net/xfrm/xfrm_output.c:64",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_outer_mode_output"
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
  "name": "xfrm4_transport_output",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591299954,
      "name": "xfrm4_transport_output",
      "external": false,
      "loc": "net/xfrm/xfrm_output.c:64",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_outer_mode_output"
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
  "name": "xfrm4_transport_output",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592966668,
      "name": "xfrm4_transport_output",
      "external": false,
      "loc": "net/xfrm/xfrm_output.c:64",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_outer_mode_output"
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
  "name": "xfrm4_transport_output",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594852971,
      "name": "xfrm4_transport_output",
      "external": false,
      "loc": "net/xfrm/xfrm_output.c:64",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_outer_mode_output"
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
  "name": "xfrm4_transport_output",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595243966,
      "name": "xfrm4_transport_output",
      "external": false,
      "loc": "net/xfrm/xfrm_output.c:65",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_outer_mode_output"
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
  "name": "xfrm4_transport_output",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596084462,
      "name": "xfrm4_transport_output",
      "external": false,
      "loc": "net/xfrm/xfrm_output.c:65",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_outer_mode_output"
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
  "name": "xfrm4_transport_output",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336503180336,
      "name": "xfrm4_transport_output",
      "external": false,
      "loc": "net/xfrm/xfrm_output.c:58",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_outer_mode_output"
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
  "name": "xfrm4_transport_output",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235855200,
      "name": "xfrm4_transport_output",
      "external": false,
      "loc": "net/xfrm/xfrm_output.c:58",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_outer_mode_output"
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
  "name": "xfrm4_transport_output",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055296907584,
      "name": "xfrm4_transport_output",
      "external": false,
      "loc": "net/xfrm/xfrm_output.c:58",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_outer_mode_output"
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
  "name": "xfrm4_transport_output",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936279221548,
      "name": "xfrm4_transport_output",
      "external": false,
      "loc": "net/xfrm/xfrm_output.c:58",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_outer_mode_output"
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
  "name": "xfrm4_transport_output",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589119630,
      "name": "xfrm4_transport_output",
      "external": false,
      "loc": "net/xfrm/xfrm_output.c:58",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_outer_mode_output"
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
  "name": "xfrm4_transport_output",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588844670,
      "name": "xfrm4_transport_output",
      "external": false,
      "loc": "net/xfrm/xfrm_output.c:58",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_outer_mode_output"
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
  "name": "xfrm4_transport_output",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589556494,
      "name": "xfrm4_transport_output",
      "external": false,
      "loc": "net/xfrm/xfrm_output.c:58",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_outer_mode_output"
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
  "name": "xfrm4_transport_output",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589603998,
      "name": "xfrm4_transport_output",
      "external": false,
      "loc": "net/xfrm/xfrm_output.c:58",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_outer_mode_output"
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
int xfrm4_transport_output(struct xfrm_state * x, struct sk_buff * skb)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int xfrm4_transport_output(struct xfrm_state * x, struct sk_buff * skb)
```
</details>
</li>
</ul>
