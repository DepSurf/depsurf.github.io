# Function: <code>blob_to_mnt</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct vfsmount * blob_to_mnt(const void * data, size_t len, const char * name)
```

```json
{
  "name": "blob_to_mnt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579718096,
      "name": "blob_to_mnt",
      "external": false,
      "loc": "kernel/usermode_driver.c:12",
      "file": "kernel/usermode_driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/usermode_driver.c:umd_load_blob"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579718096,
      "name": "blob_to_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 297
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
  "name": "blob_to_mnt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579725587,
      "name": "blob_to_mnt",
      "external": false,
      "loc": "kernel/usermode_driver.c:12",
      "file": "kernel/usermode_driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/usermode_driver.c:umd_load_blob"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blob_to_mnt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579805619,
      "name": "blob_to_mnt",
      "external": false,
      "loc": "kernel/usermode_driver.c:12",
      "file": "kernel/usermode_driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/usermode_driver.c:umd_load_blob"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blob_to_mnt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579915695,
      "name": "blob_to_mnt",
      "external": false,
      "loc": "kernel/usermode_driver.c:12",
      "file": "kernel/usermode_driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/usermode_driver.c:umd_load_blob"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blob_to_mnt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580069999,
      "name": "blob_to_mnt",
      "external": false,
      "loc": "kernel/usermode_driver.c:12",
      "file": "kernel/usermode_driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/usermode_driver.c:umd_load_blob"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blob_to_mnt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580123999,
      "name": "blob_to_mnt",
      "external": false,
      "loc": "kernel/usermode_driver.c:12",
      "file": "kernel/usermode_driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/usermode_driver.c:umd_load_blob"
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
struct vfsmount * blob_to_mnt(const void * data, size_t len, const char * name)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
struct vfsmount * blob_to_mnt(const void * data, size_t len, const char * name)
```
</details>
</li>
</ul>
