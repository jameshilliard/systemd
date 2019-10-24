# SPDX-License-Identifier: LGPL-2.1+

if find_program('xgettext', required : false).found()
        i18n = import('i18n')
        i18n.gettext(meson.project_name(),
                     preset : 'glib',
                     data_dirs : '.')
else
        warning('Can not do gettext because xgettext is not installed.')
endif
