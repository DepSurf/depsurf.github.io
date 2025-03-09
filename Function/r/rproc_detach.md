# Function: <code>rproc_detach</code>

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
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int rproc_detach(struct rproc * rproc)
```

```json
{
  "name": "rproc_detach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rproc_detach",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:2103",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_sysfs.c:state_store",
        "drivers/remoteproc/remoteproc_cdev.c:rproc_cdev_release",
        "drivers/remoteproc/remoteproc_cdev.c:rproc_cdev_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591562839,
      "name": "rproc_detach.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    },
    {
      "addr": 18446744071589001232,
      "name": "rproc_detach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 378
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
int rproc_detach(struct rproc * rproc)
```

```json
{
  "name": "rproc_detach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rproc_detach",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:2123",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_sysfs.c:state_store",
        "drivers/remoteproc/remoteproc_cdev.c:rproc_cdev_release",
        "drivers/remoteproc/remoteproc_cdev.c:rproc_cdev_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592681919,
      "name": "rproc_detach.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    },
    {
      "addr": 18446744071589715088,
      "name": "rproc_detach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 378
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
int rproc_detach(struct rproc * rproc)
```

```json
{
  "name": "rproc_detach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rproc_detach",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:2128",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_sysfs.c:state_store",
        "drivers/remoteproc/remoteproc_cdev.c:rproc_cdev_release",
        "drivers/remoteproc/remoteproc_cdev.c:rproc_cdev_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594567370,
      "name": "rproc_detach.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071591222800,
      "name": "rproc_detach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 450
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
int rproc_detach(struct rproc * rproc)
```

```json
{
  "name": "rproc_detach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592967200,
      "name": "rproc_detach",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:2052",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_sysfs.c:state_store",
        "drivers/remoteproc/remoteproc_cdev.c:rproc_cdev_release",
        "drivers/remoteproc/remoteproc_cdev.c:rproc_cdev_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592967200,
      "name": "rproc_detach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 266
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
int rproc_detach(struct rproc * rproc)
```

```json
{
  "name": "rproc_detach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593417584,
      "name": "rproc_detach",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:2053",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_sysfs.c:state_store",
        "drivers/remoteproc/remoteproc_cdev.c:rproc_cdev_release",
        "drivers/remoteproc/remoteproc_cdev.c:rproc_cdev_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593417584,
      "name": "rproc_detach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 266
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
int rproc_detach(struct rproc * rproc)
```

```json
{
  "name": "rproc_detach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594163536,
      "name": "rproc_detach",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:2053",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_sysfs.c:state_store",
        "drivers/remoteproc/remoteproc_cdev.c:rproc_cdev_release",
        "drivers/remoteproc/remoteproc_cdev.c:rproc_cdev_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594163536,
      "name": "rproc_detach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 266
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
int rproc_detach(struct rproc * rproc)
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
