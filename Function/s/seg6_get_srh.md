# Function: <code>seg6_get_srh</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
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
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct ipv6_sr_hdr * seg6_get_srh(struct sk_buff * skb, int flags)
```

```json
{
  "name": "seg6_get_srh",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591657680,
      "name": "seg6_get_srh",
      "external": true,
      "loc": "net/ipv6/seg6.c:78",
      "file": "net/ipv6/seg6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/seg6.c:seg6_icmp_srh",
        "net/ipv6/seg6_local.c:input_action_end_bpf",
        "net/ipv6/seg6_local.c:input_action_end_b6_encap",
        "net/ipv6/seg6_local.c:input_action_end_t",
        "net/ipv6/seg6_local.c:input_action_end_x",
        "net/ipv6/seg6_local.c:input_action_end",
        "net/ipv6/seg6_local.c:decap_and_validate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591657680,
      "name": "seg6_get_srh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 259
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
struct ipv6_sr_hdr * seg6_get_srh(struct sk_buff * skb, int flags)
```

```json
{
  "name": "seg6_get_srh",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593352432,
      "name": "seg6_get_srh",
      "external": true,
      "loc": "net/ipv6/seg6.c:78",
      "file": "net/ipv6/seg6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/seg6.c:seg6_icmp_srh",
        "net/ipv6/seg6_local.c:input_action_end_bpf",
        "net/ipv6/seg6_local.c:input_action_end_b6_encap",
        "net/ipv6/seg6_local.c:input_action_end_t",
        "net/ipv6/seg6_local.c:input_action_end_x",
        "net/ipv6/seg6_local.c:input_action_end",
        "net/ipv6/seg6_local.c:decap_and_validate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593352432,
      "name": "seg6_get_srh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
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
struct ipv6_sr_hdr * seg6_get_srh(struct sk_buff * skb, int flags)
```

```json
{
  "name": "seg6_get_srh",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595259120,
      "name": "seg6_get_srh",
      "external": true,
      "loc": "net/ipv6/seg6.c:78",
      "file": "net/ipv6/seg6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/seg6.c:seg6_icmp_srh",
        "net/ipv6/seg6_local.c:input_action_end_bpf",
        "net/ipv6/seg6_local.c:input_action_end_b6_encap",
        "net/ipv6/seg6_local.c:input_action_end_t",
        "net/ipv6/seg6_local.c:input_action_end_x",
        "net/ipv6/seg6_local.c:decap_and_validate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595259120,
      "name": "seg6_get_srh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
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
struct ipv6_sr_hdr * seg6_get_srh(struct sk_buff * skb, int flags)
```

```json
{
  "name": "seg6_get_srh",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595654480,
      "name": "seg6_get_srh",
      "external": true,
      "loc": "net/ipv6/seg6.c:78",
      "file": "net/ipv6/seg6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/seg6.c:seg6_icmp_srh",
        "net/ipv6/seg6_local.c:input_action_end_bpf",
        "net/ipv6/seg6_local.c:input_action_end_b6_encap",
        "net/ipv6/seg6_local.c:input_action_end_t",
        "net/ipv6/seg6_local.c:input_action_end_x",
        "net/ipv6/seg6_local.c:end_flv8986_core",
        "net/ipv6/seg6_local.c:decap_and_validate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595654480,
      "name": "seg6_get_srh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
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
struct ipv6_sr_hdr * seg6_get_srh(struct sk_buff * skb, int flags)
```

```json
{
  "name": "seg6_get_srh",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596502128,
      "name": "seg6_get_srh",
      "external": true,
      "loc": "net/ipv6/seg6.c:78",
      "file": "net/ipv6/seg6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/seg6.c:seg6_icmp_srh",
        "net/ipv6/seg6_local.c:input_action_end_bpf",
        "net/ipv6/seg6_local.c:input_action_end_b6_encap",
        "net/ipv6/seg6_local.c:input_action_end_t",
        "net/ipv6/seg6_local.c:end_flv8986_core",
        "net/ipv6/seg6_local.c:input_action_end_x_core",
        "net/ipv6/seg6_local.c:decap_and_validate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596502128,
      "name": "seg6_get_srh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
struct ipv6_sr_hdr * seg6_get_srh(struct sk_buff * skb, int flags)
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
