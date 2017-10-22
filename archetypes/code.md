+++
repo = "{{ index (split .TranslationBaseName "/") 0 }}"
title = "{{ .TranslationBaseName }}"
date = {{ .Date }}
draft = true
+++

[View the code on GitHub](https://github.com/impractical/{{ index (split .TranslationBaseName "/") 0 }})
