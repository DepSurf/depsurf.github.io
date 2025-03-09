# Function: <code>map_irq_stack</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "map_irq_stack",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579059560,
      "name": "map_irq_stack",
      "external": false,
      "loc": "arch/x86/kernel/irq_64.c:42",
      "file": "arch/x86/kernel/irq_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/irq_64.c:irq_init_percpu_irqstack"
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
  "name": "map_irq_stack",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579061752,
      "name": "map_irq_stack",
      "external": false,
      "loc": "arch/x86/kernel/irq_64.c:33",
      "file": "arch/x86/kernel/irq_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/irq_64.c:irq_init_percpu_irqstack"
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
int map_irq_stack(unsigned int cpu)
```

```json
{
  "name": "map_irq_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579069328,
      "name": "map_irq_stack",
      "external": false,
      "loc": "arch/x86/kernel/irq_64.c:34",
      "file": "arch/x86/kernel/irq_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/irq_64.c:irq_init_percpu_irqstack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579069328,
      "name": "map_irq_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
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
int map_irq_stack(unsigned int cpu)
```

```json
{
  "name": "map_irq_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579073888,
      "name": "map_irq_stack",
      "external": false,
      "loc": "arch/x86/kernel/irq_64.c:34",
      "file": "arch/x86/kernel/irq_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/irq_64.c:irq_init_percpu_irqstack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579073888,
      "name": "map_irq_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
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
  "name": "map_irq_stack",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579081064,
      "name": "map_irq_stack",
      "external": false,
      "loc": "arch/x86/kernel/irq_64.c:35",
      "file": "arch/x86/kernel/irq_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/irq_64.c:irq_init_percpu_irqstack"
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
  "name": "map_irq_stack",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579103821,
      "name": "map_irq_stack",
      "external": false,
      "loc": "arch/x86/kernel/irq_64.c:35",
      "file": "arch/x86/kernel/irq_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/irq_64.c:irq_init_percpu_irqstack"
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
  "name": "map_irq_stack",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579134073,
      "name": "map_irq_stack",
      "external": false,
      "loc": "arch/x86/kernel/irq_64.c:35",
      "file": "arch/x86/kernel/irq_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/irq_64.c:irq_init_percpu_irqstack"
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
  "name": "map_irq_stack",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579175145,
      "name": "map_irq_stack",
      "external": false,
      "loc": "arch/x86/kernel/irq_64.c:35",
      "file": "arch/x86/kernel/irq_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/irq_64.c:irq_init_percpu_irqstack"
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
  "name": "map_irq_stack",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579178521,
      "name": "map_irq_stack",
      "external": false,
      "loc": "arch/x86/kernel/irq_64.c:35",
      "file": "arch/x86/kernel/irq_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/irq_64.c:irq_init_percpu_irqstack"
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
  "name": "map_irq_stack",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579207737,
      "name": "map_irq_stack",
      "external": false,
      "loc": "arch/x86/kernel/irq_64.c:35",
      "file": "arch/x86/kernel/irq_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/irq_64.c:irq_init_percpu_irqstack"
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "map_irq_stack",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579062104,
      "name": "map_irq_stack",
      "external": false,
      "loc": "arch/x86/kernel/irq_64.c:33",
      "file": "arch/x86/kernel/irq_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/irq_64.c:irq_init_percpu_irqstack"
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
  "name": "map_irq_stack",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578994840,
      "name": "map_irq_stack",
      "external": false,
      "loc": "arch/x86/kernel/irq_64.c:33",
      "file": "arch/x86/kernel/irq_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/irq_64.c:irq_init_percpu_irqstack"
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
  "name": "map_irq_stack",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579061688,
      "name": "map_irq_stack",
      "external": false,
      "loc": "arch/x86/kernel/irq_64.c:33",
      "file": "arch/x86/kernel/irq_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/irq_64.c:irq_init_percpu_irqstack"
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
  "name": "map_irq_stack",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579065592,
      "name": "map_irq_stack",
      "external": false,
      "loc": "arch/x86/kernel/irq_64.c:33",
      "file": "arch/x86/kernel/irq_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/irq_64.c:irq_init_percpu_irqstack"
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
int map_irq_stack(unsigned int cpu)
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
int map_irq_stack(unsigned int cpu)
```
</details>
</li>
</ul>
