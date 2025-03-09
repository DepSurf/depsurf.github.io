# Function: <code>__aa_fs_ns_mkdir</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __aa_fs_ns_mkdir(struct aa_ns * ns, struct dentry * parent, const char * name)
```

```json
{
  "name": "__aa_fs_ns_mkdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582476368,
      "name": "__aa_fs_ns_mkdir",
      "external": true,
      "loc": "security/apparmor/apparmorfs.c:721",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir",
        "security/apparmor/policy_ns.c:aa_prepare_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582476368,
      "name": "__aa_fs_ns_mkdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 463
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int __aa_fs_ns_mkdir(struct aa_ns * ns, struct dentry * parent, const char * name, struct dentry * dent)
```

```json
{
  "name": "__aa_fs_ns_mkdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582707616,
      "name": "__aa_fs_ns_mkdir",
      "external": true,
      "loc": "security/apparmor/apparmorfs.c:1217",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir",
        "security/apparmor/policy_ns.c:__aa_create_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582707616,
      "name": "__aa_fs_ns_mkdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1332
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int __aa_fs_ns_mkdir(struct aa_ns * ns, struct dentry * parent, const char * name, struct dentry * dent)
```

```json
{
  "name": "__aa_fs_ns_mkdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582802144,
      "name": "__aa_fs_ns_mkdir",
      "external": true,
      "loc": "security/apparmor/apparmorfs.c:1323",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir",
        "security/apparmor/policy_ns.c:__aa_create_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582802144,
      "name": "__aa_fs_ns_mkdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1397
    }
  ]
}
```
</details>
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
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct dentry * dent</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
int __aa_fs_ns_mkdir(struct aa_ns * ns, struct dentry * parent, const char * name, struct dentry * dent)
```
</details>
</li>
</ul>
