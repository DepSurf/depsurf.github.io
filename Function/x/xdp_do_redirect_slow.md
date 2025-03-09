# Function: <code>xdp_do_redirect_slow</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xdp_do_redirect_slow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588126672,
      "name": "xdp_do_redirect_slow",
      "external": false,
      "loc": "net/core/filter.c:3352",
      "file": "net/core/filter.c",
      "inline": "not declared, not inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:xdp_do_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588126672,
      "name": "xdp_do_redirect_slow.isra.75",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 587
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xdp_do_redirect_slow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588448128,
      "name": "xdp_do_redirect_slow",
      "external": false,
      "loc": "net/core/filter.c:3487",
      "file": "net/core/filter.c",
      "inline": "not declared, not inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:xdp_do_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588448128,
      "name": "xdp_do_redirect_slow.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 604
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xdp_do_redirect_slow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588654672,
      "name": "xdp_do_redirect_slow",
      "external": false,
      "loc": "net/core/filter.c:3489",
      "file": "net/core/filter.c",
      "inline": "not declared, not inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:xdp_do_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588654672,
      "name": "xdp_do_redirect_slow.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 604
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
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
  "name": "xdp_do_redirect_slow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502220456,
      "name": "xdp_do_redirect_slow",
      "external": false,
      "loc": "net/core/filter.c:3489",
      "file": "net/core/filter.c",
      "inline": "not declared, not inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:xdp_do_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502220456,
      "name": "xdp_do_redirect_slow.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 648
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
int xdp_do_redirect_slow(struct net_device * dev, struct xdp_buff * xdp, struct bpf_prog * xdp_prog, struct bpf_redirect_info * ri)
```

```json
{
  "name": "xdp_do_redirect_slow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234946268,
      "name": "xdp_do_redirect_slow",
      "external": false,
      "loc": "net/core/filter.c:3489",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:xdp_do_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234946268,
      "name": "xdp_do_redirect_slow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 692
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "xdp_do_redirect_slow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295680912,
      "name": "xdp_do_redirect_slow",
      "external": false,
      "loc": "net/core/filter.c:3489",
      "file": "net/core/filter.c",
      "inline": "not declared, not inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:xdp_do_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295680912,
      "name": "xdp_do_redirect_slow.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 776
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
  "name": "xdp_do_redirect_slow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278452408,
      "name": "xdp_do_redirect_slow",
      "external": false,
      "loc": "net/core/filter.c:3489",
      "file": "net/core/filter.c",
      "inline": "not declared, not inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:xdp_do_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278452408,
      "name": "xdp_do_redirect_slow.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 470
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xdp_do_redirect_slow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588261408,
      "name": "xdp_do_redirect_slow",
      "external": false,
      "loc": "net/core/filter.c:3489",
      "file": "net/core/filter.c",
      "inline": "not declared, not inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:xdp_do_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588261408,
      "name": "xdp_do_redirect_slow.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 604
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xdp_do_redirect_slow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587974224,
      "name": "xdp_do_redirect_slow",
      "external": false,
      "loc": "net/core/filter.c:3489",
      "file": "net/core/filter.c",
      "inline": "not declared, not inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:xdp_do_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587974224,
      "name": "xdp_do_redirect_slow.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 604
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xdp_do_redirect_slow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588593232,
      "name": "xdp_do_redirect_slow",
      "external": false,
      "loc": "net/core/filter.c:3489",
      "file": "net/core/filter.c",
      "inline": "not declared, not inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:xdp_do_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588593232,
      "name": "xdp_do_redirect_slow.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 604
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xdp_do_redirect_slow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588730784,
      "name": "xdp_do_redirect_slow",
      "external": false,
      "loc": "net/core/filter.c:3489",
      "file": "net/core/filter.c",
      "inline": "not declared, not inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:xdp_do_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588730784,
      "name": "xdp_do_redirect_slow.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 663
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int xdp_do_redirect_slow(struct net_device * dev, struct xdp_buff * xdp, struct bpf_prog * xdp_prog, struct bpf_redirect_info * ri)
```
</details>
</li>
</ul>
