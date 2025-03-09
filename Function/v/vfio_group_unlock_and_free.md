# Function: <code>vfio_group_unlock_and_free</code>

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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void vfio_group_unlock_and_free(struct vfio_group * group)
```

```json
{
  "name": "vfio_group_unlock_and_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587038112,
      "name": "vfio_group_unlock_and_free",
      "external": false,
      "loc": "drivers/vfio/vfio.c:309",
      "file": "drivers/vfio/vfio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio.c:vfio_add_group_dev",
        "drivers/vfio/vfio.c:vfio_add_group_dev",
        "drivers/vfio/vfio.c:vfio_add_group_dev",
        "drivers/vfio/vfio.c:vfio_group_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587038112,
      "name": "vfio_group_unlock_and_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
  "name": "vfio_group_unlock_and_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587871080,
      "name": "vfio_group_unlock_and_free",
      "external": false,
      "loc": "drivers/vfio/vfio.c:310",
      "file": "drivers/vfio/vfio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio.c:vfio_group_release",
        "drivers/vfio/vfio.c:vfio_create_group",
        "drivers/vfio/vfio.c:vfio_create_group",
        "drivers/vfio/vfio.c:vfio_create_group"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vfio_group_unlock_and_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587931512,
      "name": "vfio_group_unlock_and_free",
      "external": false,
      "loc": "drivers/vfio/vfio.c:310",
      "file": "drivers/vfio/vfio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio.c:vfio_group_release",
        "drivers/vfio/vfio.c:vfio_create_group",
        "drivers/vfio/vfio.c:vfio_create_group",
        "drivers/vfio/vfio.c:vfio_create_group"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vfio_group_unlock_and_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587814824,
      "name": "vfio_group_unlock_and_free",
      "external": false,
      "loc": "drivers/vfio/vfio.c:300",
      "file": "drivers/vfio/vfio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio.c:vfio_group_release",
        "drivers/vfio/vfio.c:vfio_create_group",
        "drivers/vfio/vfio.c:vfio_create_group",
        "drivers/vfio/vfio.c:vfio_create_group"
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
  "name": "vfio_group_unlock_and_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588418536,
      "name": "vfio_group_unlock_and_free",
      "external": false,
      "loc": "drivers/vfio/vfio.c:373",
      "file": "drivers/vfio/vfio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio.c:vfio_group_release",
        "drivers/vfio/vfio.c:vfio_create_group",
        "drivers/vfio/vfio.c:vfio_create_group",
        "drivers/vfio/vfio.c:vfio_create_group"
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
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void vfio_group_unlock_and_free(struct vfio_group * group)
```

```json
{
  "name": "vfio_group_unlock_and_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293362944,
      "name": "vfio_group_unlock_and_free",
      "external": false,
      "loc": "drivers/vfio/vfio.c:309",
      "file": "drivers/vfio/vfio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio.c:vfio_add_group_dev",
        "drivers/vfio/vfio.c:vfio_add_group_dev",
        "drivers/vfio/vfio.c:vfio_add_group_dev",
        "drivers/vfio/vfio.c:vfio_group_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293362944,
      "name": "vfio_group_unlock_and_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void vfio_group_unlock_and_free(struct vfio_group * group)
```

```json
{
  "name": "vfio_group_unlock_and_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586686032,
      "name": "vfio_group_unlock_and_free",
      "external": false,
      "loc": "drivers/vfio/vfio.c:309",
      "file": "drivers/vfio/vfio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio.c:vfio_add_group_dev",
        "drivers/vfio/vfio.c:vfio_add_group_dev",
        "drivers/vfio/vfio.c:vfio_add_group_dev",
        "drivers/vfio/vfio.c:vfio_group_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586686032,
      "name": "vfio_group_unlock_and_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void vfio_group_unlock_and_free(struct vfio_group * group)
```

```json
{
  "name": "vfio_group_unlock_and_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586992672,
      "name": "vfio_group_unlock_and_free",
      "external": false,
      "loc": "drivers/vfio/vfio.c:309",
      "file": "drivers/vfio/vfio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio.c:vfio_add_group_dev",
        "drivers/vfio/vfio.c:vfio_add_group_dev",
        "drivers/vfio/vfio.c:vfio_add_group_dev",
        "drivers/vfio/vfio.c:vfio_group_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586992672,
      "name": "vfio_group_unlock_and_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void vfio_group_unlock_and_free(struct vfio_group * group)
```

```json
{
  "name": "vfio_group_unlock_and_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587099840,
      "name": "vfio_group_unlock_and_free",
      "external": false,
      "loc": "drivers/vfio/vfio.c:309",
      "file": "drivers/vfio/vfio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio.c:vfio_add_group_dev",
        "drivers/vfio/vfio.c:vfio_add_group_dev",
        "drivers/vfio/vfio.c:vfio_add_group_dev",
        "drivers/vfio/vfio.c:vfio_group_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587099840,
      "name": "vfio_group_unlock_and_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
void vfio_group_unlock_and_free(struct vfio_group * group)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void vfio_group_unlock_and_free(struct vfio_group * group)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void vfio_group_unlock_and_free(struct vfio_group * group)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void vfio_group_unlock_and_free(struct vfio_group * group)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void vfio_group_unlock_and_free(struct vfio_group * group)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➖</summary>

```c
void vfio_group_unlock_and_free(struct vfio_group * group)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
