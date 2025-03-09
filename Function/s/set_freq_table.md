# Function: <code>set_freq_table</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_freq_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587314650,
      "name": "set_freq_table",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:119",
      "file": "drivers/devfreq/devfreq.c",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_freq_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587617292,
      "name": "set_freq_table",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:119",
      "file": "drivers/devfreq/devfreq.c",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_freq_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587746640,
      "name": "set_freq_table",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:117",
      "file": "drivers/devfreq/devfreq.c",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_freq_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588050350,
      "name": "set_freq_table",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:117",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/devfreq/devfreq.c:devfreq_add_device"
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
  "name": "set_freq_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588256371,
      "name": "set_freq_table",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:117",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/devfreq/devfreq.c:devfreq_add_device"
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
int set_freq_table(struct devfreq * devfreq)
```

```json
{
  "name": "set_freq_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589126864,
      "name": "set_freq_table",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:170",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:devfreq_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589126864,
      "name": "set_freq_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 270
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
int set_freq_table(struct devfreq * devfreq)
```

```json
{
  "name": "set_freq_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589125280,
      "name": "set_freq_table",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:177",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:devfreq_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589125280,
      "name": "set_freq_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 270
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
  "name": "set_freq_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589024227,
      "name": "set_freq_table",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:178",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/devfreq/devfreq.c:devfreq_add_device"
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
  "name": "set_freq_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589739859,
      "name": "set_freq_table",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:178",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/devfreq/devfreq.c:devfreq_add_device"
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
  "name": "set_freq_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591250639,
      "name": "set_freq_table",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:179",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/devfreq/devfreq.c:devfreq_add_device"
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
  "name": "set_freq_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593004152,
      "name": "set_freq_table",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:179",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/devfreq/devfreq.c:devfreq_add_device"
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
  "name": "set_freq_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593455656,
      "name": "set_freq_table",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:179",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/devfreq/devfreq.c:devfreq_add_device"
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
  "name": "set_freq_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594202587,
      "name": "set_freq_table",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:179",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/devfreq/devfreq.c:devfreq_add_device"
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
  "name": "set_freq_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336501715180,
      "name": "set_freq_table",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:117",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/devfreq/devfreq.c:devfreq_add_device"
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
  "name": "set_freq_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3234238820,
      "name": "set_freq_table",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:117",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/devfreq/devfreq.c:devfreq_add_device"
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
  "name": "set_freq_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055295159708,
      "name": "set_freq_table",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:117",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/devfreq/devfreq.c:devfreq_add_device"
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
  "name": "set_freq_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278132110,
      "name": "set_freq_table",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:117",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/devfreq/devfreq.c:devfreq_add_device"
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
  "name": "set_freq_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587868067,
      "name": "set_freq_table",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:117",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/devfreq/devfreq.c:devfreq_add_device"
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
  "name": "set_freq_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587594867,
      "name": "set_freq_table",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:117",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/devfreq/devfreq.c:devfreq_add_device"
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
  "name": "set_freq_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588193427,
      "name": "set_freq_table",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:117",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/devfreq/devfreq.c:devfreq_add_device"
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
  "name": "set_freq_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588328723,
      "name": "set_freq_table",
      "external": false,
      "loc": "drivers/devfreq/devfreq.c:117",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/devfreq/devfreq.c:devfreq_add_device"
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
int set_freq_table(struct devfreq * devfreq)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int set_freq_table(struct devfreq * devfreq)
```
</details>
</li>
</ul>
