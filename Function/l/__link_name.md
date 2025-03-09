# Function: <code>__link_name</code>

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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void __link_name(struct hash_cell * new_hc)
```

```json
{
  "name": "__link_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588714048,
      "name": "__link_name",
      "external": false,
      "loc": "drivers/md/dm-ioctl.c:132",
      "file": "drivers/md/dm-ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-ioctl.c:dm_hash_rename",
        "drivers/md/dm-ioctl.c:dm_hash_insert",
        "drivers/md/dm-ioctl.c:dm_hash_insert",
        "drivers/md/dm-ioctl.c:dm_hash_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588714048,
      "name": "__link_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void __link_name(struct hash_cell * new_hc)
```

```json
{
  "name": "__link_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__link_name",
      "external": false,
      "loc": "drivers/md/dm-ioctl.c:133",
      "file": "drivers/md/dm-ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-ioctl.c:dm_hash_rename",
        "drivers/md/dm-ioctl.c:dm_hash_insert",
        "drivers/md/dm-ioctl.c:dm_hash_insert",
        "drivers/md/dm-ioctl.c:dm_hash_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589403264,
      "name": "__link_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
    },
    {
      "addr": 18446744071592649545,
      "name": "__link_name.cold",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void __link_name(struct hash_cell * new_hc)
```

```json
{
  "name": "__link_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__link_name",
      "external": false,
      "loc": "drivers/md/dm-ioctl.c:134",
      "file": "drivers/md/dm-ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-ioctl.c:dm_hash_rename",
        "drivers/md/dm-ioctl.c:dm_hash_insert",
        "drivers/md/dm-ioctl.c:dm_hash_insert",
        "drivers/md/dm-ioctl.c:dm_hash_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590879776,
      "name": "__link_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
    },
    {
      "addr": 18446744071594534241,
      "name": "__link_name.cold",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void __link_name(struct hash_cell * new_hc)
```

```json
{
  "name": "__link_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__link_name",
      "external": false,
      "loc": "drivers/md/dm-ioctl.c:134",
      "file": "drivers/md/dm-ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-ioctl.c:dm_hash_rename",
        "drivers/md/dm-ioctl.c:dm_hash_insert",
        "drivers/md/dm-ioctl.c:dm_hash_insert",
        "drivers/md/dm-ioctl.c:dm_hash_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592576480,
      "name": "__link_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
    },
    {
      "addr": 18446744071596312262,
      "name": "__link_name.cold",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void __link_name(struct hash_cell * new_hc)
```

```json
{
  "name": "__link_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__link_name",
      "external": false,
      "loc": "drivers/md/dm-ioctl.c:143",
      "file": "drivers/md/dm-ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-ioctl.c:dm_hash_rename",
        "drivers/md/dm-ioctl.c:dm_hash_insert",
        "drivers/md/dm-ioctl.c:dm_hash_insert",
        "drivers/md/dm-ioctl.c:dm_hash_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593007440,
      "name": "__link_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
    },
    {
      "addr": 18446744071596841179,
      "name": "__link_name.cold",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void __link_name(struct hash_cell * new_hc)
```

```json
{
  "name": "__link_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__link_name",
      "external": false,
      "loc": "drivers/md/dm-ioctl.c:143",
      "file": "drivers/md/dm-ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-ioctl.c:dm_hash_rename",
        "drivers/md/dm-ioctl.c:dm_hash_insert",
        "drivers/md/dm-ioctl.c:dm_hash_insert",
        "drivers/md/dm-ioctl.c:dm_hash_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593758656,
      "name": "__link_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
    },
    {
      "addr": 18446744071597766186,
      "name": "__link_name.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
void __link_name(struct hash_cell * new_hc)
```
</details>
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
