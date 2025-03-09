# Function: <code>mptcp_sendmsg_frag</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mptcp_sendmsg_frag",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591077376,
      "name": "mptcp_sendmsg_frag",
      "external": false,
      "loc": "net/mptcp/protocol.c:531",
      "file": "net/mptcp/protocol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:mptcp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591077376,
      "name": "mptcp_sendmsg_frag.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1549
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
int mptcp_sendmsg_frag(struct sock * sk, struct sock * ssk, struct mptcp_data_frag * dfrag, struct mptcp_sendmsg_info * info)
```

```json
{
  "name": "mptcp_sendmsg_frag",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591141392,
      "name": "mptcp_sendmsg_frag",
      "external": false,
      "loc": "net/mptcp/protocol.c:1249",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:__mptcp_subflow_push_pending",
        "net/mptcp/protocol.c:__mptcp_push_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591141392,
      "name": "mptcp_sendmsg_frag",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 945
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
int mptcp_sendmsg_frag(struct sock * sk, struct sock * ssk, struct mptcp_data_frag * dfrag, struct mptcp_sendmsg_info * info)
```

```json
{
  "name": "mptcp_sendmsg_frag",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591072704,
      "name": "mptcp_sendmsg_frag",
      "external": false,
      "loc": "net/mptcp/protocol.c:1301",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:__mptcp_retrans",
        "net/mptcp/protocol.c:__mptcp_subflow_push_pending",
        "net/mptcp/protocol.c:__mptcp_push_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591072704,
      "name": "mptcp_sendmsg_frag",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 947
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
int mptcp_sendmsg_frag(struct sock * sk, struct sock * ssk, struct mptcp_data_frag * dfrag, struct mptcp_sendmsg_info * info)
```

```json
{
  "name": "mptcp_sendmsg_frag",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_sendmsg_frag",
      "external": false,
      "loc": "net/mptcp/protocol.c:1285",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:__mptcp_retrans",
        "net/mptcp/protocol.c:__mptcp_subflow_push_pending",
        "net/mptcp/protocol.c:__mptcp_push_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591922096,
      "name": "mptcp_sendmsg_frag",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1032
    },
    {
      "addr": 18446744071592752089,
      "name": "mptcp_sendmsg_frag.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
int mptcp_sendmsg_frag(struct sock * sk, struct sock * ssk, struct mptcp_data_frag * dfrag, struct mptcp_sendmsg_info * info)
```

```json
{
  "name": "mptcp_sendmsg_frag",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_sendmsg_frag",
      "external": false,
      "loc": "net/mptcp/protocol.c:1257",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:__mptcp_retrans",
        "net/mptcp/protocol.c:__mptcp_subflow_push_pending",
        "net/mptcp/protocol.c:__mptcp_push_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593651744,
      "name": "mptcp_sendmsg_frag",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2551
    },
    {
      "addr": 18446744071594639434,
      "name": "mptcp_sendmsg_frag.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
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
int mptcp_sendmsg_frag(struct sock * sk, struct sock * ssk, struct mptcp_data_frag * dfrag, struct mptcp_sendmsg_info * info)
```

```json
{
  "name": "mptcp_sendmsg_frag",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_sendmsg_frag",
      "external": false,
      "loc": "net/mptcp/protocol.c:1218",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:__mptcp_retrans",
        "net/mptcp/protocol.c:__mptcp_subflow_push_pending",
        "net/mptcp/protocol.c:__mptcp_push_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595579872,
      "name": "mptcp_sendmsg_frag",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2365
    },
    {
      "addr": 18446744071596368637,
      "name": "mptcp_sendmsg_frag.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
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
int mptcp_sendmsg_frag(struct sock * sk, struct sock * ssk, struct mptcp_data_frag * dfrag, struct mptcp_sendmsg_info * info)
```

```json
{
  "name": "mptcp_sendmsg_frag",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_sendmsg_frag",
      "external": false,
      "loc": "net/mptcp/protocol.c:1189",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:__mptcp_retrans",
        "net/mptcp/protocol.c:__mptcp_subflow_push_pending",
        "net/mptcp/protocol.c:__mptcp_push_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596088016,
      "name": "mptcp_sendmsg_frag",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2593
    },
    {
      "addr": 18446744071596898300,
      "name": "mptcp_sendmsg_frag.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
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
int mptcp_sendmsg_frag(struct sock * sk, struct sock * ssk, struct mptcp_data_frag * dfrag, struct mptcp_sendmsg_info * info)
```

```json
{
  "name": "mptcp_sendmsg_frag",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_sendmsg_frag",
      "external": false,
      "loc": "net/mptcp/protocol.c:1221",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:__mptcp_retrans",
        "net/mptcp/protocol.c:__subflow_push_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596956752,
      "name": "mptcp_sendmsg_frag",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2628
    },
    {
      "addr": 18446744071597823425,
      "name": "mptcp_sendmsg_frag.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
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
int mptcp_sendmsg_frag(struct sock * sk, struct sock * ssk, struct mptcp_data_frag * dfrag, struct mptcp_sendmsg_info * info)
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
