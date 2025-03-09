# Function: <code>sha1_init</code>

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
void sha1_init(__u32 * buf)
```

```json
{
  "name": "sha1_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585072112,
      "name": "sha1_init",
      "external": true,
      "loc": "lib/sha1.c:196",
      "file": "lib/sha1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_prog_calc_tag",
        "drivers/char/random.c:extract_buf",
        "net/ipv6/addrconf.c:ipv6_generate_stable_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585072112,
      "name": "sha1_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void sha1_init(__u32 * buf)
```

```json
{
  "name": "sha1_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585221456,
      "name": "sha1_init",
      "external": true,
      "loc": "lib/sha1.c:196",
      "file": "lib/sha1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_prog_calc_tag",
        "drivers/char/random.c:extract_buf",
        "net/ipv6/addrconf.c:ipv6_generate_stable_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585221456,
      "name": "sha1_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void sha1_init(__u32 * buf)
```

```json
{
  "name": "sha1_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585104352,
      "name": "sha1_init",
      "external": true,
      "loc": "lib/sha1.c:196",
      "file": "lib/sha1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_prog_calc_tag",
        "drivers/char/random.c:extract_buf",
        "net/ipv6/addrconf.c:ipv6_generate_stable_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585104352,
      "name": "sha1_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void sha1_init(__u32 * buf)
```

```json
{
  "name": "sha1_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585553024,
      "name": "sha1_init",
      "external": true,
      "loc": "lib/sha1.c:196",
      "file": "lib/sha1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_prog_calc_tag",
        "drivers/char/random.c:extract_buf",
        "net/ipv6/addrconf.c:ipv6_generate_stable_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585553024,
      "name": "sha1_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void sha1_init(__u32 * buf)
```

```json
{
  "name": "sha1_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586709760,
      "name": "sha1_init",
      "external": true,
      "loc": "lib/sha1.c:129",
      "file": "lib/sha1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_prog_calc_tag",
        "net/ipv6/addrconf.c:ipv6_generate_stable_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586709760,
      "name": "sha1_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void sha1_init(__u32 * buf)
```

```json
{
  "name": "sha1_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587116800,
      "name": "sha1_init",
      "external": true,
      "loc": "lib/crypto/sha1.c:130",
      "file": "lib/crypto/sha1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_prog_calc_tag",
        "net/ipv6/addrconf.c:ipv6_generate_stable_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587116800,
      "name": "sha1_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void sha1_init(__u32 * buf)
```

```json
{
  "name": "sha1_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587378768,
      "name": "sha1_init",
      "external": true,
      "loc": "lib/crypto/sha1.c:130",
      "file": "lib/crypto/sha1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_prog_calc_tag",
        "net/ipv6/addrconf.c:ipv6_generate_stable_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587378768,
      "name": "sha1_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void sha1_init(__u32 * buf)
```

```json
{
  "name": "sha1_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587665552,
      "name": "sha1_init",
      "external": true,
      "loc": "lib/crypto/sha1.c:130",
      "file": "lib/crypto/sha1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_prog_calc_tag",
        "net/ipv6/addrconf.c:ipv6_generate_stable_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587665552,
      "name": "sha1_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void sha1_init(__u32 * buf)
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
