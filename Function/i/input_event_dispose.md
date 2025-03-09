# Function: <code>input_event_dispose</code>

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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
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
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void input_event_dispose(struct input_dev * dev, int disposition, unsigned int type, unsigned int code, int value)
```

```json
{
  "name": "input_event_dispose",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592116534,
      "name": "input_event_dispose",
      "external": false,
      "loc": "drivers/input/input.c:348",
      "file": "drivers/input/input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/input/input.c:input_set_keycode"
      ],
      "caller_func": [
        "drivers/input/input.c:input_repeat_key",
        "drivers/input/input.c:__input_unregister_device",
        "drivers/input/input.c:input_dev_freeze",
        "drivers/input/input.c:input_dev_suspend",
        "drivers/input/input.c:input_reset_device",
        "drivers/input/input.c:inhibited_store",
        "drivers/input/input.c:input_set_keycode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592110048,
      "name": "input_event_dispose",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 371
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
void input_event_dispose(struct input_dev * dev, int disposition, unsigned int type, unsigned int code, int value)
```

```json
{
  "name": "input_event_dispose",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592539718,
      "name": "input_event_dispose",
      "external": false,
      "loc": "drivers/input/input.c:351",
      "file": "drivers/input/input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/input/input.c:input_set_keycode"
      ],
      "caller_func": [
        "drivers/input/input.c:input_repeat_key",
        "drivers/input/input.c:__input_unregister_device",
        "drivers/input/input.c:input_dev_freeze",
        "drivers/input/input.c:input_dev_suspend",
        "drivers/input/input.c:input_reset_device",
        "drivers/input/input.c:inhibited_store",
        "drivers/input/input.c:input_set_keycode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592533792,
      "name": "input_event_dispose",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 371
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
void input_event_dispose(struct input_dev * dev, int disposition, unsigned int type, unsigned int code, int value)
```

```json
{
  "name": "input_event_dispose",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593284166,
      "name": "input_event_dispose",
      "external": false,
      "loc": "drivers/input/input.c:351",
      "file": "drivers/input/input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/input/input.c:input_set_keycode"
      ],
      "caller_func": [
        "drivers/input/input.c:input_repeat_key",
        "drivers/input/input.c:__input_unregister_device",
        "drivers/input/input.c:input_dev_freeze",
        "drivers/input/input.c:input_dev_suspend",
        "drivers/input/input.c:input_reset_device",
        "drivers/input/input.c:inhibited_store",
        "drivers/input/input.c:input_set_keycode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593278272,
      "name": "input_event_dispose",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 371
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
void input_event_dispose(struct input_dev * dev, int disposition, unsigned int type, unsigned int code, int value)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
