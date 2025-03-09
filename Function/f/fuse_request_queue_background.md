# Function: <code>fuse_request_queue_background</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
bool fuse_request_queue_background(struct fuse_conn * fc, struct fuse_req * req)
```

```json
{
  "name": "fuse_request_queue_background",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582897632,
      "name": "fuse_request_queue_background",
      "external": true,
      "loc": "fs/fuse/dev.c:632",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_send_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582897632,
      "name": "fuse_request_queue_background",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 277
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
bool fuse_request_queue_background(struct fuse_conn * fc, struct fuse_req * req)
```

```json
{
  "name": "fuse_request_queue_background",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fuse_request_queue_background",
      "external": true,
      "loc": "fs/fuse/dev.c:656",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_send_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583077755,
      "name": "fuse_request_queue_background.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071583076624,
      "name": "fuse_request_queue_background",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
  "name": "fuse_request_queue_background",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583169977,
      "name": "fuse_request_queue_background",
      "external": false,
      "loc": "fs/fuse/dev.c:514",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_simple_background"
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
bool fuse_request_queue_background(struct fuse_conn * fc, struct fuse_req * req)
```

```json
{
  "name": "fuse_request_queue_background",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583490688,
      "name": "fuse_request_queue_background",
      "external": false,
      "loc": "fs/fuse/dev.c:514",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_simple_background"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583490688,
      "name": "fuse_request_queue_background",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
bool fuse_request_queue_background(struct fuse_req * req)
```

```json
{
  "name": "fuse_request_queue_background",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583599120,
      "name": "fuse_request_queue_background",
      "external": false,
      "loc": "fs/fuse/dev.c:526",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_simple_background"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583599120,
      "name": "fuse_request_queue_background",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
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
  "name": "fuse_request_queue_background",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583623434,
      "name": "fuse_request_queue_background",
      "external": false,
      "loc": "fs/fuse/dev.c:526",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_simple_background"
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
  "name": "fuse_request_queue_background",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583982458,
      "name": "fuse_request_queue_background",
      "external": false,
      "loc": "fs/fuse/dev.c:526",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_simple_background"
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
  "name": "fuse_request_queue_background",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584567039,
      "name": "fuse_request_queue_background",
      "external": false,
      "loc": "fs/fuse/dev.c:522",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_simple_background"
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
  "name": "fuse_request_queue_background",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585245698,
      "name": "fuse_request_queue_background",
      "external": false,
      "loc": "fs/fuse/dev.c:522",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_simple_background"
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
  "name": "fuse_request_queue_background",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585473517,
      "name": "fuse_request_queue_background",
      "external": false,
      "loc": "fs/fuse/dev.c:524",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_simple_background"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fuse_request_queue_background",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585708541,
      "name": "fuse_request_queue_background",
      "external": false,
      "loc": "fs/fuse/dev.c:524",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_simple_background"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "fuse_request_queue_background",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336494884492,
      "name": "fuse_request_queue_background",
      "external": false,
      "loc": "fs/fuse/dev.c:514",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_simple_background"
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
  "name": "fuse_request_queue_background",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3228298556,
      "name": "fuse_request_queue_background",
      "external": false,
      "loc": "fs/fuse/dev.c:514",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_simple_background"
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
  "name": "fuse_request_queue_background",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055288745504,
      "name": "fuse_request_queue_background",
      "external": false,
      "loc": "fs/fuse/dev.c:514",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_simple_background"
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
  "name": "fuse_request_queue_background",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274200276,
      "name": "fuse_request_queue_background",
      "external": false,
      "loc": "fs/fuse/dev.c:514",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_simple_background"
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
  "name": "fuse_request_queue_background",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583138713,
      "name": "fuse_request_queue_background",
      "external": false,
      "loc": "fs/fuse/dev.c:514",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_simple_background"
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
  "name": "fuse_request_queue_background",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583075865,
      "name": "fuse_request_queue_background",
      "external": false,
      "loc": "fs/fuse/dev.c:514",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_simple_background"
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
  "name": "fuse_request_queue_background",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583122745,
      "name": "fuse_request_queue_background",
      "external": false,
      "loc": "fs/fuse/dev.c:514",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_simple_background"
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
  "name": "fuse_request_queue_background",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583217721,
      "name": "fuse_request_queue_background",
      "external": false,
      "loc": "fs/fuse/dev.c:514",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_simple_background"
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
bool fuse_request_queue_background(struct fuse_conn * fc, struct fuse_req * req)
```
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➖</summary>

```c
bool fuse_request_queue_background(struct fuse_conn * fc, struct fuse_req * req)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
bool fuse_request_queue_background(struct fuse_conn * fc, struct fuse_req * req)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct fuse_conn * fc</code>
</li>
<li>
<b>Param reordered. </b>
<code>fc, req</code> ➡️ <code>req</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
bool fuse_request_queue_background(struct fuse_req * req)
```
</details>
</li>
</ul>
