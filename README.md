# mfc-hummelflug.de

[![Build Status](https://travis-ci.com/mfc-hummelflug/www.mfc-hummelflug.de.svg?branch=master)](https://travis-ci.com/github/mfc-hummelflug/www.mfc-hummelflug.de/builds)

Static site builder: <http://www.mfc-hummelflug.de>

Inhalte können auch via Siteleaf gepflegt werden:
<https://manage.siteleaf.com/sites/5da726ec9b787b7c87c0743e/pages>

## Lizenz für redaktionelle Inhalte und Bilder

Für jegliche redaktionelle Inhalte und alle Bilder innerhalb dieses
Repositories sind alle Rechte vorbehalten, Copyright Modellflugclub Berlin
e.V.

Anfragen zur möglichen Nutzung der redaktionellen Inhalte und Bilder sind and
an den [Vorstand des Modellflugclub Berlin e.V.](mailto:hummelflieger@arcor.de)
zu richten.

## Lizenz für Quelltexte / License for source code

Jeglicher Quellcode innerhalb dieses Repositories, also HTML, (S)CSS,
JavaScript und Liquid Templates stehen unter der GNU General Public License.

(**English**: All source code within this repository, i.e. HTML, (S)CSS,
JavaScript, and Liquid templates, is licensed under the GNU General Public
License.)

    Static site builder for the http://www.mfc-hummelflug.de website.
    Copyright (C) 2019 Martin Rehfeld

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <https://www.gnu.org/licenses/>.

## Entwicklungsumgebung

* Ruby 2.6.3 (`rbenv install 2.6.3`)
* ImageMagick 6.x (`brew install imagemagick@6`)
* Bundler/RubyGems (`bundle install`)

### Bei Problemen mit der RMagick Gem Installation

```
export PKG_CONFIG_PATH="/usr/local/opt/imagemagick@6/lib/pkgconfig"
bundle
```