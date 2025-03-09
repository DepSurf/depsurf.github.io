# Function: <code>__aafs_ns_mkdir_entries</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__aafs_ns_mkdir_entries",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582892345,
      "name": "__aafs_ns_mkdir_entries",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:1785",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__aafs_ns_mkdir_entries",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583050681,
      "name": "__aafs_ns_mkdir_entries",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:1849",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__aafs_ns_mkdir_entries",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583251294,
      "name": "__aafs_ns_mkdir_entries",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:1846",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__aafs_ns_mkdir_entries",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583369310,
      "name": "__aafs_ns_mkdir_entries",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:1844",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__aafs_ns_mkdir_entries",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583556398,
      "name": "__aafs_ns_mkdir_entries",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:1849",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__aafs_ns_mkdir_entries",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583662126,
      "name": "__aafs_ns_mkdir_entries",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:1817",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir"
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
int __aafs_ns_mkdir_entries(struct aa_ns * ns, struct dentry * dir)
```

```json
{
  "name": "__aafs_ns_mkdir_entries",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584010400,
      "name": "__aafs_ns_mkdir_entries",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:1936",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584010400,
      "name": "__aafs_ns_mkdir_entries",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1044
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
int __aafs_ns_mkdir_entries(struct aa_ns * ns, struct dentry * dir)
```

```json
{
  "name": "__aafs_ns_mkdir_entries",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584126480,
      "name": "__aafs_ns_mkdir_entries",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:1936",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584126480,
      "name": "__aafs_ns_mkdir_entries",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1088
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
int __aafs_ns_mkdir_entries(struct aa_ns * ns, struct dentry * dir)
```

```json
{
  "name": "__aafs_ns_mkdir_entries",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584153664,
      "name": "__aafs_ns_mkdir_entries",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:1937",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584153664,
      "name": "__aafs_ns_mkdir_entries",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1072
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
int __aafs_ns_mkdir_entries(struct aa_ns * ns, struct dentry * dir)
```

```json
{
  "name": "__aafs_ns_mkdir_entries",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584537664,
      "name": "__aafs_ns_mkdir_entries",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:1937",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584537664,
      "name": "__aafs_ns_mkdir_entries",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1072
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
int __aafs_ns_mkdir_entries(struct aa_ns * ns, struct dentry * dir)
```

```json
{
  "name": "__aafs_ns_mkdir_entries",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585183488,
      "name": "__aafs_ns_mkdir_entries",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:1957",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585183488,
      "name": "__aafs_ns_mkdir_entries",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1108
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
int __aafs_ns_mkdir_entries(struct aa_ns * ns, struct dentry * dir)
```

```json
{
  "name": "__aafs_ns_mkdir_entries",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585912352,
      "name": "__aafs_ns_mkdir_entries",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:2146",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585912352,
      "name": "__aafs_ns_mkdir_entries",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1108
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
int __aafs_ns_mkdir_entries(struct aa_ns * ns, struct dentry * dir)
```

```json
{
  "name": "__aafs_ns_mkdir_entries",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586144480,
      "name": "__aafs_ns_mkdir_entries",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:2194",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586144480,
      "name": "__aafs_ns_mkdir_entries",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1108
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
int __aafs_ns_mkdir_entries(struct aa_ns * ns, struct dentry * dir)
```

```json
{
  "name": "__aafs_ns_mkdir_entries",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586393664,
      "name": "__aafs_ns_mkdir_entries",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:2192",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586393664,
      "name": "__aafs_ns_mkdir_entries",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1108
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
  "name": "__aafs_ns_mkdir_entries",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336495455064,
      "name": "__aafs_ns_mkdir_entries",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:1817",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir"
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
  "name": "__aafs_ns_mkdir_entries",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3228822032,
      "name": "__aafs_ns_mkdir_entries",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:1817",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir"
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
  "name": "__aafs_ns_mkdir_entries",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055289504916,
      "name": "__aafs_ns_mkdir_entries",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:1817",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir"
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
  "name": "__aafs_ns_mkdir_entries",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274644110,
      "name": "__aafs_ns_mkdir_entries",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:1817",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir"
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
  "name": "__aafs_ns_mkdir_entries",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583630862,
      "name": "__aafs_ns_mkdir_entries",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:1817",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir"
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
  "name": "__aafs_ns_mkdir_entries",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583567918,
      "name": "__aafs_ns_mkdir_entries",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:1817",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir"
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
  "name": "__aafs_ns_mkdir_entries",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583614638,
      "name": "__aafs_ns_mkdir_entries",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:1817",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir"
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
  "name": "__aafs_ns_mkdir_entries",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583712494,
      "name": "__aafs_ns_mkdir_entries",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:1817",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir"
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
int __aafs_ns_mkdir_entries(struct aa_ns * ns, struct dentry * dir)
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
