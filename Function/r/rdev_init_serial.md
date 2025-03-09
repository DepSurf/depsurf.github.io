# Function: <code>rdev_init_serial</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rdev_init_serial",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588729920,
      "name": "rdev_init_serial",
      "external": false,
      "loc": "drivers/md/md.c:148",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:mddev_create_serial_pool",
        "drivers/md/md.c:mddev_create_serial_pool"
      ],
      "caller_func": [
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:mddev_create_serial_pool",
        "drivers/md/md.c:mddev_create_serial_pool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588687392,
      "name": "rdev_init_serial.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rdev_init_serial",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588758290,
      "name": "rdev_init_serial",
      "external": false,
      "loc": "drivers/md/md.c:146",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:mddev_create_serial_pool",
        "drivers/md/md.c:mddev_create_serial_pool"
      ],
      "caller_func": [
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:mddev_create_serial_pool",
        "drivers/md/md.c:mddev_create_serial_pool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588714176,
      "name": "rdev_init_serial.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
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
  "name": "rdev_init_serial",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588643656,
      "name": "rdev_init_serial",
      "external": false,
      "loc": "drivers/md/md.c:146",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:mddev_create_serial_pool",
        "drivers/md/md.c:mddev_create_serial_pool"
      ],
      "caller_func": [
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:mddev_create_serial_pool",
        "drivers/md/md.c:mddev_create_serial_pool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588599232,
      "name": "rdev_init_serial.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
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
  "name": "rdev_init_serial",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589321416,
      "name": "rdev_init_serial",
      "external": false,
      "loc": "drivers/md/md.c:147",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:mddev_create_serial_pool",
        "drivers/md/md.c:mddev_create_serial_pool"
      ],
      "caller_func": [
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:mddev_create_serial_pool",
        "drivers/md/md.c:mddev_create_serial_pool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589276112,
      "name": "rdev_init_serial.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int rdev_init_serial(struct md_rdev * rdev)
```

```json
{
  "name": "rdev_init_serial",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590729136,
      "name": "rdev_init_serial",
      "external": false,
      "loc": "drivers/md/md.c:148",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:mddev_create_serial_pool",
        "drivers/md/md.c:mddev_create_serial_pool",
        "drivers/md/md.c:mddev_create_serial_pool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590729136,
      "name": "rdev_init_serial",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
int rdev_init_serial(struct md_rdev * rdev)
```

```json
{
  "name": "rdev_init_serial",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592404560,
      "name": "rdev_init_serial",
      "external": false,
      "loc": "drivers/md/md.c:160",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:mddev_create_serial_pool",
        "drivers/md/md.c:mddev_create_serial_pool",
        "drivers/md/md.c:mddev_create_serial_pool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592404560,
      "name": "rdev_init_serial",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
int rdev_init_serial(struct md_rdev * rdev)
```

```json
{
  "name": "rdev_init_serial",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592833920,
      "name": "rdev_init_serial",
      "external": false,
      "loc": "drivers/md/md.c:146",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:mddev_create_serial_pool",
        "drivers/md/md.c:mddev_create_serial_pool",
        "drivers/md/md.c:mddev_create_serial_pool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592833920,
      "name": "rdev_init_serial",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
int rdev_init_serial(struct md_rdev * rdev)
```

```json
{
  "name": "rdev_init_serial",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593583328,
      "name": "rdev_init_serial",
      "external": false,
      "loc": "drivers/md/md.c:166",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:mddev_create_serial_pool",
        "drivers/md/md.c:mddev_create_serial_pool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593583328,
      "name": "rdev_init_serial",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
int rdev_init_serial(struct md_rdev * rdev)
```
</details>
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
