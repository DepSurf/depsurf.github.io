# Function: <code>dump_security_xattr</code>

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
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void dump_security_xattr(const char * prefix, const void * src, size_t count)
```

```json
{
  "name": "dump_security_xattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584756144,
      "name": "dump_security_xattr",
      "external": false,
      "loc": "security/integrity/evm/evm_crypto.c:189",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash",
        "security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584756144,
      "name": "dump_security_xattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
void dump_security_xattr(const char * prefix, const void * src, size_t count)
```

```json
{
  "name": "dump_security_xattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585438192,
      "name": "dump_security_xattr",
      "external": false,
      "loc": "security/integrity/evm/evm_crypto.c:186",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash",
        "security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585438192,
      "name": "dump_security_xattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
void dump_security_xattr(const char * prefix, const void * src, size_t count)
```

```json
{
  "name": "dump_security_xattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586195984,
      "name": "dump_security_xattr",
      "external": false,
      "loc": "security/integrity/evm/evm_crypto.c:186",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash",
        "security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586195984,
      "name": "dump_security_xattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
void dump_security_xattr(const char * name, const char * value, size_t value_len)
```

```json
{
  "name": "dump_security_xattr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586434528,
      "name": "dump_security_xattr",
      "external": false,
      "loc": "security/integrity/evm/evm_crypto.c:203",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash",
        "security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586434528,
      "name": "dump_security_xattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
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
void dump_security_xattr(const char * name, const char * value, size_t value_len)
```

```json
{
  "name": "dump_security_xattr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586700416,
      "name": "dump_security_xattr",
      "external": false,
      "loc": "security/integrity/evm/evm_crypto.c:203",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash",
        "security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586700416,
      "name": "dump_security_xattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
void dump_security_xattr(const char * prefix, const void * src, size_t count)
```
</details>
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
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
<code>const char * name</code>
</li>
<li>
<b>Param added. </b>
<code>const char * value</code>
</li>
<li>
<b>Param added. </b>
<code>size_t value_len</code>
</li>
<li>
<b>Param removed. </b>
<code>const char * prefix</code>
</li>
<li>
<b>Param removed. </b>
<code>const void * src</code>
</li>
<li>
<b>Param removed. </b>
<code>size_t count</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
