+++
date = '{{ .Date }}'
draft = true
title = '{{ replace .File.ContentBaseName "-" " " | title }}'
[params]
    subtitle = 'Lorem Ipsum'
+++
