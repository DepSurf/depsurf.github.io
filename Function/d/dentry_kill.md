# Function: <code>dentry_kill</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dentry_kill",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581087989,
      "name": "dentry_kill",
      "external": false,
      "loc": "fs/dcache.c:558",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dcache.c:dput"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dentry_kill",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581253511,
      "name": "dentry_kill",
      "external": false,
      "loc": "fs/dcache.c:561",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dcache.c:dput"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dentry_kill",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581331303,
      "name": "dentry_kill",
      "external": false,
      "loc": "fs/dcache.c:561",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dcache.c:dput"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dentry_kill",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581386997,
      "name": "dentry_kill",
      "external": false,
      "loc": "fs/dcache.c:595",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "dentry_kill",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581527109,
      "name": "dentry_kill",
      "external": false,
      "loc": "fs/dcache.c:602",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct dentry * dentry_kill(struct dentry * dentry)
```

```json
{
  "name": "dentry_kill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581686864,
      "name": "dentry_kill",
      "external": false,
      "loc": "fs/dcache.c:651",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:shrink_dentry_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581686864,
      "name": "dentry_kill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 403
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct dentry * dentry_kill(struct dentry * dentry)
```

```json
{
  "name": "dentry_kill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581774288,
      "name": "dentry_kill",
      "external": false,
      "loc": "fs/dcache.c:664",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:shrink_dentry_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581774288,
      "name": "dentry_kill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 403
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dentry_kill",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581890963,
      "name": "dentry_kill",
      "external": false,
      "loc": "fs/dcache.c:664",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dcache.c:dput"
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
  "name": "dentry_kill",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581963568,
      "name": "dentry_kill",
      "external": false,
      "loc": "fs/dcache.c:664",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dcache.c:dput"
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
struct dentry * dentry_kill(struct dentry * dentry)
```

```json
{
  "name": "dentry_kill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582197744,
      "name": "dentry_kill",
      "external": false,
      "loc": "fs/dcache.c:683",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:dput"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582197744,
      "name": "dentry_kill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 603
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
struct dentry * dentry_kill(struct dentry * dentry)
```

```json
{
  "name": "dentry_kill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582244336,
      "name": "dentry_kill",
      "external": false,
      "loc": "fs/dcache.c:683",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:dput"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582244336,
      "name": "dentry_kill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 435
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
struct dentry * dentry_kill(struct dentry * dentry)
```

```json
{
  "name": "dentry_kill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582269920,
      "name": "dentry_kill",
      "external": false,
      "loc": "fs/dcache.c:686",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:dput"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582269920,
      "name": "dentry_kill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 435
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct dentry * dentry_kill(struct dentry * dentry)
```

```json
{
  "name": "dentry_kill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582588112,
      "name": "dentry_kill",
      "external": false,
      "loc": "fs/dcache.c:686",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:dput"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582588112,
      "name": "dentry_kill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 435
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dentry_kill",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583119844,
      "name": "dentry_kill",
      "external": false,
      "loc": "fs/dcache.c:711",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dcache.c:dput"
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
  "name": "dentry_kill",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583690212,
      "name": "dentry_kill",
      "external": false,
      "loc": "fs/dcache.c:711",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dcache.c:dput"
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
  "name": "dentry_kill",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583908100,
      "name": "dentry_kill",
      "external": false,
      "loc": "fs/dcache.c:711",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dcache.c:dput"
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "dentry_kill",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493464076,
      "name": "dentry_kill",
      "external": false,
      "loc": "fs/dcache.c:664",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dcache.c:dput"
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
  "name": "dentry_kill",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227032120,
      "name": "dentry_kill",
      "external": false,
      "loc": "fs/dcache.c:664",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dcache.c:dput"
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
  "name": "dentry_kill",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287024452,
      "name": "dentry_kill",
      "external": false,
      "loc": "fs/dcache.c:664",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dcache.c:dput"
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
  "name": "dentry_kill",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273146208,
      "name": "dentry_kill",
      "external": false,
      "loc": "fs/dcache.c:664",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dcache.c:dput"
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
  "name": "dentry_kill",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581932304,
      "name": "dentry_kill",
      "external": false,
      "loc": "fs/dcache.c:664",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dcache.c:dput"
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
  "name": "dentry_kill",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581869888,
      "name": "dentry_kill",
      "external": false,
      "loc": "fs/dcache.c:664",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dcache.c:dput"
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
  "name": "dentry_kill",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581923616,
      "name": "dentry_kill",
      "external": false,
      "loc": "fs/dcache.c:664",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dcache.c:dput"
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
  "name": "dentry_kill",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581994482,
      "name": "dentry_kill",
      "external": false,
      "loc": "fs/dcache.c:664",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dcache.c:dput"
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
struct dentry * dentry_kill(struct dentry * dentry)
```
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
struct dentry * dentry_kill(struct dentry * dentry)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
struct dentry * dentry_kill(struct dentry * dentry)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
struct dentry * dentry_kill(struct dentry * dentry)
```
</details>
</li>
</ul>
