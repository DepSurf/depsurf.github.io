# Function: <code>clk_enable_unlock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void clk_enable_unlock(long unsigned int flags)
```

```json
{
  "name": "clk_enable_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586075344,
      "name": "clk_enable_unlock",
      "external": false,
      "loc": "drivers/clk/clk.c:137",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_disable_unused_subtree",
        "drivers/clk/clk.c:clk_enable",
        "drivers/clk/clk.c:__clk_set_parent_before",
        "drivers/clk/clk.c:__clk_set_parent_before",
        "drivers/clk/clk.c:clk_core_set_parent",
        "drivers/clk/clk.c:clk_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586075344,
      "name": "clk_enable_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
void clk_enable_unlock(long unsigned int flags)
```

```json
{
  "name": "clk_enable_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586489568,
      "name": "clk_enable_unlock",
      "external": false,
      "loc": "drivers/clk/clk.c:137",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_unregister",
        "drivers/clk/clk.c:clk_register",
        "drivers/clk/clk.c:clk_core_set_parent",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:__clk_set_parent_before",
        "drivers/clk/clk.c:clk_disable_unused_subtree",
        "drivers/clk/clk.c:clk_core_enable_lock",
        "drivers/clk/clk.c:clk_core_disable_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586489568,
      "name": "clk_enable_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
void clk_enable_unlock(long unsigned int flags)
```

```json
{
  "name": "clk_enable_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584296288,
      "name": "clk_enable_unlock",
      "external": false,
      "loc": "drivers/clk/clk.c:137",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_unregister",
        "drivers/clk/clk.c:clk_register",
        "drivers/clk/clk.c:clk_core_set_parent",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:__clk_set_parent_before",
        "drivers/clk/clk.c:clk_disable_unused_subtree",
        "drivers/clk/clk.c:clk_core_enable_lock",
        "drivers/clk/clk.c:clk_core_disable_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584296288,
      "name": "clk_enable_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
void clk_enable_unlock(long unsigned int flags)
```

```json
{
  "name": "clk_enable_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584373856,
      "name": "clk_enable_unlock",
      "external": false,
      "loc": "drivers/clk/clk.c:137",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_register",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:__clk_set_parent_before",
        "drivers/clk/clk.c:clk_disable_unused_subtree",
        "drivers/clk/clk.c:clk_core_enable_lock",
        "drivers/clk/clk.c:clk_core_disable_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584373856,
      "name": "clk_enable_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void clk_enable_unlock(long unsigned int flags)
```

```json
{
  "name": "clk_enable_unlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584775120,
      "name": "clk_enable_unlock",
      "external": false,
      "loc": "drivers/clk/clk.c:159",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_register",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:__clk_set_parent_before",
        "drivers/clk/clk.c:clk_disable_unused_subtree",
        "drivers/clk/clk.c:clk_core_enable_lock",
        "drivers/clk/clk.c:clk_core_disable_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584775120,
      "name": "clk_enable_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
void clk_enable_unlock(long unsigned int flags)
```

```json
{
  "name": "clk_enable_unlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585001504,
      "name": "clk_enable_unlock",
      "external": false,
      "loc": "drivers/clk/clk.c:169",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_unregister",
        "drivers/clk/clk.c:clk_register",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:__clk_set_parent_before",
        "drivers/clk/clk.c:clk_disable_unused_subtree",
        "drivers/clk/clk.c:clk_core_enable_lock",
        "drivers/clk/clk.c:clk_core_disable_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585001504,
      "name": "clk_enable_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
void clk_enable_unlock(long unsigned int flags)
```

```json
{
  "name": "clk_enable_unlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585106256,
      "name": "clk_enable_unlock",
      "external": false,
      "loc": "drivers/clk/clk.c:167",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_unregister",
        "drivers/clk/clk.c:clk_register",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:__clk_set_parent_before",
        "drivers/clk/clk.c:clk_disable_unused_subtree",
        "drivers/clk/clk.c:clk_core_enable_lock",
        "drivers/clk/clk.c:clk_core_disable_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585106256,
      "name": "clk_enable_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
void clk_enable_unlock(long unsigned int flags)
```

```json
{
  "name": "clk_enable_unlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585314512,
      "name": "clk_enable_unlock",
      "external": false,
      "loc": "drivers/clk/clk.c:177",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_unregister",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:__clk_set_parent_before",
        "drivers/clk/clk.c:clk_disable_unused_subtree",
        "drivers/clk/clk.c:clk_core_enable_lock",
        "drivers/clk/clk.c:clk_core_disable_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585314512,
      "name": "clk_enable_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
void clk_enable_unlock(long unsigned int flags)
```

```json
{
  "name": "clk_enable_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585456848,
      "name": "clk_enable_unlock",
      "external": false,
      "loc": "drivers/clk/clk.c:183",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_unregister",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:__clk_set_parent_before",
        "drivers/clk/clk.c:clk_disable_unused_subtree",
        "drivers/clk/clk.c:clk_core_enable_lock",
        "drivers/clk/clk.c:clk_core_disable_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585456848,
      "name": "clk_enable_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
void clk_enable_unlock(long unsigned int flags)
```

```json
{
  "name": "clk_enable_unlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586168768,
      "name": "clk_enable_unlock",
      "external": false,
      "loc": "drivers/clk/clk.c:187",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_unregister",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:__clk_set_parent_before",
        "drivers/clk/clk.c:__clk_set_parent_before",
        "drivers/clk/clk.c:clk_disable_unused_subtree",
        "drivers/clk/clk.c:clk_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586168768,
      "name": "clk_enable_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
void clk_enable_unlock(long unsigned int flags)
```

```json
{
  "name": "clk_enable_unlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586287296,
      "name": "clk_enable_unlock",
      "external": false,
      "loc": "drivers/clk/clk.c:187",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_unregister",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:__clk_set_parent_before",
        "drivers/clk/clk.c:__clk_set_parent_before",
        "drivers/clk/clk.c:clk_disable_unused_subtree",
        "drivers/clk/clk.c:clk_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586287296,
      "name": "clk_enable_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
void clk_enable_unlock(long unsigned int flags)
```

```json
{
  "name": "clk_enable_unlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586161088,
      "name": "clk_enable_unlock",
      "external": false,
      "loc": "drivers/clk/clk.c:187",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_unregister",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:__clk_set_parent_before",
        "drivers/clk/clk.c:__clk_set_parent_before",
        "drivers/clk/clk.c:clk_disable_unused_subtree",
        "drivers/clk/clk.c:clk_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586161088,
      "name": "clk_enable_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
void clk_enable_unlock(long unsigned int flags)
```

```json
{
  "name": "clk_enable_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586664880,
      "name": "clk_enable_unlock",
      "external": false,
      "loc": "drivers/clk/clk.c:187",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_unregister",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:__clk_set_parent_before",
        "drivers/clk/clk.c:__clk_set_parent_before",
        "drivers/clk/clk.c:clk_disable_unused_subtree",
        "drivers/clk/clk.c:clk_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586664880,
      "name": "clk_enable_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
void clk_enable_unlock(long unsigned int flags)
```

```json
{
  "name": "clk_enable_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587933856,
      "name": "clk_enable_unlock",
      "external": false,
      "loc": "drivers/clk/clk.c:180",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_unregister",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:__clk_set_parent_before",
        "drivers/clk/clk.c:__clk_set_parent_before",
        "drivers/clk/clk.c:clk_disable_unused_subtree",
        "drivers/clk/clk.c:clk_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587933856,
      "name": "clk_enable_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
void clk_enable_unlock(long unsigned int flags)
```

```json
{
  "name": "clk_enable_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589291216,
      "name": "clk_enable_unlock",
      "external": false,
      "loc": "drivers/clk/clk.c:180",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_unregister",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:__clk_set_parent_before",
        "drivers/clk/clk.c:__clk_set_parent_before",
        "drivers/clk/clk.c:clk_disable_unused_subtree",
        "drivers/clk/clk.c:clk_disable_unused_subtree",
        "drivers/clk/clk.c:clk_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589291216,
      "name": "clk_enable_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
void clk_enable_unlock(long unsigned int flags)
```

```json
{
  "name": "clk_enable_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589588064,
      "name": "clk_enable_unlock",
      "external": false,
      "loc": "drivers/clk/clk.c:180",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_unregister",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:__clk_set_parent_before",
        "drivers/clk/clk.c:__clk_set_parent_before",
        "drivers/clk/clk.c:clk_disable_unused_subtree",
        "drivers/clk/clk.c:clk_disable_unused_subtree",
        "drivers/clk/clk.c:clk_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589588064,
      "name": "clk_enable_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
void clk_enable_unlock(long unsigned int flags)
```

```json
{
  "name": "clk_enable_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589897616,
      "name": "clk_enable_unlock",
      "external": false,
      "loc": "drivers/clk/clk.c:180",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_unregister",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:__clk_set_parent_before",
        "drivers/clk/clk.c:__clk_set_parent_before",
        "drivers/clk/clk.c:clk_disable_unused_subtree",
        "drivers/clk/clk.c:clk_disable_unused_subtree",
        "drivers/clk/clk.c:clk_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589897616,
      "name": "clk_enable_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void clk_enable_unlock(long unsigned int flags)
```

```json
{
  "name": "clk_enable_unlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497755104,
      "name": "clk_enable_unlock",
      "external": false,
      "loc": "drivers/clk/clk.c:183",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_unregister",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:__clk_set_parent_before",
        "drivers/clk/clk.c:clk_disable_unused_subtree",
        "drivers/clk/clk.c:clk_core_enable_lock",
        "drivers/clk/clk.c:clk_core_disable_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497755104,
      "name": "clk_enable_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void clk_enable_unlock(long unsigned int flags)
```

```json
{
  "name": "clk_enable_unlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230565284,
      "name": "clk_enable_unlock",
      "external": false,
      "loc": "drivers/clk/clk.c:183",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_unregister",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:__clk_set_parent_before",
        "drivers/clk/clk.c:clk_disable_unused_subtree",
        "drivers/clk/clk.c:clk_core_enable_lock",
        "drivers/clk/clk.c:clk_core_disable_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230565284,
      "name": "clk_enable_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
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
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void clk_enable_unlock(long unsigned int flags)
```

```json
{
  "name": "clk_enable_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275893578,
      "name": "clk_enable_unlock",
      "external": false,
      "loc": "drivers/clk/clk.c:183",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_unregister",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:__clk_set_parent_before",
        "drivers/clk/clk.c:clk_disable_unused_subtree",
        "drivers/clk/clk.c:clk_core_enable_lock",
        "drivers/clk/clk.c:clk_core_disable_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275893578,
      "name": "clk_enable_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
void clk_enable_unlock(long unsigned int flags)
```

```json
{
  "name": "clk_enable_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585219376,
      "name": "clk_enable_unlock",
      "external": false,
      "loc": "drivers/clk/clk.c:183",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_unregister",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:__clk_set_parent_before",
        "drivers/clk/clk.c:clk_disable_unused_subtree",
        "drivers/clk/clk.c:clk_core_enable_lock",
        "drivers/clk/clk.c:clk_core_disable_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585219376,
      "name": "clk_enable_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
void clk_enable_unlock(long unsigned int flags)
```

```json
{
  "name": "clk_enable_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585171552,
      "name": "clk_enable_unlock",
      "external": false,
      "loc": "drivers/clk/clk.c:183",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_unregister",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:__clk_set_parent_before",
        "drivers/clk/clk.c:clk_disable_unused_subtree",
        "drivers/clk/clk.c:clk_core_enable_lock",
        "drivers/clk/clk.c:clk_core_disable_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585171552,
      "name": "clk_enable_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
void clk_enable_unlock(long unsigned int flags)
```

```json
{
  "name": "clk_enable_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585407248,
      "name": "clk_enable_unlock",
      "external": false,
      "loc": "drivers/clk/clk.c:183",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_unregister",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:__clk_set_parent_before",
        "drivers/clk/clk.c:clk_disable_unused_subtree",
        "drivers/clk/clk.c:clk_core_enable_lock",
        "drivers/clk/clk.c:clk_core_disable_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585407248,
      "name": "clk_enable_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
void clk_enable_unlock(long unsigned int flags)
```

```json
{
  "name": "clk_enable_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585514736,
      "name": "clk_enable_unlock",
      "external": false,
      "loc": "drivers/clk/clk.c:183",
      "file": "drivers/clk/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_unregister",
        "drivers/clk/clk.c:__clk_core_init",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:clk_change_rate",
        "drivers/clk/clk.c:__clk_set_parent_before",
        "drivers/clk/clk.c:clk_disable_unused_subtree",
        "drivers/clk/clk.c:clk_core_enable_lock",
        "drivers/clk/clk.c:clk_core_disable_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585514736,
      "name": "clk_enable_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void clk_enable_unlock(long unsigned int flags)
```
</details>
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
