# Function: <code>evm_xattr_change</code>

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
int evm_xattr_change(struct user_namespace * mnt_userns, struct dentry * dentry, const char * xattr_name, const void * xattr_value, size_t xattr_value_len)
```

```json
{
  "name": "evm_xattr_change",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584754032,
      "name": "evm_xattr_change",
      "external": false,
      "loc": "security/integrity/evm/evm_main.c:504",
      "file": "security/integrity/evm/evm_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/evm/evm_main.c:evm_protect_xattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584754032,
      "name": "evm_xattr_change",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 346
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
int evm_xattr_change(struct user_namespace * mnt_userns, struct dentry * dentry, const char * xattr_name, const void * xattr_value, size_t xattr_value_len)
```

```json
{
  "name": "evm_xattr_change",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585435776,
      "name": "evm_xattr_change",
      "external": false,
      "loc": "security/integrity/evm/evm_main.c:504",
      "file": "security/integrity/evm/evm_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/evm/evm_main.c:evm_protect_xattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585435776,
      "name": "evm_xattr_change",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 373
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "evm_xattr_change",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586193803,
      "name": "evm_xattr_change",
      "external": false,
      "loc": "security/integrity/evm/evm_main.c:449",
      "file": "security/integrity/evm/evm_main.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "evm_xattr_change",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586431227,
      "name": "evm_xattr_change",
      "external": false,
      "loc": "security/integrity/evm/evm_main.c:449",
      "file": "security/integrity/evm/evm_main.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "evm_xattr_change",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586696638,
      "name": "evm_xattr_change",
      "external": false,
      "loc": "security/integrity/evm/evm_main.c:466",
      "file": "security/integrity/evm/evm_main.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
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
int evm_xattr_change(struct user_namespace * mnt_userns, struct dentry * dentry, const char * xattr_name, const void * xattr_value, size_t xattr_value_len)
```
</details>
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
int evm_xattr_change(struct user_namespace * mnt_userns, struct dentry * dentry, const char * xattr_name, const void * xattr_value, size_t xattr_value_len)
```
</details>
</li>
</ul>
