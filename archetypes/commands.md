---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: true
---

# {{ replace .Name  "-" " " | title }}

#### Command Example/s:

```fix
/<command_here>
```

#### Arguments:

{{ range arguments }}
**`{{ .Title }}`** - {{ .params.Description }}
{{ end }}

#### Description:

<command_details>
