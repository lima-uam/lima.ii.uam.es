+++
date = '{{ .Date }}'
draft = true
[params]
    title = '{{ replace .File.ContentBaseName "-" " " | title }}'
    subtitle = 'Lorem Ipsum'
+++
