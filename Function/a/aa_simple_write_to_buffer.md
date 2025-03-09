# Function: <code>aa_simple_write_to_buffer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
char * aa_simple_write_to_buffer(const char * userbuf, size_t alloc_size, size_t copy_size, loff_t * pos)
```

```json
{
  "name": "aa_simple_write_to_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582470320,
      "name": "aa_simple_write_to_buffer",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:88",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:policy_update",
        "security/apparmor/apparmorfs.c:profile_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582470320,
      "name": "aa_simple_write_to_buffer",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct aa_loaddata * aa_simple_write_to_buffer(const char * userbuf, size_t alloc_size, size_t copy_size, loff_t * pos)
```

```json
{
  "name": "aa_simple_write_to_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582692752,
      "name": "aa_simple_write_to_buffer",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:91",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582692752,
      "name": "aa_simple_write_to_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
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
struct aa_loaddata * aa_simple_write_to_buffer(const char * userbuf, size_t alloc_size, size_t copy_size, loff_t * pos)
```

```json
{
  "name": "aa_simple_write_to_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582786400,
      "name": "aa_simple_write_to_buffer",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:91",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582786400,
      "name": "aa_simple_write_to_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
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
  "name": "aa_simple_write_to_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582887240,
      "name": "aa_simple_write_to_buffer",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:382",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ],
      "caller_func": [
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582880624,
      "name": "aa_simple_write_to_buffer.isra.24.part.25",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
  "name": "aa_simple_write_to_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583044141,
      "name": "aa_simple_write_to_buffer",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:383",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ],
      "caller_func": [
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583036592,
      "name": "aa_simple_write_to_buffer.isra.26.part.27",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aa_simple_write_to_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583243873,
      "name": "aa_simple_write_to_buffer",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:380",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ],
      "caller_func": [
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583237168,
      "name": "aa_simple_write_to_buffer.isra.31.part.32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aa_simple_write_to_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583362578,
      "name": "aa_simple_write_to_buffer",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:381",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ],
      "caller_func": [
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583354752,
      "name": "aa_simple_write_to_buffer.isra.31.part.32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
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
  "name": "aa_simple_write_to_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583549884,
      "name": "aa_simple_write_to_buffer",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:386",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ],
      "caller_func": [
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583542560,
      "name": "aa_simple_write_to_buffer.isra.0.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aa_simple_write_to_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583655564,
      "name": "aa_simple_write_to_buffer",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:354",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ],
      "caller_func": [
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583647648,
      "name": "aa_simple_write_to_buffer.isra.0.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aa_simple_write_to_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584014604,
      "name": "aa_simple_write_to_buffer",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:384",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ],
      "caller_func": [
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584006224,
      "name": "aa_simple_write_to_buffer.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
  "name": "aa_simple_write_to_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584135068,
      "name": "aa_simple_write_to_buffer",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:384",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ],
      "caller_func": [
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584126000,
      "name": "aa_simple_write_to_buffer.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
  "name": "aa_simple_write_to_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584162088,
      "name": "aa_simple_write_to_buffer",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:384",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ],
      "caller_func": [
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584153184,
      "name": "aa_simple_write_to_buffer.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
  "name": "aa_simple_write_to_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584546088,
      "name": "aa_simple_write_to_buffer",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:384",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ],
      "caller_func": [
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584536240,
      "name": "aa_simple_write_to_buffer.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aa_simple_write_to_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585182224,
      "name": "aa_simple_write_to_buffer",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:387",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585182224,
      "name": "aa_simple_write_to_buffer.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aa_simple_write_to_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585911808,
      "name": "aa_simple_write_to_buffer",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:388",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585911808,
      "name": "aa_simple_write_to_buffer.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aa_simple_write_to_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586143936,
      "name": "aa_simple_write_to_buffer",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:389",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586143936,
      "name": "aa_simple_write_to_buffer.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aa_simple_write_to_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586393120,
      "name": "aa_simple_write_to_buffer",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:389",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586393120,
      "name": "aa_simple_write_to_buffer.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "aa_simple_write_to_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495449768,
      "name": "aa_simple_write_to_buffer",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:354",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ],
      "caller_func": [
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495445672,
      "name": "aa_simple_write_to_buffer.isra.0.part.0",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "aa_simple_write_to_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228815940,
      "name": "aa_simple_write_to_buffer",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:354",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ],
      "caller_func": [
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228809848,
      "name": "aa_simple_write_to_buffer.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "aa_simple_write_to_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055289496464,
      "name": "aa_simple_write_to_buffer",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:354",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ],
      "caller_func": [
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289486240,
      "name": "aa_simple_write_to_buffer.isra.0.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "aa_simple_write_to_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274639570,
      "name": "aa_simple_write_to_buffer",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:354",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ],
      "caller_func": [
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274635990,
      "name": "aa_simple_write_to_buffer.isra.0.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aa_simple_write_to_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583624300,
      "name": "aa_simple_write_to_buffer",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:354",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ],
      "caller_func": [
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583616384,
      "name": "aa_simple_write_to_buffer.isra.0.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aa_simple_write_to_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583561356,
      "name": "aa_simple_write_to_buffer",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:354",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ],
      "caller_func": [
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583553440,
      "name": "aa_simple_write_to_buffer.isra.0.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aa_simple_write_to_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583608076,
      "name": "aa_simple_write_to_buffer",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:354",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ],
      "caller_func": [
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583600160,
      "name": "aa_simple_write_to_buffer.isra.0.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aa_simple_write_to_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583705639,
      "name": "aa_simple_write_to_buffer",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:354",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ],
      "caller_func": [
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583697248,
      "name": "aa_simple_write_to_buffer.isra.0.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>char *</code> ➡️ <code>struct aa_loaddata *</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
struct aa_loaddata * aa_simple_write_to_buffer(const char * userbuf, size_t alloc_size, size_t copy_size, loff_t * pos)
```
</details>
</li>
</ul>
