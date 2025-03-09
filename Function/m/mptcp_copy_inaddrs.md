# Function: <code>mptcp_copy_inaddrs</code>

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
void mptcp_copy_inaddrs(struct sock * msk, const struct sock * ssk)
```

```json
{
  "name": "mptcp_copy_inaddrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591075008,
      "name": "mptcp_copy_inaddrs",
      "external": false,
      "loc": "net/mptcp/protocol.c:1388",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_listen",
        "net/mptcp/protocol.c:mptcp_stream_connect",
        "net/mptcp/protocol.c:mptcp_bind",
        "net/mptcp/protocol.c:mptcp_accept"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591075008,
      "name": "mptcp_copy_inaddrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
void mptcp_copy_inaddrs(struct sock * msk, const struct sock * ssk)
```

```json
{
  "name": "mptcp_copy_inaddrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591140496,
      "name": "mptcp_copy_inaddrs",
      "external": false,
      "loc": "net/mptcp/protocol.c:2623",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_stream_accept",
        "net/mptcp/protocol.c:mptcp_listen",
        "net/mptcp/protocol.c:mptcp_stream_connect",
        "net/mptcp/protocol.c:mptcp_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591140496,
      "name": "mptcp_copy_inaddrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
void mptcp_copy_inaddrs(struct sock * msk, const struct sock * ssk)
```

```json
{
  "name": "mptcp_copy_inaddrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591071600,
      "name": "mptcp_copy_inaddrs",
      "external": false,
      "loc": "net/mptcp/protocol.c:2698",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_stream_accept",
        "net/mptcp/protocol.c:mptcp_listen",
        "net/mptcp/protocol.c:mptcp_stream_connect",
        "net/mptcp/protocol.c:mptcp_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591071600,
      "name": "mptcp_copy_inaddrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
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
void mptcp_copy_inaddrs(struct sock * msk, const struct sock * ssk)
```

```json
{
  "name": "mptcp_copy_inaddrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_copy_inaddrs",
      "external": false,
      "loc": "net/mptcp/protocol.c:2755",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_stream_accept",
        "net/mptcp/protocol.c:mptcp_listen",
        "net/mptcp/protocol.c:mptcp_stream_connect",
        "net/mptcp/protocol.c:mptcp_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591918016,
      "name": "mptcp_copy_inaddrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
    },
    {
      "addr": 18446744071592751789,
      "name": "mptcp_copy_inaddrs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
void mptcp_copy_inaddrs(struct sock * msk, const struct sock * ssk)
```

```json
{
  "name": "mptcp_copy_inaddrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_copy_inaddrs",
      "external": false,
      "loc": "net/mptcp/protocol.c:2890",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_stream_accept",
        "net/mptcp/protocol.c:mptcp_listen",
        "net/mptcp/protocol.c:mptcp_stream_connect",
        "net/mptcp/protocol.c:mptcp_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593643120,
      "name": "mptcp_copy_inaddrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 295
    },
    {
      "addr": 18446744071594638727,
      "name": "mptcp_copy_inaddrs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
void mptcp_copy_inaddrs(struct sock * msk, const struct sock * ssk)
```

```json
{
  "name": "mptcp_copy_inaddrs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_copy_inaddrs",
      "external": true,
      "loc": "net/mptcp/protocol.c:2978",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_listen",
        "net/mptcp/protocol.c:mptcp_bind",
        "net/mptcp/protocol.c:mptcp_connect",
        "net/mptcp/subflow.c:subflow_syn_recv_sock",
        "net/mptcp/subflow.c:subflow_syn_recv_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596369551,
      "name": "mptcp_copy_inaddrs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071595600272,
      "name": "mptcp_copy_inaddrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 295
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
void mptcp_copy_inaddrs(struct sock * msk, const struct sock * ssk)
```

```json
{
  "name": "mptcp_copy_inaddrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_copy_inaddrs",
      "external": false,
      "loc": "net/mptcp/protocol.c:3005",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_listen",
        "net/mptcp/protocol.c:mptcp_bind",
        "net/mptcp/protocol.c:mptcp_connect",
        "net/mptcp/protocol.c:mptcp_sk_clone_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596083392,
      "name": "mptcp_copy_inaddrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
    },
    {
      "addr": 18446744071596897912,
      "name": "mptcp_copy_inaddrs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
void mptcp_copy_inaddrs(struct sock * msk, const struct sock * ssk)
```

```json
{
  "name": "mptcp_copy_inaddrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_copy_inaddrs",
      "external": false,
      "loc": "net/mptcp/protocol.c:3103",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_listen",
        "net/mptcp/protocol.c:mptcp_bind",
        "net/mptcp/protocol.c:mptcp_connect",
        "net/mptcp/protocol.c:mptcp_sk_clone_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596953360,
      "name": "mptcp_copy_inaddrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
    },
    {
      "addr": 18446744071597823235,
      "name": "mptcp_copy_inaddrs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
void mptcp_copy_inaddrs(struct sock * msk, const struct sock * ssk)
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
