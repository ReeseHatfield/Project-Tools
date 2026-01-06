# Exampst!

## A set of typst tools for creating exams and programming assignments 

# `init`

Global Document Initialization.

## Parameters:

- `body`:

## Basic usage:
```
```

# `wt`

## Parameters:

- `body`
- `dsp` (default: -10pt)



## Basic usage:
```
```

# `cmd_color`
render terminal / command output with syntax coloring
highlights user input

highlights errors

formats command-style output

## Parameters:

- `input` (string or array)
- `dsp` (default: 0pt)



## Basic usage:
```
```

# `uml`

UML-style class diagram table

renders structured UML block

## Parameters:

- `title`:
- `fields`:
- `methods`:



## Basic usage:
```
#uml(

)
```

# `lp`

lab problem header
renders standardized lab title


- `class`:
- `lpNum`:
- `title`:

## Basic usage:
```
```

# `purpose`

## Parameters
- `body`

## Basic Usage:
```
```

# `partA`

## Parameters:
- `body`

## Basic Usage:
```
```

# `partB`

## Parameters:
- `body`

## Basic Usage:
```
```

# `extra`

## Parameters:
- `title` (default: "Extra")
- `body`

## Basic Usage:
```
```

# `example`

## Parameters:
- `io`
- `body`

## Basic Usage:
```
```

# `labRubric`

## Parameters:
- `docOverride`: (default: "Documentation")
- `partAOverride`: (default: "Part A correct")
- `partBOverride`: (default: "Part B correct")

## Basic Usage:
```
```


# `rubric`

## Parameters:
- `baseRubric`
- `styleRubric`
- `bonusRubric`: (default: none)
- `wtRubric`: (default: none)
- `notes`: (sink)

## Basic Usage:
```
```

# `header`

## Parameters:
- N/A

## Basic Usage:
```
```

# `setup`

## Parameters:
- `title`:

## Basic Usage:
```
```

# `spacer`

## Parameters:
- N/A

## Basic Usage:
```
```

# `question`

## Parameters:
- `body`:
- `num_points`:

## Basic Usage:
```
```


# `multiple_choice`

## Parameters:
- `body`:
- `num_points`:
- `cols`: (default: 1)
- `answers`: (sink)

## Basic Usage:
```
```

# `matching`

## Parameters:
- `q_body`:
- `points`:
- `left_opts`:
- `right_opts`:

## Basic Usage:
```
```

# `multi_true_false`

## Parameters:
- `q_body`:
- `points`:
- `statements`: (sink)

## Basic Usage:
```
```

# `free_response`

## Parameters
- `q_body`:
- `points`:
- `num_lines`:

Basic Usage:
```
```


# `short_answer`

## Parameters
- `q_body`:
- `points`:
- `num_lines`:

Basic Usage:
```
```

# `code_block`

## Parameters
- `raw_code`:

## Basic Usage:
```
```
