# Function: <code>copy_to_high_bio_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_to_high_bio_irq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582863968,
      "name": "copy_to_high_bio_irq",
      "external": false,
      "loc": "block/bounce.c:102",
      "file": "block/bounce.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bounce.c:bounce_end_io_read_isa",
        "block/bounce.c:bounce_end_io_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582863968,
      "name": "copy_to_high_bio_irq.isra.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 365
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_to_high_bio_irq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583149856,
      "name": "copy_to_high_bio_irq",
      "external": false,
      "loc": "block/bounce.c:102",
      "file": "block/bounce.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bounce.c:bounce_end_io_read_isa",
        "block/bounce.c:bounce_end_io_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583149856,
      "name": "copy_to_high_bio_irq.isra.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_to_high_bio_irq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583261792,
      "name": "copy_to_high_bio_irq",
      "external": false,
      "loc": "block/bounce.c:102",
      "file": "block/bounce.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bounce.c:bounce_end_io_read_isa",
        "block/bounce.c:bounce_end_io_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583261792,
      "name": "copy_to_high_bio_irq.isra.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 364
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_to_high_bio_irq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583312576,
      "name": "copy_to_high_bio_irq",
      "external": false,
      "loc": "block/bounce.c:112",
      "file": "block/bounce.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bounce.c:bounce_end_io_read_isa",
        "block/bounce.c:bounce_end_io_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583312576,
      "name": "copy_to_high_bio_irq.isra.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_to_high_bio_irq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583495472,
      "name": "copy_to_high_bio_irq",
      "external": false,
      "loc": "block/bounce.c:113",
      "file": "block/bounce.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bounce.c:bounce_end_io_read_isa",
        "block/bounce.c:bounce_end_io_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583495472,
      "name": "copy_to_high_bio_irq.isra.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void copy_to_high_bio_irq(struct bio * to, struct bio * from)
```

```json
{
  "name": "copy_to_high_bio_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583708992,
      "name": "copy_to_high_bio_irq",
      "external": false,
      "loc": "block/bounce.c:113",
      "file": "block/bounce.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bounce.c:bounce_end_io_read_isa",
        "block/bounce.c:bounce_end_io_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583708992,
      "name": "copy_to_high_bio_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 621
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
void copy_to_high_bio_irq(struct bio * to, struct bio * from)
```

```json
{
  "name": "copy_to_high_bio_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583817200,
      "name": "copy_to_high_bio_irq",
      "external": false,
      "loc": "block/bounce.c:132",
      "file": "block/bounce.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bounce.c:bounce_end_io_read_isa",
        "block/bounce.c:bounce_end_io_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583817200,
      "name": "copy_to_high_bio_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 622
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void copy_to_high_bio_irq(struct bio * to, struct bio * from)
```

```json
{
  "name": "copy_to_high_bio_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584006928,
      "name": "copy_to_high_bio_irq",
      "external": false,
      "loc": "block/bounce.c:132",
      "file": "block/bounce.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bounce.c:bounce_end_io_read_isa",
        "block/bounce.c:bounce_end_io_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584006928,
      "name": "copy_to_high_bio_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 703
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
void copy_to_high_bio_irq(struct bio * to, struct bio * from)
```

```json
{
  "name": "copy_to_high_bio_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584110432,
      "name": "copy_to_high_bio_irq",
      "external": false,
      "loc": "block/bounce.c:132",
      "file": "block/bounce.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bounce.c:bounce_end_io_read_isa",
        "block/bounce.c:bounce_end_io_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584110432,
      "name": "copy_to_high_bio_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 703
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void copy_to_high_bio_irq(struct bio * to, struct bio * from)
```

```json
{
  "name": "copy_to_high_bio_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584506704,
      "name": "copy_to_high_bio_irq",
      "external": false,
      "loc": "block/bounce.c:132",
      "file": "block/bounce.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bounce.c:bounce_end_io_read_isa",
        "block/bounce.c:bounce_end_io_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584506704,
      "name": "copy_to_high_bio_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 655
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
void copy_to_high_bio_irq(struct bio * to, struct bio * from)
```

```json
{
  "name": "copy_to_high_bio_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584617168,
      "name": "copy_to_high_bio_irq",
      "external": false,
      "loc": "block/bounce.c:132",
      "file": "block/bounce.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bounce.c:bounce_end_io_read_isa",
        "block/bounce.c:bounce_end_io_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584617168,
      "name": "copy_to_high_bio_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 582
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void copy_to_high_bio_irq(struct bio * to, struct bio * from)
```

```json
{
  "name": "copy_to_high_bio_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229297324,
      "name": "copy_to_high_bio_irq",
      "external": false,
      "loc": "block/bounce.c:132",
      "file": "block/bounce.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bounce.c:bounce_end_io_read_isa",
        "block/bounce.c:bounce_end_io_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229297324,
      "name": "copy_to_high_bio_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 744
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void copy_to_high_bio_irq(struct bio * to, struct bio * from)
```

```json
{
  "name": "copy_to_high_bio_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584079168,
      "name": "copy_to_high_bio_irq",
      "external": false,
      "loc": "block/bounce.c:132",
      "file": "block/bounce.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bounce.c:bounce_end_io_read_isa",
        "block/bounce.c:bounce_end_io_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584079168,
      "name": "copy_to_high_bio_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 703
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
void copy_to_high_bio_irq(struct bio * to, struct bio * from)
```

```json
{
  "name": "copy_to_high_bio_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584014928,
      "name": "copy_to_high_bio_irq",
      "external": false,
      "loc": "block/bounce.c:132",
      "file": "block/bounce.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bounce.c:bounce_end_io_read_isa",
        "block/bounce.c:bounce_end_io_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584014928,
      "name": "copy_to_high_bio_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 703
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
void copy_to_high_bio_irq(struct bio * to, struct bio * from)
```

```json
{
  "name": "copy_to_high_bio_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584062928,
      "name": "copy_to_high_bio_irq",
      "external": false,
      "loc": "block/bounce.c:132",
      "file": "block/bounce.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bounce.c:bounce_end_io_read_isa",
        "block/bounce.c:bounce_end_io_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584062928,
      "name": "copy_to_high_bio_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 703
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
void copy_to_high_bio_irq(struct bio * to, struct bio * from)
```

```json
{
  "name": "copy_to_high_bio_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584165424,
      "name": "copy_to_high_bio_irq",
      "external": false,
      "loc": "block/bounce.c:132",
      "file": "block/bounce.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bounce.c:bounce_end_io_read_isa",
        "block/bounce.c:bounce_end_io_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584165424,
      "name": "copy_to_high_bio_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 703
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void copy_to_high_bio_irq(struct bio * to, struct bio * from)
```
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void copy_to_high_bio_irq(struct bio * to, struct bio * from)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void copy_to_high_bio_irq(struct bio * to, struct bio * from)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void copy_to_high_bio_irq(struct bio * to, struct bio * from)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void copy_to_high_bio_irq(struct bio * to, struct bio * from)
```
</details>
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
