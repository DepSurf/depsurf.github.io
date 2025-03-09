# Function: <code>mptcp_get_options</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void mptcp_get_options(const struct sk_buff * skb, struct mptcp_options_received * mp_opt)
```

```json
{
  "name": "mptcp_get_options",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591104160,
      "name": "mptcp_get_options",
      "external": true,
      "loc": "net/mptcp/options.c:288",
      "file": "net/mptcp/options.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:subflow_syn_recv_sock",
        "net/mptcp/subflow.c:subflow_syn_recv_sock",
        "net/mptcp/subflow.c:subflow_finish_connect",
        "net/mptcp/subflow.c:subflow_init_req",
        "net/mptcp/options.c:mptcp_incoming_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591104160,
      "name": "mptcp_get_options",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
void mptcp_get_options(const struct sk_buff * skb, struct mptcp_options_received * mp_opt)
```

```json
{
  "name": "mptcp_get_options",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591185392,
      "name": "mptcp_get_options",
      "external": true,
      "loc": "net/mptcp/options.c:300",
      "file": "net/mptcp/options.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:subflow_syn_recv_sock",
        "net/mptcp/subflow.c:subflow_syn_recv_sock",
        "net/mptcp/subflow.c:subflow_finish_connect",
        "net/mptcp/subflow.c:mptcp_subflow_init_cookie_req",
        "net/mptcp/subflow.c:subflow_check_req",
        "net/mptcp/options.c:mptcp_incoming_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591185392,
      "name": "mptcp_get_options",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
void mptcp_get_options(const struct sock * sk, const struct sk_buff * skb, struct mptcp_options_received * mp_opt)
```

```json
{
  "name": "mptcp_get_options",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591121504,
      "name": "mptcp_get_options",
      "external": true,
      "loc": "net/mptcp/options.c:326",
      "file": "net/mptcp/options.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:subflow_syn_recv_sock",
        "net/mptcp/subflow.c:subflow_syn_recv_sock",
        "net/mptcp/subflow.c:subflow_finish_connect",
        "net/mptcp/subflow.c:mptcp_subflow_init_cookie_req",
        "net/mptcp/subflow.c:subflow_check_req",
        "net/mptcp/options.c:mptcp_incoming_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591121504,
      "name": "mptcp_get_options",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
void mptcp_get_options(const struct sock * sk, const struct sk_buff * skb, struct mptcp_options_received * mp_opt)
```

```json
{
  "name": "mptcp_get_options",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591968320,
      "name": "mptcp_get_options",
      "external": true,
      "loc": "net/mptcp/options.c:356",
      "file": "net/mptcp/options.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:subflow_syn_recv_sock",
        "net/mptcp/subflow.c:subflow_syn_recv_sock",
        "net/mptcp/subflow.c:subflow_finish_connect",
        "net/mptcp/subflow.c:mptcp_subflow_init_cookie_req",
        "net/mptcp/subflow.c:subflow_check_req",
        "net/mptcp/options.c:mptcp_incoming_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591968320,
      "name": "mptcp_get_options",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
void mptcp_get_options(const struct sk_buff * skb, struct mptcp_options_received * mp_opt)
```

```json
{
  "name": "mptcp_get_options",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593697248,
      "name": "mptcp_get_options",
      "external": true,
      "loc": "net/mptcp/options.c:359",
      "file": "net/mptcp/options.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:subflow_syn_recv_sock",
        "net/mptcp/subflow.c:subflow_syn_recv_sock",
        "net/mptcp/subflow.c:subflow_finish_connect",
        "net/mptcp/subflow.c:mptcp_subflow_init_cookie_req",
        "net/mptcp/subflow.c:subflow_check_req",
        "net/mptcp/options.c:mptcp_incoming_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593697248,
      "name": "mptcp_get_options",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
void mptcp_get_options(const struct sk_buff * skb, struct mptcp_options_received * mp_opt)
```

```json
{
  "name": "mptcp_get_options",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595630848,
      "name": "mptcp_get_options",
      "external": true,
      "loc": "net/mptcp/options.c:364",
      "file": "net/mptcp/options.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:subflow_syn_recv_sock",
        "net/mptcp/subflow.c:subflow_syn_recv_sock",
        "net/mptcp/subflow.c:subflow_finish_connect",
        "net/mptcp/subflow.c:mptcp_subflow_init_cookie_req",
        "net/mptcp/subflow.c:subflow_check_req",
        "net/mptcp/options.c:mptcp_incoming_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595630848,
      "name": "mptcp_get_options",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
void mptcp_get_options(const struct sk_buff * skb, struct mptcp_options_received * mp_opt)
```

```json
{
  "name": "mptcp_get_options",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596139200,
      "name": "mptcp_get_options",
      "external": true,
      "loc": "net/mptcp/options.c:364",
      "file": "net/mptcp/options.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:subflow_syn_recv_sock",
        "net/mptcp/subflow.c:subflow_syn_recv_sock",
        "net/mptcp/subflow.c:subflow_finish_connect",
        "net/mptcp/subflow.c:mptcp_subflow_init_cookie_req",
        "net/mptcp/subflow.c:subflow_check_req",
        "net/mptcp/options.c:mptcp_incoming_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596139200,
      "name": "mptcp_get_options",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
void mptcp_get_options(const struct sk_buff * skb, struct mptcp_options_received * mp_opt)
```

```json
{
  "name": "mptcp_get_options",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597012912,
      "name": "mptcp_get_options",
      "external": true,
      "loc": "net/mptcp/options.c:365",
      "file": "net/mptcp/options.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:subflow_syn_recv_sock",
        "net/mptcp/subflow.c:subflow_syn_recv_sock",
        "net/mptcp/subflow.c:subflow_finish_connect",
        "net/mptcp/subflow.c:mptcp_subflow_init_cookie_req",
        "net/mptcp/subflow.c:subflow_check_req",
        "net/mptcp/options.c:mptcp_incoming_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597012912,
      "name": "mptcp_get_options",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
void mptcp_get_options(const struct sk_buff * skb, struct mptcp_options_received * mp_opt)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct sock * sk</code>
</li>
<li>
<b>Param reordered. </b>
<code>skb, mp_opt</code> ➡️ <code>sk, skb, mp_opt</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>const struct sock * sk</code>
</li>
<li>
<b>Param reordered. </b>
<code>sk, skb, mp_opt</code> ➡️ <code>skb, mp_opt</code>
</li>
</ul>
</details>
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
