# Function: <code>test_taint</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int test_taint(unsigned int flag)
```

```json
{
  "name": "test_taint",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579372512,
      "name": "test_taint",
      "external": true,
      "loc": "kernel/panic.c:288",
      "file": "kernel/panic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/panic.c:panic"
      ],
      "caller_func": [
        "kernel/module.c:layout_and_allocate",
        "kernel/hung_task.c:watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579372512,
      "name": "test_taint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
int test_taint(unsigned int flag)
```

```json
{
  "name": "test_taint",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580542723,
      "name": "test_taint",
      "external": true,
      "loc": "kernel/panic.c:337",
      "file": "kernel/panic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/panic.c:panic"
      ],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/hung_task.c:watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579380480,
      "name": "test_taint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
int test_taint(unsigned int flag)
```

```json
{
  "name": "test_taint",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580606767,
      "name": "test_taint",
      "external": true,
      "loc": "kernel/panic.c:367",
      "file": "kernel/panic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/panic.c:panic"
      ],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/hung_task.c:watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579399520,
      "name": "test_taint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
int test_taint(unsigned int flag)
```

```json
{
  "name": "test_taint",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579387998,
      "name": "test_taint",
      "external": true,
      "loc": "kernel/panic.c:369",
      "file": "kernel/panic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/panic.c:panic"
      ],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/hung_task.c:watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579386624,
      "name": "test_taint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
int test_taint(unsigned int flag)
```

```json
{
  "name": "test_taint",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579415319,
      "name": "test_taint",
      "external": true,
      "loc": "kernel/panic.c:374",
      "file": "kernel/panic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/panic.c:panic"
      ],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/hung_task.c:watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579413504,
      "name": "test_taint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int test_taint(unsigned int flag)
```

```json
{
  "name": "test_taint",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579429527,
      "name": "test_taint",
      "external": true,
      "loc": "kernel/panic.c:363",
      "file": "kernel/panic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/panic.c:panic"
      ],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/hung_task.c:watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579427952,
      "name": "test_taint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int test_taint(unsigned int flag)
```

```json
{
  "name": "test_taint",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579463153,
      "name": "test_taint",
      "external": true,
      "loc": "kernel/panic.c:398",
      "file": "kernel/panic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/panic.c:panic"
      ],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/hung_task.c:watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579461376,
      "name": "test_taint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int test_taint(unsigned int flag)
```

```json
{
  "name": "test_taint",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579480941,
      "name": "test_taint",
      "external": true,
      "loc": "kernel/panic.c:403",
      "file": "kernel/panic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/panic.c:panic"
      ],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/hung_task.c:watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579479136,
      "name": "test_taint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
int test_taint(unsigned int flag)
```

```json
{
  "name": "test_taint",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579506829,
      "name": "test_taint",
      "external": true,
      "loc": "kernel/panic.c:412",
      "file": "kernel/panic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/panic.c:panic"
      ],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/hung_task.c:watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579505024,
      "name": "test_taint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int test_taint(unsigned int flag)
```

```json
{
  "name": "test_taint",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579535014,
      "name": "test_taint",
      "external": true,
      "loc": "kernel/panic.c:422",
      "file": "kernel/panic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/panic.c:panic"
      ],
      "caller_func": [
        "kernel/module.c:check_module_license_and_versions",
        "kernel/module.c:check_module_license_and_versions",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:set_license",
        "kernel/hung_task.c:check_hung_uninterruptible_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579533440,
      "name": "test_taint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int test_taint(unsigned int flag)
```

```json
{
  "name": "test_taint",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591277150,
      "name": "test_taint",
      "external": true,
      "loc": "kernel/panic.c:422",
      "file": "kernel/panic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/panic.c:panic"
      ],
      "caller_func": [
        "kernel/module.c:check_module_license_and_versions",
        "kernel/module.c:check_module_license_and_versions",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:set_license",
        "kernel/hung_task.c:check_hung_uninterruptible_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579516368,
      "name": "test_taint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int test_taint(unsigned int flag)
```

```json
{
  "name": "test_taint",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591220048,
      "name": "test_taint",
      "external": true,
      "loc": "kernel/panic.c:422",
      "file": "kernel/panic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/panic.c:panic"
      ],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/hung_task.c:check_hung_uninterruptible_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579519520,
      "name": "test_taint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int test_taint(unsigned int flag)
```

```json
{
  "name": "test_taint",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592098593,
      "name": "test_taint",
      "external": true,
      "loc": "kernel/panic.c:420",
      "file": "kernel/panic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/panic.c:panic"
      ],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/hung_task.c:check_hung_uninterruptible_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579591232,
      "name": "test_taint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int test_taint(unsigned int flag)
```

```json
{
  "name": "test_taint",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593865971,
      "name": "test_taint",
      "external": true,
      "loc": "kernel/panic.c:464",
      "file": "kernel/panic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/panic.c:panic"
      ],
      "caller_func": [
        "kernel/module/main.c:load_module",
        "kernel/module/main.c:load_module",
        "kernel/module/main.c:check_modinfo",
        "kernel/module/main.c:check_modinfo",
        "kernel/hung_task.c:check_hung_uninterruptible_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579682592,
      "name": "test_taint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int test_taint(unsigned int flag)
```

```json
{
  "name": "test_taint",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579804735,
      "name": "test_taint",
      "external": true,
      "loc": "kernel/panic.c:515",
      "file": "kernel/panic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/panic.c:panic"
      ],
      "caller_func": [
        "kernel/module/main.c:load_module",
        "kernel/module/main.c:load_module",
        "kernel/module/main.c:check_modinfo",
        "kernel/module/main.c:check_modinfo",
        "kernel/module/main.c:check_modinfo",
        "kernel/hung_task.c:check_hung_uninterruptible_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579803296,
      "name": "test_taint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int test_taint(unsigned int flag)
```

```json
{
  "name": "test_taint",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579852876,
      "name": "test_taint",
      "external": true,
      "loc": "kernel/panic.c:515",
      "file": "kernel/panic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/panic.c:panic"
      ],
      "caller_func": [
        "kernel/module/main.c:module_augment_kernel_taints",
        "kernel/module/main.c:module_augment_kernel_taints",
        "kernel/module/main.c:module_augment_kernel_taints",
        "kernel/module/main.c:module_augment_kernel_taints",
        "kernel/module/main.c:module_augment_kernel_taints",
        "kernel/hung_task.c:check_hung_uninterruptible_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579851424,
      "name": "test_taint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int test_taint(unsigned int flag)
```

```json
{
  "name": "test_taint",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579890652,
      "name": "test_taint",
      "external": true,
      "loc": "kernel/panic.c:519",
      "file": "kernel/panic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/panic.c:panic"
      ],
      "caller_func": [
        "kernel/module/main.c:module_augment_kernel_taints",
        "kernel/module/main.c:module_augment_kernel_taints",
        "kernel/module/main.c:module_augment_kernel_taints",
        "kernel/module/main.c:module_augment_kernel_taints",
        "kernel/module/main.c:module_augment_kernel_taints",
        "kernel/hung_task.c:check_hung_uninterruptible_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579889232,
      "name": "test_taint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int test_taint(unsigned int flag)
```

```json
{
  "name": "test_taint",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490642068,
      "name": "test_taint",
      "external": true,
      "loc": "kernel/panic.c:412",
      "file": "kernel/panic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/panic.c:panic"
      ],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/hung_task.c:watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490639432,
      "name": "test_taint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int test_taint(unsigned int flag)
```

```json
{
  "name": "test_taint",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224717948,
      "name": "test_taint",
      "external": true,
      "loc": "kernel/panic.c:412",
      "file": "kernel/panic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/panic.c:panic"
      ],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/hung_task.c:watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224715996,
      "name": "test_taint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
int test_taint(unsigned int flag)
```

```json
{
  "name": "test_taint",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283460356,
      "name": "test_taint",
      "external": true,
      "loc": "kernel/panic.c:412",
      "file": "kernel/panic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/panic.c:panic"
      ],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/hung_task.c:watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283457424,
      "name": "test_taint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
int test_taint(unsigned int flag)
```

```json
{
  "name": "test_taint",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271394368,
      "name": "test_taint",
      "external": true,
      "loc": "kernel/panic.c:412",
      "file": "kernel/panic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/panic.c:panic"
      ],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/hung_task.c:watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271392368,
      "name": "test_taint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
int test_taint(unsigned int flag)
```

```json
{
  "name": "test_taint",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579480493,
      "name": "test_taint",
      "external": true,
      "loc": "kernel/panic.c:412",
      "file": "kernel/panic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/panic.c:panic"
      ],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/hung_task.c:watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579478688,
      "name": "test_taint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
int test_taint(unsigned int flag)
```

```json
{
  "name": "test_taint",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579409383,
      "name": "test_taint",
      "external": true,
      "loc": "kernel/panic.c:412",
      "file": "kernel/panic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/panic.c:panic"
      ],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/hung_task.c:watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579407584,
      "name": "test_taint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
int test_taint(unsigned int flag)
```

```json
{
  "name": "test_taint",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579480413,
      "name": "test_taint",
      "external": true,
      "loc": "kernel/panic.c:412",
      "file": "kernel/panic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/panic.c:panic"
      ],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/hung_task.c:watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579478608,
      "name": "test_taint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
int test_taint(unsigned int flag)
```

```json
{
  "name": "test_taint",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579512276,
      "name": "test_taint",
      "external": true,
      "loc": "kernel/panic.c:412",
      "file": "kernel/panic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/panic.c:panic"
      ],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/hung_task.c:watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579510480,
      "name": "test_taint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
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
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
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
