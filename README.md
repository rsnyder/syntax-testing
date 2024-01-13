# ezsite

## Markdown augmentation

### Inline code

`.class #id :style-string key=value`

`ez-image key=value arg1 "phrase 1"`

`ez-image key=value arg1 "phrase 1" | list-item 1 | list-item 2`

### Code blocks

```
.class #id :style-string key=value
```

```
ez-image key=value arg1 "phrase 1"
list-item 1
list-item 2
```

```
ez-image key=value arg1 "phrase 1"
```

```
ez-image key=value arg1 "phrase 1" | list-item 1 | list-item 2
```

```bash
cat some_file.txt | wc -l
```

```ezsite
ez-image key=value arg1 "phrase 1" | list-item 1 | list-item 2
```

# Empty heading test

##
`.mcol`

##

`.mcol`

##
```
.class #id :style-string key=value
```

##

```
.class #id :style-string key=value
```
