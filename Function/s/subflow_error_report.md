# Function: <code>subflow_error_report</code>

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
void subflow_error_report(struct sock * ssk)
```

```json
{
  "name": "subflow_error_report",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591179264,
      "name": "subflow_error_report",
      "external": false,
      "loc": "net/mptcp/subflow.c:1077",
      "file": "net/mptcp/subflow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591179264,
      "name": "subflow_error_report",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
void subflow_error_report(struct sock * ssk)
```

```json
{
  "name": "subflow_error_report",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591114544,
      "name": "subflow_error_report",
      "external": false,
      "loc": "net/mptcp/subflow.c:1142",
      "file": "net/mptcp/subflow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:subflow_state_change",
        "net/mptcp/subflow.c:subflow_data_ready"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591114544,
      "name": "subflow_error_report",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
void subflow_error_report(struct sock * ssk)
```

```json
{
  "name": "subflow_error_report",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591960160,
      "name": "subflow_error_report",
      "external": false,
      "loc": "net/mptcp/subflow.c:1269",
      "file": "net/mptcp/subflow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:subflow_state_change",
        "net/mptcp/subflow.c:subflow_data_ready"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591960160,
      "name": "subflow_error_report",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void subflow_error_report(struct sock * ssk)
```

```json
{
  "name": "subflow_error_report",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593688453,
      "name": "subflow_error_report",
      "external": false,
      "loc": "net/mptcp/subflow.c:1358",
      "file": "net/mptcp/subflow.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/subflow.c:subflow_state_change",
        "net/mptcp/subflow.c:subflow_data_ready"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593687584,
      "name": "subflow_error_report",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void subflow_error_report(struct sock * ssk)
```

```json
{
  "name": "subflow_error_report",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595621557,
      "name": "subflow_error_report",
      "external": false,
      "loc": "net/mptcp/subflow.c:1430",
      "file": "net/mptcp/subflow.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/subflow.c:subflow_state_change",
        "net/mptcp/subflow.c:subflow_data_ready"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595620704,
      "name": "subflow_error_report",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void subflow_error_report(struct sock * ssk)
```

```json
{
  "name": "subflow_error_report",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596129476,
      "name": "subflow_error_report",
      "external": false,
      "loc": "net/mptcp/subflow.c:1401",
      "file": "net/mptcp/subflow.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/subflow.c:subflow_state_change",
        "net/mptcp/subflow.c:subflow_data_ready"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596128816,
      "name": "subflow_error_report",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void subflow_error_report(struct sock * ssk)
```

```json
{
  "name": "subflow_error_report",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071597003084,
      "name": "subflow_error_report",
      "external": false,
      "loc": "net/mptcp/subflow.c:1390",
      "file": "net/mptcp/subflow.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/subflow.c:subflow_state_change",
        "net/mptcp/subflow.c:subflow_data_ready"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596988688,
      "name": "subflow_error_report",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
void subflow_error_report(struct sock * ssk)
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
