# Function: <code>pkey_pack_u32</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
u8 * pkey_pack_u32(u8 * dst, u32 val)
```

```json
{
  "name": "pkey_pack_u32",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583827488,
      "name": "pkey_pack_u32",
      "external": false,
      "loc": "crypto/asymmetric_keys/public_key.c:94",
      "file": "crypto/asymmetric_keys/public_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_query",
        "crypto/asymmetric_keys/public_key.c:software_key_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583827488,
      "name": "pkey_pack_u32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
u8 * pkey_pack_u32(u8 * dst, u32 val)
```

```json
{
  "name": "pkey_pack_u32",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583929456,
      "name": "pkey_pack_u32",
      "external": false,
      "loc": "crypto/asymmetric_keys/public_key.c:94",
      "file": "crypto/asymmetric_keys/public_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_query",
        "crypto/asymmetric_keys/public_key.c:software_key_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583929456,
      "name": "pkey_pack_u32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pkey_pack_u32",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584321899,
      "name": "pkey_pack_u32",
      "external": false,
      "loc": "crypto/asymmetric_keys/public_key.c:94",
      "file": "crypto/asymmetric_keys/public_key.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_query"
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
  "name": "pkey_pack_u32",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584440150,
      "name": "pkey_pack_u32",
      "external": false,
      "loc": "crypto/asymmetric_keys/public_key.c:96",
      "file": "crypto/asymmetric_keys/public_key.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_query"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pkey_pack_u32",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584474818,
      "name": "pkey_pack_u32",
      "external": false,
      "loc": "crypto/asymmetric_keys/public_key.c:98",
      "file": "crypto/asymmetric_keys/public_key.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_query"
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
  "name": "pkey_pack_u32",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584872978,
      "name": "pkey_pack_u32",
      "external": false,
      "loc": "crypto/asymmetric_keys/public_key.c:98",
      "file": "crypto/asymmetric_keys/public_key.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_query"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pkey_pack_u32",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585570660,
      "name": "pkey_pack_u32",
      "external": false,
      "loc": "crypto/asymmetric_keys/public_key.c:142",
      "file": "crypto/asymmetric_keys/public_key.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_query",
        "crypto/asymmetric_keys/public_key.c:software_key_query"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
u8 * pkey_pack_u32(u8 * dst, u32 val)
```

```json
{
  "name": "pkey_pack_u32",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586332784,
      "name": "pkey_pack_u32",
      "external": false,
      "loc": "crypto/asymmetric_keys/public_key.c:142",
      "file": "crypto/asymmetric_keys/public_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_query",
        "crypto/asymmetric_keys/public_key.c:software_key_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586332784,
      "name": "pkey_pack_u32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
u8 * pkey_pack_u32(u8 * dst, u32 val)
```

```json
{
  "name": "pkey_pack_u32",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586579504,
      "name": "pkey_pack_u32",
      "external": false,
      "loc": "crypto/asymmetric_keys/public_key.c:149",
      "file": "crypto/asymmetric_keys/public_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_query",
        "crypto/asymmetric_keys/public_key.c:software_key_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586579504,
      "name": "pkey_pack_u32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
u8 * pkey_pack_u32(u8 * dst, u32 val)
```

```json
{
  "name": "pkey_pack_u32",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586848144,
      "name": "pkey_pack_u32",
      "external": false,
      "loc": "crypto/asymmetric_keys/public_key.c:150",
      "file": "crypto/asymmetric_keys/public_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_query",
        "crypto/asymmetric_keys/public_key.c:software_key_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586848144,
      "name": "pkey_pack_u32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
u8 * pkey_pack_u32(u8 * dst, u32 val)
```

```json
{
  "name": "pkey_pack_u32",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495748640,
      "name": "pkey_pack_u32",
      "external": false,
      "loc": "crypto/asymmetric_keys/public_key.c:94",
      "file": "crypto/asymmetric_keys/public_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_query",
        "crypto/asymmetric_keys/public_key.c:software_key_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495748640,
      "name": "pkey_pack_u32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
u8 * pkey_pack_u32(u8 * dst, u32 val)
```

```json
{
  "name": "pkey_pack_u32",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229101688,
      "name": "pkey_pack_u32",
      "external": false,
      "loc": "crypto/asymmetric_keys/public_key.c:94",
      "file": "crypto/asymmetric_keys/public_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_query",
        "crypto/asymmetric_keys/public_key.c:software_key_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229101688,
      "name": "pkey_pack_u32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
u8 * pkey_pack_u32(u8 * dst, u32 val)
```

```json
{
  "name": "pkey_pack_u32",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289911840,
      "name": "pkey_pack_u32",
      "external": false,
      "loc": "crypto/asymmetric_keys/public_key.c:94",
      "file": "crypto/asymmetric_keys/public_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_query",
        "crypto/asymmetric_keys/public_key.c:software_key_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289911840,
      "name": "pkey_pack_u32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "pkey_pack_u32",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274897918,
      "name": "pkey_pack_u32",
      "external": false,
      "loc": "crypto/asymmetric_keys/public_key.c:94",
      "file": "crypto/asymmetric_keys/public_key.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_query",
        "crypto/asymmetric_keys/public_key.c:software_key_query"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
u8 * pkey_pack_u32(u8 * dst, u32 val)
```

```json
{
  "name": "pkey_pack_u32",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583898192,
      "name": "pkey_pack_u32",
      "external": false,
      "loc": "crypto/asymmetric_keys/public_key.c:94",
      "file": "crypto/asymmetric_keys/public_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_query",
        "crypto/asymmetric_keys/public_key.c:software_key_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583898192,
      "name": "pkey_pack_u32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
u8 * pkey_pack_u32(u8 * dst, u32 val)
```

```json
{
  "name": "pkey_pack_u32",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583835248,
      "name": "pkey_pack_u32",
      "external": false,
      "loc": "crypto/asymmetric_keys/public_key.c:94",
      "file": "crypto/asymmetric_keys/public_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_query",
        "crypto/asymmetric_keys/public_key.c:software_key_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583835248,
      "name": "pkey_pack_u32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
u8 * pkey_pack_u32(u8 * dst, u32 val)
```

```json
{
  "name": "pkey_pack_u32",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583881952,
      "name": "pkey_pack_u32",
      "external": false,
      "loc": "crypto/asymmetric_keys/public_key.c:94",
      "file": "crypto/asymmetric_keys/public_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_query",
        "crypto/asymmetric_keys/public_key.c:software_key_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583881952,
      "name": "pkey_pack_u32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
u8 * pkey_pack_u32(u8 * dst, u32 val)
```

```json
{
  "name": "pkey_pack_u32",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583983024,
      "name": "pkey_pack_u32",
      "external": false,
      "loc": "crypto/asymmetric_keys/public_key.c:94",
      "file": "crypto/asymmetric_keys/public_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_query",
        "crypto/asymmetric_keys/public_key.c:software_key_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583983024,
      "name": "pkey_pack_u32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
u8 * pkey_pack_u32(u8 * dst, u32 val)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
u8 * pkey_pack_u32(u8 * dst, u32 val)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
u8 * pkey_pack_u32(u8 * dst, u32 val)
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
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
u8 * pkey_pack_u32(u8 * dst, u32 val)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
