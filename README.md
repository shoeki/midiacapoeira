Código fonte de capoeira.li
===

Este repositório contém o código do aplicativo Web2Py gerado em
<https://capoeira.li>.

Este repositório não contém todo o código de Web2Py. O conteúdo deste
repositório deve ser copiado para o diretório **applications** do Web2Py.

Receita de bolo:

```
git clone https://github.com/web2py/web2py.git
cd web2py/applications
git clone https://github.com/hiatobr/midiacapoeira.git
cd ..
ln -s applications/midiacapoeira/routes.web2py.py routes.py
python web2py.py
```

Seguindo esta receita e acessando <http://localhost:8000> deveria
aparecer a mesma coisa que tem em <https://capoeira.li>.

Se não der certo, leia a documentação do [Web2Py](http://web2py.com),
entre em contato com capoeira@riseup.net, ou use o sistema do [GitHub](https://github.com)
para enviar problemas/sugestões/etc.

[Web2Py](http://web2py.com) tem licença específica e o repositório
encontra-se em <https://github.com/web2py/web2py>.

Licença para o código fonte de <https://capoeira.li>:

> Copywrong (W) 2014 Mídia Capoeira

> This program is free software: you can redistribute it and/or modify
> it under the terms of the GNU General Public License as published by
> the Free Software Foundation, version 3 of the License.

> This program is distributed in the hope that it will be useful,
> but WITHOUT ANY WARRANTY; without even the implied warranty of
> MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
> GNU General Public License for more details.

> You should have received a copy of the GNU General Public License
> along with this program. If not, see (http://www.gnu.org/licenses/).

