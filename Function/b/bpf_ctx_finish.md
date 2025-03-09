# Function: <code>bpf_ctx_finish</code>

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
  "name": "bpf_ctx_finish",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588731211,
      "name": "bpf_ctx_finish",
      "external": false,
      "loc": "net/bpf/test_run.c:159",
      "file": "net/bpf/test_run.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/bpf/test_run.c:bpf_prog_test_run_skb"
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
  "name": "bpf_ctx_finish",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588953360,
      "name": "bpf_ctx_finish",
      "external": false,
      "loc": "net/bpf/test_run.c:159",
      "file": "net/bpf/test_run.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector",
        "net/bpf/test_run.c:bpf_prog_test_run_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588953360,
      "name": "bpf_ctx_finish.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_ctx_finish",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589848704,
      "name": "bpf_ctx_finish",
      "external": false,
      "loc": "net/bpf/test_run.c:270",
      "file": "net/bpf/test_run.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector",
        "net/bpf/test_run.c:bpf_prog_test_run_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589848704,
      "name": "bpf_ctx_finish.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_ctx_finish",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589887072,
      "name": "bpf_ctx_finish",
      "external": false,
      "loc": "net/bpf/test_run.c:353",
      "file": "net/bpf/test_run.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector",
        "net/bpf/test_run.c:bpf_prog_test_run_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589887072,
      "name": "bpf_ctx_finish.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
  "name": "bpf_ctx_finish",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589793760,
      "name": "bpf_ctx_finish",
      "external": false,
      "loc": "net/bpf/test_run.c:427",
      "file": "net/bpf/test_run.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/bpf/test_run.c:bpf_prog_test_run_sk_lookup",
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector",
        "net/bpf/test_run.c:bpf_prog_test_run_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589793760,
      "name": "bpf_ctx_finish.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_ctx_finish",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590551584,
      "name": "bpf_ctx_finish",
      "external": false,
      "loc": "net/bpf/test_run.c:428",
      "file": "net/bpf/test_run.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/bpf/test_run.c:bpf_prog_test_run_sk_lookup",
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector",
        "net/bpf/test_run.c:bpf_prog_test_run_xdp",
        "net/bpf/test_run.c:bpf_prog_test_run_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590551584,
      "name": "bpf_ctx_finish.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_ctx_finish",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592161984,
      "name": "bpf_ctx_finish",
      "external": false,
      "loc": "net/bpf/test_run.c:914",
      "file": "net/bpf/test_run.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/bpf/test_run.c:bpf_prog_test_run_sk_lookup",
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector",
        "net/bpf/test_run.c:bpf_prog_test_run_xdp",
        "net/bpf/test_run.c:bpf_prog_test_run_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592161984,
      "name": "bpf_ctx_finish.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
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
  "name": "bpf_ctx_finish",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593989488,
      "name": "bpf_ctx_finish",
      "external": false,
      "loc": "net/bpf/test_run.c:946",
      "file": "net/bpf/test_run.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/bpf/test_run.c:bpf_prog_test_run_sk_lookup",
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector",
        "net/bpf/test_run.c:bpf_prog_test_run_xdp",
        "net/bpf/test_run.c:bpf_prog_test_run_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593989488,
      "name": "bpf_ctx_finish.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_ctx_finish",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594367024,
      "name": "bpf_ctx_finish",
      "external": false,
      "loc": "net/bpf/test_run.c:787",
      "file": "net/bpf/test_run.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/bpf/test_run.c:bpf_prog_test_run_sk_lookup",
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector",
        "net/bpf/test_run.c:bpf_prog_test_run_xdp",
        "net/bpf/test_run.c:bpf_prog_test_run_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594367024,
      "name": "bpf_ctx_finish.isra.0",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_ctx_finish",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595167840,
      "name": "bpf_ctx_finish",
      "external": false,
      "loc": "net/bpf/test_run.c:815",
      "file": "net/bpf/test_run.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/bpf/test_run.c:bpf_prog_test_run_sk_lookup",
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector",
        "net/bpf/test_run.c:bpf_prog_test_run_xdp",
        "net/bpf/test_run.c:bpf_prog_test_run_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595167840,
      "name": "bpf_ctx_finish.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
  "name": "bpf_ctx_finish",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502554616,
      "name": "bpf_ctx_finish",
      "external": false,
      "loc": "net/bpf/test_run.c:159",
      "file": "net/bpf/test_run.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector",
        "net/bpf/test_run.c:bpf_prog_test_run_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502554616,
      "name": "bpf_ctx_finish.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 384
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
int bpf_ctx_finish(const union bpf_attr * kattr, union bpf_attr * uattr, const void * data, u32 size)
```

```json
{
  "name": "bpf_ctx_finish",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235259784,
      "name": "bpf_ctx_finish",
      "external": false,
      "loc": "net/bpf/test_run.c:159",
      "file": "net/bpf/test_run.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector",
        "net/bpf/test_run.c:bpf_prog_test_run_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235259784,
      "name": "bpf_ctx_finish",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 380
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
  "name": "bpf_ctx_finish",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296132560,
      "name": "bpf_ctx_finish",
      "external": false,
      "loc": "net/bpf/test_run.c:159",
      "file": "net/bpf/test_run.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector",
        "net/bpf/test_run.c:bpf_prog_test_run_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296132560,
      "name": "bpf_ctx_finish.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
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
  "name": "bpf_ctx_finish",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278715266,
      "name": "bpf_ctx_finish",
      "external": false,
      "loc": "net/bpf/test_run.c:159",
      "file": "net/bpf/test_run.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector",
        "net/bpf/test_run.c:bpf_prog_test_run_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278715266,
      "name": "bpf_ctx_finish.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
  "name": "bpf_ctx_finish",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588559744,
      "name": "bpf_ctx_finish",
      "external": false,
      "loc": "net/bpf/test_run.c:159",
      "file": "net/bpf/test_run.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector",
        "net/bpf/test_run.c:bpf_prog_test_run_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588559744,
      "name": "bpf_ctx_finish.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
  "name": "bpf_ctx_finish",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588271728,
      "name": "bpf_ctx_finish",
      "external": false,
      "loc": "net/bpf/test_run.c:159",
      "file": "net/bpf/test_run.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector",
        "net/bpf/test_run.c:bpf_prog_test_run_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588271728,
      "name": "bpf_ctx_finish.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
  "name": "bpf_ctx_finish",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588891920,
      "name": "bpf_ctx_finish",
      "external": false,
      "loc": "net/bpf/test_run.c:159",
      "file": "net/bpf/test_run.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector",
        "net/bpf/test_run.c:bpf_prog_test_run_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588891920,
      "name": "bpf_ctx_finish.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
  "name": "bpf_ctx_finish",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589034096,
      "name": "bpf_ctx_finish",
      "external": false,
      "loc": "net/bpf/test_run.c:159",
      "file": "net/bpf/test_run.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector",
        "net/bpf/test_run.c:bpf_prog_test_run_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589034096,
      "name": "bpf_ctx_finish.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
int bpf_ctx_finish(const union bpf_attr * kattr, union bpf_attr * uattr, const void * data, u32 size)
```
</details>
</li>
</ul>
