Licenças de softwares E5R Development Team
==========================================

Este repositório contém as notas legais e licenças utilizadas pelos
softwares desenvolvidos pelo Time de Desenvolvimento E5R.

As licenças de softwares desenvolvidos pelo Time de Desenvolvimento E5R
são aplicadas com a inclusão de avisos de direitos autorais nos cabeçalhos
dos códigos fontes distribuídos, os mesmos referenciam mais informações
com links para este repositório, que tem sua distribuição global.

As licenças são organizadas em 2 formatos:

1. **Notas legais**: São pequenos textos com as notas legais de direitos autorais
   de cada projeto, e estão disponíveis em *notices/nome_projeto.rst*;

2. **Licenças**: São textos completos, contendo a íntegra de cada licença utilizada.
   São genéricas para qualquer projeto que as use, e estão disponíveis em *license/nome_licenca.rst*.

## As licenças em um projeto E5R

Todo projeto de software do time E5R deve conter:

1. Um dos arquivos (`LICENSE`, `LICENSE.txt` ou `LICENSE.md`) na raiz do projeto contendo a
   íntegra do conteúdo da licença aplicado ao mesmo;
2. Cada arquivo de código fonte do projeto deve ter no cabeçalho:
```
Copyright (c) E5R Development Team. All rights reserved.
This file is a part of {PROJECT_NAME}.
Licensed under the {LICENSE_NAME}: More license information in {LICENSE_FILE}.
```
3. Cada arquivo de código fonte do projeto é distribuído pela rede de forma
   independente (como scripts de instalação por exemplo), deve ter no cabeçalho:
```
Copyright (c) E5R Development Team. All rights reserved.
This file is a part of {PROJECT_NAME}.
Licensed under the {LICENSE_NAME}: https://github.com/e5r/licenses/blob/master/license/{LICENSE}.txt
```
Exemplo em [C](http://en.cppreference.com/w/c) para projeto [NDE](https://github.com/e5r/nde) que usa a licença Apache 2.0:
```c
// Copyright (c) E5R Development Team. All rights reserved.
// This file is a part of NDE.
// Licensed under the Apache version 2.0: https://github.com/e5r/licenses/blob/master/license/APACHE-2.0.txt
```