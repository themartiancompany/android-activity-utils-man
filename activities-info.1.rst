..
   SPDX-License-Identifier: AGPL-3.0-or-later

   -------------------------------------------------------
   Copyright © 2024, 2025, 2026
               Pellegrino Prevete

   All rights reserved
   -------------------------------------------------------

   This program is free software: you can redistribute it
   and/or modify it under the terms of the
   GNU Affero General Public License as published by
   the Free Software Foundation, either version 3 of the
   License, or (at your option) any later version.

   This program is distributed in the hope that it will
   be useful, but WITHOUT ANY WARRANTY; without even the
   implied warranty of MERCHANTABILITY or FITNESS FOR A
   PARTICULAR PURPOSE.
   See the GNU Affero General Public License
   for more details.

   You should have received a copy of the
   GNU Affero General Public License
   along with this program.
   If not, see <https://www.gnu.org/licenses/>.


========================
activities-info
========================

--------------------------------------------------------------
Returns information about activities
--------------------------------------------------------------
:Version: activities-info |version|
:Manual section: 1


Synopsis
========

activities-info *[options]*


Description
===========

Returns information about activities.


Options
=======

-m mode

  Method to use to retrieve
  activities information.
  It can be 'root' for getting
  it from 'dumpsys'.


-o output-format

  Activities information output
  format. It can be:

  - plain

    It returns 'dumpsys'
    output as it is, so also,
    complete.

  - json

    It returns the information
    in JSON format.


-h

  Display help.

-c

  Enable color output.


-v

  Enable verbose output.


Bugs
====

https://github.com/themartiancompany/android-activity-utils/-/issues


Copyright
=========

Copyright Pellegrino Prevete. AGPL-3.0.

See also
========

* windows-info
* alt-tab
* windows-list
* activity-focused
* bbrightnessctl
* displayctl
* powerctl
* sissystemctl
* android-display-dim

.. include:: variables.rst
