# Function: <code>btf_struct_access</code>

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
int btf_struct_access(struct bpf_verifier_log * log, const struct btf_type * t, int off, int size, enum bpf_access_type atype, u32 * next_btf_id)
```

```json
{
  "name": "btf_struct_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581093712,
      "name": "btf_struct_access",
      "external": true,
      "loc": "kernel/bpf/btf.c:3832",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_ptr_to_btf_access",
        "kernel/bpf/btf.c:btf_struct_access",
        "net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_btf_struct_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581093712,
      "name": "btf_struct_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1140
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
int btf_struct_access(struct bpf_verifier_log * log, const struct btf * btf, const struct btf_type * t, int off, int size, enum bpf_access_type atype, u32 * next_btf_id)
```

```json
{
  "name": "btf_struct_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581121008,
      "name": "btf_struct_access",
      "external": true,
      "loc": "kernel/bpf/btf.c:4985",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_ptr_to_map_access",
        "kernel/bpf/verifier.c:check_ptr_to_btf_access",
        "net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_btf_struct_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581121008,
      "name": "btf_struct_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
int btf_struct_access(struct bpf_verifier_log * log, const struct btf * btf, const struct btf_type * t, int off, int size, enum bpf_access_type atype, u32 * next_btf_id)
```

```json
{
  "name": "btf_struct_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581139952,
      "name": "btf_struct_access",
      "external": true,
      "loc": "kernel/bpf/btf.c:5058",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_ptr_to_map_access",
        "kernel/bpf/verifier.c:check_ptr_to_btf_access",
        "net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_btf_struct_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581139952,
      "name": "btf_struct_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
int btf_struct_access(struct bpf_verifier_log * log, const struct btf * btf, const struct btf_type * t, int off, int size, enum bpf_access_type atype, u32 * next_btf_id)
```

```json
{
  "name": "btf_struct_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "btf_struct_access",
      "external": true,
      "loc": "kernel/bpf/btf.c:5111",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_ptr_to_map_access",
        "kernel/bpf/verifier.c:check_ptr_to_btf_access",
        "net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_btf_struct_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592187106,
      "name": "btf_struct_access.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071581372784,
      "name": "btf_struct_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 237
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
int btf_struct_access(struct bpf_verifier_log * log, const struct btf * btf, const struct btf_type * t, int off, int size, enum bpf_access_type atype, u32 * next_btf_id, enum bpf_type_flag * flag)
```

```json
{
  "name": "btf_struct_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "btf_struct_access",
      "external": true,
      "loc": "kernel/bpf/btf.c:5656",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_ptr_to_map_access",
        "kernel/bpf/verifier.c:check_ptr_to_btf_access",
        "net/bpf/bpf_dummy_struct_ops.c:bpf_dummy_ops_btf_struct_access",
        "net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_btf_struct_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593961632,
      "name": "btf_struct_access.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071581689312,
      "name": "btf_struct_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
int btf_struct_access(struct bpf_verifier_log * log, const struct bpf_reg_state * reg, int off, int size, enum bpf_access_type atype, u32 * next_btf_id, enum bpf_type_flag * flag)
```

```json
{
  "name": "btf_struct_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "btf_struct_access",
      "external": true,
      "loc": "kernel/bpf/btf.c:6295",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_ptr_to_map_access",
        "kernel/bpf/verifier.c:check_ptr_to_btf_access",
        "net/bpf/bpf_dummy_struct_ops.c:bpf_dummy_ops_btf_struct_access",
        "net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_btf_struct_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596022084,
      "name": "btf_struct_access.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071582086560,
      "name": "btf_struct_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 742
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
int btf_struct_access(struct bpf_verifier_log * log, const struct bpf_reg_state * reg, int off, int size, enum bpf_access_type atype, u32 * next_btf_id, enum bpf_type_flag * flag, const char * * field_name)
```

```json
{
  "name": "btf_struct_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "btf_struct_access",
      "external": true,
      "loc": "kernel/bpf/btf.c:6382",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_ptr_to_map_access",
        "kernel/bpf/verifier.c:check_ptr_to_btf_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596543994,
      "name": "btf_struct_access.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071582282832,
      "name": "btf_struct_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 823
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
int btf_struct_access(struct bpf_verifier_log * log, const struct bpf_reg_state * reg, int off, int size, enum bpf_access_type atype, u32 * next_btf_id, enum bpf_type_flag * flag, const char * * field_name)
```

```json
{
  "name": "btf_struct_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "btf_struct_access",
      "external": true,
      "loc": "kernel/bpf/btf.c:6554",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_ptr_to_map_access",
        "kernel/bpf/verifier.c:check_ptr_to_btf_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597447234,
      "name": "btf_struct_access.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071582439568,
      "name": "btf_struct_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 871
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
int btf_struct_access(struct bpf_verifier_log * log, const struct btf_type * t, int off, int size, enum bpf_access_type atype, u32 * next_btf_id)
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
<b>Param added. </b>
<code>const char * * field_name</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
