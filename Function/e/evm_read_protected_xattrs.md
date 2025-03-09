# Function: <code>evm_read_protected_xattrs</code>

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
int evm_read_protected_xattrs(struct dentry * dentry, u8 * buffer, int buffer_size, char type, bool canonical_fmt)
```

```json
{
  "name": "evm_read_protected_xattrs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584754896,
      "name": "evm_read_protected_xattrs",
      "external": true,
      "loc": "security/integrity/evm/evm_main.c:339",
      "file": "security/integrity/evm/evm_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_template_lib.c:ima_eventinodexattrs_init_common",
        "security/integrity/ima/ima_template_lib.c:ima_eventinodexattrs_init_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584754896,
      "name": "evm_read_protected_xattrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 295
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
int evm_read_protected_xattrs(struct dentry * dentry, u8 * buffer, int buffer_size, char type, bool canonical_fmt)
```

```json
{
  "name": "evm_read_protected_xattrs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585436704,
      "name": "evm_read_protected_xattrs",
      "external": true,
      "loc": "security/integrity/evm/evm_main.c:339",
      "file": "security/integrity/evm/evm_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_template_lib.c:ima_eventinodexattrs_init_common",
        "security/integrity/ima/ima_template_lib.c:ima_eventinodexattrs_init_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585436704,
      "name": "evm_read_protected_xattrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 346
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
int evm_read_protected_xattrs(struct dentry * dentry, u8 * buffer, int buffer_size, char type, bool canonical_fmt)
```

```json
{
  "name": "evm_read_protected_xattrs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586194016,
      "name": "evm_read_protected_xattrs",
      "external": true,
      "loc": "security/integrity/evm/evm_main.c:333",
      "file": "security/integrity/evm/evm_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_template_lib.c:ima_eventinodexattrs_init_common",
        "security/integrity/ima/ima_template_lib.c:ima_eventinodexattrs_init_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586194016,
      "name": "evm_read_protected_xattrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 334
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
int evm_read_protected_xattrs(struct dentry * dentry, u8 * buffer, int buffer_size, char type, bool canonical_fmt)
```

```json
{
  "name": "evm_read_protected_xattrs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586431440,
      "name": "evm_read_protected_xattrs",
      "external": true,
      "loc": "security/integrity/evm/evm_main.c:332",
      "file": "security/integrity/evm/evm_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_template_lib.c:ima_eventinodexattrs_init_common",
        "security/integrity/ima/ima_template_lib.c:ima_eventinodexattrs_init_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586431440,
      "name": "evm_read_protected_xattrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 334
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
int evm_read_protected_xattrs(struct dentry * dentry, u8 * buffer, int buffer_size, char type, bool canonical_fmt)
```

```json
{
  "name": "evm_read_protected_xattrs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586697120,
      "name": "evm_read_protected_xattrs",
      "external": true,
      "loc": "security/integrity/evm/evm_main.c:346",
      "file": "security/integrity/evm/evm_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_template_lib.c:ima_eventinodexattrs_init_common",
        "security/integrity/ima/ima_template_lib.c:ima_eventinodexattrs_init_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586697120,
      "name": "evm_read_protected_xattrs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 334
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
int evm_read_protected_xattrs(struct dentry * dentry, u8 * buffer, int buffer_size, char type, bool canonical_fmt)
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
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
