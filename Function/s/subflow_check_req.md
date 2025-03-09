# Function: <code>subflow_check_req</code>

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
int subflow_check_req(struct request_sock * req, const struct sock * sk_listener, struct sk_buff * skb)
```

```json
{
  "name": "subflow_check_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591176032,
      "name": "subflow_check_req",
      "external": false,
      "loc": "net/mptcp/subflow.c:110",
      "file": "net/mptcp/subflow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:subflow_v6_route_req",
        "net/mptcp/subflow.c:subflow_v4_route_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591176032,
      "name": "subflow_check_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 688
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
int subflow_check_req(struct request_sock * req, const struct sock * sk_listener, struct sk_buff * skb)
```

```json
{
  "name": "subflow_check_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591106208,
      "name": "subflow_check_req",
      "external": false,
      "loc": "net/mptcp/subflow.c:135",
      "file": "net/mptcp/subflow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:subflow_v6_route_req",
        "net/mptcp/subflow.c:subflow_v4_route_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591106208,
      "name": "subflow_check_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1101
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
int subflow_check_req(struct request_sock * req, const struct sock * sk_listener, struct sk_buff * skb)
```

```json
{
  "name": "subflow_check_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591950576,
      "name": "subflow_check_req",
      "external": false,
      "loc": "net/mptcp/subflow.c:137",
      "file": "net/mptcp/subflow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:subflow_v6_route_req",
        "net/mptcp/subflow.c:subflow_v4_route_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591950576,
      "name": "subflow_check_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 994
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
int subflow_check_req(struct request_sock * req, const struct sock * sk_listener, struct sk_buff * skb)
```

```json
{
  "name": "subflow_check_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593677488,
      "name": "subflow_check_req",
      "external": false,
      "loc": "net/mptcp/subflow.c:139",
      "file": "net/mptcp/subflow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:subflow_v6_route_req",
        "net/mptcp/subflow.c:subflow_v4_route_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593677488,
      "name": "subflow_check_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1041
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
int subflow_check_req(struct request_sock * req, const struct sock * sk_listener, struct sk_buff * skb)
```

```json
{
  "name": "subflow_check_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595609824,
      "name": "subflow_check_req",
      "external": false,
      "loc": "net/mptcp/subflow.c:138",
      "file": "net/mptcp/subflow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:subflow_v6_route_req",
        "net/mptcp/subflow.c:subflow_v4_route_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595609824,
      "name": "subflow_check_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1041
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
int subflow_check_req(struct request_sock * req, const struct sock * sk_listener, struct sk_buff * skb)
```

```json
{
  "name": "subflow_check_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596118448,
      "name": "subflow_check_req",
      "external": false,
      "loc": "net/mptcp/subflow.c:139",
      "file": "net/mptcp/subflow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:subflow_v6_route_req",
        "net/mptcp/subflow.c:subflow_v4_route_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596118448,
      "name": "subflow_check_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1041
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
int subflow_check_req(struct request_sock * req, const struct sock * sk_listener, struct sk_buff * skb)
```

```json
{
  "name": "subflow_check_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596992000,
      "name": "subflow_check_req",
      "external": false,
      "loc": "net/mptcp/subflow.c:139",
      "file": "net/mptcp/subflow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:subflow_v6_route_req",
        "net/mptcp/subflow.c:subflow_v4_route_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596992000,
      "name": "subflow_check_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1041
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
int subflow_check_req(struct request_sock * req, const struct sock * sk_listener, struct sk_buff * skb)
```
</details>
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
