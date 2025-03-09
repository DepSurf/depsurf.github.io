# Function: <code>__file_mqueue_perm</code>

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
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int __file_mqueue_perm(const char * op, struct aa_label * label, struct aa_label * flabel, struct file * file, u32 request, u32 denied, bool in_atomic)
```

```json
{
  "name": "__file_mqueue_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585299344,
      "name": "__file_mqueue_perm",
      "external": false,
      "loc": "security/apparmor/file.c:553",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/file.c:aa_file_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585299344,
      "name": "__file_mqueue_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 644
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
int __file_mqueue_perm(const char * op, const struct cred * subj_cred, struct aa_label * label, struct aa_label * flabel, struct file * file, u32 request, u32 denied, bool in_atomic)
```

```json
{
  "name": "__file_mqueue_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586038240,
      "name": "__file_mqueue_perm",
      "external": false,
      "loc": "security/apparmor/file.c:696",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/file.c:aa_file_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586038240,
      "name": "__file_mqueue_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 644
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
int __file_mqueue_perm(const char * op, const struct cred * subj_cred, struct aa_label * label, struct aa_label * flabel, struct file * file, u32 request, u32 denied, bool in_atomic)
```

```json
{
  "name": "__file_mqueue_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586273040,
      "name": "__file_mqueue_perm",
      "external": false,
      "loc": "security/apparmor/file.c:716",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/file.c:aa_file_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586273040,
      "name": "__file_mqueue_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 654
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
int __file_mqueue_perm(const char * op, const struct cred * subj_cred, struct aa_label * label, struct aa_label * flabel, struct file * file, u32 request, u32 denied, bool in_atomic)
```

```json
{
  "name": "__file_mqueue_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586529792,
      "name": "__file_mqueue_perm",
      "external": false,
      "loc": "security/apparmor/file.c:723",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/file.c:aa_file_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586529792,
      "name": "__file_mqueue_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 654
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
int __file_mqueue_perm(const char * op, struct aa_label * label, struct aa_label * flabel, struct file * file, u32 request, u32 denied, bool in_atomic)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct cred * subj_cred</code>
</li>
<li>
<b>Param reordered. </b>
<code>op, label, flabel, file, request, denied, in_atomic</code> ➡️ <code>op, subj_cred, label, flabel, file, request, denied, in_atomic</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
