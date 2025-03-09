# Function: <code>__secpath_destroy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __secpath_destroy(struct sec_path * sp)
```

```json
{
  "name": "__secpath_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586953072,
      "name": "__secpath_destroy",
      "external": true,
      "loc": "net/xfrm/xfrm_input.c:96",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_release_head_state",
        "net/core/skbuff.c:skb_scrub_packet",
        "net/ipv4/ip_tunnel_core.c:iptunnel_pull_header",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/ipv6/xfrm6_input.c:xfrm6_input_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586953072,
      "name": "__secpath_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void __secpath_destroy(struct sec_path * sp)
```

```json
{
  "name": "__secpath_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587399312,
      "name": "__secpath_destroy",
      "external": true,
      "loc": "net/xfrm/xfrm_input.c:96",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_scrub_packet",
        "net/core/skbuff.c:skb_release_head_state",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/ipv6/xfrm6_input.c:xfrm6_input_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587399312,
      "name": "__secpath_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void __secpath_destroy(struct sec_path * sp)
```

```json
{
  "name": "__secpath_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587602544,
      "name": "__secpath_destroy",
      "external": true,
      "loc": "net/xfrm/xfrm_input.c:96",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_scrub_packet",
        "net/core/skbuff.c:skb_release_head_state",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/ipv6/xfrm6_input.c:xfrm6_input_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587602544,
      "name": "__secpath_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void __secpath_destroy(struct sec_path * sp)
```

```json
{
  "name": "__secpath_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587749456,
      "name": "__secpath_destroy",
      "external": true,
      "loc": "net/xfrm/xfrm_input.c:90",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_scrub_packet",
        "net/core/skbuff.c:skb_release_head_state",
        "net/core/dev.c:napi_skb_free_stolen_head",
        "net/xfrm/xfrm_input.c:secpath_set",
        "net/xfrm/xfrm_output.c:xfrm_output",
        "net/xfrm/xfrm_output.c:xfrm_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587749456,
      "name": "__secpath_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void __secpath_destroy(struct sec_path * sp)
```

```json
{
  "name": "__secpath_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588277472,
      "name": "__secpath_destroy",
      "external": true,
      "loc": "net/xfrm/xfrm_input.c:107",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_release_head_state",
        "net/core/dev.c:napi_skb_free_stolen_head",
        "net/xfrm/xfrm_input.c:secpath_set",
        "net/xfrm/xfrm_output.c:xfrm_output",
        "net/xfrm/xfrm_output.c:xfrm_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588277472,
      "name": "__secpath_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void __secpath_destroy(struct sec_path * sp)
```

```json
{
  "name": "__secpath_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588632496,
      "name": "__secpath_destroy",
      "external": true,
      "loc": "net/xfrm/xfrm_input.c:114",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_release_head_state",
        "net/core/dev.c:napi_skb_free_stolen_head",
        "net/xfrm/xfrm_input.c:secpath_set",
        "net/xfrm/xfrm_output.c:xfrm_output",
        "net/xfrm/xfrm_output.c:xfrm_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588632496,
      "name": "__secpath_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
    }
  ]
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
void __secpath_destroy(struct sec_path * sp)
```
</details>
</li>
</ul>
