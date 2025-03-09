# Function: <code>edac_device_create_instance</code>

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
  "name": "edac_device_create_instance",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586575526,
      "name": "edac_device_create_instance",
      "external": false,
      "loc": "drivers/edac/edac_device_sysfs.c:608",
      "file": "drivers/edac/edac_device_sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs"
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
  "name": "edac_device_create_instance",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587042614,
      "name": "edac_device_create_instance",
      "external": false,
      "loc": "drivers/edac/edac_device_sysfs.c:608",
      "file": "drivers/edac/edac_device_sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs"
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
  "name": "edac_device_create_instance",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587341027,
      "name": "edac_device_create_instance",
      "external": false,
      "loc": "drivers/edac/edac_device_sysfs.c:608",
      "file": "drivers/edac/edac_device_sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs"
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
  "name": "edac_device_create_instance",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587519203,
      "name": "edac_device_create_instance",
      "external": false,
      "loc": "drivers/edac/edac_device_sysfs.c:608",
      "file": "drivers/edac/edac_device_sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs"
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
  "name": "edac_device_create_instance",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587793052,
      "name": "edac_device_create_instance",
      "external": false,
      "loc": "drivers/edac/edac_device_sysfs.c:608",
      "file": "drivers/edac/edac_device_sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs"
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
  "name": "edac_device_create_instance",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587997772,
      "name": "edac_device_create_instance",
      "external": false,
      "loc": "drivers/edac/edac_device_sysfs.c:608",
      "file": "drivers/edac/edac_device_sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs"
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
int edac_device_create_instance(struct edac_device_ctl_info * edac_dev, int idx)
```

```json
{
  "name": "edac_device_create_instance",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588851296,
      "name": "edac_device_create_instance",
      "external": false,
      "loc": "drivers/edac/edac_device_sysfs.c:609",
      "file": "drivers/edac/edac_device_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588851296,
      "name": "edac_device_create_instance",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 385
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
int edac_device_create_instance(struct edac_device_ctl_info * edac_dev, int idx)
```

```json
{
  "name": "edac_device_create_instance",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588866672,
      "name": "edac_device_create_instance",
      "external": false,
      "loc": "drivers/edac/edac_device_sysfs.c:609",
      "file": "drivers/edac/edac_device_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588866672,
      "name": "edac_device_create_instance",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 385
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
  "name": "edac_device_create_instance",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588753452,
      "name": "edac_device_create_instance",
      "external": false,
      "loc": "drivers/edac/edac_device_sysfs.c:609",
      "file": "drivers/edac/edac_device_sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_device_sysfs.c:edac_device_create_instances"
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
  "name": "edac_device_create_instance",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589444908,
      "name": "edac_device_create_instance",
      "external": false,
      "loc": "drivers/edac/edac_device_sysfs.c:609",
      "file": "drivers/edac/edac_device_sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_device_sysfs.c:edac_device_create_instances"
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
  "name": "edac_device_create_instance",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590923580,
      "name": "edac_device_create_instance",
      "external": false,
      "loc": "drivers/edac/edac_device_sysfs.c:609",
      "file": "drivers/edac/edac_device_sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_device_sysfs.c:edac_device_create_instances"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int edac_device_create_instance(struct edac_device_ctl_info * edac_dev, int idx)
```

```json
{
  "name": "edac_device_create_instance",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592623312,
      "name": "edac_device_create_instance",
      "external": false,
      "loc": "drivers/edac/edac_device_sysfs.c:609",
      "file": "drivers/edac/edac_device_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592623312,
      "name": "edac_device_create_instance",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 648
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
int edac_device_create_instance(struct edac_device_ctl_info * edac_dev, int idx)
```

```json
{
  "name": "edac_device_create_instance",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593053904,
      "name": "edac_device_create_instance",
      "external": false,
      "loc": "drivers/edac/edac_device_sysfs.c:611",
      "file": "drivers/edac/edac_device_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593053904,
      "name": "edac_device_create_instance",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 638
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
int edac_device_create_instance(struct edac_device_ctl_info * edac_dev, int idx)
```

```json
{
  "name": "edac_device_create_instance",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593805696,
      "name": "edac_device_create_instance",
      "external": false,
      "loc": "drivers/edac/edac_device_sysfs.c:611",
      "file": "drivers/edac/edac_device_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593805696,
      "name": "edac_device_create_instance",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 638
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
  "name": "edac_device_create_instance",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336501243456,
      "name": "edac_device_create_instance",
      "external": false,
      "loc": "drivers/edac/edac_device_sysfs.c:608",
      "file": "drivers/edac/edac_device_sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs"
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
  "name": "edac_device_create_instance",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3233746360,
      "name": "edac_device_create_instance",
      "external": false,
      "loc": "drivers/edac/edac_device_sysfs.c:608",
      "file": "drivers/edac/edac_device_sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs"
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
  "name": "edac_device_create_instance",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055294776784,
      "name": "edac_device_create_instance",
      "external": false,
      "loc": "drivers/edac/edac_device_sysfs.c:608",
      "file": "drivers/edac/edac_device_sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs"
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
  "name": "edac_device_create_instance",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936277936354,
      "name": "edac_device_create_instance",
      "external": false,
      "loc": "drivers/edac/edac_device_sysfs.c:608",
      "file": "drivers/edac/edac_device_sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs"
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
  "name": "edac_device_create_instance",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587628748,
      "name": "edac_device_create_instance",
      "external": false,
      "loc": "drivers/edac/edac_device_sysfs.c:608",
      "file": "drivers/edac/edac_device_sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs"
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
  "name": "edac_device_create_instance",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587396764,
      "name": "edac_device_create_instance",
      "external": false,
      "loc": "drivers/edac/edac_device_sysfs.c:608",
      "file": "drivers/edac/edac_device_sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs"
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
  "name": "edac_device_create_instance",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587953916,
      "name": "edac_device_create_instance",
      "external": false,
      "loc": "drivers/edac/edac_device_sysfs.c:608",
      "file": "drivers/edac/edac_device_sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs"
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
  "name": "edac_device_create_instance",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588069260,
      "name": "edac_device_create_instance",
      "external": false,
      "loc": "drivers/edac/edac_device_sysfs.c:608",
      "file": "drivers/edac/edac_device_sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_device_sysfs.c:edac_device_create_sysfs"
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
int edac_device_create_instance(struct edac_device_ctl_info * edac_dev, int idx)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int edac_device_create_instance(struct edac_device_ctl_info * edac_dev, int idx)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
int edac_device_create_instance(struct edac_device_ctl_info * edac_dev, int idx)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
