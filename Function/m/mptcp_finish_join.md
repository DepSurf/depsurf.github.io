# Function: <code>mptcp_finish_join</code>

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
bool mptcp_finish_join(struct sock * sk)
```

```json
{
  "name": "mptcp_finish_join",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591090704,
      "name": "mptcp_finish_join",
      "external": true,
      "loc": "net/mptcp/protocol.c:1703",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:subflow_syn_recv_sock",
        "net/mptcp/subflow.c:subflow_finish_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591090704,
      "name": "mptcp_finish_join",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 371
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
bool mptcp_finish_join(struct sock * ssk)
```

```json
{
  "name": "mptcp_finish_join",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591169168,
      "name": "mptcp_finish_join",
      "external": true,
      "loc": "net/mptcp/protocol.c:3067",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:subflow_syn_recv_sock",
        "net/mptcp/subflow.c:subflow_finish_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591169168,
      "name": "mptcp_finish_join",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 456
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
bool mptcp_finish_join(struct sock * ssk)
```

```json
{
  "name": "mptcp_finish_join",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591103744,
      "name": "mptcp_finish_join",
      "external": true,
      "loc": "net/mptcp/protocol.c:3046",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:subflow_syn_recv_sock",
        "net/mptcp/subflow.c:subflow_finish_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591103744,
      "name": "mptcp_finish_join",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 486
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
bool mptcp_finish_join(struct sock * ssk)
```

```json
{
  "name": "mptcp_finish_join",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_finish_join",
      "external": true,
      "loc": "net/mptcp/protocol.c:3139",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:subflow_syn_recv_sock",
        "net/mptcp/subflow.c:subflow_finish_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592753408,
      "name": "mptcp_finish_join.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071591947712,
      "name": "mptcp_finish_join",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 528
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
bool mptcp_finish_join(struct sock * ssk)
```

```json
{
  "name": "mptcp_finish_join",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_finish_join",
      "external": true,
      "loc": "net/mptcp/protocol.c:3317",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:subflow_syn_recv_sock",
        "net/mptcp/subflow.c:subflow_finish_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594640411,
      "name": "mptcp_finish_join.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071593674112,
      "name": "mptcp_finish_join",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 684
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
bool mptcp_finish_join(struct sock * ssk)
```

```json
{
  "name": "mptcp_finish_join",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_finish_join",
      "external": true,
      "loc": "net/mptcp/protocol.c:3390",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:subflow_syn_recv_sock",
        "net/mptcp/subflow.c:subflow_finish_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596369903,
      "name": "mptcp_finish_join.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071595606064,
      "name": "mptcp_finish_join",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 684
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
bool mptcp_finish_join(struct sock * ssk)
```

```json
{
  "name": "mptcp_finish_join",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_finish_join",
      "external": true,
      "loc": "net/mptcp/protocol.c:3456",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:subflow_syn_recv_sock",
        "net/mptcp/subflow.c:subflow_finish_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596899181,
      "name": "mptcp_finish_join.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071596114944,
      "name": "mptcp_finish_join",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 554
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
bool mptcp_finish_join(struct sock * ssk)
```

```json
{
  "name": "mptcp_finish_join",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_finish_join",
      "external": true,
      "loc": "net/mptcp/protocol.c:3549",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:subflow_syn_recv_sock",
        "net/mptcp/subflow.c:subflow_finish_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597824571,
      "name": "mptcp_finish_join.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071596987808,
      "name": "mptcp_finish_join",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 851
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
bool mptcp_finish_join(struct sock * sk)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct sock * ssk</code>
</li>
<li>
<b>Param removed. </b>
<code>struct sock * sk</code>
</li>
</ul>
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
