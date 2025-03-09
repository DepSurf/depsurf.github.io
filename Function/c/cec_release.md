# Function: <code>cec_release</code>

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
int cec_release(struct inode * inode, struct file * filp)
```

```json
{
  "name": "cec_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587263936,
      "name": "cec_release",
      "external": false,
      "loc": "drivers/media/cec/cec-api.c:616",
      "file": "drivers/media/cec/cec-api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587263936,
      "name": "cec_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 699
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
int cec_release(struct inode * inode, struct file * filp)
```

```json
{
  "name": "cec_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cec_release",
      "external": false,
      "loc": "drivers/media/cec/cec-api.c:608",
      "file": "drivers/media/cec/cec-api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587532560,
      "name": "cec_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 680
    },
    {
      "addr": 18446744071587537782,
      "name": "cec_release.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int cec_release(struct inode * inode, struct file * filp)
```

```json
{
  "name": "cec_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587735312,
      "name": "cec_release",
      "external": false,
      "loc": "drivers/media/cec/cec-api.c:608",
      "file": "drivers/media/cec/cec-api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587735312,
      "name": "cec_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 682
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int cec_release(struct inode * inode, struct file * filp)
```

```json
{
  "name": "cec_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500911792,
      "name": "cec_release",
      "external": false,
      "loc": "drivers/media/cec/cec-api.c:608",
      "file": "drivers/media/cec/cec-api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500911792,
      "name": "cec_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 600
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int cec_release(struct inode * inode, struct file * filp)
```

```json
{
  "name": "cec_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233430560,
      "name": "cec_release",
      "external": false,
      "loc": "drivers/media/cec/cec-api.c:608",
      "file": "drivers/media/cec/cec-api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3233430560,
      "name": "cec_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 596
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int cec_release(struct inode * inode, struct file * filp)
```

```json
{
  "name": "cec_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294371520,
      "name": "cec_release",
      "external": false,
      "loc": "drivers/media/cec/cec-api.c:608",
      "file": "drivers/media/cec/cec-api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294371520,
      "name": "cec_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 912
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int cec_release(struct inode * inode, struct file * filp)
```

```json
{
  "name": "cec_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277688774,
      "name": "cec_release",
      "external": false,
      "loc": "drivers/media/cec/cec-api.c:608",
      "file": "drivers/media/cec/cec-api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277688774,
      "name": "cec_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 514
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int cec_release(struct inode * inode, struct file * filp)
```

```json
{
  "name": "cec_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587376256,
      "name": "cec_release",
      "external": false,
      "loc": "drivers/media/cec/cec-api.c:608",
      "file": "drivers/media/cec/cec-api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587376256,
      "name": "cec_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 682
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int cec_release(struct inode * inode, struct file * filp)
```

```json
{
  "name": "cec_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587144480,
      "name": "cec_release",
      "external": false,
      "loc": "drivers/media/cec/cec-api.c:608",
      "file": "drivers/media/cec/cec-api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587144480,
      "name": "cec_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 682
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
int cec_release(struct inode * inode, struct file * filp)
```

```json
{
  "name": "cec_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587691456,
      "name": "cec_release",
      "external": false,
      "loc": "drivers/media/cec/cec-api.c:608",
      "file": "drivers/media/cec/cec-api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587691456,
      "name": "cec_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 682
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
int cec_release(struct inode * inode, struct file * filp)
```

```json
{
  "name": "cec_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587797824,
      "name": "cec_release",
      "external": false,
      "loc": "drivers/media/cec/cec-api.c:608",
      "file": "drivers/media/cec/cec-api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587797824,
      "name": "cec_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 682
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int cec_release(struct inode * inode, struct file * filp)
```
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int cec_release(struct inode * inode, struct file * filp)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
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
