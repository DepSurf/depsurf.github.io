# Function: <code>__aafs_setup_d_inode</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int __aafs_setup_d_inode(struct inode * dir, struct dentry * dentry, umode_t mode, void * data, char * link, const struct file_operations * fops, const struct inode_operations * iops)
```

```json
{
  "name": "__aafs_setup_d_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582878192,
      "name": "__aafs_setup_d_inode",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:179",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:aafs_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582878192,
      "name": "__aafs_setup_d_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 295
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__aafs_setup_d_inode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583035952,
      "name": "__aafs_setup_d_inode",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:179",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583035952,
      "name": "__aafs_setup_d_inode.constprop.36",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 287
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__aafs_setup_d_inode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583236544,
      "name": "__aafs_setup_d_inode",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:176",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583236544,
      "name": "__aafs_setup_d_inode.constprop.40",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__aafs_setup_d_inode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583354128,
      "name": "__aafs_setup_d_inode",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:176",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583354128,
      "name": "__aafs_setup_d_inode.constprop.40",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
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
  "name": "__aafs_setup_d_inode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583541920,
      "name": "__aafs_setup_d_inode",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:181",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583541920,
      "name": "__aafs_setup_d_inode.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
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
  "name": "__aafs_setup_d_inode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583647792,
      "name": "__aafs_setup_d_inode",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:181",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583647792,
      "name": "__aafs_setup_d_inode.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
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
  "name": "__aafs_setup_d_inode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584005280,
      "name": "__aafs_setup_d_inode",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:211",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584005280,
      "name": "__aafs_setup_d_inode.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__aafs_setup_d_inode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584125056,
      "name": "__aafs_setup_d_inode",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:211",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584125056,
      "name": "__aafs_setup_d_inode.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__aafs_setup_d_inode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584152240,
      "name": "__aafs_setup_d_inode",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:211",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584152240,
      "name": "__aafs_setup_d_inode.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__aafs_setup_d_inode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584536384,
      "name": "__aafs_setup_d_inode",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:211",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584536384,
      "name": "__aafs_setup_d_inode.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__aafs_setup_d_inode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585177040,
      "name": "__aafs_setup_d_inode",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:214",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585177040,
      "name": "__aafs_setup_d_inode.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
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
  "name": "__aafs_setup_d_inode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585905232,
      "name": "__aafs_setup_d_inode",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:215",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585905232,
      "name": "__aafs_setup_d_inode.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__aafs_setup_d_inode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586136464,
      "name": "__aafs_setup_d_inode",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:216",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586136464,
      "name": "__aafs_setup_d_inode.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__aafs_setup_d_inode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586385696,
      "name": "__aafs_setup_d_inode",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:216",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586385696,
      "name": "__aafs_setup_d_inode.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
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
  "name": "__aafs_setup_d_inode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495439856,
      "name": "__aafs_setup_d_inode",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:181",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495439856,
      "name": "__aafs_setup_d_inode.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "__aafs_setup_d_inode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228807576,
      "name": "__aafs_setup_d_inode",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:181",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3228807576,
      "name": "__aafs_setup_d_inode.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
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
  "name": "__aafs_setup_d_inode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055289484240,
      "name": "__aafs_setup_d_inode",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:181",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289484240,
      "name": "__aafs_setup_d_inode.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 420
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
  "name": "__aafs_setup_d_inode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274633880,
      "name": "__aafs_setup_d_inode",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:181",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274633880,
      "name": "__aafs_setup_d_inode.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
  "name": "__aafs_setup_d_inode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583616528,
      "name": "__aafs_setup_d_inode",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:181",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583616528,
      "name": "__aafs_setup_d_inode.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
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
  "name": "__aafs_setup_d_inode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583553584,
      "name": "__aafs_setup_d_inode",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:181",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583553584,
      "name": "__aafs_setup_d_inode.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
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
  "name": "__aafs_setup_d_inode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583600304,
      "name": "__aafs_setup_d_inode",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:181",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583600304,
      "name": "__aafs_setup_d_inode.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
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
  "name": "__aafs_setup_d_inode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583697392,
      "name": "__aafs_setup_d_inode",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:181",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583697392,
      "name": "__aafs_setup_d_inode.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int __aafs_setup_d_inode(struct inode * dir, struct dentry * dentry, umode_t mode, void * data, char * link, const struct file_operations * fops, const struct inode_operations * iops)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➖</summary>

```c
int __aafs_setup_d_inode(struct inode * dir, struct dentry * dentry, umode_t mode, void * data, char * link, const struct file_operations * fops, const struct inode_operations * iops)
```
</details>
</li>
</ul>
