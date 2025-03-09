# Function: <code>rproc_copy_segment</code>

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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void rproc_copy_segment(struct rproc * rproc, void * dest, struct rproc_dump_segment * segment, size_t offset, size_t size)
```

```json
{
  "name": "rproc_copy_segment",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589112469,
      "name": "rproc_copy_segment",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_coredump.c:151",
      "file": "drivers/remoteproc/remoteproc_coredump.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections",
        "drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections",
        "drivers/remoteproc/remoteproc_coredump.c:rproc_coredump",
        "drivers/remoteproc/remoteproc_coredump.c:rproc_coredump",
        "drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589112416,
      "name": "rproc_copy_segment",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
    },
    {
      "addr": 18446744071591619782,
      "name": "rproc_copy_segment.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void rproc_copy_segment(struct rproc * rproc, void * dest, struct rproc_dump_segment * segment, size_t offset, size_t size)
```

```json
{
  "name": "rproc_copy_segment",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589002312,
      "name": "rproc_copy_segment",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_coredump.c:151",
      "file": "drivers/remoteproc/remoteproc_coredump.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections",
        "drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections",
        "drivers/remoteproc/remoteproc_coredump.c:rproc_coredump",
        "drivers/remoteproc/remoteproc_coredump.c:rproc_coredump",
        "drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589002224,
      "name": "rproc_copy_segment",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
    },
    {
      "addr": 18446744071591563171,
      "name": "rproc_copy_segment.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
void rproc_copy_segment(struct rproc * rproc, void * dest, struct rproc_dump_segment * segment, size_t offset, size_t size)
```

```json
{
  "name": "rproc_copy_segment",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rproc_copy_segment",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_coredump.c:151",
      "file": "drivers/remoteproc/remoteproc_coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections",
        "drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections",
        "drivers/remoteproc/remoteproc_coredump.c:rproc_coredump",
        "drivers/remoteproc/remoteproc_coredump.c:rproc_coredump",
        "drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589716544,
      "name": "rproc_copy_segment",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 206
    },
    {
      "addr": 18446744071592683852,
      "name": "rproc_copy_segment.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
void rproc_copy_segment(struct rproc * rproc, void * dest, struct rproc_dump_segment * segment, size_t offset, size_t size)
```

```json
{
  "name": "rproc_copy_segment",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rproc_copy_segment",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_coredump.c:151",
      "file": "drivers/remoteproc/remoteproc_coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections",
        "drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections",
        "drivers/remoteproc/remoteproc_coredump.c:rproc_coredump",
        "drivers/remoteproc/remoteproc_coredump.c:rproc_coredump",
        "drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591224480,
      "name": "rproc_copy_segment",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
    },
    {
      "addr": 18446744071594569260,
      "name": "rproc_copy_segment.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
void rproc_copy_segment(struct rproc * rproc, void * dest, struct rproc_dump_segment * segment, size_t offset, size_t size)
```

```json
{
  "name": "rproc_copy_segment",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rproc_copy_segment",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_coredump.c:151",
      "file": "drivers/remoteproc/remoteproc_coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections",
        "drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections",
        "drivers/remoteproc/remoteproc_coredump.c:rproc_coredump",
        "drivers/remoteproc/remoteproc_coredump.c:rproc_coredump",
        "drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592973248,
      "name": "rproc_copy_segment",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
    },
    {
      "addr": 18446744071596319451,
      "name": "rproc_copy_segment.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
void rproc_copy_segment(struct rproc * rproc, void * dest, struct rproc_dump_segment * segment, size_t offset, size_t size)
```

```json
{
  "name": "rproc_copy_segment",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rproc_copy_segment",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_coredump.c:151",
      "file": "drivers/remoteproc/remoteproc_coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections",
        "drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections",
        "drivers/remoteproc/remoteproc_coredump.c:rproc_coredump",
        "drivers/remoteproc/remoteproc_coredump.c:rproc_coredump",
        "drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593423632,
      "name": "rproc_copy_segment",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
    },
    {
      "addr": 18446744071596849114,
      "name": "rproc_copy_segment.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
void rproc_copy_segment(struct rproc * rproc, void * dest, struct rproc_dump_segment * segment, size_t offset, size_t size)
```

```json
{
  "name": "rproc_copy_segment",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rproc_copy_segment",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_coredump.c:152",
      "file": "drivers/remoteproc/remoteproc_coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections",
        "drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections",
        "drivers/remoteproc/remoteproc_coredump.c:rproc_coredump",
        "drivers/remoteproc/remoteproc_coredump.c:rproc_coredump",
        "drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594169712,
      "name": "rproc_copy_segment",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
    },
    {
      "addr": 18446744071597773825,
      "name": "rproc_copy_segment.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
void rproc_copy_segment(struct rproc * rproc, void * dest, struct rproc_dump_segment * segment, size_t offset, size_t size)
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
