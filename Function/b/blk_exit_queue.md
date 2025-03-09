# Function: <code>blk_exit_queue</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void blk_exit_queue(struct request_queue * q)
```

```json
{
  "name": "blk_exit_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583575088,
      "name": "blk_exit_queue",
      "external": true,
      "loc": "block/blk-core.c:719",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-sysfs.c:__blk_release_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583575088,
      "name": "blk_exit_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void blk_exit_queue(struct request_queue * q)
```

```json
{
  "name": "blk_exit_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583688464,
      "name": "blk_exit_queue",
      "external": true,
      "loc": "block/blk-core.c:294",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-sysfs.c:__blk_release_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583688464,
      "name": "blk_exit_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
  "name": "blk_exit_queue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583884038,
      "name": "blk_exit_queue",
      "external": false,
      "loc": "block/blk-sysfs.c:844",
      "file": "block/blk-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-sysfs.c:__blk_release_queue"
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
  "name": "blk_exit_queue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583987222,
      "name": "blk_exit_queue",
      "external": false,
      "loc": "block/blk-sysfs.c:843",
      "file": "block/blk-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-sysfs.c:__blk_release_queue"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blk_exit_queue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584376118,
      "name": "blk_exit_queue",
      "external": false,
      "loc": "block/blk-sysfs.c:848",
      "file": "block/blk-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-sysfs.c:__blk_release_queue"
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
  "name": "blk_exit_queue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584489865,
      "name": "blk_exit_queue",
      "external": false,
      "loc": "block/blk-sysfs.c:733",
      "file": "block/blk-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-sysfs.c:blk_release_queue"
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
  "name": "blk_exit_queue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584524521,
      "name": "blk_exit_queue",
      "external": false,
      "loc": "block/blk-sysfs.c:751",
      "file": "block/blk-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-sysfs.c:blk_release_queue"
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
  "name": "blk_exit_queue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584935342,
      "name": "blk_exit_queue",
      "external": false,
      "loc": "block/blk-sysfs.c:755",
      "file": "block/blk-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-sysfs.c:blk_release_queue"
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "blk_exit_queue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336495812964,
      "name": "blk_exit_queue",
      "external": false,
      "loc": "block/blk-sysfs.c:843",
      "file": "block/blk-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-sysfs.c:__blk_release_queue"
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
  "name": "blk_exit_queue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3229163884,
      "name": "blk_exit_queue",
      "external": false,
      "loc": "block/blk-sysfs.c:843",
      "file": "block/blk-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-sysfs.c:__blk_release_queue"
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
  "name": "blk_exit_queue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055289999496,
      "name": "blk_exit_queue",
      "external": false,
      "loc": "block/blk-sysfs.c:843",
      "file": "block/blk-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-sysfs.c:__blk_release_queue"
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
  "name": "blk_exit_queue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274949450,
      "name": "blk_exit_queue",
      "external": false,
      "loc": "block/blk-sysfs.c:843",
      "file": "block/blk-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-sysfs.c:__blk_release_queue"
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
  "name": "blk_exit_queue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583955958,
      "name": "blk_exit_queue",
      "external": false,
      "loc": "block/blk-sysfs.c:843",
      "file": "block/blk-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-sysfs.c:__blk_release_queue"
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
  "name": "blk_exit_queue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583892886,
      "name": "blk_exit_queue",
      "external": false,
      "loc": "block/blk-sysfs.c:843",
      "file": "block/blk-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-sysfs.c:__blk_release_queue"
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
  "name": "blk_exit_queue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583939718,
      "name": "blk_exit_queue",
      "external": false,
      "loc": "block/blk-sysfs.c:843",
      "file": "block/blk-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-sysfs.c:__blk_release_queue"
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
  "name": "blk_exit_queue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584041718,
      "name": "blk_exit_queue",
      "external": false,
      "loc": "block/blk-sysfs.c:843",
      "file": "block/blk-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-sysfs.c:__blk_release_queue"
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
void blk_exit_queue(struct request_queue * q)
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
void blk_exit_queue(struct request_queue * q)
```
</details>
</li>
</ul>
