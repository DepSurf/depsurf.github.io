# Function: <code>pci_has_legacy_pm_support</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_has_legacy_pm_support",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583274944,
      "name": "pci_has_legacy_pm_support",
      "external": false,
      "loc": "drivers/pci/pci-driver.c:647",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_freeze_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_thaw",
        "drivers/pci/pci-driver.c:pci_pm_resume",
        "drivers/pci/pci-driver.c:pci_pm_poweroff",
        "drivers/pci/pci-driver.c:pci_pm_poweroff",
        "drivers/pci/pci-driver.c:pci_pm_freeze",
        "drivers/pci/pci-driver.c:pci_pm_freeze",
        "drivers/pci/pci-driver.c:pci_pm_suspend",
        "drivers/pci/pci-driver.c:pci_pm_suspend",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583274944,
      "name": "pci_has_legacy_pm_support.isra.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
  "name": "pci_has_legacy_pm_support",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583585904,
      "name": "pci_has_legacy_pm_support",
      "external": false,
      "loc": "drivers/pci/pci-driver.c:647",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff",
        "drivers/pci/pci-driver.c:pci_pm_poweroff",
        "drivers/pci/pci-driver.c:pci_pm_thaw",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_pm_freeze_noirq",
        "drivers/pci/pci-driver.c:pci_pm_freeze",
        "drivers/pci/pci-driver.c:pci_pm_freeze",
        "drivers/pci/pci-driver.c:pci_pm_resume",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend",
        "drivers/pci/pci-driver.c:pci_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583585904,
      "name": "pci_has_legacy_pm_support.isra.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
  "name": "pci_has_legacy_pm_support",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583723056,
      "name": "pci_has_legacy_pm_support",
      "external": false,
      "loc": "drivers/pci/pci-driver.c:645",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff",
        "drivers/pci/pci-driver.c:pci_pm_poweroff",
        "drivers/pci/pci-driver.c:pci_pm_thaw",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_pm_freeze_noirq",
        "drivers/pci/pci-driver.c:pci_pm_freeze",
        "drivers/pci/pci-driver.c:pci_pm_freeze",
        "drivers/pci/pci-driver.c:pci_pm_resume",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend",
        "drivers/pci/pci-driver.c:pci_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583723056,
      "name": "pci_has_legacy_pm_support.isra.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
  "name": "pci_has_legacy_pm_support",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583763984,
      "name": "pci_has_legacy_pm_support",
      "external": false,
      "loc": "drivers/pci/pci-driver.c:662",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff",
        "drivers/pci/pci-driver.c:pci_pm_poweroff",
        "drivers/pci/pci-driver.c:pci_pm_thaw",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_pm_freeze_noirq",
        "drivers/pci/pci-driver.c:pci_pm_freeze",
        "drivers/pci/pci-driver.c:pci_pm_freeze",
        "drivers/pci/pci-driver.c:pci_pm_resume",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend",
        "drivers/pci/pci-driver.c:pci_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583763984,
      "name": "pci_has_legacy_pm_support.isra.9",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_has_legacy_pm_support",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584023360,
      "name": "pci_has_legacy_pm_support",
      "external": false,
      "loc": "drivers/pci/pci-driver.c:660",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff",
        "drivers/pci/pci-driver.c:pci_pm_poweroff",
        "drivers/pci/pci-driver.c:pci_pm_thaw",
        "drivers/pci/pci-driver.c:pci_pm_thaw",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_pm_freeze_noirq",
        "drivers/pci/pci-driver.c:pci_pm_freeze",
        "drivers/pci/pci-driver.c:pci_pm_freeze",
        "drivers/pci/pci-driver.c:pci_pm_resume",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend",
        "drivers/pci/pci-driver.c:pci_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584023360,
      "name": "pci_has_legacy_pm_support.isra.9",
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
bool pci_has_legacy_pm_support(struct pci_dev * pci_dev)
```

```json
{
  "name": "pci_has_legacy_pm_support",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584217824,
      "name": "pci_has_legacy_pm_support",
      "external": false,
      "loc": "drivers/pci/pci-driver.c:660",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff",
        "drivers/pci/pci-driver.c:pci_pm_poweroff",
        "drivers/pci/pci-driver.c:pci_pm_thaw",
        "drivers/pci/pci-driver.c:pci_pm_thaw",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_pm_freeze_noirq",
        "drivers/pci/pci-driver.c:pci_pm_freeze",
        "drivers/pci/pci-driver.c:pci_pm_freeze",
        "drivers/pci/pci-driver.c:pci_pm_resume",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend",
        "drivers/pci/pci-driver.c:pci_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584217824,
      "name": "pci_has_legacy_pm_support",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
bool pci_has_legacy_pm_support(struct pci_dev * pci_dev)
```

```json
{
  "name": "pci_has_legacy_pm_support",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584307472,
      "name": "pci_has_legacy_pm_support",
      "external": false,
      "loc": "drivers/pci/pci-driver.c:660",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff",
        "drivers/pci/pci-driver.c:pci_pm_poweroff",
        "drivers/pci/pci-driver.c:pci_pm_thaw",
        "drivers/pci/pci-driver.c:pci_pm_thaw",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_pm_freeze_noirq",
        "drivers/pci/pci-driver.c:pci_pm_freeze",
        "drivers/pci/pci-driver.c:pci_pm_freeze",
        "drivers/pci/pci-driver.c:pci_pm_resume",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend",
        "drivers/pci/pci-driver.c:pci_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584307472,
      "name": "pci_has_legacy_pm_support",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
bool pci_has_legacy_pm_support(struct pci_dev * pci_dev)
```

```json
{
  "name": "pci_has_legacy_pm_support",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584502464,
      "name": "pci_has_legacy_pm_support",
      "external": false,
      "loc": "drivers/pci/pci-driver.c:661",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff",
        "drivers/pci/pci-driver.c:pci_pm_poweroff",
        "drivers/pci/pci-driver.c:pci_pm_thaw",
        "drivers/pci/pci-driver.c:pci_pm_thaw",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_pm_freeze_noirq",
        "drivers/pci/pci-driver.c:pci_pm_freeze",
        "drivers/pci/pci-driver.c:pci_pm_freeze",
        "drivers/pci/pci-driver.c:pci_pm_resume",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend",
        "drivers/pci/pci-driver.c:pci_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584502464,
      "name": "pci_has_legacy_pm_support",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
bool pci_has_legacy_pm_support(struct pci_dev * pci_dev)
```

```json
{
  "name": "pci_has_legacy_pm_support",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584638416,
      "name": "pci_has_legacy_pm_support",
      "external": false,
      "loc": "drivers/pci/pci-driver.c:661",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff",
        "drivers/pci/pci-driver.c:pci_pm_poweroff",
        "drivers/pci/pci-driver.c:pci_pm_thaw",
        "drivers/pci/pci-driver.c:pci_pm_thaw",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_pm_freeze_noirq",
        "drivers/pci/pci-driver.c:pci_pm_freeze",
        "drivers/pci/pci-driver.c:pci_pm_freeze",
        "drivers/pci/pci-driver.c:pci_pm_resume",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend",
        "drivers/pci/pci-driver.c:pci_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584638416,
      "name": "pci_has_legacy_pm_support",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
bool pci_has_legacy_pm_support(struct pci_dev * pci_dev)
```

```json
{
  "name": "pci_has_legacy_pm_support",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585322672,
      "name": "pci_has_legacy_pm_support",
      "external": false,
      "loc": "drivers/pci/pci-driver.c:634",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff",
        "drivers/pci/pci-driver.c:pci_pm_poweroff",
        "drivers/pci/pci-driver.c:pci_pm_thaw",
        "drivers/pci/pci-driver.c:pci_pm_thaw",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_pm_freeze_noirq",
        "drivers/pci/pci-driver.c:pci_pm_freeze_noirq",
        "drivers/pci/pci-driver.c:pci_pm_freeze",
        "drivers/pci/pci-driver.c:pci_pm_freeze",
        "drivers/pci/pci-driver.c:pci_pm_resume",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend",
        "drivers/pci/pci-driver.c:pci_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585322672,
      "name": "pci_has_legacy_pm_support",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool pci_has_legacy_pm_support(struct pci_dev * pci_dev)
```

```json
{
  "name": "pci_has_legacy_pm_support",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585476032,
      "name": "pci_has_legacy_pm_support",
      "external": false,
      "loc": "drivers/pci/pci-driver.c:639",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff",
        "drivers/pci/pci-driver.c:pci_pm_poweroff",
        "drivers/pci/pci-driver.c:pci_pm_thaw",
        "drivers/pci/pci-driver.c:pci_pm_thaw",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_pm_freeze_noirq",
        "drivers/pci/pci-driver.c:pci_pm_freeze_noirq",
        "drivers/pci/pci-driver.c:pci_pm_freeze",
        "drivers/pci/pci-driver.c:pci_pm_freeze",
        "drivers/pci/pci-driver.c:pci_pm_resume",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend",
        "drivers/pci/pci-driver.c:pci_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585476032,
      "name": "pci_has_legacy_pm_support",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool pci_has_legacy_pm_support(struct pci_dev * pci_dev)
```

```json
{
  "name": "pci_has_legacy_pm_support",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585355904,
      "name": "pci_has_legacy_pm_support",
      "external": false,
      "loc": "drivers/pci/pci-driver.c:639",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff",
        "drivers/pci/pci-driver.c:pci_pm_poweroff",
        "drivers/pci/pci-driver.c:pci_pm_thaw",
        "drivers/pci/pci-driver.c:pci_pm_thaw",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_pm_freeze_noirq",
        "drivers/pci/pci-driver.c:pci_pm_freeze_noirq",
        "drivers/pci/pci-driver.c:pci_pm_freeze",
        "drivers/pci/pci-driver.c:pci_pm_freeze",
        "drivers/pci/pci-driver.c:pci_pm_resume",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend",
        "drivers/pci/pci-driver.c:pci_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585355904,
      "name": "pci_has_legacy_pm_support",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
bool pci_has_legacy_pm_support(struct pci_dev * pci_dev)
```

```json
{
  "name": "pci_has_legacy_pm_support",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585815136,
      "name": "pci_has_legacy_pm_support",
      "external": false,
      "loc": "drivers/pci/pci-driver.c:652",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff",
        "drivers/pci/pci-driver.c:pci_pm_poweroff",
        "drivers/pci/pci-driver.c:pci_pm_thaw",
        "drivers/pci/pci-driver.c:pci_pm_thaw",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_pm_freeze_noirq",
        "drivers/pci/pci-driver.c:pci_pm_freeze_noirq",
        "drivers/pci/pci-driver.c:pci_pm_freeze",
        "drivers/pci/pci-driver.c:pci_pm_freeze",
        "drivers/pci/pci-driver.c:pci_pm_resume",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend",
        "drivers/pci/pci-driver.c:pci_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585815136,
      "name": "pci_has_legacy_pm_support",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
bool pci_has_legacy_pm_support(struct pci_dev * pci_dev)
```

```json
{
  "name": "pci_has_legacy_pm_support",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587005440,
      "name": "pci_has_legacy_pm_support",
      "external": false,
      "loc": "drivers/pci/pci-driver.c:683",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff",
        "drivers/pci/pci-driver.c:pci_pm_poweroff",
        "drivers/pci/pci-driver.c:pci_pm_thaw",
        "drivers/pci/pci-driver.c:pci_pm_thaw",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_pm_freeze_noirq",
        "drivers/pci/pci-driver.c:pci_pm_freeze_noirq",
        "drivers/pci/pci-driver.c:pci_pm_freeze",
        "drivers/pci/pci-driver.c:pci_pm_freeze",
        "drivers/pci/pci-driver.c:pci_pm_resume",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend",
        "drivers/pci/pci-driver.c:pci_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587005440,
      "name": "pci_has_legacy_pm_support",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
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
bool pci_has_legacy_pm_support(struct pci_dev * pci_dev)
```

```json
{
  "name": "pci_has_legacy_pm_support",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588174976,
      "name": "pci_has_legacy_pm_support",
      "external": false,
      "loc": "drivers/pci/pci-driver.c:683",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff",
        "drivers/pci/pci-driver.c:pci_pm_poweroff",
        "drivers/pci/pci-driver.c:pci_pm_thaw",
        "drivers/pci/pci-driver.c:pci_pm_thaw",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_pm_freeze_noirq",
        "drivers/pci/pci-driver.c:pci_pm_freeze_noirq",
        "drivers/pci/pci-driver.c:pci_pm_freeze",
        "drivers/pci/pci-driver.c:pci_pm_freeze",
        "drivers/pci/pci-driver.c:pci_pm_resume",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend",
        "drivers/pci/pci-driver.c:pci_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588174976,
      "name": "pci_has_legacy_pm_support",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
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
bool pci_has_legacy_pm_support(struct pci_dev * pci_dev)
```

```json
{
  "name": "pci_has_legacy_pm_support",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588451008,
      "name": "pci_has_legacy_pm_support",
      "external": false,
      "loc": "drivers/pci/pci-driver.c:684",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff",
        "drivers/pci/pci-driver.c:pci_pm_poweroff",
        "drivers/pci/pci-driver.c:pci_pm_thaw",
        "drivers/pci/pci-driver.c:pci_pm_thaw",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_pm_freeze_noirq",
        "drivers/pci/pci-driver.c:pci_pm_freeze_noirq",
        "drivers/pci/pci-driver.c:pci_pm_freeze",
        "drivers/pci/pci-driver.c:pci_pm_freeze",
        "drivers/pci/pci-driver.c:pci_pm_resume",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend",
        "drivers/pci/pci-driver.c:pci_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588451008,
      "name": "pci_has_legacy_pm_support",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
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
bool pci_has_legacy_pm_support(struct pci_dev * pci_dev)
```

```json
{
  "name": "pci_has_legacy_pm_support",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588747968,
      "name": "pci_has_legacy_pm_support",
      "external": false,
      "loc": "drivers/pci/pci-driver.c:696",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff",
        "drivers/pci/pci-driver.c:pci_pm_poweroff",
        "drivers/pci/pci-driver.c:pci_pm_thaw",
        "drivers/pci/pci-driver.c:pci_pm_thaw",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_pm_freeze_noirq",
        "drivers/pci/pci-driver.c:pci_pm_freeze_noirq",
        "drivers/pci/pci-driver.c:pci_pm_freeze",
        "drivers/pci/pci-driver.c:pci_pm_freeze",
        "drivers/pci/pci-driver.c:pci_pm_resume",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend",
        "drivers/pci/pci-driver.c:pci_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588747968,
      "name": "pci_has_legacy_pm_support",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
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
bool pci_has_legacy_pm_support(struct pci_dev * pci_dev)
```

```json
{
  "name": "pci_has_legacy_pm_support",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496884816,
      "name": "pci_has_legacy_pm_support",
      "external": false,
      "loc": "drivers/pci/pci-driver.c:661",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_resume",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend",
        "drivers/pci/pci-driver.c:pci_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496884816,
      "name": "pci_has_legacy_pm_support",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
bool pci_has_legacy_pm_support(struct pci_dev * pci_dev)
```

```json
{
  "name": "pci_has_legacy_pm_support",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230161676,
      "name": "pci_has_legacy_pm_support",
      "external": false,
      "loc": "drivers/pci/pci-driver.c:661",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff",
        "drivers/pci/pci-driver.c:pci_pm_poweroff",
        "drivers/pci/pci-driver.c:pci_pm_thaw",
        "drivers/pci/pci-driver.c:pci_pm_thaw",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_pm_freeze_noirq",
        "drivers/pci/pci-driver.c:pci_pm_freeze",
        "drivers/pci/pci-driver.c:pci_pm_freeze",
        "drivers/pci/pci-driver.c:pci_pm_resume",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend",
        "drivers/pci/pci-driver.c:pci_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230161676,
      "name": "pci_has_legacy_pm_support",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
bool pci_has_legacy_pm_support(struct pci_dev * pci_dev)
```

```json
{
  "name": "pci_has_legacy_pm_support",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290970048,
      "name": "pci_has_legacy_pm_support",
      "external": false,
      "loc": "drivers/pci/pci-driver.c:661",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_resume",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend",
        "drivers/pci/pci-driver.c:pci_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290970048,
      "name": "pci_has_legacy_pm_support",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
    }
  ]
}
```
</details>
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
bool pci_has_legacy_pm_support(struct pci_dev * pci_dev)
```

```json
{
  "name": "pci_has_legacy_pm_support",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584590576,
      "name": "pci_has_legacy_pm_support",
      "external": false,
      "loc": "drivers/pci/pci-driver.c:661",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff",
        "drivers/pci/pci-driver.c:pci_pm_poweroff",
        "drivers/pci/pci-driver.c:pci_pm_thaw",
        "drivers/pci/pci-driver.c:pci_pm_thaw",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_pm_freeze_noirq",
        "drivers/pci/pci-driver.c:pci_pm_freeze",
        "drivers/pci/pci-driver.c:pci_pm_freeze"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584590576,
      "name": "pci_has_legacy_pm_support",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
bool pci_has_legacy_pm_support(struct pci_dev * pci_dev)
```

```json
{
  "name": "pci_has_legacy_pm_support",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584518704,
      "name": "pci_has_legacy_pm_support",
      "external": false,
      "loc": "drivers/pci/pci-driver.c:661",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff",
        "drivers/pci/pci-driver.c:pci_pm_poweroff",
        "drivers/pci/pci-driver.c:pci_pm_thaw",
        "drivers/pci/pci-driver.c:pci_pm_thaw",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_pm_freeze_noirq",
        "drivers/pci/pci-driver.c:pci_pm_freeze",
        "drivers/pci/pci-driver.c:pci_pm_freeze",
        "drivers/pci/pci-driver.c:pci_pm_resume",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend",
        "drivers/pci/pci-driver.c:pci_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584518704,
      "name": "pci_has_legacy_pm_support",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
bool pci_has_legacy_pm_support(struct pci_dev * pci_dev)
```

```json
{
  "name": "pci_has_legacy_pm_support",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584588576,
      "name": "pci_has_legacy_pm_support",
      "external": false,
      "loc": "drivers/pci/pci-driver.c:661",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff",
        "drivers/pci/pci-driver.c:pci_pm_poweroff",
        "drivers/pci/pci-driver.c:pci_pm_thaw",
        "drivers/pci/pci-driver.c:pci_pm_thaw",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_pm_freeze_noirq",
        "drivers/pci/pci-driver.c:pci_pm_freeze",
        "drivers/pci/pci-driver.c:pci_pm_freeze",
        "drivers/pci/pci-driver.c:pci_pm_resume",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend",
        "drivers/pci/pci-driver.c:pci_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584588576,
      "name": "pci_has_legacy_pm_support",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
bool pci_has_legacy_pm_support(struct pci_dev * pci_dev)
```

```json
{
  "name": "pci_has_legacy_pm_support",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584696624,
      "name": "pci_has_legacy_pm_support",
      "external": false,
      "loc": "drivers/pci/pci-driver.c:661",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff",
        "drivers/pci/pci-driver.c:pci_pm_poweroff",
        "drivers/pci/pci-driver.c:pci_pm_thaw",
        "drivers/pci/pci-driver.c:pci_pm_thaw",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_pm_freeze_noirq",
        "drivers/pci/pci-driver.c:pci_pm_freeze",
        "drivers/pci/pci-driver.c:pci_pm_freeze",
        "drivers/pci/pci-driver.c:pci_pm_resume",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend",
        "drivers/pci/pci-driver.c:pci_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584696624,
      "name": "pci_has_legacy_pm_support",
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
bool pci_has_legacy_pm_support(struct pci_dev * pci_dev)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
bool pci_has_legacy_pm_support(struct pci_dev * pci_dev)
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
