# Function: <code>dm_init_md_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dm_init_md_queue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585805429,
      "name": "dm_init_md_queue",
      "external": false,
      "loc": "drivers/md/dm.c:2220",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_create",
        "drivers/md/dm.c:dm_setup_md_queue",
        "drivers/md/dm.c:dm_setup_md_queue",
        "drivers/md/dm.c:dm_setup_md_queue"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void dm_init_md_queue(struct mapped_device * md)
```

```json
{
  "name": "dm_init_md_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586200859,
      "name": "dm_init_md_queue",
      "external": true,
      "loc": "drivers/md/dm.c:1382",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_create",
        "drivers/md/dm.c:dm_init_normal_md_queue"
      ],
      "caller_func": [
        "drivers/md/dm-rq.c:dm_mq_init_request_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586200192,
      "name": "dm_init_md_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void dm_init_md_queue(struct mapped_device * md)
```

```json
{
  "name": "dm_init_md_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586405344,
      "name": "dm_init_md_queue",
      "external": true,
      "loc": "drivers/md/dm.c:1437",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_create",
        "drivers/md/dm.c:dm_init_normal_md_queue"
      ],
      "caller_func": [
        "drivers/md/dm-rq.c:dm_mq_init_request_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586404672,
      "name": "dm_init_md_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void dm_init_md_queue(struct mapped_device * md)
```

```json
{
  "name": "dm_init_md_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586509901,
      "name": "dm_init_md_queue",
      "external": true,
      "loc": "drivers/md/dm.c:1631",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_setup_md_queue",
        "drivers/md/dm.c:dm_create"
      ],
      "caller_func": [
        "drivers/md/dm-rq.c:dm_mq_init_request_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586508160,
      "name": "dm_init_md_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void dm_init_md_queue(struct mapped_device * md)
```

```json
{
  "name": "dm_init_md_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586977433,
      "name": "dm_init_md_queue",
      "external": true,
      "loc": "drivers/md/dm.c:1622",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_setup_md_queue",
        "drivers/md/dm.c:dm_create"
      ],
      "caller_func": [
        "drivers/md/dm-rq.c:dm_mq_init_request_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586975696,
      "name": "dm_init_md_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void dm_init_md_queue(struct mapped_device * md)
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
void dm_init_md_queue(struct mapped_device * md)
```
</details>
</li>
</ul>
