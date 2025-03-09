# Function: <code>cpu_rmap_release</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cpu_rmap_release(struct kref * ref)
```

```json
{
  "name": "cpu_rmap_release",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583128976,
      "name": "cpu_rmap_release",
      "external": false,
      "loc": "lib/cpu_rmap.c:69",
      "file": "lib/cpu_rmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:irq_cpu_rmap_release",
        "lib/cpu_rmap.c:free_irq_cpu_rmap",
        "lib/cpu_rmap.c:irq_cpu_rmap_add"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583128976,
      "name": "cpu_rmap_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cpu_rmap_release(struct kref * ref)
```

```json
{
  "name": "cpu_rmap_release",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583424372,
      "name": "cpu_rmap_release",
      "external": false,
      "loc": "lib/cpu_rmap.c:69",
      "file": "lib/cpu_rmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:irq_cpu_rmap_add",
        "lib/cpu_rmap.c:irq_cpu_rmap_release",
        "lib/cpu_rmap.c:free_irq_cpu_rmap"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583423440,
      "name": "cpu_rmap_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
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
void cpu_rmap_release(struct kref * ref)
```

```json
{
  "name": "cpu_rmap_release",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583549860,
      "name": "cpu_rmap_release",
      "external": false,
      "loc": "lib/cpu_rmap.c:69",
      "file": "lib/cpu_rmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:irq_cpu_rmap_add",
        "lib/cpu_rmap.c:irq_cpu_rmap_release",
        "lib/cpu_rmap.c:free_irq_cpu_rmap"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583549072,
      "name": "cpu_rmap_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
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
  "name": "cpu_rmap_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583586764,
      "name": "cpu_rmap_release",
      "external": false,
      "loc": "lib/cpu_rmap.c:69",
      "file": "lib/cpu_rmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:cpu_rmap_put"
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
  "name": "cpu_rmap_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583833591,
      "name": "cpu_rmap_release",
      "external": false,
      "loc": "lib/cpu_rmap.c:69",
      "file": "lib/cpu_rmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:irq_cpu_rmap_add",
        "lib/cpu_rmap.c:irq_cpu_rmap_release"
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
  "name": "cpu_rmap_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584034112,
      "name": "cpu_rmap_release",
      "external": false,
      "loc": "lib/cpu_rmap.c:69",
      "file": "lib/cpu_rmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:irq_cpu_rmap_add",
        "lib/cpu_rmap.c:irq_cpu_rmap_release"
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
  "name": "cpu_rmap_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584116848,
      "name": "cpu_rmap_release",
      "external": false,
      "loc": "lib/cpu_rmap.c:69",
      "file": "lib/cpu_rmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:irq_cpu_rmap_add",
        "lib/cpu_rmap.c:irq_cpu_rmap_release"
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
  "name": "cpu_rmap_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584305790,
      "name": "cpu_rmap_release",
      "external": false,
      "loc": "lib/cpu_rmap.c:66",
      "file": "lib/cpu_rmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:irq_cpu_rmap_add",
        "lib/cpu_rmap.c:irq_cpu_rmap_release"
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
  "name": "cpu_rmap_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584440462,
      "name": "cpu_rmap_release",
      "external": false,
      "loc": "lib/cpu_rmap.c:66",
      "file": "lib/cpu_rmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:irq_cpu_rmap_add",
        "lib/cpu_rmap.c:irq_cpu_rmap_release"
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
  "name": "cpu_rmap_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585003267,
      "name": "cpu_rmap_release",
      "external": false,
      "loc": "lib/cpu_rmap.c:66",
      "file": "lib/cpu_rmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:irq_cpu_rmap_add",
        "lib/cpu_rmap.c:irq_cpu_rmap_release"
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
  "name": "cpu_rmap_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585124003,
      "name": "cpu_rmap_release",
      "external": false,
      "loc": "lib/cpu_rmap.c:66",
      "file": "lib/cpu_rmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:irq_cpu_rmap_add",
        "lib/cpu_rmap.c:irq_cpu_rmap_release"
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
  "name": "cpu_rmap_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585004563,
      "name": "cpu_rmap_release",
      "external": false,
      "loc": "lib/cpu_rmap.c:66",
      "file": "lib/cpu_rmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:irq_cpu_rmap_add",
        "lib/cpu_rmap.c:irq_cpu_rmap_release"
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
  "name": "cpu_rmap_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585445667,
      "name": "cpu_rmap_release",
      "external": false,
      "loc": "lib/cpu_rmap.c:66",
      "file": "lib/cpu_rmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:irq_cpu_rmap_add",
        "lib/cpu_rmap.c:irq_cpu_rmap_release"
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
  "name": "cpu_rmap_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586587091,
      "name": "cpu_rmap_release",
      "external": false,
      "loc": "lib/cpu_rmap.c:66",
      "file": "lib/cpu_rmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:irq_cpu_rmap_add",
        "lib/cpu_rmap.c:irq_cpu_rmap_release"
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
  "name": "cpu_rmap_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587827443,
      "name": "cpu_rmap_release",
      "external": false,
      "loc": "lib/cpu_rmap.c:66",
      "file": "lib/cpu_rmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:irq_cpu_rmap_add",
        "lib/cpu_rmap.c:irq_cpu_rmap_release"
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
  "name": "cpu_rmap_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588100579,
      "name": "cpu_rmap_release",
      "external": false,
      "loc": "lib/cpu_rmap.c:66",
      "file": "lib/cpu_rmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:irq_cpu_rmap_add",
        "lib/cpu_rmap.c:irq_cpu_rmap_release"
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
  "name": "cpu_rmap_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588436722,
      "name": "cpu_rmap_release",
      "external": false,
      "loc": "lib/cpu_rmap.c:66",
      "file": "lib/cpu_rmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:irq_cpu_rmap_add",
        "lib/cpu_rmap.c:irq_cpu_rmap_release"
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
  "name": "cpu_rmap_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336496326236,
      "name": "cpu_rmap_release",
      "external": false,
      "loc": "lib/cpu_rmap.c:66",
      "file": "lib/cpu_rmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:cpu_rmap_put"
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
  "name": "cpu_rmap_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3229659908,
      "name": "cpu_rmap_release",
      "external": false,
      "loc": "lib/cpu_rmap.c:66",
      "file": "lib/cpu_rmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:cpu_rmap_put"
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
  "name": "cpu_rmap_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055290644588,
      "name": "cpu_rmap_release",
      "external": false,
      "loc": "lib/cpu_rmap.c:66",
      "file": "lib/cpu_rmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:cpu_rmap_put"
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
  "name": "cpu_rmap_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936275378346,
      "name": "cpu_rmap_release",
      "external": false,
      "loc": "lib/cpu_rmap.c:66",
      "file": "lib/cpu_rmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:irq_cpu_rmap_add",
        "lib/cpu_rmap.c:irq_cpu_rmap_release"
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
  "name": "cpu_rmap_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584409198,
      "name": "cpu_rmap_release",
      "external": false,
      "loc": "lib/cpu_rmap.c:66",
      "file": "lib/cpu_rmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:irq_cpu_rmap_add",
        "lib/cpu_rmap.c:irq_cpu_rmap_release"
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
  "name": "cpu_rmap_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584344398,
      "name": "cpu_rmap_release",
      "external": false,
      "loc": "lib/cpu_rmap.c:66",
      "file": "lib/cpu_rmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:irq_cpu_rmap_add",
        "lib/cpu_rmap.c:irq_cpu_rmap_release"
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
  "name": "cpu_rmap_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584392110,
      "name": "cpu_rmap_release",
      "external": false,
      "loc": "lib/cpu_rmap.c:66",
      "file": "lib/cpu_rmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:irq_cpu_rmap_add",
        "lib/cpu_rmap.c:irq_cpu_rmap_release"
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
  "name": "cpu_rmap_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584498174,
      "name": "cpu_rmap_release",
      "external": false,
      "loc": "lib/cpu_rmap.c:66",
      "file": "lib/cpu_rmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:irq_cpu_rmap_add",
        "lib/cpu_rmap.c:irq_cpu_rmap_release"
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
void cpu_rmap_release(struct kref * ref)
```
</details>
</li>
</ul>
