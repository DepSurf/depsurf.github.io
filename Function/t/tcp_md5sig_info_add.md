# Function: <code>tcp_md5sig_info_add</code>

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
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int tcp_md5sig_info_add(struct sock * sk, gfp_t gfp)
```

```json
{
  "name": "tcp_md5sig_info_add",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594369288,
      "name": "tcp_md5sig_info_add",
      "external": false,
      "loc": "net/ipv4/tcp_ipv4.c:1164",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_md5_do_add"
      ],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_md5_key_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594362240,
      "name": "tcp_md5sig_info_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
int tcp_md5sig_info_add(struct sock * sk, gfp_t gfp)
```

```json
{
  "name": "tcp_md5sig_info_add",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594759560,
      "name": "tcp_md5sig_info_add",
      "external": false,
      "loc": "net/ipv4/tcp_ipv4.c:1171",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_md5_do_add"
      ],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_md5_key_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594750560,
      "name": "tcp_md5sig_info_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
int tcp_md5sig_info_add(struct sock * sk, gfp_t gfp)
```

```json
{
  "name": "tcp_md5sig_info_add",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595567330,
      "name": "tcp_md5sig_info_add",
      "external": false,
      "loc": "net/ipv4/tcp_ipv4.c:1331",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_md5_do_add"
      ],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_md5_key_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595556624,
      "name": "tcp_md5sig_info_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
int tcp_md5sig_info_add(struct sock * sk, gfp_t gfp)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
