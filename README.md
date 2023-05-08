# .gitignore templates

- just a personal configuration set for projects, free to use.
- collaboration or service request, contact [me](https://github.com/micah0912).
- a coffee donation will help to keep the package updated :)

\
<tab>

### Basic Usage
---

1. Rename to `.gitignore` and copy it to the directory you want to apply it.

	- `.gitignore` supports subdirectory override and stacking, so copy or combine by your use accordingly. 
	- i personally will separate file by purpose so that easier to manage.

<tab>

2. Alternatively, place it to designated place and add it through command. 
	- place it to `.git/info/exclude` is recommended.

```git
	# as global
	git config --global core.excludesfile %__path_to_file__%
	
	# as local
	git config core.excludesfile %__path_to_file__%
```

\
<tab>

### Template
---

**@** : Universal, can filter out most of log, temporary, or unnecessary files and folders.

<tab>

**the rest** : Specific build according the file name, use with `@` together is ideal. 