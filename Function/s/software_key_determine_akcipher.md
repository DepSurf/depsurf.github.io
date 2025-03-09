# Function: <code>software_key_determine_akcipher</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "software_key_determine_akcipher",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583641488,
      "name": "software_key_determine_akcipher",
      "external": false,
      "loc": "crypto/asymmetric_keys/public_key.c:66",
      "file": "crypto/asymmetric_keys/public_key.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583641488,
      "name": "software_key_determine_akcipher.isra.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "software_key_determine_akcipher",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583827632,
      "name": "software_key_determine_akcipher",
      "external": false,
      "loc": "crypto/asymmetric_keys/public_key.c:63",
      "file": "crypto/asymmetric_keys/public_key.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583827632,
      "name": "software_key_determine_akcipher.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "software_key_determine_akcipher",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583929600,
      "name": "software_key_determine_akcipher",
      "external": false,
      "loc": "crypto/asymmetric_keys/public_key.c:63",
      "file": "crypto/asymmetric_keys/public_key.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583929600,
      "name": "software_key_determine_akcipher.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int software_key_determine_akcipher(const char * encoding, const char * hash_algo, const struct public_key * pkey, char * alg_name)
```

```json
{
  "name": "software_key_determine_akcipher",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584320864,
      "name": "software_key_determine_akcipher",
      "external": false,
      "loc": "crypto/asymmetric_keys/public_key.c:63",
      "file": "crypto/asymmetric_keys/public_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584320864,
      "name": "software_key_determine_akcipher",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
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
int software_key_determine_akcipher(const char * encoding, const char * hash_algo, const struct public_key * pkey, char * alg_name)
```

```json
{
  "name": "software_key_determine_akcipher",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584439104,
      "name": "software_key_determine_akcipher",
      "external": false,
      "loc": "crypto/asymmetric_keys/public_key.c:65",
      "file": "crypto/asymmetric_keys/public_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584439104,
      "name": "software_key_determine_akcipher",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
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
int software_key_determine_akcipher(const char * encoding, const char * hash_algo, const struct public_key * pkey, char * alg_name)
```

```json
{
  "name": "software_key_determine_akcipher",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584473776,
      "name": "software_key_determine_akcipher",
      "external": false,
      "loc": "crypto/asymmetric_keys/public_key.c:66",
      "file": "crypto/asymmetric_keys/public_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584473776,
      "name": "software_key_determine_akcipher",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 206
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
int software_key_determine_akcipher(const char * encoding, const char * hash_algo, const struct public_key * pkey, char * alg_name)
```

```json
{
  "name": "software_key_determine_akcipher",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584871904,
      "name": "software_key_determine_akcipher",
      "external": false,
      "loc": "crypto/asymmetric_keys/public_key.c:66",
      "file": "crypto/asymmetric_keys/public_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584871904,
      "name": "software_key_determine_akcipher",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 206
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
int software_key_determine_akcipher(const struct public_key * pkey, const char * encoding, const char * hash_algo, char * alg_name)
```

```json
{
  "name": "software_key_determine_akcipher",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585567904,
      "name": "software_key_determine_akcipher",
      "external": false,
      "loc": "crypto/asymmetric_keys/public_key.c:68",
      "file": "crypto/asymmetric_keys/public_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585567904,
      "name": "software_key_determine_akcipher",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 617
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
int software_key_determine_akcipher(const struct public_key * pkey, const char * encoding, const char * hash_algo, char * alg_name)
```

```json
{
  "name": "software_key_determine_akcipher",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586332048,
      "name": "software_key_determine_akcipher",
      "external": false,
      "loc": "crypto/asymmetric_keys/public_key.c:68",
      "file": "crypto/asymmetric_keys/public_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586332048,
      "name": "software_key_determine_akcipher",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 617
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
int software_key_determine_akcipher(const struct public_key * pkey, const char * encoding, const char * hash_algo, char * alg_name, bool * sig, enum kernel_pkey_operation op)
```

```json
{
  "name": "software_key_determine_akcipher",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586578704,
      "name": "software_key_determine_akcipher",
      "external": false,
      "loc": "crypto/asymmetric_keys/public_key.c:67",
      "file": "crypto/asymmetric_keys/public_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586578704,
      "name": "software_key_determine_akcipher",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 688
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
int software_key_determine_akcipher(const struct public_key * pkey, const char * encoding, const char * hash_algo, char * alg_name, bool * sig, enum kernel_pkey_operation op)
```

```json
{
  "name": "software_key_determine_akcipher",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586847296,
      "name": "software_key_determine_akcipher",
      "external": false,
      "loc": "crypto/asymmetric_keys/public_key.c:67",
      "file": "crypto/asymmetric_keys/public_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586847296,
      "name": "software_key_determine_akcipher",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 733
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "software_key_determine_akcipher",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495748840,
      "name": "software_key_determine_akcipher",
      "external": false,
      "loc": "crypto/asymmetric_keys/public_key.c:63",
      "file": "crypto/asymmetric_keys/public_key.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495748840,
      "name": "software_key_determine_akcipher.isra.0",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int software_key_determine_akcipher(const char * encoding, const char * hash_algo, const struct public_key * pkey, char * alg_name)
```

```json
{
  "name": "software_key_determine_akcipher",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229101844,
      "name": "software_key_determine_akcipher",
      "external": false,
      "loc": "crypto/asymmetric_keys/public_key.c:63",
      "file": "crypto/asymmetric_keys/public_key.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229101844,
      "name": "software_key_determine_akcipher",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "software_key_determine_akcipher",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055289912096,
      "name": "software_key_determine_akcipher",
      "external": false,
      "loc": "crypto/asymmetric_keys/public_key.c:63",
      "file": "crypto/asymmetric_keys/public_key.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289912096,
      "name": "software_key_determine_akcipher.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 920
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
  "name": "software_key_determine_akcipher",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274897062,
      "name": "software_key_determine_akcipher",
      "external": false,
      "loc": "crypto/asymmetric_keys/public_key.c:63",
      "file": "crypto/asymmetric_keys/public_key.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274897062,
      "name": "software_key_determine_akcipher.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "software_key_determine_akcipher",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583898336,
      "name": "software_key_determine_akcipher",
      "external": false,
      "loc": "crypto/asymmetric_keys/public_key.c:63",
      "file": "crypto/asymmetric_keys/public_key.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583898336,
      "name": "software_key_determine_akcipher.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "software_key_determine_akcipher",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583835392,
      "name": "software_key_determine_akcipher",
      "external": false,
      "loc": "crypto/asymmetric_keys/public_key.c:63",
      "file": "crypto/asymmetric_keys/public_key.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583835392,
      "name": "software_key_determine_akcipher.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "software_key_determine_akcipher",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583882096,
      "name": "software_key_determine_akcipher",
      "external": false,
      "loc": "crypto/asymmetric_keys/public_key.c:63",
      "file": "crypto/asymmetric_keys/public_key.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583882096,
      "name": "software_key_determine_akcipher.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "software_key_determine_akcipher",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583983168,
      "name": "software_key_determine_akcipher",
      "external": false,
      "loc": "crypto/asymmetric_keys/public_key.c:63",
      "file": "crypto/asymmetric_keys/public_key.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/public_key.c:public_key_verify_signature",
        "crypto/asymmetric_keys/public_key.c:software_key_eds_op",
        "crypto/asymmetric_keys/public_key.c:software_key_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583983168,
      "name": "software_key_determine_akcipher.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int software_key_determine_akcipher(const char * encoding, const char * hash_algo, const struct public_key * pkey, char * alg_name)
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param reordered. </b>
<code>encoding, hash_algo, pkey, alg_name</code> ➡️ <code>pkey, encoding, hash_algo, alg_name</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool * sig</code>
</li>
<li>
<b>Param added. </b>
<code>enum kernel_pkey_operation op</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int software_key_determine_akcipher(const char * encoding, const char * hash_algo, const struct public_key * pkey, char * alg_name)
```
</details>
</li>
</ul>
