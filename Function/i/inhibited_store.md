# Function: <code>inhibited_store</code>

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
ssize_t inhibited_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t len)
```

```json
{
  "name": "inhibited_store",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588487424,
      "name": "inhibited_store",
      "external": false,
      "loc": "drivers/input/input.c:1435",
      "file": "drivers/input/input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588487424,
      "name": "inhibited_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 391
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
ssize_t inhibited_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t len)
```

```json
{
  "name": "inhibited_store",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588373168,
      "name": "inhibited_store",
      "external": false,
      "loc": "drivers/input/input.c:1435",
      "file": "drivers/input/input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588373168,
      "name": "inhibited_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 391
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
ssize_t inhibited_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t len)
```

```json
{
  "name": "inhibited_store",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "inhibited_store",
      "external": false,
      "loc": "drivers/input/input.c:1435",
      "file": "drivers/input/input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589037296,
      "name": "inhibited_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 440
    },
    {
      "addr": 18446744071592620787,
      "name": "inhibited_store.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
ssize_t inhibited_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t len)
```

```json
{
  "name": "inhibited_store",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "inhibited_store",
      "external": false,
      "loc": "drivers/input/input.c:1482",
      "file": "drivers/input/input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590469840,
      "name": "inhibited_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 424
    },
    {
      "addr": 18446744071594504172,
      "name": "inhibited_store.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
ssize_t inhibited_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t len)
```

```json
{
  "name": "inhibited_store",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "inhibited_store",
      "external": false,
      "loc": "drivers/input/input.c:1461",
      "file": "drivers/input/input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592123408,
      "name": "inhibited_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 497
    },
    {
      "addr": 18446744071596304285,
      "name": "inhibited_store.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
ssize_t inhibited_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t len)
```

```json
{
  "name": "inhibited_store",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "inhibited_store",
      "external": false,
      "loc": "drivers/input/input.c:1464",
      "file": "drivers/input/input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592546784,
      "name": "inhibited_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 508
    },
    {
      "addr": 18446744071596833706,
      "name": "inhibited_store.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
ssize_t inhibited_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t len)
```

```json
{
  "name": "inhibited_store",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "inhibited_store",
      "external": false,
      "loc": "drivers/input/input.c:1464",
      "file": "drivers/input/input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593291232,
      "name": "inhibited_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 508
    },
    {
      "addr": 18446744071597757739,
      "name": "inhibited_store.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
ssize_t inhibited_store(struct device * dev, struct device_attribute * attr, const char * buf, size_t len)
```
</details>
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
