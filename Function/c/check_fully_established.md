# Function: <code>check_fully_established</code>

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
  "name": "check_fully_established",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591105071,
      "name": "check_fully_established",
      "external": false,
      "loc": "net/mptcp/options.c:677",
      "file": "net/mptcp/options.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/options.c:mptcp_incoming_options"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
bool check_fully_established(struct mptcp_sock * msk, struct sock * ssk, struct mptcp_subflow_context * subflow, struct sk_buff * skb, struct mptcp_options_received * mp_opt)
```

```json
{
  "name": "check_fully_established",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_fully_established",
      "external": false,
      "loc": "net/mptcp/options.c:760",
      "file": "net/mptcp/options.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/options.c:mptcp_incoming_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591183648,
      "name": "check_fully_established",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 510
    },
    {
      "addr": 18446744071591640900,
      "name": "check_fully_established.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
bool check_fully_established(struct mptcp_sock * msk, struct sock * ssk, struct mptcp_subflow_context * subflow, struct sk_buff * skb, struct mptcp_options_received * mp_opt)
```

```json
{
  "name": "check_fully_established",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_fully_established",
      "external": false,
      "loc": "net/mptcp/options.c:814",
      "file": "net/mptcp/options.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/options.c:mptcp_incoming_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591119888,
      "name": "check_fully_established",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 495
    },
    {
      "addr": 18446744071591584395,
      "name": "check_fully_established.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
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
bool check_fully_established(struct mptcp_sock * msk, struct sock * ssk, struct mptcp_subflow_context * subflow, struct sk_buff * skb, struct mptcp_options_received * mp_opt)
```

```json
{
  "name": "check_fully_established",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_fully_established",
      "external": false,
      "loc": "net/mptcp/options.c:893",
      "file": "net/mptcp/options.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/options.c:mptcp_incoming_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591966208,
      "name": "check_fully_established",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 569
    },
    {
      "addr": 18446744071592754312,
      "name": "check_fully_established.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
bool check_fully_established(struct mptcp_sock * msk, struct sock * ssk, struct mptcp_subflow_context * subflow, struct sk_buff * skb, struct mptcp_options_received * mp_opt)
```

```json
{
  "name": "check_fully_established",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_fully_established",
      "external": false,
      "loc": "net/mptcp/options.c:919",
      "file": "net/mptcp/options.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/options.c:mptcp_incoming_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593694464,
      "name": "check_fully_established",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 640
    },
    {
      "addr": 18446744071594641339,
      "name": "check_fully_established.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
bool check_fully_established(struct mptcp_sock * msk, struct sock * ssk, struct mptcp_subflow_context * subflow, struct sk_buff * skb, struct mptcp_options_received * mp_opt)
```

```json
{
  "name": "check_fully_established",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_fully_established",
      "external": false,
      "loc": "net/mptcp/options.c:924",
      "file": "net/mptcp/options.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/options.c:mptcp_incoming_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595627872,
      "name": "check_fully_established",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 728
    },
    {
      "addr": 18446744071596370762,
      "name": "check_fully_established.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
bool check_fully_established(struct mptcp_sock * msk, struct sock * ssk, struct mptcp_subflow_context * subflow, struct sk_buff * skb, struct mptcp_options_received * mp_opt)
```

```json
{
  "name": "check_fully_established",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_fully_established",
      "external": false,
      "loc": "net/mptcp/options.c:924",
      "file": "net/mptcp/options.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/options.c:mptcp_incoming_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596136240,
      "name": "check_fully_established",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 689
    },
    {
      "addr": 18446744071596900076,
      "name": "check_fully_established.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
bool check_fully_established(struct mptcp_sock * msk, struct sock * ssk, struct mptcp_subflow_context * subflow, struct sk_buff * skb, struct mptcp_options_received * mp_opt)
```

```json
{
  "name": "check_fully_established",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_fully_established",
      "external": false,
      "loc": "net/mptcp/options.c:925",
      "file": "net/mptcp/options.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/options.c:mptcp_incoming_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597011024,
      "name": "check_fully_established",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 694
    },
    {
      "addr": 18446744071597825414,
      "name": "check_fully_established.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
bool check_fully_established(struct mptcp_sock * msk, struct sock * ssk, struct mptcp_subflow_context * subflow, struct sk_buff * skb, struct mptcp_options_received * mp_opt)
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
