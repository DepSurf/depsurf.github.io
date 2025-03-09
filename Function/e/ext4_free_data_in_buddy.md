# Function: <code>ext4_free_data_in_buddy</code>

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
  "name": "ext4_free_data_in_buddy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582057443,
      "name": "ext4_free_data_in_buddy",
      "external": false,
      "loc": "fs/ext4/mballoc.c:2807",
      "file": "fs/ext4/mballoc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_process_freed_data"
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
  "name": "ext4_free_data_in_buddy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582208707,
      "name": "ext4_free_data_in_buddy",
      "external": false,
      "loc": "fs/ext4/mballoc.c:2807",
      "file": "fs/ext4/mballoc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_process_freed_data"
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
  "name": "ext4_free_data_in_buddy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582398001,
      "name": "ext4_free_data_in_buddy",
      "external": false,
      "loc": "fs/ext4/mballoc.c:2776",
      "file": "fs/ext4/mballoc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_process_freed_data"
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
  "name": "ext4_free_data_in_buddy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582496833,
      "name": "ext4_free_data_in_buddy",
      "external": false,
      "loc": "fs/ext4/mballoc.c:2776",
      "file": "fs/ext4/mballoc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_process_freed_data"
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
  "name": "ext4_free_data_in_buddy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582669030,
      "name": "ext4_free_data_in_buddy",
      "external": false,
      "loc": "fs/ext4/mballoc.c:2778",
      "file": "fs/ext4/mballoc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_process_freed_data"
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
  "name": "ext4_free_data_in_buddy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582771046,
      "name": "ext4_free_data_in_buddy",
      "external": false,
      "loc": "fs/ext4/mballoc.c:2796",
      "file": "fs/ext4/mballoc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_process_freed_data"
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
void ext4_free_data_in_buddy(struct super_block * sb, struct ext4_free_data * entry)
```

```json
{
  "name": "ext4_free_data_in_buddy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583066288,
      "name": "ext4_free_data_in_buddy",
      "external": false,
      "loc": "fs/ext4/mballoc.c:2919",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_process_freed_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583066288,
      "name": "ext4_free_data_in_buddy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 789
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
void ext4_free_data_in_buddy(struct super_block * sb, struct ext4_free_data * entry)
```

```json
{
  "name": "ext4_free_data_in_buddy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583143648,
      "name": "ext4_free_data_in_buddy",
      "external": false,
      "loc": "fs/ext4/mballoc.c:3023",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_process_freed_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583143648,
      "name": "ext4_free_data_in_buddy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 777
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
void ext4_free_data_in_buddy(struct super_block * sb, struct ext4_free_data * entry)
```

```json
{
  "name": "ext4_free_data_in_buddy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583170208,
      "name": "ext4_free_data_in_buddy",
      "external": false,
      "loc": "fs/ext4/mballoc.c:3555",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_process_freed_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583170208,
      "name": "ext4_free_data_in_buddy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 618
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_free_data_in_buddy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583528961,
      "name": "ext4_free_data_in_buddy",
      "external": false,
      "loc": "fs/ext4/mballoc.c:3637",
      "file": "fs/ext4/mballoc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_process_freed_data"
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
  "name": "ext4_free_data_in_buddy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584062286,
      "name": "ext4_free_data_in_buddy",
      "external": false,
      "loc": "fs/ext4/mballoc.c:3634",
      "file": "fs/ext4/mballoc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_process_freed_data"
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
  "name": "ext4_free_data_in_buddy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584695150,
      "name": "ext4_free_data_in_buddy",
      "external": false,
      "loc": "fs/ext4/mballoc.c:3604",
      "file": "fs/ext4/mballoc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_process_freed_data"
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
  "name": "ext4_free_data_in_buddy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584920408,
      "name": "ext4_free_data_in_buddy",
      "external": false,
      "loc": "fs/ext4/mballoc.c:3827",
      "file": "fs/ext4/mballoc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_process_freed_data"
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
  "name": "ext4_free_data_in_buddy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585153274,
      "name": "ext4_free_data_in_buddy",
      "external": false,
      "loc": "fs/ext4/mballoc.c:3851",
      "file": "fs/ext4/mballoc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_process_freed_data"
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
  "name": "ext4_free_data_in_buddy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336494437064,
      "name": "ext4_free_data_in_buddy",
      "external": false,
      "loc": "fs/ext4/mballoc.c:2796",
      "file": "fs/ext4/mballoc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_process_freed_data"
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
  "name": "ext4_free_data_in_buddy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227873084,
      "name": "ext4_free_data_in_buddy",
      "external": false,
      "loc": "fs/ext4/mballoc.c:2796",
      "file": "fs/ext4/mballoc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_process_freed_data"
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
  "name": "ext4_free_data_in_buddy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055288187924,
      "name": "ext4_free_data_in_buddy",
      "external": false,
      "loc": "fs/ext4/mballoc.c:2796",
      "file": "fs/ext4/mballoc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_process_freed_data"
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
  "name": "ext4_free_data_in_buddy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273850118,
      "name": "ext4_free_data_in_buddy",
      "external": false,
      "loc": "fs/ext4/mballoc.c:2796",
      "file": "fs/ext4/mballoc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_process_freed_data"
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
  "name": "ext4_free_data_in_buddy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582739782,
      "name": "ext4_free_data_in_buddy",
      "external": false,
      "loc": "fs/ext4/mballoc.c:2796",
      "file": "fs/ext4/mballoc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_process_freed_data"
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
  "name": "ext4_free_data_in_buddy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582676950,
      "name": "ext4_free_data_in_buddy",
      "external": false,
      "loc": "fs/ext4/mballoc.c:2796",
      "file": "fs/ext4/mballoc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_process_freed_data"
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
  "name": "ext4_free_data_in_buddy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582729638,
      "name": "ext4_free_data_in_buddy",
      "external": false,
      "loc": "fs/ext4/mballoc.c:2796",
      "file": "fs/ext4/mballoc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_process_freed_data"
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
  "name": "ext4_free_data_in_buddy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582814641,
      "name": "ext4_free_data_in_buddy",
      "external": false,
      "loc": "fs/ext4/mballoc.c:2796",
      "file": "fs/ext4/mballoc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_process_freed_data"
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
void ext4_free_data_in_buddy(struct super_block * sb, struct ext4_free_data * entry)
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
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
void ext4_free_data_in_buddy(struct super_block * sb, struct ext4_free_data * entry)
```
</details>
</li>
</ul>
