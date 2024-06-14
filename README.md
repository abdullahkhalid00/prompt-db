# Personal Prompt Database

This repository holds prompts that I use on a daily basis both professionally and personally. Prompts are stored in a `.txt` file extension (for now) until I find a better more efficient file system (i.e. `.jinja2`, `.md` etc.)

## Repository Structure

```txt
.
└── root/
    ├── .gitignore
    ├── README.md
    ├── company/
    │   ├── task/
    │   │   ├── prompt.txt
    │   │   └── ...
    │   └── ...
    └── ...
```

### Common Structure of Prompts

Each prompt follows a common structure as given below.

```txt
system: {prompt_body}
user: {input_vars}
```

## Contribution

Feel free to open a pull request where you think a prompt can be improved.
