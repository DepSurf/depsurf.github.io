# Function: <code>build_protos</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "build_protos",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580731637,
      "name": "build_protos",
      "external": false,
      "loc": "kernel/bpf/sockmap.c:183",
      "file": "kernel/bpf/sockmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/sockmap.c:bpf_tcp_ulp_register",
        "kernel/bpf/sockmap.c:bpf_tcp_init"
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
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void build_protos(struct proto * espintcp_prot, struct proto_ops * espintcp_ops, const struct proto * orig_prot, const struct proto_ops * orig_ops)
```

```json
{
  "name": "build_protos",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590521952,
      "name": "build_protos",
      "external": false,
      "loc": "net/xfrm/espintcp.c:552",
      "file": "net/xfrm/espintcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/espintcp.c:espintcp_init_sk",
        "net/xfrm/espintcp.c:espintcp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590521952,
      "name": "build_protos",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
void build_protos(struct proto * espintcp_prot, struct proto_ops * espintcp_ops, const struct proto * orig_prot, const struct proto_ops * orig_ops)
```

```json
{
  "name": "build_protos",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590581216,
      "name": "build_protos",
      "external": false,
      "loc": "net/xfrm/espintcp.c:556",
      "file": "net/xfrm/espintcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/espintcp.c:espintcp_init_sk",
        "net/xfrm/espintcp.c:espintcp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590581216,
      "name": "build_protos",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
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
void build_protos(struct proto * espintcp_prot, struct proto_ops * espintcp_ops, const struct proto * orig_prot, const struct proto_ops * orig_ops)
```

```json
{
  "name": "build_protos",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590506768,
      "name": "build_protos",
      "external": false,
      "loc": "net/xfrm/espintcp.c:556",
      "file": "net/xfrm/espintcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/espintcp.c:espintcp_init_sk",
        "net/xfrm/espintcp.c:espintcp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590506768,
      "name": "build_protos",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
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
void build_protos(struct proto * espintcp_prot, struct proto_ops * espintcp_ops, const struct proto * orig_prot, const struct proto_ops * orig_ops)
```

```json
{
  "name": "build_protos",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591312464,
      "name": "build_protos",
      "external": false,
      "loc": "net/xfrm/espintcp.c:556",
      "file": "net/xfrm/espintcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/espintcp.c:espintcp_init_sk",
        "net/xfrm/espintcp.c:espintcp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591312464,
      "name": "build_protos",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
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
void build_protos(struct proto * espintcp_prot, struct proto_ops * espintcp_ops, const struct proto * orig_prot, const struct proto_ops * orig_ops)
```

```json
{
  "name": "build_protos",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592980368,
      "name": "build_protos",
      "external": false,
      "loc": "net/xfrm/espintcp.c:554",
      "file": "net/xfrm/espintcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/espintcp.c:espintcp_init_sk",
        "net/xfrm/espintcp.c:espintcp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592980368,
      "name": "build_protos",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
void build_protos(struct proto * espintcp_prot, struct proto_ops * espintcp_ops, const struct proto * orig_prot, const struct proto_ops * orig_ops)
```

```json
{
  "name": "build_protos",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594869264,
      "name": "build_protos",
      "external": false,
      "loc": "net/xfrm/espintcp.c:555",
      "file": "net/xfrm/espintcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/espintcp.c:espintcp_init_sk",
        "net/xfrm/espintcp.c:espintcp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594869264,
      "name": "build_protos",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
void build_protos(struct proto * espintcp_prot, struct proto_ops * espintcp_ops, const struct proto * orig_prot, const struct proto_ops * orig_ops)
```

```json
{
  "name": "build_protos",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595261200,
      "name": "build_protos",
      "external": false,
      "loc": "net/xfrm/espintcp.c:564",
      "file": "net/xfrm/espintcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/espintcp.c:espintcp_init_sk",
        "net/xfrm/espintcp.c:espintcp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595261200,
      "name": "build_protos",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
void build_protos(struct proto * espintcp_prot, struct proto_ops * espintcp_ops, const struct proto * orig_prot, const struct proto_ops * orig_ops)
```

```json
{
  "name": "build_protos",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596101584,
      "name": "build_protos",
      "external": false,
      "loc": "net/xfrm/espintcp.c:564",
      "file": "net/xfrm/espintcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/espintcp.c:espintcp_init_sk",
        "net/xfrm/espintcp.c:espintcp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596101584,
      "name": "build_protos",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void build_protos(struct proto * espintcp_prot, struct proto_ops * espintcp_ops, const struct proto * orig_prot, const struct proto_ops * orig_ops)
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
