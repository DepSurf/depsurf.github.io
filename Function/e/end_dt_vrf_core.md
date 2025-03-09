# Function: <code>end_dt_vrf_core</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct sk_buff * end_dt_vrf_core(struct sk_buff * skb, struct seg6_local_lwt * slwt)
```

```json
{
  "name": "end_dt_vrf_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590963968,
      "name": "end_dt_vrf_core",
      "external": false,
      "loc": "net/ipv6/seg6_local.c:595",
      "file": "net/ipv6/seg6_local.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/seg6_local.c:input_action_end_dt6",
        "net/ipv6/seg6_local.c:input_action_end_dt4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590963968,
      "name": "end_dt_vrf_core",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
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
struct sk_buff * end_dt_vrf_core(struct sk_buff * skb, struct seg6_local_lwt * slwt)
```

```json
{
  "name": "end_dt_vrf_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590894576,
      "name": "end_dt_vrf_core",
      "external": false,
      "loc": "net/ipv6/seg6_local.c:624",
      "file": "net/ipv6/seg6_local.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/seg6_local.c:input_action_end_dt6",
        "net/ipv6/seg6_local.c:input_action_end_dt4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590894576,
      "name": "end_dt_vrf_core",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
struct sk_buff * end_dt_vrf_core(struct sk_buff * skb, struct seg6_local_lwt * slwt, u16 family)
```

```json
{
  "name": "end_dt_vrf_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "end_dt_vrf_core",
      "external": false,
      "loc": "net/ipv6/seg6_local.c:614",
      "file": "net/ipv6/seg6_local.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/seg6_local.c:input_action_end_dt6",
        "net/ipv6/seg6_local.c:input_action_end_dt4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591726832,
      "name": "end_dt_vrf_core",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 454
    },
    {
      "addr": 18446744071592744504,
      "name": "end_dt_vrf_core.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
struct sk_buff * end_dt_vrf_core(struct sk_buff * skb, struct seg6_local_lwt * slwt, u16 family)
```

```json
{
  "name": "end_dt_vrf_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "end_dt_vrf_core",
      "external": false,
      "loc": "net/ipv6/seg6_local.c:616",
      "file": "net/ipv6/seg6_local.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/seg6_local.c:input_action_end_dt6",
        "net/ipv6/seg6_local.c:input_action_end_dt4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593428448,
      "name": "end_dt_vrf_core",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 511
    },
    {
      "addr": 18446744071594631084,
      "name": "end_dt_vrf_core.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
struct sk_buff * end_dt_vrf_core(struct sk_buff * skb, struct seg6_local_lwt * slwt, u16 family)
```

```json
{
  "name": "end_dt_vrf_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "end_dt_vrf_core",
      "external": false,
      "loc": "net/ipv6/seg6_local.c:741",
      "file": "net/ipv6/seg6_local.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/seg6_local.c:input_action_end_dt6",
        "net/ipv6/seg6_local.c:input_action_end_dt4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595341600,
      "name": "end_dt_vrf_core",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 526
    },
    {
      "addr": 18446744071596364628,
      "name": "end_dt_vrf_core.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
struct sk_buff * end_dt_vrf_core(struct sk_buff * skb, struct seg6_local_lwt * slwt, u16 family)
```

```json
{
  "name": "end_dt_vrf_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "end_dt_vrf_core",
      "external": false,
      "loc": "net/ipv6/seg6_local.c:1068",
      "file": "net/ipv6/seg6_local.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/seg6_local.c:input_action_end_dt6",
        "net/ipv6/seg6_local.c:input_action_end_dt4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595736544,
      "name": "end_dt_vrf_core",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 504
    },
    {
      "addr": 18446744071596892645,
      "name": "end_dt_vrf_core.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
struct sk_buff * end_dt_vrf_core(struct sk_buff * skb, struct seg6_local_lwt * slwt, u16 family)
```

```json
{
  "name": "end_dt_vrf_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "end_dt_vrf_core",
      "external": false,
      "loc": "net/ipv6/seg6_local.c:1128",
      "file": "net/ipv6/seg6_local.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/seg6_local.c:input_action_end_dt6",
        "net/ipv6/seg6_local.c:input_action_end_dt4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596584368,
      "name": "end_dt_vrf_core",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 500
    },
    {
      "addr": 18446744071597817269,
      "name": "end_dt_vrf_core.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
struct sk_buff * end_dt_vrf_core(struct sk_buff * skb, struct seg6_local_lwt * slwt)
```
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u16 family</code>
</li>
</ul>
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
