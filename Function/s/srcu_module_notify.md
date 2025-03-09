# Function: <code>srcu_module_notify</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int srcu_module_notify(struct notifier_block * self, long unsigned int val, void * data)
```

```json
{
  "name": "srcu_module_notify",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579993856,
      "name": "srcu_module_notify",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:1342",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579993856,
      "name": "srcu_module_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int srcu_module_notify(struct notifier_block * self, long unsigned int val, void * data)
```

```json
{
  "name": "srcu_module_notify",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580043984,
      "name": "srcu_module_notify",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:1344",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580043984,
      "name": "srcu_module_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
int srcu_module_notify(struct notifier_block * self, long unsigned int val, void * data)
```

```json
{
  "name": "srcu_module_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580099120,
      "name": "srcu_module_notify",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:1359",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580099120,
      "name": "srcu_module_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
int srcu_module_notify(struct notifier_block * self, long unsigned int val, void * data)
```

```json
{
  "name": "srcu_module_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580080640,
      "name": "srcu_module_notify",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:1348",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580080640,
      "name": "srcu_module_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
int srcu_module_notify(struct notifier_block * self, long unsigned int val, void * data)
```

```json
{
  "name": "srcu_module_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580082224,
      "name": "srcu_module_notify",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:1436",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580082224,
      "name": "srcu_module_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
int srcu_module_notify(struct notifier_block * self, long unsigned int val, void * data)
```

```json
{
  "name": "srcu_module_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580218592,
      "name": "srcu_module_notify",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:1435",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580218592,
      "name": "srcu_module_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
int srcu_module_notify(struct notifier_block * self, long unsigned int val, void * data)
```

```json
{
  "name": "srcu_module_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580379120,
      "name": "srcu_module_notify",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:1790",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580379120,
      "name": "srcu_module_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
int srcu_module_notify(struct notifier_block * self, long unsigned int val, void * data)
```

```json
{
  "name": "srcu_module_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580607024,
      "name": "srcu_module_notify",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:1859",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580607024,
      "name": "srcu_module_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int srcu_module_notify(struct notifier_block * self, long unsigned int val, void * data)
```

```json
{
  "name": "srcu_module_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "srcu_module_notify",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:1946",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580678304,
      "name": "srcu_module_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
    },
    {
      "addr": 18446744071596508880,
      "name": "srcu_module_notify.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int srcu_module_notify(struct notifier_block * self, long unsigned int val, void * data)
```

```json
{
  "name": "srcu_module_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "srcu_module_notify",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:1972",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580744976,
      "name": "srcu_module_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
    },
    {
      "addr": 18446744071597406618,
      "name": "srcu_module_notify.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int srcu_module_notify(struct notifier_block * self, long unsigned int val, void * data)
```

```json
{
  "name": "srcu_module_notify",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491245504,
      "name": "srcu_module_notify",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:1344",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491245504,
      "name": "srcu_module_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int srcu_module_notify(struct notifier_block * self, long unsigned int val, void * data)
```

```json
{
  "name": "srcu_module_notify",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225258588,
      "name": "srcu_module_notify",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:1344",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3225258588,
      "name": "srcu_module_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int srcu_module_notify(struct notifier_block * self, long unsigned int val, void * data)
```

```json
{
  "name": "srcu_module_notify",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284148464,
      "name": "srcu_module_notify",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:1344",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284148464,
      "name": "srcu_module_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int srcu_module_notify(struct notifier_block * self, long unsigned int val, void * data)
```

```json
{
  "name": "srcu_module_notify",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271774016,
      "name": "srcu_module_notify",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:1344",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271774016,
      "name": "srcu_module_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int srcu_module_notify(struct notifier_block * self, long unsigned int val, void * data)
```

```json
{
  "name": "srcu_module_notify",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580012720,
      "name": "srcu_module_notify",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:1344",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580012720,
      "name": "srcu_module_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int srcu_module_notify(struct notifier_block * self, long unsigned int val, void * data)
```

```json
{
  "name": "srcu_module_notify",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579951472,
      "name": "srcu_module_notify",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:1344",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579951472,
      "name": "srcu_module_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int srcu_module_notify(struct notifier_block * self, long unsigned int val, void * data)
```

```json
{
  "name": "srcu_module_notify",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580004256,
      "name": "srcu_module_notify",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:1344",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580004256,
      "name": "srcu_module_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int srcu_module_notify(struct notifier_block * self, long unsigned int val, void * data)
```

```json
{
  "name": "srcu_module_notify",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580051584,
      "name": "srcu_module_notify",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:1344",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580051584,
      "name": "srcu_module_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int srcu_module_notify(struct notifier_block * self, long unsigned int val, void * data)
```
</details>
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
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
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
