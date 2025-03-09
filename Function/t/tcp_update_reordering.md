# Function: <code>tcp_update_reordering</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_update_reordering",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586627680,
      "name": "tcp_update_reordering",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:851",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert"
      ],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_check_reno_reordering",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_sacktag_write_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586627680,
      "name": "tcp_update_reordering.constprop.58",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_update_reordering",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587092508,
      "name": "tcp_update_reordering",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:853",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert"
      ],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_check_reno_reordering",
        "net/ipv4/tcp_input.c:tcp_sacktag_write_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587071504,
      "name": "tcp_update_reordering.constprop.61",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_update_reordering",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587289425,
      "name": "tcp_update_reordering",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:876",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert"
      ],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_check_reno_reordering",
        "net/ipv4/tcp_input.c:tcp_sacktag_write_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587269168,
      "name": "tcp_update_reordering.constprop.62",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void tcp_update_reordering(struct sock * sk, const int metric, const int ts)
```

```json
{
  "name": "tcp_update_reordering",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587396944,
      "name": "tcp_update_reordering",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:883",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_check_reno_reordering",
        "net/ipv4/tcp_input.c:tcp_sacktag_write_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587396944,
      "name": "tcp_update_reordering",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
    }
  ]
}
```
</details>
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
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void tcp_update_reordering(struct sock * sk, const int metric, const int ts)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➖</summary>

```c
void tcp_update_reordering(struct sock * sk, const int metric, const int ts)
```
</details>
</li>
</ul>
