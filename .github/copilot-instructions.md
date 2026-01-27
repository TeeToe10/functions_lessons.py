# Copilot Instructions for functions_lessons.py

## Project Overview
This is a **Python learning curriculum** focused on mastering Python functions. The repository contains 8 progressive lesson files that build from basic function definitions through advanced parameter handling.

## Lesson Progression & Structure

### Files 1-4: Core Function Concepts
- **1_.py**: Basic function definitions, parameters, invocation, and return statements
- **2_functions.py**: Practice exercises (3 problems) - writing simple functions with parameters
- **3_return.py**: Return value patterns (3 exercises) - return statements and result passing
- **4_dynamicFunctions.py**: Dynamic list operations (3 exercises) - functions iterating over lists with conditionals

### Files 5-8: Advanced Patterns
- **5_function_example.py**: Currently empty (placeholder for integrated examples)
- **6_function_interaction.py**: Function composition (3 exercises) - passing results between functions, using `random` module
- **7_indefinite_arguments_args.py**: Variadic positional args `*args` (3 exercises)
- **8_indefinite_arguments_kwargs.py**: Variadic keyword args `**kwargs` (3 exercises)

## Key Patterns & Conventions

### Exercise Format
Each file contains 3 practice problems in this format:
```python
# Practice Title
# Problem description with context
# Implementation requirements as comments

def solution_function():
    # Complete the function
    pass
```

### Code Patterns to Follow
1. **Simple print functions**: No return statement, output via `print()`
2. **Return-based functions**: Use `return` to pass results between functions
3. **List iteration**: Use `for num in list:` pattern with conditionals
4. **Variadic args**: `*args` captures multiple positional arguments as tuple; `**kwargs` for keyword arguments
5. **String operations**: Use `str.capitalize()`, slicing `[::-1]`, `.upper()` as appropriate

### Common Requirements
- Parameter naming: Match suggested names (e.g., `numbers` for lists, `name` for strings)
- No external dependencies except `random` (used in file 6)
- Keep implementations concise - one-liner returns acceptable when readable
- Functions return values rather than print (when not explicitly specified as print)

## Testing & Execution
- Scripts are standalone (no unit test framework)
- Each file can run independently: `python {filename}.py`
- Partial implementations & commented code are common (learning scaffolds)

## Important Notes for AI Agents
- These are **learning exercises**, not production code - verbose comments and example code are intentional
- `notes/` directory may contain supplementary learning materials
- When adding/fixing code, preserve problem statement comments above functions
- Match the file's existing style: minimal complexity, readable over clever
