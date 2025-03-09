# Function: <code>add_addr_generate_hmac</code>

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
  "name": "add_addr_generate_hmac",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591106083,
      "name": "add_addr_generate_hmac",
      "external": false,
      "loc": "net/mptcp/options.c:541",
      "file": "net/mptcp/options.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/options.c:mptcp_incoming_options",
        "net/mptcp/options.c:mptcp_established_options_addr"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "add_addr_generate_hmac",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591187819,
      "name": "add_addr_generate_hmac",
      "external": false,
      "loc": "net/mptcp/options.c:557",
      "file": "net/mptcp/options.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/options.c:mptcp_incoming_options",
        "net/mptcp/options.c:mptcp_established_options_add_addr"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
u64 add_addr_generate_hmac(u64 key1, u64 key2, struct mptcp_addr_info * addr)
```

```json
{
  "name": "add_addr_generate_hmac",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591119200,
      "name": "add_addr_generate_hmac",
      "external": false,
      "loc": "net/mptcp/options.c:590",
      "file": "net/mptcp/options.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/options.c:mptcp_incoming_options",
        "net/mptcp/options.c:mptcp_established_options_add_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591119200,
      "name": "add_addr_generate_hmac",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
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
u64 add_addr_generate_hmac(u64 key1, u64 key2, struct mptcp_addr_info * addr)
```

```json
{
  "name": "add_addr_generate_hmac",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591965264,
      "name": "add_addr_generate_hmac",
      "external": false,
      "loc": "net/mptcp/options.c:617",
      "file": "net/mptcp/options.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/options.c:mptcp_incoming_options",
        "net/mptcp/options.c:mptcp_established_options_add_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591965264,
      "name": "add_addr_generate_hmac",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 338
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
u64 add_addr_generate_hmac(u64 key1, u64 key2, struct mptcp_addr_info * addr)
```

```json
{
  "name": "add_addr_generate_hmac",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593693568,
      "name": "add_addr_generate_hmac",
      "external": false,
      "loc": "net/mptcp/options.c:619",
      "file": "net/mptcp/options.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/options.c:mptcp_incoming_options",
        "net/mptcp/options.c:mptcp_established_options_add_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593693568,
      "name": "add_addr_generate_hmac",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 391
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
u64 add_addr_generate_hmac(u64 key1, u64 key2, struct mptcp_addr_info * addr)
```

```json
{
  "name": "add_addr_generate_hmac",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595624800,
      "name": "add_addr_generate_hmac",
      "external": false,
      "loc": "net/mptcp/options.c:624",
      "file": "net/mptcp/options.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/options.c:mptcp_incoming_options",
        "net/mptcp/options.c:mptcp_established_options_add_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595624800,
      "name": "add_addr_generate_hmac",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 391
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
u64 add_addr_generate_hmac(u64 key1, u64 key2, struct mptcp_addr_info * addr)
```

```json
{
  "name": "add_addr_generate_hmac",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596133136,
      "name": "add_addr_generate_hmac",
      "external": false,
      "loc": "net/mptcp/options.c:621",
      "file": "net/mptcp/options.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/options.c:mptcp_incoming_options",
        "net/mptcp/options.c:mptcp_established_options_add_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596133136,
      "name": "add_addr_generate_hmac",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 391
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
u64 add_addr_generate_hmac(u64 key1, u64 key2, struct mptcp_addr_info * addr)
```

```json
{
  "name": "add_addr_generate_hmac",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597006864,
      "name": "add_addr_generate_hmac",
      "external": false,
      "loc": "net/mptcp/options.c:622",
      "file": "net/mptcp/options.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/options.c:mptcp_incoming_options",
        "net/mptcp/options.c:mptcp_established_options_add_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597006864,
      "name": "add_addr_generate_hmac",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 391
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
u64 add_addr_generate_hmac(u64 key1, u64 key2, struct mptcp_addr_info * addr)
```
</details>
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
