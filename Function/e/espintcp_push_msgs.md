# Function: <code>espintcp_push_msgs</code>

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
int espintcp_push_msgs(struct sock * sk, int flags)
```

```json
{
  "name": "espintcp_push_msgs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590522048,
      "name": "espintcp_push_msgs",
      "external": false,
      "loc": "net/xfrm/espintcp.c:248",
      "file": "net/xfrm/espintcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/espintcp.c:espintcp_tx_work",
        "net/xfrm/espintcp.c:espintcp_sendmsg",
        "net/xfrm/espintcp.c:espintcp_sendmsg",
        "net/xfrm/espintcp.c:espintcp_push_skb",
        "net/xfrm/espintcp.c:espintcp_push_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590522048,
      "name": "espintcp_push_msgs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
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
int espintcp_push_msgs(struct sock * sk, int flags)
```

```json
{
  "name": "espintcp_push_msgs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590581936,
      "name": "espintcp_push_msgs",
      "external": false,
      "loc": "net/xfrm/espintcp.c:252",
      "file": "net/xfrm/espintcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/espintcp.c:espintcp_tx_work",
        "net/xfrm/espintcp.c:espintcp_sendmsg",
        "net/xfrm/espintcp.c:espintcp_sendmsg",
        "net/xfrm/espintcp.c:espintcp_push_skb",
        "net/xfrm/espintcp.c:espintcp_push_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590581936,
      "name": "espintcp_push_msgs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
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
int espintcp_push_msgs(struct sock * sk, int flags)
```

```json
{
  "name": "espintcp_push_msgs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590507488,
      "name": "espintcp_push_msgs",
      "external": false,
      "loc": "net/xfrm/espintcp.c:252",
      "file": "net/xfrm/espintcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/espintcp.c:espintcp_tx_work",
        "net/xfrm/espintcp.c:espintcp_sendmsg",
        "net/xfrm/espintcp.c:espintcp_sendmsg",
        "net/xfrm/espintcp.c:espintcp_push_skb",
        "net/xfrm/espintcp.c:espintcp_push_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590507488,
      "name": "espintcp_push_msgs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
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
int espintcp_push_msgs(struct sock * sk, int flags)
```

```json
{
  "name": "espintcp_push_msgs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "espintcp_push_msgs",
      "external": false,
      "loc": "net/xfrm/espintcp.c:252",
      "file": "net/xfrm/espintcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/espintcp.c:espintcp_tx_work",
        "net/xfrm/espintcp.c:espintcp_sendmsg",
        "net/xfrm/espintcp.c:espintcp_sendmsg",
        "net/xfrm/espintcp.c:espintcp_push_skb",
        "net/xfrm/espintcp.c:espintcp_push_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591313456,
      "name": "espintcp_push_msgs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 307
    },
    {
      "addr": 18446744071592734659,
      "name": "espintcp_push_msgs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int espintcp_push_msgs(struct sock * sk, int flags)
```

```json
{
  "name": "espintcp_push_msgs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "espintcp_push_msgs",
      "external": false,
      "loc": "net/xfrm/espintcp.c:250",
      "file": "net/xfrm/espintcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/espintcp.c:espintcp_tx_work",
        "net/xfrm/espintcp.c:espintcp_sendmsg",
        "net/xfrm/espintcp.c:espintcp_sendmsg",
        "net/xfrm/espintcp.c:espintcp_push_skb",
        "net/xfrm/espintcp.c:espintcp_push_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592981648,
      "name": "espintcp_push_msgs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 353
    },
    {
      "addr": 18446744071594621214,
      "name": "espintcp_push_msgs.cold",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int espintcp_push_msgs(struct sock * sk, int flags)
```

```json
{
  "name": "espintcp_push_msgs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "espintcp_push_msgs",
      "external": false,
      "loc": "net/xfrm/espintcp.c:250",
      "file": "net/xfrm/espintcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/espintcp.c:espintcp_tx_work",
        "net/xfrm/espintcp.c:espintcp_sendmsg",
        "net/xfrm/espintcp.c:espintcp_sendmsg",
        "net/xfrm/espintcp.c:espintcp_push_skb",
        "net/xfrm/espintcp.c:espintcp_push_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594870032,
      "name": "espintcp_push_msgs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 353
    },
    {
      "addr": 18446744071596355959,
      "name": "espintcp_push_msgs.cold",
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
int espintcp_push_msgs(struct sock * sk, int flags)
```

```json
{
  "name": "espintcp_push_msgs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "espintcp_push_msgs",
      "external": false,
      "loc": "net/xfrm/espintcp.c:257",
      "file": "net/xfrm/espintcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/espintcp.c:espintcp_tx_work",
        "net/xfrm/espintcp.c:espintcp_sendmsg",
        "net/xfrm/espintcp.c:espintcp_sendmsg",
        "net/xfrm/espintcp.c:espintcp_push_skb",
        "net/xfrm/espintcp.c:espintcp_push_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595262848,
      "name": "espintcp_push_msgs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 353
    },
    {
      "addr": 18446744071596884853,
      "name": "espintcp_push_msgs.cold",
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
int espintcp_push_msgs(struct sock * sk, int flags)
```

```json
{
  "name": "espintcp_push_msgs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "espintcp_push_msgs",
      "external": false,
      "loc": "net/xfrm/espintcp.c:257",
      "file": "net/xfrm/espintcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/espintcp.c:espintcp_tx_work",
        "net/xfrm/espintcp.c:espintcp_sendmsg",
        "net/xfrm/espintcp.c:espintcp_sendmsg",
        "net/xfrm/espintcp.c:espintcp_push_skb",
        "net/xfrm/espintcp.c:espintcp_push_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596103280,
      "name": "espintcp_push_msgs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 353
    },
    {
      "addr": 18446744071597809470,
      "name": "espintcp_push_msgs.cold",
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int espintcp_push_msgs(struct sock * sk, int flags)
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
