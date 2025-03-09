# Function: <code>__request_region_locked</code>

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
int __request_region_locked(struct resource * res, struct resource * parent, resource_size_t start, resource_size_t n, const char * name, int flags)
```

```json
{
  "name": "__request_region_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__request_region_locked",
      "external": false,
      "loc": "kernel/resource.c:1163",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:__request_free_mem_region",
        "kernel/resource.c:__request_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579552352,
      "name": "__request_region_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 341
    },
    {
      "addr": 18446744071591221489,
      "name": "__request_region_locked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
int __request_region_locked(struct resource * res, struct resource * parent, resource_size_t start, resource_size_t n, const char * name, int flags)
```

```json
{
  "name": "__request_region_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__request_region_locked",
      "external": false,
      "loc": "kernel/resource.c:1163",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:__request_free_mem_region",
        "kernel/resource.c:__request_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579624928,
      "name": "__request_region_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
    },
    {
      "addr": 18446744071592100569,
      "name": "__request_region_locked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
int __request_region_locked(struct resource * res, struct resource * parent, resource_size_t start, resource_size_t n, const char * name, int flags)
```

```json
{
  "name": "__request_region_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__request_region_locked",
      "external": false,
      "loc": "kernel/resource.c:1150",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:__request_free_mem_region",
        "kernel/resource.c:__request_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579719552,
      "name": "__request_region_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 350
    },
    {
      "addr": 18446744071593868138,
      "name": "__request_region_locked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
int __request_region_locked(struct resource * res, struct resource * parent, resource_size_t start, resource_size_t n, const char * name, int flags)
```

```json
{
  "name": "__request_region_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579846448,
      "name": "__request_region_locked",
      "external": false,
      "loc": "kernel/resource.c:1158",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:get_free_mem_region",
        "kernel/resource.c:__request_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579846448,
      "name": "__request_region_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 373
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
int __request_region_locked(struct resource * res, struct resource * parent, resource_size_t start, resource_size_t n, const char * name, int flags)
```

```json
{
  "name": "__request_region_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579896672,
      "name": "__request_region_locked",
      "external": false,
      "loc": "kernel/resource.c:1158",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:get_free_mem_region",
        "kernel/resource.c:__request_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579896672,
      "name": "__request_region_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 373
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
int __request_region_locked(struct resource * res, struct resource * parent, resource_size_t start, resource_size_t n, const char * name, int flags)
```

```json
{
  "name": "__request_region_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579935888,
      "name": "__request_region_locked",
      "external": false,
      "loc": "kernel/resource.c:1213",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:get_free_mem_region",
        "kernel/resource.c:__request_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579935888,
      "name": "__request_region_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 373
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
int __request_region_locked(struct resource * res, struct resource * parent, resource_size_t start, resource_size_t n, const char * name, int flags)
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
