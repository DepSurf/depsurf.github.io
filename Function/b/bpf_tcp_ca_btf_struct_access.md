# Function: <code>bpf_tcp_ca_btf_struct_access</code>

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
int bpf_tcp_ca_btf_struct_access(struct bpf_verifier_log * log, const struct btf_type * t, int off, int size, enum bpf_access_type atype, u32 * next_btf_id)
```

```json
{
  "name": "bpf_tcp_ca_btf_struct_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590433744,
      "name": "bpf_tcp_ca_btf_struct_access",
      "external": false,
      "loc": "net/ipv4/bpf_tcp_ca.c:125",
      "file": "net/ipv4/bpf_tcp_ca.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590433744,
      "name": "bpf_tcp_ca_btf_struct_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
int bpf_tcp_ca_btf_struct_access(struct bpf_verifier_log * log, const struct btf * btf, const struct btf_type * t, int off, int size, enum bpf_access_type atype, u32 * next_btf_id)
```

```json
{
  "name": "bpf_tcp_ca_btf_struct_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590491968,
      "name": "bpf_tcp_ca_btf_struct_access",
      "external": false,
      "loc": "net/ipv4/bpf_tcp_ca.c:97",
      "file": "net/ipv4/bpf_tcp_ca.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590491968,
      "name": "bpf_tcp_ca_btf_struct_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 230
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
int bpf_tcp_ca_btf_struct_access(struct bpf_verifier_log * log, const struct btf * btf, const struct btf_type * t, int off, int size, enum bpf_access_type atype, u32 * next_btf_id)
```

```json
{
  "name": "bpf_tcp_ca_btf_struct_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590417440,
      "name": "bpf_tcp_ca_btf_struct_access",
      "external": false,
      "loc": "net/ipv4/bpf_tcp_ca.c:98",
      "file": "net/ipv4/bpf_tcp_ca.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590417440,
      "name": "bpf_tcp_ca_btf_struct_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
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
int bpf_tcp_ca_btf_struct_access(struct bpf_verifier_log * log, const struct btf * btf, const struct btf_type * t, int off, int size, enum bpf_access_type atype, u32 * next_btf_id)
```

```json
{
  "name": "bpf_tcp_ca_btf_struct_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591215888,
      "name": "bpf_tcp_ca_btf_struct_access",
      "external": false,
      "loc": "net/ipv4/bpf_tcp_ca.c:101",
      "file": "net/ipv4/bpf_tcp_ca.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591215888,
      "name": "bpf_tcp_ca_btf_struct_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
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
int bpf_tcp_ca_btf_struct_access(struct bpf_verifier_log * log, const struct btf * btf, const struct btf_type * t, int off, int size, enum bpf_access_type atype, u32 * next_btf_id, enum bpf_type_flag * flag)
```

```json
{
  "name": "bpf_tcp_ca_btf_struct_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592877904,
      "name": "bpf_tcp_ca_btf_struct_access",
      "external": false,
      "loc": "net/ipv4/bpf_tcp_ca.c:95",
      "file": "net/ipv4/bpf_tcp_ca.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592877904,
      "name": "bpf_tcp_ca_btf_struct_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 287
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
int bpf_tcp_ca_btf_struct_access(struct bpf_verifier_log * log, const struct bpf_reg_state * reg, int off, int size, enum bpf_access_type atype, u32 * next_btf_id, enum bpf_type_flag * flag)
```

```json
{
  "name": "bpf_tcp_ca_btf_struct_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594756464,
      "name": "bpf_tcp_ca_btf_struct_access",
      "external": false,
      "loc": "net/ipv4/bpf_tcp_ca.c:73",
      "file": "net/ipv4/bpf_tcp_ca.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594756464,
      "name": "bpf_tcp_ca_btf_struct_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 360
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
int bpf_tcp_ca_btf_struct_access(struct bpf_verifier_log * log, const struct bpf_reg_state * reg, int off, int size)
```

```json
{
  "name": "bpf_tcp_ca_btf_struct_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595148864,
      "name": "bpf_tcp_ca_btf_struct_access",
      "external": false,
      "loc": "net/ipv4/bpf_tcp_ca.c:73",
      "file": "net/ipv4/bpf_tcp_ca.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595148864,
      "name": "bpf_tcp_ca_btf_struct_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 318
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
int bpf_tcp_ca_btf_struct_access(struct bpf_verifier_log * log, const struct bpf_reg_state * reg, int off, int size)
```

```json
{
  "name": "bpf_tcp_ca_btf_struct_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595990592,
      "name": "bpf_tcp_ca_btf_struct_access",
      "external": false,
      "loc": "net/ipv4/bpf_tcp_ca.c:71",
      "file": "net/ipv4/bpf_tcp_ca.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595990592,
      "name": "bpf_tcp_ca_btf_struct_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 318
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
int bpf_tcp_ca_btf_struct_access(struct bpf_verifier_log * log, const struct btf_type * t, int off, int size, enum bpf_access_type atype, u32 * next_btf_id)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct btf * btf</code>
</li>
<li>
<b>Param reordered. </b>
<code>log, t, off, size, atype, next_btf_id</code> ➡️ <code>log, btf, t, off, size, atype, next_btf_id</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum bpf_type_flag * flag</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct bpf_reg_state * reg</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct btf * btf</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct btf_type * t</code>
</li>
<li>
<b>Param reordered. </b>
<code>log, btf, t, off, size, atype, next_btf_id, flag</code> ➡️ <code>log, reg, off, size, atype, next_btf_id, flag</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>enum bpf_access_type atype</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 * next_btf_id</code>
</li>
<li>
<b>Param removed. </b>
<code>enum bpf_type_flag * flag</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
