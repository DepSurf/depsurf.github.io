# Function: <code>__tcp_md5_do_add</code>

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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int __tcp_md5_do_add(struct sock * sk, const union tcp_md5_addr * addr, int family, u8 prefixlen, int l3index, u8 flags, const u8 * newkey, u8 newkeylen, gfp_t gfp)
```

```json
{
  "name": "__tcp_md5_do_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__tcp_md5_do_add",
      "external": false,
      "loc": "net/ipv4/tcp_ipv4.c:1180",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_md5_key_copy",
        "net/ipv4/tcp_ipv4.c:tcp_md5_do_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594364640,
      "name": "__tcp_md5_do_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 884
    },
    {
      "addr": 18446744071596341615,
      "name": "__tcp_md5_do_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
int __tcp_md5_do_add(struct sock * sk, const union tcp_md5_addr * addr, int family, u8 prefixlen, int l3index, u8 flags, const u8 * newkey, u8 newkeylen, gfp_t gfp)
```

```json
{
  "name": "__tcp_md5_do_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__tcp_md5_do_add",
      "external": false,
      "loc": "net/ipv4/tcp_ipv4.c:1187",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_md5_key_copy",
        "net/ipv4/tcp_ipv4.c:tcp_md5_do_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594752960,
      "name": "__tcp_md5_do_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 884
    },
    {
      "addr": 18446744071596870891,
      "name": "__tcp_md5_do_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
int __tcp_md5_do_add(struct sock * sk, const union tcp_ao_addr * addr, int family, u8 prefixlen, int l3index, u8 flags, const u8 * newkey, u8 newkeylen, gfp_t gfp)
```

```json
{
  "name": "__tcp_md5_do_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__tcp_md5_do_add",
      "external": false,
      "loc": "net/ipv4/tcp_ipv4.c:1347",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_md5_key_copy",
        "net/ipv4/tcp_ipv4.c:tcp_md5_do_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595559296,
      "name": "__tcp_md5_do_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 864
    },
    {
      "addr": 18446744071597794495,
      "name": "__tcp_md5_do_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
int __tcp_md5_do_add(struct sock * sk, const union tcp_md5_addr * addr, int family, u8 prefixlen, int l3index, u8 flags, const u8 * newkey, u8 newkeylen, gfp_t gfp)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const union tcp_md5_addr * addr</code> ➡️ <code>const union tcp_ao_addr * addr</code>
</li>
</ul>
</details>
</li>
</ul>
