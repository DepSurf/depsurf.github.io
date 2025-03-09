# Function: <code>xattr_verify</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xattr_verify",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583809034,
      "name": "xattr_verify",
      "external": false,
      "loc": "security/integrity/ima/ima_appraise.c:210",
      "file": "security/integrity/ima/ima_appraise.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_appraise.c:ima_appraise_measurement"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int xattr_verify(enum ima_hooks func, struct integrity_iint_cache * iint, struct evm_ima_xattr_data * xattr_value, int xattr_len, enum integrity_status * status, const char * * cause)
```

```json
{
  "name": "xattr_verify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584201696,
      "name": "xattr_verify",
      "external": false,
      "loc": "security/integrity/ima/ima_appraise.c:216",
      "file": "security/integrity/ima/ima_appraise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_appraise.c:ima_appraise_measurement",
        "security/integrity/ima/ima_appraise.c:ima_appraise_measurement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584201696,
      "name": "xattr_verify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 397
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
int xattr_verify(enum ima_hooks func, struct integrity_iint_cache * iint, struct evm_ima_xattr_data * xattr_value, int xattr_len, enum integrity_status * status, const char * * cause)
```

```json
{
  "name": "xattr_verify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584320080,
      "name": "xattr_verify",
      "external": false,
      "loc": "security/integrity/ima/ima_appraise.c:232",
      "file": "security/integrity/ima/ima_appraise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_appraise.c:ima_appraise_measurement",
        "security/integrity/ima/ima_appraise.c:ima_appraise_measurement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584320080,
      "name": "xattr_verify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 397
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
int xattr_verify(enum ima_hooks func, struct integrity_iint_cache * iint, struct evm_ima_xattr_data * xattr_value, int xattr_len, enum integrity_status * status, const char * * cause)
```

```json
{
  "name": "xattr_verify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584354672,
      "name": "xattr_verify",
      "external": false,
      "loc": "security/integrity/ima/ima_appraise.c:234",
      "file": "security/integrity/ima/ima_appraise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_appraise.c:ima_appraise_measurement",
        "security/integrity/ima/ima_appraise.c:ima_appraise_measurement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584354672,
      "name": "xattr_verify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 390
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
int xattr_verify(enum ima_hooks func, struct integrity_iint_cache * iint, struct evm_ima_xattr_data * xattr_value, int xattr_len, enum integrity_status * status, const char * * cause)
```

```json
{
  "name": "xattr_verify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584747248,
      "name": "xattr_verify",
      "external": false,
      "loc": "security/integrity/ima/ima_appraise.c:235",
      "file": "security/integrity/ima/ima_appraise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_appraise.c:ima_appraise_measurement",
        "security/integrity/ima/ima_appraise.c:ima_appraise_measurement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584747248,
      "name": "xattr_verify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 393
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
int xattr_verify(enum ima_hooks func, struct integrity_iint_cache * iint, struct evm_ima_xattr_data * xattr_value, int xattr_len, enum integrity_status * status, const char * * cause)
```

```json
{
  "name": "xattr_verify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585427472,
      "name": "xattr_verify",
      "external": false,
      "loc": "security/integrity/ima/ima_appraise.c:277",
      "file": "security/integrity/ima/ima_appraise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_appraise.c:ima_appraise_measurement",
        "security/integrity/ima/ima_appraise.c:ima_appraise_measurement",
        "security/integrity/ima/ima_appraise.c:ima_appraise_measurement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585427472,
      "name": "xattr_verify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 763
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
int xattr_verify(enum ima_hooks func, struct integrity_iint_cache * iint, struct evm_ima_xattr_data * xattr_value, int xattr_len, enum integrity_status * status, const char * * cause)
```

```json
{
  "name": "xattr_verify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586183120,
      "name": "xattr_verify",
      "external": false,
      "loc": "security/integrity/ima/ima_appraise.c:277",
      "file": "security/integrity/ima/ima_appraise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_appraise.c:ima_appraise_measurement",
        "security/integrity/ima/ima_appraise.c:ima_appraise_measurement",
        "security/integrity/ima/ima_appraise.c:ima_appraise_measurement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586183120,
      "name": "xattr_verify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 763
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
int xattr_verify(enum ima_hooks func, struct integrity_iint_cache * iint, struct evm_ima_xattr_data * xattr_value, int xattr_len, enum integrity_status * status, const char * * cause)
```

```json
{
  "name": "xattr_verify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586420800,
      "name": "xattr_verify",
      "external": false,
      "loc": "security/integrity/ima/ima_appraise.c:280",
      "file": "security/integrity/ima/ima_appraise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_appraise.c:ima_appraise_measurement",
        "security/integrity/ima/ima_appraise.c:ima_appraise_measurement",
        "security/integrity/ima/ima_appraise.c:ima_appraise_measurement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586420800,
      "name": "xattr_verify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 766
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
int xattr_verify(enum ima_hooks func, struct integrity_iint_cache * iint, struct evm_ima_xattr_data * xattr_value, int xattr_len, enum integrity_status * status, const char * * cause)
```

```json
{
  "name": "xattr_verify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586685792,
      "name": "xattr_verify",
      "external": false,
      "loc": "security/integrity/ima/ima_appraise.c:279",
      "file": "security/integrity/ima/ima_appraise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_appraise.c:ima_appraise_measurement",
        "security/integrity/ima/ima_appraise.c:ima_appraise_measurement",
        "security/integrity/ima/ima_appraise.c:ima_appraise_measurement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586685792,
      "name": "xattr_verify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 766
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
  "name": "xattr_verify",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336495613884,
      "name": "xattr_verify",
      "external": false,
      "loc": "security/integrity/ima/ima_appraise.c:210",
      "file": "security/integrity/ima/ima_appraise.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_appraise.c:ima_appraise_measurement"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "xattr_verify",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3228973216,
      "name": "xattr_verify",
      "external": false,
      "loc": "security/integrity/ima/ima_appraise.c:210",
      "file": "security/integrity/ima/ima_appraise.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_appraise.c:ima_appraise_measurement"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "xattr_verify",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055289728840,
      "name": "xattr_verify",
      "external": false,
      "loc": "security/integrity/ima/ima_appraise.c:210",
      "file": "security/integrity/ima/ima_appraise.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_appraise.c:ima_appraise_measurement"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "xattr_verify",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274773956,
      "name": "xattr_verify",
      "external": false,
      "loc": "security/integrity/ima/ima_appraise.c:210",
      "file": "security/integrity/ima/ima_appraise.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_appraise.c:ima_appraise_measurement"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xattr_verify",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583777770,
      "name": "xattr_verify",
      "external": false,
      "loc": "security/integrity/ima/ima_appraise.c:210",
      "file": "security/integrity/ima/ima_appraise.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_appraise.c:ima_appraise_measurement"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xattr_verify",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583714826,
      "name": "xattr_verify",
      "external": false,
      "loc": "security/integrity/ima/ima_appraise.c:210",
      "file": "security/integrity/ima/ima_appraise.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_appraise.c:ima_appraise_measurement"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xattr_verify",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583761530,
      "name": "xattr_verify",
      "external": false,
      "loc": "security/integrity/ima/ima_appraise.c:210",
      "file": "security/integrity/ima/ima_appraise.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_appraise.c:ima_appraise_measurement"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xattr_verify",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583862522,
      "name": "xattr_verify",
      "external": false,
      "loc": "security/integrity/ima/ima_appraise.c:210",
      "file": "security/integrity/ima/ima_appraise.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_appraise.c:ima_appraise_measurement"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int xattr_verify(enum ima_hooks func, struct integrity_iint_cache * iint, struct evm_ima_xattr_data * xattr_value, int xattr_len, enum integrity_status * status, const char * * cause)
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
