# Function: <code>dfrag_clear</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void dfrag_clear(struct sock * sk, struct mptcp_data_frag * dfrag)
```

```json
{
  "name": "dfrag_clear",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591079406,
      "name": "dfrag_clear",
      "external": false,
      "loc": "net/mptcp/protocol.c:456",
      "file": "net/mptcp/protocol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:__mptcp_clear_xmit"
      ],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_clean_una"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591080288,
      "name": "dfrag_clear",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 235
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void dfrag_clear(struct sock * sk, struct mptcp_data_frag * dfrag)
```

```json
{
  "name": "dfrag_clear",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591145772,
      "name": "dfrag_clear",
      "external": false,
      "loc": "net/mptcp/protocol.c:981",
      "file": "net/mptcp/protocol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:__mptcp_clear_xmit"
      ],
      "caller_func": [
        "net/mptcp/protocol.c:__mptcp_clean_una"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591146256,
      "name": "dfrag_clear",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dfrag_clear",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591077740,
      "name": "dfrag_clear",
      "external": false,
      "loc": "net/mptcp/protocol.c:1024",
      "file": "net/mptcp/protocol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:__mptcp_clear_xmit",
        "net/mptcp/protocol.c:__mptcp_clean_una"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dfrag_clear",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591945707,
      "name": "dfrag_clear",
      "external": false,
      "loc": "net/mptcp/protocol.c:1041",
      "file": "net/mptcp/protocol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_destroy_common",
        "net/mptcp/protocol.c:__mptcp_clean_una"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void dfrag_clear(struct sock * sk, struct mptcp_data_frag * dfrag)
```

```json
{
  "name": "dfrag_clear",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593645744,
      "name": "dfrag_clear",
      "external": false,
      "loc": "net/mptcp/protocol.c:1000",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_destroy_common",
        "net/mptcp/protocol.c:__mptcp_clean_una"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593645744,
      "name": "dfrag_clear",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 346
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
void dfrag_clear(struct sock * sk, struct mptcp_data_frag * dfrag)
```

```json
{
  "name": "dfrag_clear",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595576864,
      "name": "dfrag_clear",
      "external": false,
      "loc": "net/mptcp/protocol.c:973",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_destroy_common",
        "net/mptcp/protocol.c:__mptcp_clean_una"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595576864,
      "name": "dfrag_clear",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 354
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
void dfrag_clear(struct sock * sk, struct mptcp_data_frag * dfrag)
```

```json
{
  "name": "dfrag_clear",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596086848,
      "name": "dfrag_clear",
      "external": false,
      "loc": "net/mptcp/protocol.c:950",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_destroy_common",
        "net/mptcp/protocol.c:__mptcp_clean_una"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596086848,
      "name": "dfrag_clear",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 357
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
void dfrag_clear(struct sock * sk, struct mptcp_data_frag * dfrag)
```

```json
{
  "name": "dfrag_clear",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596955584,
      "name": "dfrag_clear",
      "external": false,
      "loc": "net/mptcp/protocol.c:979",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_destroy_common",
        "net/mptcp/protocol.c:__mptcp_clean_una"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596955584,
      "name": "dfrag_clear",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 354
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
void dfrag_clear(struct sock * sk, struct mptcp_data_frag * dfrag)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void dfrag_clear(struct sock * sk, struct mptcp_data_frag * dfrag)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void dfrag_clear(struct sock * sk, struct mptcp_data_frag * dfrag)
```
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
