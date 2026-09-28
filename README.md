# PLP Python Week 5: Password Generator & Custom Modules

This repository contains the solutions for the Week 5 Python assignment focusing on utilizing built-in modules (`random`, `string`, `math`), defining custom modules, and understanding module execution entry points (`if __name__ == "__main__":`).

## Files Included

* `password_generator.py` - Uses `random` and `string` modules to construct random passwords of configurable lengths.
* `helpers.py` - A custom module defining utility functions `tables_needed()` (using `math.ceil()`) and `welcome()`.
* `main.py` - Main execution script that imports `helpers.py` and calls its functions.

## Reflection Question

The hardest concept to grasp was the `if __name__ == "__main__":` block in `helpers.py`. Understanding that `__name__` evaluates to `"__main__"` when executed directly, but takes the module's name (`"helpers"`) when imported into `main.py`, helped clarify how Python handles script execution vs. module imports.
