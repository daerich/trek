# ISC License
#
# Copyright (c) 2022 Erich Ericson
#
# Permission to use, copy, modify, and/or distribute this software for any
# purpose with or without fee is hereby granted, provided that the above
# copyright notice and this permission notice appear in all copies.
#
# THE SOFTWARE IS PROVIDED "AS IS" AND THE AUTHOR DISCLAIMS ALL WARRANTIES WITH
# REGARD TO THIS SOFTWARE INCLUDING ALL IMPLIED WARRANTIES OF MERCHANTABILITY
# AND FITNESS. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR ANY SPECIAL, DIRECT,
# INDIRECT, OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES WHATSOEVER RESULTING FROM
# LOSS OF USE, DATA OR PROFITS, WHETHER IN AN ACTION OF CONTRACT, NEGLIGENCE OR
# OTHER TORTIOUS ACTION, ARISING OUT OF OR IN CONNECTION WITH THE USE OR
# PERFORMANCE OF THIS SOFTWARE.

AC_PREREQ([2.69])
AC_INIT([trek], [1.0], [daerich@users.github.com])

AC_CONFIG_SRCDIR([phaser.c])
# Checks for programs.
AC_PROG_CC

# Checks for libraries.
AC_CHECK_LIB([m],[atan2])
# Checks for header files.
AC_CHECK_HEADERS([stdlib.h stdio.h string.h setjmp.h err.h math.h unistd.h],[],[AC_MSG_ERROR([Couldnt find header please verify output and try again])])

# Checks for typedefs, structures, and compiler characteristics.
AC_TYPE_SIZE_T

# Checks for library functions.
AC_CHECK_FUNCS([pow sqrt atan2 cos log exp])

AC_CONFIG_FILES([Makefile])
AC_OUTPUT
