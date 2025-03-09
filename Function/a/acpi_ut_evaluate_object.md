# Function: <code>acpi_ut_evaluate_object</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
acpi_status acpi_ut_evaluate_object(struct acpi_namespace_node * prefix_node, char * path, u32 expected_return_btypes, union acpi_operand_object * * return_desc)
```

```json
{
  "name": "acpi_ut_evaluate_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583726356,
      "name": "acpi_ut_evaluate_object",
      "external": true,
      "loc": "drivers/acpi/acpica/uteval.c:71",
      "file": "drivers/acpi/acpica/uteval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_prt_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_crs_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_prs_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_aei_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_method_data",
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_numeric_object",
        "drivers/acpi/acpica/uteval.c:acpi_ut_execute_STA",
        "drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_HID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_SUB",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_UID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583726356,
      "name": "acpi_ut_evaluate_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 411
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
acpi_status acpi_ut_evaluate_object(struct acpi_namespace_node * prefix_node, const char * path, u32 expected_return_btypes, union acpi_operand_object * * return_desc)
```

```json
{
  "name": "acpi_ut_evaluate_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584050836,
      "name": "acpi_ut_evaluate_object",
      "external": true,
      "loc": "drivers/acpi/acpica/uteval.c:71",
      "file": "drivers/acpi/acpica/uteval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_aei_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_prs_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_crs_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_prt_method_data",
        "drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods",
        "drivers/acpi/acpica/uteval.c:acpi_ut_execute_STA",
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_numeric_object",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_UID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_HID"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584050836,
      "name": "acpi_ut_evaluate_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 412
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
acpi_status acpi_ut_evaluate_object(struct acpi_namespace_node * prefix_node, const char * path, u32 expected_return_btypes, union acpi_operand_object * * return_desc)
```

```json
{
  "name": "acpi_ut_evaluate_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584193111,
      "name": "acpi_ut_evaluate_object",
      "external": true,
      "loc": "drivers/acpi/acpica/uteval.c:71",
      "file": "drivers/acpi/acpica/uteval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_aei_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_prs_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_crs_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_prt_method_data",
        "drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods",
        "drivers/acpi/acpica/uteval.c:acpi_ut_execute_STA",
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_numeric_object",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_UID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_HID"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584193111,
      "name": "acpi_ut_evaluate_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 412
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
acpi_status acpi_ut_evaluate_object(struct acpi_namespace_node * prefix_node, const char * path, u32 expected_return_btypes, union acpi_operand_object * * return_desc)
```

```json
{
  "name": "acpi_ut_evaluate_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584260743,
      "name": "acpi_ut_evaluate_object",
      "external": true,
      "loc": "drivers/acpi/acpica/uteval.c:71",
      "file": "drivers/acpi/acpica/uteval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_aei_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_prs_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_crs_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_prt_method_data",
        "drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods",
        "drivers/acpi/acpica/uteval.c:acpi_ut_execute_STA",
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_numeric_object",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_UID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_HID"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584260743,
      "name": "acpi_ut_evaluate_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 412
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
acpi_status acpi_ut_evaluate_object(struct acpi_namespace_node * prefix_node, const char * path, u32 expected_return_btypes, union acpi_operand_object * * return_desc)
```

```json
{
  "name": "acpi_ut_evaluate_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584625463,
      "name": "acpi_ut_evaluate_object",
      "external": true,
      "loc": "drivers/acpi/acpica/uteval.c:71",
      "file": "drivers/acpi/acpica/uteval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_aei_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_prs_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_crs_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_prt_method_data",
        "drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods",
        "drivers/acpi/acpica/uteval.c:acpi_ut_execute_STA",
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_numeric_object",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_UID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_HID"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584625463,
      "name": "acpi_ut_evaluate_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 594
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
acpi_status acpi_ut_evaluate_object(struct acpi_namespace_node * prefix_node, const char * path, u32 expected_return_btypes, union acpi_operand_object * * return_desc)
```

```json
{
  "name": "acpi_ut_evaluate_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584851156,
      "name": "acpi_ut_evaluate_object",
      "external": true,
      "loc": "drivers/acpi/acpica/uteval.c:37",
      "file": "drivers/acpi/acpica/uteval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_aei_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_prs_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_crs_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_prt_method_data",
        "drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods",
        "drivers/acpi/acpica/uteval.c:acpi_ut_execute_STA",
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_numeric_object",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_UID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_HID"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584851156,
      "name": "acpi_ut_evaluate_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 594
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
acpi_status acpi_ut_evaluate_object(struct acpi_namespace_node * prefix_node, const char * path, u32 expected_return_btypes, union acpi_operand_object * * return_desc)
```

```json
{
  "name": "acpi_ut_evaluate_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584954670,
      "name": "acpi_ut_evaluate_object",
      "external": true,
      "loc": "drivers/acpi/acpica/uteval.c:37",
      "file": "drivers/acpi/acpica/uteval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_aei_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_prs_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_crs_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_prt_method_data",
        "drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods",
        "drivers/acpi/acpica/uteval.c:acpi_ut_execute_STA",
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_numeric_object",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_UID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_HID"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584954670,
      "name": "acpi_ut_evaluate_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 594
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
acpi_status acpi_ut_evaluate_object(struct acpi_namespace_node * prefix_node, const char * path, u32 expected_return_btypes, union acpi_operand_object * * return_desc)
```

```json
{
  "name": "acpi_ut_evaluate_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585157805,
      "name": "acpi_ut_evaluate_object",
      "external": true,
      "loc": "drivers/acpi/acpica/uteval.c:37",
      "file": "drivers/acpi/acpica/uteval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_aei_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_prs_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_crs_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_prt_method_data",
        "drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods",
        "drivers/acpi/acpica/uteval.c:acpi_ut_execute_STA",
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_numeric_object",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_UID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_HID"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585157805,
      "name": "acpi_ut_evaluate_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 592
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
acpi_status acpi_ut_evaluate_object(struct acpi_namespace_node * prefix_node, const char * path, u32 expected_return_btypes, union acpi_operand_object * * return_desc)
```

```json
{
  "name": "acpi_ut_evaluate_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585294167,
      "name": "acpi_ut_evaluate_object",
      "external": true,
      "loc": "drivers/acpi/acpica/uteval.c:37",
      "file": "drivers/acpi/acpica/uteval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_aei_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_prs_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_crs_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_prt_method_data",
        "drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods",
        "drivers/acpi/acpica/uteval.c:acpi_ut_execute_STA",
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_numeric_object",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_UID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_HID"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585294167,
      "name": "acpi_ut_evaluate_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 592
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
acpi_status acpi_ut_evaluate_object(struct acpi_namespace_node * prefix_node, const char * path, u32 expected_return_btypes, union acpi_operand_object * * return_desc)
```

```json
{
  "name": "acpi_ut_evaluate_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586000647,
      "name": "acpi_ut_evaluate_object",
      "external": true,
      "loc": "drivers/acpi/acpica/uteval.c:37",
      "file": "drivers/acpi/acpica/uteval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_aei_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_prs_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_crs_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_prt_method_data",
        "drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods",
        "drivers/acpi/acpica/uteval.c:acpi_ut_execute_STA",
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_numeric_object",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_UID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_HID"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586000647,
      "name": "acpi_ut_evaluate_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 592
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
acpi_status acpi_ut_evaluate_object(struct acpi_namespace_node * prefix_node, const char * path, u32 expected_return_btypes, union acpi_operand_object * * return_desc)
```

```json
{
  "name": "acpi_ut_evaluate_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586123493,
      "name": "acpi_ut_evaluate_object",
      "external": true,
      "loc": "drivers/acpi/acpica/uteval.c:37",
      "file": "drivers/acpi/acpica/uteval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_aei_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_prs_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_crs_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_prt_method_data",
        "drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods",
        "drivers/acpi/acpica/uteval.c:acpi_ut_execute_STA",
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_numeric_object",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_UID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_HID"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586123493,
      "name": "acpi_ut_evaluate_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 592
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
acpi_status acpi_ut_evaluate_object(struct acpi_namespace_node * prefix_node, const char * path, u32 expected_return_btypes, union acpi_operand_object * * return_desc)
```

```json
{
  "name": "acpi_ut_evaluate_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586000269,
      "name": "acpi_ut_evaluate_object",
      "external": true,
      "loc": "drivers/acpi/acpica/uteval.c:37",
      "file": "drivers/acpi/acpica/uteval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_aei_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_prs_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_crs_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_prt_method_data",
        "drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods",
        "drivers/acpi/acpica/uteval.c:acpi_ut_execute_STA",
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_numeric_object",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_UID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_HID"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586000269,
      "name": "acpi_ut_evaluate_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 592
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
acpi_status acpi_ut_evaluate_object(struct acpi_namespace_node * prefix_node, const char * path, u32 expected_return_btypes, union acpi_operand_object * * return_desc)
```

```json
{
  "name": "acpi_ut_evaluate_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586489809,
      "name": "acpi_ut_evaluate_object",
      "external": true,
      "loc": "drivers/acpi/acpica/uteval.c:37",
      "file": "drivers/acpi/acpica/uteval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_aei_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_prs_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_crs_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_prt_method_data",
        "drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods",
        "drivers/acpi/acpica/uteval.c:acpi_ut_execute_STA",
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_numeric_object",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_UID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_HID"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586489809,
      "name": "acpi_ut_evaluate_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 592
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
acpi_status acpi_ut_evaluate_object(struct acpi_namespace_node * prefix_node, const char * path, u32 expected_return_btypes, union acpi_operand_object * * return_desc)
```

```json
{
  "name": "acpi_ut_evaluate_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587744378,
      "name": "acpi_ut_evaluate_object",
      "external": true,
      "loc": "drivers/acpi/acpica/uteval.c:37",
      "file": "drivers/acpi/acpica/uteval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_aei_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_prs_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_crs_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_prt_method_data",
        "drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods",
        "drivers/acpi/acpica/uteval.c:acpi_ut_execute_STA",
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_numeric_object",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_UID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_HID"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587744378,
      "name": "acpi_ut_evaluate_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 623
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
acpi_status acpi_ut_evaluate_object(struct acpi_namespace_node * prefix_node, const char * path, u32 expected_return_btypes, union acpi_operand_object * * return_desc)
```

```json
{
  "name": "acpi_ut_evaluate_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589068960,
      "name": "acpi_ut_evaluate_object",
      "external": true,
      "loc": "drivers/acpi/acpica/uteval.c:37",
      "file": "drivers/acpi/acpica/uteval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_aei_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_prs_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_crs_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_prt_method_data",
        "drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods",
        "drivers/acpi/acpica/uteval.c:acpi_ut_execute_STA",
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_numeric_object",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_UID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_HID"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589068960,
      "name": "acpi_ut_evaluate_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 638
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
acpi_status acpi_ut_evaluate_object(struct acpi_namespace_node * prefix_node, const char * path, u32 expected_return_btypes, union acpi_operand_object * * return_desc)
```

```json
{
  "name": "acpi_ut_evaluate_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589360288,
      "name": "acpi_ut_evaluate_object",
      "external": true,
      "loc": "drivers/acpi/acpica/uteval.c:37",
      "file": "drivers/acpi/acpica/uteval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_aei_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_prs_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_crs_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_prt_method_data",
        "drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods",
        "drivers/acpi/acpica/uteval.c:acpi_ut_execute_STA",
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_numeric_object",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_UID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_HID"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589360288,
      "name": "acpi_ut_evaluate_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 638
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
acpi_status acpi_ut_evaluate_object(struct acpi_namespace_node * prefix_node, const char * path, u32 expected_return_btypes, union acpi_operand_object * * return_desc)
```

```json
{
  "name": "acpi_ut_evaluate_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589667136,
      "name": "acpi_ut_evaluate_object",
      "external": true,
      "loc": "drivers/acpi/acpica/uteval.c:37",
      "file": "drivers/acpi/acpica/uteval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_aei_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_prs_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_crs_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_prt_method_data",
        "drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods",
        "drivers/acpi/acpica/uteval.c:acpi_ut_execute_STA",
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_numeric_object",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_UID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_HID"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589667136,
      "name": "acpi_ut_evaluate_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 689
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
acpi_status acpi_ut_evaluate_object(struct acpi_namespace_node * prefix_node, const char * path, u32 expected_return_btypes, union acpi_operand_object * * return_desc)
```

```json
{
  "name": "acpi_ut_evaluate_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497609840,
      "name": "acpi_ut_evaluate_object",
      "external": true,
      "loc": "drivers/acpi/acpica/uteval.c:37",
      "file": "drivers/acpi/acpica/uteval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_aei_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_prs_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_crs_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_prt_method_data",
        "drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods",
        "drivers/acpi/acpica/uteval.c:acpi_ut_execute_STA",
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_numeric_object",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_UID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_HID"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497609840,
      "name": "acpi_ut_evaluate_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 436
    }
  ]
}
```
</details>
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
acpi_status acpi_ut_evaluate_object(struct acpi_namespace_node * prefix_node, const char * path, u32 expected_return_btypes, union acpi_operand_object * * return_desc)
```

```json
{
  "name": "acpi_ut_evaluate_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585132473,
      "name": "acpi_ut_evaluate_object",
      "external": true,
      "loc": "drivers/acpi/acpica/uteval.c:37",
      "file": "drivers/acpi/acpica/uteval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_aei_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_prs_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_crs_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_prt_method_data",
        "drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods",
        "drivers/acpi/acpica/uteval.c:acpi_ut_execute_STA",
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_numeric_object",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_UID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_HID"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585132473,
      "name": "acpi_ut_evaluate_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 409
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
acpi_status acpi_ut_evaluate_object(struct acpi_namespace_node * prefix_node, const char * path, u32 expected_return_btypes, union acpi_operand_object * * return_desc)
```

```json
{
  "name": "acpi_ut_evaluate_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585047728,
      "name": "acpi_ut_evaluate_object",
      "external": true,
      "loc": "drivers/acpi/acpica/uteval.c:37",
      "file": "drivers/acpi/acpica/uteval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_aei_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_prs_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_crs_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_prt_method_data",
        "drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods",
        "drivers/acpi/acpica/uteval.c:acpi_ut_execute_STA",
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_numeric_object",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_UID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_HID"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585047728,
      "name": "acpi_ut_evaluate_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 404
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
acpi_status acpi_ut_evaluate_object(struct acpi_namespace_node * prefix_node, const char * path, u32 expected_return_btypes, union acpi_operand_object * * return_desc)
```

```json
{
  "name": "acpi_ut_evaluate_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585245751,
      "name": "acpi_ut_evaluate_object",
      "external": true,
      "loc": "drivers/acpi/acpica/uteval.c:37",
      "file": "drivers/acpi/acpica/uteval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_aei_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_prs_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_crs_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_prt_method_data",
        "drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods",
        "drivers/acpi/acpica/uteval.c:acpi_ut_execute_STA",
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_numeric_object",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_UID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_HID"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585245751,
      "name": "acpi_ut_evaluate_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 592
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
acpi_status acpi_ut_evaluate_object(struct acpi_namespace_node * prefix_node, const char * path, u32 expected_return_btypes, union acpi_operand_object * * return_desc)
```

```json
{
  "name": "acpi_ut_evaluate_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585351911,
      "name": "acpi_ut_evaluate_object",
      "external": true,
      "loc": "drivers/acpi/acpica/uteval.c:37",
      "file": "drivers/acpi/acpica/uteval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_aei_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_prs_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_crs_method_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_prt_method_data",
        "drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods",
        "drivers/acpi/acpica/uteval.c:acpi_ut_execute_STA",
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_numeric_object",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_CID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_UID",
        "drivers/acpi/acpica/utids.c:acpi_ut_execute_HID"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585351911,
      "name": "acpi_ut_evaluate_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 592
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
<b>Param type changed. </b>
<code>char * path</code> ➡️ <code>const char * path</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
acpi_status acpi_ut_evaluate_object(struct acpi_namespace_node * prefix_node, const char * path, u32 expected_return_btypes, union acpi_operand_object * * return_desc)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
acpi_status acpi_ut_evaluate_object(struct acpi_namespace_node * prefix_node, const char * path, u32 expected_return_btypes, union acpi_operand_object * * return_desc)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
acpi_status acpi_ut_evaluate_object(struct acpi_namespace_node * prefix_node, const char * path, u32 expected_return_btypes, union acpi_operand_object * * return_desc)
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
